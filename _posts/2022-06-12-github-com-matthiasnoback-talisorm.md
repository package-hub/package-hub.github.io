---
title: TalisORM
categories: ['php']
---
## [TalisORM](https://github.com/matthiasnoback/TalisORM)

### An ORM for "ORMless" persistance of DDD-inspired domain models


A good design starts with some limitations. You can start simple and keep building until you have a large ORM like Doctrine. Or you can choose not to support a mapping configuration, table inheritance, combined write/read models, navigable object graphs, lazy-loading, etc. That's what I'm looking for with TalisOrm. The rules are:

- You model a persistable domain object as an _Aggregate_: one (root) _Entity_, and optionally some _Child entities_.
- The child entities themselves have no children.
- You use the ORM for your _write model_ only. That is, you don't need to fetch hundreds of these aggregates to show them to the user.
- Your aggregate internally records domain events, which will automatically be released and dispatched after saving changes to the aggregate.

Furthermore:

- You're going to write your own mapping code, which converts your values or _Value objects_ to and from column values.

I explain more about the motivation for doing this in ["ORMless; a Memento-like pattern for object persistence"](https://matthiasnoback.nl/2018/03/ormless-a-memento-like-pattern-for-object-persistence).

You can find some examples of how to use this library in [test/TalisOrm/AggregateRepositoryTest/](test/TalisOrm/AggregateRepositoryTest/).
