# AWS SimuLearn: Networking Concepts

## Overview
This guided AWS lab focused on networking and secure communication between application components inside an AWS Virtual Private Cloud (VPC). The exercise demonstrated how security group rules control traffic between resources in different subnets.

## Objective
To configure secure connectivity between a web server and a database server by updating the appropriate security group rules.

## Tasks Performed
- Reviewed the VPC network layout
- Identified the web server in the **public subnet**
- Identified the database server in the **private subnet**
- Modified security group rules to allow traffic on **port 3306**
- Validated successful communication between the web server and the database server

## AWS Services and Concepts Involved
- Amazon VPC
- Public subnet
- Private subnet
- Security groups
- TCP port 3306
- Web-to-database connectivity
- Basic routing and network segmentation concepts

## What I Learned
- How VPCs separate resources into network segments
- The difference between public and private subnets
- How security groups control inbound traffic between cloud resources
- Why databases should be protected in private network layers
- How application-to-database communication is configured securely in AWS

## Business Relevance
A common enterprise cloud design pattern is to keep the application layer accessible while protecting the database layer from direct external exposure. This lab reflects that model by allowing controlled internal communication between the web server and the database server, while keeping the backend more secure.

## Skills Demonstrated
- Basic VPC architecture understanding
- Security group configuration
- Subnet separation awareness
- Controlled database connectivity
- Secure cloud design thinking

## Evidence
This lab was completed successfully in a guided AWS SimuLearn environment.  
The original temporary lab environment is no longer active, so live instance screenshots are not available.  
A completion certificate is included as proof of completion.

## Status
Completed guided lab

## Next Step
Recreate a similar VPC setup independently and document the architecture with a custom diagram and live configuration screenshots.
