# Unsupervised Techniques Analysis
A comparative analysis framework for evaluating six different unsupervised machine learning techniques on real-world and synthetic datasets.

## Overview
This repository implements a benchmarking system to compare the performance of various dimensionality reduction and clustering algorithms across different data characteristics. The framework is designed to assess how each technique handles both real-world data complexity and controlled synthetic scenarios.

## Techniques Analyzed
The framework evaluates six unsupervised learning approaches:

- **PCA** - Principal Component Analysis (linear dimensionality reduction)
- **t-SNE** - t-distributed Stochastic Neighbor Embedding (non-linear dimensionality reduction)
- **k-means** - Centroid-based clustering
- **AHC** - Agglomerative Hierarchical Clustering
- **Autoencoder** - Neural network-based dimensionality reduction
- **SOM** - Self-Organizing Maps

## Datasets
- Real Dataset (`A2-real.txt`)
  - Records: 342 entries A2-real.txt:31-334
  - Features: 7 columns (BL, BD, FL, BM, S, Location, Class)
  - Data Types: Mixed numerical and categorical features
  - Categories:
    - Location: L1, L2, L3
    - Class: C1, C2, C3

- Synthetic Dataset (`A2-synthetic.txt`)
  - Records: 200 entries A2-synthetic.txt:61-120
  - Features: 5 columns (x1, x2, x3, x4, class)
  - Data Types: Numerical features with integer class labels (1-6)
  - Class Range: 1-6
  - Feature Range: Approximately -1 to +1 for x1-x4
