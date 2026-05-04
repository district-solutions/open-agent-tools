# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/cse/embedder.py

Prompts

```
['create a VertexDirectEmbedder or VertexFeatureEmbedder from a CfgNode spec and embedding dimension', 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load embedder state dict from a pkl or torch checkpoint file with a configurable key prefix', 'produce vertex embeddings as an NxD tensor for a named mesh via the Embedder forward method', 'check whether an Embedder has registered embeddings for a given mesh name using has_embeddings', 'build a python module that computes pairwise squared Euclidean distances between two sets of points', 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test the function that interpolates embeddings and segmentations to find closest mesh vertices', 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize the function that computes closest vertices and segmentation masks from interpolated embeddings', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load precomputed vertex embeddings from a pickle file into the embedder', 'use normalize_embeddings utility to L2-normalize a tensor of embedding vectors', 'create a VertexFeatureEmbedder with num_vertices, feature_dim, and embed_dim parameters', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder instance', 'review the VertexFeatureEmbedder class and its forward pass that computes normalized embeddings']
```

Usage

```
{'create_embedder_from_config': 'create a VertexDirectEmbedder or VertexFeatureEmbedder from a CfgNode spec and embedding dimension', 'build_embedder_module': 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load_embedder_checkpoint': 'load embedder state dict from a pkl or torch checkpoint file with a configurable key prefix', 'forward_vertex_embeddings': 'produce vertex embeddings as an NxD tensor for a named mesh via the Embedder forward method', 'check_mesh_embeddings': 'check whether an Embedder has registered embeddings for a given mesh name using has_embeddings'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/cse/utils.py

Prompts

```
['create a VertexDirectEmbedder or VertexFeatureEmbedder from a CfgNode spec and embedding dimension', 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load embedder state dict from a pkl or torch checkpoint file with a configurable key prefix', 'produce vertex embeddings as an NxD tensor for a named mesh via the Embedder forward method', 'check whether an Embedder has registered embeddings for a given mesh name using has_embeddings', 'build a python module that computes pairwise squared Euclidean distances between two sets of points', 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test the function that interpolates embeddings and segmentations to find closest mesh vertices', 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize the function that computes closest vertices and segmentation masks from interpolated embeddings', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load precomputed vertex embeddings from a pickle file into the embedder', 'use normalize_embeddings utility to L2-normalize a tensor of embedding vectors', 'create a VertexFeatureEmbedder with num_vertices, feature_dim, and embed_dim parameters', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder instance', 'review the VertexFeatureEmbedder class and its forward pass that computes normalized embeddings']
```

Usage

```
{'build_squared_euclidean_distance_matrix': 'build a python module that computes pairwise squared Euclidean distances between two sets of points', 'create_normalize_embeddings': 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test_get_closest_vertices_mask_from_ES': 'test the function that interpolates embeddings and segmentations to find closest mesh vertices', 'refactor_squared_euclidean_distance_matrix': 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize_get_closest_vertices_mask_from_ES': 'summarize the function that computes closest vertices and segmentation masks from interpolated embeddings'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/cse/vertex_direct_embedder.py

Prompts

```
['create a VertexDirectEmbedder or VertexFeatureEmbedder from a CfgNode spec and embedding dimension', 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load embedder state dict from a pkl or torch checkpoint file with a configurable key prefix', 'produce vertex embeddings as an NxD tensor for a named mesh via the Embedder forward method', 'check whether an Embedder has registered embeddings for a given mesh name using has_embeddings', 'build a python module that computes pairwise squared Euclidean distances between two sets of points', 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test the function that interpolates embeddings and segmentations to find closest mesh vertices', 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize the function that computes closest vertices and segmentation masks from interpolated embeddings', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load precomputed vertex embeddings from a pickle file into the embedder', 'use normalize_embeddings utility to L2-normalize a tensor of embedding vectors', 'create a VertexFeatureEmbedder with num_vertices, feature_dim, and embed_dim parameters', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder instance', 'review the VertexFeatureEmbedder class and its forward pass that computes normalized embeddings']
```

Usage

```
{'create_vertex_direct_embedder': 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset_embedder_parameters': 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'forward_normalized_embeddings': 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load_embeddings_from_file': 'load precomputed vertex embeddings from a pickle file into the embedder', 'normalize_embedding_vectors': 'use normalize_embeddings utility to L2-normalize a tensor of embedding vectors'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/cse/vertex_feature_embedder.py

Prompts

```
['create a VertexDirectEmbedder or VertexFeatureEmbedder from a CfgNode spec and embedding dimension', 'build an Embedder nn.Module from a Detectron2 config that registers embedders for multiple meshes', 'load embedder state dict from a pkl or torch checkpoint file with a configurable key prefix', 'produce vertex embeddings as an NxD tensor for a named mesh via the Embedder forward method', 'check whether an Embedder has registered embeddings for a given mesh name using has_embeddings', 'build a python module that computes pairwise squared Euclidean distances between two sets of points', 'create a function that normalizes N D-dimensional embedding vectors to unit L2 norm', 'test the function that interpolates embeddings and segmentations to find closest mesh vertices', 'refactor the squared Euclidean distance matrix computation to support batched tensor inputs', 'summarize the function that computes closest vertices and segmentation masks from interpolated embeddings', 'create a VertexDirectEmbedder with a given number of vertices and embedding dimensions', 'reset the VertexDirectEmbedder embeddings to zero using reset_parameters', 'call forward on VertexDirectEmbedder to get L2-normalized vertex embeddings as a tensor', 'load precomputed vertex embeddings from a pickle file into the embedder', 'use normalize_embeddings utility to L2-normalize a tensor of embedding vectors', 'create a VertexFeatureEmbedder with num_vertices, feature_dim, and embed_dim parameters', 'build vertex embeddings by calling forward on a VertexFeatureEmbedder instance', 'review the VertexFeatureEmbedder class and its forward pass that computes normalized embeddings']
```

Usage

```
{'create_VertexFeatureEmbedder': 'create a VertexFeatureEmbedder with num_vertices, feature_dim, and embed_dim parameters', 'build_vertex_embeddings': 'build vertex embeddings by calling forward on a VertexFeatureEmbedder instance', 'load_embeddings_from_file': 'load precomputed features and embeddings into a VertexFeatureEmbedder from a pickle file', 'reset_embedder_parameters': 'reset all features and embeddings in a VertexFeatureEmbedder to zero', 'review_VertexFeatureEmbedder_class': 'review the VertexFeatureEmbedder class and its forward pass that computes normalized embeddings'}
```

