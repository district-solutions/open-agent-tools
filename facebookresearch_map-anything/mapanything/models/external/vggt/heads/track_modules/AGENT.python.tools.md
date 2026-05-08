# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/mapanything/models/external/vggt/heads/track_modules/base_track_predictor.py

Prompts

```
['build a BaseTrackerPredictor model with configurable correlation levels, radius, and latent dimension for visual tracking', 'run the BaseTrackerPredictor forward pass with query points and feature maps to predict tracked coordinates', 'test the visibility predictor head to output per-point visibility scores across video frames', 'review the correlation MLP that processes multi-level correlation features into latent embeddings', 'refactor the EfficientUpdateFormer to adjust spatial and temporal attention depth for tracking refinement', 'build an EfficientUpdateFormer transformer model to update track estimates with spatial and temporal attention blocks', 'create a CorrBlock to build a feature map pyramid and sample correlation volumes for tracking', 'run compute_corr_level to compute normalized correlation between target features and spatial feature maps', 'review the EfficientUpdateFormer forward pass that processes input tensors through time and space attention blocks', 'test the CorrBlock corr_sample method that samples correlation volumes using bilinear interpolation across pyramid levels', 'build a ResidualBlock with two conv layers, residual connections, and configurable group or batch normalization', 'create an MLP module with GELU activation and dropout for Vision Transformer networks', 'build an AttnBlock with self-attention, LayerNorm, and an MLP for transformer-style feature processing', 'create a CrossAttnBlock that applies cross-attention between query features and context features with masking', 'refactor the ResidualBlock to switch between group, batch, instance, or no normalization via the norm_fn parameter', 'generate a 2D sine-cosine positional embedding tensor from a given grid size and embedding dimension', 'create a 2D positional embedding from batched coordinate tensors with optional coordinate concatenation', 'sample a tensor at arbitrary coordinates using bilinear interpolation with grid sample', 'sample spatial features from a 4D tensor at given 2D coordinate points using bilinear interpolation', 'generate a 1D sine-cosine positional embedding from a position tensor for encoding spatial axes']
```

Usage

```
{'build_BaseTrackerPredictor': 'build a BaseTrackerPredictor model with configurable correlation levels, radius, and latent dimension for visual tracking', 'run_BaseTrackerPredictor_forward': 'run the BaseTrackerPredictor forward pass with query points and feature maps to predict tracked coordinates', 'test_BaseTrackerPredictor_vis_predictor': 'test the visibility predictor head to output per-point visibility scores across video frames', 'review_BaseTrackerPredictor_corr_mlp': 'review the correlation MLP that processes multi-level correlation features into latent embeddings', 'refactor_BaseTrackerPredictor_updateformer': 'refactor the EfficientUpdateFormer to adjust spatial and temporal attention depth for tracking refinement'}
```

## File: facebookresearch_map-anything/mapanything/models/external/vggt/heads/track_modules/blocks.py

Prompts

```
['build a BaseTrackerPredictor model with configurable correlation levels, radius, and latent dimension for visual tracking', 'run the BaseTrackerPredictor forward pass with query points and feature maps to predict tracked coordinates', 'test the visibility predictor head to output per-point visibility scores across video frames', 'review the correlation MLP that processes multi-level correlation features into latent embeddings', 'refactor the EfficientUpdateFormer to adjust spatial and temporal attention depth for tracking refinement', 'build an EfficientUpdateFormer transformer model to update track estimates with spatial and temporal attention blocks', 'create a CorrBlock to build a feature map pyramid and sample correlation volumes for tracking', 'run compute_corr_level to compute normalized correlation between target features and spatial feature maps', 'review the EfficientUpdateFormer forward pass that processes input tensors through time and space attention blocks', 'test the CorrBlock corr_sample method that samples correlation volumes using bilinear interpolation across pyramid levels', 'build a ResidualBlock with two conv layers, residual connections, and configurable group or batch normalization', 'create an MLP module with GELU activation and dropout for Vision Transformer networks', 'build an AttnBlock with self-attention, LayerNorm, and an MLP for transformer-style feature processing', 'create a CrossAttnBlock that applies cross-attention between query features and context features with masking', 'refactor the ResidualBlock to switch between group, batch, instance, or no normalization via the norm_fn parameter', 'generate a 2D sine-cosine positional embedding tensor from a given grid size and embedding dimension', 'create a 2D positional embedding from batched coordinate tensors with optional coordinate concatenation', 'sample a tensor at arbitrary coordinates using bilinear interpolation with grid sample', 'sample spatial features from a 4D tensor at given 2D coordinate points using bilinear interpolation', 'generate a 1D sine-cosine positional embedding from a position tensor for encoding spatial axes']
```

Usage

```
{'build_EfficientUpdateFormer': 'build an EfficientUpdateFormer transformer model to update track estimates with spatial and temporal attention blocks', 'create_CorrBlock': 'create a CorrBlock to build a feature map pyramid and sample correlation volumes for tracking', 'run_compute_corr_level': 'run compute_corr_level to compute normalized correlation between target features and spatial feature maps', 'review_EfficientUpdateFormer_forward': 'review the EfficientUpdateFormer forward pass that processes input tensors through time and space attention blocks', 'test_CorrBlock_corr_sample': 'test the CorrBlock corr_sample method that samples correlation volumes using bilinear interpolation across pyramid levels'}
```

