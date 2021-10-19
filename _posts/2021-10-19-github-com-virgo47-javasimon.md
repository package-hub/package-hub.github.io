---
title: javasimon
categories: ['java']
---
## [javasimon](https://github.com/virgo47/javasimon)

### Java Simon is a simple monitoring API that allows you to follow and better understand your application.


Easiest way to start with Java Simon is to [add Maven dependencies into your Maven project](docs/Maven.md).

A monitors in Java Simon is called "Simon". There are two types of Simons available: `Counter` and `Stopwatch`.
Counter tracks single long value, its maximum and minimum. Stopwatch measures time and tracks
number of measurements (splits), total time, split minimum and maximum, etc.
