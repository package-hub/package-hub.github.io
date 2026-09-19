---
title: minimal-json
categories: ['java']
---
## [minimal-json](https://github.com/ralfstx/minimal-json)

### A fast and small JSON parser and writer for Java


You can parse JSON from a `String` or from a `java.io.Reader`. You *don't* need to wrap your reader in a BufferedReader, as the parse method uses a reading buffer.

```java
JsonValue value = Json.parse(string);
```
