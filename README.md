# CloudFormation-WordPress-Template
CloudFormation template that launches EC2 basic running basic WordPress blog in default VPC with subnets. Ansible automates the instance configuration by pulling the necessary CM code (modules, classes, recipes etc.) from a Git. 

Prerequisites:
- AWS account 
- VPC available in the selected region (us-east-1)
- EC2 key pair
- Git
- Ansible

The Cloudformation Security Group IP uses the permissive default open address. Users are advised to update their Security Group Access with your own IP Address for greater instance security.
