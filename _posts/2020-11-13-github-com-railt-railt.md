---
title: railt
categories: ['php', 'graphql', 'framework']
---
## [railt](https://github.com/railt/railt)

### ⚡️ A PHP GraphQL Framework



Project idea is clean and high-quality code.
Unlike most (all at the moment) implementations, like [webonyx](https://github.com/webonyx/graphql-php), 
[youshido](https://github.com/youshido-php/GraphQL) or [digitalonline](https://github.com/digiaonline/graphql-php) 
the Railt contains a completely own implementation of the GraphQL SDL parser 
which is based on [EBNF-like grammar](https://github.com/railt/railt/tree/1.4.x/resources/graphql). This opportunity 
allows not only to have the [original implementation of the language](https://facebook.github.io/graphql/draft/) and to 
keep it always up to date, but also to implement [a new backward compatible 
functionality](https://github.com/railt/railt/projects/1) that is not available 
to other implementations.

Goal of Railt:
- Do not repeat the mistakes made in the JS-based implementations.
- Implement a modern and convenient environment for PHP developers.
- Implement easy integration into any ready-made solutions based on PSR.
- Provide familiar functionality (including dependency injection, routing, etc.).
