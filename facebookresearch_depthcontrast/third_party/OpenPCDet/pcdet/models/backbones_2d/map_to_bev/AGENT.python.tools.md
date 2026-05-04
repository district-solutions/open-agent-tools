# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/backbones_2d/map_to_bev/height_compression.py

Prompts

```
['build a python module using HeightCompression to compress 3D sparse tensor height dimension into 2D BEV features', 'create a forward pass that converts encoded sparse conv tensor to dense spatial features with flattened height channel', 'test the HeightCompression forward method by passing a batch_dict with encoded_spconv_tensor and verifying spatial_features output', 'review the HeightCompression class to understand how it compresses the depth dimension into BEV feature channels', 'refactor the HeightCompression forward method to add custom stride handling for spatial_features_stride in the batch_dict', 'create a PointPillarScatter module with a model config and grid size for BEV feature scattering', 'run the PointPillarScatter forward pass on a batch dict containing pillar features and voxel coordinates', 'build a BEV spatial feature tensor from pillar features and voxel coordinates using PointPillarScatter', 'review the PointPillarScatter scatter logic that maps 3D pillar features to a 2D BEV grid', 'refactor the PointPillarScatter forward method batch loop to vectorize the per-batch spatial feature scattering']
```

Usage

```
{'build_HeightCompression_module': 'build a python module using HeightCompression to compress 3D sparse tensor height dimension into 2D BEV features', 'create_forward_pass': 'create a forward pass that converts encoded sparse conv tensor to dense spatial features with flattened height channel', 'test_HeightCompression_forward': 'test the HeightCompression forward method by passing a batch_dict with encoded_spconv_tensor and verifying spatial_features output', 'review_HeightCompression_class': 'review the HeightCompression class to understand how it compresses the depth dimension into BEV feature channels', 'refactor_HeightCompression_stride': 'refactor the HeightCompression forward method to add custom stride handling for spatial_features_stride in the batch_dict'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/backbones_2d/map_to_bev/pointpillar_scatter.py

Prompts

```
['build a python module using HeightCompression to compress 3D sparse tensor height dimension into 2D BEV features', 'create a forward pass that converts encoded sparse conv tensor to dense spatial features with flattened height channel', 'test the HeightCompression forward method by passing a batch_dict with encoded_spconv_tensor and verifying spatial_features output', 'review the HeightCompression class to understand how it compresses the depth dimension into BEV feature channels', 'refactor the HeightCompression forward method to add custom stride handling for spatial_features_stride in the batch_dict', 'create a PointPillarScatter module with a model config and grid size for BEV feature scattering', 'run the PointPillarScatter forward pass on a batch dict containing pillar features and voxel coordinates', 'build a BEV spatial feature tensor from pillar features and voxel coordinates using PointPillarScatter', 'review the PointPillarScatter scatter logic that maps 3D pillar features to a 2D BEV grid', 'refactor the PointPillarScatter forward method batch loop to vectorize the per-batch spatial feature scattering']
```

Usage

```
{'create_PointPillarScatter': 'create a PointPillarScatter module with a model config and grid size for BEV feature scattering', 'run_PointPillarScatter_forward': 'run the PointPillarScatter forward pass on a batch dict containing pillar features and voxel coordinates', 'build_PointPillarScatter_BEV': 'build a BEV spatial feature tensor from pillar features and voxel coordinates using PointPillarScatter', 'review_PointPillarScatter_scatter_logic': 'review the PointPillarScatter scatter logic that maps 3D pillar features to a 2D BEV grid', 'refactor_PointPillarScatter_batch_loop': 'refactor the PointPillarScatter forward method batch loop to vectorize the per-batch spatial feature scattering'}
```

