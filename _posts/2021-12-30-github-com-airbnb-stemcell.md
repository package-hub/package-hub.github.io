---
title: stemcell
categories: ['ruby']
---
## [stemcell](https://github.com/airbnb/stemcell)

### Airbnb's EC2 instance creation and bootstrapping tool


Stemcell launches instances in EC2.
These instances are created to your specification, with knobs like AMI, instance type, and region exposed.
The instances are bootstrapped with chef-solo, using a specified git repo and branch as the source of roles and recipes.
