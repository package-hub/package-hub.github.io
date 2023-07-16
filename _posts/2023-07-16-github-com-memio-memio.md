---
title: memio
categories: ['php']
---
## [memio](https://github.com/memio/memio)

### [main] A highly opinionated PHP code generator library


Memio is a library, it allows you to describe PHP code by building "Model" classes
(e.g. `new Method('__construct')`) and then to generate it using a `PrettyPrinter`!

> **Note**: The actual generation logic is held in [Twig templates](http://twig.sensiolabs.org/).
> If the coding style provided doesn't appeal to you, you can overwrite those templates easily.
