---
title: BaRMIe
categories: ['java']
---
## [BaRMIe](https://github.com/NickstaDB/BaRMIe)

### Java RMI enumeration and attack tool.

BaRMIe is a tool for enumerating and attacking Java RMI (Remote Method Invocation) services.

RMI services often expose dangerous functionality without adequate security controls, however RMI services tend to pass under the radar during security assessments due to the lack of effective testing tools. In 2008 Adam Boulton spoke at AppSec USA ([YouTube](https://www.youtube.com/watch?v=owN9EnoLsFY)) and released some RMI attack tools which disappeared soon after, however even with those tools a successful zero-knowledge attack relies on a significant brute force attack (~64-bits/9 quintillion possibilities) being performed over the network.

The goal of BaRMIe is to enable security professionals to identify, attack, and secure insecure RMI services. Using partial RMI interfaces from existing software, BaRMIe can interact directly with those services without first brute forcing 64-bits over the network.

Download the latest version build and ready to run here: [https://github.com/NickstaDB/BaRMIe/releases/latest](https://github.com/NickstaDB/BaRMIe/releases/latest)
