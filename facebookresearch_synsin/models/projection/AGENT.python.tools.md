# Agent Python Tools

- repo: facebookresearch/synsin
- repo_uri: https://github.com/facebookresearch/synsin

## File: facebookresearch_synsin/models/projection/depth_manipulator.py

Prompts

```
['create a DepthManipulator instance with a specified width for image manipulation', 'homogenize a tensor of coordinates by appending a ones dimension', 'project depth maps using camera intrinsics and extrinsics to get a bilinear sampler', 'review the DepthManipulator class and its depth projection capabilities', 'summarize the project_zbuffer method that transforms depth into camera coordinates', 'create a PtsManipulator module with width W and channel C for 3D point projection and splatting', 'project 3D points from one camera view to another using intrinsic and extrinsic matrices', 'run the PtsManipulator forward pass with alphas, source features, and predicted 3D points for view synthesis', 'run the PtsManipulator forward pass with source features and predicted 3D points without alpha blending', 'get a RasterizePointsXYsBlending splatter module for xy blending with configurable radius and points per pixel']
```

Usage

```
{'create_depth_manipulator': 'create a DepthManipulator instance with a specified width for image manipulation', 'homogenize_coordinates': 'homogenize a tensor of coordinates by appending a ones dimension', 'project_zbuffer_depth': 'project depth maps using camera intrinsics and extrinsics to get a bilinear sampler', 'review_depth_manipulator_class': 'review the DepthManipulator class and its depth projection capabilities', 'summarize_project_zbuffer': 'summarize the project_zbuffer method that transforms depth into camera coordinates'}
```

## File: facebookresearch_synsin/models/projection/z_buffer_manipulator.py

Prompts

```
['create a DepthManipulator instance with a specified width for image manipulation', 'homogenize a tensor of coordinates by appending a ones dimension', 'project depth maps using camera intrinsics and extrinsics to get a bilinear sampler', 'review the DepthManipulator class and its depth projection capabilities', 'summarize the project_zbuffer method that transforms depth into camera coordinates', 'create a PtsManipulator module with width W and channel C for 3D point projection and splatting', 'project 3D points from one camera view to another using intrinsic and extrinsic matrices', 'run the PtsManipulator forward pass with alphas, source features, and predicted 3D points for view synthesis', 'run the PtsManipulator forward pass with source features and predicted 3D points without alpha blending', 'get a RasterizePointsXYsBlending splatter module for xy blending with configurable radius and points per pixel']
```

Usage

```
{'create_PtsManipulator': 'create a PtsManipulator module with width W and channel C for 3D point projection and splatting', 'project_pts_PtsManipulator': 'project 3D points from one camera view to another using intrinsic and extrinsic matrices', 'forward_PtsManipulator': 'run the PtsManipulator forward pass with alphas, source features, and predicted 3D points for view synthesis', 'forward_justpts_PtsManipulator': 'run the PtsManipulator forward pass with source features and predicted 3D points without alpha blending', 'get_splatter': 'get a RasterizePointsXYsBlending splatter module for xy blending with configurable radius and points per pixel'}
```

