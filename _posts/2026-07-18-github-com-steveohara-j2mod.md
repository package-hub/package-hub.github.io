---
title: j2mod
categories: ['java', 'modbus', 'modbus-tcp']
---
## [j2mod](https://github.com/steveohara/j2mod)

### Enhanced Modbus library implemented in the Java programming language

This project is a fork of the [j2mod](https://sourceforge.net/projects/j2mod/) library which began life as [jamod](http://jamod.sourceforge.net/). 
A huge amount of refactoring and code fixing has been carried out on this library, with the addition of supporting JUnit tests, to ensure the library is fit for production use.

This implementation supports Modbus TCP, UDP, RTU over TCP, Serial RTU and Serial ASCII in both Master and Slave configurations.
The serial comms is implemented using [jSerialComm](http://fazecast.github.io/jSerialComm/) and does not require any outside dependencies over and above the logging facade [slf4j](https://www.slf4j.org/).

For instructions on how to use the library, visit the wiki [here](https://github.com/steveohara/j2mod/wiki) 
