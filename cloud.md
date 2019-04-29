Searches using Cloud API and log event data

| Event Type       | Category             | Search Name                                                                                     |
|------------------|----------------------|-------------------------------------------------------------------------------------------------|
| Flows            | Behavioral Detection | Website Welcome                                                                                 |
| API Events       | Behavioral Detection | VPC CRUD events (creates, changes, deletes)                                                     |
| API Events       | Behavioral Detection | User data set by Pacu                                                                           |
| API Events       | Behavioral Detection | Uncommon service/API usage                                                                      |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Container Logs   | Behavioral Detection | Suspicious container creation                                                                   |
| Container Logs   | Behavioral Detection | Suspicious container change                                                                     |
| Container Logs   | Behavioral Detection | Staaldraad                                                                                      |
| Host Logs        | Persistence          | SSH login on automated instance                                                                 |
| S3 Logs          | Discovery            | Special data access in S3                                                                       |
| Auth             | Initial Access       | Simultaneous API access from different countries                                                |
| API Events       | Execution            | Shell payload in metadata                                                                       |
| API Events       | Privilege Elevation  | Setting default IAM policy version                                                              |
| API Events       | Privilege Elevation  | Sensitive changes to user permissions                                                           |
| API Events       | Behavioral Detection | SAML config changes                                                                             |
| S3 Logs          | Initial Access       | S3 download by remote caller                                                                    |
| S3 Logs          | Privilege Elevation  | S3 Bucket permission changes                                                                    |
| S3 Logs          | Privilege Elevation  | S3 Bucket permission changes                                                                    |
| S3 Logs          | Initial Access       | S3 auth successful, remote                                                                      |
| S3 Logs          | Initial Access       | S3 auth failed, remote                                                                          |
| S3 Logs          | Initial Access       | S3 activity, remote caller                                                                      |
| Auth             | Initial Access       | Root account usage, remote                                                                      |
| Auth             | Initial Access       | Root account usage, anomalous                                                                   |
| Auth             | Initial Access       | Root account MFA config changes                                                                 |
| S3 Logs          | Behavioral Detection | Rogue s3 bucket                                                                                 |
| API Events       | Behavioral Detection | Rogue ec2 instance with user data                                                               |
| API Events       | Behavioral Detection | Rogue ec2 instance                                                                              |
| Container Logs   | Behavioral Detection | Remote network connection by hypervisor process                                                 |
| Container Logs   | Behavioral Detection | Remote network connection by container host                                                     |
| Host Logs        | Persistence          | RDP login on automated instance                                                                 |
| Flows            | Behavioral Detection | Rackspace                                                                                       |
| API Events       | Behavioral Detection | Public IP associated with an instance                                                           |
| API Events       | Behavioral Detection | Prowler activity                                                                                |
| API Events       | Behavioral Detection | Passing a role to Data Pipeline                                                                 |
| API Events       | Behavioral Detection | Passing a role to cloudformation                                                                |
| API Events       | Behavioral Detection | Passing a role to a Glue Development Endpoint                                                   |
| API Events       | Behavioral Detection | Pacu activity                                                                                   |
| Flows            | Behavioral Detection | OVH                                                                                             |
| Auth             | Initial Access       | Non-MFA root login                                                                              |
| API Events       | Persistence          | New instance launched in service vpc                                                            |
| S3 Logs          | Discovery            | NAT private key access in S3                                                                    |
| Auth             | Initial Access       | Multiple failed logins                                                                          |
| Container Logs   | Persistence          | Manual container instantiation                                                                  |
| Container Logs   | Behavioral Detection | Lxc-ls command                                                                                  |
| Container Logs   | Behavioral Detection | Lxc-console command                                                                             |
| Flows            | Behavioral Detection | Ipage                                                                                           |
| API Events       | Initial Access       | Internal IAM credentials used from external sources                                             |
| API Events       | Behavioral Detection | Interesting guardduty alert                                                                     |
| API Events       | Behavioral Detection | Interesting config alert                                                                        |
| API Events       | Behavioral Detection | Interesting  macie alert                                                                        |
| Process Creation | Exploitation         | Interactive shell commands on automated instance                                                |
| API Events       | Persistence          | Instance launched in service VPC                                                                |
| S3 Logs          | Discovery            | Instance key access in S3                                                                       |
| API Events       | Behavioral Detection | Insecure security group created                                                                 |
| API Events       | Behavioral Detection | Insecure network ACL created                                                                    |
| API Events       | Privilege Elevation  | Identity And Access Management  (IAM) CRUD                                                      |
| Auth             | Initial Access       | IAM credentials from anomalous source IP                                                        |
| API Events       | Privilege Elevation  | IAM change from EC2 instance                                                                    |
| API Events       | Privilege Elevation  | IAM change from anomalous source                                                                |
| Flows            | Behavioral Detection | Hetzner Online                                                                                  |
| Flows            | Behavioral Detection | Google?                                                                                         |
| Flows            | Behavioral Detection | Go Daddy                                                                                        |
| S3 Logs          | Behavioral Detection | Foreign S3 bucket activity                                                                      |
| Container Logs   | Execution            | Execution from current path (./*)                                                               |
| Container Logs   | Execution            | Execution from /tmp                                                                             |
| Container Logs   | Initial Access       | Etcd access from the Internet                                                                   |
| API Events       | Behavioral Detection | Elderly instance                                                                                |
| Flows            | Behavioral Detection | Dreamhost                                                                                       |
| Container Logs   | Collection           | Docker tcpdump activity                                                                         |
| Flows            | Behavioral Detection | Digital Ocean                                                                                   |
| S3 Logs          | Discovery            | Crypto key access in S3                                                                         |
| API Events       | Discovery            | Credential/permission enumeration                                                               |
| API Events       | Privilege Elevation  | Creation/Deletion Of Groups                                                                     |
| API Events       | Privilege Elevation  | Creation of new IAM policy                                                                      |
| API Events       | Initial Access       | Console / API activity from anomalous IP or geo                                                 |
| Flows            | Behavioral Detection | Cloudflare                                                                                      |
| API Events       | Privilege Elevation  | Changes to user accounts/logging/detection configurations                                       |
| Flows            | Behavioral Detection | CDN                                                                                             |
| Flows            | Behavioral Detection | Bluehost                                                                                        |
| Flows            | Behavioral Detection | Blockdos                                                                                        |
| API Events       | Behavioral Detection | Billing in unused regions                                                                       |
| API Events       | Behavioral Detection | Billing for new services                                                                        |
| Container Logs   | Execution            | Bash activity by hypervisor process                                                             |
| Container Logs   | Execution            | Bash activity by a container process                                                            |
| Flows            | Behavioral Detection | Azure                                                                                           |
| API Events       | Discovery            | AWS Exploration https://danielgrzelak.com/exploring-an-aws-account-after-pwning-it-ff629c2aae39 |
| API Events       | Defense Evasion      | Attempts to encrypt Cloudtrail                                                                  |
| API Events       | Defense Evasion      | Attempts to disable cloudtrail                                                                  |
| Auth             | Initial Access       | Attempted activity from terminated accounts/credentials/keys                                    |
| API Events       | Behavioral Detection | Anomalous updateloginprofile                                                                    |
| API Events       | Behavioral Detection | Anomalous updatefunctioncode                                                                    |
| API Events       | Behavioral Detection | Anomalous updateassumerolepolicy                                                                |
| API Events       | Behavioral Detection | Anomalous snapshot sharing                                                                      |
| S3 Logs          | Behavioral Detection | Anomalous S3 activity                                                                           |
| Container Logs   | Execution            | Anomalous process on Kubernetes server                                                          |
| API Events       | Behavioral Detection | Anomalous policy update                                                                         |
| Flows            | Behavioral Detection | Anomalous management / consumer instance traffic                                                |
| Container Logs   | Behavioral Detection | Anomalous Kubernetes service access                                                             |
| Container Logs   | Behavioral Detection | Anomalous Kubernetes server connection outbound                                                 |
| API Events       | Behavioral Detection | Anomalous key sharing                                                                           |
| API Events       | Behavioral Detection | Anomalous key activity                                                                          |
| API Events       | Behavioral Detection | Anomalous instance profile activity                                                             |
| API Events       | Persistence          | Anomalous Google cloud shell                                                                    |
| API Events       | Behavioral Detection | Anomalous data transfer charges                                                                 |
| S3 Logs          | Discovery            | Anomalous crypto key access in S3                                                               |
| S3 Logs          | Discovery            | Anomalous crypto key access in S3                                                               |
| API Events       | Behavioral Detection | Anomalous createloginprofile                                                                    |
| API Events       | Behavioral Detection | Anomalous create user                                                                           |
| API Events       | Behavioral Detection | Anomalous create access keys                                                                    |
| API Events       | Behavioral Detection | Anomalous billing spikes                                                                        |
| API Events       | Behavioral Detection | Anomalous attachuserpolicy                                                                      |
| API Events       | Behavioral Detection | Anomalous API calls                                                                             |
| API Events       | Privilege Elevation  | Anomalous addusertogroup                                                                        |
| Container Logs   | Behavioral Detection | Anomalous activity by virtualization processes                                                  |
| Container Logs   | Behavioral Detection | Anomalous activity by hypervisor process                                                        |
| Container Logs   | Behavioral Detection | Anomalous activity by a container host                                                          |
| Flows            | Behavioral Detection | Akamai                                                                                          |
| API Events       | Privilege Elevation  | Add/Remove Group Members                                                                        |
| API Events       | Behavioral Detection | Activity in inactive regions                                                                    |
| Container Logs   | Privilege Elevation  | /etc/passwd or /etc/shadow activity                                                             |
