---
title: herddb
categories: ['java', 'database', 'distributed']
---
## [herddb](https://github.com/diennea/herddb)

### A JVM-embeddable Distributed Database


HerdDB is a **distributed Database**, data is distributed among a cluster of server **without the need of a shared storage**.

HerdDB primary language is **SQL** and clients are encouraged to use both the JDBC Driver API and the low level API.

HerdDB is **embeddable** in any Java Virtual Machine, each node will access directly to local data without the use of the network.

HerdDB replication functions are built upon **Apache ZooKeeper** and **Apache BookKeeper**.

HerdDB is internally very similar to a NoSQL database and, basically, it is a **key-value DB** with an SQL abstraction layer which enables every user to leverage existing known-how and to port existing applications.

*HerdDB has been designed for fast "writes" and for primary key read/update data access patterns.*

HerdDB supports **transactions** and "committed read" isolation level

HerdDB uses **Apache Calcite** as SQL parser and SQL Planner
