## Lung Cancer Classification Using Gene Expression (LDA)

### Overview
This project applies **linear discriminant analysis (LDA)** to Affymetrix microarray gene expression data to classify lung tissue samples into **small cell lung carcinoma (SCLC)**, **adenocarcinoma**, and **normal lung tissue**. Using a supervised learning framework, the model is trained on a subset of labeled samples and evaluated on held-out data to assess its predictive performance.

### Biological Motivation
Lung cancer is a heterogeneous disease with multiple histological subtypes that differ in prognosis, treatment response, and molecular drivers. Accurate classification of tumor type is critical for clinical decision-making. Gene expression profiling enables the identification of transcriptional patterns that distinguish cancer subtypes from each other and from healthy tissue.

This analysis demonstrates how transcriptomic signatures can be leveraged to:

* Differentiate malignant from normal tissue
* Discriminate between biologically distinct lung cancer subtypes
* Explore the feasibility of molecular diagnostics based on expression data

### Analytical Goals
* Train an **LDA classifier** on labeled gene expression data
* Compare classification performance using:
  * A minimal feature set (first 2 genes)
  * The full gene set
* Evaluate model accuracy using a **confusion matrix**
* Visualize class separation using **linear discriminant functions (LD1 and LD2)**

### Key Methods
* Affymetrix microarray preprocessing (pre-selected probes)
* Supervised classification with **Linear Discriminant Analysis**
* Train/test data partitioning
* Confusion matrix–based performance evaluation
* Low-dimensional visualization of discriminant space

### Key Findings
* Using only two genes leads to substantial misclassification, highlighting the limitations of overly sparse feature sets
* Incorporating the full gene set significantly improves class separation
* LDA effectively captures biologically meaningful variation between lung cancer subtypes and normal tissue

### Impact
This project illustrates a classic use case of **machine learning in cancer genomics**, showing how gene expression data can support diagnostic classification tasks. The workflow mirrors real-world translational bioinformatics pipelines used in biomarker discovery and clinical genomics.
