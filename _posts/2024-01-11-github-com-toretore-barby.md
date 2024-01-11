---
title: barby
categories: ['ruby']
---
## [barby](https://github.com/toretore/barby)

### The Ruby barcode generator

Barby is a Ruby library that generates barcodes in a variety of symbologies.

Its functionality is split into _barcode_ and "_outputter_" objects:
  * [`Barby::Barcode` objects] [symbologies] turn data into a binary representation for a given symbology.
  * [`Barby::Outputter`] [outputters] then takes this representation and turns it into images, PDF, etc.

You can easily add a symbology without having to worry about graphical
representation. If it can be represented as the usual 1D or 2D matrix of
lines or squares, outputters will do that for you.

Likewise, you can easily add an outputter for a format that doesn't have one
yet, and it will work with all existing symbologies.

For more information, check out [the Barby wiki][wiki].

