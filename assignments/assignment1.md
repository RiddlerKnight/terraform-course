# Create basic resources with local provider

A basic provider is the first step to learn terraform.

Use provider local <https://registry.terraform.io/providers/hashicorp/local/latest/docs>

Objectives:

- You can read and understand document.
- Use various block type to understand basic concept of Terraform.
- Understand folder structure, file naming and naming convention.
- Understand Terraform basic command like `init`, `plan`, `apply`

## Basic folder structure

```text
.
└── project_a/
    ├── main.tf
    ├── backend.tf
    ├── version.tf
    ├── variable.tf
    ├── output.tf
    └── values.auto.tfvars
```

## Basic Terraform Command

```bash
terraform init #-backend-config=path
terraform plan #-var-file=path
terraform apply #-var-file=path
```
