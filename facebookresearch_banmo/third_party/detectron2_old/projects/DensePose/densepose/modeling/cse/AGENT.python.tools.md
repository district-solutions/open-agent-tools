# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/modeling/cse/embedder.py

Prompts

```
['create a vertex direct or vertex feature embedder from a CfgNode spec and embedding dimension', 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load embedder state dict from a pkl or torch model checkpoint file with a given prefix', 'forward a mesh name through the Embedder to get vertex embeddings as an NxD tensor', 'check whether the Embedder has registered embeddings for a given mesh name', 'build a python module to compute pairwise squared Euclidean distances between two sets of points', 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test the function that interpolates embeddings and segmentations to compute closest mesh vertices', 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize the function that finds closest mesh vertices from interpolated embeddings and segmentation masks', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load precomputed vertex embeddings from a pickle file into the embedder', 'review the VertexDirectEmbedder class and its embedding initialization and normalization logic', 'create a VertexFeatureEmbedder with num_vertices, feature_dim, embed_dim, and optional train_features flag', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized [N, D] tensor', 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review the VertexFeatureEmbedder forward method that computes F * E matrix multiplication and normalizes embeddings']
```

Usage

```
{'create_embedder_from_config': 'create a vertex direct or vertex feature embedder from a CfgNode spec and embedding dimension', 'build_embedder_module': 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load_embedder_checkpoint': 'load embedder state dict from a pkl or torch model checkpoint file with a given prefix', 'forward_vertex_embeddings': 'forward a mesh name through the Embedder to get vertex embeddings as an NxD tensor', 'check_mesh_embeddings': 'check whether the Embedder has registered embeddings for a given mesh name'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/modeling/cse/utils.py

Prompts

```
['create a vertex direct or vertex feature embedder from a CfgNode spec and embedding dimension', 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load embedder state dict from a pkl or torch model checkpoint file with a given prefix', 'forward a mesh name through the Embedder to get vertex embeddings as an NxD tensor', 'check whether the Embedder has registered embeddings for a given mesh name', 'build a python module to compute pairwise squared Euclidean distances between two sets of points', 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test the function that interpolates embeddings and segmentations to compute closest mesh vertices', 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize the function that finds closest mesh vertices from interpolated embeddings and segmentation masks', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load precomputed vertex embeddings from a pickle file into the embedder', 'review the VertexDirectEmbedder class and its embedding initialization and normalization logic', 'create a VertexFeatureEmbedder with num_vertices, feature_dim, embed_dim, and optional train_features flag', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized [N, D] tensor', 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review the VertexFeatureEmbedder forward method that computes F * E matrix multiplication and normalizes embeddings']
```

Usage

```
{'build_squared_euclidean_distance_matrix': 'build a python module to compute pairwise squared Euclidean distances between two sets of points', 'create_normalize_embeddings': 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test_get_closest_vertices_mask_from_ES': 'test the function that interpolates embeddings and segmentations to compute closest mesh vertices', 'refactor_squared_euclidean_distance_matrix': 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize_get_closest_vertices_mask_from_ES': 'summarize the function that finds closest mesh vertices from interpolated embeddings and segmentation masks'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/modeling/cse/vertex_direct_embedder.py

Prompts

```
['create a vertex direct or vertex feature embedder from a CfgNode spec and embedding dimension', 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load embedder state dict from a pkl or torch model checkpoint file with a given prefix', 'forward a mesh name through the Embedder to get vertex embeddings as an NxD tensor', 'check whether the Embedder has registered embeddings for a given mesh name', 'build a python module to compute pairwise squared Euclidean distances between two sets of points', 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test the function that interpolates embeddings and segmentations to compute closest mesh vertices', 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize the function that finds closest mesh vertices from interpolated embeddings and segmentation masks', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load precomputed vertex embeddings from a pickle file into the embedder', 'review the VertexDirectEmbedder class and its embedding initialization and normalization logic', 'create a VertexFeatureEmbedder with num_vertices, feature_dim, embed_dim, and optional train_features flag', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized [N, D] tensor', 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review the VertexFeatureEmbedder forward method that computes F * E matrix multiplication and normalizes embeddings']
```

Usage

```
{'create_vertex_embedder': 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset_embedder_parameters': 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'forward_normalized_embeddings': 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load_embeddings_from_file': 'load precomputed vertex embeddings from a pickle file into the embedder', 'review_vertex_embedder_class': 'review the VertexDirectEmbedder class and its embedding initialization and normalization logic'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/modeling/cse/vertex_feature_embedder.py

Prompts

```
['create a vertex direct or vertex feature embedder from a CfgNode spec and embedding dimension', 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load embedder state dict from a pkl or torch model checkpoint file with a given prefix', 'forward a mesh name through the Embedder to get vertex embeddings as an NxD tensor', 'check whether the Embedder has registered embeddings for a given mesh name', 'build a python module to compute pairwise squared Euclidean distances between two sets of points', 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test the function that interpolates embeddings and segmentations to compute closest mesh vertices', 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize the function that finds closest mesh vertices from interpolated embeddings and segmentation masks', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load precomputed vertex embeddings from a pickle file into the embedder', 'review the VertexDirectEmbedder class and its embedding initialization and normalization logic', 'create a VertexFeatureEmbedder with num_vertices, feature_dim, embed_dim, and optional train_features flag', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized [N, D] tensor', 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review the VertexFeatureEmbedder forward method that computes F * E matrix multiplication and normalizes embeddings']
```

Usage

```
{'create_VertexFeatureEmbedder': 'create a VertexFeatureEmbedder with num_vertices, feature_dim, embed_dim, and optional train_features flag', 'build_vertex_embeddings': 'build vertex embeddings by calling forward on a VertexFeatureEmbedder to get normalized [N, D] tensor', 'reset_VertexFeatureEmbedder_parameters': 'reset all features and embeddings in a VertexFeatureEmbedder to zero using reset_parameters', 'load_VertexFeatureEmbedder_from_file': 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'review_VertexFeatureEmbedder_forward': 'review the VertexFeatureEmbedder forward method that computes F * E matrix multiplication and normalizes embeddings'}
```

