![things](/img/snorts2.png?raw=true "text")

### Snort / Suricata Searches

Update: I have added 35 searches for a bunch of Suricata alerts from Travis Green's excellent hunting rules at https://github.com/travisbgreen/hunting-rules/blob/master/hunting.rules

I've added a test to these five for a non-private Internet destination address in order to filter out noise from local web services and applications that may use non-standard ports. These searches look like this:

| Name                                                        | Search in KQL                                                                                                                                                                                         |
|-------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Suricata FTP Traffic on Unusual Port, Internet Destination  | suricata.eve.alert.signature_id:2610005 and (event.module:suricata and event.kind:alert) and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16 |
| Suricata HTTP On Unusual Port, Internet Destination         | suricata.eve.alert.signature_id:2610001 and (event.module:suricata and event.kind:alert) and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16 |
| Suricata IMAP Traffic on Unusual Port, internet Destination | suricata.eve.alert.signature_id:2610009 and (event.module:suricata and event.kind:alert) and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16 |
| Suricata SSH Traffic Not on Port 22, Internet Destination   | suricata.eve.alert.signature_id:2610007 and (event.module:suricata and event.kind:alert) and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16 |
| Suricata TLS on Unusual Port, Internet Destination          | suricata.eve.alert.signature_id:2610003 and (event.module:suricata and event.kind:alert) and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16 |

So we need a way to sift interesting Suricata / Snort detects at scale without using wildcards - and something more useful than returning all alerts with a severity of one like this;

event.module:suricata and event.kind:alert and event.severity:1

This search looks for a set of potentially interesting and relevant alerts in the emerging threats and the ptreseach attack detection rules meting these criteria:

1. Rules that reference CVES from the year 2019 (my thinking is older CVEs are probably patched or blocked if security is taken seriously enough to run IDS sensors at scale) and
2. Appear more or less enterprise relevant; IoT device attacks and less "enterprisey" uncommon software products are not included (yet.) My reasoning: IDK many small businesses or home users running Suricata.

TODO: Make one rule per SID so that it is easier to tune these by selectively enabling and disabling them. This is the search in KQL:

(event.module:suricata and event.kind:alert) and suricata.eve.alert.signature_id: (10004953 or 10004555 or 10004699 or 10004529 or 10004779 or 10004927 or 10004781 or 10004698 or 10004867 or 10004864 or 10005399 or 10004861 or 10005396 or 10004865 or 10005400 or 10004862 or 10005397 or 10004863 or 10005398 or 2027369 or 2027451 or 2027450 or 2027721 or 2026860 or 2027442 or 2027959 or 2027696 or 2028928 or 2027315 or 2027333 or 2028895 or 2027706 or 2027712 or 2027711 or 2027368 or 2027349 or 2027350 or 2027346 or 2027345)

These are the Suricata rules matched by this search.
ATT&CK Categories: I am going to place all of these in the Initial Access / T1190: Exploit Public Facing Application category.

| SID      | Message                                                                                        |
|----------|------------------------------------------------------------------------------------------------|
| 10004953 | ATTACK [PTsecurity] Apache Tomcat RCE on Windows (CVE-2019-0232)                               |
| 10004555 | ATTACK [PTsecurity] Arbitrary PHP RCE in Drupal 8 < 8.5.11,8.6.10 (CVE-2019-6340)              |
| 10004699 | ATTACK [PTsecurity] Confluence <6.14.2,6.13.3,6.12.3 Unauthorized RCE (CVE-2019-3396)          |
| 10004529 | ATTACK [PTsecurity] Jenkins sandbox bypassing RCE (CVE-2019-1003000/1/2)                       |
| 10004779 | ATTACK [PTsecurity] Oracle Weblogic _async deserialization RCE Attempt (CVE-2019-2725)         |
| 10004927 | ATTACK [PTsecurity] Oracle Weblogic _async deserialization RCE Attempt (CVE-2019-2725)         |
| 10004781 | ATTACK [PTsecurity] Oracle Weblogic file upload RCE (CVE-2019-2618)                            |
| 10004698 | ATTACK [PTsecurity] Possible Apache Axis RCE via SSRF (CVE-2019-0227)                          |
| 10004867 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708                                |
| 10004864 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (MCS Channel Join Requests)    |
| 10005399 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (MCS Channel Join Requests)    |
| 10004861 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (pkt #1)                       |
| 10005396 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (pkt #1)                       |
| 10004865 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (pkt #12)                      |
| 10005400 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (pkt #12)                      |
| 10004862 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (pkt #2)                       |
| 10005397 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (pkt #2)                       |
| 10004863 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (pkt #3)                       |
| 10005398 | ATTACK [PTsecurity] Possible Bluekeep RDP exploit CVE-2019-0708 (pkt #3)                       |
| 2027369  | ET EXPLOIT [NCC GROUP] Possible Bluekeep Inbound RDP Exploitation Attempt (CVE-2019-0708)      |
| 2027451  | ET EXPLOIT Attempted Remote Command Injection Inbound (CVE-2019-3929)                          |
| 2027450  | ET EXPLOIT Attempted Remote Command Injection Outbound (CVE-2019-3929)                         |
| 2027721  | ET EXPLOIT IE Scripting Engine Memory Corruption Vulnerability (CVE-2019-0752)                 |
| 2026860  | ET EXPLOIT Possible Cisco RV320 RCE Attempt (CVE-2019-1652)                                    |
| 2027442  | ET EXPLOIT Possible Exim 4.87-4.91 RCE Attempt Inbound (CVE-2019-10149                         |
| 2027959  | ET EXPLOIT Possible EXIM RCE Inbound (CVE-2019-15846)                                          |
| 2027696  | ET EXPLOIT Possible Zoom Client Auto-Join (CVE-2019-13450                                      |
| 2028928  | ET EXPLOIT VMware VeloCloud Authorization Bypass (CVE-2019-5533)                               |
| 2027315  | ET WEB_CLIENT Attempted RCE in Wordpress Social Warfare Plugin Inbound (CVE-2019-9978          |
| 2027333  | ET WEB_CLIENT Possible Confluence SSTI Exploitation Attempt - Leads to RCE/LFI (CVE-2019-3396) |
| 2028895  | ET WEB_SERVER Possible PHP Remote Code Execution CVE-2019-11043 PoC (Inbound)                  |
| 2027706  | ET WEB_SPECIFIC_APPS Appointment Hour Booking - WordPress Plugin - Stored XSS (CVE-2019-13505) |
| 2027712  | ET WEB_SPECIFIC_APPS Atlassian Crowd Plugin Upload Attempt (CVE-2019-11580)                    |
| 2027711  | ET WEB_SPECIFIC_APPS Atlassian JIRA Template Injection RCE (CVE-2019-11581                     |
| 2027368  | ET WEB_SPECIFIC_APPS Cisco Prime Infrastruture RCE - CVE-2019-1821                             |
| 2027349  | ET WEB_SPECIFIC_APPS Jenkins Chained Exploits CVE-2018-1000861 and CVE-2019-1003000 M1         |
| 2027350  | ET WEB_SPECIFIC_APPS Jenkins Chained Exploits CVE-2018-1000861 and CVE-2019-1003000 M2         |
| 2027346  | ET WEB_SPECIFIC_APPS Jenkins RCE CVE-2019-1003000                                              |
| 2027345  | ET WEB_SPECIFIC_APPS Possible SharePoint RCE Attempt (CVE-2019-0604)                           |
