# Cloud Infrastructure (Infrastructure as Code)

## Overview
This repository defines the complete AWS infrastructure for the Smart Surveillance System using Infrastructure as Code (IaC).

All cloud resources are declaratively managed to ensure reproducibility, scalability, and secure deployment.

## Core Responsibilities
- VPC configuration
- IAM role and policy management
- RDS database provisioning
- S3 storage configuration
- OpenSearch cluster setup
- ECS / Lambda deployment definitions
- Networking & security rules
- Environment isolation (dev / staging / production)

## Why This Repository Exists
Infrastructure must be version-controlled to:

- Ensure consistent deployments
- Enable team collaboration
- Support automated CI/CD
- Maintain auditability
- Prevent configuration drift

This approach aligns with modern DevOps best practices.

## Technology Stack
- Terraform or AWS CDK
- Docker images stored in ECR
- GitHub Actions for deployment

## Environments
- Development
- Staging
- Production

## Future Improvements
- Blue/green deployments
- Cost monitoring automation
- Security compliance scanning
