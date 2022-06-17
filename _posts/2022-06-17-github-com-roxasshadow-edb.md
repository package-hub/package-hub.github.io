---
title: EDB
categories: ['ruby']
---
## [EDB](https://github.com/RoxasShadow/EDB)

### A framework to make and manage backups of your database


*EDB* is a framework to make and manage backups of your database.
It is composed by three macro areas that reflect themself inside `edb.yml` and are *DBMS*, *CRYPTOGRAPHY* and *STORAGE*.
The first one deals with the actual backup process of your database. The second one will eventually encrypt the backup copies you made and the last one will copy them somewhere (S3 bucket, your local filesystem, etc.).


**tl;dr** Make (optionally) ciphered backups of your database(s) and then upload them via FTP and Amazon S3 (or just keep them in your server).
