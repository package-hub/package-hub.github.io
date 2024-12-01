---
title: POCDriver
categories: ['java']
---
## [POCDriver](https://github.com/johnlpage/POCDriver)

### Workload Driver for MongoDB in Java


Disclaimer: POCDriver is NOT in any way an official MongoDB product or project.

This is open source, immature, and undoubtedly buggy code. If you find bugs please fix them and [send a pull request](https://github.com/johnlpage/POCDriver/pulls) or report in the [GitHub issue queue](https://github.com/johnlpage/POCDriver/issues).

This tool is designed to make it easy to answer many of the questions people have during a MongoDB 'Proof of Concept':

- How fast will MongoDB be on my hardware?
- How could MongoDB handle my workload?
- How does MongoDB scale?
- How does High Availability work (aka How do I handle a failover)?

POCDriver is a single JAR file which allows you to specify and run a number of different workloads easily from the command line. It is intended to show how MongoDB should be used for various tasks and avoids testing your own client code versus MongoDB's capabilities.

POCDriver is an alternative to using generic tools like YCSB. Unlike these tools, POCDriver:

- Only works with MongoDB. This shows what MongoDB can do rather than comparing lowest common denominator between systems that aren't directly comparable.

- Includes much more sophisticated workloads using the appropriate MongoDB feature.
