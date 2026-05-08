# Agent Python Tools

- repo: facebookresearch/hgnn
- repo_uri: https://github.com/facebookresearch/hgnn

## File: facebookresearch_hgnn/hyperbolic_module/CentroidDistance.py

Prompts

```
['build a PyTorch module to calculate pairwise distances between node representations and centroids on a manifold', 'create a centroid embedding layer with configurable num_centroid and embed_size parameters for hyperbolic or euclidean manifolds', 'compute pairwise distances between node representations and centroid embeddings using manifold distance metrics', 'compute average pooled graph-level centroid distances by summing node distances and dividing by mask sum', 'review the CentroidDistance forward method that broadcasts node and centroid representations and returns graph and node level distances', 'compute the Poincare distance between two tensors u and v using the forward method', 'compute the backward gradient for Poincare distance using the backward method', 'compute the gradient of Poincare distance with respect to input tensors using the grad method', 'review the PoincareDistance class and its custom autograd forward and backward implementations', 'test the PoincareDistance class by computing distances between two PyTorch tensors']
```

Usage

```
{'build_centroid_distance_module': 'build a PyTorch module to calculate pairwise distances between node representations and centroids on a manifold', 'create_centroid_embedding': 'create a centroid embedding layer with configurable num_centroid and embed_size parameters for hyperbolic or euclidean manifolds', 'compute_node_centroid_distances': 'compute pairwise distances between node representations and centroid embeddings using manifold distance metrics', 'compute_graph_centroid_distances': 'compute average pooled graph-level centroid distances by summing node distances and dividing by mask sum', 'review_CentroidDistance_forward': 'review the CentroidDistance forward method that broadcasts node and centroid representations and returns graph and node level distances'}
```

## File: facebookresearch_hgnn/hyperbolic_module/PoincareDistance.py

Prompts

```
['build a PyTorch module to calculate pairwise distances between node representations and centroids on a manifold', 'create a centroid embedding layer with configurable num_centroid and embed_size parameters for hyperbolic or euclidean manifolds', 'compute pairwise distances between node representations and centroid embeddings using manifold distance metrics', 'compute average pooled graph-level centroid distances by summing node distances and dividing by mask sum', 'review the CentroidDistance forward method that broadcasts node and centroid representations and returns graph and node level distances', 'compute the Poincare distance between two tensors u and v using the forward method', 'compute the backward gradient for Poincare distance using the backward method', 'compute the gradient of Poincare distance with respect to input tensors using the grad method', 'review the PoincareDistance class and its custom autograd forward and backward implementations', 'test the PoincareDistance class by computing distances between two PyTorch tensors']
```

Usage

```
{'compute_poincare_distance_forward': 'compute the Poincare distance between two tensors u and v using the forward method', 'compute_poincare_distance_backward': 'compute the backward gradient for Poincare distance using the backward method', 'compute_poincare_gradient': 'compute the gradient of Poincare distance with respect to input tensors using the grad method', 'review_poincare_distance_class': 'review the PoincareDistance class and its custom autograd forward and backward implementations', 'test_poincare_distance': 'test the PoincareDistance class by computing distances between two PyTorch tensors'}
```

