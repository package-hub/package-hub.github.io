---
title: re2j
categories: ['java', 'regular-expressions']
---
## [re2j](https://github.com/google/re2j)

### linear time regular expression matching in Java


If you use regular expression patterns with a high degree of alternation, your
code may run faster with RE2/J. In the worst case, the `java.util.regex`
matcher may run forever, or exceed the available stack space and fail; this
will never happen with RE2/J.
