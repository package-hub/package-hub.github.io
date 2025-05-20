---
title: valet-linux-plus
categories: ['php', 'valet', 'linux']
---
## [valet-linux-plus](https://github.com/valet-linux-plus/valet-linux-plus)

### Advanced local development experience for Linux.


Valet *Linux+* is an advanced development environment for Linux minimalists. No Vagrant, no `/etc/hosts` file. You can even share your sites publicly using local tunnels. _Yeah, we like it too._

Valet *Linux+* configures your system to always run Nginx in the background when your machine starts. Then, using [DnsMasq](https://en.wikipedia.org/wiki/Dnsmasq), Valet proxies all requests on the `*.test` domain to point to sites installed on your local machine.

In other words, a blazing fast PHP development environment that uses roughly 7mb of RAM. Valet *Linux+* isn't a complete replacement for Vagrant or Homestead, but provides a great alternative if you want flexible basics, prefer extreme speed, or are working on a machine with a limited amount of RAM.
