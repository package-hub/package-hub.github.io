---
title: danbooru
categories: ['ruby', 'rails', 'booru']
---
## [danbooru](https://github.com/danbooru/danbooru)

### A taggable image board written in Rails 6.


It is recommended that you install Danbooru on a Debian-based system
since most of the required packages are available on APT. Danbooru
has been successfully installed on Fedora, CentOS, FreeBSD, and OS X.
The INSTALL.debian install script is straightforward and should be
simple to adapt for other platforms.

For best performance, you will need at least 256MB of RAM for
PostgreSQL and Rails. The memory requirement will grow as your
database gets bigger. 

On production Danbooru uses PostgreSQL 9.4, but any 9.x release should
work.

Use your operating system's package management system whenever
possible.  This will simplify the process of installing init scripts,
which will not always happen when compiling from source.
