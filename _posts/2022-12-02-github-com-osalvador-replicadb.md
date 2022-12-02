---
title: ReplicaDB
categories: ['java', 'fast', 'nosql-databases']
---
## [ReplicaDB](https://github.com/osalvador/ReplicaDB)

### ReplicaDB is open source tool for database replication, designed for efficiently transferring bulk data between relational and non-relational databases


Because I have not found any tool that covers my needs:

- Open Source.
- Java based cross-platform solution, compatible with Linux, Windows, and MacOS.
- Any database engine SQL, NoSQL, or other persistent stores like CSV, Amazon S3, or Kafka. 
- Simple architecture, just a command line tool that can run on any server (including my laptop), without any remote agents in the databases.
- Good performance for a large amount of data. 
- I do not need streaming replication or a pure change data capture (CDC) system that requires installation in the source database.

I have reviewed and tested other open source tools and none of them meets all the above requirements:

- **SymetricDS**: It was the best option of all, but I was looking for a smaller solution, mainly focused on performance. SymmetricDS is intrusive since installs database triggers that capture data changes in a data capture table. This table requires maintenance. SymmetricDS is more like a CDC system based on triggers.  
- **Sqoop**: Sqoop is what I was looking for, but oh! it is only valid for Hadoop.
- **Pentaho** and **Talend**: Both are very complete ETL tools, but for each of the different source and sink tables that I have to replicate, I should do a custom development

