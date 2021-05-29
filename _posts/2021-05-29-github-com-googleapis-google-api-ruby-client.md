---
title: google-api-ruby-client
categories: ['ruby']
---
## [google-api-ruby-client](https://github.com/googleapis/google-api-ruby-client)

### REST client for Google APIs


This repository contains a set of simple client libraries for various Google APIs. These libraries are generated automatically from [Discovery Documents](https://developers.google.com/discovery), and the code generator is also hosted here in this repository.

Each client provides:

* A client object that connects to the HTTP/JSON REST endpoint for the service.
* Ruby objects for data structures related to the service.
* Integration with the googleauth gem for authentication using OAuth, API keys, and service accounts.
* Control of retry, pagination, and timeouts.

These client libraries are officially supported by Google, and are updated regularly to track changes to the service. However, many Google services, especially Google Cloud Platform services such as Cloud Storage, Pub/Sub, and BigQuery, may provide a more modern client that is easier to use and more performant. See the section below titled ["Which client should I use?"](#which-client-should-i-use) for more information.
