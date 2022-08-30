---
title: parallelshell
categories: ['javascript']
---
## [parallelshell](https://github.com/darkguy2008/parallelshell)

### Run multiple shell commands in parallel


This is a super simple npm module to run shell commands in parallel. All
processes will share the same stdout/stderr, and if any command exits with a
non-zero exit status, the rest are stopped and the exit code carries through.
