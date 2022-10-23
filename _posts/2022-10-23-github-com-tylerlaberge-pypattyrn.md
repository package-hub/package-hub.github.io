---
title: PyPattyrn
categories: ['python', 'design-patterns', 'library']
---
## [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn)

### A simple library for implementing common design patterns.


```python
from pypattyrn.creational.singleton import Singleton

class DummyClass(object, metaclass=Singleton):  #  DummyClass is now a Singleton!
    ...
```

PyPattyrn is a python package aiming to make it easier and faster to implement design patterns into your own projects.

Design patterns by nature cannot be directly translated into code as they are just a description of how to solve a particular problem. However, many of the common design patterns have boilerplate code that is common throughout all implementations of the pattern. This package captures that common code and makes it easy to use so that you dont have to write it yourself in all your projects.
___
