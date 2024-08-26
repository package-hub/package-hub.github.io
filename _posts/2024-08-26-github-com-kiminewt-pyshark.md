---
title: pyshark
categories: ['python', 'tshark', 'packet-capture']
---
## [pyshark](https://github.com/KimiNewt/pyshark)

### Python wrapper for tshark, allowing python packet parsing using wireshark dissectors


Python wrapper for tshark, allowing python packet parsing using wireshark dissectors.

Extended documentation: http://kiminewt.github.io/pyshark

**Looking for contributors** - for various reasons I have a hard time finding time to maintain and enhance the package at the moment. Any pull-requests will be reviewed and if any one is interested and is suitable, I will be happy to include them in the project. Feel free to mail me at dorgreen1 at gmail.

There are quite a few python packet parsing modules, this one is different because it doesn't actually parse any packets, it simply uses tshark's (wireshark command-line utility) ability to export XMLs to use its parsing.

This package allows parsing from a capture file or a live capture, using all wireshark dissectors you have installed.
Tested on windows/linux.
