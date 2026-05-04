# terraform-aws-platform

Production-grade Terraform modules for AWS multi-cloud platform engineering.
Built from real infrastructure patterns used at enterprise scale.

## What this solves
- Repeatable, version-controlled AWS infrastructure
- EKS cluster provisioning with managed node groups
- VPC with proper subnet segmentation and NAT gateways
- IAM roles enforcing least-privilege access
- CloudWatch monitoring and alerting

## Modules

| Module | What it provisions |
|---|---|
| `modules/eks` | EKS cluster with managed node groups |
| `modules/vpc` | VPC, subnets, route tables, NAT gateway |
| `modules/iam` | IAM roles and policies |
| `modules/monitoring` | CloudWatch alarms and dashboards |

## Prerequisites
- Terraform >= 1.5
- AWS CLI configured
- kubectl

## Usage
```bash
git clone https://github.com/YOUR_USERNAME/terraform-aws-platform
cd terraform-aws-platform
terraform init
terraform plan
terraform apply
```

## Related resume projects
- Project Runway — Southwest Airlines multi-cloud infrastructure overhaul
- Project CloudCore — AWS Well-Architected cloud-native platform
