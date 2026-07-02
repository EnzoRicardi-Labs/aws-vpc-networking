# AWS VPC Networking Fundamentals

## Project Overview

This project demonstrates the creation of a basic Amazon VPC using the AWS VPC Wizard.

The environment includes public and private subnets, Internet and NAT Gateways, route tables, and Network ACLs following AWS networking best practices.

## Architecture Components

- Amazon VPC
- Internet Gateway
- NAT Gateway
- Public and Private Subnets
- Network Access Control Lists
- Route Tables

## Architecture

Available in "aws-vpc-networking/architecture"

## Skills Demonstrated

- Amazon VPC
- AWS Networking
- Amazon VPC Wizard
- Network Architecture

## Implementation Steps

1. Created a new Amazon VPC using the AWS VPC Wizard.
2. Configured one public and one private subnet.
3. Attached an Internet Gateway to provide public internet access.
4. Provisioned and associated a NAT Gateway for outbound traffic from the private subnet.
5. Configured route tables for public and private network traffic.
6. Applied Network ACLs to control subnet-level traffic.
7. Validated the network topology using the AWS Resource Map.

## What I Learned

- How Amazon VPC works
- Public vs Private networking
- Internet Gateway
- Route propagation
- NAT Gateway purpose

## Possible Improvements

- Deploy resources across multiple Availability Zones for high availability.
- Implement Security Groups for workload-level protection.
- Enable VPC Flow Logs for network monitoring.
- Create custom Network ACL rules following least privilege.

## Project Files

- Architecture Diagram
- AWS Resource Map
- VPC Details
- Public Route Table
- Private Route Table
