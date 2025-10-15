# fix-terraform-project

# Terraform EC2 Lab - Fix the Errors

This Terraform configuration deploys an EC2 instance with a security group. However, the project includes intentional errors to help you learn and troubleshoot.

## ❗ What You'll Practice

- Validating and applying Terraform configs
- Fixing bad resource references
- Correcting invalid CIDR blocks
- Providing correct AMI and key names
- Debugging Terraform apply errors

## 🛠 Instructions

1. Inspect the configuration files.
2. Run `terraform init`
3. Run `terraform validate` — fix any validation errors.
4. Run `terraform plan` — identify issues.
5. Run `terraform apply` — troubleshoot runtime errors.
6. Fix errors like:
   - Invalid CIDR blocks
   - Nonexistent AMI or key pair
   - Incorrect VPC ID
   - Missing resources

## ✅ Tasks

- [ ] Fix invalid AMI ID
- [ ] Provide valid key pair
- [ ] Replace invalid CIDR block in security group
- [ ] Ensure VPC ID is valid
- [ ] Confirm instance is deployed and reachable (SSH)

## 🔁 Cleanup

After testing, destroy resources:

```bash
terraform destroy
