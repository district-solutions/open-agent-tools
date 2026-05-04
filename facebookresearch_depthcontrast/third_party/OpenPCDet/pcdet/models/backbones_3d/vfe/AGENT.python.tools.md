# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/backbones_3d/vfe/mean_vfe.py

Prompts

```
['build a MeanVFE module to compute mean voxel features from 3D point cloud voxels', 'run the MeanVFE forward pass to average point features across each voxel in the batch', 'test the MeanVFE get_output_feature_dim method to verify it returns the correct number of point features', 'review the MeanVFE forward method to understand how voxel features are normalized by point count', 'refactor the MeanVFE forward pass to support additional voxel feature aggregation strategies beyond mean', 'build a PillarVFE module to extract pillar features from 3D LiDAR voxel data for point cloud detection', 'create a PFNLayer neural network layer with configurable normalization and batch partitioning for large inputs', 'test the PillarVFE forward pass by passing a batch_dict with voxels, voxel_num_points, and voxel_coords', 'refactor the PFNLayer to toggle BatchNorm1d normalization on or off via the use_norm parameter', 'summarize the PillarVFE feature extraction pipeline including f_cluster, f_center, and distance encoding']
```

Usage

```
{'build_MeanVFE': 'build a MeanVFE module to compute mean voxel features from 3D point cloud voxels', 'run_MeanVFE_forward': 'run the MeanVFE forward pass to average point features across each voxel in the batch', 'test_MeanVFE_get_output_feature_dim': 'test the MeanVFE get_output_feature_dim method to verify it returns the correct number of point features', 'review_MeanVFE_normalization': 'review the MeanVFE forward method to understand how voxel features are normalized by point count', 'refactor_MeanVFE_forward': 'refactor the MeanVFE forward pass to support additional voxel feature aggregation strategies beyond mean'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/backbones_3d/vfe/pillar_vfe.py

Prompts

```
['build a MeanVFE module to compute mean voxel features from 3D point cloud voxels', 'run the MeanVFE forward pass to average point features across each voxel in the batch', 'test the MeanVFE get_output_feature_dim method to verify it returns the correct number of point features', 'review the MeanVFE forward method to understand how voxel features are normalized by point count', 'refactor the MeanVFE forward pass to support additional voxel feature aggregation strategies beyond mean', 'build a PillarVFE module to extract pillar features from 3D LiDAR voxel data for point cloud detection', 'create a PFNLayer neural network layer with configurable normalization and batch partitioning for large inputs', 'test the PillarVFE forward pass by passing a batch_dict with voxels, voxel_num_points, and voxel_coords', 'refactor the PFNLayer to toggle BatchNorm1d normalization on or off via the use_norm parameter', 'summarize the PillarVFE feature extraction pipeline including f_cluster, f_center, and distance encoding']
```

Usage

```
{'build_pillar_vfe': 'build a PillarVFE module to extract pillar features from 3D LiDAR voxel data for point cloud detection', 'create_pfn_layer': 'create a PFNLayer neural network layer with configurable normalization and batch partitioning for large inputs', 'test_pillar_vfe_forward': 'test the PillarVFE forward pass by passing a batch_dict with voxels, voxel_num_points, and voxel_coords', 'refactor_pfn_layer_norm': 'refactor the PFNLayer to toggle BatchNorm1d normalization on or off via the use_norm parameter', 'summarize_pillar_vfe_features': 'summarize the PillarVFE feature extraction pipeline including f_cluster, f_center, and distance encoding'}
```

