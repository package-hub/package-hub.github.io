---
title: enum4linux-ng
categories: ['python', 'enum4linux', 'security']
---
## [enum4linux-ng](https://github.com/cddmp/enum4linux-ng)

### A next generation version of enum4linux (a Windows/Samba enumeration tool) with additional features like JSON/YAML export. Aimed for security professionals and CTF players.

- support for YAML and JSON export
- colored console output (can be disabled via [NO_COLOR](https://no-color.org/))
- ldapsearch und polenum are natively implemented
- support for multiple authentication methods
- support for legacy SMBv1 connections
- auto detection of IPC signing support
- 'smart' enumeration will automatically disable tests which would otherwise fail
- timeout support
- SMB dialect checks
- IPv6 support (experimental)
