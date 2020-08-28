---
title: bitauth
categories: ['javascript']
---
## [bitauth](https://github.com/bitpay/bitauth)

### Authenticate with web services utilizing the same strategy as Bitcoin.


BitAuth is a way to do secure, passwordless authentication using the cryptography
in Bitcoin. Instead of using a shared secret, the client signs each request using
a private key and the server checks to make sure the signature is valid and matches
the public key.
