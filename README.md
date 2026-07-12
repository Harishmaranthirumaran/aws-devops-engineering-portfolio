# AWS DevOps Engineering Portfolio

[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com)
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)](https://terraform.io)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)

A structured collection of hands-on AWS and DevOps engineering projects covering cloud infrastructure, platform engineering, observability, security, and automation. Each project is a standalone implementation with Terraform IaC, application code, architecture documentation, and operational runbooks.

## Project Tracks

### Foundational Delivery
| Project | Description | Stack |
|---------|-------------|-------|
| 01 — Static Website Platform | S3 + CloudFront + ACM static delivery with CI/CD | Terraform, S3, CloudFront |
| 02 — ECS Fargate App | Containerised application on ECS Fargate | Terraform, ECS, ECR, Docker |
| 03 — Serverless Image Pipeline | Event-driven image processing via Lambda + S3 | Lambda, S3, SQS |

### Platform Engineering
| Project | Description | Stack |
|---------|-------------|-------|
| 04 — Landing Zone Starter | Multi-account AWS landing zone with SCPs | Control Tower, Terraform |
| 05 — EKS Platform Starter | Production Kubernetes cluster with GitOps | EKS, Terraform, ArgoCD |
| 06 — Observability Platform | Full-stack monitoring and alerting | Prometheus, Grafana, Loki |
| 07 — Internal Developer Platform | Self-service platform for engineering teams | Backstage, Kubernetes |

### Senior Portfolio Projects
| Project | Description | Stack |
|---------|-------------|-------|
| 08 — AIOps Incident Copilot | AI-assisted incident management and triage | Python, Claude API, PagerDuty |
| 09 — Multi-Account Security Guardrails | Automated security policy enforcement | AWS Config, OPA, Lambda |
| 10 — Disaster Recovery Platform | Multi-region DR with automated failover | Route 53, RDS, Velero |
| 11 — Event-Driven Integration Factory | Message-driven service integration | EventBridge, SQS, Lambda |
| 12 — Data Analytics Lakehouse | Cloud data lake with streaming analytics | S3, Glue, Athena, Kinesis |
| 13 — Global Active-Active Platform | Multi-region active-active application | Route 53, DynamoDB Global |

### Tooling & Delivery
| Project | Description | Stack |
|---------|-------------|-------|
| 14 — Kubernetes GitOps Platform | Production GitOps with ArgoCD + Flux | ArgoCD, Flux, Helm |
| 15 — Terraform Blueprint Registry | Reusable Terraform module library | Terraform, Terragrunt |
| 16 — Ansible Ops Automation | Configuration management automation | Ansible, AWS SSM |
| 17 — Jenkins CI/CD Pipeline Factory | Enterprise Jenkins pipeline templates | Jenkins, Docker, Python |
| 18 — Maven Cloud Service | Java microservice with cloud deployment | Maven, Spring Boot, ECS |

### Core AWS Control Plane
| Project | Description | Stack |
|---------|-------------|-------|
| 19 — S3 Storage Governance | Bucket policies, lifecycle, replication | S3, Terraform, Python |
| 20 — VPC Network Foundation | Multi-AZ VPC with transit gateway | VPC, TGW, Terraform |
| 21 — KMS Encryption & Secrets | Encryption key management at scale | KMS, Secrets Manager |
| 22 — Policy-as-Code Security Gates | OPA-based policy enforcement | OPA, Gatekeeper, Terraform |
| 23 — IAM Identity Boundary Platform | Zero-trust IAM with permission boundaries | IAM, SCP, Terraform |
| 24 — Backup & Restore Governance | Automated backup compliance | AWS Backup, Velero, Lambda |

### Advanced Platform Themes
| Project | Description | Stack |
|---------|-------------|-------|
| 25 — Edge Delivery Security | WAF, Shield, CloudFront security rules | WAF, Shield, CloudFront |
| 26 — Managed Data Platform | RDS, ElastiCache, managed database ops | RDS, ElastiCache, Terraform |
| 27 — Deep Systems Orchestration | Complex workflow orchestration | Step Functions, Lambda |
| 28 — Event Streaming & Analytics | Real-time streaming data platform | Kinesis, MSK (Kafka) |
| 29 — Zero-Trust Workforce Access | Workforce identity with zero-trust | IAM Identity Center, SSO |
| 30 — Cloud Cost Intelligence | FinOps dashboards and anomaly detection | Cost Explorer, Python, Grafana |
| 31 — Multi-Region Backup Drill | Automated DR drill and validation | Velero, Lambda, Route 53 |

## Repository Structure

```
aws-devops-engineering-portfolio/
├── projects/
│   ├── 01-static-website-platform/
│   ├── 02-ecs-fargate-app/
│   ├── ...
│   └── 31-multi-region-backup-drill-platform/
└── README.md
```

## Author

**Harishmaran Subbaiah Thirumaran** — DevOps & Platform Engineer, Amsterdam

[linkedin.com/in/harishmaran](https://linkedin.com/in/harishmaran) · [harryportfolio-gamma.vercel.app](https://harryportfolio-gamma.vercel.app)

