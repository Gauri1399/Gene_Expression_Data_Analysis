# Breast Cancer Microarray Dimensionality Reduction

## Project Overview
This project applies **dimensionality reduction (DR) techniques** to a breast cancer microarray dataset (Affymetrix HGU133A) to evaluate **processing variability across different sites**. The goal is to visualize and quantify how technical factors influence gene expression patterns, helping to distinguish **technical noise from true biological signal**.

## Key Methods
- **Principal Component Analysis (PCA)** to capture major variance components  
- **Classic and Nonmetric Multi-Dimensional Scaling (MDS)** for alternative low-dimensional embeddings  
- **Weighted Graph Laplacian (Spectral Embedding)** to examine sample relationships in two dimensions  

## Biological Motivation
Processing variability (batch effects) can confound biological conclusions. By assessing the variance explained by the **processing site**, this project helps identify sources of non-biological variability and improves the reliability of downstream gene expression analyses.

## Outcomes
- Quantified variance contributed by technical factors  
- Visualized differences in data embeddings across DR methods  
- Insights into preprocessing and normalization effects in high-dimensional gene expression datasets  

## Data
- Breast cancer microarray dataset (HGU133A) from Sotiriou et al.  
- Annotation file containing sample metadata, including processing site  

## Usage
1. Load data and annotation files in R  
2. Perform PCA, MDS, and Laplacian embedding  
3. Visualize the results and compare variability explained by site  

