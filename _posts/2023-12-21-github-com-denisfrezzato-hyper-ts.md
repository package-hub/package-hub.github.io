---
title: hyper-ts
categories: ['typescript']
---
## [hyper-ts](https://github.com/DenisFrezzato/hyper-ts)

### Type safe middleware architecture for HTTP servers


The goal of `hyper-ts` is to make use of type system features in TypeScript to enforce correctly stacked middleware in
HTTP server applications. All effects of middleware should be reflected in the types to ensure that common mistakes
cannot be made. A few examples of such mistakes could be:

- Incorrect ordering of header and body writing
- Writing incomplete responses
- Writing multiple responses
- Trying to consume a non-parsed request body
- Consuming a request body parsed as the wrong type
- Incorrect ordering of, or missing, error handling middleware
- Incorrect ordering of middleware for sessions, authentication, authorization
- Missing authentication and/or authorization checks
