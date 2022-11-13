---
title: plantuml-parser
categories: ['typescript', 'parser', 'plantuml']
---
## [plantuml-parser](https://github.com/Enteee/plantuml-parser)

### Parse PlantUML with JavaScript or TypeScript

_Parse PlantUML with JavaScript or TypeScript_

The aim of this project is to provide a feature-complete, well tested and
maintainable [Parsing Expression Grammar (PEG)](src/plantuml.pegjs)
for the [PlantUML](http://plantuml.com/) syntax. The parser is designed
to be used as [JavaScript library](#usage) or from the [Command Line](#command-line-interface).

**Important**: The parser is not yet feature-complete. But we focus on writing a
robust implementation which can parse parts of diagrams without knowing the full
syntax. This means that the parser probably still parses just about enough to get
you started. If not, please [contribute :heart:](#contribute-heart).
