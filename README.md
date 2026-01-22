# Terraform – VPC, Subnet, and S3 Bucket
This project demonstrates how to use HashiCorp Terraform to provision AWS infrastructure components within the same region.
The configuration is developed using Visual Studio Code with the Terraform extension installed.

## Objective

The goal of this project is to write Terraform code that accomplishes the following:

- Create an Amazon VPC in the us-east-1 region with a CIDR block of 10.0.0.0/16

- Create a subnet with a CIDR block of 10.0.2.0/24 within the above VPC.

- Create an Amazon S3 bucket in the same AWS region.

<img width="1092" height="656" alt="image" src="https://github.com/user-attachments/assets/54bd2b67-4aac-4192-a6ee-d70d9e1a9d68" />




## Execute the Terraform Commands

### Run the following Terraform commands in sequence:

- terraform validate
  (Validates the Terraform configuration files and checks for syntax errors)

- terraform plan
  (Generates and displays an execution plan, allowing you to review the changes Terraform will make before applying them)

- terraform apply or terraform apply -auto-approve
  (Applies the planned changes to create the resources,
  use -auto-approve to skip the manual confirmation prompt)
