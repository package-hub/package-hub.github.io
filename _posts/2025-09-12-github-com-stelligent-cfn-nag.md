---
title: cfn_nag
categories: ['ruby', 'continuous-testing', 'unit-testing']
---
## [cfn_nag](https://github.com/stelligent/cfn_nag)

### Linting tool for CloudFormation templates


The cfn-nag tool looks for patterns in CloudFormation templates that may indicate insecure infrastructure.
Roughly speaking, it will look for:

* IAM rules that are too permissive (wildcards)
* Security group rules that are too permissive (wildcards)
* Access logs that aren't enabled
* Encryption that isn't enabled
* Password literals

For more background on the tool, please see this post at Stelligent's blog:

[Finding Security Problems Early in the Development Process of a CloudFormation Template with "cfn-nag"](https://stelligent.com/2016/04/07/finding-security-problems-early-in-the-development-process-of-a-cloudformation-template-with-cfn-nag/)
