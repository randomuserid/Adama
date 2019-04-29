Windows SQL injection Searches - used by 28006, SQL Injection - Windows SQL Server

| Description                  | Search String                                                        |
|------------------------------|----------------------------------------------------------------------|
| (select @@version)           | %28select%20%40%40version%29                                         |
| (select system_user)         | %28select%20system%5Fuser%29                                         |
| Auth mode query              | %28%28select%20serverproperty%28%27IsIntegratedSecurityOnly%27%29%29 |
| command execution            | xp%5Fcmdshell AND cmd                                                |
| command using temp directory | xp%5Fcmdshell AND cmd AND %25TEMP%25                                 |
| command using temp directory | xp%5Fcmdshell AND cmd AND %23temp%23                                 |
| debug activity               | xp%5Fcmdshell AND cmd AND debug%20%3C                                |
| echo command                 | xp%5Fcmdshell AND cmd AND echo                                       |
| echo command piped           | xp%5Fcmdshell AND cmd AND echo AND %3E%3E                            |
| exec master..xp_cmdshell     | exec%20master%2E%2Exp%5Fcmdshell                                     |
| netcat cmd activity          | xp%5Fcmdshell AND cmd AND nc AND 2De%20cmd%2Eexe                     |
| process started              | xp%5Fcmdshell AND cmd AND %2Eexe                                     |
