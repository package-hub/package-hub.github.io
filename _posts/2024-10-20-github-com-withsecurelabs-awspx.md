---
title: awspx
categories: ['python', 'aws', 'aws-security']
---
## [awspx](https://github.com/WithSecureLabs/awspx)

### A graph-based tool for visualizing effective access and resource relationships in AWS environments.


**awspx** is a graph-based tool for visualizing effective access and resource relationships within AWS. It resolves policy information to determine *what* actions affect *which* resources, while taking into account how these actions may be combined to produce attack paths. Unlike tools like [Bloodhound](https://github.com/BloodHoundAD/BloodHound), awspx requires permissions to function — it is not expected to be useful in cases where these privileges have not been granted.
