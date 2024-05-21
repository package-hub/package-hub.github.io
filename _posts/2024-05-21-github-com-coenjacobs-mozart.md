---
title: mozart
categories: ['php', 'composer', 'autoloader']
---
## [mozart](https://github.com/coenjacobs/mozart)

### Developers tool for WordPress plugins: Wraps all your projects dependencies in your own namespace, in order to prevent conflicts with other plugins loading the same dependencies in different versions.

Composes all dependencies as a package inside a WordPress plugin. Load packages through Composer and have them wrapped inside your own namespace. Gone are the days when plugins could load conflicting versions of the same package, resulting in hard to reproduce bugs.

This package requires PHP 7.3 or higher in order to run the tool. You can use the resulting files as a bundle, requiring any PHP version you like, even PHP 5.2.

**Warning:** This package is very experimental and breaking changes are very likely until version 1.0.0 is tagged. Use with caution, always wear a helmet when using this in production environments.
