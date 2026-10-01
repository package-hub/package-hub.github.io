---
title: eggnog-mapper
categories: ['python', 'annotations', 'orthology-assignments']
---
## [eggnog-mapper](https://github.com/eggnogdb/eggnog-mapper)

### Fast genome-wide functional annotation through orthology assignment

**EggNOG-mapper** is a tool for fast functional annotation of novel sequences. It uses precomputed orthologous groups and phylogenies from the eggNOG database (http://eggnog5.embl.de) to transfer functional information from fine-grained orthologs only.

Common uses of eggNOG-mapper include the annotation of novel genomes, transcriptomes or even metagenomic gene catalogs.

The use of orthology predictions for functional annotation permits a higher precision than traditional homology searches (i.e. BLAST searches), as it avoids transferring annotations from close paralogs (duplicate genes with a higher chance of being involved in functional divergence).

Benchmarks comparing different eggNOG-mapper options against BLAST and InterProScan [can be found here](https://github.com/jhcepas/emapper-benchmark/blob/master/benchmark_analysis.ipynb).

EggNOG-mapper is also available as a public online resource: http://eggnog-mapper.embl.de
