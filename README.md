# Ensemble Methods & Clustering

**Hellenic Open University | MSc Data Science & Machine Learning | 2024–2026**

---

## Overview  
This project explores ensemble learning methods combined with dimensionality reduction techniques and unsupervised clustering approaches to improve classification performance and data efficiency.

---

## Problem 1 — Breast Cancer Classification (Random Forest)

- **Dataset:** Wisconsin Breast Cancer (scikit-learn)  
- **Goal:** Classify tumors as malignant or benign  
- **Techniques:** Decision Trees, Random Forest, PCA, LLE, GridSearchCV  
- **Evaluation:** ROC-AUC, accuracy, training time comparison across different preprocessing pipelines  
- **Key Insight:** Analysis of how dimensionality reduction (PCA vs LLE) affects Random Forest performance and computational efficiency  

---

## Problem 2 — Pulsar Detection (K-Means & t-SNE)

- **Dataset:** HTRU2 Pulsar Dataset (UCI)  
- **Goal:** Improve classification efficiency using clustering-based data reduction and sampling strategies  
- **Techniques:** K-Means clustering, t-SNE visualization, stratified sampling  
- **Evaluation:** Classification report and performance comparison across different cluster sizes (k = 5, 10, 25)  
- **Key Insight:** Evaluation of how representative cluster sampling can reduce dataset size while preserving model performance  

---

## Tools & Libraries

Python · NumPy · pandas · scikit-learn · matplotlib · seaborn
