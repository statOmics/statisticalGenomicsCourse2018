---
layout: default
title: scRNAseq.md
mathjax: true
---

Darmanis et al. 2017 investigate investigate the heterogeneity of glioblastoma tumors and assess differential expression between cells within and in proximity of the tumor using scRNA-seq technology. They sequenced cells of 4 different individuals and are interested in discovering genes that are differentially expressed between cells of a celltype within the tumor and in the proximity of the tumor. They also would like to find genes for which the difference in regulation of the expression between normal and tumor cells differs according to cell type.
They deposited the data at [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE84465](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE84465).
Mapped gene counts can be found on [https://www.dropbox.com/s/hg9vhj2ltiypahx/GSE84465_gene.rds?dl=0](https://www.dropbox.com/s/hg9vhj2ltiypahx/GSE84465_gene.rds?dl=0).

The object can be loaded in R by using the code. Note, that I assumed that the downloaded count object file is in your working directory. 

```
data <-readRDS("GSE84465_gene.rds")
```
