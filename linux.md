Linux searches

| Auditd                            | Linux    |  file made executable                                                                                                                 |
|-----------------------------------|----------|---------------------------------------------------------------------------------------------------------------------------------------|
|  Auditd                           | Linux    |  abnormal end to file or directory access                                                                                             |
| Exploit activity                  | Linux    | bash started by nagios                                                                                                                |
| Exploit activity                  | Linux    | mknod activity                                                                                                                        |
| Exploit activity                  | Linux    | mknod activity by bash                                                                                                                |
| Exploit activity                  | Linux    | tcpdevice activity - /dev/tcp command activity                                                                                        |
| Exploit activity                  | Linux    | shell commands with no tty session                                                                                                    |
| Persistence                       | Linux    | process started from /tmp (not jenkins)                                                                                               |
| Network                           | Linux    | http to remote not apt / yum                                                                                                          |
| Network                           | Linux    | anomalous apt / yum connect                                                                                                           |
| Network                           | Linux    | rsynch                                                                                                                                |
| Network                           | Linux    | nfs                                                                                                                                   |
| Network                           | Linux    | ftp activity by wget                                                                                                                  |
| Network                           | Linux    | Iodine DNS tunneling                                                                                                                  |
| Network                           | Linux    | anomalous snapd activity                                                                                                              |
| Network                           | Linux    | Powershell activity from a Linux instance                                                                                             |
| Process Activity                  | Linux    | !ELF activity                                                                                                                         |
| Process Activity                  | Linux    | anomalous package install                                                                                                             |
| Process Activity                  | Linux    | base64 command                                                                                                                        |
| Process Activity                  | Linux    | base64 python - base64 AND python                                                                                                     |
| Process Activity                  | Linux    | compiler - apt-get install build-essential                                                                                            |
| Process Activity                  | Linux    | compiler - gcc, make, yasm                                                                                                            |
| Process Activity                  | Linux    | cp command on /passwd file                                                                                                            |
| Process Activity                  | Linux    | cp command on authorized_keys directory                                                                                               |
| Process Activity                  | Linux    | Curl, wget, lynx                                                                                                                      |
| Process Activity                  | Linux    | dirty sock                                                                                                                            |
| Process Activity                  | Linux    | dpkg or rpm installs                                                                                                                  |
| Process Activity                  | Linux    | echo "wernerbrandes ALL=(ALL) NOPASSWD: ALL" > /etc/sudoers                                                                           |
| Process Activity                  | Linux    | echo 0 | sudo tee /proc/sys/net/ipv4/ip_unprivileged_port_start                                                                       |
| Process Activity                  | Linux    | echo AND  * base64 *                                                                                                                  |
| Process Activity                  | Linux    | echo to the sudoers file                                                                                                              |
| Process Activity                  | Linux    | evinemtry memory dump                                                                                                                 |
| Process Activity                  | Linux    | file editor invoked by a user                                                                                                         |
| Process Activity                  | Linux    | Fileless ELF execution                                                                                                                |
| Process Activity                  | Linux    | Ipsec tunnel creation                                                                                                                 |
| Process Activity                  | Linux    | Kernel module loaded - Insmod / modprobe activity                                                                                     |
| Process Activity                  | Linux    | kmod                                                                                                                                  |
| Process Activity                  | Linux    | LinEnum                                                                                                                               |
| Process Activity                  | Linux    | linpmem memory dump                                                                                                                   |
| Process Activity                  | Linux    | Linux PrivChecker                                                                                                                     |
| Process Activity                  | Linux    | Local firewall policy mod - Iptables –AID or command OR changes to iptables-config                                                    |
| Process Activity                  | Linux    | Local firewall rule flush - Iptables –F command                                                                                       |
| Process Activity                  | Linux    | Local firewall stop - Commands containing string iptables stop                                                                        |
| Process Activity                  | Linux    | Memory dumping - /dev/mem or /dev/kmem command activity                                                                               |
| Process Activity                  | Linux    | nmap activity                                                                                                                         |
| Process Activity                  | Linux    | nping activity                                                                                                                        |
| Process Activity                  | Linux    | PortPush technique                                                                                                                    |
| Process Activity                  | Linux    | privilege elevation                                                                                                                   |
| Process Activity                  | Linux    | process with /etc/passwd arguments                                                                                                    |
| Process Activity                  | Linux    | python using base64 encoding - python * import base64 *                                                                               |
| Process Activity                  | Linux    | rm -rf                                                                                                                                |
| Process Activity                  | Linux    | search for writable executables:                                                                                                      |
| Process Activity                  | Linux    | SearchSploit                                                                                                                          |
| Process Activity                  | Linux    | shell run from /tmp directory                                                                                                         |
| Process Activity                  | Linux    | strace command                                                                                                                        |
| Process Activity                  | Linux    | suid set on file in /tmp - chmod u+s                                                                                                  |
| Process Activity                  | Linux    | sysctl command                                                                                                                        |
| Process Activity                  | Linux    | tcpdump activity                                                                                                                      |
| Process Activity                  | Linux    | Unix PrivsecCheck                                                                                                                     |
| Process Activity                  | Linux    | unprivileged port start config                                                                                                        |
| Process Activity                  | Linux    | vim persistence                                                                                                                       |
| Process Activity                  | Linux    | TLs key activity  - *.key                                                                                                             |
| Process Activity                  | Linux    | rootshell piped to tcp device                                                                                                         |
| Logs                              | Linux    | Anomalous  authentication                                                                                                             |
| Logs                              | Linux    | Anomalous root authentication                                                                                                         |
| Logs                              | Linux    |  AppArmor / SELinux exec or mknod operation denied                                                                                    |
| Logs                              | Linux    |  command not allowed                                                                                                                  |
| Logs                              | Linux    |  new USB device (in kernel log)                                                                                                       |
| Logs                              | Linux    |  possible exploit of service fail "segfault" or "segfault at *"                                                                       |
| Logs                              | Linux    | anomalous /etc/passwd activity                                                                                                        |
| Logs                              | Linux    | first su or sudo by a user                                                                                                            |
| Logs                              | Linux    | local default gw configured                                                                                                           |
| Logs                              | Linux    | local fw policy mod                                                                                                                   |
| Logs                              | Linux    | local group mod - Changes to /etc/shadow OR /etc/passwd OR passwd command                                                             |
| Logs                              | Linux    | Local group mod - Groupadd, groupmod or groupdel (from shell history)                                                                 |
| Logs                              | Linux    | Local key activity - changes to authorized_keys                                                                                       |
| Logs                              | Linux    | local root / administrator activity                                                                                                   |
| Logs                              | Linux    | local user creation - useradd                                                                                                         |
| Logs                              | Linux    | local user mod                                                                                                                        |
| Logs                              | Linux    | Root or su activity                                                                                                                   |
| Logs                              | Linux    | SSH config change - changes to ssh_config file                                                                                        |
| Logs                              | Linux    | sudo activity                                                                                                                         |
| Logs                              | Linux    | System logs cleared - Wipes of last, $HISTFILE or log files in /var/log                                                               |
| Logs                              | Linux    | user / group change, remote caller                                                                                                    |
| Logs                              | Linux    | user NOT in sudoers                                                                                                                   |
| Logs                              | Linux    | zone transfer succeeded                                                                                                               |
| Logs                              | Linux    | zone transfer denied                                                                                                                  |
| Logs                              | Linux    | large number of DNSSEC requests from one source                                                                                       |
| Shell activity by suspicious user | Linux    | apache                                                                                                                                |
| Shell activity by suspicious user | Linux    | mysql                                                                                                                                 |
| Shell activity by suspicious user | Linux    | www                                                                                                                                   |
| Shell activity by suspicious user | Linux    | nobody                                                                                                                                |
| Shell activity by suspicious user | Linux    | nogroup                                                                                                                               |
| Shell activity by suspicious user | Linux    | portmap                                                                                                                               |
| Shell activity by suspicious user | Linux    | named                                                                                                                                 |
| Shell activity by suspicious user | Linux    | rpc                                                                                                                                   |
| Shell activity by suspicious user | Linux    | mail                                                                                                                                  |
| Shell activity by suspicious user | Linux    | ftp                                                                                                                                   |
| Shell activity by suspicious user | Linux    | shutdown                                                                                                                              |
| Shell activity by suspicious user | Linux    | halt                                                                                                                                  |
| Shell activity by suspicious user | Linux    | daemon                                                                                                                                |
| Shell activity by suspicious user | Linux    | bin                                                                                                                                   |
| Shell activity by suspicious user | Linux    | postfix                                                                                                                               |
| Shell activity by suspicious user | Linux    | shell                                                                                                                                 |
| Shell activity by suspicious user | Linux    | info                                                                                                                                  |
| Shell activity by suspicious user | Linux    | guest                                                                                                                                 |
| Shell activity by suspicious user | Linux    | psql                                                                                                                                  |
| Shell activity by suspicious user | Linux    | user                                                                                                                                  |
| Shell activity by suspicious user | Linux    | users                                                                                                                                 |
| Shell activity by suspicious user | Linux    | console                                                                                                                               |
| Shell activity by suspicious user | Linux    | uucp                                                                                                                                  |
| Shell activity by suspicious user | Linux    | lp                                                                                                                                    |
| Shell activity by suspicious user | Linux    | sync                                                                                                                                  |
| Shell activity by suspicious user | Linux    | sshd                                                                                                                                  |
| Shell activity by suspicious user | Linux    | cdrom                                                                                                                                 |
| Shell activity by suspicious user | Linux    | ossec                                                                                                                                 |
| Logs                              | named    |  named invalid packet: "dropping * packet from*"                                                                                      |
| Logs                              | named    |  named zone transfer failure: "denied AXFR from*" "zone transfer * denied"                                                            |
| Logs                              | named    |  named zone transfer: "IN AXFR -"                                                                                                     |
| Logs                              | named    |  zone transfer error: "bad zone transfer request:"                                                                                    |
| Logs                              | named    |  named service fail: "exiting (due to fatal error)"                                                                                   |
| Logs                              | postfix  |  postfix send blocked due to IP blacklist: " blocked using "                                                                          |
| Logs                              | postfix  |  postfix auth failure: " authentication failed"                                                                                       |
| Logs                              | postfix  |  postfix error burst: "^too many "                                                                                                    |
| Logs                              | postfix  |  postfix stop: "^terminating on signal"                                                                                               |
| Logs                              | postfix  |  postfix hostname verify failed: "verification"                                                                                       |
| Logs                              | postfix  |  postfil RBL lookup fail: "RBL"                                                                                                       |
| Logs                              | postfix  |  postfix illegal address: "MAIL|does not resolve to address"                                                                          |
| Logs                              | sendmail |  sendmail relay request denied "reject=550 5.7.1"                                                                                     |
| Logs                              | sendmail |  sendmail: sender domain lacks valid MX record "reject=451 4.1.8"                                                                     |
| Logs                              | sendmail |  sendmail reject due to ACL "reject=550 5.0.0 |reject=553 5.3.0"                                                                      |
| Logs                              | sendmail |  sendmail: send fail due to missing domain "reject=553 5.5.4 "                                                                        |
| Logs                              | sshd     |  suspicious ssh conection "Bad protocol version identification"                                                                       |
| Logs                              | sshd     |  sshd reverse lookup error "failed - POSSIBLE BREAK"                                                                                  |
| Logs                              | sshd     |  sshd possible exploit: "fatal: buffer_get_string: bad string"                                                                        |
| Logs                              | sshd     |  sshd insecure connection: "Did not receive identification string from"                                                               |
| Logs                              | sshd     |  sshd connection errors: "Connection reset|connection abort"                                                                          |
| Logs                              | sshd     |  sshd suspicious packet; "^Bad packet length"                                                                                         |
| Logs                              | sshd     |  sshd corrupted MAC input: "Corrupted MAC on input."                                                                                  |
| Logs                              | sshd     |  sshd negotiation fail: "Unable to negotiate with |Unable to negotiate a key|fatal: no matching"                                      |
| Logs                              | sshd     |  sshd hostkey error: "no hostkey alg [preauth]"                                                                                       |
| Logs                              | sshd     |  sshd negotiation error: "no matching cipher found"                                                                                   |
| Logs                              | sshd     |  sshd negotiation error: "no matching mac found"                                                                                      |
| Logs                              | sshd     |  sshd session error: "Failed to create session: "                                                                                     |
| Logs                              | sshd     |  sshd auth failure due to permissions on authorized_keys: "bad ownership or modes for file"                                           |
| Logs                              | sshd     |  sshd subsystem error: " failed, subsystem not found$"                                                                                |
| Logs                              | sshd     |  sshd dns error: "but this does not map back to the address - POSSIBLE BREAK-IN ATTEMPT!$"                                            |
| Logs                              | sshd     |  sshd excessive auth attempts: "^error: maximum authentication attempts exceeded "                                                    |
| Logs                              | syslog   | rsyslog message drops "imuxsock begins to drop messages                                                                               |
| Logs                              | syslog   | from pid * due to rate-limiting"                                                                                                      |
| Logs                              | syslog   |  possible attack on rpc.statd "rpc.statd[*]: gethostbyname error for *"                                                               |
| Logs                              | syslog   | syslog errors "core_dumped|failure|error|attack| bad |illegal |denied|refused|unauthorized|fatal|failed|Segmentation Fault|Corrupted" |
| Logs                              | syslog   |  large syslog message: larger than 1025 bytes                                                                                         |
| Logs                              | syslog   |  syslog exit: "exiting on signal"                                                                                                     |
| Logs                              | syslog   |  syslog restart: "Syslogd restarted"                                                                                                  |
| Logs                              | syslog   |  syslog disk full: "file system full|No space left on device"                                                                         |
| Logs                              | syslog   |  process killed: "killed by SIGTERM"                                                                                                  |
| Logs                              | syslog   |  malicious ping: "Oversized packet received from *"                                                                                   |
| Logs                              | syslog   |  promiscuous mode: device * entered promiscuous mode"                                                                                 |
| Logs                              | syslog   |  kernel error: "I/O error*" Firmware error detected.| ACPI Error                                                                      |
| Logs                              | syslog   |  low memory: "Out of Memory:"                                                                                                         |
| Logs                              | syslog   |  crontab edit: "BEGIN EDIT"                                                                                                           |
| Logs                              | syslog   |  crontab replace: "REPLACE"                                                                                                           |
| Logs                              | syslog   |  root crontab change: "^(root)"                                                                                                       |
|                                   |          | amap - https://sectools.org/tool/amap/                                                                                                |
| Process Activity                  | Linux    | ASP auditor asp-audit.pl                                                                                                              |
| Process Activity                  | Linux    | etrace                                                                                                                                |
| Process Activity                  | Linux    | firewalk                                                                                                                              |
| Process Activity                  | Linux    | fl0p                                                                                                                                  |
| Process Activity                  | Linux    | fpdns                                                                                                                                 |
| Process Activity                  | Linux    | fragroute                                                                                                                             |
| Process Activity                  | Linux    | gnetcat                                                                                                                               |
| Process Activity                  | Linux    | httprint                                                                                                                              |
| Process Activity                  | Linux    | httptunnel - hts / htc                                                                                                                |
| Process Activity                  | Linux    | icmp shell (ish)                                                                                                                      |
| Process Activity                  | Linux    | icmp-mtu (https://www.gont.com.ar/tools/icmp-attacks/index.html)                                                                      |
| Process Activity                  | Linux    | icmp-quench (https://www.gont.com.ar/tools/icmp-attacks/index.html)                                                                   |
| Process Activity                  | Linux    | icmpshell.sourceforge.net                                                                                                             |
| Process Activity                  | Linux    | iodine  - dns tunneling - iodine / iodined                                                                                            |
| Process Activity                  | Linux    | iperf multicast activity (iperf)                                                                                                      |
| Process Activity                  | Linux    | isnprober technique                                                                                                                   |
| Process Activity                  | Linux    | lft                                                                                                                                   |
| Process Activity                  | Linux    | nemesis (packet creation)                                                                                                             |
| Process Activity                  | Linux    | Net-SNMP - snmp*                                                                                                                      |
| Process Activity                  | Linux    | nssl - https://sourceforge.net/projects/nssl/                                                                                         |
| Process Activity                  | Linux    | ntp-fingerprint http://www.hackingciscoexposed.com/?link=tools                                                                        |
| Process Activity                  | Linux    | p0f                                                                                                                                   |
| Process Activity                  | Linux    | packit (maybe defunct)                                                                                                                |
| Process Activity                  | Linux    | Passive asset detection system -pads                                                                                                  |
| Process Activity                  | Linux    | pf (pfctl)                                                                                                                            |
| Process Activity                  | Linux    | ping tunnel (ptunnel)                                                                                                                 |
| Process Activity                  | Linux    | sinfp                                                                                                                                 |
| Process Activity                  | Linux    | sing                                                                                                                                  |
| Process Activity                  | Linux    | snmpd                                                                                                                                 |
| Process Activity                  | Linux    | snmpdelta                                                                                                                             |
| Process Activity                  | Linux    | snmpdf                                                                                                                                |
| Process Activity                  | Linux    | snmpget                                                                                                                               |
| Process Activity                  | Linux    | snmpgetnext                                                                                                                           |
| Process Activity                  | Linux    | snmpnetstat                                                                                                                           |
| Process Activity                  | Linux    | snmpset                                                                                                                               |
| Process Activity                  | Linux    | snmpstatus                                                                                                                            |
| Process Activity                  | Linux    | snmptable                                                                                                                             |
| Process Activity                  | Linux    | snmptranslate                                                                                                                         |
| Process Activity                  | Linux    | snmptrapd                                                                                                                             |
| Process Activity                  | Linux    | snmpwalk                                                                                                                              |
| Process Activity                  | Linux    | udpcast - file transfer over IP multicast (udp-sender)                                                                                |
| Process Activity                  | Linux    | xprobe2                                                                                                                               |
| Network - layer 2                 | Linux    | aprping http://www.habets.pp.se/synscan/programs.php?prog=arping                                                                      |
| Network - layer 3                 | Linux    | arpdig                                                                                                                                |
| Network - layer 4                 | Linux    | arp-sk                                                                                                                                |
| Network - layer 5                 | Linux    | arpwatch                                                                                                                              |
| Network - layer 6                 | Linux    | dsniff                                                                                                                                |
| Network - layer 7                 | Linux    | ettercap                                                                                                                              |
| Network - layer 8                 | Linux    | kismet                                                                                                                                |
| Network - layer 9                 | Linux    | macof                                                                                                                                 |
| Network - layer 10                | Linux    | yersenia                                                                                                                              |
