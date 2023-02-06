---
title: terraform-aws-notify-slack
categories: ['python', 'aws', 'aws-lambda']
---
## [terraform-aws-notify-slack](https://github.com/terraform-aws-modules/terraform-aws-notify-slack)

### Terraform module which creates SNS topic and Lambda function which sends notifications to Slack 🇺🇦


This module creates an SNS topic (or uses an existing one) and an AWS Lambda function that sends notifications to Slack using the [incoming webhooks API](https://api.slack.com/incoming-webhooks).

Start by setting up an [incoming webhook integration](https://my.slack.com/services/new/incoming-webhook/) in your Slack workspace.

Doing serverless with Terraform? Check out [serverless.tf framework](https://serverless.tf), which aims to simplify all operations when working with the serverless in Terraform.
