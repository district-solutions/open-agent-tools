# Agent Python Tools

- repo: facebookresearch/co-tracker
- repo_uri: https://github.com/facebookresearch/co-tracker

## File: facebookresearch_co-tracker/cotracker/models/core/embeddings.py

Prompts

```
['generate a 2D positional embedding from a grid size using get_2d_sincos_pos_embed', 'generate a 2D positional embedding from batched XY coordinates using get_2d_embedding', 'generate a 1D positional embedding from position values using get_1d_sincos_pos_embed_from_grid', 'generate a 2D positional embedding from a pre-built grid tensor using get_2d_sincos_pos_embed_from_grid', 'review the sincos positional embedding functions for use in vision transformer models', 'generate uniformly sampled spatiotemporal points across video frames with random time and spatial coordinates', 'generate a grid of uniformly distributed 2D points covering a rectangular region with configurable margin', 'sample spatial features from a 4D tensor at specified 2D coordinates using bilinear interpolation', 'sample spatio-temporal features from a 5D tensor at specified 3D coordinates using bilinear interpolation', 'compute the mean of a tensor weighted by a mask tensor along a specified dimension']
```

Usage

```
{'generate_2d_sincos_grid_embedding': 'generate a 2D positional embedding from a grid size using get_2d_sincos_pos_embed', 'generate_2d_embedding_from_coords': 'generate a 2D positional embedding from batched XY coordinates using get_2d_embedding', 'generate_1d_sincos_embedding': 'generate a 1D positional embedding from position values using get_1d_sincos_pos_embed_from_grid', 'generate_2d_embedding_from_grid_tensor': 'generate a 2D positional embedding from a pre-built grid tensor using get_2d_sincos_pos_embed_from_grid', 'review_sincos_embedding_functions': 'review the sincos positional embedding functions for use in vision transformer models'}
```

## File: facebookresearch_co-tracker/cotracker/models/core/model_utils.py

Prompts

```
['generate a 2D positional embedding from a grid size using get_2d_sincos_pos_embed', 'generate a 2D positional embedding from batched XY coordinates using get_2d_embedding', 'generate a 1D positional embedding from position values using get_1d_sincos_pos_embed_from_grid', 'generate a 2D positional embedding from a pre-built grid tensor using get_2d_sincos_pos_embed_from_grid', 'review the sincos positional embedding functions for use in vision transformer models', 'generate uniformly sampled spatiotemporal points across video frames with random time and spatial coordinates', 'generate a grid of uniformly distributed 2D points covering a rectangular region with configurable margin', 'sample spatial features from a 4D tensor at specified 2D coordinates using bilinear interpolation', 'sample spatio-temporal features from a 5D tensor at specified 3D coordinates using bilinear interpolation', 'compute the mean of a tensor weighted by a mask tensor along a specified dimension']
```

Usage

```
{'generate_uniform_sampled_points': 'generate uniformly sampled spatiotemporal points across video frames with random time and spatial coordinates', 'generate_grid_points': 'generate a grid of uniformly distributed 2D points covering a rectangular region with configurable margin', 'sample_spatial_features': 'sample spatial features from a 4D tensor at specified 2D coordinates using bilinear interpolation', 'sample_spatiotemporal_features': 'sample spatio-temporal features from a 5D tensor at specified 3D coordinates using bilinear interpolation', 'compute_masked_mean': 'compute the mean of a tensor weighted by a mask tensor along a specified dimension'}
```

