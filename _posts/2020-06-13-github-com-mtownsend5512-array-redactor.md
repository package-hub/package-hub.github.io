---
title: array-redactor
categories: ['php', 'array', 'redactor']
---
## [array-redactor](https://github.com/mtownsend5512/array-redactor)

### A PHP package to redact array values by their keys.


Have you ever built or interacted with an api and needed to log all outgoing and incoming calls? Chances are that somewhere in that process is an authentication, either by an app or on behalf of a user. Logs are useful for debugging, but storing sensitive information such as passwords or api keys is not something you want to have in your logs for anyone to see. The usage goes beyond just this example, but that is what prompted me to create the ArrayRedactor package.

Whatever your usage needs may be, this package aims to provide a dead-simple, lightweight way to censor sensitive information in an array no matter how deeply it is nested.
