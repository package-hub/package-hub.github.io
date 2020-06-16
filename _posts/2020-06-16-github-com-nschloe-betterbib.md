---
title: betterbib
categories: ['python', 'bibtex', 'latex']
---
## [betterbib](https://github.com/nschloe/betterbib)

### Update BibTeX files with info from online resources.


All of the following tools can read from standard input and write to standard output, so
you can concatenate them to get exactly what you want. For example, the above
`betterbib` command is equivalent to
```
betterbib-sync in.bib | betterbib-journal-abbrev | betterbib-format -b - out.bib
```

