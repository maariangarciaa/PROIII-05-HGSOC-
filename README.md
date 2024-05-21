# PROIII-05-HGSOC Research Repository

Welcome to the PROIII-05-HGSOC repository, a dedicated space for our research into High-Grade Serous Ovarian Cancer (HGSOC). HGSOC stands as a challenge in oncology, characterized by its aggressive nature and often grim prognosis. Our research is focused on underlying molecular intricacies of this disease and its subtypes, aiming to decipher the nuanced mechanisms that propel ovarian cancer progression.

## Installation

Ensure you have the necessary R packages installed to follow the analyses in this repository:

```R
# Install necessary R packages
install.packages(c("FactoMineR", "factoextra", "glmnet", "survival", "caret", "mixOmics", "blockForest", "dplyr","priorityLasso", "pROC", "ggplot2", "DescTools","randomForest", "stats", "pls"))
```

## Understanding HGSOC

High-Grade Serous Ovarian Cancer (HGSOC) represents a complex oncological entity with multiple subtypes each contributing differently to patient outcomes. Through comprehensive analysis of multi-omic data, we explore the distinct etiological factors and the omic variables that define each subtype.

## Research Focus and Data Overview

Our research leverages advanced classification and regression models to identify unique molecular signatures of HGSOC and its subtypes. The dataset used, ‘TCGAforMORE.RData’, contains multi-omic data from about 300 patients classified into four subtypes: immunoreactive, differentiated, proliferative, and mesenchymal, each with distinct prognoses.

### Data Composition
- **GeneExpr**: Matrix not used directly for creating subtype classifications.
- **Subtypes**: Classifications of ovarian cancer subtypes for each patient.
- **Omicas**:
  - **CNV (Copy Number Variations)**: Genetic alteration data across patients.
  - **methyl (DNA methylation)**: Methylation profiles.
  - **miRNA (microRNA regulation)**: miRNA expression levels.
  - **TF (Transcription Factors)**: Transcription factor activity profiles.

## Methodologies Employed

In this repository, you'll find a range of innovative computational methods applied to our research, including:
- **PLS-DA (Partial Least Squares Discriminant Analysis):** Enhancing the diagnostic accuracy by modeling complex data structures.
- **BlockForest:** A robust algorithm for feature selection and classification, tailored for high-dimensional genomic data.
- **Elastic Net:** A regularization and variable selection method that combines the properties of both ridge and lasso regression.
- **Random Forest:** An ensemble learning method for classification and regression that improves predictive accuracy and overfitting control.
- **Priority Lasso:** An advanced variant of the Lasso technique that prioritizes variables based on their potential relevance, optimizing feature selection.

## Objective

Our objective is to enhance diagnostic precision, understand subtype distinctions, and improve clinical management of HGSOC by providing accurate, interpretable results of genes influencing HGSOC subtypes.

Stay tuned for updates, data releases, and collaborative opportunities!


