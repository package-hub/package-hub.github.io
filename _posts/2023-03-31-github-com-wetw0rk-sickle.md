---
title: Sickle
categories: ['python']
---
## [Sickle](https://github.com/wetw0rk/Sickle)

### Payload development tool


Sickle is a payload development tool originally created to aid me in crafting shellcode, however it can be used in crafting payloads for other exploit types as well (non-binary). Although the current modules are mostly aimed towards assembly this tool is not limited to shellcode.

Sickle can aid in the following:
- Identifying instructions resulting in bad characters when crafting shellcode
- Formatting output in various languages (python, perl, javascript, etc).
- Accepting bytecode via STDIN and formatting it.
- Executing shellcode in both Windows and Linux environments.
- Diffing for two binaries (hexdump, raw, asm, byte)
- Dissembling shellcode into assembly language (ARM, x86, etc).
- Shellcode extraction from raw bins (nasm sc.asm -o sc)
