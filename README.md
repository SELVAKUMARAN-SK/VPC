## Ex.4 Deployment and configuration of a Private Cloud  in AWS

### NAME: SELVAKUMARAN J
#### REG NO: 212224060242

## Aim:
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

## Procedure:
## 1. Plan Your VPC:
## ● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
## ● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
## ● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
## ● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
## ● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.

## 3. Create Your VPC:
Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
 Choose "Create VPC": Initiate the VPC creation process.
Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
other necessary settings.
Create subnets: Define subnets within your VPC to isolate different parts of your
network.
Create route tables: Specify how traffic is routed within and outside the VPC.
 Create security groups: Define access control rules for your resources.

## 4. Deploying Resources:
Launch EC2 instances: Create and launch virtual machines within your VPC.
 Set up RDS instances: Deploy databases for your applications.
Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

## 5.Managing and Monitoring:
Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
Implement security best practices: Regularly review and update your security
configuration.
Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

##  Output:

## Create VPC:

<img width="1919" height="908" alt="image" src="https://github.com/user-attachments/assets/cb98e529-adbc-4b45-9093-54f849dbf4a7" />

<img width="1919" height="914" alt="image" src="https://github.com/user-attachments/assets/314703ea-27ee-4c8e-9a06-1e6d29667790" />

## Configure subnets:

<img width="1918" height="905" alt="image" src="https://github.com/user-attachments/assets/60c67ded-710f-4a38-ab35-e4fd539b916f" />


3)

## Setting Internet Gateway:
<img width="1919" height="908" alt="image" src="https://github.com/user-attachments/assets/f13f5969-cefe-4921-8a8e-2f1a4cd3764d" />
<img width="1919" height="900" alt="image" src="https://github.com/user-attachments/assets/5f8f1e66-c98f-4ef9-8976-05a0cd3a9581" />
<img width="1916" height="908" alt="image" src="https://github.com/user-attachments/assets/91962217-db08-4faf-b39f-4eda76708b68" />


## Creating Route Table:
<img width="1918" height="902" alt="image" src="https://github.com/user-attachments/assets/3102afc4-c475-419e-b3c5-b4ad5b2df4e5" />


## Configuring Route Table:
<img width="1919" height="914" alt="image" src="https://github.com/user-attachments/assets/1809056e-54f7-45e0-9a79-6d16af755972" />


## Editing Routes:

<img width="1919" height="910" alt="image" src="https://github.com/user-attachments/assets/9c197c62-a2c3-48fe-84db-2bf98d9afa15" />

## Creating Route Table:

<img width="1916" height="908" alt="image" src="https://github.com/user-attachments/assets/64d5ffc8-7a16-4c5c-8f51-6a13d94f4d2a" />


## Result:

Thus, a private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our require
