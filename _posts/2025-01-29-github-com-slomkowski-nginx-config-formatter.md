---
title: nginx-config-formatter
categories: ['python', 'nginx', 'formatter']
---
## [nginx-config-formatter](https://github.com/slomkowski/nginx-config-formatter)

### nginx config file formatter/beautifier written in Python with no additional dependencies.


*nginx* config file formatter/beautifier written in Python with no additional dependencies. It can be used as library or standalone script. It formats *nginx* configuration files in consistent way, described below:

* All lines are indented in uniform manner, with 4 spaces per level. Number of spaces is customizable.
* Neighbouring empty lines are collapsed to at most two empty lines.
* Curly braces placement follows Java convention.
* Whitespaces are collapsed, except in comments and quotation marks.

