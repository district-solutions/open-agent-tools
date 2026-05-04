# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/cse/embedder.py

Prompts

```
['create an embedder from a CfgNode spec and embedding dimension using create_embedder', 'initialize an Embedder module from a Detectron2 CfgNode to manage multiple mesh embedders', 'load embedder state dict from a .pkl or .pth model checkpoint file', 'produce vertex embeddings tensor of shape [N, D] for a named mesh via forward', 'check whether a given mesh name has registered embeddings using has_embeddings', 'compute pairwise squared Euclidean distances between two sets of D-dimensional points using torch tensors', 'normalize N D-dimensional embedding vectors so their L2 norms equal 1 with a configurable epsilon floor', 'find closest mesh vertices and segmentation mask from interpolated embeddings and segmentation tensors for a bounding box', 'review the squared_euclidean_distance_matrix function to understand how it computes pairwise distances via matrix multiplication', 'refactor get_closest_vertices_mask_from_ES to support a different chunk size or interpolation mode for memory optimization', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'get normalized vertex embeddings tensor by calling forward on the embedder', 'load precomputed vertex embeddings from a pickle file into the embedder', 'build a PyTorch nn.Module that produces normalized vertex embeddings for DensePose CSE', 'create a VertexFeatureEmbedder instance with num_vertices, feature_dim, and embed_dim parameters', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized NxD tensor', 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review the VertexFeatureEmbedder forward method that computes F times E and normalizes embeddings']
```

Usage

