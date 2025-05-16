---
title: PMapper
categories: ['python', 'aws', 'iam']
---
## [PMapper](https://github.com/nccgroup/PMapper)

### A tool for quickly evaluating IAM permissions in AWS.


Principal Mapper (PMapper) is a script and library for identifying risks in the configuration of AWS Identity and 
Access Management (IAM) for an AWS account or an AWS organization. It models the different IAM Users and Roles in an 
account as a directed graph, which enables checks for privilege escalation and for alternate paths an attacker could 
take to gain access to a resource or action in AWS.

PMapper includes a querying mechanism that uses a local simulation of AWS's authorization behavior. 
When running a query to determine if a principal has access to a certain action/resource, PMapper also checks if the 
user or role could access other users or roles that have access to that action/resource. This catches scenarios such as 
when a user doesn't have permission to read an S3 object, but could launch an EC2 instance that can read the S3 object.

Additional information can be found in [the project wiki](https://github.com/nccgroup/PMapper/wiki).
