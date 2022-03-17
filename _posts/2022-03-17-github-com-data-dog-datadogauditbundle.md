---
title: DataDogAuditBundle
categories: ['php']
---
## [DataDogAuditBundle](https://github.com/DATA-DOG/DataDogAuditBundle)

### Stores all database changes for doctrine ORM


This bundle creates an audit log for all doctrine ORM database related changes:

- inserts and updates including their diffs and relation field diffs.
- many to many relation changes, association and dissociation actions.
- if there is an user in token storage, it will link him to the log.
- the audit entries are inserted within the same transaction during **flush**,
if something fails the state remains clean.

Basically you can track any change from these log entries if they were
managed through standard **ORM** operations.

**NOTE:** audit cannot track DQL or direct SQL updates or delete statement executions.
