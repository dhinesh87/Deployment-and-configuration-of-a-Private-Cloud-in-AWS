# Deployment-and-configuration-of-a-Private-Cloud-in-AWS
# Name:Dhinesh M
# Reg no:212223040040
# Ex.4 Deployment and configuration of a Private Cloud  in AWS

# Aim: 
To set up of a Private Cloud  in AWS.
## Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.
# Procedure:
## 1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.
## 2. Create Your VPC:
•	Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
•	 Choose "Create VPC": Initiate the VPC creation process.
•	Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
•	other necessary settings.
•	Create subnets: Define subnets within your VPC to isolate different parts of your
•	network.
•	Create route tables: Specify how traffic is routed within and outside the VPC.
•	 Create security groups: Define access control rules for your resources.
## 3. Deploying Resources:
•	Launch EC2 instances: Create and launch virtual machines within your VPC.
•	 Set up RDS instances: Deploy databases for your applications.
•	Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
•	Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.
## 4.Managing and Monitoring:
•	Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
•	Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
•	Implement security best practices: Regularly review and update your security
configuration.
•	Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

# Snap Shots:

 

## Snapshot 1: Configure and Create VPC
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/aaef0e8f-4ca3-4ff5-b51b-acfdfb81fa05" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/396145ec-67a8-4363-a3d2-36782a4fc5b5" />

## Snapshot 2: Configure and Create Subnets
 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f30f094d-e7f9-4ce3-b0c5-1f23df82c206" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/22a6377a-1724-46a0-87f4-7944656fce2c" />



## Snapshot 3: Setting Internet gateway


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/39e6e529-3c1a-46fa-9c06-6c3ecba0450f" />

## Snapshot 4: Attach to a VPC
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/729b8f36-875b-4349-b499-bd75bc469f56" />


 
## Snapshot 5: Configure and Create route table
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/39085bcc-7046-4627-8caa-5aa64b35e280" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8b541eb1-21c3-4536-9b2e-4f5f0e1c95dd" />


 
## Snapshot 6: Editing routes
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/40569c1a-bb4d-4020-96fc-0a8499c90088" />

 
## Snapshot 10: Creating route table
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fbbd0c7f-3dbf-41f1-8229-acd96ee12db1" />


 
## Snapshot 11: Launch EC2 instances

<img width="1920" height="1080" alt="Screenshot 2026-08-02 122704" src="https://github.com/user-attachments/assets/a6c60558-cf31-4e7e-8a59-0facd82a27fc" />

## Snapshot 12: Launch S3
<img width="1920" height="1080" alt="Screenshot 2026-08-02 123003" src="https://github.com/user-attachments/assets/50490ad3-d96d-498e-a7c0-c4b007550aca" />



## Snapsshot 13: Monitor using AWS Cloudwatch

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9e452abe-b4d0-4e29-84d9-6410dce6f5db" />






# Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
 
