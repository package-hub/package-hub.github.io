---
title: mongodb-file-server
categories: ['java', 'file-server', 'mongodb']
---
## [mongodb-file-server](https://github.com/waylau/mongodb-file-server)

### MongoDB File Server is a file server system based on MongoDB. 基于 MongoDB 的文件服务器。


MongoDB File Server is a file server system based on MongoDB. MongoDB File Server is committed to the storage of small files, such as pictures in the blog, ordinary documents and so on.

It's using some very popular technology like:

* MongoDB 3.6.4
* Spring Boot 2.0.3.RELEASE
* Spring Data MongoDB 2.0.8.RELEASE
* Spring 5.0.7.RELEASE
* Thymeleaf 3.0.9.RELEASE
* Thymeleaf Layout Dialect 2.2.0
* Embedded MongoDB 2.0.2
* Gradle 4.5.1

基于 MongoDB 的文件服务器。MongoDB File Server 致力于小型文件的存储，比如博客中图片、普通文档等。由于MongoDB 支持多种数据格式的存储，对于二进制的存储自然也是不话下，所以可以很方便的用于存储文件。由于  MongoDB 的 BSON 文档对于数据量大小的限制（每个文档不超过16M），所以本文件服务器主要针对的是小型文件的存储。对于大型文件的存储（比如超过16M），MongoDB 官方已经提供了成熟的产品  [GridFS](https://docs.mongodb.com/manual/core/gridfs/)，读者朋友可以自行了解。

本文不会对 MongoDB 的概念、基本用法做过多的介绍，有兴趣的朋友可自行查阅其他文献，比如，笔者所著的[《分布式系统常用技术及案例分析》](https://github.com/waylau/distributed-systems-technologies-and-cases-analysis)一书，对 MongoDB 方面也有所着墨。 

