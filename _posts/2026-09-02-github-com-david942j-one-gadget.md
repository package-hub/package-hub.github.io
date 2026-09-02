---
title: one_gadget
categories: ['ruby', 'ctf', 'pwnable']
---
## [one_gadget](https://github.com/david942j/one_gadget)

### The best tool for finding one gadget RCE in libc.so.6


When solving CTF pwn challenges we usually want a one-gadget RCE: a single address in
libc that, jumped to, calls `execve("/bin/sh", NULL, NULL)`.

This gem finds them for you, so you don't have to dig through objdump or IDA Pro every
time :wink:

Point it at a libc -- `one_gadget /path/to/libc` -- and enjoy the magic :laughing:
