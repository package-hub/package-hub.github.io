---
title: sync-dotenv
categories: ['typescript', 'nodejs', 'dotenv']
---
## [sync-dotenv](https://github.com/codeshifu/sync-dotenv)

### Keep your .env in sync with .env.example


Projects often rely on environmental variables stored in a `.env` file to run... and because these
variables sometimes contain sensitive data, we never add them to source control.
Instead, these variables are added e.g. to a `.env.example` file so it's easy to
get the project running for other developers. However, it's very easy to forget to update this file
when a variable is added/updated in `.env` (during development). This can make
it difficult for devs to get the project running (locally) because they rely on
`.env.example` file to setup their environment (with their own configs).

Enter `sync-dotenv` 🔥
