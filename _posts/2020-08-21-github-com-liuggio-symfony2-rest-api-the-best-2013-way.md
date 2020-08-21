---
title: symfony2-rest-api-the-best-2013-way
categories: ['php']
---
## [symfony2-rest-api-the-best-2013-way](https://github.com/liuggio/symfony2-rest-api-the-best-2013-way)

### Code for the article at:


As Symfony uses [Composer][1] to manage its dependencies, the recommended way
to create a new project is to use it.

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

    curl -s http://getcomposer.org/installer | php

Then, use the `create-project` command to generate a new Symfony application:

    php composer.phar create-project liuggio/symfony2-rest-api-the-best-2013-way -sdev
    cd blog-rest-symfony2

Composer will install Symfony and all its dependencies under the
`blog-rest-symfony2` directory.
