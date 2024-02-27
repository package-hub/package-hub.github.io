---
title: sitewhere
categories: ['java', 'sitewhere', 'internet-of-things']
---
## [sitewhere](https://github.com/sitewhere/sitewhere)

### SiteWhere is an industrial strength open-source application enablement platform for the Internet of Things (IoT). It provides a multi-tenant microservice-based infrastructure that includes device/asset management, data ingestion, big-data storage, and integration through a modern, scalable architecture.  SiteWhere provides REST APIs for all system functionality.  SiteWhere provides SDKs for many common device platforms including Android, iOS, Arduino, and any Java-capable platform such as Raspberry Pi rapidly accelerating the speed of innovation.


SiteWhere is composed of Java-based microservices which are built as
[Docker](https://www.docker.com/) images and deployed to Kubernetes for
orchestration. To simplify installation and configuration, [Helm](https://helm.sh/) 
is used to provide standard templates for various deployment scenarios. Helm
[charts](https://github.com/sitewhere/sitewhere-recipes/tree/master/charts)
are provided to supply both the microservices and the dependencies needed to 
run a complete SiteWhere deployment. Infrastructure components include 
technologies such as Apache Zookeeper and Kafka, highly available databases such
as MongoDB, InfluxDB, and Cassandra, and other supporting technologies 
such as MQTT brokers.
