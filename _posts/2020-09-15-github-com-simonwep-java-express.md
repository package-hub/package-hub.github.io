---
title: java-express
categories: ['java', 'http-server', 'java-http-server']
---
## [java-express](https://github.com/Simonwep/java-express)

### 🧪 HTTP Framework  based on expressjs, no dependencies, simple usage. Can be used to quickly spin up an API or serve local files.

```java
Express app = new Express();

app.get("/", (req, res) -> {
   res.send("Hello World");
}).listen(); // Will listen on port 80 which is set as default
```
