Machine learning hunts using the significant terms aggregation

| Pipeline | Term                | Significant Term    | Dependencies              | Notes                                   |
|----------|---------------------|---------------------|---------------------------|-----------------------------------------|
| Auth     | username            | key hash            | .                         | .                                       |
| Auth     | source country      | source city         | .                         | .                                       |
| Auth     | user                | sourceIP            | .                         | .                                       |
| Auth     | user                | source country      | .                         | .                                       |
| Flows    | action              | destination ip      | .                         | .                                       |
| Flows    | action              | sourceip            | .                         | .                                       |
| Flows    | action              | source country      | .                         | .                                       |
| Flows    | action              | destination country | .                         | .                                       |
| Flows    | destination country | destination city    | .                         | .                                       |
| Flows    | source country      | destination ip      | .                         | remote to local                         |
| Flows    | source country      | destination city    | .                         | .                                       |
| Flows    | sourceip            | destip              | .                         | local to remote                         |
| Flows    | sourceip            | protocol            | .                         | local to remote                         |
| Flows    | sourceip            | destination country | .                         | local to remote                         |
| Linux    | euid                | command             | .                         | .                                       |
| Linux    | euid                | syscall name        | .                         | .                                       |
| Linux    | euid                | data.message        | .                         | .                                       |
| Linux    | euid                | ip address          | connect                   | use on local to remote connects         |
| Linux    | euid                | port                | connect                   | use on local to remote connects         |
| Linux    | executable          | command             | .                         | use for interactive user shell commands |
| Linux    | executable          | ip address          | connect                   | use on local to remote connects         |
| Linux    | executable          | port                | connect                   | use on local to remote connects         |
| Linux    | executable          | port                | listen                    | .                                       |
| Linux    | user                | command             | .                         | .                                       |
| Linux    | user                | syscall name        | .                         | .                                       |
| Linux    | user                | data.message        | .                         | .                                       |
| Linux    | username            | ip address          | connect                   | use on local to remote connects         |
| Linux    | username            | port                | connect                   | use on local to remote connects         |
| Nginx    | response            | source IP           | 200s                      | remote to local                         |
| Nginx    | response            | country             | 200s                      | remote to local                         |
| Nginx    | response            | useragent           | 200s                      | remote to local                         |
| Nginx    | uri                 | country             | 200s                      | remote to local                         |
| Nginx    | uri                 | srcip               | 200s                      | remote to local                         |
| Nginx    | verb                | response            | .                         | .                                       |
| Windows  | destIP              | protocol            | .                         | local to remote                         |
| Windows  | destIP              | protocol            | .                         | local to local                          |
| Windows  | hostname            | ip address          | .                         | local to remote                         |
| Windows  | hostname            | port                | .                         | local to remote                         |
| Windows  | hostname            | ip address          | .                         | local to local                          |
| Windows  | hostname            | port                | .                         | local to local                          |
| Windows  | Image               | ParentImage         | .                         | .                                       |
| Windows  | Image               | TargetObject        | use on registry add       | exclude system procs                    |
| Windows  | Image               | ip address          | .                         | local to remote                         |
| Windows  | Image               | port                | .                         | local to remote                         |
| Windows  | Image               | ip address          | .                         | local to local                          |
| Windows  | Image               | port                | .                         | local to local                          |
| Windows  | Image               | TargetObject        | use on registry modify    | exclude system procs                    |
| Windows  | Image               | TargetFileName      | use on file change events | .                                       |
| Windows  | user                | image               | .                         | .                                       |
| Windows  | user                | commandLine         | .                         | .                                       |
| Windows  | user                | TargetObject        | use on registry add       | exclude system procs                    |
| Windows  | user                | ip address          | .                         | local to remote                         |
| Windows  | user                | port                | .                         | local to remote                         |
| Windows  | user                | ip address          | .                         | local to local                          |
| Windows  | user                | port                | .                         | local to local                          |
| Windows  | user                | TargetObject        | use on registry modify    | exclude system procs                    |
| Windows  | user                | TargetFileName      | use on file change events | .                                       |
