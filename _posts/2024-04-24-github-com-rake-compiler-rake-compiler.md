---
title: rake-compiler
categories: ['ruby']
---
## [rake-compiler](https://github.com/rake-compiler/rake-compiler)

### Provide a standard and simplified way to build and package Ruby C and Java extensions using Rake as glue.


rake-compiler is first and foremost a productivity tool for Ruby developers.
Its goal is to make the busy developer's life easier by simplifying the building
and packaging of Ruby extensions by simplifying code and reducing duplication.

It follows **convention over configuration** by advocating a standardized build and
package structure for both C and Java based RubyGems.

rake-compiler is the result of many hard-won experiences dealing with several
diverse RubyGems that provided native extensions for different platforms and
different user configurations in different ways. Details such as differences in
code portability, differences in code clarity, and differences in project directory
structure often made it very difficult for newcomers to those RubyGems.

From these challenges, rake-compiler was born with the single-minded goal of
making the busy RubyGem developer's life much less difficult.
