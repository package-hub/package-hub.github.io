---
title: pyensembl
categories: ['python']
---
## [pyensembl](https://github.com/openvax/pyensembl)

### Python interface to access reference genome features (such as genes, transcripts, and exons) from Ensembl 


```python
from pyensembl import EnsemblRelease

# release 77 uses human reference genome GRCh38
data = EnsemblRelease(77)

# will return ['HLA-A']
gene_names = data.gene_names_at_locus(contig=6, position=29945884)

# get all exons associated with HLA-A
exon_ids  = data.exon_ids_of_gene_name('HLA-A')
```
