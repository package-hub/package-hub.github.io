---
title: cfn-lint
categories: ['typescript', 'cloudformation', 'intrinsic-functions']
---
## [cfn-lint](https://github.com/martysweet/cfn-lint)

### A CloudFormation JSON and YAML Validator


A more friendly CloudFormation JSON and YAML Validator

`cfn-lint` is a tool used to improve your CloudFormation development cycle. If you are here, you are probably
fed up of waiting for 10 minutes or more before CloudFormation gives you an error due to a typo. This tool aims to 
remove that waste of time. The tool takes the CloudFormation template, and resolves all the Intrinsic functions 
defined before checking the Properties of Resources defined. 

The tool can be used over the commandline using `cfn-lint`, or can be used as a module within another JavaScript application.

*Note: This tool is currently case-sensitive in relation to AWS CloudFormation types, for example aws::lambda::function != AWS::Lambda::Function.*
