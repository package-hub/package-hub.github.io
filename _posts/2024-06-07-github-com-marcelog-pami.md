---
title: PAMI
categories: ['php', 'asterisk', 'ami']
---
## [PAMI](https://github.com/marcelog/PAMI)

### PHP Asterisk Manager Interface ( AMI ) supports synchronous command ( action )/ responses and asynchronous events using the pattern observer-listener. Supports commands with responses with multiple events. Very suitable for development of operator consoles and / or asterisk / channels / peers monitoring through SOA, etc


PAMI means PHP Asterisk Manager Interface. As its name suggests its just a
set of php classes that will let you issue commands to an ami and/or receive
events, using an observer-listener pattern.

The idea behind this, is to easily implement operator consoles, monitors, etc.
either via SOA or ajax.

A port for nodejs is available at: http://marcelog.github.com/Nami
A port for erlang is available at: https://github.com/marcelog/erlami
