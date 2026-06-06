# AWS Highly Available Web Architecture using Terraform

## Project Highlights

* Infrastructure as Code (IaC) using Terraform
* Multi-AZ deployment for high availability
* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* Launch Templates
* Public and Private Subnet Architecture
* AWS Networking Components
* Scalable and fault-tolerant web application design

---

## Project Overview

This project demonstrates the deployment of a highly available AWS web architecture using Terraform.

The infrastructure was designed following AWS best practices to provide fault tolerance, scalability, and high availability across multiple Availability Zones.

The deployment automatically provisions networking resources, compute resources, load balancing, and scaling components using Infrastructure as Code.

---

## Architecture

```text
                Internet
                    |
                    v
      +---------------------------+
      | Application Load Balancer |
      +-------------+-------------+
                    |
        +-----------+-----------+
        |                       |
        v                       v

+---------------+      +---------------+
| EC2 Instance  |      | EC2 Instance  |
| Availability  |      | Availability  |
| Zone A        |      | Zone B        |
+---------------+      +---------------+
        ^                       ^
        |                       |
        +-----------+-----------+
                    |
                    v
         Auto Scaling Group
```

---

## AWS Services Used

* Amazon VPC
* Public Subnets
* Route Tables
* Internet Gateway
* Security Groups
* EC2 Instances
* Launch Templates
* Auto Scaling Groups
* Application Load Balancer
* Target Groups
* IAM
* Terraform

---

## Terraform Resources Created

* VPC
* Internet Gateway
* Route Tables
* Public Subnets
* Security Groups
* Launch Template
* Auto Scaling Group
* Application Load Balancer
* Target Group
* Listener Configuration

---

## Key Tasks Performed

* Designed highly available architecture across multiple Availability Zones
* Created AWS infrastructure using Terraform
* Configured Application Load Balancer
* Configured Auto Scaling Group
* Configured Launch Templates
* Attached EC2 instances to Target Groups
* Configured Security Groups
* Verified load balancing functionality
* Tested infrastructure deployment and destruction using Terraform

---

## Commands Used

```bash
terraform init
terraform validate
terraform plan
terraform apply
terraform destroy
```

---

## Skills Demonstrated

* AWS Networking
* Infrastructure as Code
* Terraform
* High Availability Design
* Auto Scaling
* Load Balancing
* Cloud Architecture
* Git and GitHub

---

## Outcome

Successfully deployed a highly available AWS web infrastructure using Terraform with Application Load Balancer and Auto Scaling Group integration. The architecture was designed to improve availability, scalability, and fault tolerance while following Infrastructure as Code best practices.
