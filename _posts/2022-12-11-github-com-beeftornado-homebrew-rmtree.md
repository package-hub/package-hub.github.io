---
title: homebrew-rmtree
categories: ['ruby']
---
## [homebrew-rmtree](https://github.com/beeftornado/homebrew-rmtree)

### Remove a formula and its unused dependencies


It's an [external command][ec] for [Homebrew][h] that provides a new command, `rmtree`,
that will uninstall that formula, and uninstall any of its dependencies
that have no formula left installed that depend on them. The command will check all dependencies
recursively starting at the one specified on the command line.

This is tricky business. So this command comes with a warning.

[ec]: https://github.com/mxcl/homebrew/wiki/External-Commands
[h]: https://github.com/mxcl/homebrew
