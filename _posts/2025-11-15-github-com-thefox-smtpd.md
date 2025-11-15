---
title: smtpd
categories: ['php', 'smtp-server', 'smtp-library']
---
## [smtpd](https://github.com/TheFox/smtpd)

### SMTP server (library) for receiving emails, written in pure PHP.


SMTP server (library) for receiving emails, written in pure PHP. This library provides an interface to the SMTP server-side protocol with PHP. It creates a `\Zend\Mail\Message` Class object for every incoming email and hands this object to a custom PHP function for further processing. The project is in Beta status, so it's not recommended for production use.

The `d` in `SMTPd` stands for [Daemon](https://en.wikipedia.org/wiki/Daemon_(computing)). This script can run in background like any other daemon process. It's not meant for running as a webapplication.
