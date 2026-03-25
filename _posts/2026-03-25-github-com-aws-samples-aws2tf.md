---
title: aws2tf
categories: ['python']
---
## [aws2tf](https://github.com/aws-samples/aws2tf)

### aws2tf - automates the importing of existing AWS resources into Terraform and outputs the Terraform HCL code.


aws2tf.py will import into Terraform existing AWS infrastructure, and produce the corresponding Terraform HCL files. 

`aws2tf.py` will also attempt to:

* De-reference hardcoded values into their Terraform addresses.
* Find dependent resources and import them.
* Where possible, remove region and account references and replace with Terraform data values.


Finally aws2tf runs a `terraform plan` command and there should hopefully be no subsequent additions or deletions reported by the terraform plan command as all the appropriate terraform configuration files will have automatically been created.
