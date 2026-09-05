
# Homework 2 – Clustering Analysis

This project is part of the **Data Science for Health Informatics** course.

The purpose of this homework is to apply unsupervised learning and clustering techniques to both a synthetic dataset and a real-world dataset.

## Contents

- `DSHI_HW2_Chantale_Nzeggemvele_GitHub.ipynb` – Jupyter notebook containing the complete analysis.

## Datasets

Two datasets are used:

1. **Synthetic dataset** created using `make_moons()` from scikit-learn.
2. **UCI Adult Census Income Dataset**, used as the real-world dataset.

## Clustering Methods

The synthetic dataset is analysed using:

- K-Means with 2 clusters
- K-Means with 5 clusters
- DBSCAN

For the Adult dataset, K-Means clustering is performed using two selected numerical features. Different numbers of clusters are evaluated using silhouette scores to identify the most suitable number of clusters.

## Analysis

The notebook includes:

- Data preparation and preprocessing
- Normalization of numerical features
- Visualization of real and estimated clusters
- Comparison of clustering results
- Silhouette score analysis
- Interpretation of the resulting clusters
