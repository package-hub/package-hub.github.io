---
title: bnd
categories: ['java', 'bnd', 'bndtools']
---
## [bnd](https://github.com/bndtools/bnd)

### Bnd/Bndtools.  Tooling to build OSGi bundles including Eclipse, Maven, and Gradle plugins.


Bnd/Bndtools is a swiss army knife for OSGi. It creates manifest headers for you based on analyzing the class code, it verifies your settings, it manages project dependencies, diffs jars, and much more. At the core is a library with all the functions. The library is then used in a myriad of subsystems to provide the core functionality to the rest of the world.

* [bndlib and friends](https://bnd.bndtools.org) – The core library plus repository, resolve, etc.
* [maven plugins](maven-plugins/README.md) – A full set of maven plugins that make bnd useful for maven users
* [eclipse](https://bndtools.org) – Bndtools is the plugin for Eclipse that provides full GUI support for bnd. This is a p2 repository.
* [bnd](biz.aQute.bnd) – a command line utility with a hodgepodge of sometimes extremely useful functions. Can even be used instead of a build tool. is available through [Homebrew formula](https://formulae.brew.sh/formula/bnd).
* [gradle plugin(s)](gradle-plugins/README.md) – A bnd workspace plugin that builds identical to Eclipse's bndtool as well as a gradle plugin that provides bnd support for non-workspace projects
* ant – well ...
