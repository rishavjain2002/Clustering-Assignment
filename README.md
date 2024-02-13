# Clustering Algorithms README

This repository contains implementations and explanations of three popular clustering algorithms: KMeans, Hierarchical, and Mean Shift clustering.

## KMeans Clustering

### Introduction
KMeans clustering is a popular unsupervised learning algorithm used for partitioning data into distinct clusters based on similarities in the data points' features.

### Usage
To use the KMeans clustering algorithm:
1. Prepare your dataset.
2. Choose the number of clusters (`n_clusters`) you want to partition your data into.
3. Call the `perform_clustering()` function with your dataset and the chosen number of clusters as arguments.
4. Retrieve the cluster labels assigned to each data point.

Example:
```python
from clustering_algorithms import perform_clustering

# Assuming X is your dataset and n_clusters is the desired number of clusters
X = ...  # Your dataset
n_clusters = 5

# Perform KMeans clustering
cluster_labels = perform_clustering(X, n_clusters)
