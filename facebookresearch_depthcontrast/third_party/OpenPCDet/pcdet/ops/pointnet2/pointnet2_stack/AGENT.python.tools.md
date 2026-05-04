# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/ops/pointnet2/pointnet2_stack/pointnet2_modules.py

Prompts

```
['build a StackSAModuleMSG module with multi-scale grouping radii and MLP specs for point cloud feature extraction', 'build a StackPointnetFPModule with an MLP spec for feature propagation between point cloud resolutions', 'run the StackSAModuleMSG forward pass with xyz coordinates and features to extract multi-scale grouped features', 'run the StackPointnetFPModule forward pass to interpolate known features onto unknown points using inverse distance weighting', 'review the StackSAModuleMSG init_weights method that initializes Conv2d with Kaiming normal and BatchNorm2d with constant values', 'build a module that runs ball_query to find neighboring points within a given radius for point cloud data', 'create a function that uses grouping_operation to gather features by index for grouped point cloud processing', 'test the QueryAndGroup module to combine ball query and feature grouping for point cloud layers', 'refactor code using furthest_point_sample to downsample point clouds by selecting the most distant points', 'summarize the three_nn function that finds the three nearest neighbors between two point sets']
```

Usage

```
{'build_stack_samodule_msg': 'build a StackSAModuleMSG module with multi-scale grouping radii and MLP specs for point cloud feature extraction', 'build_stack_pointnet_fp_module': 'build a StackPointnetFPModule with an MLP spec for feature propagation between point cloud resolutions', 'run_samodule_msg_forward': 'run the StackSAModuleMSG forward pass with xyz coordinates and features to extract multi-scale grouped features', 'run_pointnet_fp_forward': 'run the StackPointnetFPModule forward pass to interpolate known features onto unknown points using inverse distance weighting', 'review_stack_samodule_msg_init_weights': 'review the StackSAModuleMSG init_weights method that initializes Conv2d with Kaiming normal and BatchNorm2d with constant values'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/ops/pointnet2/pointnet2_stack/pointnet2_utils.py

Prompts

```
['build a StackSAModuleMSG module with multi-scale grouping radii and MLP specs for point cloud feature extraction', 'build a StackPointnetFPModule with an MLP spec for feature propagation between point cloud resolutions', 'run the StackSAModuleMSG forward pass with xyz coordinates and features to extract multi-scale grouped features', 'run the StackPointnetFPModule forward pass to interpolate known features onto unknown points using inverse distance weighting', 'review the StackSAModuleMSG init_weights method that initializes Conv2d with Kaiming normal and BatchNorm2d with constant values', 'build a module that runs ball_query to find neighboring points within a given radius for point cloud data', 'create a function that uses grouping_operation to gather features by index for grouped point cloud processing', 'test the QueryAndGroup module to combine ball query and feature grouping for point cloud layers', 'refactor code using furthest_point_sample to downsample point clouds by selecting the most distant points', 'summarize the three_nn function that finds the three nearest neighbors between two point sets']
```

Usage

```
{'build_ball_query': 'build a module that runs ball_query to find neighboring points within a given radius for point cloud data', 'create_grouping_operation': 'create a function that uses grouping_operation to gather features by index for grouped point cloud processing', 'test_QueryAndGroup': 'test the QueryAndGroup module to combine ball query and feature grouping for point cloud layers', 'refactor_furthest_point_sample': 'refactor code using furthest_point_sample to downsample point clouds by selecting the most distant points', 'summarize_three_nn': 'summarize the three_nn function that finds the three nearest neighbors between two point sets'}
```

