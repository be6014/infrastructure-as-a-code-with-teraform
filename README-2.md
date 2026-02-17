# Terraform Docker Container Provisioning

## Objective
Provision a local Docker container using Terraform.

## Tools
- Terraform
- Docker

## Files
- main.tf → Terraform configuration
- Screenshots → Execution outputs

## Steps
```bash
terraform init
terraform plan
terraform apply -auto-approve
terraform state list
terraform destroy -auto-approve
```

## Expected Result
- Nginx container running on http://localhost:8080