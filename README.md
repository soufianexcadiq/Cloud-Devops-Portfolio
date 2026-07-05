# AWS Cloud & DevOps Portfolio

Welcome to my AWS Cloud and DevOps engineering portfolio.

This portfolio documents ten progressive projects covering CI/CD, infrastructure as code, container orchestration, observability, disaster recovery, security automation, event-driven architecture, Kubernetes and GitOps.

Each project includes architecture diagrams, implementation details, screenshots, operational evidence, security considerations and lessons learned.

## Portfolio Roadmap

[View the complete project roadmap](./AWS-DevOps-Portfolio-Roadmap-Projects.pdf)

## Projects

| # | Project | Technologies | Status |
|---|---------|--------------|--------|
| 01 | [Jenkins ECR to EC2 CI/CD](./projects/01-jenkins-ec2-cicd/) | Jenkins, Docker, ECR, EC2, SSM | Completed ! |
| 02 | Terraform Production Infrastructure | Terraform, VPC, ALB, ECS | Planned |
| 03 | Blue/Green and Canary Deployment | ECS, ALB, CloudWatch | Planned |
| 04 | Monitoring and Observability | CloudWatch, SNS, OpenTelemetry | Planned |
| 05 | Disaster Recovery | AWS Backup, EBS, RDS, S3 | Planned |
| 06 | Security Automation | Security Hub, GuardDuty, Config, Lambda | Planned |
| 07 | Event-Driven Automation | S3, Lambda, DynamoDB, SNS | Planned |
| 08 | Kubernetes on Amazon EKS | EKS, Kubernetes, HPA, ALB | Planned |
| 09 | GitOps Platform | GitHub Actions, Terraform, Argo CD | Planned |
| 10 | Enterprise Cloud Platform | Complete AWS production architecture | Planned |

## Current Project

### Project 01: Jenkins ECR to EC2 CI/CD

The first project builds an automated deployment pipeline:

```text
GitHub → Jenkins → Docker → Amazon ECR → Systems Manager → EC2
