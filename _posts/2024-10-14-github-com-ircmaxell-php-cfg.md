---
title: php-cfg
categories: ['php']
---
## [php-cfg](https://github.com/ircmaxell/php-cfg)

### A Control Flow Graph implementation in PHP


Pure PHP implementation of a control flow graph (CFG) with instructions in static single assignment (SSA) form.

The used SSA construction algorithm is based on "Simple and Efficient Construction of Static Single Assignment Form" by
Braun et al. This algorithm constructs SSA form directly from the abstract syntax tree, without going through a non-SSA
IR first. If you're looking for dominance frontiers, you won't find them here...

The constructed SSA form is minimal and pure (or is supposed to be).
