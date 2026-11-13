
# Azure Enterprise Cloud Infrastructure

## Overview

This repository contains a reference design for an enterprise Azure cloud infrastructure environment.

The project focuses on infrastructure organization, network architecture, security controls, infrastructure as code, and operational monitoring.

## Project Objectives

- Design a structured Azure cloud environment.
- Define infrastructure using Terraform.
- Organize network resources and security boundaries.
- Apply identity and access management principles.
- Document monitoring and operational considerations.
- Prepare infrastructure validation through GitHub Actions.

## Technology Stack

- Microsoft Azure
- Terraform
- Azure Virtual Network
- Network Security Groups
- Azure App Service
- Azure SQL Database
- Azure Key Vault
- Azure Monitor
- GitHub Actions

## Architecture Components

| Component | Purpose |
|---|---|
| Virtual Network | Network isolation |
| Subnets | Network segmentation |
| NSG | Network traffic filtering |
| App Service | Application hosting |
| Azure SQL | Relational database |
| Key Vault | Secrets management |
| Azure Monitor | Monitoring and logging |
| Terraform | Infrastructure as Code |

## Repository Structure

```text
azure-enterprise-infrastructure/
├── architecture/
├── terraform/
├── security/
├── monitoring/
├── docs/
└── .github/
    └── workflows/
```

## Security Considerations

- Least privilege access
- Managed Identity
- Secure secrets management
- Network segmentation
- Restricted network access

## Project Status

Design and documentation phase.

This repository is a reference implementation project. Infrastructure deployment to an Azure subscription has not been performed.

## Author

Cloud Infrastructure Portfolio Project

