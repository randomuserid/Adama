Linux searches

| Category                          | Description                                                                                                                           |
|-----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| Process Activity                  |  abnormal end to file or directory access                                                                                             |
| Process Activity                  |  file made executable                                                                                                                 |
| Process Activity                  | bash started by nagios                                                                                                                |
| Process Activity                  | mknod activity                                                                                                                        |
| Process Activity                  | mknod activity by bash                                                                                                                |
| Process Activity                  | shell commands with no tty session                                                                                                    |
| Process Activity                  | tcpdevice activity - /dev/tcp command activity                                                                                        |
| Logs                              |  AppArmor / SELinux exec or mknod operation denied                                                                                    |
| Logs                              |  command not allowed                                                                                                                  |
| Logs                              |  crontab edit: "BEGIN EDIT"                                                                                                           |
| Logs                              |  crontab replace: "REPLACE"                                                                                                           |
| Logs                              |  kernel error: "I/O error*" Firmware error detected.| ACPI Error                                                                      |
| Logs                              |  large syslog message: larger than 1025 bytes                                                                                         |
| Logs                              |  low memory: "Out of Memory:"                                                                                                         |
| Logs                              |  malicious ping: "Oversized packet received from *"                                                                                   |
| Logs                              |  named invalid packet: "dropping * packet from*"                                                                                      |
| Logs                              |  named service fail: "exiting (due to fatal error)"                                                                                   |
| Logs                              |  named zone transfer failure: "denied AXFR from*" "zone transfer * denied"                                                            |
| Logs                              |  named zone transfer: "IN AXFR -"                                                                                                     |
| Logs                              |  new USB device (in kernel log)                                                                                                       |
| Logs                              |  possible attack on rpc.statd "rpc.statd[*]: gethostbyname error for *"                                                               |
| Logs                              |  possible exploit of service fail "segfault" or "segfault at *"                                                                       |
| Logs                              |  postfil RBL lookup fail: "RBL"                                                                                                       |
| Logs                              |  postfix auth failure: " authentication failed"                                                                                       |
| Logs                              |  postfix error burst: "^too many "                                                                                                    |
| Logs                              |  postfix hostname verify failed: "verification"                                                                                       |
| Logs                              |  postfix illegal address: "MAIL|does not resolve to address"                                                                          |
| Logs                              |  postfix send blocked due to IP blacklist: " blocked using "                                                                          |
| Logs                              |  postfix stop: "^terminating on signal"                                                                                               |
| Logs                              |  process killed: "killed by SIGTERM"                                                                                                  |
| Logs                              |  promiscuous mode: device * entered promiscuous mode"                                                                                 |
| Logs                              |  root crontab change: "^(root)"                                                                                                       |
| Logs                              |  sendmail reject due to ACL "reject=550 5.0.0 |reject=553 5.3.0"                                                                      |
| Logs                              |  sendmail relay request denied "reject=550 5.7.1"                                                                                     |
| Logs                              |  sendmail: send fail due to missing domain "reject=553 5.5.4 "                                                                        |
| Logs                              |  sendmail: sender domain lacks valid MX record "reject=451 4.1.8"                                                                     |
| Logs                              |  sshd auth failure due to permissions on authorized_keys: "bad ownership or modes for file"                                           |
| Logs                              |  sshd connection errors: "Connection reset|connection abort"                                                                          |
| Logs                              |  sshd corrupted MAC input: "Corrupted MAC on input."                                                                                  |
| Logs                              |  sshd dns error: "but this does not map back to the address - POSSIBLE BREAK-IN ATTEMPT!$"                                            |
| Logs                              |  sshd excessive auth attempts: "^error: maximum authentication attempts exceeded "                                                    |
| Logs                              |  sshd hostkey error: "no hostkey alg [preauth]"                                                                                       |
| Logs                              |  sshd insecure connection: "Did not receive identification string from"                                                               |
| Logs                              |  sshd negotiation error: "no matching cipher found"                                                                                   |
| Logs                              |  sshd negotiation error: "no matching mac found"                                                                                      |
| Logs                              |  sshd negotiation fail: "Unable to negotiate with |Unable to negotiate a key|fatal: no matching"                                      |
| Logs                              |  sshd possible exploit: "fatal: buffer_get_string: bad string"                                                                        |
| Logs                              |  sshd reverse lookup error "failed - POSSIBLE BREAK"                                                                                  |
| Logs                              |  sshd session error: "Failed to create session: "                                                                                     |
| Logs                              |  sshd subsystem error: " failed, subsystem not found$"                                                                                |
| Logs                              |  sshd suspicious packet; "^Bad packet length"                                                                                         |
| Logs                              |  suspicious ssh conection "Bad protocol version identification"                                                                       |
| Logs                              |  syslog disk full: "file system full|No space left on device"                                                                         |
| Logs                              |  syslog exit: "exiting on signal"                                                                                                     |
| Logs                              |  syslog restart: "Syslogd restarted"                                                                                                  |
| Logs                              |  zone transfer error: "bad zone transfer request:"                                                                                    |
| Logs                              | Anomalous  authentication                                                                                                             |
| Logs                              | anomalous /etc/passwd activity                                                                                                        |
| Logs                              | Anomalous root authentication                                                                                                         |
| Logs                              | first su or sudo by a user                                                                                                            |
| Logs                              | from pid * due to rate-limiting"                                                                                                      |
| Logs                              | large number of DNSSEC requests from one source                                                                                       |
| Logs                              | local default gw configured                                                                                                           |
| Logs                              | local fw policy mod                                                                                                                   |
| Logs                              | local group mod - Changes to /etc/shadow OR /etc/passwd OR passwd command                                                             |
| Logs                              | Local group mod - Groupadd, groupmod or groupdel (from shell history)                                                                 |
| Logs                              | Local key activity - changes to authorized_keys                                                                                       |
| Logs                              | local root / administrator activity                                                                                                   |
| Logs                              | local user creation - useradd                                                                                                         |
| Logs                              | local user mod                                                                                                                        |
| Logs                              | Root or su activity                                                                                                                   |
| Logs                              | rsyslog message drops "imuxsock begins to drop messages                                                                               |
| Logs                              | SSH config change - changes to ssh_config file                                                                                        |
| Logs                              | sudo activity                                                                                                                         |
| Logs                              | syslog errors "core_dumped|failure|error|attack| bad |illegal |denied|refused|unauthorized|fatal|failed|Segmentation Fault|Corrupted" |
| Logs                              | System logs cleared - Wipes of last, $HISTFILE or log files in /var/log                                                               |
| Logs                              | user / group change, remote caller                                                                                                    |
| Logs                              | user NOT in sudoers                                                                                                                   |
| Logs                              | zone transfer denied                                                                                                                  |
| Logs                              | zone transfer succeeded                                                                                                               |
| Network                           | anomalous apt / yum connect                                                                                                           |
| Network                           | Anomalous memcache activity                                                                                                           |
| Network                           | anomalous snapd activity                                                                                                              |
| Network                           | ftp activity by wget                                                                                                                  |
| Network                           | http to remote not apt / yum                                                                                                          |
| Network                           | Iodine DNS tunneling                                                                                                                  |
| Network                           | nfs                                                                                                                                   |
| Network                           | Powershell activity from a Linux instance                                                                                             |
| Network                           | rsynch                                                                                                                                |
| Network - layer 2                 | aprping http://www.habets.pp.se/synscan/programs.php?prog=arping                                                                      |
| Network - layer 2                 | arpdig                                                                                                                                |
| Network - layer 2                 | arp-sk                                                                                                                                |
| Network - layer 2                 | arpwatch                                                                                                                              |
| Network - layer 2                 | dsniff                                                                                                                                |
| Network - layer 2                 | ettercap                                                                                                                              |
| Network - layer 2                 | kismet                                                                                                                                |
| Network - layer 2                 | macof                                                                                                                                 |
| Network - layer 2                 | yersenia                                                                                                                              |
| Persistence                       | process started from /tmp (not jenkins)                                                                                               |
| Process Activity                  | !ELF activity                                                                                                                         |
| Process Activity                  | amap - https://sectools.org/tool/amap/                                                                                                |
| Process Activity                  | anomalous package install                                                                                                             |
| Process Activity                  | ASP auditor asp-audit.pl                                                                                                              |
| Process Activity                  | base64 command                                                                                                                        |
| Process Activity                  | base64 python - base64 AND python                                                                                                     |
| Process Activity                  | compiler - apt-get install build-essential                                                                                            |
| Process Activity                  | compiler - gcc, make, yasm                                                                                                            |
| Process Activity                  | cp command on /passwd file                                                                                                            |
| Process Activity                  | cp command on authorized_keys directory                                                                                               |
| Process Activity                  | Curl, wget, lynx                                                                                                                      |
| Process Activity                  | dirty sock                                                                                                                            |
| Process Activity                  | dpkg or rpm installs                                                                                                                  |
| Process Activity                  | echo "wernerbrandes ALL=(ALL) NOPASSWD: ALL" > /etc/sudoers                                                                           |
| Process Activity                  | echo 0 | sudo tee /proc/sys/net/ipv4/ip_unprivileged_port_start                                                                       |
| Process Activity                  | echo AND  * base64 *                                                                                                                  |
| Process Activity                  | echo to the sudoers file                                                                                                              |
| Process Activity                  | etrace                                                                                                                                |
| Process Activity                  | evinemtry memory dump                                                                                                                 |
| Process Activity                  | file editor invoked by a user                                                                                                         |
| Process Activity                  | Fileless ELF execution                                                                                                                |
| Process Activity                  | firewalk                                                                                                                              |
| Process Activity                  | fl0p                                                                                                                                  |
| Process Activity                  | fpdns                                                                                                                                 |
| Process Activity                  | fragroute                                                                                                                             |
| Process Activity                  | gnetcat                                                                                                                               |
| Process Activity                  | httprint                                                                                                                              |
| Process Activity                  | httptunnel - hts / htc                                                                                                                |
| Process Activity                  | icmp shell (ish)                                                                                                                      |
| Process Activity                  | icmp-mtu (https://www.gont.com.ar/tools/icmp-attacks/index.html)                                                                      |
| Process Activity                  | icmp-quench (https://www.gont.com.ar/tools/icmp-attacks/index.html)                                                                   |
| Process Activity                  | icmpshell.sourceforge.net                                                                                                             |
| Process Activity                  | iodine  - dns tunneling - iodine / iodined                                                                                            |
| Process Activity                  | iperf multicast activity (iperf)                                                                                                      |
| Process Activity                  | Ipsec tunnel creation                                                                                                                 |
| Process Activity                  | isnprober technique                                                                                                                   |
| Process Activity                  | Kernel module loaded - Insmod / modprobe activity                                                                                     |
| Process Activity                  | kmod                                                                                                                                  |
| Process Activity                  | lft                                                                                                                                   |
| Process Activity                  | LinEnum                                                                                                                               |
| Process Activity                  | linpmem memory dump                                                                                                                   |
| Process Activity                  | Linux PrivChecker                                                                                                                     |
| Process Activity                  | Local firewall policy mod - Iptables –AID or command OR changes to iptables-config                                                    |
| Process Activity                  | Local firewall rule flush - Iptables –F command                                                                                       |
| Process Activity                  | Local firewall stop - Commands containing string iptables stop                                                                        |
| Process Activity                  | Memory dumping - /dev/mem or /dev/kmem command activity                                                                               |
| Process Activity                  | nemesis (packet creation)                                                                                                             |
| Process Activity                  | Net-SNMP - snmp*                                                                                                                      |
| Process Activity                  | nmap activity                                                                                                                         |
| Process Activity                  | nping activity                                                                                                                        |
| Process Activity                  | nssl - https://sourceforge.net/projects/nssl/                                                                                         |
| Process Activity                  | ntp-fingerprint http://www.hackingciscoexposed.com/?link=tools                                                                        |
| Process Activity                  | p0f                                                                                                                                   |
| Process Activity                  | packit (maybe defunct)                                                                                                                |
| Process Activity                  | Passive asset detection system -pads                                                                                                  |
| Process Activity                  | pf (pfctl)                                                                                                                            |
| Process Activity                  | ping tunnel (ptunnel)                                                                                                                 |
| Process Activity                  | PortPush technique                                                                                                                    |
| Process Activity                  | privilege elevation                                                                                                                   |
| Process Activity                  | process with /etc/passwd arguments                                                                                                    |
| Process Activity                  | python using base64 encoding - python * import base64 *                                                                               |
| Process Activity                  | rm -rf                                                                                                                                |
| Process Activity                  | rootshell piped to tcp device                                                                                                         |
| Process Activity                  | search for writable executables:                                                                                                      |
| Process Activity                  | SearchSploit                                                                                                                          |
| Process Activity                  | shell run from /tmp directory                                                                                                         |
| Process Activity                  | sinfp                                                                                                                                 |
| Process Activity                  | sing                                                                                                                                  |
| Process Activity                  | snmpd                                                                                                                                 |
| Process Activity                  | snmpdelta                                                                                                                             |
| Process Activity                  | snmpdf                                                                                                                                |
| Process Activity                  | snmpget                                                                                                                               |
| Process Activity                  | snmpgetnext                                                                                                                           |
| Process Activity                  | snmpnetstat                                                                                                                           |
| Process Activity                  | snmpset                                                                                                                               |
| Process Activity                  | snmpstatus                                                                                                                            |
| Process Activity                  | snmptable                                                                                                                             |
| Process Activity                  | snmptranslate                                                                                                                         |
| Process Activity                  | snmptrapd                                                                                                                             |
| Process Activity                  | snmpwalk                                                                                                                              |
| Process Activity                  | strace command                                                                                                                        |
| Process Activity                  | suid set on file in /tmp - chmod u+s                                                                                                  |
| Process Activity                  | sysctl command                                                                                                                        |
| Process Activity                  | tcpdump activity                                                                                                                      |
| Process Activity                  | TLs key activity  - *.key                                                                                                             |
| Process Activity                  | udpcast - file transfer over IP multicast (udp-sender)                                                                                |
| Process Activity                  | Unix PrivsecCheck                                                                                                                     |
| Process Activity                  | unprivileged port start config                                                                                                        |
| Process Activity                  | vim persistence                                                                                                                       |
| Process Activity                  | xprobe2                                                                                                                               |
| Shell activity by suspicious user | apache                                                                                                                                |
| Shell activity by suspicious user | bin                                                                                                                                   |
| Shell activity by suspicious user | cdrom                                                                                                                                 |
| Shell activity by suspicious user | console                                                                                                                               |
| Shell activity by suspicious user | daemon                                                                                                                                |
| Shell activity by suspicious user | ftp                                                                                                                                   |
| Shell activity by suspicious user | guest                                                                                                                                 |
| Shell activity by suspicious user | halt                                                                                                                                  |
| Shell activity by suspicious user | info                                                                                                                                  |
| Shell activity by suspicious user | lp                                                                                                                                    |
| Shell activity by suspicious user | mail                                                                                                                                  |
| Shell activity by suspicious user | mysql                                                                                                                                 |
| Shell activity by suspicious user | named                                                                                                                                 |
| Shell activity by suspicious user | nobody                                                                                                                                |
| Shell activity by suspicious user | nogroup                                                                                                                               |
| Shell activity by suspicious user | ossec                                                                                                                                 |
| Shell activity by suspicious user | portmap                                                                                                                               |
| Shell activity by suspicious user | postfix                                                                                                                               |
| Shell activity by suspicious user | psql                                                                                                                                  |
| Shell activity by suspicious user | rpc                                                                                                                                   |
| Shell activity by suspicious user | shell                                                                                                                                 |
| Shell activity by suspicious user | shutdown                                                                                                                              |
| Shell activity by suspicious user | sshd                                                                                                                                  |
| Shell activity by suspicious user | sync                                                                                                                                  |
| Shell activity by suspicious user | user                                                                                                                                  |
| Shell activity by suspicious user | users                                                                                                                                 |
| Shell activity by suspicious user | uucp                                                                                                                                  |
| Shell activity by suspicious user | www                                                                                                                                   |
