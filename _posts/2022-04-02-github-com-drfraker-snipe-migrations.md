---
title: snipe-migrations
categories: ['php', 'laravel', 'migrations']
---
## [snipe-migrations](https://github.com/drfraker/snipe-migrations)

### Blazing fast database migrations for Laravel tests.


Blazing fast database migrations for Laravel tests. 

The package takes a snapshot of your mysql database and imports the schema to your test database rather than running 
all of your migrations when the test suite starts up. 

If you have a project with many migration files, this process can provide you with a massive speed improvement when 
initializing your test suite. This package can be used as a replacement for the RefreshDatabase trait that is provided out
of the box with Laravel.

As an example, we tested this on an application that takes about 4 seconds to run all migrations with RefreshDatabase. 
Using SnipeMigrations the tests start up in 200 ms.
