# Detecting attacks on Sysmon and Winlogbeat

Recent research was published on on methods of tampering with messages in the Sysmon / Winlogbeat queue. The most interesting technique in the set, which allows for selective message manipulation, requires injecting the Winlogbeat process on the host. Process injection can be detected with Sysmon event 7, CreateRemoteThread detected, like this:

- `winlog.event_data.TargetImage:*winlogbeat.exe and event.action:"CreateRemoteThread detected (rule: CreateRemoteThread)"`

Changes to the Sysmon and Winlogbeat configuration files could also lead to classes of events being dropped. These can be detected with Sysmon event 11, File created;

- `event.action: "File created (rule: FileCreate)" and file.path: *Sysmon* and *xml`
- `event.action: "File created (rule: FileCreate)" and file.path: *winlogbeat* and *yml`

Finally, termination of either process can be detected using Sysmon event 5, Process terminated;

- `process.name: (Sysmon64.exe or Sysmon.exe) and event.action: "Process terminated (rule: ProcessTerminate)"`
- `process.name:winlogbeat.exe and event.action: "Process terminated (rule: ProcessTerminate)"`

All of these are included as rules in the tampering.ndjson SIEM rules file herein. References:

- https://twitter.com/dottor_morte/status/1243134039772606464?s=20
- https://riccardoancarani.github.io/2020-03-21-fooling-the-blue-team-abusing-insecure-elk/
- https://github.com/FuzzySecurity/Fermion
- https://www.fuzzysecurity.com/tutorials/29.html
\
