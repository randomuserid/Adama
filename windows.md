Windows event searches - some use event logs and some need sysmon data

| Event Type | Category                        | Description                                                                    |
|------------|---------------------------------|--------------------------------------------------------------------------------|
| Process    | Sysmon subversion               | %*%.exe                                                                        |
| Process    | Anomalous Process Activity      | 0phcrack activity                                                              |
| Logs       | tbd                             | 3033 / 3063 lsass protection events                                            |
| Logs       | tbd                             | 3033 / 3063 lsass protection events                                            |
| Logs       | tbd                             | 3065 / 3066 Llsass auditing events                                             |
| Logs       | tbd                             | 4013 (powershell events)                                                       |
| Logs       | tbd                             | 4648: using other’s creds - runas or impersonation                             |
| Logs       | tbd                             | 4722 adding local admin                                                        |
| Logs       | tbd                             | 4776 bad logins - kerberos                                                     |
| Logs       | tbd                             | 4798 - user local group membership enumerated                                  |
| Process    | Anomalous Process Activity      | Abnormal lsaiso.exe                                                            |
| Logs       | tbd                             | abnormal path                                                                  |
| Process    | Anomalous Process Activity      | Abnormal RuntimeBroker.exe                                                     |
| Process    | Anomalous Process Activity      | Abnormal svchost.exe                                                           |
| Logs       | tbd                             | AD: backdoor using service principal name                                      |
| Logs       | tbd                             | AD: backdoor via delegation                                                    |
| Logs       | tbd                             | AD: enabling more efficient hash cracking (sigma)                              |
| Logs       | tbd                             | AD: right to control all users (sigma)                                         |
| Process    | Remote Network Connections      | Anomalous acrobat.exe activity                                                 |
| Process    | Remote Network Connections      | Anomalous adobe_licutil.exe activity                                           |
| Process    | Remote Network Connections      | Anomalous AdobeARM.exe activity                                                |
| Process    | Remote Network Connections      | Anomalous AdobeGCClient.exe activity                                           |
| Process    | Anomalous Process Activity      | Anomalous at \\host*                                                           |
| Process    | Anomalous Process Activity      | Anomalous at command activity                                                  |
| Process    | Anomalous Image and CommandLine | Anomalous cmd.exe command                                                      |
| Process    | Anomalous Image and CommandLine | Anomalous cmd.exe command                                                      |
| Process    | Anomalous Image and CommandLine | Anomalous cmd.exe command                                                      |
| Process    | Remote Network Connections      | Anomalous CompatTelRunner.exe activity                                         |
| Process    | Anomalous Image and CommandLine | Anomalous conhost.exe command                                                  |
| Process    | Remote Network Connections      | Anomalous dns activity                                                         |
| Process    | Remote Network Connections      | Anomalous dropbox.exe activity                                                 |
| Process    | Remote Network Connections      | Anomalous DropboxUpdate                                                        |
| Process    | Remote Network Connections      | Anomalous excel.exe activity                                                   |
| Process    | Remote Network Connections      | Anomalous explorer activity                                                    |
| Process    | Remote Network Connections      | Anomalous g2mupdate.exe activity                                               |
| Process    | Anomalous Process Activity      | Anomalous host create *                                                        |
| Process    | Anomalous Process Activity      | Anomalous host start *                                                         |
| Process    | Anomalous Image and CommandLine | Anomalous logman.exe command                                                   |
| Process    | Remote Network Connections      | Anomalous lsass  activity                                                      |
| Process    | Anomalous Image and CommandLine | Anomalous lsass.exe command                                                    |
| Process    | Remote Network Connections      | Anomalous lync.exe activity                                                    |
| Process    | Remote Network Connections      | Anomalous MpCmdRun activity                                                    |
| Process    | Remote Network Connections      | Anomalous MRT.exe activity                                                     |
| Process    | Anomalous Process Activity      | Anomalous named pipe activity                                                  |
| Process    | Anomalous Process Activity      | Anomalous nbtstat activity                                                     |
| Process    | Anomalous Process Activity      | Anomalous net command activity                                                 |
| Process    | Anomalous Process Activity      | Anomalous net localgroup command                                               |
| Process    | Anomalous Process Activity      | Anomalous net start command                                                    |
| Process    | Anomalous Process Activity      | Anomalous net use command activity                                             |
| Process    | Anomalous Process Activity      | Anomalous net user command                                                     |
| Process    | Anomalous Process Activity      | Anomalous netsh activity                                                       |
| Logs       | tbd                             | anomalous network share access                                                 |
| Logs       | tbd                             | anomalous network share creation                                               |
| Process    | Remote Network Connections      | Anomalous Notepad updater                                                      |
| Process    | Remote Network Connections      | Anomalous outlook.exe activity                                                 |
| Process    | Anomalous Process Activity      | Anomalous pkgmgr activity                                                      |
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
| Process    | Remote Network Connections      | Anomalous powerpoint.exe activity                                              |
| Logs       | Persistence                     | Anomalous RDP login                                                            |
| Process    | Anomalous Process Activity      | Anomalous reg add \\host*                                                      |
| Process    | Anomalous Process Activity      | Anomalous reg import                                                           |
| Process    | Anomalous Process Activity      | Anomalous remote management activity                                           |
| Process    | Anomalous Process Activity      | Anomalous sc command activity                                                  |
| Process    | Anomalous Process Activity      | Anomalous scheduled task creation                                              |
| Process    | Anomalous Process Activity      | Anomalous schtasks /CREATE*                                                    |
| Process    | Anomalous Process Activity      | Anomalous schtasks command activity                                            |
| Process    | Remote Network Connections      | Anomalous SIHClient.exe.exe activity                                           |
| Process    | Anomalous Process Activity      | Anomalous svchost                                                              |
| Process    | Remote Network Connections      | Anomalous svchost activity                                                     |
| Process    | Anomalous Image and CommandLine | Anomalous svchost.exe command                                                  |
| Process    | Remote Network Connections      | Anomalous System activity                                                      |
| Process    | Anomalous Process Activity      | Anomalous system process                                                       |
| Process    | Anomalous Process Activity      | Anomalous tasklist activity                                                    |
| Process    | Remote Network Connections      | Anomalous TeamViewer_Service.exe activity                                      |
| Process    | Anomalous Image and CommandLine | Anomalous typeperf.exe command                                                 |
| Logs       | Persistence                     | Anomalous Windows Management Instrumentation                                   |
| Process    | Anomalous Process Activity      | Anomalous winrs command activity                                               |
| Process    | Anomalous Process Activity      | Anomalous winrs -r:*                                                           |
| Process    | Remote Network Connections      | Anomalous winword.exe activity                                                 |
| Process    | Anomalous Process Activity      | Anomalous WMI activity                                                         |
| Process    | Anomalous Image and CommandLine | Anomalous WmiApSrv.exe command                                                 |
| Process    | Anomalous Process Activity      | Anomalous wmic command activity                                                |
| Process    | Anomalous Process Activity      | Anomalous wmiprvse command activity                                            |
| Process    | Anomalous Process Activity      | Anomalous wsmprovhost command activity (powershell)                            |
| Registry   | tbd                             | AppInit_DLLs Value kb # 197571                                                 |
| Process    | Anomalous Process Activity      | auditpol usage                                                                 |
| Process    | tbd                             | Bloodhound                                                                     |
| Logs       | tbd                             | broadcast name resolution poisoning (like WPAD)                                |
| Process    | Anomalous Process Activity      | cacls.exe activity                                                             |
| Process    | Persistence                     | certutil download                                                              |
| Logs       | tbd                             | clearing firewall logs                                                         |
| Process    | tbd                             | cmake activitry                                                                |
| Process    | Execution                       | cmd executing a child from a variable                                          |
| Process    | tbd                             | cmd prompt internal command activity                                           |
| Process    | tbd                             | Cobalt strike                                                                  |
| Registry   | tbd                             | Command Procesor autorun key                                                   |
| Files      | Collection                      | copy of directory files                                                        |
| Process    | Collection                      | copy of directory files                                                        |
| Process    | tbd                             | CradleCrafter                                                                  |
| Logs       | tbd                             | creating backup policy                                                         |
| Process    | Credential Dumping              | CredsLeaker                                                                    |
| Process    | Exploitation                    | dnscmd injection                                                               |
| Process    | Anomalous Process Activity      | Doo Vmware detection script                                                    |
| Process    | Anomalous Process Activity      | doo.vbs VMware fingerprinter                                                   |
| Process    | Credential Dumping              | dumpcreds                                                                      |
| Process    | Credential Dumping              | DumpSec                                                                        |
| Process    | tbd                             | Empire                                                                         |
| Process    | Anomalous Process Activity      | enum                                                                           |
| Logs       | tbd                             | event 8001 in WLAN autoconfig                                                  |
| Logs       | tbd                             | event log service stopped                                                      |
| Registry   | tbd                             | exefile shell open command activity                                            |
| Process    | Credential Dumping              | fgdump www.truesec.se                                                          |
| Process    | Exploitation                    | File-less meterpreter activity                                                 |
| Process    | Anomalous Process Activity      | firewall disable                                                               |
| Process    | Anomalous Process Activity      | fport                                                                          |
| Process    | Anomalous Process Activity      | FTK Imager                                                                     |
| Logs       | tbd                             | Gold and silver tickets                                                        |
| Process    | Credential Dumping              | gsecdump                                                                       |
| Process    | Credential Dumping              | htool                                                                          |
| Process    | Anomalous Process Activity      | HTTPort                                                                        |
| Registry   | tbd                             | Image File Execution key                                                       |
| Process    | Anomalous Process Activity      | Indirect Command Execution                                                     |
| Logs       | tbd                             | Install Root Certificate                                                       |
| Process    | Anomalous Process Activity      | jerry.exe VMware fingerprinter                                                 |
| Process    | tbd                             | Kerberoasting                                                                  |
| Logs       | tbd                             | large number of DNSSEC requests from one source                                |
| Logs       | tbd                             | log tampering - stop or deletes                                                |
| Process    | Persistence                     | LOLbins                                                                        |
| Process    | Anomalous Process Activity      | LSASS Driver                                                                   |
| Process    | Credential Dumping              | lslass www.truesec.se                                                          |
| Process    | Anomalous Process Activity      | memoryze                                                                       |
| Process    | Exploitation                    | metrepreter activity                                                           |
| Process    | Credential Dumping              | mimikatz                                                                       |
| Process    | Anomalous Process Activity      | Mimikatz DCSynch                                                               |
| Process    | Anomalous Process Activity      | mimikatz: eventr.data.GrantedAccess is 0x1010 and the targetImage is lsass.exe |
| Process    | Credential Dumping              | minimerberos                                                                   |
| Logs       | tbd                             | MS Telnet service started                                                      |
| Process    | Anomalous Process Activity      | msbuild activity                                                               |
| Process    | Credential Dumping              | netscan                                                                        |
| Logs       | tbd                             | non-admin system configuration                                                 |
| Process    | Anomalous Process Activity      | nslookup activity                                                              |
| Logs       | misc                            | null session activity                                                          |
| Process    | Exploitation                    | Obfuscated metasploit shellcode                                                |
| Logs       | tbd                             | Open network share created                                                     |
| Files      | Persistence                     | Overwrite of C:\Windows\System32\sethc.exe with cmd.exe                        |
| Process    | Credential Dumping              | pass-the-hash-toolkit                                                          |
| Process    | Credential Dumping              | Password dumping                                                               |
| Powershell | Powershell                      | Powercat technique                                                             |
| Powershell | Powershell                      | powershell base64 encoded script                                               |
| Powershell | Powershell                      | Powershell Base64 Shellcode                                                    |
| Powershell | Powershell                      | powershell binary file download                                                |
| Process    | Powershell                      | powershell connect outbound                                                    |
| Powershell | Powershell                      | powershell creating executable file in Temp directory                          |
| Powershell | Powershell                      | powershell executed by cmd.exe                                                 |
| Powershell | Powershell                      | powershell execution from temp folder                                          |
| Powershell | Powershell                      | Powershell in-memory injection using certutil                                  |
| Powershell | Powershell                      | Powershell password access                                                     |
| Powershell | Powershell                      | powershell remote connection                                                   |
| Powershell | Powershell                      | Powershell script from temp directory                                          |
| Powershell | Powershell                      | powershell scripts using WMI                                                   |
| Process    | Powershell                      | powershell started by office app                                               |
| Powershell | Powershell                      | powershell started by Outlook                                                  |
| Powershell | Powershell                      | Powershell using HTTP                                                          |
| Powershell | Powershell                      | Powershell using RPC                                                           |
| Process    | Credential Dumping              | procdump                                                                       |
| Process    | Anomalous Process Activity      | process activity from \local\temp                                              |
| Process    | Powershell                      | process activity from downloads directory                                      |
| Process    | Anomalous Process Activity      | process activity from user profile                                             |
| Process    | Anomalous Process Activity      | process activity from windows directory                                        |
| Process    | Persistence                     | Process Doppleganing                                                           |
| Process    | Anomalous Process Activity      | process started by cmd.exe                                                     |
| Process    | Anomalous Process Activity      | process started by csrss.exe                                                   |
| Logs       | tbd                             | Protected System file..was not restored to its original                        |
| Process    | Anomalous Process Activity      | pscp.exe                                                                       |
| Process    | Credential Dumping              | psexec                                                                         |
| Process    | Persistence                     | psexec                                                                         |
| Process    | Persistence                     | psexec activity                                                                |
| Process    | Credential Dumping              | PSWtool                                                                        |
| Process    | Anomalous Process Activity      | putty.exe                                                                      |
| Process    | Credential Dumping              | pwcrack                                                                        |
| Process    | Credential Dumping              | pwdump                                                                         |
| Process    | Credential Dumping              | pwdump7                                                                        |
| Process    | Credential Dumping              | pwdumpx                                                                        |
| Process    | tbd                             | py2exe activity                                                                |
| Process    | Credential Dumping              | pypkatz                                                                        |
| Process    | tbd                             | Ranger                                                                         |
| Logs       | Collection                      | RDP shadowing                                                                  |
| Process    | Anomalous Process Activity      | regback.exe                                                                    |
| Process    | Anomalous Process Activity      | regconfig.vbs                                                                  |
| Process    | Anomalous Process Activity      | regdmp.exe                                                                     |
| Process    | Anomalous Process Activity      | regfind.exe                                                                    |
| Process    | Anomalous Process Activity      | regini.exe                                                                     |
| Process    | Anomalous Process Activity      | regtest.exe                                                                    |
| Process    | Sysmon subversion               | Renamed image                                                                  |
| Process    | Explotation                     | requests to sqm.microsoft.com                                                  |
| Process    | Anomalous Process Activity      | resource kit tools run by a user                                               |
| Registry   | tbd                             | Run key change                                                                 |
| Process    | tbd                             | sc.exe activity by a user                                                      |
| Logs       | tbd                             | scheduled task creation                                                        |
| Logs       | tbd                             | Scheduled Task on DC                                                           |
| Process    | Anomalous Process Activity      | scoopy.exe VMware fingerprinter                                                |
| Process    | Anomalous Process Activity      | scoopyNG.exe VMware fingerprinter                                              |
| Process    | Anomalous Process Activity      | scp.exe                                                                        |
| Process    | Persistence                     | SecureBoot tampering                                                           |
| Process    | tbd                             | Sharesniffer                                                                   |
| Process    | tbd                             | SharpPack techniques                                                           |
| Process    | Anomalous Process Activity      | ssh.exe                                                                        |
| Logs       | tbd                             | Suspicious 4648 event                                                          |
| Process    | Anomalous Process Activity      | Suspicious svchost                                                             |
| Process    | Sysmon subversion               | sysmon process errors                                                          |
| Process    | Sysmon subversion               | sysmon process errors                                                          |
| Process    | Sysmon subversion               | Sysmon subversion                                                              |
| Process    | Anomalous Process Activity      | system tool not spawned by cmd.exe                                             |
| Files      | Persistence                     | System32 and SysWoW64 folder file creates                                      |
| Process    | Anomalous Process Activity      | these load a DLL into lsass.exe from %temp%                                    |
| Logs       | tbd                             | Unhandled malware event - Left alone or Leave alone (log only)                 |
| Process    | Anomalous Process Activity      | unusual process handle to lsass.exe                                            |
| Process    | Powershell                      | vbscript spawned by powershell                                                 |
| Process    | Anomalous Process Activity      | VmDetect.exe VMware fingerprinter                                              |
| Process    | Collection                      | volume shadow copy of drive C:                                                 |
| Process    | Credential Dumping              | WCE                                                                            |
| Process    | Persistence                     | web shell activity                                                             |
| Process    | tbd                             | WES technique                                                                  |
| Logs       | tbd                             | windows defender detect                                                        |
| Logs       | tbd                             | Windows File Protection is not active                                          |
| Process    | Anomalous Process Activity      | windump                                                                        |
| Process    | Anomalous Process Activity      | windump                                                                        |
| Process    | Anomalous Process Activity      | winfingerprint                                                                 |
| Process    | Anomalous Process Activity      | winscp                                                                         |
| Logs       | tbd                             | WMI activity                                                                   |
| Powershell | Powershell                      | WMI calling powershell                                                         |
| Logs       | tbd                             | WMI lateral movement                                                           |
| Process    | tbd                             | wmic query                                                                     |
| Logs       | tbd                             | zone transfer denied                                                           |
| Logs       | tbd                             | zone transfer succeeded                                                        |
