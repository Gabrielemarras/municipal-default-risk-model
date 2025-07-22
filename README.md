# Municipal Default Risk – Predictive Model for Italian Local Governments

**Author**: Gabriele Marras  
**Project**: Final assignment for the Statistical Learning course  
**Institution**: Università Cattolica del Sacro Cuore, MSc in Finance  
**Year**: 2024

---

## Project Overview

This project presents a predictive model designed to assess the financial distress risk of Italian municipalities.  
The work relies on official budgetary and demographic indicators to estimate default probability using classical and modern classification techniques.

The main goal is to build an early-warning system capable of identifying high-risk municipalities before financial distress occurs.

---

## Methods and Models

The predictive framework includes the following approaches:

- **Logistic Regression (GLM)** with variable selection
- **Linear Discriminant Analysis (LDA)**
- **K-Nearest Neighbors (KNN)**
- **Principal Component Analysis (PCA)** for dimensionality reduction
- **10-fold Cross-validation** to test generalization

---

## Data and Sources

- Indicators from **ISTAT** (Italian National Institute of Statistics)
- Default data from **Ca’ Foscari University Foundation**
- Variables include:
  - Fiscal autonomy, spending rigidity, interest burden
  - Receivables/payables indicators
  - Transfer-dependence ratios
  - Personnel metrics

---

## Key Insights

- Strong predictors include collection capacity, interest expenses, and receivables management
- The final logistic model achieved:
  - **Accuracy** ≈ 74%
  - **Sensitivity** ≈ 81%
  - **Specificity** ≈ 74%
- PCA revealed weak territorial clustering, supporting a financial rather than geographic interpretation

---

## Applications

This model can be used as an **early-warning tool** for policymakers, financial analysts, and public administrators to:
- Prevent fiscal crises
- Prioritize supervision efforts
- Allocate support resources effectively

---

For academic or professional use, please contact the author.
