
# Azure Infrastructure Architecture

## Architecture Overview

The proposed environment uses a segmented network architecture with separate application and data layers.

## Network Design

- One Azure Virtual Network
- Application subnet
- Private endpoint subnet
- Network Security Groups

## Application Layer

Azure App Service is used as the application hosting platform.

## Data Layer

Azure SQL Database is used for relational data storage.

## Security Layer

Azure Key Vault and Managed Identity are included in the security design.

## Monitoring

Azure Monitor and Log Analytics are considered for operational visibility.
