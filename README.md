This is the list of services with their scope(Global, Regional, zonal) I created while studying for CSCI5902: Special topics in Applied Computer Science (Cloud Architecture).
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

One of the biggest issues I face while preparing for AWS Solution Architect exam is getting confused about the services' scope (Global, Regional, zonal). I usually end up doing google everytime I study a service, so I created a list of services with their scopes and grouped it according to its type (example: EC2 will be in compute group), so that easier to remember.

Please help me maintain this list so that its useful for everyone. See the [contribution guidelines](CONTRIBUTING.md)

## Table of Contents

- [Compute](#compute)
- [Storage](#storage)
- [Networking](#networking)
- [Database](#database)
- [Security](#security)
- [Management & Governance](#management--governance)
- [Application Integration](#application-integration)
- [Developer Tools](#developer-tools)
- [Analytics](#analytics)
- [Machine Learning](#machine-learning)
- [Internet of Things (IoT)](#internet-of-things-iot)
- [Contributors](#contributors)
---

## Compute

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | Amazon Elastic Compute Cloud (EC2)                  | Regional                              |
| 2   | EC2 Auto Scaling                                    | Regional                              |
| 3   | EC2 Spot Instances                                  | Regional                              |
| 4   | Elastic Load Balancing (ELB)                        | Regional                              |
| 5   | Elastic Beanstalk                                   | Regional                              |
| 6   | AWS Fargate                                         | Regional                              |
| 7   | AWS Lambda                                          | Regional                              |
| 8   | AWS Batch                                           | Regional                              |
| 9   | Amazon Machine Image (AMI)                          | Regional                              |
| 10  | Security Groups                                     | Regional                              |
| 11  | Elastic Network Interface (ENI)                     | AZ - specific                         |

## Storage

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | Simple Storage Service (S3)                         | Regional                              |
| 2   | Elastic Block Store (EBS)                           | AZ-specific                           |
| 3   | Elastic File System (EFS)                           | Regional                              |
| 4   | Snowball                                            | Regional                              |
| 5   | Storage Gateway                                     | Regional                              |

## Networking

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | Amazon Virtual Private Cloud (VPC)                   | Regional                              |
| 2   | Subnets                                             | AZ-specific                           |
| 3   | Route Tables                                        | Regional                              |
| 4   | Elastic Load Balancer (ELB)                         | Regional                              |
| 5   | Network Load Balancer (NLB)                         | Regional                              |
| 6   | Internet Gateway                                    | Regional                              |
| 7   | NAT Gateway                                         | AZ-specific                           |
| 8   | Elastic IP (EIP)                                    | Regional                              |
| 9   | AWS Direct Connect                                  | Regional                              |
| 10  | AWS Global Accelerator                              | Global                                |
| 11  | Route 53                                            | Global                                |

## Database

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | Amazon RDS                                          | Regional                              |
| 2   | Amazon Aurora                                       | Regional                              |
| 3   | Amazon Redshift                                     | Regional                              |
| 4   | Amazon DynamoDB                                     | Regional                              |
| 5   | Amazon ElastiCache                                  | Regional                              |
| 6   | Amazon Neptune                                      | Regional                              |
| 7   | Amazon DocumentDB                                   | Regional                              |
| 8   | Amazon Keyspaces (for Apache Cassandra)              | Regional                              |
| 9   | AWS Database Migration Service (DMS)                | Regional                              |

## Security

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | Identity and Access Management (IAM)                 | Global                                |
| 2   | AWS Secrets Manager                                 | Regional                              |
| 3   | AWS Key Management Service (KMS)                    | Regional                              |
| 4   | AWS Shield                                          | Global                                |
| 5   | AWS WAF                                             | Global                                |
| 6   | AWS Firewall Manager                                | Regional                              |
| 7   | Amazon GuardDuty                                    | Regional                              |
| 8   | Amazon Macie                                        | Regional                              |
| 9   | AWS Single Sign-On (SSO)                            | Regional                              |
| 10  | AWS Directory Service                               | Regional                              |

## Management & Governance

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | AWS CloudFormation                                  | Regional                              |
| 2   | AWS CloudTrail                                      | Regional                              |
| 3   | AWS Config                                          | Regional                              |
| 4   | AWS Systems Manager                                 | Regional                              |
| 5   | AWS OpsWorks                                        | Regional                              |
| 6   | AWS Service Catalog                                 | Regional                              |
| 7   | AWS CloudWatch                                      | Regional                              |
| 8   | AWS Auto Scaling                                    | Regional                              |
| 9   | AWS Trusted Advisor                                 | Regional                              |
| 10  | AWS Control Tower                                   | Regional                              |
| 11  | AWS AppConfig                                       | Regional                              |
| 12  | AWS Management Console                              | Global                                |

## Application Integration

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | AWS Step Functions                                  | Regional                              |
| 2   | Amazon Simple Queue Service (SQS)                   | Regional                              |
| 3   | Amazon Simple Notification Service (SNS)            | Regional                              |
| 4   | Amazon EventBridge                                  | Regional                              |
| 5   | Amazon MQ                                           | Regional                              |
| 6   | Amazon AppSync                                      | Regional                              |
| 7   | AWS Glue                                            | Regional                              |
| 8   | AWS Data Pipeline                                   | Regional                              |

## Developer Tools

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | AWS CodeStar                                        | Regional                              |
| 2   | AWS CodeCommit                                      | Regional                              |
| 3   | AWS CodeBuild                                       | Regional                              |
| 4   | AWS CodeDeploy                                      | Regional                              |
| 5   | AWS CodePipeline                                    | Regional                              |
| 6   | AWS CodeArtifact                                    | Regional                              |
| 7   | AWS CodeGuru                                        | Regional                              |
| 8   | AWS CodeStar Connections                            | Regional                              |
| 9   | AWS Cloud9                                          | Regional                              |
| 10  | AWS X-Ray                                           | Regional                              |
| 11  | AWS App Runner                                      | Regional                              |

## Analytics

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | Amazon Athena                                       | Regional                              |
| 2   | Amazon EMR                                          | Regional                              |
| 3   | Amazon Kinesis                                      | Regional                              |
| 4   | AWS Glue                                            | Regional                              |
| 5   | AWS Lake Formation                                  | Regional                              |
| 6   | AWS Data Pipeline                                   | Regional                              |
| 7   | Amazon QuickSight                                   | Regional                              |

## Machine Learning

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | Amazon SageMaker                                    | Regional                              |
| 2   | Amazon Comprehend                                   | Regional                              |
| 3   | Amazon Lex                                          | Regional                              |
| 4   | Amazon Rekognition                                  | Regional                              |
| 5   | Amazon Polly                                        | Regional                              |
| 6   | Amazon Translate                                    | Regional                              |
| 7   | Amazon Forecast                                     | Regional                              |
| 8   | Amazon Personalize                                  | Regional                              |
| 9   | Amazon Augmented AI (A2I)                           | Regional                              |
| 10  | AWS DeepLens                                        | Regional                              |

## Internet of Things (IoT)

| No. | Component                                           | Region/AZ/Global                      |
|-----|-----------------------------------------------------|---------------------------------------|
| 1   | AWS IoT Core                                        | Regional                              |
| 2   | AWS IoT Device Management                           | Regional                              |
| 3   | AWS IoT Analytics                                   | Regional                              |
| 4   | AWS IoT Events                                      | Regional                              |
| 5   | AWS IoT SiteWise                                    | Regional                              |
| 6   | AWS IoT Greengrass                                  | Regional                              |
| 7   | AWS IoT Things Graph                                | Regional                              |
| 8   | AWS IoT 1-Click                                     | Regional                              |
| 9   | AWS IoT Button                                      | Regional                              |
| 10  | AWS IoT Events                                      | Regional                              |

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/sksaifuddin"><img src="https://avatars.githubusercontent.com/u/31506305?v=4?s=100" width="100px;" alt="saif"/><br /><sub><b>saif</b></sub></a><br /><a href="#content-sksaifuddin" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/sourav15102"><img src="https://avatars.githubusercontent.com/u/23266046?v=4?s=100" width="100px;" alt="Sourav"/><br /><sub><b>Sourav</b></sub></a><br /><a href="#content-sourav15102" title="Content">🖋</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
