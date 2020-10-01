---
title: X2CRM
categories: ['php']
---
## [X2CRM](https://github.com/X2Engine/X2CRM)

### X2CRM Open Source CRM - PHP


1/3/2019
* General Changelog / Developer Notes
  * X2CRM is now compatible with PHP 7.1+

* Miscellaneous bug fixes
  * Fixed issue with emailing where mail servers which are not configured to use VERP can still send email
  * Removed list option from the reporting module
  * A/B campaigns now work with dynamic lists
  * Fixed issue where 'do not email' settings would get incorrectly set
  * Fixed issue where a 500 error would occur if the 'maxFileSize' attribute was not created correctly
  * Fixed issue where X2Flow would incorrectly reference a workflow ID
  * Fixed issue where logging time on a record would incorrectly calculate time spent
  * Fixed front-end with the complete stage action in X2Workflow where the note textarea was covering the stage selection dropdown
