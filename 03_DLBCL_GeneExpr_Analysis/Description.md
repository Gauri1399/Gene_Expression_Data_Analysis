## 1. Project Overview

This project examines **gene expression differences between biological classes** using the Eisen gene expression dataset.  
The analysis integrates **gene-level expression comparisons**, **transcriptome-wide variability assessment**, and **statistical power estimation** to inform robust experimental design in gene expression studies.


## 2. Biological Motivation

Gene expression profiling is widely used to identify molecular differences between biological conditions.  
However, high biological variability and limited sample sizes can reduce the ability to detect true expression changes.

This project addresses the following questions:

1. How do individual genes differ in expression between biological classes?  
2. How variable is gene expression across the transcriptome?  
3. What sample sizes are required to reliably detect biologically meaningful fold changes?  

Answering these questions is essential for **biomarker discovery**, **hypothesis testing**, and the design of adequately powered genomic experiments.


## 3. Data Description

- **Expression Matrix (`eisen.txt`)**  
  - Rows represent genes  
  - Columns represent biological samples  

- **Class Metadata (`eisenClasses.txt`)**  
  - Provides class assignments for each sample  
  - Enables group-wise comparisons and statistical analysis
