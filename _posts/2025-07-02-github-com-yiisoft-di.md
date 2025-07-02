---
title: di
categories: ['php', 'di', 'container']
---
## [di](https://github.com/yiisoft/di)

### PSR-11 compatible DI container and injector


- [PSR-11](https://www.php-fig.org/psr/psr-11/) compatible.
- Supports property injection, constructor injection, and method injection.
- Detects circular references.
- Accepts array definitions. You can use it with mergeable configs.
- Provides optional autoload fallback for classes without explicit definition.
- Allows delegated lookup and has a composite container.
- Supports aliasing.
- Supports service providers.
- Has state resetter for long-running workers serving many requests, such as [RoadRunner](https://roadrunner.dev/)
  or [Swoole](https://www.swoole.co.uk/).
- Supports container delegates.
- Does auto-wiring.
