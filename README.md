# aws-secure-architecture-project
Secure AWS Architecture with VPC, Auto Scaling &amp; Load Balancer

**Architecture Overview**

Designed a secure and scalable AWS architecture with public and private subnets. Deployed application on private EC2 instances using Auto Scaling Group and exposed it via Application Load Balancer. Used Bastion Host for secure SSH access and implemented monitoring using CloudWatch.


User → ALB → Target Group → Auto Scaling → Private EC2
                      ↑
                 Bastion Host


 **Services Used**
Amazon VPC
Amazon EC2
Application Load Balancer
Amazon EC2 Auto Scaling
Amazon CloudWatch
AWS NAT Gateway


**Steps i did**
Created VPC with public & private subnets
Configured Internet Gateway & NAT Gateway
Launched Bastion Host in public subnet
Created Auto Scaling Group in private subnet
Deployed application on EC2
Configured ALB and Target Group
Enabled monitoring & alerts


**Key Learnings**
Secure architecture design
Private subnet access via bastion
Load balancing & scaling
Troubleshooting SSH & networking issues<img width="1536" height="1024" alt="aws-secure-architecture-project" src="https://github.com/user-attachments/assets/b5a26eaf-9b3d-4e37-a6a0-6ac990414542" />


