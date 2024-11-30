---
title: devise-otp
categories: ['ruby']
---
## [devise-otp](https://github.com/wmlele/devise-otp)

### Two Factors authentication for Devise using Time Based OTP/rfc6238 tokens.


Devise OTP is a Two-Factor Authentication extension for Devise. The second factor is done using an [RFC 6238](https://datatracker.ietf.org/doc/html/rfc6238) Time-Based One-Time Password (TOTP) implemented by the [rotp library](https://github.com/mdp/rotp).

It has the following features:

- Optional and mandatory OTP enforcement
- Setting up trusted browsers for limited access
- Generating QR codes

Some of the compatible token devices are:

* [Google Authenticator](https://code.google.com/p/google-authenticator/)
* [FreeOTP](https://fedorahosted.org/freeotp/)

Device OTP was recently updated to work with Rails 7+ and Turbo.
