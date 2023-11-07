---
title: graalpython
categories: ['python']
---
## [graalpython](https://github.com/oracle/graalpython)

### A Python 3 implementation built on GraalVM


GraalPy is an implementation of the Python language on top of GraalVM.
A primary goal is to support PyTorch, SciPy, and their constituent libraries, as well as to work with other data science and machine learning libraries from the rich Python ecosystem.
GraalPy can usually execute pure Python code faster than CPython, and nearly match CPython performance when C extensions are involved.
GraalPy currently aims to be compatible with Python 3.10.
While many workloads run fine, any Python program that uses external packages could hit something unsupported.
At this point, the Python implementation is made available for experimentation and curious end-users.
We welcome issue reports of all kinds and are working hard to close our compatibility gaps.
