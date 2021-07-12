---
title: php-vcr
categories: ['php', 'php-vcr', 'accurate-tests']
---
## [php-vcr](https://github.com/php-vcr/php-vcr)

### Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests.


* Automatically records and replays your HTTP(s) interactions with minimal setup/configuration code.
* Supports common http functions and extensions
  * everything using [streamWrapper](http://php.net/manual/en/class.streamwrapper.php): fopen(), fread(), file_get_contents(), ... without any modification (except `$http_response_header` see #96)
  * [SoapClient](http://www.php.net/manual/en/soapclient.soapclient.php) by adding `\VCR\VCR::turnOn();` in your `tests/bootstrap.php`
  * curl(), by adding `\VCR\VCR::turnOn();` in your `tests/bootstrap.php`
* The same request can receive different responses in different tests -- just use different cassettes.
* Disables all HTTP requests that you don't explicitly allow by [setting the record mode](http://php-vcr.github.io/documentation/configuration/)
* [Request matching](http://php-vcr.github.io/documentation/configuration/) is configurable based on HTTP method, URI, host, path, body and headers, or you can easily
  implement a custom request matcher to handle any need.
* The recorded requests and responses are stored on disk in a serialization format of your choice
  (currently YAML and JSON are built in, and you can easily implement your own custom serializer)
* Supports PHPUnit annotations.
