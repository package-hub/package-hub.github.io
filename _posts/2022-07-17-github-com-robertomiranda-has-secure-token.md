---
title: has_secure_token
categories: ['ruby']
---
## [has_secure_token](https://github.com/robertomiranda/has_secure_token)

### Create uniques random tokens for any model in ruby on rails. Backport of ActiveRecord::SecureToken 5 to AR 3.x and 4.x


HasSecureToken provides an easy way to generate uniques random tokens for any model in ruby on rails. **SecureRandom::base58** is used to generate the 24-character unique tokens, so collisions are highly unlikely.

**Note** If you're worried about possible collissions, there's a way to generate a race condition in the database in the same way that [validates_uniqueness_of](http://api.rubyonrails.org/classes/ActiveRecord/Validations/ClassMethods.html) can. You're encouraged to add an unique index in the database to deal with this even more unlikely scenario.
