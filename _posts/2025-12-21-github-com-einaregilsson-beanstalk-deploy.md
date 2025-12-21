---
title: beanstalk-deploy
categories: ['javascript']
---
## [beanstalk-deploy](https://github.com/einaregilsson/beanstalk-deploy)

### GitHub action (and command line script) to deploy apps to Elastic Beanstalk


Beanstalk Deploy is a GitHub action (and command line script) to deploy apps to AWS Elastic Beanstalk. It takes the application
name, environment name, version name, region and filename as parameters, uploads the file to S3, creates a new version in
Elastic Beanstalk, and then deploys that version to the environment. It will wait until the deployment is finished, logging
any messages from the environment during the update and exiting with a non-zero exit code if the deployment fails. It does
not handle rolling back the environment.
