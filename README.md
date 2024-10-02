# Payments Devops Task

## Task: Deploy a Simple Web Application on AWS using Terraform

### Objective:

Use Terraform to deploy a basic infrastructure on AWS to host a simple web application.

### Requirements:

1. AWS Resources to Create:

   - VPC with two subnets (one public, one private).
   - An EC2 instance (Ubuntu) in the public subnet to serve as a web server.
   - A security group to allow HTTP (port 80) and SSH (port 22) access to the EC2 instance.
   - A public-facing Elastic IP attached to the EC2 instance.
   - A simple HTML file served using the web server on the EC2 instance (e.g., using Nginx or Apache).

2. Terraform Configuration:

   - Write Terraform code to define the infrastructure.
   - Use terraform variables to make the configuration flexible (e.g., instance type, key name, region).
   - Use the formatter and validate to ensure proper formatting and validation.

3. Instructions:

   - Provide clear instructions on how to initialize and apply the Terraform configuration.
   - Document any AWS IAM roles or permissions needed to apply the infrastructure.

4. Deliverables:

   - Terraform code (main.tf, variables.tf, and outputs.tf files).
   - A README file with steps to run the Terraform code.
   - A brief description of the solution.
