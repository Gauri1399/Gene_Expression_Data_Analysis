
# Zebrafish Swirl Microarray Analysis

## Overview

This project explores **gene expression profiling in zebrafish**, focusing on the **swirl mutant**, a point mutation in the BMP2 gene affecting dorsal/ventral axis development. The analysis uses multiple platforms: **2-channel cDNA arrays, Agilent arrays, and Affymetrix CEL files**, providing hands-on experience with microarray data processing and normalization.

**Key Goals:**

* Visualize raw microarray data using **MA and MvA plots**
* Perform **normalization** to correct technical biases
* Generate **normalized expression matrices** for downstream analysis
* Evaluate normalization methods via **correlation analysis**

---

## Biological Motivation

The swirl mutant disrupts early zebrafish development. By comparing **wildtype and mutant fish**, we can identify **differentially expressed genes** involved in key developmental pathways. Microarray data often contain technical noise, including:

* Dye effects (Cy3/Cy5)
* Intensity-dependent bias
* Array-to-array variability

Normalization ensures that observed differences reflect **true biological variation** rather than technical artifacts. This lab demonstrates how proper normalization is essential for reliable gene expression analysis.

---

## Data Sets

* **Swirl:** 2-channel cDNA array (wildtype vs swirl mutant zebrafish)
* **Agilent Patient Arrays:** 2 patient samples, 2-channel arrays
* **Affymetrix HGU133plus CEL files:** 3 healthy normal subjects

---

## Methods / Workflow

1. **Load and explore data**
   * Use `marray` for swirl cDNA arrays
   * Use `limma`, `affy`, and `affyPLM` for Agilent and Affymetrix arrays

2. **Visualize raw data**
   * MA / MvA plots for 2-channel arrays

3. **Normalize data**
   * Global median and LOESS for swirl cDNA arrays
   * Print-tip LOESS and scale normalization for Agilent arrays
   * RMA and MAS normalization for Affymetrix arrays

4. **Create normalized expression matrices**
   * Extract probe IDs and assign to row names
   * Combine arrays for downstream analysis

5. **Assess normalization performance**
   * Correlation analysis across arrays
   * Determine which normalization method preserves biological signal best

---

## Outcomes
* Understanding of **raw vs normalized data**
* Hands-on experience with **Bioconductor tools**
* Ability to correct technical variability in microarray experiments
* Creation of **normalized datasets** suitable for statistical analysis
* Insights into which normalization methods best preserve **true biological signal**

---

