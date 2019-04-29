Windows hunts - some use event logs and some need sysmon data; a few need registry events.

| Event Type         | Category             | Search Name                                                    |
|--------------------|----------------------|----------------------------------------------------------------|
| Process Create     | Behavioral Detection | Anomalous cmd.exe activity from a user                         |
| Process Create     | Behavioral Detection | Anomalous cmd.exe, system account                              |
| Process Create     | Behavioral Detection | Anomalous cmd.exe, outside WINDIR                              |
| Process Create     | Behavioral Detection | Anomalous conhost.exe command                                  |
| Process Create     | Behavioral Detection | Anomalous logman.exe command                                   |
| Process Create     | Behavioral Detection | Anomalous lsass.exe command                                    |
| Process Create     | Behavioral Detection | Anomalous svchost.exe command                                  |
| Process Create     | Behavioral Detection | Anomalous typeperf.exe command                                 |
| Process Create     | Behavioral Detection | Anomalous wmiapsrv.exe command                                 |
| Process Create     | Behavioral Detection | Abnormal lsaiso.exe                                            |
| Process Create     | Behavioral Detection | Abnormal runtimebroker.exe                                     |
| Process Create     | Behavioral Detection | Abnormal svchost.exe                                           |
| Process Create     | Behavioral Detection | Anomalous net use command activity                             |
| Process Create     | Behavioral Detection | Firewall disable                                               |
| Process Create     | Behavioral Detection | Httport                                                        |
| Process Create     | Behavioral Detection | Process started by csrss.exe                                   |
| Process Create     | Behavioral Detection | Abnormal path                                                  |
| Network Connection | Behavioral Detection | Anomalous acrobat.exe activity                                 |
| Network Connection | Behavioral Detection | Anomalous adobe_licutil.exe activity                           |
| Network Connection | Behavioral Detection | Anomalous adobearm.exe activity                                |
| Network Connection | Behavioral Detection | Anomalous adobegcclient.exe activity                           |
| Process Create     | Behavioral Detection | Anomalous at \\host*                                           |
| Process Create     | Behavioral Detection | Anomalous at command activity                                  |
| Network Connection | Behavioral Detection | Anomalous compattelrunner.exe activity                         |
| Network Connection | Behavioral Detection | Anomalous dns activity                                         |
| Network Connection | Behavioral Detection | Anomalous dropbox.exe activity                                 |
| Network Connection | Behavioral Detection | Anomalous dropboxupdate                                        |
| Network Connection | Behavioral Detection | Anomalous excel.exe activity                                   |
| Network Connection | Behavioral Detection | Anomalous explorer activity                                    |
| Network Connection | Behavioral Detection | Anomalous g2mupdate.exe activity                               |
| Process Create     | Behavioral Detection | Anomalous host create *                                        |
| Process Create     | Behavioral Detection | Anomalous host start *                                         |
| Network Connection | Behavioral Detection | Anomalous lsass  activity                                      |
| Network Connection | Behavioral Detection | Anomalous lync.exe activity                                    |
| Network Connection | Behavioral Detection | Anomalous mpcmdrun activity                                    |
| Network Connection | Behavioral Detection | Anomalous MRT.exe activity                                     |
| Process Create     | Behavioral Detection | Anomalous named pipe activity                                  |
| Process Create     | Behavioral Detection | Anomalous nbtstat activity                                     |
| Process Create     | Behavioral Detection | Anomalous net command activity                                 |
| Process Create     | Behavioral Detection | Anomalous net localgroup command                               |
| Process Create     | Behavioral Detection | Anomalous net start command                                    |
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
| Process Create     | Behavioral Detection | Anomalous reg add \\host*                                      |
| Process Create     | Behavioral Detection | Anomalous reg import                                           |
| Process Create     | Behavioral Detection | Anomalous remote management activity                           |
| Process Create     | Behavioral Detection | Anomalous sc command activity                                  |
| Process Create     | Behavioral Detection | Anomalous schtasks command activity                            |
| Network Connection | Behavioral Detection | Anomalous sihclient.exe.exe activity                           |
| Network Connection | Behavioral Detection | Anomalous svchost activity                                     |
| Network Connection | Behavioral Detection | Anomalous System activity                                      |
| Process Create     | Behavioral Detection | Anomalous system process                                       |
| Process Create     | Behavioral Detection | Anomalous tasklist activity                                    |
| Network Connection | Behavioral Detection | Anomalous teamviewer_Service.exe activity                      |
| Process Create     | Behavioral Detection | Anomalous winrs command activity                               |
| Process Create     | Behavioral Detection | Anomalous winrs -r:*                                           |
| Network Connection | Behavioral Detection | Anomalous winword.exe activity                                 |
| Process Create     | Behavioral Detection | Anomalous WMI activity                                         |
| Process Create     | Behavioral Detection | Anomalous wmic command activity                                |
| Process Create     | Behavioral Detection | Anomalous wmiprvse command activity                            |
| Process Create     | Behavioral Detection | Anomalous wsmprovhost command activity (powershell)            |
| Process Create     | Behavioral Detection | Auditpol usage                                                 |
| Process Create     | Behavioral Detection | Cacls.exe activity                                             |
| Process Create     | Behavioral Detection | Doo Vmware detection script                                    |
| Process Create     | Behavioral Detection | Doo.vbs vmware fingerprinter                                   |
| Process Create     | Behavioral Detection | Enum                                                           |
| Process Create     | Behavioral Detection | Fport                                                          |
| Process Create     | Behavioral Detection | FTK Imager                                                     |
| Process Create     | Behavioral Detection | Indirect Command Execution                                     |
| Process Create     | Behavioral Detection | Jerry.exe vmware fingerprinter                                 |
| Event Logs         | Behavioral Detection | Large number of DNSSEC requests from one source                |
| Process Create     | Behavioral Detection | LSASS Driver                                                   |
| Process Create     | Behavioral Detection | Memoryze                                                       |
| Event Logs         | Behavioral Detection | MS Telnet service started                                      |
| Process Create     | Behavioral Detection | Msbuild activity                                               |
| Event Logs         | Behavioral Detection | Non-admin system configuration                                 |
| Process Create     | Behavioral Detection | Nslookup activity                                              |
| Event Logs         | Behavioral Detection | Null session activity                                          |
| Event Logs         | Behavioral Detection | Open network share created                                     |
| Process Create     | Behavioral Detection | Process activity from \local\temp                              |
| Process Create     | Behavioral Detection | Process activity from user profile                             |
| Process Create     | Behavioral Detection | Process activity from windows directory                        |
| Process Create     | Behavioral Detection | Process started by cmd.exe                                     |
| Process Create     | Behavioral Detection | Pscp.exe                                                       |
| Process Create     | Behavioral Detection | Putty.exe                                                      |
| Process Create     | Behavioral Detection | Regback.exe                                                    |
| Process Create     | Behavioral Detection | Regconfig.vbs                                                  |
| Process Create     | Behavioral Detection | Regdmp.exe                                                     |
| Process Create     | Behavioral Detection | Regfind.exe                                                    |
| Process Create     | Behavioral Detection | Regini.exe                                                     |
| Process Create     | Behavioral Detection | Regtest.exe                                                    |
| Process Create     | Behavioral Detection | Resource kit tools run by a user                               |
| Process Create     | Behavioral Detection | Scoopy.exe vmware fingerprinter                                |
| Process Create     | Behavioral Detection | Scoopyng.exe vmware fingerprinter                              |
| Process Create     | Behavioral Detection | Scp.exe                                                        |
| Process Create     | Behavioral Detection | Ssh.exe                                                        |
| Process Create     | Behavioral Detection | System tool not spawned by cmd.exe                             |
| Event Logs         | Behavioral Detection | These load a DLL into lsass.exe from %temp%                    |
| Event Logs         | Behavioral Detection | Unusual process handle to lsass.exe                            |
| Process Create     | Behavioral Detection | Vmdetect.exe vmware fingerprinter                              |
| Process Create     | Behavioral Detection | Windump                                                        |
| Process Create     | Behavioral Detection | Winfingerprint                                                 |
| Process Create     | Behavioral Detection | Winscp                                                         |
| Process Create     | Behavioral Detection | Nishang activity                                               |
| Process Create     | Behavioral Detection | Vssadmin activity                                              |
| Process Create     | Behavioral Detection | 32 bit Powershell activity                                     |
| Process Create     | Behavioral Detection | Anomalous runas activity                                       |
| Process Create     | Behavioral Detection | Wevutil activity                                               |
| Process Create     | Behavioral Detection | Process Creation by Office App in Users Directory              |
| Event Logs         | Collection           | RDP shadowing                                                  |
| Process Create     | Collection           | Volume shadow copy of drive C:                                 |
| Process Create     | Credential Access    | 0phcrack activity                                              |
| Event Logs         | Credential Access    | Anomalous 3033 / 3063 lsass protection events                  |
| Event Logs         | Credential Access    | Anomalous 3065 / 3066 lsass auditing events                    |
| Files              | Credential Access    | Copy of directory files                                        |
| Process Create     | Credential Access    | Copy of directory files                                        |
| Process Create     | Credential Access    | Credsleaker                                                    |
| Process Create     | Credential Access    | Dumpcreds                                                      |
| Process Create     | Credential Access    | Dumpsec                                                        |
| Process Create     | Credential Access    | Fgdump www.truesec.se                                          |
| Process Create     | Credential Access    | Gsecdump                                                       |
| Process Create     | Credential Access    | Htool                                                          |
| Process Create     | Credential Access    | Lslass www.truesec.se                                          |
| Process Create     | Credential Access    | Mimikatz                                                       |
| Process Create     | Credential Access    | Mimikatz dcsynch                                               |
| Event Logs         | Credential Access    | Mimikatz lsass activity                                        |
| Process Create     | Credential Access    | Minimerberos                                                   |
| Process Create     | Credential Access    | Netscan                                                        |
| Process Create     | Credential Access    | Pass-the-hash-toolkit                                          |
| Process Create     | Credential Access    | Password dumping                                               |
| Process Create     | Credential Access    | Procdump                                                       |
| Process Create     | Credential Access    | Pswtool                                                        |
| Process Create     | Credential Access    | Pwcrack                                                        |
| Process Create     | Credential Access    | Pwdump                                                         |
| Process Create     | Credential Access    | Pwdump7                                                        |
| Process Create     | Credential Access    | Pwdumpx                                                        |
| Process Create     | Credential Access    | Pypkatz                                                        |
| Process Create     | Credential Access    | WCE                                                            |
| Process Create     | Credential Access    | Creddump                                                       |
| Process Create     | Credential Access    | Acehash                                                        |
| Event Logs         | Credential Access    | Passing the ticket technique                                   |
| Event Logs         | Credential Access    | Overpass the hash technique                                    |
| Event Logs         | Credential Access    | Golden ticket activity                                         |
| Event Logs         | Credential Access    | Silver ticket activity                                         |
| Event Logs         | Credential Access    | Skeleton key activity                                          |
| Process Create     | Credential Access    | Ntdsutil activity                                              |
| Process Create     | Credential Access    | Ntdsxtract activity                                            |
| Process Create     | Credential Access    | Ntdsdump activity                                              |
| Event Logs         | Credential Access    | Pass the Hash technique                                        |
| Event Logs         | Credential Access    | Bloodhound Activity                                            |
| Event Logs         | Defense Evasion      | Clearing firewall logs                                         |
| Event Logs         | Defense Evasion      | Event log service stopped                                      |
| Event Logs         | Defense Evasion      | Log tampering - stop or deletes                                |
| Process Create     | Defense Evasion      | Deletion of prefetch directory                                 |
| Event Logs         | Defense Evasion      | Volume shadow service stops                                    |
| Event Logs         | Defense Evasion      | Event log access by Mimikatz                                   |
| Event Logs         | Defense Evasion      | Event log access by Danderspritz                               |
| Process Create     | Defense Evasion      | Consolehost history disabled                                   |
| Process Create     | Execution            | Cmd executing a child from a variable                          |
| Process Create     | Execution            | Dnscmd injection                                               |
| Registry           | Execution            | Exefile shell open command activity                            |
| Process Create     | Execution            | File-less meterpreter activity                                 |
| Process Create     | Execution            | Metrepreter activity                                           |
| Process Create     | Execution            | Obfuscated metasploit shellcode                                |
| Event Logs         | Execution            | Protected System file..was not restored to its original        |
| Process Create     | Execution            | Py2exe activity                                                |
| Process Create     | Execution            | Ranger                                                         |
| Process Create     | Execution            | Requests to sqm.microsoft.com                                  |
| Registry           | Execution            | Run key change                                                 |
| Process Create     | Execution            | Sc.exe activity by a user                                      |
| Event Logs         | Execution            | Scheduled task creation                                        |
| Event Logs         | Execution            | Scheduled Task on DC                                           |
| Process Create     | Execution            | Sharesniffer                                                   |
| Process Create     | Execution            | Sharppack techniques                                           |
| Event Logs         | Execution            | Suspicious 4648 event                                          |
| Event Logs         | Execution            | Unhandled malware event - Left alone or Leave alone (log only) |
| Process Create     | Execution            | WES technique                                                  |
| Event Logs         | Execution            | Windows defender detect                                        |
| Event Logs         | Execution            | Windows File Protection is not active                          |
| Event Logs         | Execution            | WMI activity                                                   |
| Event Logs         | Execution            | Powershell cradle                                              |
| Event Logs         | Execution            | Powershell using IEX                                           |
| Event Logs         | Execution            | DLL activity with a .d1l or .dl1 extension                     |
| Event Logs         | Initial Access       | Anomalous Kerberos Events                                      |
| Event Logs         | Initial Access       | Broadcast name resolution poisoning (like WPAD)                |
| Event Logs         | Initial Access       | Event 8001 in WLAN autoconfig                                  |
| Event Logs         | Initial Access       | Zone transfer denied                                           |
| Event Logs         | Initial Access       | Zone transfer succeeded                                        |
| Event Logs         | Initial Access       | Login from hostname BT                                         |
| Event Logs         | Lateral Movement     | WMI lateral movement                                           |
| Network Connection | Lateral Movement     | Wmic query                                                     |
| Event Logs         | Lateral Movement     | WMI consumer with script or executable payload                 |
| Process Create     | Lateral Movement     | Process started by scrcons                                     |
| Process Create     | Lateral Movement     | Process started by wmiprvse                                    |
| Sysmon             | Lateral Movement     | Memory Access by Another Process                               |
| Event Logs         | Lateral Movement     | Username with C$ character                                     |
| Event Logs         | Lateral Movement     | Anomalous event 4771  - pre-ticket auth failed                 |
| Event Logs         | Lateral Movement     | Anomalous 4776 events                                          |
| Event Logs         | Lateral Movement     | Login Type 10 for a service account                            |
| Event Logs         | Lateral Movement     | Workstation to Workstation share access                        |
| Event Logs         | Lateral Movement     | Server to Workstation share access                             |
| Event Logs         | Lateral Movement     | Anomalous C$ Activity in Event 5140                            |
| Event Logs         | Lateral Movement     | Workstation to Workstation Login                               |
| Event Logs         | Lateral Movement     | Interactive Login by a Service Account                         |
| Event Logs         | Lateral Movement     | Anomalous remote thread creation                               |
| Event Logs         | Lateral Movement     | Powershell remoting activity (wsmprovhost.exe)                 |
| Event Logs         | Persistence          | Anomalous 4013 (powershell events)                             |
| Event Logs         | Persistence          | AD: backdoor using service principal name                      |
| Event Logs         | Persistence          | AD: backdoor via delegation                                    |
| Event Logs         | Persistence          | AD: enabling more efficient hash cracking (sigma)              |
| Event Logs         | Persistence          | Anomalous RDP login                                            |
| Event Logs         | Persistence          | Anomalous scheduled task creation                              |
| Event Logs         | Persistence          | Anomalous schtasks /CREATE*                                    |
| Process Create     | Persistence          | Anomalous svchost                                              |
| Event Logs         | Persistence          | Anomalous Windows Management Instrumentation                   |
| Registry           | Persistence          | Appinit_dlls Value kb # 197571                                 |
| Process Create     | Persistence          | Bloodhound                                                     |
| Process Create     | Persistence          | Certutil download                                              |
| Process Create     | Persistence          | Cmake activitry                                                |
| Process Create     | Persistence          | Cmd prompt internal command activity                           |
| Process Create     | Persistence          | Cobalt strike                                                  |
| Registry           | Persistence          | Command Procesor autorun key                                   |
| Process Create     | Persistence          | Cradlecrafter                                                  |
| Event Logs         | Persistence          | Creating backup policy                                         |
| Process Create     | Persistence          | Empire                                                         |
| Registry           | Persistence          | Image File Execution key                                       |
| Event Logs         | Persistence          | Install Root Certificate                                       |
| Process Create     | Persistence          | Lolbins                                                        |
| Files              | Persistence          | Overwrite of C:\Windows\System32\sethc.exe with cmd.exe        |
| Process Create     | Persistence          | Process Doppleganing                                           |
| Process Create     | Persistence          | Psexec activity                                                |
| Process Create     | Persistence          | Secureboot tampering                                           |
| Process Create     | Persistence          | Suspicious svchost                                             |
| Files              | Persistence          | System32 and syswow64 folder file creates                      |
| Process Create     | Persistence          | Web shell activity                                             |
| Event Logs         | Persistence          | Anomalous service creation                                     |
| Event Logs         | Persistence          | Service replacement                                            |
| Process Create     | Persistence          | Batch file making registry modifications                       |
| Powershell         | Behavioral Detection | Powercat                                                       |
| Powershell         | Behavioral Detection | Powershell base64 encoded script                               |
| Powershell         | Behavioral Detection | Powershell Base64 Shellcode                                    |
| Powershell         | Persistence          | Powershell binary file download                                |
| Process Create     | Command and Control  | Powershell connect outbound                                    |
| Powershell         | Execution            | Powershell creating executable file in Temp directory          |
| Powershell         | Behavioral Detection | Powershell executed by cmd.exe                                 |
| Powershell         | Behavioral Detection | Powershell execution from temp folder                          |
| Powershell         | Execution            | Powershell in-memory injection using certutil                  |
| Powershell         | Credential Access    | Powershell password access                                     |
| Powershell         | Command and Control  | Powershell remote connection                                   |
| Files              | Execution            | Powershell script written to temp directory                    |
| Powershell         | Lateral Movement     | Powershell scripts using WMI                                   |
| Process Create     | Behavioral Detection | Powershell started by office app                               |
| Powershell         | Behavioral Detection | Powershell started by Outlook                                  |
| Powershell         | Behavioral Detection | Powershell using HTTP                                          |
| Powershell         | Behavioral Detection | Powershell using RPC                                           |
| Process Create     | Behavioral Detection | Process activity from downloads directory                      |
| Process Create     | Execution            | Vbscript spawned by powershell                                 |
| Powershell         | Lateral Movement     | WMI calling powershell                                         |
| Event Logs         | Privilege Escalation | Suspicious Impersonation                                       |
| Event Logs         | Privilege Escalation | Local Admin Creation                                           |
| Event Logs         | Privilege Escalation | User local group membership enumerated (4798)                  |
| Event Logs         | Privilege Escalation | Gold and silver tickets                                        |
| Process Create     | Privilege Escalation | Kerberoasting                                                  |
| Event Logs         | Defense Evasion      | Anomalous %*%.exe paramater to process creation                |
| Event Logs         | Defense Evasion      | Renamed image                                                  |
| Event Logs         | Defense Evasion      | Sysmon process errors                                          |
| Event Logs         | Defense Evasion      | Sysmon process errors                                          |
| Event Logs         | Defense Evasion      | Sysmon subversion                                              |
