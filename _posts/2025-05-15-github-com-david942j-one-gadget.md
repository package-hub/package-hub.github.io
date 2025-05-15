---
title: one_gadget
categories: ['ruby', 'ctf', 'pwnable']
---
## [one_gadget](https://github.com/david942j/one_gadget)

### The best tool for finding one gadget RCE in libc.so.6


When playing ctf pwn challenges we usually need the one-gadget RCE (remote code execution),
which leads to call `execve('/bin/sh', NULL, NULL)`.

This gem provides such gadgets finder, no need to use objdump or IDA-pro every time like a fool :wink:

To use this tool, type `one_gadget /path/to/libc` in command line and enjoy the magic :laughing:
