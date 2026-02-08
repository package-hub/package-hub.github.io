---
title: DBDiff
categories: ['php']
---
## [DBDiff](https://github.com/DBDiff/DBDiff)

### Compare MySQL databases & automatically create schema & data change scripts/migrations rapidly (up & down SQL supported) for database version control. Supports *some* migration tools.

-   Works on Windows, Linux & Mac command-line/Terminal because it has been developed in PHP
-   Connects to a source and target database to do the comparison diff, locally and remotely
-   Diffs can include changes to the schema and/or data, both in valid SQL to bring the target up-to-date with the source
-   Some tables and/or fields can be ignored in the comparison with a YAML collection in the config file (see File Examples)
-   Diffs are SUPER fast and this tool has been tested with databases of multiple tables of millions of rows
-   Since this diff tool is being used for migrations, it provides up and down SQL in the same file
-   Works with existing migration tools like Flyway and Simple DB Migrate by specifying output template files/formats, for example, Simple DB Migrate may work with simple-db-migrate.tmpl which includes: `SQL_UP = u""" {{ $up }} """ SQL_DOWN = u""" {{ $down }} """`
-   Is Unicode aware, can work with UTF8 data, which includes foreign characters/symbols
-   Works with just MySQL for now, but we will be expanding to other DBs in the future on request (please create an issue and vote on it!)
