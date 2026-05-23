# Agent Python Tools

- repo: facebookresearch/ssl-data-curation
- repo_uri: https://github.com/facebookresearch/ssl-data-curation

## File: facebookresearch_ssl-data-curation/vis/generalized_kmeans_1d.py

Prompts

```
['run generalized k-means clustering on 1D data with L2^(2n) distance and k-means++ initialization', 'run k-means++ initialization to select initial cluster centers from a torch tensor dataset', "compute k-means centroids using Newton's method to minimize L2^(2n) distortion over multiple iterations", 'assign data points to the nearest centroids using L2 distance with optional chunking support', 'update cluster centroids by recomputing means based on newly assigned cluster memberships']
```

Usage

```
{'run_generalized_kmeans_1d': 'run generalized k-means clustering on 1D data with L2^(2n) distance and k-means++ initialization', 'run_kmeans_plusplus_initialization': 'run k-means++ initialization to select initial cluster centers from a torch tensor dataset', 'compute_centroids_newton': "compute k-means centroids using Newton's method to minimize L2^(2n) distortion over multiple iterations", 'assign_clusters_to_centroids': 'assign data points to the nearest centroids using L2 distance with optional chunking support', 'update_centroids_from_clusters': 'update cluster centroids by recomputing means based on newly assigned cluster memberships'}
```

