---
title: twitter-cldr-js
categories: ['javascript']
---
## [twitter-cldr-js](https://github.com/twitter/twitter-cldr-js)

### JavaScript implementation of the ICU (International Components for Unicode) that uses the Common Locale Data Repository to format dates, plurals, and more.  Based on twitter-cldr-rb.


TwitterCldr uses Unicode's Common Locale Data Repository (CLDR) to format certain types of text into their
localized equivalents via the Rails asset pipeline.  It is a port of [twitter-cldr-rb](http://github.com/twitter/twitter-cldr-rb), a Ruby gem that uses the same CLDR data.  Originally, this project was not a gem, but a collection of JavaScript files.  It has been turned into a gem to move the JavaScript compiling routines from twitter-cldr-rb and provide support for the asset pipeline.

Currently, twitter-cldr-js supports the following:

1. Date and time formatting
2. Relative date and time formatting (eg. 1 month ago)
3. Number formatting (decimal, currency, and percentage)
4. Long/short decimals
5. Plural rules
6. Bidirectional reordering
7. Text Segmentation
