---
title: capistrano-db-tasks
categories: ['ruby']
---
## [capistrano-db-tasks](https://github.com/sgruhier/capistrano-db-tasks)

### Add capistrano tasks for syncing remote and local database


Add database AND assets tasks to capistrano to a Rails project. It only works with capistrano 3. Older versions until 0.3 works with capistrano 2.

Currently

* It only supports mysql and postgresql (both side remote and local)
* Synchronize assets remote to local and local to remote

Commands mysql, mysqldump (or pg\_dump, psql), bzip2 and unbzip2 (or gzip) must be in your PATH

Feel free to fork and to add more database support or new tasks.
