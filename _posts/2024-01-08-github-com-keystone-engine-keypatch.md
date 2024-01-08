---
title: keypatch
categories: ['python', 'ida-pro', 'assembler']
---
## [keypatch](https://github.com/keystone-engine/keypatch)

### Multi-architecture assembler for IDA Pro. Powered by Keystone Engine.


Sometimes we want to patch the binary while analyzing it in IDA, but unfortunately the built-in asssembler of IDA Pro is not adequate.

- This tool is not friendly and without many options that would make the life of reverser easier.
- Only X86 assembler is available. Support for all other architectures is totally missing.
- The X86 assembler is not in a good shape, either: it cannot understand many modern Intel instructions.

Keypatch was developed to solve this problem. Thanks to the power of [Keystone](http://keystone-engine.org), our plugin offers some nice features.

- Cross-architecture: support Arm, Arm64 (AArch64/Armv8), Hexagon, Mips, PowerPC, Sparc, SystemZ & X86 (include 16/32/64bit).
- Cross-platform: work everywhere that IDA works, which is on Windows, MacOS, Linux.
- Based on Python, so it is easy to install as no compilation is needed.
- User-friendly: automatically add comments to patched code, and allow reverting (undo) modification.
- Open source under GPL v2.

Keypatch can be the missing piece in your toolset of reverse engineering.

--------------
