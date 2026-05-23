# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/dit/embedder/dino.py

Prompts

```
['build a frozen DINO ViT backbone wrapper that loads dinov2_vitb14 via torch hub', 'create a forward pass that preprocesses images and extracts normalized patch tokens from DINO', 'create a forward pass that extracts intermediate layer features from the DINO backbone', 'create a DinoForMasks module that wraps a Dino backbone to extract features from masks', 'refactor the Dino class to prune unused mask token and norm parameters for training', 'create an EmbedderFuser instance with a list of condition embedders and positional embedding configuration', 'build a projection network with LayerNorm and FeedForward layers for token dimension transformation', 'test the EmbedderFuser forward pass by passing condition kwargs and verifying concatenated token output', 'review the _dropout_modalities method to understand how probabilistic and forced modality dropout are applied', 'refactor the _build_dropout_distribution method to customize probability distribution for modality dropout sampling', 'create a PointRemapper with exp remap type to transform 3D point coordinates using log1p on z', 'create a PointRemapper with sinh remap type to apply asinh transformation to all point coordinates', 'forward pass 3D point tensor through PointRemapper to apply the configured coordinate remapping', 'call inverse on PointRemapper to recover original 3D point coordinates from remapped space', 'review the PointRemapper VALID_TYPES list to see supported remap strategies like linear sinh and exp', 'build a PointPatchEmbed module that projects 3D pointmaps into patch window embeddings using self-attention', 'test the PointPatchEmbed forward method with a batch of (B, 3, H, W) xyz coordinate tensors', 'refactor the apply_pointmap_dropout method to support per-window dropout instead of full batch dropout', 'review the embed_pointmap_windows method that resizes inputs, remaps points, and projects to embedding space', 'summarize the inner_forward method that reshapes patches, adds CLS tokens, runs intra-window attention, and applies positional embeddings']
```

Usage

