| SpaceCake search name                                                                  | ATT&CK categories           | Sigma rule name                        |
|----------------------------------------------------------------------------------------|-----------------------------|----------------------------------------|
| DHCP server callout errors - possible DLL injection                                    | attack.defense_evasion      | win_susp_dhcp_config_failed.yml        |
| DHCP server loaded the callout DLL - possible DLL injection                            | attack.defense_evasion      | win_susp_dhcp_config.yml               |
| DNS server error failed loading the ServerLevelPluginDLL - possible DLL injection      | attack.defense_evasion      | win_susp_dns_config.yml                |
| Malicious service installed                                                            | attack.persistence          | win_mal_service_installs.yml           |
| Malware indicators in Windows event log                                                | none                        | win_av_relevant_match.yml              |
| Microsoft malware protection engine crashed                                            | attack.defense_evasion      | win_susp_msmpeng_crash.yml             |
| Mimikatz indicators in Windows event log                                               | attack.credential_access    | win_alert_mimikatz_keywords.yml        |
| Overpass the hash attempt - logon type 9 (NewCredentials) = possible Mimikatz activity | attack.lateral_movement     | win_overpass_the_hash.yml              |
| Pass the hash activity in event logs - possible lateral movement                       | attack.lateral_movement     | win_pass_the_hash.yml                  |
| Password change on a DSRM account - possible persistence                               | attack.persistence          | win_susp_dsrm_password_change.yml      |
| Remote login by an admin user                                                          | attack.lateral_movement     | win_admin_rdp_login.yml                |
| Ruler hacktool activity                                                                | attack.discovery            | win_alert_ruler.yml.                   |
| Security event log was cleared                                                         | attack.defense_evasion      | win_susp_security_eventlog_cleared.yml |
| SID history added to Active Directory object - possible privilege elevation            | attack.privilege_escalation | win_susp_add_sid_history.yml           |
| smbexec.py service installed                                                           | attack.lateral_movement     | win_hack_smbexec.yml                   |
| Suspicious system time modification                                                    | attack.defense_evasion      | win_susp_time_modification.yml         |
| System backup catalog deleted                                                          | attack.defense_evasion      | win_susp_backup_delete.yml             |
| Unusual failed logon codes - possible account tampering                                | attack.persistence          | win_susp_failed_logon_reasons.yml      |
| USB device connected                                                                   | attack.initial_access       | win_usb_device_plugged.yml             |
| Windows event log cleared                                                              | attack.defense_evasion      | win_susp_eventlog_cleared.yml          |
