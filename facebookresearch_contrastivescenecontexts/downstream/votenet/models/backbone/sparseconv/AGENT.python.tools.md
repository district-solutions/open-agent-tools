# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/sparseconv/config.py

Prompts

```
['parse command line arguments and return a config object with all training and network settings', 'convert a string value to a boolean using the str2bool function for argparse type parsing', 'convert a comma-separated string of integers into a Python list using str2list', 'validate and return an optimizer name (SGD or Adam) using the str2opt function', 'validate and return a learning rate scheduler name (StepLR, PolyLR, ExpLR, SquaredLR) using str2scheduler', 'create a VoxelizationDataset wrapper that voxelizes point clouds from an underlying dataset with a configurable voxel size', 'use VoxelizationDataset getitem to retrieve a voxelized sample with sparse quantized coordinates and colors', 'use the collate_fn to batch voxel samples into tensors with voxel_coords, voxel_inds, and voxel_feats keys', 'review the VoxelizationDataset constructor to understand how voxel_size defaults to 0.05 for point cloud quantization', 'test the collate_fn to verify it correctly concatenates voxel coordinates and assigns batch IDs per sample', 'create a Voxelizer instance with voxel size, clip bounds, and data augmentation settings enabled', 'run voxelize on point cloud coordinates, features, and labels to produce sparse voxel grid output', 'run voxelize_temporal on a sequence of point clouds sharing a single transformation matrix', 'test the clip method to filter point cloud coordinates within a specified bounding box', 'review get_transformation_matrix to understand how rotation and scale augmentation matrices are computed']
```

Usage

```
{'get_config_parse_args': 'parse command line arguments and return a config object with all training and network settings', 'str2bool_convert': 'convert a string value to a boolean using the str2bool function for argparse type parsing', 'str2list_convert': 'convert a comma-separated string of integers into a Python list using str2list', 'str2opt_validate': 'validate and return an optimizer name (SGD or Adam) using the str2opt function', 'str2scheduler_validate': 'validate and return a learning rate scheduler name (StepLR, PolyLR, ExpLR, SquaredLR) using str2scheduler'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/sparseconv/voxelized_dataset.py

Prompts

```
['parse command line arguments and return a config object with all training and network settings', 'convert a string value to a boolean using the str2bool function for argparse type parsing', 'convert a comma-separated string of integers into a Python list using str2list', 'validate and return an optimizer name (SGD or Adam) using the str2opt function', 'validate and return a learning rate scheduler name (StepLR, PolyLR, ExpLR, SquaredLR) using str2scheduler', 'create a VoxelizationDataset wrapper that voxelizes point clouds from an underlying dataset with a configurable voxel size', 'use VoxelizationDataset getitem to retrieve a voxelized sample with sparse quantized coordinates and colors', 'use the collate_fn to batch voxel samples into tensors with voxel_coords, voxel_inds, and voxel_feats keys', 'review the VoxelizationDataset constructor to understand how voxel_size defaults to 0.05 for point cloud quantization', 'test the collate_fn to verify it correctly concatenates voxel coordinates and assigns batch IDs per sample', 'create a Voxelizer instance with voxel size, clip bounds, and data augmentation settings enabled', 'run voxelize on point cloud coordinates, features, and labels to produce sparse voxel grid output', 'run voxelize_temporal on a sequence of point clouds sharing a single transformation matrix', 'test the clip method to filter point cloud coordinates within a specified bounding box', 'review get_transformation_matrix to understand how rotation and scale augmentation matrices are computed']
```

Usage

```
{'create_VoxelizationDataset': 'create a VoxelizationDataset wrapper that voxelizes point clouds from an underlying dataset with a configurable voxel size', 'use_VoxelizationDataset_getitem': 'use VoxelizationDataset getitem to retrieve a voxelized sample with sparse quantized coordinates and colors', 'use_collate_fn': 'use the collate_fn to batch voxel samples into tensors with voxel_coords, voxel_inds, and voxel_feats keys', 'review_VoxelizationDataset_init': 'review the VoxelizationDataset constructor to understand how voxel_size defaults to 0.05 for point cloud quantization', 'test_collate_fn_batching': 'test the collate_fn to verify it correctly concatenates voxel coordinates and assigns batch IDs per sample'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/sparseconv/voxelizer.py

Prompts

```
['parse command line arguments and return a config object with all training and network settings', 'convert a string value to a boolean using the str2bool function for argparse type parsing', 'convert a comma-separated string of integers into a Python list using str2list', 'validate and return an optimizer name (SGD or Adam) using the str2opt function', 'validate and return a learning rate scheduler name (StepLR, PolyLR, ExpLR, SquaredLR) using str2scheduler', 'create a VoxelizationDataset wrapper that voxelizes point clouds from an underlying dataset with a configurable voxel size', 'use VoxelizationDataset getitem to retrieve a voxelized sample with sparse quantized coordinates and colors', 'use the collate_fn to batch voxel samples into tensors with voxel_coords, voxel_inds, and voxel_feats keys', 'review the VoxelizationDataset constructor to understand how voxel_size defaults to 0.05 for point cloud quantization', 'test the collate_fn to verify it correctly concatenates voxel coordinates and assigns batch IDs per sample', 'create a Voxelizer instance with voxel size, clip bounds, and data augmentation settings enabled', 'run voxelize on point cloud coordinates, features, and labels to produce sparse voxel grid output', 'run voxelize_temporal on a sequence of point clouds sharing a single transformation matrix', 'test the clip method to filter point cloud coordinates within a specified bounding box', 'review get_transformation_matrix to understand how rotation and scale augmentation matrices are computed']
```

Usage

```
{'create_Voxelizer_with_augmentation': 'create a Voxelizer instance with voxel size, clip bounds, and data augmentation settings enabled', 'run_Voxelizer_voxelize': 'run voxelize on point cloud coordinates, features, and labels to produce sparse voxel grid output', 'run_Voxelizer_voxelize_temporal': 'run voxelize_temporal on a sequence of point clouds sharing a single transformation matrix', 'test_Voxelizer_clip': 'test the clip method to filter point cloud coordinates within a specified bounding box', 'review_Voxelizer_get_transformation_matrix': 'review get_transformation_matrix to understand how rotation and scale augmentation matrices are computed'}
```

