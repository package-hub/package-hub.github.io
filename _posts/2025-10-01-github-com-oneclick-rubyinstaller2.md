---
title: rubyinstaller2
categories: ['ruby', 'msys2', 'rubyinstaller']
---
## [rubyinstaller2](https://github.com/oneclick/rubyinstaller2)

### MSYS2 based RubyInstaller for Windows


This project provides an Installer for Ruby-2.4 and newer on Windows based on the MSYS2 toolchain.
It is the successor to the MSYS1 based [RubyInstaller](https://github.com/oneclick/rubyinstaller/) which was used for Ruby-2.3 and older.
It is licensed under the 3-clause Modified BSD License.

In contrast to the old RubyInstaller it does not provide its own DevKit, but makes use of the rich set of [MINGW libraries](https://github.com/Alexpux/MINGW-packages) from the [MSYS2 project](https://msys2.github.io/).
It therefore integrates well into MSYS2 after installation on the target system to provide a build-and-runtime environment for installation of gems with C-extensions.
This and more changes are documented in the [CHANGELOG](https://github.com/oneclick/rubyinstaller2/blob/master/CHANGELOG-2.4.md#rubyinstaller-241-1---2017-05-25).
