---
title: openDCIM
categories: ['php']
---
## [openDCIM](https://github.com/opendcim/openDCIM)

### An open source (GPL v3) Data Center Inventory Management (DCIM) application.

[Official Website](http://www.opendcim.org/participation.html)

Installation
------------
Supposing you are using apache, php and apache-php-module firstly clone openDCIM in a directory which is accessible by apache user (e.g. /srv/http/) and then configure apache to load required modules and have access to project directory (you can define virtual host too).

If you're gonna create Dockerized development environment, you should enable apache's fast-cgi to connect to php-fpm's container
