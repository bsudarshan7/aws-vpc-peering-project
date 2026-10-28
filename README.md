# AWS VPC Peering Project

## Overview
This project demonstrates private communication between two Amazon Virtual Private Clouds (VPCs) using AWS VPC Peering.

## AWS Services Used
- Amazon VPC
- VPC Peering
- Amazon EC2
- Subnets and Route Tables
- Internet Gateway
- Security Groups

## Network Configuration
- **Region:** Asia Pacific (Mumbai) — `ap-south-1`
- **VPC A CIDR:** `10.10.0.0/16`
- **VPC B CIDR:** `10.20.0.0/16`
- **App-A Private IP:** `10.10.2.169`
- **App-B Private IP:** `10.20.1.91`
- **Bastion Host:** `10.10.1.73`

## Implementation
- Created two VPCs with separate CIDR ranges.
- Configured public and private subnets.
- Created and activated a VPC Peering connection.
- Updated route tables to enable communication between the VPCs.
- Configured security groups for SSH access and ICMP testing.
- Used a bastion host to access private EC2 instances.
- Tested network connectivity using ping.

## Project Documentation
The PDF report includes the network architecture, AWS configuration screenshots, routing details, and project learning outcomes.

**Report:** `Sudarshan_Birajdar_EWB_VPC_Peering_Final.pdf`

## Learning Outcomes
Learned AWS networking fundamentals, VPC Peering, subnetting, route tables, security groups, bastion-host access, and network troubleshooting.

## Note
This repository contains project documentation and screenshots. It does not include application source code or automation scripts.
