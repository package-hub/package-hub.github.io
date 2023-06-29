---
title: card-validator
categories: ['typescript']
---
## [card-validator](https://github.com/braintree/card-validator)

### Validate credit cards as users type.


Credit Card Validator provides validation utilities for credit card data inputs. It is designed as a CommonJS module for use in Node.js, io.js, or the [browser](http://browserify.org/). It includes first class support for 'potential' validity so you can use it to present appropriate UI to your user as they type.

A typical use case in a credit card form is to notify the user if the data they are entering is invalid. In a credit card field, entering “411” is not necessarily valid for submission, but it is still potentially valid. Conversely, if a user enters “41x” that value can no longer pass strict validation and you can provide a response immediately.

Credit Card Validator will also provide a determined card type (using [credit-card-type](https://github.com/braintree/credit-card-type)). This is useful for scenarios in which you wish to render an accompanying payment method icon (Visa, MasterCard, etc.). Additionally, by having access to the current card type, you can better manage the state of your credit card form as a whole. For example, if you detect a user is entering (or has entered) an American Express card number, you can update the `maxlength` attribute of your `CVV` input element from 3 to 4 and even update the corresponding `label` from 'CVV' to 'CID'.
