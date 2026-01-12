---
title: devise-pwned_password
categories: ['ruby']
---
## [devise-pwned_password](https://github.com/michaelbanfield/devise-pwned_password)

### Devise extension that checks user passwords against the PwnedPasswords dataset

Devise extension that checks user passwords against the PwnedPasswords dataset (https://haveibeenpwned.com/Passwords).

Checks for compromised ("pwned") passwords in 2 different places/ways:
1. As a standard model validation using [pwned](https://github.com/philnash/pwned). This:
   - prevents new users from being created (signing up) with a compromised password
   - prevents existing users from changing their password to a password that is known to be compromised
2. (Optionally) Whenever a user signs in, checks if their current password is compromised and shows a warning if it is.

Based on [devise-uncommon_password](https://github.com/HCLarsen/devise-uncommon_password).

Recently the HaveIBeenPwned API has moved to an [authenticated/paid model](https://www.troyhunt.com/authentication-and-the-have-i-been-pwned-api/), but this does not affect the PwnedPasswords API; no payment or authentication is required.

