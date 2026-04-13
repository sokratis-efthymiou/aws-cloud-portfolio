# AWS SimuLearn: Cloud First Steps

## Overview
This guided AWS lab focused on launching and configuring an Amazon EC2 instance as part of an introductory cloud deployment scenario. The exercise introduced core cloud concepts such as regions, availability zones, EC2 instances, and basic instance setup using user data.

## Objective
To understand the basics of launching an EC2 instance in AWS and extending the setup by deploying a second instance in a different Availability Zone within the same AWS Region.

## Lab Context
The practice lab focused on:
- launching an Amazon EC2 instance
- configuring a user data script to display instance details in a browser
- understanding regions and availability zones
- deploying compute resources across separate availability zones

## Tasks Performed
- Reviewed the initial lab architecture in the **us-east-1 (N. Virginia)** region
- Explored the relationship between Region, Availability Zone, EC2 instance, and EBS volume
- Worked with an initial EC2 instance in one Availability Zone
- Configured and launched a **second EC2 instance** in a **different Availability Zone** within the same Region
- Validated that the two EC2 instances were placed in separate Availability Zones

## AWS Services and Concepts Involved
- Amazon EC2
- Amazon EBS
- AWS Region
- Availability Zones
- User data script
- Basic compute deployment concepts

## What I Learned
- How AWS Regions and Availability Zones are structured
- How EC2 instances are launched within a selected Availability Zone
- How EBS volumes are associated with EC2 instances
- How user data can be used to configure instance behavior at launch
- Why distributing compute resources across multiple Availability Zones improves resilience and availability

## Business Relevance
Deploying workloads across multiple Availability Zones is a common cloud architecture principle for improving resilience and reducing single points of failure. This lab introduced a foundational high-availability concept by showing how compute resources can be distributed within the same AWS Region.

## Skills Demonstrated
- Basic EC2 deployment understanding
- Awareness of Regions and Availability Zones
- Understanding of EBS attachment concepts
- Introductory use of user data scripts
- Foundational cloud architecture thinking
- Basic high-availability awareness

## Evidence
This project includes supporting evidence for clarity and traceability:
- Completion certificate
- Project overview screenshot
- Verification task screenshot

The completion certificate confirms successful completion of **AWS SimuLearn: Cloud First Steps**, completed on **June 24, 2025**, and awarded to **Sokratis Efthymiou**. :contentReference[oaicite:0]{index=0}

## Files Included
- `certificate.pdf`
- `project-overview.png`
- `verification-task.png`

## Status
Completed guided lab

## Next Step
Recreate a similar EC2 deployment independently and document how multi-Availability-Zone deployment supports availability, resilience, and basic infrastructure design in AWS.
