---
title: pyanalyze
categories: ['python']
---
## [pyanalyze](https://github.com/quora/pyanalyze)

### A static analysis tool for Python


Pyanalyze is a tool for programmatically detecting common mistakes in Python code, such as references to undefined variables and type errors.
It can be extended to add additional rules and perform checks specific to particular functions.

Some use cases for this tool include:

- **Catching bugs before they reach production**. The script will catch accidental mistakes like writing "`collections.defalutdict`" instead of "`collections.defaultdict`", so that they won't cause errors in production. Other categories of bugs it can find include variables that may be undefined at runtime, duplicate keys in dict literals, and missing `await` keywords.
- **Making refactoring easier**. When you make a change like removing an object attribute or moving a class from one file to another, pyanalyze will often be able to flag code that you forgot to change.
- **Finding dead code**. It has an option for finding Python objects (functions and classes) that are not used anywhere in the codebase.
- **Checking type annotations**. Type annotations are useful as documentation for readers of code, but only when they are actually correct. Although pyanalyze does not support the full Python type system (see [below](#type-system) for details), it can often detect incorrect type annotations.
