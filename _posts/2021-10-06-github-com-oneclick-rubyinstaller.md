---
title: rubyinstaller
categories: ['ruby']
---
## [rubyinstaller](https://github.com/oneclick/rubyinstaller)

### RubyInstaller for Windows - Build recipes


This project, licensed under the 3-clause Modified BSD License, attempts to
generate a development sandbox that can be used to compile Ruby and it's
components using the freely available MinGW toolchain. Our goal is to offer a
simplified way to boost your productivity when building Ruby from source code
on your Windows system, and ease the path for anyone wishing to contribute to
the RubyInstaller for Windows project.

This project is a work-in-progress collection of Rake build recipes that download
and verify the MinGW utilities required to compile and build a Ruby interpreter
and it's core components and dependencies.

The recipes also build a DevKit package that, when combined with a RubyInstaller
installation, enables Windows users to easily build and use many of the native
C-based RubyGems extensions that may not yet have a binary RubyGem. The DevKit
(available as a Windows Installer and normal 7-Zip and self-extracting archives)
provides an easy-to-install compiler and build system, and convenient setup helper
scripts.
