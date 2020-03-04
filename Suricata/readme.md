![things](/img/snorts2.png?raw=true "text")

### Snort / Suricata Rules

Update: I have made the first eight Elastic SIEM rules for interesting Suricata alerts. Three are for very recent exploits in the Emerging Threats rules like Ghostcat and the Exchange RCE. Five utilize Travis Green's excellent hunting rules at https://github.com/travisbgreen/hunting-rules/blob/master/hunting.rules - these rules need to be enabled with this command:

`suricata-update -add-source tgreen/hunting`

I've added a test to these five for a non-private Internet destination address in order to filter out noise from local web services and applications that may use non-standard ports. These searches look like this:

| Name                                                              | Search                                                                                                                                                                                          |
|-------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Exchange Exploit Activity - CVE-2020-0688                         | suricata.eve.alert.signature_id:2029540                                                                                                                                                         |
| Ghostcat Exploit Detected                                         | suricata.eve.alert.signature_id:2029533                                                                                                                                                         |
| Internet FTP Traffic on Unusual Port                              | suricata.eve.alert.signature_id:2610005 and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16                                            |
| Internet HTTP Traffic on Unusual Port                             | suricata.eve.alert.signature_id:2610001 and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16 and not destination.ip: 169.254.169.254/32 |
| Internet IMAP Traffic on Unusual Port                             | suricata.eve.alert.signature_id:2610009 and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16                                            |
| Internet SSH Traffic on Unusual Port                              | suricata.eve.alert.signature_id:2610003 and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16 and not destination.ip: 169.254.169.254/32 |
| Internet TLS Traffic on Unusual Port                              | suricata.eve.alert.signature_id:2610003 and not destination.ip:10.0.0.0/8 and not destination.ip:172.16.0.0/12 and not destination.ip:192.168.0.0/16 and not destination.ip: 169.254.169.254/32 |
| Microsoft SQL Reporting Services Exploit Activity - CVE-2020-0618 | suricata.eve.alert.signature_id:2029476                                                                                                                                                         |
