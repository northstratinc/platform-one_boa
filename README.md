# Northstrat, Inc. Platform One BOA Oral Presentation Portfolio Review Materials

## Northstrat Mobile App Cloud Formation Templates

### Overview

Northstrat has created a mobile app that is one of multiple
internal corporate communications channels (including email, Microsoft
Teams, etc.).

The mobile app development team leveraged AWS CloudFormation, an 
AWS-specific Infrastructure as Code (IaC) tool for creating and 
deploying AWS resources providing the 100% serverless backend
for the mobile app.

Northstrat created CloudFormation templates for creating all AWS
resources for the production deployment environment.

### Template Descriptions

1. `production-api_endpoints.yaml`: Creates the [AWS API Gateway](https://aws.amazon.com/api-gateway/) REST endpoints in the production  environment 
1. `production-cognito.yaml`: Creates the User Groups and values inside [AWS Cognito](https://aws.amazon.com/cognito/), AWS's managed Identity Access Management (IAM) service 
1. `production-resources.yaml`: Creates the supporting AWS resources (e.g., S3 buckets, Lambda functions, etc.) for the production environment
