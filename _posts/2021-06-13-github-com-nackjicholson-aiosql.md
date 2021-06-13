---
title: aiosql
categories: ['python']
---
## [aiosql](https://github.com/nackjicholson/aiosql)

### Simple SQL in Python


Simple SQL in Python

SQL is code, you should be able to write it, version control it, comment it, and run it using files. Writing your SQL code in Python programs as strings doesn't allow you to easily reuse your SQL in database GUI tools or CLI tools like psql. With aiosql you can organize your SQL statements in _.sql_ files, load them into your python application as methods to call without losing the ability to use them as you would any other SQL file.

This project supports standard and [asyncio](https://docs.python.org/3/library/asyncio.html) based drivers for SQLite and PostgreSQL out of the box ([sqlite3](https://docs.python.org/3/library/sqlite3.html), [aiosqlite](https://aiosqlite.omnilib.dev/en/latest/?badge=latest), [psycopg2](https://www.psycopg.org/docs/), [asyncpg](https://magicstack.github.io/asyncpg/current/)). Extensions to support other database drivers can be written by you!

If you are using python versions <3.6 please see the related [anosql](https://github.com/honza/anosql) package which this project is based on.
