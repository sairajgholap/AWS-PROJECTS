# Highly Available Web Application on AWS

## Project Overview
This project demonstrates the deployment of a **highly available and scalable web application on AWS** using core cloud services. The architecture is designed to follow **production-level best practices**, including high availability, security, and auto-scaling.

The project focuses on building a fault-tolerant infrastructure across multiple Availability Zones and handling traffic efficiently using AWS-managed services.

---

## Architecture
- Multi-AZ architecture for high availability
- Load-balanced EC2 instances with Auto Scaling
- Secure networking using VPC and Security Groups
- Static content hosted on Amazon S3
- DNS management using Amazon Route 53

---

## AWS Services Used
- **Amazon EC2** – Web application hosting
- **Application Load Balancer (ALB)** – Traffic distribution
- **Auto Scaling Group** – Automatic scaling based on load
- **Amazon VPC** – Custom networking
- **Subnets (Public & Private)** – Network segmentation
- **Security Groups** – Inbound and outbound traffic control
- **IAM** – Secure access and role-based permissions
- **Amazon S3** – Static content storage
- **Amazon Route 53** – Domain name and DNS routing

---

## Key Features
- High availability using multiple Availability Zones
- Auto Scaling to handle traffic spikes automatically
- Secure access using IAM policies and Security Groups
- Scalable and production-ready cloud architecture
- Fault-tolerant design to avoid single points of failure

---

## Implementation Steps
1. Created a custom **VPC** with public and private subnets
2. Configured **Internet Gateway** and Route Tables
3. Launched EC2 instances in multiple Availability Zones
4. Set up **Application Load Balancer**
5. Configured **Auto Scaling Group**
6. Created **IAM roles and policies** for secure access
7. Hosted static files using **Amazon S3**
8. Configured **Route 53** for DNS routing
9. Tested application scalability and availability

---

## Screenshots
The following screenshots are included to demonstrate implementation:
- VPC and Subnet creation
- EC2 instances and Auto Scaling Group
- Load Balancer configuration
- IAM roles and policies
- S3 bucket configuration
- Route 53 DNS setup

(Refer to the `/screenshots` folder)

---

## Project Status
 **90% Completed**

### Planned Enhancements
- HTTPS configuration using ACM (SSL)
- CloudWatch monitoring and alarms
- Infrastructure as Code using Terraform / CloudFormation
- CI/CD pipeline integration
- WAF for enhanced security

---

## Skills Demonstrated
- AWS Cloud Architecture
- High Availability Design
- Auto Scaling & Load Balancing
- Networking (VPC, Subnets, Routing)
- IAM & Cloud Security
- Basic DevOps and Cloud Operations

---

## Author
**[Your Name]**  
Cloud / DevOps Enthusiast  
GitHub: [Your GitHub Profile Link]
