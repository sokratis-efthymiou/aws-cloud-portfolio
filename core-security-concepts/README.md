# AWS SimuLearn: Core Security Concepts

## Overview

This project documents a guided AWS SimuLearn lab focused on core security concepts in AWS. The lab introduced identity and access management practices, including IAM users, IAM groups, AWS managed policies, and the principle of least privilege.

The scenario focused on restricting support engineers' access to AWS resources by assigning only the permissions required for their role.

## Objective

The objective of this lab was to understand how AWS Identity and Access Management can be used to securely manage access to cloud resources.

The lab focused on:

- Comparing IAM users, roles, and groups
- Understanding IAM policy structure and permissions
- Applying the principle of least privilege
- Reviewing AWS security responsibilities
- Implementing IAM best practices for secure access management

## Lab Context

In the simulated business scenario, a stock exchange organization wanted to restrict support engineers' system access to only the AWS actions required for their responsibilities.

The solution required creating an IAM user group and attaching read-only permissions so that support engineers could view relevant AWS resources without being able to modify or delete them.

## Tasks Performed

- Created an IAM user group named `SupportEngineers`
- Created or reviewed an IAM user assigned to the group
- Attached AWS managed policies to the IAM group
- Granted read-only access to Amazon EC2
- Granted read-only access to Amazon RDS
- Verified that the user group contained the correct user
- Verified that the correct permissions were attached to the group
- Captured screenshots as evidence of the completed configuration

## AWS Services and Concepts Involved

- AWS Identity and Access Management
- IAM users
- IAM user groups
- IAM policies
- AWS managed policies
- Least privilege access
- Amazon EC2 permissions
- Amazon RDS permissions
- Access management best practices

## Policies Used

The following AWS managed policies were attached to the `SupportEngineers` IAM group:

- `AmazonEC2ReadOnlyAccess`
- `AmazonRDSReadOnlyAccess`

These policies allowed support engineers to describe and view EC2 and RDS resources without granting permissions to modify, stop, terminate, or delete resources.

## What I Learned

- How IAM groups can simplify access management for multiple users
- How AWS managed policies can be attached to IAM groups
- How read-only access supports the principle of least privilege
- How to separate viewing permissions from administrative permissions
- How IAM supports secure and role-based access control in AWS environments
- Why cloud security requires clear permission boundaries and regular access review

## Business Relevance

IAM is a core part of cloud governance and cybersecurity. In real business environments, organizations need to ensure that users have only the access required to perform their duties.

This lab is relevant for cloud security, compliance, IT operations, and governance because it demonstrates how access can be structured around job responsibilities. Applying least privilege reduces the risk of accidental changes, unauthorized actions, and operational security incidents.

## Skills Demonstrated

- IAM user group configuration
- AWS managed policy assignment
- Least privilege access design
- Read-only permission setup
- Cloud security awareness
- AWS console navigation
- Evidence-based technical documentation
- Security and governance fundamentals

## Evidence

This project includes supporting evidence of lab completion:

- [Completion certificate](certificate.pdf)
- Lab overview screenshot
- IAM user group screenshot
- IAM group permissions screenshot
- Lab completion screenshot

## Status

Completed guided AWS SimuLearn lab.

## Next Step

The next step is to build on this knowledge by creating a small independent IAM security project, such as designing least-privilege access for different user groups, documenting access boundaries, or comparing read-only and administrator access policies.