```
{'create_embedder_from_config': 'create an embedder from a CfgNode spec and embedding dimension using create_embedder', 'initialize_Embedder_with_cfg': 'initialize an Embedder module from a Detectron2 CfgNode to manage multiple mesh embedders', 'load_embeddings_from_checkpoint': 'load embedder state dict from a .pkl or .pth model checkpoint file', 'forward_vertex_embeddings': 'produce vertex embeddings tensor of shape [N, D] for a named mesh via forward', 'check_mesh_has_embeddings': 'check whether a given mesh name has registered embeddings using has_embeddings'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/cse/utils.py

Prompts

```
['create an embedder from a CfgNode spec and embedding dimension using create_embedder', 'initialize an Embedder module from a Detectron2 CfgNode to manage multiple mesh embedders', 'load embedder state dict from a .pkl or .pth model checkpoint file', 'produce vertex embeddings tensor of shape [N, D] for a named mesh via forward', 'check whether a given mesh name has registered embeddings using has_embeddings', 'compute pairwise squared Euclidean distances between two sets of D-dimensional points using torch tensors', 'normalize N D-dimensional embedding vectors so their L2 norms equal 1 with a configurable epsilon floor', 'find closest mesh vertices and segmentation mask from interpolated embeddings and segmentation tensors for a bounding box', 'review the squared_euclidean_distance_matrix function to understand how it computes pairwise distances via matrix multiplication', 'refactor get_closest_vertices_mask_from_ES to support a different chunk size or interpolation mode for memory optimization', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'get normalized vertex embeddings tensor by calling forward on the embedder', 'load precomputed vertex embeddings from a pickle file into the embedder', 'build a PyTorch nn.Module that produces normalized vertex embeddings for DensePose CSE', 'create a VertexFeatureEmbedder instance with num_vertices, feature_dim, and embed_dim parameters', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized NxD tensor', 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review the VertexFeatureEmbedder forward method that computes F times E and normalizes embeddings']
```

Usage

```
{'compute_squared_euclidean_distance_matrix': 'compute pairwise squared Euclidean distances between two sets of D-dimensional points using torch tensors', 'normalize_embedding_vectors': 'normalize N D-dimensional embedding vectors so their L2 norms equal 1 with a configurable epsilon floor', 'find_closest_mesh_vertices': 'find closest mesh vertices and segmentation mask from interpolated embeddings and segmentation tensors for a bounding box', 'review_squared_euclidean_distance_matrix': 'review the squared_euclidean_distance_matrix function to understand how it computes pairwise distances via matrix multiplication', 'refactor_get_closest_vertices_mask_from_ES': 'refactor get_closest_vertices_mask_from_ES to support a different chunk size or interpolation mode for memory optimization'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/cse/vertex_direct_embedder.py

Prompts

```
['create an embedder from a CfgNode spec and embedding dimension using create_embedder', 'initialize an Embedder module from a Detectron2 CfgNode to manage multiple mesh embedders', 'load embedder state dict from a .pkl or .pth model checkpoint file', 'produce vertex embeddings tensor of shape [N, D] for a named mesh via forward', 'check whether a given mesh name has registered embeddings using has_embeddings', 'compute pairwise squared Euclidean distances between two sets of D-dimensional points using torch tensors', 'normalize N D-dimensional embedding vectors so their L2 norms equal 1 with a configurable epsilon floor', 'find closest mesh vertices and segmentation mask from interpolated embeddings and segmentation tensors for a bounding box', 'review the squared_euclidean_distance_matrix function to understand how it computes pairwise distances via matrix multiplication', 'refactor get_closest_vertices_mask_from_ES to support a different chunk size or interpolation mode for memory optimization', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'get normalized vertex embeddings tensor by calling forward on the embedder', 'load precomputed vertex embeddings from a pickle file into the embedder', 'build a PyTorch nn.Module that produces normalized vertex embeddings for DensePose CSE', 'create a VertexFeatureEmbedder instance with num_vertices, feature_dim, and embed_dim parameters', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized NxD tensor', 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review the VertexFeatureEmbedder forward method that computes F times E and normalizes embeddings']
```

Usage

```
{'create_vertex_embedder': 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset_embedder_parameters': 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'get_normalized_embeddings': 'get normalized vertex embeddings tensor by calling forward on the embedder', 'load_embeddings_from_file': 'load precomputed vertex embeddings from a pickle file into the embedder', 'build_vertex_embedding_module': 'build a PyTorch nn.Module that produces normalized vertex embeddings for DensePose CSE'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/cse/vertex_feature_embedder.py

Prompts

```
['create an embedder from a CfgNode spec and embedding dimension using create_embedder', 'initialize an Embedder module from a Detectron2 CfgNode to manage multiple mesh embedders', 'load embedder state dict from a .pkl or .pth model checkpoint file', 'produce vertex embeddings tensor of shape [N, D] for a named mesh via forward', 'check whether a given mesh name has registered embeddings using has_embeddings', 'compute pairwise squared Euclidean distances between two sets of D-dimensional points using torch tensors', 'normalize N D-dimensional embedding vectors so their L2 norms equal 1 with a configurable epsilon floor', 'find closest mesh vertices and segmentation mask from interpolated embeddings and segmentation tensors for a bounding box', 'review the squared_euclidean_distance_matrix function to understand how it computes pairwise distances via matrix multiplication', 'refactor get_closest_vertices_mask_from_ES to support a different chunk size or interpolation mode for memory optimization', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'get normalized vertex embeddings tensor by calling forward on the embedder', 'load precomputed vertex embeddings from a pickle file into the embedder', 'build a PyTorch nn.Module that produces normalized vertex embeddings for DensePose CSE', 'create a VertexFeatureEmbedder instance with num_vertices, feature_dim, and embed_dim parameters', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized NxD tensor', 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review the VertexFeatureEmbedder forward method that computes F times E and normalizes embeddings']
```

Usage

```
{'create_VertexFeatureEmbedder': 'create a VertexFeatureEmbedder instance with num_vertices, feature_dim, and embed_dim parameters', 'build_vertex_embeddings': 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized NxD tensor', 'reset_VertexFeatureEmbedder_parameters': 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load_VertexFeatureEmbedder_from_file': 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review_VertexFeatureEmbedder_forward': 'review the VertexFeatureEmbedder forward method that computes F times E and normalizes embeddings'}
```

