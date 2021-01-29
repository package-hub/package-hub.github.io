---
title: Crunch
categories: ['python', 'png', 'png-compression']
---
## [Crunch](https://github.com/chrissimpkins/Crunch)

### Insane(ly slow but wicked good) PNG image optimization


Crunch is a tool for lossy PNG image file optimization.  It combines selective bit depth, color type, and color palette reduction with zopfli DEFLATE compression algorithm encoding using the pngquant and zopflipng PNG optimization tools.  This approach leads to a significant file size gain relative to lossless approaches at the expense of a relatively modest decrease in image quality (see [example images](#examples) below).

Continuous benchmark testing is available on [Travis CI](https://travis-ci.com/chrissimpkins/Crunch) (open the Benchmarks build for the commit of interest). Please see the benchmarks directory of this repository for details about the benchmarking approach and instructions on how to execute benchmarks locally on the reference images distributed in this repository or with your own image files.

Crunch PNG image optimization is available through the following applications that are distributed in this repository:

- [`crunch`](docs/EXECUTABLE.md) - a *nix command line executable that can be used on macOS, Linux, and Windows POSIX application deployment environments such as Cygwin or the Windows subsystem for Linux
- [Crunch GUI](docs/MACOSGUI.md) - a native macOS drag and drop GUI tool
- [Crunch Image(s)](docs/SERVICE.md) service - a macOS right-click menu service for PNG images selected in the Finder
