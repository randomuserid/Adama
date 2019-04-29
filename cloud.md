Searches using Cloud API and log event data

| Event Type       | Category             | Search Name                                                                                     |
|------------------|----------------------|-------------------------------------------------------------------------------------------------|
| Flows            | Behavioral Detection | Akamai                                                                                          |
| Flows            | Behavioral Detection | Azure                                                                                           |
| Flows            | Behavioral Detection | BlockDOS                                                                                        |
| Flows            | Behavioral Detection | BlueHost                                                                                        |
| Flows            | Behavioral Detection | CDN                                                                                             |
| Flows            | Behavioral Detection | CloudFlare                                                                                      |
| Flows            | Behavioral Detection | Digital Ocean                                                                                   |
| Flows            | Behavioral Detection | Dreamhost                                                                                       |
| Flows            | Behavioral Detection | Go Daddy                                                                                        |
| Flows            | Behavioral Detection | Google?                                                                                         |
| Flows            | Behavioral Detection | Hetzner Online                                                                                  |
| Flows            | Behavioral Detection | iPage                                                                                           |
| Flows            | Behavioral Detection | OVH                                                                                             |
| Flows            | Behavioral Detection | Rackspace                                                                                       |
| Flows            | Behavioral Detection | Website Welcome                                                                                 |
| S3 Logs          | Discovery            | Anomalous crypto key access in S3                                                               |
| S3 Logs          | Discovery            | Anomalous crypto key access in S3                                                               |
| S3 Logs          | Behavioral Detection | Anomalous S3 activity                                                                           |
| S3 Logs          | Discovery            | Crypto key access in S3                                                                         |
| S3 Logs          | Behavioral Detection | Foreign S3 bucket activity                                                                      |
| S3 Logs          | Discovery            | Instance key access in S3                                                                       |
| S3 Logs          | Discovery            | NAT private key access in S3                                                                    |
| S3 Logs          | Behavioral Detection | rogue s3 bucket                                                                                 |
| S3 Logs          | Initial Access       | S3 activity, remote caller                                                                      |
| S3 Logs          | Initial Access       | S3 auth failed, remote                                                                          |
| S3 Logs          | Initial Access       | S3 auth successful, remote                                                                      |
| S3 Logs          | Privilege Elevation  | S3 Bucket permission changes                                                                    |
| S3 Logs          | Privilege Elevation  | S3 Bucket permission changes                                                                    |
| S3 Logs          | Initial Access       | S3 download by remote caller                                                                    |
| S3 Logs          | Discovery            | Special data access in S3                                                                       |
| API Events       | Behavioral Detection | Activity in inactive regions                                                                    |
| API Events       | Privilege Elevation  | Add/Remove Group Members                                                                        |
| API Events       | Privilege Elevation  | Anomalous AddUserToGroup                                                                        |
| API Events       | Behavioral Detection | anomalous API calls                                                                             |
| API Events       | Behavioral Detection | Anomalous AttachUserPolicy                                                                      |
| API Events       | Behavioral Detection | anomalous billing spikes                                                                        |
| API Events       | Behavioral Detection | Anomalous create access keys                                                                    |
| API Events       | Behavioral Detection | Anomalous create user                                                                           |
| API Events       | Behavioral Detection | Anomalous createLoginProfile                                                                    |
| API Events       | Behavioral Detection | anomalous data transfer charges                                                                 |
| API Events       | Behavioral Detection | Anomalous instance profile activity                                                             |
| API Events       | Behavioral Detection | Anomalous key activity                                                                          |
| API Events       | Behavioral Detection | Anomalous key sharing                                                                           |
| API Events       | Behavioral Detection | Anomalous policy update                                                                         |
| API Events       | Behavioral Detection | Anomalous snapshot sharing                                                                      |
| API Events       | Behavioral Detection | Anomalous UpdateAssumeRolePolicy                                                                |
| API Events       | Behavioral Detection | Anomalous UpdateFunctionCode                                                                    |
| API Events       | Behavioral Detection | Anomalous UpdateLoginProfile                                                                    |
| API Events       | Defense Evasion      | attempts to disable cloudtrail                                                                  |
| API Events       | Defense Evasion      | attempts to encrypt Cloudtrail                                                                  |
| API Events       | Discovery            | AWS Exploration https://danielgrzelak.com/exploring-an-aws-account-after-pwning-it-ff629c2aae39 |
| API Events       | Behavioral Detection | billing for new services                                                                        |
| API Events       | Behavioral Detection | billing in unused regions                                                                       |
| API Events       | Privilege Elevation  | Changes to user accounts/logging/detection configurations                                       |
| API Events       | Initial Access       | console / API activity from anomalous IP or geo                                                 |
| API Events       | Privilege Elevation  | creation of new IAM policy                                                                      |
| API Events       | Privilege Elevation  | Creation/Deletion Of Groups                                                                     |
| API Events       | Discovery            | Credential/permission enumeration                                                               |
| API Events       | Behavioral Detection | elderly instance                                                                                |
| API Events       | Privilege Elevation  | IAM change from anomalous source                                                                |
| API Events       | Privilege Elevation  | IAM change from EC2 instance                                                                    |
| API Events       | Privilege Elevation  | Identity And Access Management  (IAM) CRUD                                                      |
| API Events       | Behavioral Detection | Insecure network ACL created                                                                    |
| API Events       | Behavioral Detection | Insecure security group created                                                                 |
| API Events       | Persistence          | Instance launched in service VPC                                                                |
| API Events       | Behavioral Detection | Interesting  macie alert                                                                        |
| API Events       | Behavioral Detection | Interesting config alert                                                                        |
| API Events       | Behavioral Detection | Interesting guardduty alert                                                                     |
| API Events       | Initial Access       | Internal IAM credentials used from external sources                                             |
| API Events       | Persistence          | New instance launched in service vpc                                                            |
| API Events       | Behavioral Detection | Pacu activity                                                                                   |
| API Events       | Behavioral Detection | Passing a role to a Glue Development Endpoint                                                   |
| API Events       | Behavioral Detection | Passing a role to CloudFormation                                                                |
| API Events       | Behavioral Detection | Passing a role to Data Pipeline                                                                 |
| API Events       | Behavioral Detection | prowler activity                                                                                |
| API Events       | Behavioral Detection | Public IP associated with an instance                                                           |
| API Events       | Behavioral Detection | rogue ec2 instance                                                                              |
| API Events       | Behavioral Detection | rogue ec2 instance with user data                                                               |
| API Events       | Behavioral Detection | SAML config changes                                                                             |
| API Events       | Privilege Elevation  | Sensitive changes to user permissions                                                           |
| API Events       | Privilege Elevation  | Setting default IAM policy version                                                              |
| API Events       | Execution            | shell payload in metadata                                                                       |
| API Events       | Behavioral Detection | Uncommon service/API usage                                                                      |
| API Events       | Behavioral Detection | user data set by Pacu                                                                           |
| API Events       | Behavioral Detection | VPC CRUD events (creates, changes, deletes)                                                     |
| Auth             | Initial Access       | Attempted activity from terminated accounts/credentials/keys                                    |
| Auth             | Initial Access       | IAM credentials from anomalous source IP                                                        |
| Auth             | Initial Access       | Multiple failed logins                                                                          |
| Auth             | Initial Access       | Non-MFA root login                                                                              |
| Auth             | Initial Access       | Root account MFA config changes                                                                 |
| Auth             | Initial Access       | Root account usage, anomalous                                                                   |
| Auth             | Initial Access       | Root account usage, remote                                                                      |
| Auth             | Initial Access       | Simultaneous API access from different countries                                                |
| Container Logs   | Privilege Elevation  | /etc/passwd or /etc/shadow activity                                                             |
| Container Logs   | Behavioral Detection | anomalous activity by a container host                                                          |
| Container Logs   | Behavioral Detection | anomalous activity by hypervisor process                                                        |
| Container Logs   | Behavioral Detection | anomalous activity by virtualization processes                                                  |
| Container Logs   | Behavioral Detection | Anomalous Kubernetes server connection outbound                                                 |
| Container Logs   | Behavioral Detection | Anomalous Kubernetes service access                                                             |
| Container Logs   | Execution            | Anomalous process on Kubernetes server                                                          |
| Container Logs   | Execution            | bash activity by a container process                                                            |
| Container Logs   | Execution            | bash activity by hypervisor process                                                             |
| Container Logs   | Collection           | docker tcpdump activity                                                                         |
| Container Logs   | Execution            | execution from /tmp                                                                             |
| Container Logs   | Execution            | execution from current path (./*)                                                               |
| Container Logs   | Behavioral Detection | lxc-console command                                                                             |
| Container Logs   | Behavioral Detection | lxc-ls command                                                                                  |
| Container Logs   | Behavioral Detection | remote network connection by container host                                                     |
| Container Logs   | Behavioral Detection | remote network connection by hypervisor process                                                 |
| Container Logs   | Behavioral Detection | Staaldraad                                                                                      |
| Container Logs   | Behavioral Detection | suspicious container change                                                                     |
| Container Logs   | Behavioral Detection | suspicious container creation                                                                   |
| Container Logs   | Initial Access       | etcd access from the Internet                                                                   |
| Container Logs   | Persistence          | Manual container instantiation                                                                  |
| Process Creation | Exploitation         | interactive shell commands on automated instance                                                |
| API Events       | Persistence          | Anomalous Google cloud shell                                                                    |
| Host Logs        | Persistence          | RDP login on automated instance                                                                 |
| Host Logs        | Persistence          | SSH login on automated instance                                                                 |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Cloudtrail       | Defense Evasion      | Tampering with Cloudtrail:                                                                      |
| Flows            | Behavioral Detection | Anomalous management / consumer instance traffic                                                |
