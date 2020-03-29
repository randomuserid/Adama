# Hunting for MSBuild LOLBin Activity and SILENTTRINITY

So MSBuild, the Microsoft Build Engine, is being increasingly used for execution and persistence. This is a collection of searches and rules that were translated from a wide variety of sources (see references.) The SIEM rules are populated with ATT&CK tags and can be imported in the "Signal Detection Rules" page. The searches can be imported as usual in the Kibana Saved Objects page.

Let's start with Execution:
T1127 - Trusted Developer Utilities

Suspicious MSBuild Process Execution

- `process.name: MSBuild.exe and process.parent.name: (cmd.exe or powershell.exe)`

- `process.name: MSBuild.exe and process.parent.name: (excel.exe or winword.exe)`

- `process.name: MSBuild.exe and process.parent.name: explorer.exe`

- `process.name: MSBuild.exe and process.parent.name: mshta.exe`

- `process.name: MSBuild.exe and process.parent.name: wmiprvse.exe`

T1036 - Masquerading - Microsoft Build Engine Executed After Renaming

`winlog.event_data.OriginalFileName:MSBuild.exe and not process.name: MSBuild.exe`

T1500 - Compile After Delivery - Defense Evasion Using the Microsoft Build Engine

`process.parent.name: MSBuild.exe and process.name: (csc.exe or iexplore.exe or powershell.exe)`

T1003  - Credential Dumping - Credential Dumping Using the Microsoft Build Engine

`winlog.event_data.OriginalFileName: (vaultcli.dll or samlib.dll) and process.name:MSBuild.exe and event.action:"Image loaded (rule: ImageLoad)"`

T1055 - Process Injection - Process Injection By the Microsoft Build Engine

`process.name:MSBuild.exe and event.action:"CreateRemoteThread detected (rule: CreateRemoteThread)"`

Inline Task Activity - 	Image Loading By the Microsoft Build Engine

`process.name:MSBuild.exe and event.action:"Image loaded (rule: ImageLoad)" and file.path:*Microsoft.Build.Tasks.v4.0.ni.dll*`

Command and Control - Possible C2 Using the Microsoft Build Engine
- T1043 - Commonly Used Port
- T1071 - Standard Application Layer Protocol

`process.name: MSBuild.exe and event.action:"Network connection detected (rule: NetworkConnect)"`

SILENTTRINTIY is a recent persistence mechanism that utilizes MSBuild along with Iron Python. It makes use of the libraries below but of course these could be renamed so these Image Load events are probably best regarded as secondary indicators to be combined with process or network activity searches above.

Search: Possible SILENTTRINITY Activity Using Iron Python

`winlog.event_data.OriginalFileName: (IronPython.dll or IronPythonModules.dll) and event.action:"Image loaded (rule: ImageLoad)"`

"MSBuild Without MSBuild" is also interesting and needs a behavioral search: https://pentestlaboratories.com/2020/01/27/msbuild-without-msbuild/

references

- https://github.com/MHaggis/CBR-Queries/blob/master/msbuild.md
- https://twitter.com/M_haggis/status/1225853330045333504?s=20
- https://gist.github.com/SwitHak/62fa7f8df378cae3a459670e3a18742d
- https://blog.f-secure.com/hunting-for-silenttrinity/
- https://blog.talosintelligence.com/2020/02/building-bypass-with-msbuild.html
- https://github.com/byt3bl33d3r/SILENTTRINITY
- https://github.com/rvrsh3ll/MSBuildAPICaller
- https://docs.microsoft.com/en-us/visualstudio/msbuild/msbuild?view%253Dvs-2019=&view=vs-2019
