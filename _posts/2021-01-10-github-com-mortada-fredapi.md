---
title: fredapi
categories: ['python', 'fred', 'finance']
---
## [fredapi](https://github.com/mortada/fredapi)

### Python API for FRED (Federal Reserve Economic Data) and ALFRED (Archival FRED)


`fredapi` is a Python API for the [FRED](http://research.stlouisfed.org/fred2/) data provided by the
Federal Reserve Bank of St. Louis. `fredapi` provides a wrapper in python to the 
[FRED web service](http://api.stlouisfed.org/docs/fred/), and also provides several convenient methods
for parsing and analyzing point-in-time data (i.e. historic data revisions) from [ALFRED](http://research.stlouisfed.org/tips/alfred/)

`fredapi` makes use of `pandas` and returns data to you in a `pandas` `Series` or `DataFrame`
