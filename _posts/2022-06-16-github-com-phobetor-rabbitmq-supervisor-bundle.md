---
title: rabbitmq-supervisor-bundle
categories: ['php', 'symfony', 'rabbitmq']
---
## [rabbitmq-supervisor-bundle](https://github.com/Phobetor/rabbitmq-supervisor-bundle)

### Symfony bundle to automatically create and update supervisor configurations for RabbitMQ consumer daemons


If you use `php-amqplib/rabbitmq-bundle` to handle the communication with RabbitMQ, just install [supervisor](http://supervisord.org/), add this bundle and run
```sh
$ app/console rabbitmq-supervisor:rebuild
```
to get a running `supervisord` instance that automatically manages all your consumer daemons.
When your worker configuration or your code changes, run the command again and all the daemons will be updated.
