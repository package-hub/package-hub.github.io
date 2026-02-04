---
title: wp-migrations
categories: ['php']
---
## [wp-migrations](https://github.com/deliciousbrains/wp-migrations)

### WordPress library for managing database table schema upgrades and data seeding


A WordPress library for managing database table schema upgrades and data seeding.

Ever had to create a custom table for some plugin or custom code to use? To keep the site updated with the latest version of that table you need to keep track of what version the table is at. This can get overly complex for lots of tables.

This package is inspired by [Laravel's database migrations](https://laravel.com/docs/5.8/migrations). You create a new migration PHP file, add your schema update code, and optionally include a rollback method to reverse the change. 

Simply run `wp dbi migrate` on the command line using WP CLI and any migrations not already run will be executed.

The great thing about making database schema and data updates with migrations, is that the changes are file-based and therefore can be stored in version control, giving you better control when working across different branches. 
