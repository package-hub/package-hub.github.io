---
title: nextcloud-oidc-login
categories: ['php', 'nextcloud', 'nextcloud-login']
---
## [nextcloud-oidc-login](https://github.com/pulsejet/nextcloud-oidc-login)

### Nextcloud login via a single OpenID Connect 1.0 provider


Make possible create users and login via one single OpenID Connect provider. Even though a fork of [nextcloud-social-login](https://github.com/zorn-v/nextcloud-social-login), it fundamentally differs in two ways - aims for simplistic, single provider login (and hence is very minimalistic), and it supports having LDAP as the primary user backend. This way, you can use OpenID Connect to login to Nextcloud while maintaining an LDAP backend with attributes with the LDAP plugin. Supports automatic discovery of endpoints through the OpenID Connect spec, with a single provider configuration attribute. It also supports accessing Nextcloud WebDAV using a providers bearer token.
