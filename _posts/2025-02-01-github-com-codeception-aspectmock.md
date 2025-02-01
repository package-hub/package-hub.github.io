---
title: AspectMock
categories: ['php']
---
## [AspectMock](https://github.com/Codeception/AspectMock)

### The most powerful and flexible mocking framework for PHPUnit / Codeception.


PHP is a language that was not designed to be testable. Really. 
How would you fake the `time()` function to produce the same result for each test call?
Is there any way to stub a static method of a class? Can you redefine a class method at runtime?
Dynamic languages like Ruby or JavaScript allow us to do this. 
These features are essential for testing. AspectMock to the rescue!

Thousands of lines of untested code are written everyday in PHP.
In most cases, this code is not actually bad, 
but PHP does not provide capabilities to test it. You may suggest rewriting it from scratch following test driven design practices and use dependency injection wherever possible. Should this be done for stable working code? Well, there are much better ways to waste time.

With AspectMock you can unit-test practically any OOP code. PHP powered with AOP incorporates features of dynamic languages we have long been missing. There is no excuse for not testing your code.
You do not have to rewrite it from scratch to make it testable. Just install AspectMock with PHPUnit or Codeception and try to write some tests. It's really, really simple!

