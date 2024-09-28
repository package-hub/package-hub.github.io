---
title: ast
categories: ['java', 'kotlin', 'ast']
---
## [ast](https://github.com/kotlinx/ast)

### Generic AST parsing library for kotlin multiplatform


`kotlinx.ast` is a generic AST (Abstract Syntax Tree) parsing library, Kotlin is currently the only supported language.
The library is designed that other languages can be easily added.
`kotlinx.ast` does not use the Kotlin Compiler for parsing,
it is using ANTLR (the Kotlin variant: https://github.com/Strumenta/antlr-kotlin)
using the official Kotlin Grammar (https://kotlinlang.org/docs/reference/grammar.html).

One Component is [Klass](common/src/commonMain/kotlin/kotlinx/ast/common/klass),
a collection of language independent data classes
used to represent and easily access the AST.
