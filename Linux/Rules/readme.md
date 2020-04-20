### Linux Signal Rules

Elastic SIEM rules for threat hunting & detection using Linux Auditbeat data

| Rule Name                                              | Tactic              | Technique |                               |
|--------------------------------------------------------|---------------------|-----------|-------------------------------|
| Data Encryption - Possible Exfiltration                | exfiltration        | T1022     | Data Encrypted                |
| Defense Evasion - Attempt to Disable IPtables Firewall | defense-evasion     | T1089     | Disabling Security Tools      |
| Defense Evasion - Attempt to Disable SELinux           | defense-evasion     | T1089     | Disabling Security Tools      |
| Defense Evasion - Attempt to Disable Syslog            | defense-evasion     | T1089     | Disabling Security Tools      |
| Defense Evasion - File Destruction                     | defense-evasion     | T1107     | File Deletion                 |
| Defense Evasion - Systemd Service Tampering            | persistence         | T1502     | Systemd Service               |
| Discovery - Virtual Machine Fingerprinting             | discovery           | T1082     | System Information Discovery  |
| Linux Complier Activity                                | execution           | T1127     | Trusted Developer Utilities   |
| Linux Defense Evasion via Kernel Module Removal        | defense-evasion     | T1089     | Disabling Security Tools      |
| Linux Persistence via Account Creation                 | persistence         | T1136     | Create Account                |
| Linux Persistence via Kernel Module Load               | persistence         | T1215     | Kernel Modules and Extensions |
| Linux Persistence via Kernel Module Rename             | persistence         | T1216     | Kernel Modules and Extensions |
| Linux Persistence via Root UID Creation                | persistence         | T1136     | Create Account                |
| Linux Persistence via Systemd Service Creation         | persistence         | T1501     | Systemd Service               |
| Linux Persistence via the SetGID Parameter             | persistence         | T1166     | Setuid and Setgid             |
| Linux Persistence via the SetUID Parameter             | persistence         | T1166     | Setuid and Setgid             |
| Linux System Discovery - Kernel Module Enumeration     | discovery           | T1082     | System Information Discovery  |
| Linux System Owner / User Discovery                    | discovery           | T1033     | System Owner/User Discovery   |
| Network Activity by a Telnet Process                   | command-and-control | T1065     | Uncommonly Used Port          |
| Potential Defense Evasion via Time-stomping            | defense-evasion     | T1099     | Timestomp                     |
