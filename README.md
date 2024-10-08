# Terraform-Basics-Creating-and-Managing-AWS-Resources
Terraform Basics: Creating and Managing AWS Resources
## Introduction

In this section, we will cover the basics of provisioning an EC2 instance, IAM User, S3 Bucket, and VPC using Terraform, an open-source infrastructure as code (IaC) tool that allows you to define and manage cloud resources using configuration files. Terraform simplifies the process of setting up and managing infrastructure by allowing you to declare your desired state in code, which it then uses to create and configure resources.

## EC2  Instance

- Launch an instance.
- Connect the instance.
- Install terraform
- Configure AWS
- Create a file with the extension “.tf”


- **Terraform Configuration Files:** We'll start by creating a Terraform configuration file that defines the AWS provider and the details for your EC2 instance.

- Initialize terraform using ***terraform init***

- Apply Your Configuration ***terraform apply***

- The instance is created Successfully.

  ## IAM User

- Create a file with .tf extension.
- Start creating a Terraform configuration file that defines the AWS provider and the details for your IAM User.
- As you have already specified the provider before no need to provide it again.
- Apply the configuration.
- The example user is created successfully.

  ## S3 Bucket

- Create a file with .tf extension.
- Start creating a Terraform configuration file that defines the AWS provider and the details for your S3 Bucket.
- As you have already specified the provider before no need to provide it again.
- Apply the configuration.
- The example user is created successfully.


## VPC

- Create a file with .tf extension.
- Start creating a Terraform configuration file that defines the AWS provider and the details for your VPC, IGW, and Subnets.
- As you have already specified the provider before no need to provide it again.
- Apply the configuration.
- The example user is created successfully.

To destroy all resources defined in your Terraform configuration, execute the following command: ***terraform destroy***


## Summary

We have successfully created EC2 instance, IAM user, VPC, Subnets, IGW, Route table, S3 Bucket using terraform.
