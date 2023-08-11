---
title: guzzle-oauth2-plugin
categories: ['php']
---
## [guzzle-oauth2-plugin](https://github.com/commerceguys/guzzle-oauth2-plugin)

### Provides an OAuth2 plugin (subscriber) for Guzzle


- Acquires access tokens via one of the supported grant types (code, client credentials,
  user credentials, refresh token). Or you can set an access token yourself.
- Supports refresh tokens (stores them and uses them to get new access tokens).
- Handles token expiration (acquires new tokens and retries failed requests).
