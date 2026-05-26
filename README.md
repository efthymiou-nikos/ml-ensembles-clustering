# Ensemble Methods & Clustering

**Hellenic Open University | MSc Data Science & Machine Learning | 2024-26**

---

## Overview
Two machine learning problems exploring ensemble classifiers with dimensionality 
reduction and unsupervised clustering techniques.

## Problem 1 — Breast Cancer Classification (Random Forest)
- Dataset: Wisconsin Breast Cancer (sklearn)
- Goal: Classify tumors as malignant or benign
- Techniques: Decision Trees, Random Forest, PCA, LLE, GridSearchCV
- Evaluation: ROC-AUC, accuracy, training time comparison across three variants
- Key insight: Impact of dimensionality reduction (PCA vs LLE) on Random Forest performance

## Problem 2 — Pulsar Detection (K-Means & t-SNE)
- Dataset: HTRU2 Pulsar Dataset (UCI)
- Goal: Detect pulsar signals using Random Forest with reduced training data via clustering
- Techniques: K-Means clustering, t-SNE visualization, stratified sampling
- Evaluation: Classification report across different cluster sizes (k=5, 10, 25)
- Key insight: Using representative samples from K-Means to minimize data requirements 
  without significant performance loss

## Tools & Libraries
Python · scikit-learn · pandas · matplotlib · seaborn · numpy
