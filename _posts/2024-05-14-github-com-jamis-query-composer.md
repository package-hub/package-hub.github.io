---
title: query-composer
categories: ['ruby']
---
## [query-composer](https://github.com/jamis/query-composer)

### A library for composing complex SQL queries by defining their subcomponents and the dependencies between them.


Simple SQL queries are, well, simple. But when you start needing to deal with nested subqueries, and especially when those nested subqueries themselves require nested subqueries...things start getting difficult to manage.

`Query::Composer` was extracted from a real application, where reporting queries were dynamically generated and typically exceeded 50KB of text for the query alone!

This library allows you to specify each component of query independently, as well as allowing you to indicate which other components each component depends on. The composer will then build the correct query from those components, on demand.
