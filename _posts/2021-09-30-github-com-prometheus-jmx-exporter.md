---
title: jmx_exporter
categories: ['java', 'jmx', 'prometheus']
---
## [jmx_exporter](https://github.com/prometheus/jmx_exporter)

### A process for exposing JMX Beans via HTTP for Prometheus consumption


The Java agent is available in two versions with identical functionality:
* [jmx_prometheus_javaagent-0.16.1.jar](https://repo1.maven.org/maven2/io/prometheus/jmx/jmx_prometheus_javaagent/0.16.1/jmx_prometheus_javaagent-0.16.1.jar) requires Java >= 7.
* [jmx_prometheus_javaagent-0.16.1_java6.jar](https://repo1.maven.org/maven2/io/prometheus/jmx/jmx_prometheus_javaagent_java6/0.16.1/jmx_prometheus_javaagent_java6-0.16.1.jar) is compatible with Java 6.

The only difference between these versions is the version of the bundled snakeyaml dependency. See [release notes](https://github.com/prometheus/jmx_exporter/releases/tag/parent-0.16.1) for more info.

To run as a Java agent, download one of the JARs and run:
```
java -javaagent:./jmx_prometheus_javaagent-0.16.1.jar=8080:config.yaml -jar yourJar.jar
```
Metrics will now be accessible at http://localhost:8080/metrics

To bind the java agent to a specific IP change the port number to `host:port`.

See `./run_sample_httpserver.sh` for a sample script that runs the httpserver against itself.

Please note that due to the nature of JMX the `/metrics` endpoint might exceed Prometheus default scrape timeout of 10 seconds.
