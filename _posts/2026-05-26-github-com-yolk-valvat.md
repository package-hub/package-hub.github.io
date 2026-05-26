---
title: valvat
categories: ['ruby', 'taxes', 'vat-validation']
---
## [valvat](https://github.com/yolk/valvat)

### Validates european vat numbers. Standalone or as a ActiveModel validator.


Valvat supports validating VAT-IDs from the UK by syntax, checksum and using the HMRC API v2.0. Validation against the VIES web service stopped working early 2021.

Sadly with the deprecation of the HMRC API v1 on January 2025 there is no open accessible web service to validate UK vat numbers anymore. To use the current v2 of the HMRC API you will need to create an account on the [HMRC Developer Hub](https://developer.service.hmrc.gov.uk/developer/registration) and then apply for production credentials. The second step is a little bit more involved and can take up to ten business days. See the configuration section below how to use valvat with your HMRC authentication credentials.

Northern Ireland received its own VAT number prefix - XI which is supported by VIES web service so any XI-prefixed VAT numbers should be validated as any EU VAT number.
