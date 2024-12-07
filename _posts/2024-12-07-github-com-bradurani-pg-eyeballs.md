---
title: pg-eyeballs
categories: ['ruby']
---
## [pg-eyeballs](https://github.com/bradurani/pg-eyeballs)

### A Ruby gem for using the postgres explain command with Active Record :eyes:


`pg-eyeballs` is a ruby gem that gives you detailed information about how the
SQL queries created by the active record code you write are executed by the database.
It gives you an easy, ruby friendly way to see the output of the Postgres
[`EXPLAIN` command](https://www.postgresql.org/docs/9.4/static/using-explain.html) and integrates with the popular query analysis tool [`gocmdpev`](https://github.com/simon-engledew/gocmdpev).

Using it you can see:
- What queries were run
- How long they took
- Which indexes were used
- Which algorithms were used
- Much more!
