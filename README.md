# Advanced Data Science 2023: Stephanie Hicks

Advanced Data Science Fall 2023 (140.711) from Stephanie Hicks. 


## Key resources

- Workshop material: [pkgdown website](https://stephaniehicks.com/singlecelldemo)
- Code: [GitHub](https://github.com/stephaniehicks/singlecelldemo)

## Instructor

```
Stephanie C. Hicks, PhD
Associate Professor, Biostatistics, Johns Hopkins Bloomberg School of Public Health
Faculty member, Johns Hopkins Data Science Lab
Pronouns: she/her 
```
- web: https://www.stephaniehicks.com
- email: shicks19@jhu.edu
- twitter: [@stephaniehicks](http://twitter.com/stephaniehicks)

## Acknowledgements

This course website was developed and is maintained by Stephanie C. Hicks.

The following individuals have contributed to improving the course or materials have been adapted from their courses: 

- [Mike Love](https://biodatascience.github.io/compbio/bioc/objects)
- [Orchestrating Single-Cell Analysis with Bioconductor](https://bioconductor.org/books/release/OSCA) (OSCA) contributors (cite: [Amezquita et al. 2019](https://doi.org/10.1038/s41592-019-0654-x))

The course materials are licensed under the Creative Commons Attribution 4.0 International License. 
Linked and embedded materials are governed by their own licenses. 
I assume that all external materials used or embedded here are covered under the educational fair use policy. 
If this is not the case and any material displayed here violates copyright, please let me know and I will remove it.


## Software

These materials use `tidyverse` and packages from Bioconductor version 3.17.
This is the current 'release' version of Bioconductor, which can be installed following [these instructions](https://bioconductor.org/install).

For example, you can then install a subset of the packages necessary for these tutorials using the following:

```
library(BiocManager)
BiocManager::install(c("SingleCellExperiment","scater", "scran"))
```



