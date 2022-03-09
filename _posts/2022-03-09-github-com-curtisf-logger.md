---
title: logger
categories: ['javascript']
---
## [logger](https://github.com/curtisf/logger)

### Loggerbot version 3, the Discord bot serving nearly 24 million users.


A detailed guide has yet to be made. You will need:
- PostgreSQL 11
- Redis
- NodeJS

1. Setup Postgres and add a superuser (default user works)
2. Clone bot repo and enter the created folder
3. Copy .env.example into .env
4. Fill out **all** fields in it (even Sentry unless you hotpatch it out)
5. `npm install`
6. `node src/miscellaneous/generateDB.js`
6. `node index.js`
