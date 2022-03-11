---
title: Stikked
categories: ['javascript']
---
## [Stikked](https://github.com/claudehohl/Stikked)

### An advanced and beautiful pastebin written in PHP


* Rewritten the Docker setup to be simple and clean:
  * switch to nginx-alpine, php-fpm-alpine and mariadb
  * docker-compose: autobuild php-image for stikked
  * serve all files directly (htdocs is mounted instead of copied)
  * stikked-configuration for docker resides in docker/stikked.php
* force private-flag when a previously encrypted paste gets pasted public
* Fixed a critical bug that allowed pasting despite captcha
* Various bugfixes and improvements
