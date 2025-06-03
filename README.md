# Code Review Party Overview

## Installing the project

```
git clone https://github.com/aifimmunology/pediatric_IH.git
cd pediatric_IH
```

## Overview
The scripts that need reviewing can be found here: https://github.com/aifimmunology/pediatric_IH/tree/pediatric_analysis/pediatric_IH/jupyter/Analysis/DEG/Flu_Y2_D0_D7

These notebooks, consist of work done to perform Deseq2 analysis at Flu Year 2 Day 0 in order to look at pediatric response to the flu vaccine. These scripts do the following:

* Generates a filtered gene list of genes that pass thr 10% threshold
* Running Deseq2 to do multiple group comparison, prioritizing visit timepoint comparison
* Code to generate barplot to look at DEG results
* Scatter plot code, to look at individual celltypes and see how genes are expressed between different age cohorts
