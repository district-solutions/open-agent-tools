# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/models/middle_encoders/pillar_scatter.py

Prompts

```
['build a PointPillarsScatter module to scatter voxel features into a pseudo image tensor', 'create a forward pass that scatters single sample voxel features to a 2D canvas', 'create a batched forward pass that scatters voxel features for multiple samples at once', 'test the PointPillarsScatter forward method with voxel features and coordinates to verify scattering', 'review the PointPillarsScatter class and its auto fp16 support for mixed precision training', 'build a SparseEncoder with custom in_channels, sparse_shape, and encoder_channels for 3D detection', 'run the SparseEncoder forward pass with voxel_features, coordinates, and batch_size inputs', 'create encoder layers using make_encoder_layers with SubMConv3d or SparseConv3d block types', 'review the SparseEncoder __init__ to understand conv_input, conv_out, and encoder layer configuration', 'refactor the SparseEncoder encoder_channels and encoder_paddings tuples to adjust network depth and capacity', 'build a SparseUNet model with custom encoder and decoder channel configurations for 3D detection', 'run the SparseUNet forward pass with voxel features, coordinates, and batch size inputs', 'create decoder layers using make_decoder_layers with lateral, merge, and upsample sparse conv modules', 'test the decoder_layer_forward method with lateral and bottom sparse tensor features']
```

Usage

```
{'build_PointPillarsScatter': 'build a PointPillarsScatter module to scatter voxel features into a pseudo image tensor', 'create_forward_single': 'create a forward pass that scatters single sample voxel features to a 2D canvas', 'create_forward_batch': 'create a batched forward pass that scatters voxel features for multiple samples at once', 'test_PointPillarsScatter_forward': 'test the PointPillarsScatter forward method with voxel features and coordinates to verify scattering', 'review_PointPillarsScatter_fp16': 'review the PointPillarsScatter class and its auto fp16 support for mixed precision training'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/middle_encoders/sparse_encoder.py

Prompts

```
['build a PointPillarsScatter module to scatter voxel features into a pseudo image tensor', 'create a forward pass that scatters single sample voxel features to a 2D canvas', 'create a batched forward pass that scatters voxel features for multiple samples at once', 'test the PointPillarsScatter forward method with voxel features and coordinates to verify scattering', 'review the PointPillarsScatter class and its auto fp16 support for mixed precision training', 'build a SparseEncoder with custom in_channels, sparse_shape, and encoder_channels for 3D detection', 'run the SparseEncoder forward pass with voxel_features, coordinates, and batch_size inputs', 'create encoder layers using make_encoder_layers with SubMConv3d or SparseConv3d block types', 'review the SparseEncoder __init__ to understand conv_input, conv_out, and encoder layer configuration', 'refactor the SparseEncoder encoder_channels and encoder_paddings tuples to adjust network depth and capacity', 'build a SparseUNet model with custom encoder and decoder channel configurations for 3D detection', 'run the SparseUNet forward pass with voxel features, coordinates, and batch size inputs', 'create decoder layers using make_decoder_layers with lateral, merge, and upsample sparse conv modules', 'test the decoder_layer_forward method with lateral and bottom sparse tensor features']
```

Usage

```
{'build_sparse_encoder': 'build a SparseEncoder with custom in_channels, sparse_shape, and encoder_channels for 3D detection', 'run_sparse_encoder_forward': 'run the SparseEncoder forward pass with voxel_features, coordinates, and batch_size inputs', 'create_encoder_layers': 'create encoder layers using make_encoder_layers with SubMConv3d or SparseConv3d block types', 'review_sparse_encoder_init': 'review the SparseEncoder __init__ to understand conv_input, conv_out, and encoder layer configuration', 'refactor_encoder_channels': 'refactor the SparseEncoder encoder_channels and encoder_paddings tuples to adjust network depth and capacity'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/middle_encoders/sparse_unet.py

Prompts

```
['build a PointPillarsScatter module to scatter voxel features into a pseudo image tensor', 'create a forward pass that scatters single sample voxel features to a 2D canvas', 'create a batched forward pass that scatters voxel features for multiple samples at once', 'test the PointPillarsScatter forward method with voxel features and coordinates to verify scattering', 'review the PointPillarsScatter class and its auto fp16 support for mixed precision training', 'build a SparseEncoder with custom in_channels, sparse_shape, and encoder_channels for 3D detection', 'run the SparseEncoder forward pass with voxel_features, coordinates, and batch_size inputs', 'create encoder layers using make_encoder_layers with SubMConv3d or SparseConv3d block types', 'review the SparseEncoder __init__ to understand conv_input, conv_out, and encoder layer configuration', 'refactor the SparseEncoder encoder_channels and encoder_paddings tuples to adjust network depth and capacity', 'build a SparseUNet model with custom encoder and decoder channel configurations for 3D detection', 'run the SparseUNet forward pass with voxel features, coordinates, and batch size inputs', 'create decoder layers using make_decoder_layers with lateral, merge, and upsample sparse conv modules', 'test the decoder_layer_forward method with lateral and bottom sparse tensor features']
```

Usage

```
{'build_sparse_unet_model': 'build a SparseUNet model with custom encoder and decoder channel configurations for 3D detection', 'run_forward_sparse_unet': 'run the SparseUNet forward pass with voxel features, coordinates, and batch size inputs', 'create_encoder_layers': 'create encoder layers using make_encoder_layers with sparse convolutions and configurable channel depths', 'create_decoder_layers': 'create decoder layers using make_decoder_layers with lateral, merge, and upsample sparse conv modules', 'test_decoder_layer_forward': 'test the decoder_layer_forward method with lateral and bottom sparse tensor features'}
```

