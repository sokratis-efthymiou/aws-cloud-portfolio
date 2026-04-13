# AWS SimuLearn: Networking Concepts

## Overview
This guided AWS lab focused on networking and secure communication between application components inside an AWS Virtual Private Cloud (VPC). The exercise demonstrated how routing, subnet separation, and security group rules are used to control traffic between cloud resources.

## Objective
To understand the core components of a VPC and configure secure communication between a web server and a database server by updating the appropriate security group rules.

## Lab Context
The practice lab focused on:
- exploring the components that comprise a Virtual Private Cloud (VPC)
- configuring a route table attached to a subnet within a VPC
- configuring an internet gateway inside a VPC
- configuring inbound rules within a security group to control access

## Tasks Performed
- Reviewed the VPC network layout
- Identified the web server in the **public subnet**
- Identified the database server in the **private subnet**
- Reviewed the connectivity path from the internet to the VPC through the internet gateway and router
- Updated the security group rules to allow traffic on **port 3306**
- Validated successful communication between the web server and the database server

## AWS Services and Concepts Involved
- Amazon VPC
- Public subnet
- Private subnet
- Route tables
- Internet gateway
- Security groups
- TCP port 3306
- Web-to-database connectivity

## What I Learned
- How core VPC components work together in a cloud network
- The difference between public and private subnets
- How route tables and internet gateways support traffic flow
- How security groups control inbound connectivity between AWS resources
- Why databases should be protected in private network layers
- How application-to-database communication is configured securely in AWS

## Business Relevance
A common enterprise cloud design pattern is to keep the application layer accessible while protecting the database layer from direct external exposure. This lab reflects that model by allowing controlled internal communication between the web server and the database server, while keeping the backend more secure through subnet separation and rule-based access.

## Skills Demonstrated
- Basic VPC architecture understanding
- Subnet separation awareness
- Route table and gateway understanding
- Security group configuration
- Controlled database connectivity
- Secure cloud design thinking

## Evidence
This project includes supporting evidence for clarity and traceability:
- Completion certificate
- Architecture / concept screenshot
- Lab screenshot showing the security group validation task

## Files Included
- `certificate.pdf`
- `project-overview.png`
- `verification-task.png`

## Status
Completed guided lab

## Next Step
Recreate a similar VPC setup independently and document the architecture with a custom diagram and live configuration screenshots from a self-built environment.