## File: facebookresearch_map-anything/mapanything/models/external/vggt/heads/track_modules/modules.py

Prompts

```
['build a BaseTrackerPredictor model with configurable correlation levels, radius, and latent dimension for visual tracking', 'run the BaseTrackerPredictor forward pass with query points and feature maps to predict tracked coordinates', 'test the visibility predictor head to output per-point visibility scores across video frames', 'review the correlation MLP that processes multi-level correlation features into latent embeddings', 'refactor the EfficientUpdateFormer to adjust spatial and temporal attention depth for tracking refinement', 'build an EfficientUpdateFormer transformer model to update track estimates with spatial and temporal attention blocks', 'create a CorrBlock to build a feature map pyramid and sample correlation volumes for tracking', 'run compute_corr_level to compute normalized correlation between target features and spatial feature maps', 'review the EfficientUpdateFormer forward pass that processes input tensors through time and space attention blocks', 'test the CorrBlock corr_sample method that samples correlation volumes using bilinear interpolation across pyramid levels', 'build a ResidualBlock with two conv layers, residual connections, and configurable group or batch normalization', 'create an MLP module with GELU activation and dropout for Vision Transformer networks', 'build an AttnBlock with self-attention, LayerNorm, and an MLP for transformer-style feature processing', 'create a CrossAttnBlock that applies cross-attention between query features and context features with masking', 'refactor the ResidualBlock to switch between group, batch, instance, or no normalization via the norm_fn parameter', 'generate a 2D sine-cosine positional embedding tensor from a given grid size and embedding dimension', 'create a 2D positional embedding from batched coordinate tensors with optional coordinate concatenation', 'sample a tensor at arbitrary coordinates using bilinear interpolation with grid sample', 'sample spatial features from a 4D tensor at given 2D coordinate points using bilinear interpolation', 'generate a 1D sine-cosine positional embedding from a position tensor for encoding spatial axes']
```

Usage

```
{'build_residual_block': 'build a ResidualBlock with two conv layers, residual connections, and configurable group or batch normalization', 'create_mlp': 'create an MLP module with GELU activation and dropout for Vision Transformer networks', 'build_attn_block': 'build an AttnBlock with self-attention, LayerNorm, and an MLP for transformer-style feature processing', 'create_cross_attn_block': 'create a CrossAttnBlock that applies cross-attention between query features and context features with masking', 'refactor_norm_fn': 'refactor the ResidualBlock to switch between group, batch, instance, or no normalization via the norm_fn parameter'}
```

## File: facebookresearch_map-anything/mapanything/models/external/vggt/heads/track_modules/utils.py

Prompts

```
['build a BaseTrackerPredictor model with configurable correlation levels, radius, and latent dimension for visual tracking', 'run the BaseTrackerPredictor forward pass with query points and feature maps to predict tracked coordinates', 'test the visibility predictor head to output per-point visibility scores across video frames', 'review the correlation MLP that processes multi-level correlation features into latent embeddings', 'refactor the EfficientUpdateFormer to adjust spatial and temporal attention depth for tracking refinement', 'build an EfficientUpdateFormer transformer model to update track estimates with spatial and temporal attention blocks', 'create a CorrBlock to build a feature map pyramid and sample correlation volumes for tracking', 'run compute_corr_level to compute normalized correlation between target features and spatial feature maps', 'review the EfficientUpdateFormer forward pass that processes input tensors through time and space attention blocks', 'test the CorrBlock corr_sample method that samples correlation volumes using bilinear interpolation across pyramid levels', 'build a ResidualBlock with two conv layers, residual connections, and configurable group or batch normalization', 'create an MLP module with GELU activation and dropout for Vision Transformer networks', 'build an AttnBlock with self-attention, LayerNorm, and an MLP for transformer-style feature processing', 'create a CrossAttnBlock that applies cross-attention between query features and context features with masking', 'refactor the ResidualBlock to switch between group, batch, instance, or no normalization via the norm_fn parameter', 'generate a 2D sine-cosine positional embedding tensor from a given grid size and embedding dimension', 'create a 2D positional embedding from batched coordinate tensors with optional coordinate concatenation', 'sample a tensor at arbitrary coordinates using bilinear interpolation with grid sample', 'sample spatial features from a 4D tensor at given 2D coordinate points using bilinear interpolation', 'generate a 1D sine-cosine positional embedding from a position tensor for encoding spatial axes']
```

Usage

```
{'get_2d_sincos_pos_embed': 'generate a 2D sine-cosine positional embedding tensor from a given grid size and embedding dimension', 'get_2d_embedding': 'create a 2D positional embedding from batched coordinate tensors with optional coordinate concatenation', 'bilinear_sampler': 'sample a tensor at arbitrary coordinates using bilinear interpolation with grid sample', 'sample_features4d': 'sample spatial features from a 4D tensor at given 2D coordinate points using bilinear interpolation', 'get_1d_sincos_pos_embed_from_grid': 'generate a 1D sine-cosine positional embedding from a position tensor for encoding spatial axes'}
```

