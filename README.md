# AWS_CF_JSON_Template
AWS CloudFormation sample template to create EC2Instance in vpc network with puppet node application: 
Region:US East (N. Virginia) 
AMI used is Red Hat Enterprise Linux 7.2 (HVM)- ami -2051294a:
Create a puppet node using a single EC2 instance on VPC public network. This template demonstrates using the AWS CloudFormation bootstrap scripts to install the packages and files necessary to deploy the CloudFormation Helper Scripts and puppet node at instance launch time.

**WARNING** This template creates an Amazon EC2 instance. You will be billed for the AWS resources used if you create a stack from this template.
Parameters to modify:
Key Name,Instance Type,Subnet ID, Private IP,VPC Id & Image Id.

