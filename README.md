# NOISeq: Exploratory analysis and differential expression for RNA-seq data

Author: Sonia Tarazona, Pedro Furio-Tari, Maria Jose Nueda, Alberto Ferrer and Ana Conesa

### About NOISeq
Analysis of RNA-seq expression data or other similar kind of data. Exploratory plots to evualuate saturation, count distribution, expression per chromosome, type of detected features, features length, etc. Differential expression between two experimental conditions with no parametric assumptions.

## How to Install
To install this package, start R (version "4.0") and enter:

```
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("NOISeq")
```

- More information avariable on [Bioconductor NOISeq website](https://www.bioconductor.org/packages/release/bioc/html/NOISeq.html)
