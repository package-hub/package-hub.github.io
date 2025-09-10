---
title: MutabilityDetector
categories: ['java']
---
## [MutabilityDetector](https://github.com/MutabilityDetector/MutabilityDetector)

### Lightweight analysis tool for detecting mutability in Java classes

Mutability Detector is designed to analyse Java classes and report on whether instances of a given class are immutable. It can be used:

  * In a unit test, with an assertion like `assertImmutable(MyClass.class)`. Is your class actually immutable? What about after that change you just made?
  * As a FindBugs plugin. Those classes you annotated with `@Immutable`, are they actually?
  * At runtime. Does your API require being given immutable objects?
  * From the command line. Do you want to quickly run Mutability Detector over an entire code base?
  
  
  
  