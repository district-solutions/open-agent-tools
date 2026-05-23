# Agent Python Tools

- repo: facebookresearch/omnivore
- repo_uri: https://github.com/facebookresearch/omnivore

## File: facebookresearch_omnivore/omnivision/models/swin_transformer.py

Prompts

```
['build a SwinTransformer3D backbone with configurable depths, num_heads, and window_size for video feature extraction', 'create a PatchEmbed3D layer to convert video frames into non-overlapping patch tokens with optional depth channel support', 'run WindowAttention3D to compute multi-head self-attention with relative position bias over 3D spatiotemporal windows', 'test SwinTransformerBlock3D forward pass with shifted window partitioning, cyclic shift, and attention masking', 'review BasicLayer forward method that iterates over SwinTransformerBlock3D blocks with optional gradient checkpointing and downsampling', 'build a VisionTransformer model with configurable patch size, depth, and embedding dimension for image classification', 'create a transformer Block with optional layer scale gamma parameters for stable training', 'test the PatchEmbed module to convert images into patch embeddings with configurable patch size', 'review the Decoder forward pass that processes patch embeddings with optional checkpointing and interim layer output', 'summarize the interpolate_pos_encoding method that resizes positional embeddings for variable input resolutions']
```

Usage

```
{'build_swin3d_backbone': 'build a SwinTransformer3D backbone with configurable depths, num_heads, and window_size for video feature extraction', 'create_patch_embedding': 'create a PatchEmbed3D layer to convert video frames into non-overlapping patch tokens with optional depth channel support', 'run_window_attention_3d': 'run WindowAttention3D to compute multi-head self-attention with relative position bias over 3D spatiotemporal windows', 'test_swin_transformer_block_3d': 'test SwinTransformerBlock3D forward pass with shifted window partitioning, cyclic shift, and attention masking', 'review_basic_layer_forward': 'review BasicLayer forward method that iterates over SwinTransformerBlock3D blocks with optional gradient checkpointing and downsampling'}
```

## File: facebookresearch_omnivore/omnivision/models/vision_transformer.py

Prompts

```
['build a SwinTransformer3D backbone with configurable depths, num_heads, and window_size for video feature extraction', 'create a PatchEmbed3D layer to convert video frames into non-overlapping patch tokens with optional depth channel support', 'run WindowAttention3D to compute multi-head self-attention with relative position bias over 3D spatiotemporal windows', 'test SwinTransformerBlock3D forward pass with shifted window partitioning, cyclic shift, and attention masking', 'review BasicLayer forward method that iterates over SwinTransformerBlock3D blocks with optional gradient checkpointing and downsampling', 'build a VisionTransformer model with configurable patch size, depth, and embedding dimension for image classification', 'create a transformer Block with optional layer scale gamma parameters for stable training', 'test the PatchEmbed module to convert images into patch embeddings with configurable patch size', 'review the Decoder forward pass that processes patch embeddings with optional checkpointing and interim layer output', 'summarize the interpolate_pos_encoding method that resizes positional embeddings for variable input resolutions']
```

Usage

```
{'build_VisionTransformer': 'build a VisionTransformer model with configurable patch size, depth, and embedding dimension for image classification', 'create_Block_with_layerscale': 'create a transformer Block with optional layer scale gamma parameters for stable training', 'test_PatchEmbed': 'test the PatchEmbed module to convert images into patch embeddings with configurable patch size', 'review_Decoder_forward': 'review the Decoder forward pass that processes patch embeddings with optional checkpointing and interim layer output', 'summarize_interpolate_pos_encoding': 'summarize the interpolate_pos_encoding method that resizes positional embeddings for variable input resolutions'}
```

