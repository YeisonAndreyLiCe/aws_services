## Compute in AWS

- Instances (EC2)
- Containers (ECS)(ECR)
- Functions (Lambda)
- Edges

## EC2 (Elastic compute cloud)

Virtual machines (EC2 instances)
Payment under demand (per hour)

## Containers

- Docker
- Amazon Elastic Container Service

# Amazon Aurora

Compatibility whit MySQL and postgresSQL

# Amazon RDS

Configuration, use and scaling of databases engines

# Amazon Redshit

Analytics

# key-value pair databases

DynamoDB - noSQL

# Database in Memory

ElastiCache

# Amazon DocumentDB

MongoDB compatibility

# Dynamo db

## Partition key

Dynamo uses hash partitioning to spread data across partitions. The partition key is used to determine the partition in which the item will be stored. The partition key must be unique for each item in the table. The partition key is also known as the hash attribute.

- Partitions 10-GB units.

- Dynamo stores data as groups of attributes (items). Those items are stored and retrieved using a primary key.

### How to choose a partition key

- High-cardinality
- Compose attributes
- Add random suffix

## Sort Key (Sort key)

## Security in the cloud

- IAM (Identity and Access Management)
- AWS Organizations
- AWS Directory Service
- AWS Certificate Manager
- AWS Key Management Service
- AWS CloudHSM
- AWS Shield
- AWS WAF
- AWS Inspector
- AWS Macie
- AWS Artifact
- AWS Security Hub

---

# Security

## Share responsibility model

- AWS is the responsibly for the security in the cloud.
- The customer is the responsibility for the security in the data center.

## AWS Identity and Access Management (IAM)

- Users
- Groups
- Roles
  - Allows to give access to a user to our account from another aws account
- Policies

## AWS Shield (DDoS)

- DDoS protection
- Standard
- Advanced

## AWS WAF (web application firewall)

- Web Application Firewall
- Protects web applications
- Protects APIs
- Protects CloudFront

## Amazon Inspector

- Automated security assessment
- Security best practices
- Vulnerability assessment

## AWS trusted advisor

- Security
- Performance
- Cost
- Fault tolerance
- Service limits

## AWS GardDuty

- Threat detection
- Threat intelligence
- Threat analysis
- Machine learning analysis

## AWS Organizations

- Consolidated billing
- Service control policies
- Consolidated view of accounts

## AWS Directory Service

- Microsoft Active Directory
- Simple AD
- AD Connector

## AWS Certificate Manager

- SSL/TLS certificates
- Free
- Automated
- Secure

## AWS Key Management Service

- Encryption keys
- Secure
- Managed
- Auditable

## AWS CloudHSM

- Hardware Security Module
- FIPS 140-2 Level 3
- Hardware-based key storage
- Hardware-based encryption

## AWS Macie

- Security and data discovery
- Data classification
- Data discovery
- Data security

## AWS Artifact

- Compliance reports
- Security reports
- Audit reports

---

## AWS CLI

- Command line interface
- Configure
- Create

## AWS SDK

- Software development kit
- Configure
- Create

## Serverless

- Lambda
- API Gateway
- DynamoDB
- S3

Paying for operations. No management of a runtime vm.
Can pair cyclical workloads.
Leverage many workloads on a group of virtual machines.

- Benefits
  - Cost savings
  - Separation
  -
