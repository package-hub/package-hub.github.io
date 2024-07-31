---
title: php-reverse-shell
categories: ['php', 'reverse-tcp', 'reverse-shell']
---
## [php-reverse-shell](https://github.com/ivan-sincek/php-reverse-shell)

### PHP shells that work on Linux OS, macOS, and Windows OS.


Just a little refresh on the popular PHP reverse shell script [pentestmonkey/php-reverse-shell](https://github.com/pentestmonkey/php-reverse-shell). Credits to the original author!

Works on Linux OS and macOS with `/bin/sh` and Windows OS with `cmd.exe`. Script will automatically detect the underlying OS.

Works with both, `ncat` and `multi/handler`.

Tested on XAMPP for Linux v7.3.19 (64-bit) with PHP v7.3.19 on Kali Linux v2020.2 (64-bit).

Tested on XAMPP for OS X v7.4.10 (64-bit) with PHP v7.4.10 on macOS Catalina v10.15.6 (64-bit).

Tested on XAMPP for Windows v7.4.3 (64-bit) with PHP v7.4.3 on Windows 10 Enterprise OS (64-bit).

In addition, everything was tested on Docker images [nouphet/docker-php4](https://hub.docker.com/r/nouphet/docker-php4) with PHP v4.4.0 and [steeze/php52-nginx](https://hub.docker.com/r/steeze/php52-nginx) with PHP v5.2.17.

Made for educational purposes. I hope it will help!

**Process pipes on Windows OS do not support asynchronous operations so `stream_set_blocking()`, `stream_select()`, and `feof()` will not work properly, but I found a workaround.**
