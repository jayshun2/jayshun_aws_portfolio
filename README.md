# jayshun_aws_portfolio
Hands-on AWS projects showcasing core cloud engineering skills using S3, EC2, Lambda, and more. Built for certification prep, portfolio growth, and real-world deployment scenarios.

# 🧠 AWS Cloud Portfolio

Welcome to my AWS Cloud Portfolio! This repository has been broken out into multiple repos. This is so I could segregate my projects into individual items, and make it easier to manage. Here is a list of my AWS Projects. Thank you
---
## Phase 1: Foundations
| Project | Description | Core Services Used | Project Status |
|------|-------|-------|-------|
|[Cloud Resume Challenge](https://github.com/jayshun2/Cloud-Resume-Challenge)| (Repo is currently private. Security audit before release is required to ensure no leaked credentials, sorry!) The Cloud Resume Challenge is a full-stack cloud engineering project that guides you through building and deploying a personal resume website entirely in the cloud. It involves using services like AWS S3, CloudFront, Route 53, API Gateway, Lambda, and DynamoDB to create a secure, scalable, and dynamic site. You write infrastructure as code with tools like Terraform and automate deployments with GitHub Actions, demonstrating real-world DevOps practices. Designed to showcase your practical skills, the challenge helps you build a professional portfolio project that proves your ability to design and manage cloud infrastructure from end to end. | S3, CloudFront, Route53, Lambda, API Gateway, DynamoDB | In Progress |
| [S3 Static Website](https://github.com/jayshun2/s3StaticWebsite) | The static website at hello.awsportfolio.jayfrench.cloud is a simple, fast-loading personal site hosted on Amazon S3 and delivered securely via CloudFront. | S3, CloudFront, Route53, ACM | Completed |
| [Pre-Signed URLs](https://github.com/jayshun2/PRJ002-S3PreSignedURL) | The pre-signed URL project uses the AWS CLI to generate secure, time-limited URLs that grant temporary access to private objects stored in an S3 bucket. The project demonstrates how to control access at the object level using pre-signed URLs directly from the command line, showing how AWS handles fine-grained access without making the files public. | S3, IAM, AWS CLI | Completed |
| [EC2 SSH](https://github.com/jayshun2/PRJ003-EC2_SSH) | This project walks through launching a Linux-based EC2 instance on Amazon Web Services (AWS) and securely connecting to it via SSH. This is a foundational skill for anyone getting started with AWS or cloud infrastructure. You'll gain practical experience with virtual machines, secure access control, and basic network configuration in the AWS environment. | EC2, VPC, Security Groups, Key Pairs | Completed |
| [VPC Public and Private Subnets](https://github.com/jayshun2/PRJ004-VPC-Subnets) | Create a secure and scalable AWS network using a Virtual Private Cloud (VPC) with public and private subnets. This project demonstrates how to separate internet-facing resources from internal infrastructure using best practices like NAT gateways, route tables, and subnet isolation. | VPC, Subnets, Internet Gateway (IGW), NAT Gateway, Route Tables, EC2 | Completed |
| [IAM Access - GUI, CLI, and Terraform](https://github.com/jayshun2/PRJ005-iam-access) | This repository contains three implementations—GUI, CLI, and Terraform—for creating IAM users, groups, and roles with fine-grained permissions in AWS. Each version demonstrates a different way to manage secure access control using best practices. | IAM, AWS CLI, Terraform, IAM Policies, IAM Roles | Completed |
| [Set up and test an S3 lifecycle policy for storage class transitions](https://github.com/jayshun2/PRJ006-S3-Lifecycle-Policies/) | This project sets up an Amazon S3 lifecycle policy that automatically transitions files between storage classes, helping reduce costs as data ages. It also includes testing and verification using S3 Inventory to ensure the policy works as intended. | S3, S3 Policies | Completed |
| [S3 versioning and MFA Delete](https://github.com/jayshun2/PRJ007-S3-MFA-Delete) | Amazon S3 bucket with versioning and MFA delete to protect data by keeping every file change and requiring multi factor authentication for permanent deletions. | S3, IAM, AWS CLI | Completed |
| CloudWatch alarms for EC2 CPU usage | This project sets up a CloudWatch alarm to monitor EC2 CPU usage and send notifications when performance crosses a defined threshold. | CloudWatch, EC2 | Delivery by 8/24/2025 |
| Tracking API activity on account with CloudTrail | | AWS CLI, CloudTrail | Planning |
| AWS Budgets and Cost Alerts | | | Planning |
| Build a simple Lambda function triggered by an S3 upload ||||
| Host a static portfolio on Amplify with custom domain ||||
|Use Systems Manager Session Manager to connect to EC2 without SSH ||||
---
## Phase 2: IaC, Automation, and DevOps
| Project | Description | Core Services Used | Project Status |
|------|-------|-------|-------|
| Deploy a static site using CloudFormation ||||
| Use the AWS CLI to automate S3 file uploads and bucket creation ||||
| Create an IAM policy document and attach it using Terraform ||||
| Launch an EC2 instance using Terraform ||||
| Set up GitHub Actions to deploy changes to an S3-hosted site ||||
| Create a CodeCommit repo and trigger CodePipeline for CI/CD ||||
| Build a basic CloudFormation template for a 2-tier web app ||||
| Automate EC2 backups using Lambda and CloudWatch Events ||||
| Create a Terraform module for reusable EC2/VPC code ||||
| Configure Cloud9 as your cloud-based IDE and develop Python apps ||||
| Set up CodeBuild to run unit tests on a Lambda function ||||
| Use AWS Parameter Store to store secrets securely ||||
| Create an AWS Organization and apply SCPs to member accounts ||||
---
## Phase 3: Serverless and Data Services
| Project | Description | Core Services Used | Project Status |
|------|-------|-------|-------|
| Build an API with API Gateway + Lambda + DynamoDB ||||
| Add CORS support to your API Gateway ||||
| Create a Lambda@Edge function to customize CloudFront behavior ||||
| Use Step Functions to orchestrate multi-step Lambda workflows ||||
| Set up S3 event notification to trigger a Lambda (image processing) ||||
| Create a basic Cognito user pool and implement sign-up/sign-in ||||
| Secure your API with API Gateway + Cognito authorizer ||||
| Schedule a Lambda job using EventBridge (e.g., daily email) ||||
| Build a contact form using SES + Lambda + API Gateway ||||
| Analyze S3 access logs using Athena ||||
| Store objects in S3 Glacier and restore them ||||
| Build a real-time dashboard with DynamoDB Streams + Lambda ||||
| Configure an S3 bucket as a data lake source (partitioned by prefix) ||||
---
## Phase 4: Monitoring, Scaling, Security
| Project | Description | Core Services Used | Project Status |
|------|-------|-------|-------|
| Enable GuardDuty and investigate sample findings ||||
| Create a custom metric in CloudWatch with PutMetricData ||||
| Visualize metrics using CloudWatch dashboards ||||
| Set up a WAF to block malicious traffic on CloudFront ||||
| Use Auto Scaling Groups to scale EC2 based on CPU ||||
| Attach an Application Load Balancer to EC2 fleet ||||
| Set up AWS Backup for RDS, EC2, and EFS ||||
| Build a fault-tolerant WordPress site using RDS Multi-AZ + EC2 + ALB ||||
| Configure VPC peering between two regions ||||
| Use AWS Transit Gateway to connect multiple VPCs ||||
| Set up hybrid connectivity using Site-to-Site VPN (simulated) ||||
| Design a Well-Architected Review using AWS WA Tool ||||
