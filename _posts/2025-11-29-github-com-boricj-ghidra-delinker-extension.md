---
title: ghidra-delinker-extension
categories: ['java', 'ghidra', 'ghidra-extension']
---
## [ghidra-delinker-extension](https://github.com/boricj/ghidra-delinker-extension)

### Ghidra extension for exporting relocatable object files


This Ghidra extension enables exporting parts of a program as object files. These object files have valid metadata (symbols, relocation tables…) and as such can be reused directly by a toolchain for further processing.

Use-cases include:

 * [Advanced binary patching](https://boricj.net/tenchu1/2024/05/31/part-11.html), by leveraging the linker to mend both original and modified parts together instead of doing this work by hand ;
 * [Software ports](https://boricj.net/atari-jaguar-sdk/2024/01/02/part-5.html), by isolating system-independent code from a program and replacing the rest ;
 * Converting [programs](https://boricj.net/atari-jaguar-sdk/2023/12/18/part-3.html) or object files from one file format to another ;
 * [Creating](https://boricj.net/tenchu1/2024/03/11/part-5.html) [libraries](https://boricj.net/tenchu1/2024/03/18/part-6.html), by extracting parts of a program and reusing them in another context ;
 * Decompilation projects, by splitting a program into multiple object files and reimplementing these _Ship of Theseus_-style ;
 * …

Matrix of supported instruction set architectures and object files:

|               | x86  | MIPS |
| ------------- | ---- | ---- |
| COFF          | ✅ | ❌ |
| ELF           | ✅ | ✅ |
