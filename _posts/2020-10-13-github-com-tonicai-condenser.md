---
title: condenser
categories: ['python', 'database', 'subsetter']
---
## [condenser](https://github.com/TonicAI/condenser)

### Condenser is a database subsetting tool


Condenser is a config-driven database subsetting tool for Postgres and MySQL.

Subsetting data is the process of taking a representative sample of your data in a manner that preserves the integrity of your database, e.g., give me 5% of my users. If you do this naively, e.g., just grab 5% of all the tables in your database, most likely, your database will break foreign key constraints. At best, you’ll end up with a statistically non-representative data sample.

One common use-case is to scale down a production database to a more reasonable size so that it can be used in staging, test, and development environments. This can be done to save costs and, when used in tandem with PII removal, can be quite powerful as a productivity enhancer. Another example is copying specific rows from one database and placing them into another while maintaining referential integrity.

You can find more details about how we built this [here](https://www.tonic.ai/blog/condenser-a-database-subsetting-tool) and [here](https://www.tonic.ai/post/condenser-v2/).
