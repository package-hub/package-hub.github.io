---
title: partyline
categories: ['php', 'laravel', 'laravel-5-package']
---
## [partyline](https://github.com/wilderborn/partyline)

### Output to Laravel's console from outside of your Command classes.


This package allows you to output to the console from outside of command class.

For example, you might have a feature that does the same thing from a command and through the web.
Until now, you may have found yourself duplicating code just to be able to output to the console in various places.

With Partyline, you can use output commands within your logic. If it's being run inside the console, you'll see it. Otherwise, nothing will happen.
