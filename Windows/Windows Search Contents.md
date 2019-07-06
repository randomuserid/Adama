Windows hunts - some use event logs and some need sysmon data; a few need registry events.

| Event Type         | Category             | Search Name                                                    |
|--------------------|----------------------|----------------------------------------------------------------|
| Process Create     | Credential Access    | 0phcrack activity                                              |
| Process Create     | Behavioral Detection | 32 bit Powershell activity                                     |
| Process Create     | Behavioral Detection | Abnormal lsaiso.exe                                            |
| Process Create     | Behavioral Detection | Abnormal path                                                  |
| Process Create     | Behavioral Detection | Abnormal runtimebroker.exe                                     |
| Process Create     | Behavioral Detection | Abnormal svchost.exe                                           |
| Process Create     | Credential Access    | Acehash                                                        |
| Event Logs         | Persistence          | AD: backdoor using service principal name                      |
| Event Logs         | Persistence          | AD: backdoor via delegation                                    |
| Event Logs         | Persistence          | AD: enabling more efficient hash cracking (sigma)              |
| Event Logs         | Defense Evasion      | Anomalous %*%.exe paramater to process creation                |
| Event Logs         | Credential Access    | Anomalous 3033 / 3063 lsass protection events                  |
| Event Logs         | Credential Access    | Anomalous 3065 / 3066 lsass auditing events                    |
| Event Logs         | Persistence          | Anomalous 4013 (powershell events)                             |
| Event Logs         | Lateral Movement     | Anomalous 4776 events                                          |
| Network Connection | Behavioral Detection | Anomalous acrobat.exe activity                                 |
| Network Connection | Behavioral Detection | Anomalous adobe_licutil.exe activity                           |
| Network Connection | Behavioral Detection | Anomalous adobearm.exe activity                                |
| Network Connection | Behavioral Detection | Anomalous adobegcclient.exe activity                           |
| Process Create     | Behavioral Detection | Anomalous at \\host*                                           |
| Process Create     | Behavioral Detection | Anomalous at command activity                                  |
| Event Logs         | Lateral Movement     | Anomalous C$ Activity in Event 5140                            |
| Process Create     | Behavioral Detection | Anomalous cmd.exe activity from a user                         |
| Process Create     | Behavioral Detection | Anomalous cmd.exe, outside WINDIR                              |
| Process Create     | Behavioral Detection | Anomalous cmd.exe, system account                              |
| Network Connection | Behavioral Detection | Anomalous compattelrunner.exe activity                         |
| Process Create     | Behavioral Detection | Anomalous conhost.exe command                                  |
| Network Connection | Behavioral Detection | Anomalous dns activity                                         |
| Network Connection | Behavioral Detection | Anomalous dropbox.exe activity                                 |
| Network Connection | Behavioral Detection | Anomalous dropboxupdate                                        |
| Event Logs         | Lateral Movement     | Anomalous event 4771  - pre-ticket auth failed                 |
| Network Connection | Behavioral Detection | Anomalous excel.exe activity                                   |
| Network Connection | Behavioral Detection | Anomalous explorer activity                                    |
| Network Connection | Behavioral Detection | Anomalous g2mupdate.exe activity                               |
| Process Create     | Behavioral Detection | Anomalous host create *                                        |
| Process Create     | Behavioral Detection | Anomalous host start *                                         |
| Event Logs         | Initial Access       | Anomalous Kerberos Events                                      |
| Process Create     | Behavioral Detection | Anomalous logman.exe command                                   |
| Network Connection | Behavioral Detection | Anomalous lsass  activity                                      |
| Process Create     | Behavioral Detection | Anomalous lsass.exe command                                    |
| Network Connection | Behavioral Detection | Anomalous lync.exe activity                                    |
| Network Connection | Behavioral Detection | Anomalous mpcmdrun activity                                    |
| Network Connection | Behavioral Detection | Anomalous MRT.exe activity                                     |
| Process Create     | Behavioral Detection | Anomalous named pipe activity                                  |
| Process Create     | Behavioral Detection | Anomalous nbtstat activity                                     |
| Process Create     | Behavioral Detection | Anomalous net command activity                                 |
| Process Create     | Behavioral Detection | Anomalous net localgroup command                               |
| Process Create     | Behavioral Detection | Anomalous net start command                                    |
| Process Create     | Behavioral Detection | Anomalous net use command activity                             |
| Process Create     | Behavioral Detection | Anomalous net user command                                     |
| Process Create     | Behavioral Detection | Anomalous netsh activity                                       |
| Event Logs         | Behavioral Detection | Anomalous network share access                                 |
| Event Logs         | Behavioral Detection | Anomalous network share creation                               |
| Network Connection | Behavioral Detection | Anomalous Notepad updater                                      |
| Network Connection | Behavioral Detection | Anomalous outlook.exe activity                                 |
| Process Create     | Behavioral Detection | Anomalous pkgmgr activity                                      |
| Network Connection | Behavioral Detection | Anomalous port 102 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 110 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 123 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 135 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 137 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 138 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 139                                             |
| Network Connection | Behavioral Detection | Anomalous port 143 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 25 activity                                     |
| Network Connection | Behavioral Detection | Anomalous port 3268 activity                                   |
| Network Connection | Behavioral Detection | Anomalous port 3269 activity                                   |
| Network Connection | Behavioral Detection | Anomalous port 3389 activity                                   |
| Network Connection | Behavioral Detection | Anomalous port 3389 activity                                   |
| Network Connection | Behavioral Detection | Anomalous port 389 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 42 activity                                     |
| Network Connection | Behavioral Detection | Anomalous port 443 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 445 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 53 activity                                     |
| Network Connection | Behavioral Detection | Anomalous port 593 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 593 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 636 activity                                    |
| Network Connection | Behavioral Detection | Anomalous port 88 activity                                     |
| Network Connection | Behavioral Detection | Anomalous port 993 activity                                    |
| Network Connection | Behavioral Detection | Anomalous powerpoint.exe activity                              |
| Event Logs         | Persistence          | Anomalous RDP login                                            |
| Process Create     | Behavioral Detection | Anomalous reg add \\host*                                      |
| Process Create     | Behavioral Detection | Anomalous reg import                                           |
| Process Create     | Behavioral Detection | Anomalous remote management activity                           |
| Event Logs         | Lateral Movement     | Anomalous remote thread creation                               |
| Process Create     | Behavioral Detection | Anomalous runas activity                                       |
| Process Create     | Behavioral Detection | Anomalous sc command activity                                  |
| Event Logs         | Persistence          | Anomalous scheduled task creation                              |
| Event Logs         | Persistence          | Anomalous schtasks /CREATE*                                    |
| Process Create     | Behavioral Detection | Anomalous schtasks command activity                            |
| Event Logs         | Persistence          | Anomalous service creation                                     |
| Network Connection | Behavioral Detection | Anomalous sihclient.exe.exe activity                           |
| Process Create     | Persistence          | Anomalous svchost                                              |
| Network Connection | Behavioral Detection | Anomalous svchost activity                                     |
| Process Create     | Behavioral Detection | Anomalous svchost.exe command                                  |
| Network Connection | Behavioral Detection | Anomalous System activity                                      |
| Process Create     | Behavioral Detection | Anomalous system process                                       |
| Process Create     | Behavioral Detection | Anomalous tasklist activity                                    |
| Network Connection | Behavioral Detection | Anomalous teamviewer_Service.exe activity                      |
| Process Create     | Behavioral Detection | Anomalous typeperf.exe command                                 |
| Event Logs         | Persistence          | Anomalous Windows Management Instrumentation                   |
| Process Create     | Behavioral Detection | Anomalous winrs command activity                               |
| Process Create     | Behavioral Detection | Anomalous winrs -r:*                                           |
| Network Connection | Behavioral Detection | Anomalous winword.exe activity                                 |
| Process Create     | Behavioral Detection | Anomalous WMI activity                                         |
| Process Create     | Behavioral Detection | Anomalous wmiapsrv.exe command                                 |
| Process Create     | Behavioral Detection | Anomalous wmic command activity                                |
| Process Create     | Behavioral Detection | Anomalous wmiprvse command activity                            |
| Process Create     | Behavioral Detection | Anomalous wsmprovhost command activity (powershell)            |
| Registry           | Persistence          | Appinit_dlls Value kb # 197571                                 |
| Process Create     | Behavioral Detection | Auditpol usage                                                 |
| Process Create     | Persistence          | Batch file making registry modifications                       |
| Process Create     | Persistence          | Bloodhound                                                     |
| Event Logs         | Credential Access    | Bloodhound Activity                                            |
| Event Logs         | Initial Access       | Broadcast name resolution poisoning (like WPAD)                |
| Process Create     | Behavioral Detection | Cacls.exe activity                                             |
| Process Create     | Persistence          | Certutil download                                              |
| Event Logs         | Defense Evasion      | Clearing firewall logs                                         |
| Process Create     | Persistence          | Cmake activitry                                                |
| Process Create     | Execution            | Cmd executing a child from a variable                          |
| Process Create     | Persistence          | Cmd prompt internal command activity                           |
| Process Create     | Persistence          | Cobalt strike                                                  |
| Registry           | Persistence          | Command Procesor autorun key                                   |
| Process Create     | Defense Evasion      | Consolehost history disabled                                   |
| Files              | Credential Access    | Copy of directory files                                        |
| Process Create     | Credential Access    | Copy of directory files                                        |
| Process Create     | Persistence          | Cradlecrafter                                                  |
| Event Logs         | Persistence          | Creating backup policy                                         |
| Process Create     | Credential Access    | Creddump                                                       |
| Process Create     | Credential Access    | Credsleaker                                                    |
| Process Create     | Defense Evasion      | Deletion of prefetch directory                                 |
| Event Logs         | Execution            | DLL activity with a .d1l or .dl1 extension                     |
| Process Create     | Execution            | Dnscmd injection                                               |
| Process Create     | Behavioral Detection | Doo Vmware detection script                                    |
| Process Create     | Behavioral Detection | Doo.vbs vmware fingerprinter                                   |
| Process Create     | Credential Access    | Dumpcreds                                                      |
| Process Create     | Credential Access    | Dumpsec                                                        |
| Process Create     | Persistence          | Empire                                                         |
| Process Create     | Behavioral Detection | Enum                                                           |
| Event Logs         | Initial Access       | Event 8001 in WLAN autoconfig                                  |
| Event Logs         | Defense Evasion      | Event log access by Danderspritz                               |
| Event Logs         | Defense Evasion      | Event log access by Mimikatz                                   |
| Event Logs         | Defense Evasion      | Event log service stopped                                      |
| Registry           | Execution            | Exefile shell open command activity                            |
| Process Create     | Credential Access    | Fgdump www.truesec.se                                          |
| Process Create     | Execution            | File-less meterpreter activity                                 |
| Process Create     | Behavioral Detection | Firewall disable                                               |
| Process Create     | Behavioral Detection | Fport                                                          |
| Process Create     | Behavioral Detection | FTK Imager                                                     |
| Event Logs         | Privilege Escalation | Gold and silver tickets                                        |
| Event Logs         | Credential Access    | Golden ticket activity                                         |
| Process Create     | Credential Access    | Gsecdump                                                       |
| Process Create     | Credential Access    | Htool                                                          |
| Process Create     | Behavioral Detection | Httport                                                        |
| Registry           | Persistence          | Image File Execution key                                       |
| Process Create     | Behavioral Detection | Indirect Command Execution                                     |
| Event Logs         | Persistence          | Install Root Certificate                                       |
| Event Logs         | Lateral Movement     | Interactive Login by a Service Account                         |
| Process Create     | Behavioral Detection | Jerry.exe vmware fingerprinter                                 |
| Process Create     | Privilege Escalation | Kerberoasting                                                  |
| Event Logs         | Behavioral Detection | Large number of DNSSEC requests from one source                |
| Event Logs         | Privilege Escalation | Local Admin Creation                                           |
| Event Logs         | Defense Evasion      | Log tampering - stop or deletes                                |
| Event Logs         | Initial Access       | Login from hostname BT                                         |
| Event Logs         | Lateral Movement     | Login Type 10 for a service account                            |
| Process Create     | Persistence          | Lolbins                                                        |
| Process Create     | Behavioral Detection | LSASS Driver                                                   |
| Process Create     | Credential Access    | Lslass www.truesec.se                                          |
| Sysmon             | Lateral Movement     | Memory Access by Another Process                               |
| Process Create     | Behavioral Detection | Memoryze                                                       |
| Process Create     | Execution            | Metrepreter activity                                           |
| Process Create     | Credential Access    | Mimikatz                                                       |
| Process Create     | Credential Access    | Mimikatz dcsynch                                               |
| Event Logs         | Credential Access    | Mimikatz lsass activity                                        |
| Process Create     | Credential Access    | Minimerberos                                                   |
| Event Logs         | Behavioral Detection | MS Telnet service started                                      |
| Process Create     | Behavioral Detection | Msbuild activity                                               |
| Process Create     | Credential Access    | Netscan                                                        |
| Process Create     | Behavioral Detection | Nishang activity                                               |
| Event Logs         | Behavioral Detection | Non-admin system configuration                                 |
| Process Create     | Behavioral Detection | Nslookup activity                                              |
| Process Create     | Credential Access    | Ntdsdump activity                                              |
| Process Create     | Credential Access    | Ntdsutil activity                                              |
| Process Create     | Credential Access    | Ntdsxtract activity                                            |
| Event Logs         | Behavioral Detection | Null session activity                                          |
| Process Create     | Execution            | Obfuscated metasploit shellcode                                |
| Event Logs         | Behavioral Detection | Open network share created                                     |
| Event Logs         | Credential Access    | Overpass the hash technique                                    |
| Files              | Persistence          | Overwrite of C:\Windows\System32\sethc.exe with cmd.exe        |
| Event Logs         | Credential Access    | Pass the Hash technique                                        |
| Event Logs         | Credential Access    | Passing the ticket technique                                   |
| Process Create     | Credential Access    | Pass-the-hash-toolkit                                          |
| Process Create     | Credential Access    | Password dumping                                               |
| Powershell         | Behavioral Detection | Powercat                                                       |
| Powershell         | Behavioral Detection | Powershell base64 encoded script                               |
| Powershell         | Behavioral Detection | Powershell Base64 Shellcode                                    |
| Powershell         | Persistence          | Powershell binary file download                                |
| Process Create     | Command and Control  | Powershell connect outbound                                    |
| Event Logs         | Execution            | Powershell cradle                                              |
| Powershell         | Execution            | Powershell creating executable file in Temp directory          |
| Powershell         | Behavioral Detection | Powershell executed by cmd.exe                                 |
| Powershell         | Behavioral Detection | Powershell execution from temp folder                          |
| Powershell         | Execution            | Powershell in-memory injection using certutil                  |
| Powershell         | Credential Access    | Powershell password access                                     |
| Powershell         | Command and Control  | Powershell remote connection                                   |
| Event Logs         | Lateral Movement     | Powershell remoting activity (wsmprovhost.exe)                 |
| Files              | Execution            | Powershell script written to temp directory                    |
| Powershell         | Lateral Movement     | Powershell scripts using WMI                                   |
| Process Create     | Behavioral Detection | Powershell started by office app                               |
| Powershell         | Behavioral Detection | Powershell started by Outlook                                  |
| Powershell         | Behavioral Detection | Powershell using HTTP                                          |
| Event Logs         | Execution            | Powershell using IEX                                           |
| Powershell         | Behavioral Detection | Powershell using RPC                                           |
| Process Create     | Credential Access    | Procdump                                                       |
| Process Create     | Behavioral Detection | Process activity from \local\temp                              |
| Process Create     | Behavioral Detection | Process activity from downloads directory                      |
| Process Create     | Behavioral Detection | Process activity from user profile                             |
| Process Create     | Behavioral Detection | Process activity from windows directory                        |
| Process Create     | Behavioral Detection | Process Creation by Office App in Users Directory              |
| Process Create     | Persistence          | Process Doppleganing                                           |
| Process Create     | Behavioral Detection | Process started by cmd.exe                                     |
| Process Create     | Behavioral Detection | Process started by csrss.exe                                   |
| Process Create     | Lateral Movement     | Process started by scrcons                                     |
| Process Create     | Lateral Movement     | Process started by wmiprvse                                    |
| Event Logs         | Execution            | Protected System file..was not restored to its original        |
| Process Create     | Behavioral Detection | Pscp.exe                                                       |
| Process Create     | Persistence          | Psexec activity                                                |
| Process Create     | Credential Access    | Pswtool                                                        |
| Process Create     | Behavioral Detection | Putty.exe                                                      |
| Process Create     | Credential Access    | Pwcrack                                                        |
| Process Create     | Credential Access    | Pwdump                                                         |
| Process Create     | Credential Access    | Pwdump7                                                        |
| Process Create     | Credential Access    | Pwdumpx                                                        |
| Process Create     | Execution            | Py2exe activity                                                |
| Process Create     | Credential Access    | Pypkatz                                                        |
| Process Create     | Execution            | Ranger                                                         |
| Event Logs         | Collection           | RDP shadowing                                                  |
| Process Create     | Behavioral Detection | Regback.exe                                                    |
| Process Create     | Behavioral Detection | Regconfig.vbs                                                  |
| Process Create     | Behavioral Detection | Regdmp.exe                                                     |
| Process Create     | Behavioral Detection | Regfind.exe                                                    |
| Process Create     | Behavioral Detection | Regini.exe                                                     |
| Process Create     | Behavioral Detection | Regtest.exe                                                    |
| Event Logs         | Defense Evasion      | Renamed image                                                  |
| Process Create     | Execution            | Requests to sqm.microsoft.com                                  |
| Process Create     | Behavioral Detection | Resource kit tools run by a user                               |
| Registry           | Execution            | Run key change                                                 |
| Process Create     | Execution            | Sc.exe activity by a user                                      |
| Event Logs         | Execution            | Scheduled task creation                                        |
| Event Logs         | Execution            | Scheduled Task on DC                                           |
| Process Create     | Behavioral Detection | Scoopy.exe vmware fingerprinter                                |
| Process Create     | Behavioral Detection | Scoopyng.exe vmware fingerprinter                              |
| Process Create     | Behavioral Detection | Scp.exe                                                        |
| Process Create     | Persistence          | Secureboot tampering                                           |
| Event Logs         | Lateral Movement     | Server to Workstation share access                             |
| Event Logs         | Persistence          | Service replacement                                            |
| Process Create     | Execution            | Sharesniffer                                                   |
| Process Create     | Execution            | Sharppack techniques                                           |
| Event Logs         | Credential Access    | Silver ticket activity                                         |
| Event Logs         | Credential Access    | Skeleton key activity                                          |
| Process Create     | Behavioral Detection | Ssh.exe                                                        |
| Event Logs         | Execution            | Suspicious 4648 event                                          |
| Event Logs         | Privilege Escalation | Suspicious Impersonation                                       |
| Process Create     | Persistence          | Suspicious svchost                                             |
| Event Logs         | Defense Evasion      | Sysmon process errors                                          |
| Event Logs         | Defense Evasion      | Sysmon process errors                                          |
| Event Logs         | Defense Evasion      | Sysmon subversion                                              |
| Process Create     | Behavioral Detection | System tool not spawned by cmd.exe                             |
| Files              | Persistence          | System32 and syswow64 folder file creates                      |
| Event Logs         | Behavioral Detection | These load a DLL into lsass.exe from %temp%                    |
| Event Logs         | Execution            | Unhandled malware event - Left alone or Leave alone (log only) |
| Event Logs         | Behavioral Detection | Unusual process handle to lsass.exe                            |
| Event Logs         | Privilege Escalation | User local group membership enumerated (4798)                  |
| Event Logs         | Lateral Movement     | Username with C$ character                                     |
| Process Create     | Execution            | Vbscript spawned by powershell                                 |
| Process Create     | Behavioral Detection | Vmdetect.exe vmware fingerprinter                              |
| Process Create     | Collection           | Volume shadow copy of drive C:                                 |
| Event Logs         | Defense Evasion      | Volume shadow service stops                                    |
| Process Create     | Behavioral Detection | Vssadmin activity                                              |
| Process Create     | Credential Access    | WCE                                                            |
| Process Create     | Persistence          | Web shell activity                                             |
| Process Create     | Execution            | WES technique                                                  |
| Process Create     | Behavioral Detection | Wevutil activity                                               |
| Event Logs         | Execution            | Windows defender detect                                        |
| Event Logs         | Execution            | Windows File Protection is not active                          |
| Process Create     | Behavioral Detection | Windump                                                        |
| Process Create     | Behavioral Detection | Winfingerprint                                                 |
| Process Create     | Behavioral Detection | Winscp                                                         |
| Event Logs         | Execution            | WMI activity                                                   |
| Powershell         | Lateral Movement     | WMI calling powershell                                         |
| Event Logs         | Lateral Movement     | WMI consumer with script or executable payload                 |
| Event Logs         | Lateral Movement     | WMI lateral movement                                           |
| Network Connection | Lateral Movement     | Wmic query                                                     |
| Event Logs         | Lateral Movement     | Workstation to Workstation Login                               |
| Event Logs         | Lateral Movement     | Workstation to Workstation share access                        |
| Event Logs         | Initial Access       | Zone transfer denied                                           |
| Event Logs         | Initial Access       | Zone transfer succeeded                                        |
