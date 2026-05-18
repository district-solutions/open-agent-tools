# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/models/voxel_encoders/pillar_encoder.py

Prompts

```
['build a PillarFeatureNet module to encode 3D point cloud pillars into feature representations', 'build a DynamicPillarFeatureNet module to encode dynamic voxels with variable point counts', 'test PillarFeatureNet forward pass with point features, num_points tensor, and voxel coordinates', 'test DynamicPillarFeatureNet forward pass with raw point features and voxel coordinates', 'review DynamicPillarFeatureNet map_voxel_center_to_point method that maps voxel centers to individual points', 'create a boolean mask tensor indicating valid points in each padded voxel', 'build a Voxel Feature Encoder layer with linear projection, batch norm, and max pooling', 'run a VFELayer forward pass on voxel features with shape N, M, C', 'build a Pillar Feature Net layer supporting max or avg pooling modes', 'run a PFNLayer forward pass on pillar inputs with optional aligned distance weighting', 'build a HardSimpleVFE module to average point features inside each voxel for SECOND', 'build a DynamicSimpleVFE module to dynamically scatter and average point features into voxels', 'build a DynamicVFE module to encode voxel features with optional distance and cluster center augmentation', 'build a HardVFE module to encode fixed-voxel features with optional multi-modal image fusion support', 'review the HardVFE fusion_with_mask method that fuses image and point features using a validity mask']
```

Usage

```
{'build_PillarFeatureNet': 'build a PillarFeatureNet module to encode 3D point cloud pillars into feature representations', 'build_DynamicPillarFeatureNet': 'build a DynamicPillarFeatureNet module to encode dynamic voxels with variable point counts', 'test_PillarFeatureNet_forward': 'test PillarFeatureNet forward pass with point features, num_points tensor, and voxel coordinates', 'test_DynamicPillarFeatureNet_forward': 'test DynamicPillarFeatureNet forward pass with raw point features and voxel coordinates', 'review_map_voxel_center_to_point': 'review DynamicPillarFeatureNet map_voxel_center_to_point method that maps voxel centers to individual points'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/voxel_encoders/utils.py

Prompts

```
['build a PillarFeatureNet module to encode 3D point cloud pillars into feature representations', 'build a DynamicPillarFeatureNet module to encode dynamic voxels with variable point counts', 'test PillarFeatureNet forward pass with point features, num_points tensor, and voxel coordinates', 'test DynamicPillarFeatureNet forward pass with raw point features and voxel coordinates', 'review DynamicPillarFeatureNet map_voxel_center_to_point method that maps voxel centers to individual points', 'create a boolean mask tensor indicating valid points in each padded voxel', 'build a Voxel Feature Encoder layer with linear projection, batch norm, and max pooling', 'run a VFELayer forward pass on voxel features with shape N, M, C', 'build a Pillar Feature Net layer supporting max or avg pooling modes', 'run a PFNLayer forward pass on pillar inputs with optional aligned distance weighting', 'build a HardSimpleVFE module to average point features inside each voxel for SECOND', 'build a DynamicSimpleVFE module to dynamically scatter and average point features into voxels', 'build a DynamicVFE module to encode voxel features with optional distance and cluster center augmentation', 'build a HardVFE module to encode fixed-voxel features with optional multi-modal image fusion support', 'review the HardVFE fusion_with_mask method that fuses image and point features using a validity mask']
```

Usage

```
{'create_paddings_indicator': 'create a boolean mask tensor indicating valid points in each padded voxel', 'build_VFELayer': 'build a Voxel Feature Encoder layer with linear projection, batch norm, and max pooling', 'run_VFELayer_forward': 'run a VFELayer forward pass on voxel features with shape N, M, C', 'build_PFNLayer': 'build a Pillar Feature Net layer supporting max or avg pooling modes', 'run_PFNLayer_forward': 'run a PFNLayer forward pass on pillar inputs with optional aligned distance weighting'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/voxel_encoders/voxel_encoder.py

Prompts

```
['build a PillarFeatureNet module to encode 3D point cloud pillars into feature representations', 'build a DynamicPillarFeatureNet module to encode dynamic voxels with variable point counts', 'test PillarFeatureNet forward pass with point features, num_points tensor, and voxel coordinates', 'test DynamicPillarFeatureNet forward pass with raw point features and voxel coordinates', 'review DynamicPillarFeatureNet map_voxel_center_to_point method that maps voxel centers to individual points', 'create a boolean mask tensor indicating valid points in each padded voxel', 'build a Voxel Feature Encoder layer with linear projection, batch norm, and max pooling', 'run a VFELayer forward pass on voxel features with shape N, M, C', 'build a Pillar Feature Net layer supporting max or avg pooling modes', 'run a PFNLayer forward pass on pillar inputs with optional aligned distance weighting', 'build a HardSimpleVFE module to average point features inside each voxel for SECOND', 'build a DynamicSimpleVFE module to dynamically scatter and average point features into voxels', 'build a DynamicVFE module to encode voxel features with optional distance and cluster center augmentation', 'build a HardVFE module to encode fixed-voxel features with optional multi-modal image fusion support', 'review the HardVFE fusion_with_mask method that fuses image and point features using a validity mask']
```

Usage

```
{'build_HardSimpleVFE': 'build a HardSimpleVFE module to average point features inside each voxel for SECOND', 'build_DynamicSimpleVFE': 'build a DynamicSimpleVFE module to dynamically scatter and average point features into voxels', 'build_DynamicVFE': 'build a DynamicVFE module to encode voxel features with optional distance and cluster center augmentation', 'build_HardVFE': 'build a HardVFE module to encode fixed-voxel features with optional multi-modal image fusion support', 'review_HardVFE_fusion_with_mask': 'review the HardVFE fusion_with_mask method that fuses image and point features using a validity mask'}
```

