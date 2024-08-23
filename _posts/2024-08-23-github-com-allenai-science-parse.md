---
title: science-parse
categories: ['java']
---
## [science-parse](https://github.com/allenai/science-parse)

### Science Parse parses scientific papers (in PDF form) and returns them in structured form.


Science Parse parses scientific papers (in PDF form) and returns them in structured form. As of today, it supports these fields:
 * Title
 * Authors
 * Abstract
 * Sections (each with heading and body text)
 * Bibliography, each with
   * Title
   * Authors
   * Venue
   * Year
 * Mentions, i.e., places in the paper where bibliography entries are mentioned

In JSON format, the [output looks like this](http://scienceparse.allenai.org/v1/498bb0efad6ec15dd09d941fb309aa18d6df9f5f) (or like [this, if you want sections](http://scienceparse.allenai.org/v1/498bb0efad6ec15dd09d941fb309aa18d6df9f5f?skipFields=sections)). The easiest way to get started is to use the output from this server.
