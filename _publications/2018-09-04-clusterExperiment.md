---
title: "clusterExperiment and RSEC: A Bioconductor package and framework for clustering of single-cell and other large gene expression datasets"
collection: publications
permalink: /publications/2018-09-04-clusterExperiment
excerpt: 'With the increasing popularity of single-cell transcriptome sequencing, many experiments are creating large gene expression datasets with the goal of detecting previously unknown heterogeneity within cells. We introduce a Bioconductor R package, clusterExperiment, that implements a general and flexible clustering strategy we entitle Resampling-based Sequential Ensemble Clustering (RSEC).'
date: 2018-09-04
venue: PLOS Computational Biology
paperurl: https://doi.org/10.1371/journal.pcbi.1006378
citation: 'Davide Risso, Liam Purvis, Russell Fletcher, <b>Diya Das</b>, John Ngai, Sandrine Dudoit, and Elizabeth Purdom. (2018). clusterExperiment and RSEC: A Bioconductor package and framework for clustering of single-cell and other large gene expression datasets. <i>PLOS Computational Biology</i> 14(9): e1006378.'
---

## Abstract
Clustering of genes and/or samples is a common task in gene expression analysis. The goals in clustering can vary, but an important scenario is that of finding biologically meaningful subtypes within the samples. This is an application that is particularly appropriate when there are large numbers of samples, as in many human disease studies. With the increasing popularity of single-cell transcriptome sequencing (RNA-Seq), many more controlled experiments on model organisms are similarly creating large gene expression datasets with the goal of detecting previously unknown heterogeneity within cells. It is common in the detection of novel subtypes to run many clustering algorithms, as well as rely on subsampling and ensemble methods to improve robustness. We introduce a Bioconductor R package, clusterExperiment, that implements a general and flexible strategy we entitle Resampling-based Sequential Ensemble Clustering (RSEC). RSEC enables the user to easily create multiple, competing clusterings of the data based on different techniques and associated tuning parameters, including easy integration of resampling and sequential clustering, and then provides methods for consolidating the multiple clusterings into a final consensus clustering. The package is modular and allows the user to separately apply the individual components of the RSEC procedure, i.e., apply multiple clustering algorithms, create a consensus clustering or choose tuning parameters, and merge clusters. Additionally, clusterExperiment provides a variety of visualization tools for the clustering process, as well as methods for the identification of possible cluster signatures or biomarkers. The package clusterExperiment is publicly available through the Bioconductor Project, with a detailed manual (vignette) as well as well documented help pages for each function.

## Code
The associated R package can be found [on Bioconductor](https://bioconductor.org/packages/devel/bioc/html/clusterExperiment.html) and [on GitHub](https://github.com/epurdom/clusterExperiment).

## Preprint
A version of this paper was previously published as a preprint. The citation for the preprint is as follows:

Davide Risso, Liam Purvis, Russell Fletcher, Diya Das, John Ngai, Sandrine Dudoit, and Elizabeth Purdom. (2018). clusterExperiment and RSEC: A Bioconductor package and framework for clustering of single-cell and other large gene expression datasets. <i>bioRxiv</i> 280545; doi: [https://doi.org/10.1101/280545](https://doi.org/10.1101/280545).