# Terraform Infrastructure

Infrastructure-as-code for provisioning the food platform's cloud resources.

## Planned scope

- Networking and security groups
- Compute and Kubernetes infrastructure
- Databases, storage, and container registries
- IAM roles and environment-specific configuration

## Repository conventions

- Reusable components belong in `modules/`.
- Environment configuration belongs in `environments/`.
- Terraform state and secret values must never be committed.
- Changes should be validated with `terraform fmt`, `terraform validate`, and a reviewed plan.

Operational procedures are documented in `devops-engineering-docs`.
