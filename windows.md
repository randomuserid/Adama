Windows event searches - some use event logs and some need sysmon data

| Event Type | Category                        | Description                                                                    |
|------------|---------------------------------|--------------------------------------------------------------------------------|
| Process    | Explotation                     | requests to sqm.microsoft.com                                                  |
| Process    | Powershell                      | powershell connect outbound                                                    |
| Files      | Collection                      | copy of directory files                                                        |
| Files      | Persistence                     | Overwrite of C:\Windows\System32\sethc.exe with cmd.exe                        |
| Files      | Persistence                     | System32 and SysWoW64 folder file creates                                      |
| Logs       | Collection                      | RDP shadowing                                                                  |
| Logs       | Persistence                     | Anomalous RDP login                                                            |
| Logs       | Persistence                     | Anomalous Windows Management Instrumentation                                   |
| Logs       | Persistence                     | Anomalous Windows Remote Management                                            |
| Logs       | tbd                             | 3033 / 3063 lsass protection events                                            |
| Logs       | tbd                             | 3033 / 3063 lsass protection events                                            |
| Logs       | tbd                             | 3065 / 3066 Llsass auditing events                                             |
| Logs       | tbd                             | 3065 / 3066 Llsass auditing events                                             |
| Logs       | tbd                             | 4013 (powershell events)                                                       |
| Logs       | tbd                             | 4648: using other’s creds - runas or impersonation                             |
| Logs       | tbd                             | 4722 adding local admin                                                        |
| Logs       | tbd                             | 4776 bad logins - kerberos                                                     |
| Logs       | tbd                             | 4798 - user local group membership enumerated                                  |
| Logs       | tbd                             | 4798 - user local group membership enumerated                                  |
| Logs       | tbd                             | abnormal path                                                                  |
| Logs       | tbd                             | AD: backdoor using service principal name                                      |
| Logs       | tbd                             | AD: backdoor via delegation                                                    |
| Logs       | tbd                             | AD: enabling more efficient hash cracking (sigma)                              |
| Logs       | tbd                             | AD: right to control all users (sigma)                                         |
| Logs       | tbd                             | anomalous network share access                                                 |
| Logs       | tbd                             | anomalous network share creation                                               |
| Logs       | tbd                             | broadcast name resolution poisoning (like WPAD)                                |
| Logs       | tbd                             | clearing firewall logs                                                         |
| Logs       | tbd                             | creating backup policy                                                         |
| Logs       | tbd                             | event 8001 in WLAN autoconfig                                                  |
| Logs       | tbd                             | Gold and silver tickets                                                        |
| Logs       | tbd                             | Install Root Certificate                                                       |
| Logs       | tbd                             | large number of DNSSEC requests from one source                                |
| Logs       | tbd                             | log tampering - stop or deletes                                                |
| Logs       | tbd                             | non-admin system configuration                                                 |
| Logs       | tbd                             | scheduled task creation                                                        |
| Logs       | tbd                             | Scheduled Task on DC                                                           |
| Logs       | tbd                             | Scheduled Task on DC                                                           |
| Logs       | tbd                             | Suspicious 4648 event                                                          |
| Logs       | tbd                             | Suspicious 4648 event                                                          |
| Logs       | tbd                             | Unhandled malware event - Left alone or Leave alone (log only)                 |
| Logs       | tbd                             | windows defender detect                                                        |
| Logs       | tbd                             | WMI activity                                                                   |
| Logs       | tbd                             | WMI lateral movement                                                           |
| Logs       | tbd                             | WMI lateral movement                                                           |
| Logs       | tbd                             | zone transfer denied                                                           |
| Logs       | tbd                             | zone transfer succeeded                                                        |
| Powershell | Powershell                      | Powercat technique                                                             |
| Powershell | Powershell                      | powershell base64 encoded script                                               |
| Powershell | Powershell                      | Powershell Base64 Shellcode                                                    |
| Powershell | Powershell                      | powershell binary file download                                                |
| Powershell | Powershell                      | powershell creating executable file in Temp directory                          |
| Powershell | Powershell                      | powershell executed by cmd.exe                                                 |
| Powershell | Powershell                      | powershell execution from temp folder                                          |
| Powershell | Powershell                      | Powershell in-memory injection using certutil                                  |
| Powershell | Powershell                      | Powershell password access                                                     |
| Powershell | Powershell                      | powershell remote connection                                                   |
| Powershell | Powershell                      | Powershell script from temp directory                                          |
| Powershell | Powershell                      | powershell scripts using WMI                                                   |
| Powershell | Powershell                      | powershell started by Outlook                                                  |
| Powershell | Powershell                      | Powershell using HTTP                                                          |
| Powershell | Powershell                      | Powershell using RPC                                                           |
| Powershell | Powershell                      | WMI calling powershell                                                         |
| Process    | Anomalous Image and CommandLine | Anomalous cmd.exe command                                                      |
| Process    | Anomalous Image and CommandLine | Anomalous cmd.exe command                                                      |
| Process    | Anomalous Image and CommandLine | Anomalous cmd.exe command                                                      |
| Process    | Anomalous Image and CommandLine | Anomalous conhost.exe command                                                  |
| Process    | Anomalous Image and CommandLine | Anomalous logman.exe command                                                   |
| Process    | Anomalous Image and CommandLine | Anomalous lsass.exe command                                                    |
| Process    | Anomalous Image and CommandLine | Anomalous svchost.exe command                                                  |
| Process    | Anomalous Image and CommandLine | Anomalous typeperf.exe command                                                 |
| Process    | Anomalous Image and CommandLine | Anomalous WmiApSrv.exe command                                                 |
| Process    | Anomalous Process Activity      | Abnormal lsaiso.exe                                                            |
| Process    | Anomalous Process Activity      | Abnormal RuntimeBroker.exe                                                     |
| Process    | Anomalous Process Activity      | Abnormal svchost.exe                                                           |
| Process    | Anomalous Process Activity      | Anomalous at \\host*                                                           |
| Process    | Anomalous Process Activity      | Anomalous at command activity                                                  |
| Process    | Anomalous Process Activity      | Anomalous host create *                                                        |
| Process    | Anomalous Process Activity      | Anomalous host start *                                                         |
| Process    | Anomalous Process Activity      | Anomalous named pipe activity                                                  |
| Process    | Anomalous Process Activity      | Anomalous net use                                                              |
| Process    | Anomalous Process Activity      | Anomalous net use command activity                                             |
| Process    | Anomalous Process Activity      | Anomalous reg add \\host*                                                      |
| Process    | Anomalous Process Activity      | Anomalous remote management activity                                           |
| Process    | Anomalous Process Activity      | Anomalous sc command activity                                                  |
| Process    | Anomalous Process Activity      | Anomalous sc.exe                                                               |
| Process    | Anomalous Process Activity      | Anomalous scheduled task creation                                              |
| Process    | Anomalous Process Activity      | Anomalous schtasks /CREATE*                                                    |
| Process    | Anomalous Process Activity      | Anomalous schtasks command activity                                            |
| Process    | Anomalous Process Activity      | Anomalous svchost                                                              |
| Process    | Anomalous Process Activity      | Anomalous system process                                                       |
| Process    | Anomalous Process Activity      | Anomalous winrs command activity                                               |
| Process    | Anomalous Process Activity      | Anomalous winrs -r:*                                                           |
| Process    | Anomalous Process Activity      | Anomalous WMI activity                                                         |
| Process    | Anomalous Process Activity      | Anomalous wmic command activity                                                |
| Process    | Anomalous Process Activity      | Anomalous wmiprvse command activity                                            |
| Process    | Anomalous Process Activity      | Anomalous wsmprovhost command activity (powershell)                            |
| Process    | Anomalous Process Activity      | auditpol usage                                                                 |
| Process    | Anomalous Process Activity      | firewall disable                                                               |
| Process    | Anomalous Process Activity      | Indirect Command Execution                                                     |
| Process    | Anomalous Process Activity      | LSASS Driver                                                                   |
| Process    | Anomalous Process Activity      | Mimikatz DCSynch                                                               |
| Process    | Anomalous Process Activity      | mimikatz: eventr.data.GrantedAccess is 0x1010 and the targetImage is lsass.exe |
| Process    | Anomalous Process Activity      | msbuild activity                                                               |
| Process    | Anomalous Process Activity      | nslookup activity                                                              |
| Process    | Anomalous Process Activity      | process activity from \local\temp                                              |
| Process    | Anomalous Process Activity      | process activity from user profile                                             |
| Process    | Anomalous Process Activity      | process activity from windows directory                                        |
| Process    | Anomalous Process Activity      | process started by cmd.exe                                                     |
| Process    | Anomalous Process Activity      | process started by csrss.exe                                                   |
| Process    | Anomalous Process Activity      | Suspicious svchost                                                             |
| Process    | Anomalous Process Activity      | system tool not spawned by cmd.exe                                             |
| Process    | Anomalous Process Activity      | these load a DLL into lsass.exe from %temp%                                    |
| Process    | Anomalous Process Activity      | unusual process handle to lsass.exe                                            |
| Process    | Anomalous Process Activity      | winscp                                                                         |
| Process    | Collection                      | copy of directory files                                                        |
| Process    | Collection                      | volume shadow copy of drive C:                                                 |
| Process    | Credential Dumping              | CredsLeaker                                                                    |
| Process    | Credential Dumping              | dumpcreds                                                                      |
| Process    | Credential Dumping              | fgdump www.truesec.se                                                          |
| Process    | Credential Dumping              | gsecdump                                                                       |
| Process    | Credential Dumping              | htool                                                                          |
| Process    | Credential Dumping              | lslass www.truesec.se                                                          |
| Process    | Credential Dumping              | mimikatz                                                                       |
| Process    | Credential Dumping              | minimerberos                                                                   |
| Process    | Credential Dumping              | netscan                                                                        |
| Process    | Credential Dumping              | pass-the-hash-toolkit                                                          |
| Process    | Credential Dumping              | Password dumping                                                               |
| Process    | Credential Dumping              | procdump                                                                       |
| Process    | Credential Dumping              | psexec                                                                         |
| Process    | Credential Dumping              | PSWtool                                                                        |
| Process    | Credential Dumping              | pwcrack                                                                        |
| Process    | Credential Dumping              | pwdump                                                                         |
| Process    | Credential Dumping              | pwdump7                                                                        |
| Process    | Credential Dumping              | pwdumpx                                                                        |
| Process    | Credential Dumping              | pypkatz                                                                        |
| Process    | Credential Dumping              | WCE                                                                            |
| Process    | Execution                       | cmd executing a child from a variable                                          |
| Process    | Exploitation                    | dnscmd injection                                                               |
| Process    | Exploitation                    | File-less meterpreter activity                                                 |
| Process    | Exploitation                    | metrepreter activity                                                           |
| Process    | Exploitation                    | Obfuscated metasploit shellcode                                                |
| Process    | Local Network Connections       | anomalous port 102 activity                                                    |
| Process    | Local Network Connections       | anomalous port 110 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 123 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 135 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 137 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 138 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 139                                                             |
| Process    | Local Network Connections       | anomalous port 143 activity                                                    |
| Process    | Local Network Connections       | anomalous port 25 activity                                                     |
| Process    | Local Network Connections       | Anomalous port 3268 activity                                                   |
| Process    | Local Network Connections       | Anomalous port 3269 activity                                                   |
| Process    | Local Network Connections       | Anomalous port 3389 activity                                                   |
| Process    | Local Network Connections       | anomalous port 3389 activity                                                   |
| Process    | Local Network Connections       | Anomalous port 389 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 42 activity                                                     |
| Process    | Local Network Connections       | anomalous port 443 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 445 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 53 activity                                                     |
| Process    | Local Network Connections       | anomalous port 593 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 593 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 636 activity                                                    |
| Process    | Local Network Connections       | Anomalous port 88 activity                                                     |
| Process    | Local Network Connections       | anomalous port 993 activity                                                    |
| Process    | Persistence                     | certutil download                                                              |
| Process    | Persistence                     | LOLbins                                                                        |
| Process    | Persistence                     | Process Doppleganing                                                           |
| Process    | Persistence                     | psexec                                                                         |
| Process    | Persistence                     | psexec activity                                                                |
| Process    | Persistence                     | SecureBoot tampering                                                           |
| Process    | Persistence                     | web shell activity                                                             |
| Process    | Powershell                      | powershell started by office app                                               |
| Process    | Powershell                      | process activity from downloads directory                                      |
| Process    | Powershell                      | vbscript spawned by powershell                                                 |
| Process    | Remote Network Connections      | Anomalous acrobat.exe activity                                                 |
| Process    | Remote Network Connections      | Anomalous adobe_licutil.exe activity                                           |
| Process    | Remote Network Connections      | Anomalous AdobeARM.exe activity                                                |
| Process    | Remote Network Connections      | Anomalous AdobeGCClient.exe activity                                           |
| Process    | Remote Network Connections      | Anomalous CompatTelRunner.exe activity                                         |
| Process    | Remote Network Connections      | Anomalous dns activity                                                         |
| Process    | Remote Network Connections      | Anomalous dropbox.exe activity                                                 |
| Process    | Remote Network Connections      | Anomalous DropboxUpdate                                                        |
| Process    | Remote Network Connections      | Anomalous excel.exe activity                                                   |
| Process    | Remote Network Connections      | Anomalous explorer activity                                                    |
| Process    | Remote Network Connections      | Anomalous g2mupdate.exe activity                                               |
| Process    | Remote Network Connections      | Anomalous lsass  activity                                                      |
| Process    | Remote Network Connections      | Anomalous lync.exe activity                                                    |
| Process    | Remote Network Connections      | Anomalous MpCmdRun activity                                                    |
| Process    | Remote Network Connections      | Anomalous MRT.exe activity                                                     |
| Process    | Remote Network Connections      | Anomalous Notepad updater                                                      |
| Process    | Remote Network Connections      | Anomalous outlook.exe activity                                                 |
| Process    | Remote Network Connections      | Anomalous powerpoint.exe activity                                              |
| Process    | Remote Network Connections      | Anomalous SIHClient.exe.exe activity                                           |
| Process    | Remote Network Connections      | Anomalous svchost activity                                                     |
| Process    | Remote Network Connections      | Anomalous System activity                                                      |
| Process    | Remote Network Connections      | Anomalous TeamViewer_Service.exe activity                                      |
| Process    | Remote Network Connections      | Anomalous winword.exe activity                                                 |
| Process    | Sysmon subversion               | %*%.exe                                                                        |
| Process    | Sysmon subversion               | Renamed image                                                                  |
| Process    | Sysmon subversion               | sysmon process errors                                                          |
| Process    | Sysmon subversion               | sysmon process errors                                                          |
| Process    | Sysmon subversion               | Sysmon subversion                                                              |
| Process    | tbd                             | Bloodhound                                                                     |
| Process    | tbd                             | cmake activitry                                                                |
| Process    | tbd                             | cmd prompt internal command activity                                           |
| Process    | tbd                             | Cobalt strike                                                                  |
| Process    | tbd                             | CradleCrafter                                                                  |
| Process    | tbd                             | Empire                                                                         |
| Process    | tbd                             | py2exe activity                                                                |
| Process    | tbd                             | Ranger                                                                         |
| Process    | tbd                             | sc.exe activity by a user                                                      |
| Process    | tbd                             | Sharesniffer                                                                   |
| Process    | tbd                             | SharpPack techniques                                                           |
| Process    | tbd                             | WES technique                                                                  |
| Process    | tbd                             | wmic query                                                                     |
| Process    | tbd                             | Kerberoasting                                                                  |
