### Sentinel ATT&CK Rule Re-factors

Acknowledgments to the Sentinel ATT&CK project (https://github.com/BlueTeamLabs/sentinel-attack) (https://github.com/BlueTeamLabs/sentinel-attack/blob/master/LICENSE.md)

So I re-factored some of these in KQL for Kibana using Sysmon events in ECS. Here is a lookup table of the original rule names (https://github.com/BlueTeamLabs/sentinel-attack/tree/master/detections) and corresponding SpaceCake searches in this folder:

| Sentinel ATT&CK Rule                                       | SpaceCake Search                                            |
|------------------------------------------------------------|-------------------------------------------------------------|
| T1002_Data_Compressed.txt                                  | Windows Data Compression Using Powershell / WinRAR activity |
| T1003_Credential_Dumping_ImageLoad.txt                     | Windows Credential Dumping via ImageLoad                    |
| T1003_Credential_Dumping_Process.txt                       | Windows Credential Dumping Commands                         |
| T1003_Credential_Dumping_Registry_Save.txt                 | Windows Credential Dumping via Registry Save                |
| T1012_Query_Registry_Network.txt                           | Windows Registry Query, Network                             |
| T1012_Query_Registry_Process.txt                           | Windows Registry Query                                      |
| T1015_Accessibility_Features.txt                           | Windows Priv Escalation via Accessibility Features          |
| T1027_Obfuscated_Files_Or_Information.txt                  | Windows Payload Obfuscation via Certutil                    |
| T1028_Windows_Remote_Management.txt                        | Windows Remote Management Execution                         |
| T1031_Modify_Existing_Service.txt                          | Windows Persistence via Modification of Existing Service    |
| T1047_Windows_Management_Instrumentation_Process.txt       | Windows Management Instrumentation (WMI) Execution          |
| T1053_Scheduled_Task_Process.txt                           | Windows Scheduled Task Activity                             |
| T1054_Indicator_Blocking_Driver_Unloaded.txt               | Windows Defense evasion via Filter Manager                  |
| T1057_Process_Discovery.txt                                | Windows Process Discovery via Tasklist Command              |
| T1070_Indicator_Removal_On_Host.txt                        | Windows Defense Evasion via Windows Event Log Tools         |
| T1117_Bypassing_Application_Whitelisting_With_Regsvr32.txt | Windows Execution via Regsvr32                              |
| T1121_Regsvcs_Regasm.txt                                   | Windows Execution via .NET COM Assemblies                   |
| T1127_Trusted_Developer_Utilities.txt                      | Windows Execution via rusted Developer Utilities            |
| T1128_Netsh_Helper_DLL_Process.txt                         | Windows Persistence via Netshell Helper DLL                 |
| T1138_Application_Shimming_Process.txt                     | Windows Persistence via Application Shimming                |
| T1140_Deobfuscate_Decode_Files_Or_Information.txt          | Windows Defense Evasion - Decoding Using Certutil           |
| T1158_Hidden_Files_And_Directories.txt                     | Windows Defense Evasion or Persistence via Hidden Files     |
| T1170_MSHTA_Process.txt                                    | Windows Execution via Microsoft HTML Application (HTA)      |
| T1179_Hooking.txt                                          | Windows Persistence or Priv Escalation via Hooking          |
| T1191_CMSTP.txt                                            | Windows Execution via Connection Manager                    |
| T1197_BITS_Jobs_Process.txt                                | Windows Persistence via BITS Jobs                           |
| T1202_Indirect_Command_Execution.txt                       | Windows Indirect Command Execution                          |
| T1218_Signed_Binary_Proxy_Execution_Network.txt            | Windows Signed Binary Proxy Execution Download              |
| T1218_Signed_Binary_Proxy_Execution_Process.txt            | Windows Signed Binary Proxy Execution                       |
| T1223_Compiled_HTML_File.txt                               | Windows Execution via Compiled HTML File                    |
