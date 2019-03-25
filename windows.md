Windows searches

| Process      | Anomalous Image and CommandLine | Anomalous cmd.exe command                                                            |
|--------------|---------------------------------|--------------------------------------------------------------------------------------|
| Process      | Anomalous Image and CommandLine | Anomalous cmd.exe command                                                            |
| Process      | Anomalous Image and CommandLine | Anomalous cmd.exe command                                                            |
| Process      | Anomalous Image and CommandLine | Anomalous conhost.exe command                                                        |
| Process      | Anomalous Image and CommandLine | Anomalous logman.exe command                                                         |
| Process      | Anomalous Image and CommandLine | Anomalous lsass.exe command                                                          |
| Process      | Anomalous Image and CommandLine | Anomalous svchost.exe command                                                        |
| Process      | Anomalous Image and CommandLine | Anomalous typeperf.exe command                                                       |
| Process      | Anomalous Image and CommandLine | Anomalous WmiApSrv.exe command                                                       |
| Process      | Anomalous Process Activity      | Abnormal lsaiso.exe                                                                  |
| Process      | Anomalous Process Activity      | Abnormal RuntimeBroker.exe                                                           |
| Process      | Anomalous Process Activity      | Abnormal svchost.exe                                                                 |
| Process      | Anomalous Process Activity      | Anomalous at \\host*                                                                 |
| Process      | Anomalous Process Activity      | Anomalous at command activity                                                        |
| Process      | Anomalous Process Activity      | Anomalous host create *                                                              |
| Process      | Anomalous Process Activity      | Anomalous host start *                                                               |
| Process      | Anomalous Process Activity      | Anomalous named pipe activity                                                        |
| Process      | Anomalous Process Activity      | Anomalous net use                                                                    |
| Process      | Anomalous Process Activity      | Anomalous net use command activity                                                   |
| Process      | Anomalous Process Activity      | Anomalous reg add \\host*                                                            |
| Process      | Anomalous Process Activity      | Anomalous remote management activity                                                 |
| Process      | Anomalous Process Activity      | Anomalous sc command activity                                                        |
| Process      | Anomalous Process Activity      | Anomalous sc.exe                                                                     |
| Process      | Anomalous Process Activity      | Anomalous scheduled task creation                                                    |
| Process      | Anomalous Process Activity      | Anomalous schtasks /CREATE*                                                          |
| Process      | Anomalous Process Activity      | Anomalous schtasks command activity                                                  |
| Process      | Anomalous Process Activity      | Anomalous svchost                                                                    |
| Process      | Anomalous Process Activity      | Anomalous system process                                                             |
| Process      | Anomalous Process Activity      | Anomalous winrs command activity                                                     |
| Process      | Anomalous Process Activity      | Anomalous winrs -r:*                                                                 |
| Process      | Anomalous Process Activity      | Anomalous WMI activity                                                               |
| Process      | Anomalous Process Activity      | Anomalous wmic command activity                                                      |
| Process      | Anomalous Process Activity      | Anomalous wmiprvse command activity                                                  |
| Process      | Anomalous Process Activity      | Anomalous wsmprovhost command activity (powershell)                                  |
| Process      | Anomalous Process Activity      | auditpol usage                                                                       |
| Process      | Anomalous Process Activity      | firewall disable                                                                     |
| Process      | Anomalous Process Activity      | Indirect Command Execution                                                           |
| Process      | Anomalous Process Activity      | LSASS Driver                                                                         |
| Process      | Anomalous Process Activity      | Mimikatz DCSynch                                                                     |
| Process      | Anomalous Process Activity      | mimikatz: eventr.data.GrantedAccess is 0x1010 and the targetImage is lsass.exe       |
| Process      | Anomalous Process Activity      | msbuild activity                                                                     |
| Process      | Anomalous Process Activity      | nslookup activity                                                                    |
| Process      | Anomalous Process Activity      | process activity from \local\temp                                                    |
| Process      | Anomalous Process Activity      | process activity from user profile                                                   |
| Process      | Anomalous Process Activity      | process activity from windows directory                                              |
| Process      | Anomalous Process Activity      | process started by cmd.exe                                                           |
| Process      | Anomalous Process Activity      | process started by csrss.exe                                                         |
| Process      | Anomalous Process Activity      | Suspicious svchost                                                                   |
| Process      | Anomalous Process Activity      | system tool not spawned by cmd.exe                                                   |
| Process      | Anomalous Process Activity      | these load a DLL into lsass.exe from %temp%                                          |
| Process      | Anomalous Process Activity      | unusual process handle to lsass.exe                                                  |
| Process      | Anomalous Process Activity      | winscp                                                                               |
| Files        | Collection                      | copy of directory files                                                              |
| Process      | Collection                      | copy of directory files                                                              |
| Logs         | Collection                      | RDP shadowing                                                                        |
| Process      | Collection                      | volume shadow copy of drive C:                                                       |
| Process      | Credential Dumping              | CredsLeaker                                                                          |
| Process      | Credential Dumping              | dumpcreds                                                                            |
| Process      | Credential Dumping              | fgdump www.truesec.se                                                                |
| Process      | Credential Dumping              | gsecdump                                                                             |
| Process      | Credential Dumping              | htool                                                                                |
| Process      | Credential Dumping              | lslass www.truesec.se                                                                |
| Process      | Credential Dumping              | mimikatz                                                                             |
| Process      | Credential Dumping              | minimerberos                                                                         |
| Process      | Credential Dumping              | netscan                                                                              |
| Process      | Credential Dumping              | pass-the-hash-toolkit                                                                |
| Process      | Credential Dumping              | Password dumping                                                                     |
| Process      | Credential Dumping              | procdump                                                                             |
| Process      | Credential Dumping              | psexec                                                                               |
| Process      | Credential Dumping              | PSWtool                                                                              |
| Process      | Credential Dumping              | pwcrack                                                                              |
| Process      | Credential Dumping              | pwdump                                                                               |
| Process      | Credential Dumping              | pwdump7                                                                              |
| Process      | Credential Dumping              | pwdumpx                                                                              |
| Process      | Credential Dumping              | pypkatz                                                                              |
| Process      | Credential Dumping              | WCE                                                                                  |
| Process      | Execution                       | cmd executing a child from a variable                                                |
| Process      | Exploitation                    | dnscmd injection                                                                     |
| Process      | Exploitation                    | File-less meterpreter activity                                                       |
| Process      | Exploitation                    | metrepreter activity                                                                 |
| Process      | Exploitation                    | Obfuscated metasploit shellcode                                                      |
| Exploitation | Explotation                     | requests to sqm.microsoft.com                                                        |
| Process      | Local Network Connections       | anomalous port 102 activity                                                          |
| Process      | Local Network Connections       | anomalous port 110 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 123 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 135 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 137 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 138 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 139                                                                   |
| Process      | Local Network Connections       | anomalous port 143 activity                                                          |
| Process      | Local Network Connections       | anomalous port 25 activity                                                           |
| Process      | Local Network Connections       | Anomalous port 3268 activity                                                         |
| Process      | Local Network Connections       | Anomalous port 3269 activity                                                         |
| Process      | Local Network Connections       | Anomalous port 3389 activity                                                         |
| Process      | Local Network Connections       | anomalous port 3389 activity                                                         |
| Process      | Local Network Connections       | Anomalous port 389 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 42 activity                                                           |
| Process      | Local Network Connections       | anomalous port 443 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 445 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 53 activity                                                           |
| Process      | Local Network Connections       | anomalous port 593 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 593 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 636 activity                                                          |
| Process      | Local Network Connections       | Anomalous port 88 activity                                                           |
| Process      | Local Network Connections       | anomalous port 993 activity                                                          |
| Logs         | Persistence                     | Anomalous RDP login                                                                  |
| Logs         | Persistence                     | Anomalous Windows Management Instrumentation                                         |
| Logs         | Persistence                     | Anomalous Windows Remote Management                                                  |
| Process      | Persistence                     | certutil download                                                                    |
| Process      | Persistence                     | LOLbins                                                                              |
| Files        | Persistence                     | Overwrite of C:\Windows\System32\sethc.exe with cmd.exe                              |
| Process      | Persistence                     | Process Doppleganing                                                                 |
| Process      | Persistence                     | psexec                                                                               |
| Process      | Persistence                     | psexec activity                                                                      |
| Process      | Persistence                     | SecureBoot tampering                                                                 |
| Process      | Persistence                     | web shell activity                                                                   |
| Powershell   | Powershell                      | Powercat technique                                                                   |
| Powershell   | Powershell                      | powershell base64 encoded script                                                     |
| Powershell   | Powershell                      | Powershell Base64 Shellcode                                                          |
| Powershell   | Powershell                      | powershell binary file download                                                      |
| Exploitation | Powershell                      | powershell connect outbound                                                          |
| Powershell   | Powershell                      | powershell creating executable file in Temp directory                                |
| Powershell   | Powershell                      | powershell executed by cmd.exe                                                       |
| Powershell   | Powershell                      | powershell execution from temp folder                                                |
| Powershell   | Powershell                      | Powershell in-memory injection using certutil                                        |
| Powershell   | Powershell                      | Powershell password access                                                           |
| Powershell   | Powershell                      | powershell remote connection                                                         |
| Powershell   | Powershell                      | Powershell script from temp directory                                                |
| Powershell   | Powershell                      | powershell scripts using WMI                                                         |
| Process      | Powershell                      | powershell started by office app                                                     |
| Powershell   | Powershell                      | powershell started by Outlook                                                        |
| Powershell   | Powershell                      | Powershell using HTTP                                                                |
| Powershell   | Powershell                      | Powershell using RPC                                                                 |
| Process      | Powershell                      | process activity from downloads directory                                            |
| Process      | Powershell                      | vbscript spawned by powershell                                                       |
| Powershell   | Powershell                      | WMI calling powershell                                                               |
| Process      | Remote Network Connections      | Anomalous acrobat.exe activity                                                       |
| Process      | Remote Network Connections      | Anomalous adobe_licutil.exe activity                                                 |
| Process      | Remote Network Connections      | Anomalous AdobeARM.exe activity                                                      |
| Process      | Remote Network Connections      | Anomalous AdobeGCClient.exe activity                                                 |
| Process      | Remote Network Connections      | Anomalous CompatTelRunner.exe activity                                               |
| Process      | Remote Network Connections      | Anomalous dns activity                                                               |
| Process      | Remote Network Connections      | Anomalous dropbox.exe activity                                                       |
| Process      | Remote Network Connections      | Anomalous DropboxUpdate                                                              |
| Process      | Remote Network Connections      | Anomalous excel.exe activity                                                         |
| Process      | Remote Network Connections      | Anomalous explorer activity                                                          |
| Process      | Remote Network Connections      | Anomalous g2mupdate.exe activity                                                     |
| Process      | Remote Network Connections      | Anomalous lsass  activity                                                            |
| Process      | Remote Network Connections      | Anomalous lync.exe activity                                                          |
| Process      | Remote Network Connections      | Anomalous MpCmdRun activity                                                          |
| Process      | Remote Network Connections      | Anomalous MRT.exe activity                                                           |
| Process      | Remote Network Connections      | Anomalous Notepad updater                                                            |
| Process      | Remote Network Connections      | Anomalous outlook.exe activity                                                       |
| Process      | Remote Network Connections      | Anomalous powerpoint.exe activity                                                    |
| Process      | Remote Network Connections      | Anomalous SIHClient.exe.exe activity                                                 |
| Process      | Remote Network Connections      | Anomalous svchost activity                                                           |
| Process      | Remote Network Connections      | Anomalous System activity                                                            |
| Process      | Remote Network Connections      | Anomalous TeamViewer_Service.exe activity                                            |
| Process      | Remote Network Connections      | Anomalous winword.exe activity                                                       |
| Process      | Suspicious User Activity        | ammyy.exe                                                                            |
| Process      | Suspicious User Activity        | arp –a                                                                               |
| Process      | Suspicious User Activity        | at                                                                                   |
| Process      | Suspicious User Activity        | bruter.exe                                                                           |
| Process      | Suspicious User Activity        | cachedump.exe                                                                        |
| Process      | Suspicious User Activity        | cmd /c dir "c:\docume~1\<CurrentUser>\desktop" /od                                   |
| Process      | Suspicious User Activity        | cmd /c dir “c:\docume~1\<CurrentUser>\recent” /od                                    |
| Process      | Suspicious User Activity        | cmd /c dir c:\docume~1\                                                              |
| Process      | Suspicious User Activity        | cmd /c dir c:\progra~1\                                                              |
| Process      | Suspicious User Activity        | cmd /c net start                                                                     |
| Process      | Suspicious User Activity        | cmd /c net use                                                                       |
| Process      | Suspicious User Activity        | cmd /c netstat –n                                                                    |
| Process      | Suspicious User Activity        | csvde.exe                                                                            |
| Process      | Suspicious User Activity        | curl.exe                                                                             |
| Process      | Suspicious User Activity        | dir systemdrive\Users\*.*                                                            |
| Process      | Suspicious User Activity        | dir userprofile\AppData\Roaming\Microsoft\Windows\Recent\*.*                         |
| Process      | Suspicious User Activity        | dir userprofile\Desktop\*.*                                                          |
| Process      | Suspicious User Activity        | dumpel.exe                                                                           |
| Process      | Suspicious User Activity        | dumpsec.exe                                                                          |
| Process      | Suspicious User Activity        | find.exe                                                                             |
| Process      | Suspicious User Activity        | gpresult                                                                             |
| Process      | Suspicious User Activity        | gpresult /z                                                                          |
| Process      | Suspicious User Activity        | gpresult.exe                                                                         |
| Process      | Suspicious User Activity        | gsecdump.exe                                                                         |
| Process      | Suspicious User Activity        | hostname                                                                             |
| Process      | Suspicious User Activity        | ipconfig /all                                                                        |
| Process      | Suspicious User Activity        | ipconfig.exe                                                                         |
| Process      | Suspicious User Activity        | lazagne.exe                                                                          |
| Process      | Suspicious User Activity        | mimikatz.exe                                                                         |
| Process      | Suspicious User Activity        | msdtc [IP] [port]                                                                    |
| Process      | Suspicious User Activity        | nc.exe                                                                               |
| Process      | Suspicious User Activity        | net localgroup                                                                       |
| Process      | Suspicious User Activity        | net share                                                                            |
| Process      | Suspicious User Activity        | net start                                                                            |
| Process      | Suspicious User Activity        | net use                                                                              |
| Process      | Suspicious User Activity        | net user /domain                                                                     |
| Process      | Suspicious User Activity        | net user administrator                                                               |
| Process      | Suspicious User Activity        | net user administrator /domain                                                       |
| Process      | Suspicious User Activity        | net view                                                                             |
| Process      | Suspicious User Activity        | net view                                                                             |
| Process      | Suspicious User Activity        | net view                                                                             |
| Process      | Suspicious User Activity        | net view /domain                                                                     |
| Process      | Suspicious User Activity        | net view /domain                                                                     |
| Process      | Suspicious User Activity        | net.exe                                                                              |
| Process      | Suspicious User Activity        | netcat.exe                                                                           |
| Process      | Suspicious User Activity        | netsh                                                                                |
| Process      | Suspicious User Activity        | netsh.exe                                                                            |
| Process      | Suspicious User Activity        | netstat -ano | find \TCP\                                                            |
| Process      | Suspicious User Activity        | netstat -nao                                                                         |
| Process      | Suspicious User Activity        | netstat.exe                                                                          |
| Process      | Suspicious User Activity        | ping www.google.com                                                                  |
| Process      | Suspicious User Activity        | powershell.exe                                                                       |
| Process      | Suspicious User Activity        | psexec.exe                                                                           |
| Process      | Suspicious User Activity        | pwdump                                                                               |
| Process      | Suspicious User Activity        | query user                                                                           |
| Process      | Suspicious User Activity        | query user                                                                           |
| Process      | Suspicious User Activity        | query.exe                                                                            |
| Process      | Suspicious User Activity        | quser                                                                                |
| Process      | Suspicious User Activity        | rar.exe                                                                              |
| Process      | Suspicious User Activity        | rdpclip.exe                                                                          |
| Process      | Suspicious User Activity        | reg query \"HKCU\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Internet Settings\"  |
| Process      | Suspicious User Activity        | route                                                                                |
| Process      | Suspicious User Activity        | sc.exe                                                                               |
| Process      | Suspicious User Activity        | sc.exe                                                                               |
| Process      | Suspicious User Activity        | sdelete.exe                                                                          |
| Process      | Suspicious User Activity        | systeminfo                                                                           |
| Process      | Suspicious User Activity        | systeminfo.exe                                                                       |
| Process      | Suspicious User Activity        | tasklist                                                                             |
| Process      | Suspicious User Activity        | tasklist /fi                                                                         |
| Process      | Suspicious User Activity        | tasklist /svc                                                                        |
| Process      | Suspicious User Activity        | tasklist /v                                                                          |
| Process      | Suspicious User Activity        | tasklist.exe                                                                         |
| Process      | Suspicious User Activity        | teamviewer.exe                                                                       |
| Process      | Suspicious User Activity        | ver                                                                                  |
| Process      | Suspicious User Activity        | vnc                                                                                  |
| Process      | Suspicious User Activity        | wce.exe                                                                              |
| Process      | Suspicious User Activity        | wget.exe                                                                             |
| Process      | Suspicious User Activity        | whoami                                                                               |
| Process      | Suspicious User Activity        | whoami                                                                               |
| Process      | Suspicious User Activity        | whoami.exe                                                                           |
| Process      | Suspicious User Activity        | winscanx.exe                                                                         |
| Process      | Suspicious User Activity        | wmic.exe                                                                             |
| Process      | Sysmon subversion               | %*%.exe                                                                              |
| Process      | Sysmon subversion               | Renamed image                                                                        |
| Process      | Sysmon subversion               | sysmon process errors                                                                |
| Process      | Sysmon subversion               | sysmon process errors                                                                |
| Process      | Sysmon subversion               | Sysmon subversion                                                                    |
| Logs         |                                 | 3033 / 3063 lsass protection events                                                  |
| Logs         |                                 | 3033 / 3063 lsass protection events                                                  |
| Logs         |                                 | 3065 / 3066 Llsass auditing events                                                   |
| Logs         |                                 | 3065 / 3066 Llsass auditing events                                                   |
| Logs         |                                 | 4013 (powershell events)                                                             |
| Logs         |                                 | 4648: using other’s creds - runas or impersonation                                   |
| Logs         |                                 | 4722 adding local admin                                                              |
| Logs         |                                 | 4776 bad logins - kerberos                                                           |
| Logs         |                                 | 4798 - user local group membership enumerated                                        |
| Logs         |                                 | 4798 - user local group membership enumerated                                        |
| Logs         |                                 | abnormal path                                                                        |
| Logs         |                                 | AD: backdoor using service principal name                                            |
| Logs         |                                 | AD: backdoor via delegation                                                          |
| Logs         |                                 | AD: enabling more efficient hash cracking (sigma)                                    |
| Logs         |                                 | AD: right to control all users (sigma)                                               |
| Logs         |                                 | anomalous network share access                                                       |
| Logs         |                                 | anomalous network share creation                                                     |
| Process      |                                 | Bloodhound                                                                           |
| Logs         |                                 | broadcast name resolution poisoning (like WPAD)                                      |
| Logs         |                                 | clearing firewall logs                                                               |
| Process      |                                 | cmake activitry                                                                      |
| Process      |                                 | cmd prompt internal command activity                                                 |
| Process      |                                 | Cobalt strike                                                                        |
| Process      |                                 | CradleCrafter                                                                        |
| Logs         |                                 | creating backup policy                                                               |
| Process      |                                 | Empire                                                                               |
| Logs         |                                 | event 8001 in WLAN autoconfig                                                        |
| Logs         |                                 | Gold and silver tickets                                                              |
| Logs         |                                 | Install Root Certificate                                                             |
|              |                                 | Kerberoasting                                                                        |
| Logs         |                                 | large number of DNSSEC requests from one source                                      |
| Logs         |                                 | log tampering - stop or deletes                                                      |
| Logs         |                                 | non-admin system configuration                                                       |
| Process      |                                 | py2exe activity                                                                      |
| Process      |                                 | Ranger                                                                               |
| Process      |                                 | sc.exe activity by a user                                                            |
| Logs         |                                 | scheduled task creation                                                              |
| Logs         |                                 | Scheduled Task on DC                                                                 |
| Logs         |                                 | Scheduled Task on DC                                                                 |
| Process      |                                 | Sharesniffer                                                                         |
| Process      |                                 | SharpPack techniques                                                                 |
| Logs         |                                 | Suspicious 4648 event                                                                |
| Logs         |                                 | Suspicious 4648 event                                                                |
| Files        |                                 | System32 and SysWoW64 folder file creates                                            |
| Logs         |                                 | Unhandled malware event - Left alone or Leave alone (log only)                       |
| Process      |                                 | WES technique                                                                        |
| Logs         |                                 | windows defender detect                                                              |
| Logs         |                                 | WMI activity                                                                         |
| Logs         |                                 | WMI lateral movement                                                                 |
| Logs         |                                 | WMI lateral movement                                                                 |
| Logs         |                                 | zone transfer denied                                                                 |
| Logs         |                                 | zone transfer succeeded                                                              |
