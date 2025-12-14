---
title: passwordless
categories: ['javascript']
---
## [passwordless](https://github.com/florianheinemann/passwordless)

### node.js/express module to authenticate users without password


Passwordless is a modern node.js module for [Express](http://expressjs.com/) that allows *authentication* and *authorization* without passwords by simply sending one-time password (OTPW) tokens via email or other means. It utilizes a very similar mechanism as the reset password feature of classic websites. The module was inspired by Justin Balthrop's article "[Passwords are Obsolete](https://medium.com/@ninjudd/passwords-are-obsolete-9ed56d483eb)"

Token-based authentication is...
* **Faster to implement** compared to typical user auth systems (you only need one form)
* **Better for your users** as they get started with your app quickly and don't have to remember passwords
* **More secure** for your users avoiding the risks of reused passwords