```
{'build_dino_backbone': 'build a frozen DINO ViT backbone wrapper that loads dinov2_vitb14 via torch hub', 'create_dino_forward_features': 'create a forward pass that preprocesses images and extracts normalized patch tokens from DINO', 'create_dino_intermediate_layers': 'create a forward pass that extracts intermediate layer features from the DINO backbone', 'create_dino_for_masks': 'create a DinoForMasks module that wraps a Dino backbone to extract features from masks', 'refactor_dino_prune_network': 'refactor the Dino class to prune unused mask token and norm parameters for training'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/dit/embedder/embedder_fuser.py

Prompts

```
['build a frozen DINO ViT backbone wrapper that loads dinov2_vitb14 via torch hub', 'create a forward pass that preprocesses images and extracts normalized patch tokens from DINO', 'create a forward pass that extracts intermediate layer features from the DINO backbone', 'create a DinoForMasks module that wraps a Dino backbone to extract features from masks', 'refactor the Dino class to prune unused mask token and norm parameters for training', 'create an EmbedderFuser instance with a list of condition embedders and positional embedding configuration', 'build a projection network with LayerNorm and FeedForward layers for token dimension transformation', 'test the EmbedderFuser forward pass by passing condition kwargs and verifying concatenated token output', 'review the _dropout_modalities method to understand how probabilistic and forced modality dropout are applied', 'refactor the _build_dropout_distribution method to customize probability distribution for modality dropout sampling', 'create a PointRemapper with exp remap type to transform 3D point coordinates using log1p on z', 'create a PointRemapper with sinh remap type to apply asinh transformation to all point coordinates', 'forward pass 3D point tensor through PointRemapper to apply the configured coordinate remapping', 'call inverse on PointRemapper to recover original 3D point coordinates from remapped space', 'review the PointRemapper VALID_TYPES list to see supported remap strategies like linear sinh and exp', 'build a PointPatchEmbed module that projects 3D pointmaps into patch window embeddings using self-attention', 'test the PointPatchEmbed forward method with a batch of (B, 3, H, W) xyz coordinate tensors', 'refactor the apply_pointmap_dropout method to support per-window dropout instead of full batch dropout', 'review the embed_pointmap_windows method that resizes inputs, remaps points, and projects to embedding space', 'summarize the inner_forward method that reshapes patches, adds CLS tokens, runs intra-window attention, and applies positional embeddings']
```

Usage

```
{'create_EmbedderFuser': 'create an EmbedderFuser instance with a list of condition embedders and positional embedding configuration', 'build_projection_net': 'build a projection network with LayerNorm and FeedForward layers for token dimension transformation', 'test_forward_pass': 'test the EmbedderFuser forward pass by passing condition kwargs and verifying concatenated token output', 'review_dropout_modalities': 'review the _dropout_modalities method to understand how probabilistic and forced modality dropout are applied', 'refactor_build_dropout_distribution': 'refactor the _build_dropout_distribution method to customize probability distribution for modality dropout sampling'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/dit/embedder/point_remapper.py

Prompts

```
['build a frozen DINO ViT backbone wrapper that loads dinov2_vitb14 via torch hub', 'create a forward pass that preprocesses images and extracts normalized patch tokens from DINO', 'create a forward pass that extracts intermediate layer features from the DINO backbone', 'create a DinoForMasks module that wraps a Dino backbone to extract features from masks', 'refactor the Dino class to prune unused mask token and norm parameters for training', 'create an EmbedderFuser instance with a list of condition embedders and positional embedding configuration', 'build a projection network with LayerNorm and FeedForward layers for token dimension transformation', 'test the EmbedderFuser forward pass by passing condition kwargs and verifying concatenated token output', 'review the _dropout_modalities method to understand how probabilistic and forced modality dropout are applied', 'refactor the _build_dropout_distribution method to customize probability distribution for modality dropout sampling', 'create a PointRemapper with exp remap type to transform 3D point coordinates using log1p on z', 'create a PointRemapper with sinh remap type to apply asinh transformation to all point coordinates', 'forward pass 3D point tensor through PointRemapper to apply the configured coordinate remapping', 'call inverse on PointRemapper to recover original 3D point coordinates from remapped space', 'review the PointRemapper VALID_TYPES list to see supported remap strategies like linear sinh and exp', 'build a PointPatchEmbed module that projects 3D pointmaps into patch window embeddings using self-attention', 'test the PointPatchEmbed forward method with a batch of (B, 3, H, W) xyz coordinate tensors', 'refactor the apply_pointmap_dropout method to support per-window dropout instead of full batch dropout', 'review the embed_pointmap_windows method that resizes inputs, remaps points, and projects to embedding space', 'summarize the inner_forward method that reshapes patches, adds CLS tokens, runs intra-window attention, and applies positional embeddings']
```

Usage

```
{'create_PointRemapper_exp': 'create a PointRemapper with exp remap type to transform 3D point coordinates using log1p on z', 'create_PointRemapper_sinh': 'create a PointRemapper with sinh remap type to apply asinh transformation to all point coordinates', 'forward_PointRemapper': 'forward pass 3D point tensor through PointRemapper to apply the configured coordinate remapping', 'inverse_PointRemapper': 'call inverse on PointRemapper to recover original 3D point coordinates from remapped space', 'review_PointRemapper_valid_types': 'review the PointRemapper VALID_TYPES list to see supported remap strategies like linear sinh and exp'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/dit/embedder/pointmap.py

Prompts

```
['build a frozen DINO ViT backbone wrapper that loads dinov2_vitb14 via torch hub', 'create a forward pass that preprocesses images and extracts normalized patch tokens from DINO', 'create a forward pass that extracts intermediate layer features from the DINO backbone', 'create a DinoForMasks module that wraps a Dino backbone to extract features from masks', 'refactor the Dino class to prune unused mask token and norm parameters for training', 'create an EmbedderFuser instance with a list of condition embedders and positional embedding configuration', 'build a projection network with LayerNorm and FeedForward layers for token dimension transformation', 'test the EmbedderFuser forward pass by passing condition kwargs and verifying concatenated token output', 'review the _dropout_modalities method to understand how probabilistic and forced modality dropout are applied', 'refactor the _build_dropout_distribution method to customize probability distribution for modality dropout sampling', 'create a PointRemapper with exp remap type to transform 3D point coordinates using log1p on z', 'create a PointRemapper with sinh remap type to apply asinh transformation to all point coordinates', 'forward pass 3D point tensor through PointRemapper to apply the configured coordinate remapping', 'call inverse on PointRemapper to recover original 3D point coordinates from remapped space', 'review the PointRemapper VALID_TYPES list to see supported remap strategies like linear sinh and exp', 'build a PointPatchEmbed module that projects 3D pointmaps into patch window embeddings using self-attention', 'test the PointPatchEmbed forward method with a batch of (B, 3, H, W) xyz coordinate tensors', 'refactor the apply_pointmap_dropout method to support per-window dropout instead of full batch dropout', 'review the embed_pointmap_windows method that resizes inputs, remaps points, and projects to embedding space', 'summarize the inner_forward method that reshapes patches, adds CLS tokens, runs intra-window attention, and applies positional embeddings']
```

Usage

```
{'build_PointPatchEmbed': 'build a PointPatchEmbed module that projects 3D pointmaps into patch window embeddings using self-attention', 'test_forward_pointmap': 'test the PointPatchEmbed forward method with a batch of (B, 3, H, W) xyz coordinate tensors', 'refactor_apply_pointmap_dropout': 'refactor the apply_pointmap_dropout method to support per-window dropout instead of full batch dropout', 'review_embed_pointmap_windows': 'review the embed_pointmap_windows method that resizes inputs, remaps points, and projects to embedding space', 'summarize_inner_forward': 'summarize the inner_forward method that reshapes patches, adds CLS tokens, runs intra-window attention, and applies positional embeddings'}
```

