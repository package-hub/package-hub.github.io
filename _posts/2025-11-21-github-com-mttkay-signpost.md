---
title: signpost
categories: ['java']
---
## [signpost](https://github.com/mttkay/signpost)

### A light-weight client-side OAuth library for Java

Using Signpost is as simple as it could possibly get -- all actions are executed with only a few lines of code. For example, this is how you would sign a classic Java HTTP message using Signpost:

```java
        // create an HTTP request to a protected resource
        URL url = new URL("http://api.example.com/protected")
        HttpURLConnection request = (HttpURLConnection) url.openConnection();

        // sign the request (consumer is a Signpost DefaultOAuthConsumer)
        consumer.sign(request);

        // send the request
        request.connect();
```

Signpost exposes a minimalistic API designed for two purposes: Signing HTTP messages and requesting tokens from an OAuth service provider. Everything else is beyond the scope of the OAuth specification, and is thus left to the HTTP messaging layer, where it belongs.

For more exhaustive examples, please refer to [GettingStarted](docs/GettingStarted.md).
