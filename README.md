# Signpost
## Description of your project

**Signpost** *is a project for XXXXXXXXXXXXXXXX*



>This project provides a bsic implementation of XXXXXXXXX


`Code Section or code snippet `

This project sets up the following:
- A highly available architecture that spans three Availability Zones.*
- A VPC configured with public and private subnets, according to AWS best practices, to provide you with your own virtual network.*
- In the public subnets:
  - Managed network address translation (NAT) gateways to allow outbound internet access for resources in the private subnets.*
  - A Linux bastion host in an Auto Scaling group to allow inbound Secure Shell (SSH) access to Amazon Elastic Compute Cloud (Amazon EC2) instances in public and private subnets.*
- In the private subnets, installed as highly available clusters:
  - The Solumina proprietary software.
  –	Amazon Elasticsearch Service (Amazon ES).
  - A MongoDB resource.
  - Amazon Relational Database Service (Amazon RDS).
- An Application Load Balancer to route traffic to the Solumina web application over HTTPS.
- Amazon Elastic Kubernetes Service (Amazon EKS).
- An Amazon S3 bucket for storing Quick Start assets.
- Amazon Elastic File System (Amazon EFS) to provide on-demand scaling and management of AWS Cloud services and resources.
