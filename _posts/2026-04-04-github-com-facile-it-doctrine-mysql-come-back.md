---
title: doctrine-mysql-come-back
categories: ['php', 'hacktoberfest', 'doctrine-dbal']
---
## [doctrine-mysql-come-back](https://github.com/facile-it/doctrine-mysql-come-back)

### Doctrine DBAL able to try reconnect on MySQL has gone away exceptions


This library tries to solve the infamous "MySQL has gone away" issue, and similar ones. 

It does so by providing a `doctrine/dbal` driver wrapper that automatically reconnects to the database server when applicable; to avoid consistency issues, the reconnection is not attempted when writes are concerned (i.e. open transaction, timeout on write queries).
