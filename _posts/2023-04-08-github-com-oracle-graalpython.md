---
title: graalpython
categories: ['python']
---
## [graalpython](https://github.com/oracle/graalpython)

### A Python 3 implementation built on GraalVM


This is GraalPy, an implementation of the Python language.
A primary goal is to support SciPy and its constituent libraries.
GraalPy can usually execute pure Python code faster than CPython (but not when C extensions are involved).
GraalPy currently aims to be compatible with Python 3.10, but it is some way from there.
While your specific workload may function, any Python program that uses external packages could hit something unsupported.
At this point, the Python implementation is made available for experimentation and curious end-users.
