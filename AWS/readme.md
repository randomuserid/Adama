![things](/img/pacu.png?raw=true "text")

### AWS / CloudTrail Signal Rules

22 rules for API layer threat hunting using CloudTrail data - except for "Unusual Process Calling Metadata Service" which needs endpoint data like Auditbeat.

| Name                                              |
|---------------------------------------------------|
| AWS Access Key Created by Pacu                    |
| AWS Config Elements Deleted                       |
| AWS Config Service Configuration Elements Deleted |
| AWS Database Instance Modified by Pacu            |
| AWs Database Restored From Snapshot               |
| AWS Root Account Activity                         |
| AWS User Authenticated Without MFA                |
| AWS WAF Enumeration                               |
| AWS WAF Service Configuration Elements Deleted    |
| CloudTrail Deleted                                |
| CloudTrail Disabled                               |
| CloudTrail Mimimized                              |
| EC2 Instance Modified by Pacu                     |
| EC2 Instance User Data Modified                   |
| EC2 Snapshot Attribute Modification               |
| Flow Logs Deleted                                 |
| IAM Enumeration                                   |
| Pacu Activity in CloudTrail logs                  |
| S3 Bucket Public Access Policy Change             |
| Security Group Allowing Any Protocol              |
| Security Group Allowing Any Source IP             |
| Unusual Process Calling Metadata Service          |
