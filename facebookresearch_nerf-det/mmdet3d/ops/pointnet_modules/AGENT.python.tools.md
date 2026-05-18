# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/ops/pointnet_modules/builder.py

Prompts

```
['build a PointNet2 SA module using the default PointSAModule type with no config', 'build a PointNet2 SA module from a config dict specifying type and init args', 'build a PointNet2 SA module passing extra keyword arguments through to the module constructor', 'review the SA_MODULES registry to see which PointNet2 set abstraction module types are available', 'test that build_sa_module raises TypeError for non-dict cfg and KeyError for missing type key', 'build a PointFPModule with mlp_channels list to propagate features between point sets in PointNet', 'run PointFPModule forward pass with target and source xyz tensors and their features', 'create a PointFPModule with custom norm_cfg dict for batch normalization configuration', 'test the three_nn nearest neighbor search and three_interpolate used inside PointFPModule forward', 'review PointFPModule forward method that concatenates interpolated source features with target features', 'build a PointSAModuleMSG module with multi-scale grouping for point cloud feature abstraction', 'build a PointSAModule with single-scale grouping for point cloud set abstraction', 'test PointSAModuleMSG forward pass with points_xyz and features tensors', 'test PointSAModule forward pass with points_xyz and optional target_xyz tensor', 'review PointSAModuleMSG initialization with radii sample_nums and mlp_channels configuration']
```

Usage

```
{'build_sa_module_default': 'build a PointNet2 SA module using the default PointSAModule type with no config', 'build_sa_module_from_cfg': 'build a PointNet2 SA module from a config dict specifying type and init args', 'build_sa_module_with_kwargs': 'build a PointNet2 SA module passing extra keyword arguments through to the module constructor', 'review_sa_module_registry': 'review the SA_MODULES registry to see which PointNet2 set abstraction module types are available', 'test_build_sa_module_errors': 'test that build_sa_module raises TypeError for non-dict cfg and KeyError for missing type key'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/pointnet_modules/point_fp_module.py

Prompts

```
['build a PointNet2 SA module using the default PointSAModule type with no config', 'build a PointNet2 SA module from a config dict specifying type and init args', 'build a PointNet2 SA module passing extra keyword arguments through to the module constructor', 'review the SA_MODULES registry to see which PointNet2 set abstraction module types are available', 'test that build_sa_module raises TypeError for non-dict cfg and KeyError for missing type key', 'build a PointFPModule with mlp_channels list to propagate features between point sets in PointNet', 'run PointFPModule forward pass with target and source xyz tensors and their features', 'create a PointFPModule with custom norm_cfg dict for batch normalization configuration', 'test the three_nn nearest neighbor search and three_interpolate used inside PointFPModule forward', 'review PointFPModule forward method that concatenates interpolated source features with target features', 'build a PointSAModuleMSG module with multi-scale grouping for point cloud feature abstraction', 'build a PointSAModule with single-scale grouping for point cloud set abstraction', 'test PointSAModuleMSG forward pass with points_xyz and features tensors', 'test PointSAModule forward pass with points_xyz and optional target_xyz tensor', 'review PointSAModuleMSG initialization with radii sample_nums and mlp_channels configuration']
```

Usage

```
{'build_PointFPModule': 'build a PointFPModule with mlp_channels list to propagate features between point sets in PointNet', 'run_PointFPModule_forward': 'run PointFPModule forward pass with target and source xyz tensors and their features', 'create_PointFPModule_with_custom_norm': 'create a PointFPModule with custom norm_cfg dict for batch normalization configuration', 'test_three_nn_interpolation': 'test the three_nn nearest neighbor search and three_interpolate used inside PointFPModule forward', 'review_PointFPModule_feature_concat': 'review PointFPModule forward method that concatenates interpolated source features with target features'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/pointnet_modules/point_sa_module.py

Prompts

```
['build a PointNet2 SA module using the default PointSAModule type with no config', 'build a PointNet2 SA module from a config dict specifying type and init args', 'build a PointNet2 SA module passing extra keyword arguments through to the module constructor', 'review the SA_MODULES registry to see which PointNet2 set abstraction module types are available', 'test that build_sa_module raises TypeError for non-dict cfg and KeyError for missing type key', 'build a PointFPModule with mlp_channels list to propagate features between point sets in PointNet', 'run PointFPModule forward pass with target and source xyz tensors and their features', 'create a PointFPModule with custom norm_cfg dict for batch normalization configuration', 'test the three_nn nearest neighbor search and three_interpolate used inside PointFPModule forward', 'review PointFPModule forward method that concatenates interpolated source features with target features', 'build a PointSAModuleMSG module with multi-scale grouping for point cloud feature abstraction', 'build a PointSAModule with single-scale grouping for point cloud set abstraction', 'test PointSAModuleMSG forward pass with points_xyz and features tensors', 'test PointSAModule forward pass with points_xyz and optional target_xyz tensor', 'review PointSAModuleMSG initialization with radii sample_nums and mlp_channels configuration']
```

Usage

```
{'build_PointSAModuleMSG': 'build a PointSAModuleMSG module with multi-scale grouping for point cloud feature abstraction', 'build_PointSAModule': 'build a PointSAModule with single-scale grouping for point cloud set abstraction', 'test_PointSAModuleMSG_forward': 'test PointSAModuleMSG forward pass with points_xyz and features tensors', 'test_PointSAModule_forward': 'test PointSAModule forward pass with points_xyz and optional target_xyz tensor', 'review_PointSAModuleMSG_init': 'review PointSAModuleMSG initialization with radii sample_nums and mlp_channels configuration'}
```

