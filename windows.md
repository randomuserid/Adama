Windows searches - some use event logs and some need sysmon data; a few need registry events.

| Event Type | Category                        | Description                                                                    |
|------------|---------------------------------|--------------------------------------------------------------------------------|
| Process    | Sysmon subversion               | %*%.exe                                                                        |
| Process    | Anomalous Process Activity      | 0phcrack activity                                                              |
| Logs       | Credential Access               | 3033 / 3063 lsass protection events                                            |
| Logs       | Credential Access               | 3065 / 3066 Llsass auditing events                                             |
| Logs       | Persistence                     | 4013 (powershell events)                                                       |
| Logs       | Initial Access                  | 4648: using other’s creds - runas or impersonation                             |
| Logs       | Privliege Escalation            | 4722 adding local admin                                                        |
| Logs       | Initial Access                  | 4776 bad logins - kerberos                                                     |
| Logs       | Collection                      | 4798 - user local group membership enumerated                                  |
| Process    | Anomalous Process Activity      | Abnormal lsaiso.exe                                                            |
| Logs       | Behavioral Detection            | abnormal path                                                                  |
| Process    | Anomalous Process Activity      | Abnormal RuntimeBroker.exe                                                     |
| Process    | Anomalous Process Activity      | Abnormal svchost.exe                                                           |
| Logs       | Persistence                     | AD: backdoor using service principal name                                      |
| Logs       | Persistence                     | AD: backdoor via delegation                                                    |
| Logs       | Persistence                     | AD: enabling more efficient hash cracking (sigma)                              |
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
| Logs       | Behavioral Detection            | anomalous network share access                                                 |
| Logs       | Behavioral Detection            | anomalous network share creation                                               |
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
| Registry   | Persistence                     | AppInit_DLLs Value kb # 197571                                                 |
| Process    | Anomalous Process Activity      | auditpol usage                                                                 |
| Process    | Persistence                     | Bloodhound                                                                     |
| Logs       | Initial Access                  | broadcast name resolution poisoning (like WPAD)                                |
| Process    | Anomalous Process Activity      | cacls.exe activity                                                             |
| Process    | Persistence                     | certutil download                                                              |
| Logs       | Defense Evasion                 | clearing firewall logs                                                         |
| Process    | Persistence                     | cmake activitry                                                                |
| Process    | Execution                       | cmd executing a child from a variable                                          |
| Process    | Persistence                     | cmd prompt internal command activity                                           |
| Process    | Persistence                     | Cobalt strike                                                                  |
| Registry   | Persistence                     | Command Procesor autorun key                                                   |
| Files      | Collection                      | copy of directory files                                                        |
| Process    | Collection                      | copy of directory files                                                        |
| Process    | Persistence                     | CradleCrafter                                                                  |
| Logs       | Persistence                     | creating backup policy                                                         |
| Process    | Credential Dumping              | CredsLeaker                                                                    |
| Process    | Exploitation                    | dnscmd injection                                                               |
| Process    | Anomalous Process Activity      | Doo Vmware detection script                                                    |
| Process    | Anomalous Process Activity      | doo.vbs VMware fingerprinter                                                   |
| Process    | Credential Dumping              | dumpcreds                                                                      |
| Process    | Credential Dumping              | DumpSec                                                                        |
| Process    | Persistence                     | Empire                                                                         |
| Process    | Anomalous Process Activity      | enum                                                                           |
| Logs       | Initial Access                  | event 8001 in WLAN autoconfig                                                  |
| Logs       | Defense Evasion                 | event log service stopped                                                      |
| Registry   | Execution                       | exefile shell open command activity                                            |
| Process    | Credential Dumping              | fgdump www.truesec.se                                                          |
| Process    | Exploitation                    | File-less meterpreter activity                                                 |
| Process    | Anomalous Process Activity      | firewall disable                                                               |
| Process    | Anomalous Process Activity      | fport                                                                          |
| Process    | Anomalous Process Activity      | FTK Imager                                                                     |
| Logs       | Privliege Escalation            | Gold and silver tickets                                                        |
| Process    | Credential Dumping              | gsecdump                                                                       |
| Process    | Credential Dumping              | htool                                                                          |
| Process    | Anomalous Process Activity      | HTTPort                                                                        |
| Registry   | Persistence                     | Image File Execution key                                                       |
| Process    | Anomalous Process Activity      | Indirect Command Execution                                                     |
| Logs       | Persistence                     | Install Root Certificate                                                       |
| Process    | Anomalous Process Activity      | jerry.exe VMware fingerprinter                                                 |
| Process    | Privliege Escalation            | Kerberoasting                                                                  |
| Logs       | Behavioral Detection            | large number of DNSSEC requests from one source                                |
| Logs       | Defense Evasion                 | log tampering - stop or deletes                                                |
| Process    | Persistence                     | LOLbins                                                                        |
| Process    | Anomalous Process Activity      | LSASS Driver                                                                   |
| Process    | Credential Dumping              | lslass www.truesec.se                                                          |
| Process    | Anomalous Process Activity      | memoryze                                                                       |
| Process    | Exploitation                    | metrepreter activity                                                           |
| Process    | Credential Dumping              | mimikatz                                                                       |
| Process    | Anomalous Process Activity      | Mimikatz DCSynch                                                               |
| Process    | Anomalous Process Activity      | mimikatz: eventr.data.GrantedAccess is 0x1010 and the targetImage is lsass.exe |
| Process    | Credential Dumping              | minimerberos                                                                   |
| Logs       | Behavioral Detection            | MS Telnet service started                                                      |
| Process    | Anomalous Process Activity      | msbuild activity                                                               |
| Process    | Credential Dumping              | netscan                                                                        |
| Logs       | Behavioral Detection            | non-admin system configuration                                                 |
| Process    | Anomalous Process Activity      | nslookup activity                                                              |
| Logs       | misc                            | null session activity                                                          |
| Process    | Exploitation                    | Obfuscated metasploit shellcode                                                |
| Logs       | Behavioral Detection            | Open network share created                                                     |
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
| Logs       | Execution                       | Protected System file..was not restored to its original                        |
| Process    | Anomalous Process Activity      | pscp.exe                                                                       |
| Process    | Persistence                     | psexec activity                                                                |
| Process    | Credential Dumping              | PSWtool                                                                        |
| Process    | Anomalous Process Activity      | putty.exe                                                                      |
| Process    | Credential Dumping              | pwcrack                                                                        |
| Process    | Credential Dumping              | pwdump                                                                         |
| Process    | Credential Dumping              | pwdump7                                                                        |
| Process    | Credential Dumping              | pwdumpx                                                                        |
| Process    | Execution                       | py2exe activity                                                                |
| Process    | Credential Dumping              | pypkatz                                                                        |
| Process    | Execution                       | Ranger                                                                         |
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
| Registry   | Execution                       | Run key change                                                                 |
| Process    | Execution                       | sc.exe activity by a user                                                      |
| Logs       | Execution                       | scheduled task creation                                                        |
| Logs       | Execution                       | Scheduled Task on DC                                                           |
| Process    | Anomalous Process Activity      | scoopy.exe VMware fingerprinter                                                |
| Process    | Anomalous Process Activity      | scoopyNG.exe VMware fingerprinter                                              |
| Process    | Anomalous Process Activity      | scp.exe                                                                        |
| Process    | Persistence                     | SecureBoot tampering                                                           |
| Process    | Execution                       | Sharesniffer                                                                   |
| Process    | Execution                       | SharpPack techniques                                                           |
| Process    | Anomalous Process Activity      | ssh.exe                                                                        |
| Logs       | Execution                       | Suspicious 4648 event                                                          |
| Process    | Anomalous Process Activity      | Suspicious svchost                                                             |
| Process    | Sysmon subversion               | sysmon process errors                                                          |
| Process    | Sysmon subversion               | sysmon process errors                                                          |
| Process    | Sysmon subversion               | Sysmon subversion                                                              |
| Process    | Anomalous Process Activity      | system tool not spawned by cmd.exe                                             |
| Files      | Persistence                     | System32 and SysWoW64 folder file creates                                      |
| Process    | Anomalous Process Activity      | these load a DLL into lsass.exe from %temp%                                    |
| Logs       | Execution                       | Unhandled malware event - Left alone or Leave alone (log only)                 |
| Process    | Anomalous Process Activity      | unusual process handle to lsass.exe                                            |
| Process    | Powershell                      | vbscript spawned by powershell                                                 |
| Process    | Anomalous Process Activity      | VmDetect.exe VMware fingerprinter                                              |
| Process    | Collection                      | volume shadow copy of drive C:                                                 |
| Process    | Credential Dumping              | WCE                                                                            |
| Process    | Persistence                     | web shell activity                                                             |
| Process    | Execution                       | WES technique                                                                  |
| Logs       | Execution                       | windows defender detect                                                        |
| Logs       | Execution                       | Windows File Protection is not active                                          |
| Process    | Anomalous Process Activity      | windump                                                                        |
| Process    | Anomalous Process Activity      | winfingerprint                                                                 |
| Process    | Anomalous Process Activity      | winscp                                                                         |
| Logs       | Execution                       | WMI activity                                                                   |
| Powershell | Powershell                      | WMI calling powershell                                                         |
| Logs       | Lateral Movement                | WMI lateral movement                                                           |
| Process    | Lateral Movement                | wmic query                                                                     |
| Logs       | Discovery                       | zone transfer denied                                                           |
| Logs       | Discovery                       | zone transfer succeeded                                                        |
