---
title: doctrine-test-bundle
categories: ['php', 'symfony', 'symfony-bundle']
---
## [doctrine-test-bundle](https://github.com/dmaicher/doctrine-test-bundle)

### Symfony bundle to isolate your app's doctrine database tests and improve the test performance


This bundle provides features that help you run your Symfony-framework-based App's testsuite more efficiently with isolated tests.

It provides a `StaticDriver` that will wrap your originally configured `Driver` class (like `DBAL\Driver\PDOMysql\Driver`) and keeps a database connection statically in the current php process.

With the help of a PHPUnit extension class it will begin a transaction before every testcase and roll it back again after the test finished for all configured DBAL connections. This results in a performance boost as there is no need to rebuild the schema, import a backup SQL dump or re-insert fixtures before every testcase. As long as you avoid issuing DDL queries that might result in implicit transaction commits (Like `ALTER TABLE`, `DROP TABLE` etc; see https://wiki.postgresql.org/wiki/Transactional_DDL_in_PostgreSQL:_A_Competitive_Analysis) your tests will be isolated and all see the same database state.

It also includes a `Psr6StaticArrayCache` that will be automatically configured as meta data & query cache for all EntityManagers. This improved the speed and memory usage for my testsuites dramatically! This is especially beneficial if you have a lot of tests that boot kernels (like Controller tests or ContainerAware tests) and use Doctrine entities.
