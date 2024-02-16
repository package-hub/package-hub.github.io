---
title: jobrunr
categories: ['java', 'java-8', 'background-jobs']
---
## [jobrunr](https://github.com/jobrunr/jobrunr)

### An extremely easy way to perform background processing in Java. Backed by persistent storage. Open and free for commercial use.

```java
BackgroundJob.enqueue(() -> System.out.println("This is all you need for distributed jobs!"));
```

Incredibly easy way to perform **fire-and-forget**, **delayed**, **scheduled** and **recurring jobs** inside **Java applications** using only *Java 8 lambda's*. CPU and I/O intensive, long-running and short-running jobs are supported. Persistent storage is done via either RDBMS (e.g. Postgres, MariaDB/MySQL, Oracle, SQL Server, DB2 and SQLite) or NoSQL (ElasticSearch, MongoDB and Redis).

JobRunr provides a unified programming model to handle background tasks in a **reliable way** and runs them on shared hosting, dedicated hosting or in the cloud ([hello Kubernetes](https://www.jobrunr.io/en/blog/2020-05-06-jobrunr-kubrnetes-terraform/)) within a JVM instance.

