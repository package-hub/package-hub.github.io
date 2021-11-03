---
title: reflectasm
categories: ['java']
---
## [reflectasm](https://github.com/EsotericSoftware/reflectasm)

### High performance Java reflection


ReflectASM is a very small Java library that provides high performance reflection by using code generation. An access class is generated to set/get fields, call methods, or create a new instance. The access class uses bytecode rather than Java's reflection, so it is much faster. It can also access primitive fields via bytecode to avoid boxing.
