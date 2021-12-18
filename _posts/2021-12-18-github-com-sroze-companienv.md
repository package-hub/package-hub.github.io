---
title: companienv
categories: ['php', 'dotenv', 'companion']
---
## [companienv](https://github.com/sroze/companienv)

### Companion for .env files


Your companion for `.env` files. Everybody knows about [12 factor](https://12factor.net/) and [environments variables](https://12factor.net/config) now.
A lot of frameworks such as Symfony [are using a `.env` file](https://symfony.com/doc/current/configuration.html#the-env-file-environment-variables) to configure the application,
but we don't have anything to help users to complete their local `.env` file.

Companienv will helps you manage the `.env` files, from a reference `.env.dist` version in your code repository. Companienv can:

- Read and populate default values
- Identify and ask only missing variables
- Ask variables [only if matching some conditions](#only-if-extension)
- [Propagate files](#file-to-propagate-extension) (copy files from somewhere else)
- Generate [public/private RSA keys](#rsa-pair-extension)
- Generate [SSL certificates](#ssl-certificate-extension)
- Much more, via [your own extensions](#your-own-extensions)
