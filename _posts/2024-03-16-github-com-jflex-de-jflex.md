---
title: jflex
categories: ['java', 'scanner', 'lexical-analyzer']
---
## [jflex](https://github.com/jflex-de/jflex)

### The fast scanner generator for Java™ with full Unicode support


[JFlex][jflex] is a lexical analyzer generator (also known as scanner generator) for Java.

JFlex takes as input a specification with a set of regular expressions and corresponding actions.
It generates Java source of a lexer that reads input, matches the input against the regular
expressions in the spec file, and runs the corresponding action if a regular expression
matched. Lexers usually are the first front-end step in compilers, matching keywords, comments,
operators, etc, and generating an input token stream for parsers.

JFlex lexers are based on deterministic finite automata (DFAs).
They are fast, without expensive backtracking.

