---
title: atdatabases
categories: ['typescript', 'sql', 'postgres']
---
## [atdatabases](https://github.com/ForbesLindesay/atdatabases)

### TypeScript clients for databases that prevent SQL Injection


Using tagged template literals for queries, e.g.

```ts
db.query(sql`SELECT * FROM users WHERE id=${userID}`);
```

makes it virtually impossible for SQL Injection attacks to slip in un-noticed. All the @databases libraries enforce the use of the sql tagged template literals, so you can't accidentally miss them.

The query is then passed to your database engine as a separate string and values:

```js
{text: 'SELECT * FROM users WHERE id=?', values: [userID]}
```
