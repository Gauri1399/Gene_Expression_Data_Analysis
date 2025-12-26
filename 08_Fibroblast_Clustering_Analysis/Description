# Cross-Species Fibroblast Clustering Analysis

## Overview
This project explores **unsupervised clustering of gene expression data** derived from primary fibroblast cell lines across three primate species: **human, bonobo, and gorilla**. The data were generated using the **Affymetrix HGU95Av2 microarray platform** and include 46 samples spanning the three species.
The primary goal is to evaluate how well **clustering and dimensionality reduction methods** can recover known biological groupings (species) based solely on transcriptional profiles.


## Biological Motivation
- Fibroblasts are highly conserved cell types across mammals, yet species-specific differences in gene regulation reflect **evolutionary divergence**. 
- By analyzing transcriptomic variation across species, this project highlights how gene expression patterns encode strong biological signals that can be recovered using unsupervised methods.
- Because interspecies differences are large relative to technical noise, this dataset provides a robust test case for evaluating clustering approaches and visualization techniques.


## Data
- **Dataset:** `fibroEset` (Bioconductor)
- **Platform:** Affymetrix Human HGU95Av2 array
- **Samples:** 46 total
  - Human (*Homo sapiens*): 23
  - Bonobo (*Pan paniscus*): 11
  - Gorilla (*Gorilla gorilla*): 12


## Methods
The analysis applies both **gene-level** and **spectral** clustering techniques:

### 1. Hierarchical Clustering
- Random subset of 50 genes
- Manhattan distance
- Median linkage
- Dendrogram visualization with species labels

### 2. Heatmap Visualization
- Joint hierarchical clustering of genes and samples
- Manhattan distance and median linkage
- Scaled gene expression values

### 3. Spectral Clustering via PCA + K-means
- Principal Component Analysis (PCA)
- Retention of first two eigenfunctions
- K-means clustering (k = 3)
- Visualization of clusters in reduced dimensional space


## Outcomes
- Clear separation of samples by **species**
- Consistent clustering across hierarchical and spectral methods
- Demonstration that **low-dimensional embeddings** capture dominant biological variation
- Validation of clustering as an effective tool for exploratory transcriptomic analysis


## Key Takeaways
This project illustrates how unsupervised learning methods can:
- Reveal strong biological structure without prior labels
- Distinguish evolutionary differences in gene expression
- Complement traditional differential expression analyses

The results demonstrate the power of clustering and dimensionality reduction in uncovering meaningful biological patterns from high-dimensional genomic data.
