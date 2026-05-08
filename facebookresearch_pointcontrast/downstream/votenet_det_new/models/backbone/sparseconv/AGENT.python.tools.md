# Agent Python Tools

- repo: facebookresearch/pointcontrast
- repo_uri: https://github.com/facebookresearch/pointcontrast

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/sparseconv/config.py

Prompts

```
['parse command line arguments and return a config object with all training and network settings', 'convert a string value to a boolean using the str2bool function', 'convert a comma-separated string of integers to a list using str2list', 'validate and return an optimizer name (SGD or Adam) using str2opt', 'validate and return a learning rate scheduler name (StepLR, PolyLR, ExpLR, SquaredLR) using str2scheduler', 'create a VoxelizationDataset wrapper that voxelizes point clouds from an existing PyTorch Dataset', 'use VoxelizationDataset getitem to retrieve a voxelized point cloud sample with sparse quantized coordinates', 'use collate_fn to batch voxelized samples into voxel_coords, voxel_inds, and voxel_feats tensors', 'review the VoxelizationDataset class and its voxelization logic using MinkowskiEngine sparse quantize', 'refactor the collate_fn to customize how voxel coordinates and features are batched for sparse convolution', 'create a Voxelizer instance with voxel_size, clip_bound, and augmentation settings for 3D point cloud processing', 'voxelize 3D point cloud coordinates with features and labels using the Voxelizer class', 'get the voxelization and rotation transformation matrices for point cloud coordinate transformation', 'clip point cloud coordinates within specified bounds using the Voxelizer clip method', 'voxelize multiple temporal point clouds with shared transformation using the Voxelizer voxelize_temporal method']
```

Usage

```
{'get_config_parse_args': 'parse command line arguments and return a config object with all training and network settings', 'str2bool_convert': 'convert a string value to a boolean using the str2bool function', 'str2list_convert': 'convert a comma-separated string of integers to a list using str2list', 'str2opt_validate': 'validate and return an optimizer name (SGD or Adam) using str2opt', 'str2scheduler_validate': 'validate and return a learning rate scheduler name (StepLR, PolyLR, ExpLR, SquaredLR) using str2scheduler'}
```

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/sparseconv/voxelized_dataset.py

Prompts

```
['parse command line arguments and return a config object with all training and network settings', 'convert a string value to a boolean using the str2bool function', 'convert a comma-separated string of integers to a list using str2list', 'validate and return an optimizer name (SGD or Adam) using str2opt', 'validate and return a learning rate scheduler name (StepLR, PolyLR, ExpLR, SquaredLR) using str2scheduler', 'create a VoxelizationDataset wrapper that voxelizes point clouds from an existing PyTorch Dataset', 'use VoxelizationDataset getitem to retrieve a voxelized point cloud sample with sparse quantized coordinates', 'use collate_fn to batch voxelized samples into voxel_coords, voxel_inds, and voxel_feats tensors', 'review the VoxelizationDataset class and its voxelization logic using MinkowskiEngine sparse quantize', 'refactor the collate_fn to customize how voxel coordinates and features are batched for sparse convolution', 'create a Voxelizer instance with voxel_size, clip_bound, and augmentation settings for 3D point cloud processing', 'voxelize 3D point cloud coordinates with features and labels using the Voxelizer class', 'get the voxelization and rotation transformation matrices for point cloud coordinate transformation', 'clip point cloud coordinates within specified bounds using the Voxelizer clip method', 'voxelize multiple temporal point clouds with shared transformation using the Voxelizer voxelize_temporal method']
```

Usage

```
{'create_voxelization_dataset': 'create a VoxelizationDataset wrapper that voxelizes point clouds from an existing PyTorch Dataset', 'use_voxelization_dataset_getitem': 'use VoxelizationDataset getitem to retrieve a voxelized point cloud sample with sparse quantized coordinates', 'use_collate_fn_batch': 'use collate_fn to batch voxelized samples into voxel_coords, voxel_inds, and voxel_feats tensors', 'review_voxelization_dataset_class': 'review the VoxelizationDataset class and its voxelization logic using MinkowskiEngine sparse quantize', 'refactor_collate_fn': 'refactor the collate_fn to customize how voxel coordinates and features are batched for sparse convolution'}
```

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/sparseconv/voxelizer.py

Prompts

```
['parse command line arguments and return a config object with all training and network settings', 'convert a string value to a boolean using the str2bool function', 'convert a comma-separated string of integers to a list using str2list', 'validate and return an optimizer name (SGD or Adam) using str2opt', 'validate and return a learning rate scheduler name (StepLR, PolyLR, ExpLR, SquaredLR) using str2scheduler', 'create a VoxelizationDataset wrapper that voxelizes point clouds from an existing PyTorch Dataset', 'use VoxelizationDataset getitem to retrieve a voxelized point cloud sample with sparse quantized coordinates', 'use collate_fn to batch voxelized samples into voxel_coords, voxel_inds, and voxel_feats tensors', 'review the VoxelizationDataset class and its voxelization logic using MinkowskiEngine sparse quantize', 'refactor the collate_fn to customize how voxel coordinates and features are batched for sparse convolution', 'create a Voxelizer instance with voxel_size, clip_bound, and augmentation settings for 3D point cloud processing', 'voxelize 3D point cloud coordinates with features and labels using the Voxelizer class', 'get the voxelization and rotation transformation matrices for point cloud coordinate transformation', 'clip point cloud coordinates within specified bounds using the Voxelizer clip method', 'voxelize multiple temporal point clouds with shared transformation using the Voxelizer voxelize_temporal method']
```

Usage

```
{'create_Voxelizer': 'create a Voxelizer instance with voxel_size, clip_bound, and augmentation settings for 3D point cloud processing', 'voxelize_point_cloud': 'voxelize 3D point cloud coordinates with features and labels using the Voxelizer class', 'get_transformation_matrix': 'get the voxelization and rotation transformation matrices for point cloud coordinate transformation', 'clip_point_cloud': 'clip point cloud coordinates within specified bounds using the Voxelizer clip method', 'voxelize_temporal_point_clouds': 'voxelize multiple temporal point clouds with shared transformation using the Voxelizer voxelize_temporal method'}
```

