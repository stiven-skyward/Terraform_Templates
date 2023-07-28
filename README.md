# Terraform Templates

This repository contains Terraform templates for various cloud infrastructure tasks. Each template is designed to be reusable and modular, allowing for easy deployment and configuration of cloud resources.

## Repository Contents

### Automations

#### On-Off

- `TF_Create_Role_lambda_On_Off_ec2.tf`: This Terraform script creates an IAM role with the necessary policy to allow an AWS Lambda function to trigger from a scheduled rule in the EventBridge Scheduler to start and stop EC2 instances.

## Important Note

All templates in this repository are examples and should be used as a starting point. They will need to be customized with your specific AWS account details and requirements. Always review and understand the changes that Terraform will make before applying them.

## How to Use

To use these Terraform scripts, clone this repository to your local machine, navigate to the desired script directory, and run the Terraform commands.

Here's a list of useful commands:

```bash
git clone https://github.com/stiven-skyward/Terraform_Templates.git    # Clone the repository
cd Terraform_Templates                                                    # Change to the script directory
terraform init                                                            # Initialize Terraform in the directory
terraform validate                                                        # Validates the Terraform scripts
terraform fmt                                                             # Formats the Terraform scripts to a standard style
terraform plan                                                            # Show what Terraform will do before applying changes
terraform apply                                                           # Apply the Terraform scripts
