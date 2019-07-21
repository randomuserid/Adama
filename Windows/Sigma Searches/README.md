
### Rewritten Sigma Rules for ELK

So I was asked to take a look at getting the Sigma rules working in ELK. There are syntax issues with things like wildcards and special characters and there appears to be limited support for ECS (the Elastic common schema) which is needed in order to make searches portable. These are rewrites of the Sigma rules for ELK in KQL (Kibana Query Language) and ECS from scratch; I have looked at the Sigma rules one by one and created new KQL searches that look for the same things. I have mapped the MITRE ATT&CK categories from the originals to the new searches.

### Contents

SpaceCake to Sigma Matrix: these are a cross reference of the new searches and the original Sigma rules. I have mapped the MITRE ATT&CK categories from the originals to the new searches.

Process Event Searches -  these are rewrites of the Sigma rules from the "process_creation" folder. They work on sysmon process creation events.

Windows Event Log Searches - these are rewrites of the Sigma rules from the "builtin" folder. They work on Windows event log events.
