# AWS VPC Peering and Secure Private EC2 Communication

## Project Overview
This project demonstrates communication between two
separate Amazon VPCs using AWS VPC Peering.

## Architecture

### VPC A
- CIDR: 10.10.0.0/16
- Public Subnet: 10.10.1.0/24
- Private Subnet: 10.10.2.0/24

### VPC B
- CIDR: 10.20.0.0/16
- Private Subnet: 10.20.1.0/24

## AWS Services Used
- Amazon VPC
- Amazon EC2
- VPC Peering
- Internet Gateway
- Route Tables
- Security Groups
- Amazon Linux 2023

## Implementation
1. Created two separate VPCs.
2. Created public and private subnets.
3. Configured an Internet Gateway.
4. Established a VPC Peering connection.
5. Updated route tables.
6. Configured security groups.
7. Launched a Bastion host and two private EC2 instances.
8. Connected to private instances using SSH.
9. Tested communication using ICMP ping.

## Testing Results
- App-A to App-B: Successful
- App-B to App-A: Successful
- Packet Loss: 0%

## Learning Outcomes
Learned AWS networking, VPC Peering, subnetting,
route table configuration, Linux SSH connectivity,
security groups, and troubleshooting.
