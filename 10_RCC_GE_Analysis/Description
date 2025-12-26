
# Renal Cell Carcinoma Gene Expression Analysis

## Overview
This project analyzes an Affymetrix HGU133A microarray dataset (GEO accession **GDS2880**) to investigate gene expression patterns in **clear cell renal cell carcinoma (cRCC)**. The dataset consists of **patient-matched normal kidney tissue and stage I/II tumor samples**, enabling systematic assessment of data quality, outlier detection, and missing value imputation in a cancer transcriptomics context.

Rather than focusing on differential expression alone, this analysis emphasizes **quality control and preprocessing**, which are critical steps in ensuring reliable biological interpretation of high-dimensional gene expression data.


## Biological Context
Clear cell renal cell carcinoma is the most common subtype of kidney cancer and is characterized by significant molecular heterogeneity. Disruptions in genes associated with **normal renal function**, such as **KNG1 (Kininogen 1)** and **AQP2 (Aquaporin 2)**, can reflect tumor-associated dedifferentiation and loss of physiological regulation. Examining expression profiles of these genes provides biological grounding for evaluating sample integrity and imputation accuracy.


## Analysis Objectives
* Identify **outlier samples** using multiple complementary approaches
* Assess **sample similarity and variability** using correlation-based methods
* Evaluate **missing value imputation accuracy** using:\
  * k-nearest neighbors (KNN)
  * Singular value decomposition (SVD)
* Compare imputed values against known ground truth
* Visualize gene-level expression profiles to preserve biological interpretability


## Methods
* **Outlier Detection**
  * Correlation heatmaps
  * Hierarchical clustering dendrograms
  * Coefficient of variation (CV) vs. mean plots
  * Average correlation per sample

* **Gene-Level Analysis**
  * Extraction of probesets for KNG1 and AQP2
  * Expression profile visualization across samples

* **Missing Value Imputation**
  * KNN imputation using Euclidean distance
  * SVD-based imputation using PCA
  * Relative error calculation against true values


## Key Outcomes
* Identification and removal of aberrant arrays that could bias downstream analysis
* Demonstration that **KNN imputation outperforms SVD** for preserving local gene expression structure in this dataset
* Validation of biologically meaningful gene expression patterns following preprocessing
* Reinforcement of the importance of rigorous quality control in microarray studies


## Tools & Packages
* **R / Bioconductor**
* `impute`
* `pcaMethods`
* `hgu133a.db`
* `ggplot2`
* `gplots`


