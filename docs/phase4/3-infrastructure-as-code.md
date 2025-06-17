# Topic 3: Infrastructure as Code (IaC)

Infrastructure as Code (IaC) is a key DevOps practice  that allows you to manage and provision infrastructure using code, rather than manual processes, like using console. It ensures consistency, repeatability, and scalability in managing cloud resources.

## Study

- What is [Infrastructure as Code](https://www.hashicorp.com/resources/what-is-infrastructure-as-code)?
- Since Terraform is cloud-agnostic(meaning you can deploy resources to any cloud provider), it is pretty popular. Hence we recommend [Terraform](https://developer.hashicorp.com/terraform/intro).
- Learn the basics of Terraform:
  - [Terraform init](https://developer.hashicorp.com/terraform/cli/commands/init)
  - [Terraform plan](https://developer.hashicorp.com/terraform/cli/commands/plan)
  - [Terraform apply](https://developer.hashicorp.com/terraform/cli/commands/apply)
  - [Terraform destroy](https://developer.hashicorp.com/terraform/cli/commands/destroy)
- Explore cloud-specific Terraform providers:
  - [AWS Provider](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
  - [Azure Provider](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)
  - [GCP Provider](https://registry.terraform.io/providers/hashicorp/google/latest/docs)

## Hands-on Tasks

### Basic IaC Project

1. Install Terraform on your system:
   - [Install Terraform](https://developer.hashicorp.com/terraform/install)
2. Write a Terraform configuration file to:
   - Create a virtual machine in your preferred cloud platform.
   - Configure a security group to allow SSH access.
   - Or deploy a static site to your choice of cloud provider.
3. Learn how you can deploy it using Terraform:
   - Run `terraform init` to set up the working directory.
   - Run `terraform plan` to preview changes.
   - Run `terraform apply` to create the resources.
5. Verify the resources in your cloud platform.
6. Destroy the resources:
   - Run `terraform destroy` to clean up.


### Additional Project

- Use Terraform to deploy a multi-tier application:
  - Create a VPC with public and private subnets.
  - Deploy a web server in the public subnet and a database in the private subnet.
  - Configure security groups to allow communication between the web server and database.
  - Configure variables withing your terraform configuration.
  - Use a backend for the state file management.

## Test Your Knowledge

Use an AI assistant to test your understanding of IaC concepts. Here are some example prompts:

1. What are the benefits of using Infrastructure as Code?
2. How does Terraform ensure idempotency in resource management?
3. What is the purpose of the `terraform state` file?
4. How do you manage sensitive data like API keys in Terraform?
5. What is the difference between `terraform plan` and `terraform apply`?
6. What are terraform modules and why/how you should use them?
7. What are the best practices for terraform?

## Resources

- [Terraform Documentation](https://developer.hashicorp.com/terraform/docs)
- [Terraform Best Practices](https://www.terraform-best-practices.com/)
- [AWS Terraform Example](https://youtu.be/P4A62b1dkJE?si=-Lsed7_wyvbXv0RI)
- [Azure Terraform Example](https://youtu.be/HdMB2YCtVr4?si=zRkEGPLy7zhRKPAX)
- [GCP Terraform Example](https://youtu.be/VCayKl82Lt8?si=wWZ5DuabFPaZEDsY)
