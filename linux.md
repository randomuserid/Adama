Linux Searches and hunts

| Event Type | Category             | Search Name                                                                                                                           |
|------------|----------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| syslog     | Execution            |  Apparmor / selinux exec or mknod operation denied                                                                                    |
| syslog     | Execution            |  Command not allowed                                                                                                                  |
| syslog     | Persistence          |  Crontab edit: "begin edit"                                                                                                           |
| syslog     | Persistence          |  Crontab replace: "replace"                                                                                                           |
| Auditd     | Execution            |  File made executable                                                                                                                 |
| syslog     | Execution            |  Kernel error: "i/o error*" firmware error detected.| acpi error                                                                      |
| syslog     | Execution            |  Large syslog message: larger than 1025 bytes                                                                                         |
| syslog     | Execution            |  Low memory: "out of memory:"                                                                                                         |
| syslog     | Execution            |  Malicious ping: "oversized packet received from *"                                                                                   |
| named      | Execution            |  Named invalid packet: "dropping * packet from*"                                                                                      |
| named      | Execution            |  Named service fail: "exiting (due to fatal error)"                                                                                   |
| named      | Collection           |  Named zone transfer failure: "denied axfr from*" "zone transfer * denied"                                                            |
| named      | Collection           |  Named zone transfer: "in axfr -"                                                                                                     |
| syslog     | Persistence          |  New usb device (in kernel log)                                                                                                       |
| syslog     | Execution            |  Possible attack on rpc.statd "rpc.statd[*]: gethostbyname error for *"                                                               |
| syslog     | Execution            |  Possible exploit of service fail "segfault" or "segfault at *"                                                                       |
| postfix    | Execution            |  Postfil rbl lookup fail: "rbl"                                                                                                       |
| postfix    | Execution            |  Postfix auth failure: " authentication failed"                                                                                       |
| postfix    | Execution            |  Postfix error burst: "^too many "                                                                                                    |
| postfix    | Execution            |  Postfix hostname verify failed: "verification"                                                                                       |
| postfix    | Execution            |  Postfix illegal address: "mail|does not resolve to address"                                                                          |
| postfix    | Execution            |  Postfix send blocked due to ip blacklist: " blocked using "                                                                          |
| postfix    | Execution            |  Postfix stop: "^terminating on signal"                                                                                               |
| syslog     | Defense Evasion      |  Process killed: "killed by sigterm"                                                                                                  |
| syslog     | Collection           |  Promiscuous mode: device * entered promiscuous mode"                                                                                 |
| syslog     | Persistence          |  Root crontab change: "^(root)"                                                                                                       |
| sendmail   | Initial Access       |  Sendmail reject due to acl "reject=550 5.0.0 |reject=553 5.3.0"                                                                      |
| sendmail   | Initial Access       |  Sendmail relay request denied "reject=550 5.7.1"                                                                                     |
| sendmail   | Initial Access       |  Sendmail: send fail due to missing domain "reject=553 5.5.4 "                                                                        |
| sendmail   | Initial Access       |  Sendmail: sender domain lacks valid mx record "reject=451 4.1.8"                                                                     |
| sshd       | Execution            |  Sshd auth failure due to permissions on authorized_keys: "bad ownership or modes for file"                                           |
| sshd       | Execution            |  Sshd connection errors: "connection reset|connection abort"                                                                          |
| sshd       | Execution            |  Sshd corrupted mac input: "corrupted mac on input."                                                                                  |
| sshd       | Execution            |  Sshd dns error: "but this does not map back to the address - possible break-in attempt!$"                                            |
| sshd       | Execution            |  Sshd excessive auth attempts: "^error: maximum authentication attempts exceeded "                                                    |
| sshd       | Execution            |  Sshd hostkey error: "no hostkey alg [preauth]"                                                                                       |
| sshd       | Execution            |  Sshd insecure connection: "did not receive identification string from"                                                               |
| sshd       | Execution            |  Sshd negotiation error: "no matching cipher found"                                                                                   |
| sshd       | Execution            |  Sshd negotiation error: "no matching mac found"                                                                                      |
| sshd       | Execution            |  Sshd negotiation fail: "unable to negotiate with |unable to negotiate a key|fatal: no matching"                                      |
| sshd       | Execution            |  Sshd possible exploit: "fatal: buffer_get_string: bad string"                                                                        |
| sshd       | Execution            |  Sshd reverse lookup error "failed - possible break"                                                                                  |
| sshd       | Execution            |  Sshd session error: "failed to create session: "                                                                                     |
| sshd       | Execution            |  Sshd subsystem error: " failed, subsystem not found$"                                                                                |
| sshd       | Execution            |  Sshd suspicious packet; "^bad packet length"                                                                                         |
| sshd       | Execution            |  Suspicious ssh conection "bad protocol version identification"                                                                       |
| syslog     | Defense Evasion      |  Syslog disk full: "file system full|no space left on device"                                                                         |
| syslog     | Defense Evasion      |  Syslog exit: "exiting on signal"                                                                                                     |
| syslog     | Defense Evasion      |  Syslog restart: "syslogd restarted"                                                                                                  |
| named      | Initial Access       |  Zone transfer error: "bad zone transfer request:"                                                                                    |
| Auditd     | Behavioral Detection | !Elf activity                                                                                                                         |
| Auditd     | Behavioral Detection | Abnormal end to file or directory access                                                                                              |
| Auditd     | Behavioral Detection | Amap - https://sectools.org/tool/amap/                                                                                                |
| Linux      | Initial Access       | Anomalous  authentication                                                                                                             |
| Linux      | Initial Access       | Anomalous /etc/passwd activity                                                                                                        |
| Auditd     | Behavioral Detection | Anomalous apt / yum connect                                                                                                           |
| Auditd     | Behavioral Detection | Anomalous memcache activity                                                                                                           |
| Auditd     | Behavioral Detection | Anomalous nfs activity                                                                                                                |
| Auditd     | Behavioral Detection | Anomalous package install                                                                                                             |
| Linux      | Initial Access       | Anomalous root authentication                                                                                                         |
| Auditd     | Behavioral Detection | Anomalous snapd activity                                                                                                              |
| Auditd     | Behavioral Detection | Aprping http://www.habets.pp.se/synscan/programs.php?Prog=arping                                                                      |
| Auditd     | Behavioral Detection | Arpdig                                                                                                                                |
| Auditd     | Behavioral Detection | Arp-sk                                                                                                                                |
| Auditd     | Behavioral Detection | Arpwatch                                                                                                                              |
| Auditd     | Behavioral Detection | Asp auditor asp-audit.pl                                                                                                              |
| Auditd     | Behavioral Detection | Base64 command                                                                                                                        |
| Auditd     | Behavioral Detection | Base64 python - base64 and python                                                                                                     |
| Auditd     | Execution            | Bash started by nagios                                                                                                                |
| Auditd     | Behavioral Detection | Cheops                                                                                                                                |
| Auditd     | Behavioral Detection | Compiler - apt-get install build-essential                                                                                            |
| Auditd     | Behavioral Detection | Compiler - gcc, make, yasm                                                                                                            |
| Auditd     | Behavioral Detection | Covert_tcp                                                                                                                            |
| Auditd     | Behavioral Detection | Cowpatty                                                                                                                              |
| Auditd     | Behavioral Detection | Cp command on /passwd file                                                                                                            |
| Auditd     | Behavioral Detection | Cp command on authorized_keys directory                                                                                               |
| Auditd     | Behavioral Detection | Curl, wget, lynx                                                                                                                      |
| Auditd     | Behavioral Detection | Curses                                                                                                                                |
| Auditd     | Behavioral Detection | Curses toolkit                                                                                                                        |
| Auditd     | Behavioral Detection | Dirty sock                                                                                                                            |
| Auditd     | Behavioral Detection | Dpkg or rpm installs                                                                                                                  |
| Auditd     | Behavioral Detection | Dsniff                                                                                                                                |
| Auditd     | Privilege Escalation | Echo "* all=(all) nopasswd: all" > /etc/sudoers                                                                                       |
| Auditd     | Behavioral Detection | Echo 0 | sudo tee /proc/sys/net/ipv4/ip_unprivileged_port_start                                                                       |
| Auditd     | Behavioral Detection | Echo and  * base64 *                                                                                                                  |
| Auditd     | Behavioral Detection | Echo to the sudoers file                                                                                                              |
| Auditd     | Behavioral Detection | Etrace                                                                                                                                |
| Auditd     | Behavioral Detection | Ettercap                                                                                                                              |
| Auditd     | Behavioral Detection | Evinemtry memory dump                                                                                                                 |
| Auditd     | Behavioral Detection | File editor invoked by a user                                                                                                         |
| Auditd     | Behavioral Detection | File2air                                                                                                                              |
| Auditd     | Execution            | Fileless elf execution                                                                                                                |
| Auditd     | Behavioral Detection | Firewalk                                                                                                                              |
| Linux      | Initial Access       | First su or sudo by a user                                                                                                            |
| Auditd     | Behavioral Detection | Fl0p                                                                                                                                  |
| Auditd     | Behavioral Detection | Fpdns                                                                                                                                 |
| Auditd     | Behavioral Detection | Fragroute                                                                                                                             |
| Auditd     | Behavioral Detection | Freeradius-wpe                                                                                                                        |
| syslog     | Execution            | From pid * due to rate-limiting"                                                                                                      |
| Auditd     | Behavioral Detection | Ftp activity by wget                                                                                                                  |
| Auditd     | Behavioral Detection | Gnetcat                                                                                                                               |
| Auditd     | Behavioral Detection | Http to remote not apt / yum                                                                                                          |
| Auditd     | Behavioral Detection | Httprint                                                                                                                              |
| Auditd     | Behavioral Detection | Httptunnel - hts / htc                                                                                                                |
| Auditd     | Behavioral Detection | Hydra                                                                                                                                 |
| Auditd     | Behavioral Detection | Icmp shell (ish)                                                                                                                      |
| Auditd     | Behavioral Detection | Icmp-mtu (https://www.gont.com.ar/tools/icmp-attacks/index.html)                                                                      |
| Auditd     | Behavioral Detection | Icmp-quench (https://www.gont.com.ar/tools/icmp-attacks/index.html)                                                                   |
| Auditd     | Behavioral Detection | Icmpshell.sourceforge.net                                                                                                             |
| Auditd     | Behavioral Detection | Iodine  - dns tunneling - iodine / iodined                                                                                            |
| Auditd     | Behavioral Detection | Iodine dns tunneling                                                                                                                  |
| Auditd     | Behavioral Detection | Iperf multicast activity (iperf)                                                                                                      |
| Auditd     | Behavioral Detection | Ipsec tunnel creation                                                                                                                 |
| Auditd     | Behavioral Detection | Isnprober technique                                                                                                                   |
| Auditd     | Behavioral Detection | Jerry vmware fingerprinter                                                                                                            |
| Auditd     | Persistence          | Kernel module loaded - insmod / modprobe activity                                                                                     |
| Auditd     | Behavioral Detection | Kismet                                                                                                                                |
| Auditd     | Behavioral Detection | Kmod                                                                                                                                  |
| Linux      | Initial Access       | Large number of dnssec requests from one source                                                                                       |
| Auditd     | Behavioral Detection | Lft                                                                                                                                   |
| Auditd     | Behavioral Detection | Linenum                                                                                                                               |
| Auditd     | Behavioral Detection | Linpmem memory dump                                                                                                                   |
| Auditd     | Behavioral Detection | Linux privchecker                                                                                                                     |
| Linux      | Behavioral Detection | Local default gw configured                                                                                                           |
| Auditd     | Behavioral Detection | Local firewall policy mod - iptables –aid or command or changes to iptables-config                                                    |
| Auditd     | Behavioral Detection | Local firewall rule flush - iptables –f command                                                                                       |
| Auditd     | Behavioral Detection | Local firewall stop - commands containing string iptables stop                                                                        |
| Linux      | Behavioral Detection | Local fw policy mod                                                                                                                   |
| Auditd     | Privilege Escalation | Local group mod - changes to /etc/shadow or /etc/passwd or passwd command                                                             |
| Auditd     | Privilege Escalation | Local group mod - groupadd, groupmod or groupdel (from shell history)                                                                 |
| Auditd     | Privilege Escalation | Local key activity - changes to authorized_keys                                                                                       |
| Auditd     | Privilege Escalation | Local root / administrator activity                                                                                                   |
| Auditd     | Privilege Escalation | Local user creation - useradd                                                                                                         |
| Auditd     | Privilege Escalation | Local user mod                                                                                                                        |
| Auditd     | Behavioral Detection | Macof                                                                                                                                 |
| Auditd     | Behavioral Detection | Memory dumping - /dev/mem or /dev/kmem command activity                                                                               |
| Auditd     | Behavioral Detection | Mknod activity                                                                                                                        |
| Auditd     | Behavioral Detection | Mknod activity by bash                                                                                                                |
| Auditd     | Behavioral Detection | Nemesis (packet creation)                                                                                                             |
| Auditd     | Behavioral Detection | Net-snmp - snmp*                                                                                                                      |
| Auditd     | Behavioral Detection | Netstumbler                                                                                                                           |
| Auditd     | Behavioral Detection | Nmap activity                                                                                                                         |
| Auditd     | Behavioral Detection | Nping activity                                                                                                                        |
| Auditd     | Behavioral Detection | Nssl - https://sourceforge.net/projects/nssl/                                                                                         |
| Auditd     | Behavioral Detection | Ntp-fingerprint http://www.hackingciscoexposed.com/?Link=tools                                                                        |
| Auditd     | Behavioral Detection | P0f                                                                                                                                   |
| Auditd     | Behavioral Detection | Packit (maybe defunct)                                                                                                                |
| Auditd     | Behavioral Detection | Passive asset detection system -pads                                                                                                  |
| Auditd     | Behavioral Detection | Pf (pfctl)                                                                                                                            |
| Auditd     | Behavioral Detection | Ping tunnel (ptunnel)                                                                                                                 |
| Auditd     | Behavioral Detection | Portpush technique                                                                                                                    |
| Auditd     | Behavioral Detection | Powershell activity from a linux instance                                                                                             |
| Auditd     | Persistence          | Process started from /tmp (not jenkins)                                                                                               |
| Auditd     | Behavioral Detection | Process with /etc/passwd arguments                                                                                                    |
| Auditd     | Behavioral Detection | Python using base64 encoding - python * import base64 *                                                                               |
| Auditd     | Discovery            | Redpill vmware fingerprinter                                                                                                          |
| Auditd     | Behavioral Detection | Rm -rf                                                                                                                                |
| Linux      | Behavioral Detection | Root or su activity                                                                                                                   |
| Auditd     | Behavioral Detection | Rootshell piped to tcp device                                                                                                         |
| Auditd     | Behavioral Detection | Rsynch                                                                                                                                |
| syslog     | Defense Evasion      | Rsyslog message drops "imuxsock begins to drop messages                                                                               |
| Auditd     | Discovery            | Scoopy vmware fingerprinter                                                                                                           |
| Auditd     | Discovery            | Search for writable executables:                                                                                                      |
| Auditd     | Behavioral Detection | Searchsploit                                                                                                                          |
| Auditd     | Behavioral Detection | Shell activity by service account                                                                                                     |
| Auditd     | Execution            | Shell commands with no tty session                                                                                                    |
| Auditd     | Execution            | Shell run from /tmp directory                                                                                                         |
| Auditd     | Behavioral Detection | Sinfp                                                                                                                                 |
| Auditd     | Behavioral Detection | Sing                                                                                                                                  |
| Auditd     | Behavioral Detection | Sniffit                                                                                                                               |
| Auditd     | Behavioral Detection | Snmpd                                                                                                                                 |
| Auditd     | Behavioral Detection | Snmpdelta                                                                                                                             |
| Auditd     | Behavioral Detection | Snmpdf                                                                                                                                |
| Auditd     | Behavioral Detection | Snmpget                                                                                                                               |
| Auditd     | Behavioral Detection | Snmpgetnext                                                                                                                           |
| Auditd     | Behavioral Detection | Snmpnetstat                                                                                                                           |
| Auditd     | Behavioral Detection | Snmpset                                                                                                                               |
| Auditd     | Behavioral Detection | Snmpstatus                                                                                                                            |
| Auditd     | Behavioral Detection | Snmptable                                                                                                                             |
| Auditd     | Behavioral Detection | Snmptranslate                                                                                                                         |
| Auditd     | Behavioral Detection | Snmptrapd                                                                                                                             |
| Auditd     | Behavioral Detection | Snmpwalk                                                                                                                              |
| Auditd     | Persistence          | Ssh config change - changes to ssh_config file                                                                                        |
| Auditd     | Behavioral Detection | Strace command                                                                                                                        |
| syslog     | Privilege Escalation | Sudo activity                                                                                                                         |
| Auditd     | Behavioral Detection | Suid set on file in /tmp - chmod u+s                                                                                                  |
| Auditd     | Behavioral Detection | Sysctl command                                                                                                                        |
| syslog     | Execution            | Syslog errors "core_dumped|failure|error|attack| bad |illegal |denied|refused|unauthorized|fatal|failed|segmentation fault|corrupted" |
| Auditd     | Defense Evasion      | System logs cleared - wipes of last, $histfile or log files in /var/log                                                               |
| Auditd     | Behavioral Detection | Tcpdevice activity - /dev/tcp command activity                                                                                        |
| Auditd     | Behavioral Detection | Tcpdump activity                                                                                                                      |
| Auditd     | Behavioral Detection | Tls key activity  - *.key                                                                                                             |
| Auditd     | Behavioral Detection | Udpcast - file transfer over ip multicast (udp-sender)                                                                                |
| Auditd     | Behavioral Detection | Unix privseccheck                                                                                                                     |
| Auditd     | Behavioral Detection | Unprivileged port start config                                                                                                        |
| Auditd     | Privilege Escalation | User / group change, remote caller                                                                                                    |
| Auditd     | Privilege Escalation | User not in sudoers                                                                                                                   |
| Auditd     | Behavioral Detection | User2sid                                                                                                                              |
| Auditd     | Behavioral Detection | Vim persistence                                                                                                                       |
| Auditd     | Behavioral Detection | Vmdetect vmware fingerprinter                                                                                                         |
| Auditd     | Behavioral Detection | Xprobe2                                                                                                                               |
| Auditd     | Behavioral Detection | Yersenia                                                                                                                              |
| Auditd     | Initial Access       | Zone transfer denied                                                                                                                  |
| Auditd     | Initial Access       | Zone transfer succeeded                                                                                                               |
