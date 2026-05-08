# Agent Python Tools

- repo: facebookresearch/pysparnn
- repo_uri: https://github.com/facebookresearch/pysparnn

## File: facebookresearch_pysparnn/pysparnn/cluster_index.py

Prompts

```
['create a ClusterIndex from features and records_data for approximate K-NN search with cluster pruning', 'search a ClusterIndex for the k-nearest neighbors of query features with optional k_clusters parameter', 'insert a single feature and record into an existing ClusterIndex and rebuild the index', 'create a MultiClusterIndex with multiple ClusterIndexes for improved recall at the cost of memory', 'search a MultiClusterIndex across multiple indexes for k-nearest neighbors with deduplication and optional num_indexes', 'create a CosineDistance matrix search object from sparse features and records data', 'create a DenseCosineDistance matrix search object from dense numpy features and records', 'run nearest_search on a MatrixMetricSearch object to find closest items by distance scores', 'remove near duplicate records from a MatrixMetricSearch object where distance ratio is below threshold', 'create a SlowEuclideanDistance matrix search object from dense features and records data']
```

Usage

```
{'create_ClusterIndex': 'create a ClusterIndex from features and records_data for approximate K-NN search with cluster pruning', 'search_ClusterIndex': 'search a ClusterIndex for the k-nearest neighbors of query features with optional k_clusters parameter', 'insert_ClusterIndex': 'insert a single feature and record into an existing ClusterIndex and rebuild the index', 'create_MultiClusterIndex': 'create a MultiClusterIndex with multiple ClusterIndexes for improved recall at the cost of memory', 'search_MultiClusterIndex': 'search a MultiClusterIndex across multiple indexes for k-nearest neighbors with deduplication and optional num_indexes'}
```

## File: facebookresearch_pysparnn/pysparnn/matrix_distance.py

Prompts

```
['create a ClusterIndex from features and records_data for approximate K-NN search with cluster pruning', 'search a ClusterIndex for the k-nearest neighbors of query features with optional k_clusters parameter', 'insert a single feature and record into an existing ClusterIndex and rebuild the index', 'create a MultiClusterIndex with multiple ClusterIndexes for improved recall at the cost of memory', 'search a MultiClusterIndex across multiple indexes for k-nearest neighbors with deduplication and optional num_indexes', 'create a CosineDistance matrix search object from sparse features and records data', 'create a DenseCosineDistance matrix search object from dense numpy features and records', 'run nearest_search on a MatrixMetricSearch object to find closest items by distance scores', 'remove near duplicate records from a MatrixMetricSearch object where distance ratio is below threshold', 'create a SlowEuclideanDistance matrix search object from dense features and records data']
```

Usage

```
{'create_cosine_distance_search': 'create a CosineDistance matrix search object from sparse features and records data', 'create_dense_cosine_distance_search': 'create a DenseCosineDistance matrix search object from dense numpy features and records', 'run_nearest_search': 'run nearest_search on a MatrixMetricSearch object to find closest items by distance scores', 'remove_near_duplicates': 'remove near duplicate records from a MatrixMetricSearch object where distance ratio is below threshold', 'create_euclidean_distance_search': 'create a SlowEuclideanDistance matrix search object from dense features and records data'}
```

