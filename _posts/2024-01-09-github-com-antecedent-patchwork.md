---
title: patchwork
categories: ['php']
---
## [patchwork](https://github.com/antecedent/patchwork)

### Method redefinition (monkey-patching) functionality for PHP.


Patchwork implements the redefinition ([monkey-patching](https://en.wikipedia.org/wiki/Monkey_patch)) of functions and methods in PHP. This includes both user-defined and internal callables, which can be functions, class methods, or instance methods. In addition, [many](https://github.com/antecedent/patchwork/blob/master/src/Redefinitions/LanguageConstructs.php) function-like constructs, such as `exit` or `include`, are supported in an analogous way.

Internally, Patchwork uses a [stream wrapper](http://php.net/manual/en/class.streamwrapper.php) on `file://`. In the case of user-defined functions and methods, it is used to inject a simple interceptor snippet to the beginning of every such callable. For the remaining types of callables, various other strategies are applied.
