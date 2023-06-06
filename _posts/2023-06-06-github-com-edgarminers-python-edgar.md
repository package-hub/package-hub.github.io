---
title: python-edgar
categories: ['python', 'edgar', '10k']
---
## [python-edgar](https://github.com/edgarminers/python-edgar)

### Download the SEC filings index from EDGAR since 1993


The SEC filings index is split in quarterly files since 1993 (1993-QTR1, 1993-QTR2...). By using `python-edgar` and some scripting, you can easily rebuild a master index of all filings since 1993 by stitching quarterly index files together. The master index file can be then feed to a database, a pandas dataframe, stata, etc... 

An index file is a csv-like (pipe `|` separated) file that contains the following information:
  - Company name (eg. ```TWITTER, INC```)
  - Company CIK (eg.``` 0001418091```)
  - Filling date (eg. ```2013-10-03```)
  - Filling type (eg. ```S1```)
  - Filling URL on EDGAR (```edgar/data/1418091/0001193125-13-390321.txt```)

Once `python-edgar` is finished downloading index files, you can open an index file with ```csv.csvreader``` or ```pandas.read_csv```  to have the data programmatically usable. Remember that the delimiter character is `|`!

`python-edgar` can be used as a library called from another python script, or as a standalone script.
