---
title: bcbio-nextgen
categories: ['python']
---
## [bcbio-nextgen](https://github.com/bcbio/bcbio-nextgen)

### Validated, scalable, community developed variant calling, RNA-seq and small RNA analysis


* Community developed: We welcome contributors with the goal of overcoming the biological, algorithmic and computational challenges that face individual developers working on complex pipelines in quickly changing research areas. See our [users page](https://bcbio-nextgen.readthedocs.io/en/latest/contents/users.html) for examples of bcbio-nextgen deployments, and the [developer documentation](https://bcbio-nextgen.readthedocs.io/en/latest/contents/development.html) for tips on contributing.
* Installation: [A single installer script](https://bcbio-nextgen.readthedocs.io/en/latest/contents/installation.html#automated) prepares all third party software, data libraries and system configuration files.
* [Automated validation](https://bcb.io/2014/05/12/wgs-trio-variant-evaluation/): Compare variant calls against common reference materials or sample specific SNP arrays to ensure call correctness. Incorporation of multiple approaches for alignment, preparation and variant calling enable unbiased comparisons of algorithms.
* Distributed: Focus on [parallel analysis and scaling](https://bcb.io/2013/05/22/scaling-variant-detection-pipelines-for-whole-genome-sequencing-analysis/) to handle large population studies and whole genome analysis. Runs on single multicore computers, in compute clusters using [IPython parallel](https://ipyparallel.readthedocs.io/en/latest/), or on the Amazon cloud. See the [parallel documentation](https://bcbio-nextgen.readthedocs.org/en/latest/contents/parallel.html) for full details.
* Multiple analysis algorithms: bcbio-nextgen provides configurable [variant calling (small and copy number), RNA-seq, ATAC-seq, , BS-Seq, SC RNA-seq, and small RNA pipelines](https://bcbio-nextgen.readthedocs.io/en/latest/).
