# Terraform-EC2-Creation
Creating resources with terraform




The project uses Terraform Input Variables and output variables and a terraform.tfvars file to make the infrastructure configuration flexible and reusable.
I also performed the complete Terraform lifecycle:
terraform init
terraform plan
terraform apply
terraform destroy
 AWS Resource Created
Amazon EC2 Instance
Subnet 
The EC2 instance is deployed into a specific AWS subnet using Terraform.
 Technologies Used
AWS
Terraform
Amazon EC2
AWS VPC
HCL (HashiCorp Configuration Language)
VS Code
AWS CLI

1. Terraform Init
terraform init
Initializes the Terraform working directory and downloads the required providers.
2. Terraform Plan
terraform plan
Shows what Terraform is going to create, modify, or delete before making changes.
3. Terraform Apply
terraform apply
Creates the AWS infrastructure defined in the Terraform configuration.
4. Terraform Destroy
terraform destroy
Removes the infrastructure that was created by Terraform.
This helps avoid leaving unnecessary AWS resources running and incurring charges.
Workflow
Terraform Configuration
        |
        v
terraform init
        |
        v
terraform plan
        |
        v
terraform apply
        |
        v
AWS EC2 Instance Created
        |
        v
terraform destroy
        |
        v
AWS Resources Removed
