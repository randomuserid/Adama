# Detecting attacks on Sysmon and Winlogbeat

Recent research was published on on methods of selectively deleting messages in the Sysmon / Winlogbeat queue. This technique requires injecting the Winlogbeat process which can be detected with Sysmon event 7, CreateRemoteThread detected, like this:

- `winlog.event_data.TargetImage:*winlogbeat.exe and event.action:"CreateRemoteThread detected (rule: CreateRemoteThread)"``

T1036 - Masquerading - Microsoft Build Engine Executed After Renaming

`winlog.event_data.OriginalFileName:MSBuild.exe and not process.name: MSBuild.exe`

T1055 - Process Injection - Process Injection By the Microsoft Build Engine

`process.name:MSBuild.exe and event.action:"CreateRemoteThread detected (rule: CreateRemoteThread)"`

Inline Task Activity - 	Image Loading By the Microsoft Build Engine

`process.name:MSBuild.exe and event.action:"Image loaded (rule: ImageLoad)" and file.path:*Microsoft.Build.Tasks.v4.0.ni.dll*`



references

- https://github.com/MHaggis/CBR-Queries/blob/master/msbuild.md
- https://twitter.com/M_haggis/status/1225853330045333504?s=20
- https://gist.github.com/SwitHak/62fa7f8df378cae3a459670e3a18742d
- https://blog.f-secure.com/hunting-for-silenttrinity/
- https://blog.talosintelligence.com/2020/02/building-bypass-with-msbuild.html
- https://github.com/byt3bl33d3r/SILENTTRINITY
- https://github.com/rvrsh3ll/MSBuildAPICaller
- https://docs.microsoft.com/en-us/visualstudio/msbuild/msbuild?view%253Dvs-2019=&view=vs-2019
