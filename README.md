# AWS High Availability & Resilient Architecture Lab ☁️

Hands-on AWS architecture lab focused on building a more resilient, scalable, secure, and highly available cloud environment.

## 🎯 Project Objective

The objective of this lab was to identify and fix architectural issues in an AWS environment that could affect availability, scalability, security, and communication between resources.

The environment initially contained several single points of failure and configuration issues. Each challenge required analyzing the existing architecture and implementing the appropriate AWS solution.

## 🛠️ AWS Services & Concepts

- Amazon EC2
- EC2 Auto Scaling
- Amazon RDS Multi-AZ
- Amazon DynamoDB
- Amazon VPC
- VPC Peering
- Route Tables
- Security Groups
- AWS IAM
- Availability Zones

## 🏗️ Architecture Improvements

During the lab, I implemented improvements involving:

- Database high availability using **Amazon RDS Multi-AZ**
- Application scaling across **multiple Availability Zones**
- Network communication between VPCs using **VPC Peering**
- Route table configuration for bidirectional communication
- Security Group rules based on the **least privilege principle**
- A DynamoDB table for application activity logs
- IAM permissions allowing the application to securely read DynamoDB data

## 📚 Key Learning Outcomes

This project strengthened my practical understanding of:

- High availability and fault tolerance
- Multi-AZ architectures
- Network routing between AWS VPCs
- Identity and access management
- Infrastructure security
- Application scalability
- Managed database services

## 📌 Project Context

This repository documents a hands-on AWS training lab completed through **AWS Skill Builder / AWS Cloud Quest**.

The environment was created specifically for training purposes and does not represent a production workload.
