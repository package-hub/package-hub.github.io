---
title: definitions
categories: ['ruby']
---
## [definitions](https://github.com/holidays/definitions)

### Holiday definition files. You deserve a holiday!


This repository contains the 'raw' definitions for the various holidays projects. It should be added a submodule to
any project that wants to use them.

Currently it is only used by the [existing Holidays gem](https://github.com/holidays/holidays), which takes these
definitions and generates ruby classes for use in that gem. In the future it will be used by other languages in
a similar manner.

**Please note** that this is _not_ a gem. The validation process is written in ruby simply for convenience. The real
stars of this show are the YAML files.
