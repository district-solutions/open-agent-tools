# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/datasets/collators/point_moco_collator.py

Prompts

```
['run the point_moco_collator function to stack a batch of point cloud samples into tensors', 'test the point_moco_collator function with a sample batch containing data, data_moco, label, and data_valid keys', 'review the point_moco_collator function that collates point cloud batches for MoCo contrastive learning', 'refactor the point_moco_collator to support additional batch keys or different tensor stacking logic', 'summarize the point_moco_collator function that extracts and stacks points, labels, and validity flags from a batch', 'run the point_vox_moco_collator function to collate a batch of point cloud and voxel data for MoCo training', 'review the point_vox_moco_collator function to understand how it stacks points and voxels into tensors', 'test the point_vox_moco_collator function with a sample batch containing data, data_moco, vox, vox_moco, label, and data_valid keys', 'refactor the point_vox_moco_collator function to support additional batch keys or different tensor stacking logic', 'summarize the point_vox_moco_collator function which extracts and stacks point and voxel data from a batch for contrastive learning', 'build a PyTorch DataLoader collator that stacks point cloud data and concatenates voxel data across a batch', 'build a python module that collates MoCo and voxel data batches for depth contrast learning', 'create a collate function using cfl_collate_fn_factory to batch voxel and MoCo data', 'test the vox_moco_collator function with a sample batch of data points and labels', 'review the vox_moco_collator function to understand how it extracts and batches voxel data', 'refactor the vox_moco_collator to support additional batch keys beyond vox and vox_moco']
```

Usage

```
{'run_point_moco_collator': 'run the point_moco_collator function to stack a batch of point cloud samples into tensors', 'test_point_moco_collator': 'test the point_moco_collator function with a sample batch containing data, data_moco, label, and data_valid keys', 'review_point_moco_collator': 'review the point_moco_collator function that collates point cloud batches for MoCo contrastive learning', 'refactor_point_moco_collator': 'refactor the point_moco_collator to support additional batch keys or different tensor stacking logic', 'summarize_point_moco_collator': 'summarize the point_moco_collator function that extracts and stacks points, labels, and validity flags from a batch'}
```

## File: facebookresearch_depthcontrast/datasets/collators/point_vox_moco_collator.py

Prompts

```
['run the point_moco_collator function to stack a batch of point cloud samples into tensors', 'test the point_moco_collator function with a sample batch containing data, data_moco, label, and data_valid keys', 'review the point_moco_collator function that collates point cloud batches for MoCo contrastive learning', 'refactor the point_moco_collator to support additional batch keys or different tensor stacking logic', 'summarize the point_moco_collator function that extracts and stacks points, labels, and validity flags from a batch', 'run the point_vox_moco_collator function to collate a batch of point cloud and voxel data for MoCo training', 'review the point_vox_moco_collator function to understand how it stacks points and voxels into tensors', 'test the point_vox_moco_collator function with a sample batch containing data, data_moco, vox, vox_moco, label, and data_valid keys', 'refactor the point_vox_moco_collator function to support additional batch keys or different tensor stacking logic', 'summarize the point_vox_moco_collator function which extracts and stacks point and voxel data from a batch for contrastive learning', 'build a PyTorch DataLoader collator that stacks point cloud data and concatenates voxel data across a batch', 'build a python module that collates MoCo and voxel data batches for depth contrast learning', 'create a collate function using cfl_collate_fn_factory to batch voxel and MoCo data', 'test the vox_moco_collator function with a sample batch of data points and labels', 'review the vox_moco_collator function to understand how it extracts and batches voxel data', 'refactor the vox_moco_collator to support additional batch keys beyond vox and vox_moco']
```

Usage

```
{'run_collator': 'run the point_vox_moco_collator function to collate a batch of point cloud and voxel data for MoCo training', 'review_collator': 'review the point_vox_moco_collator function to understand how it stacks points and voxels into tensors', 'test_collator': 'test the point_vox_moco_collator function with a sample batch containing data, data_moco, vox, vox_moco, label, and data_valid keys', 'refactor_collator': 'refactor the point_vox_moco_collator function to support additional batch keys or different tensor stacking logic', 'summarize_collator': 'summarize the point_vox_moco_collator function which extracts and stacks point and voxel data from a batch for contrastive learning'}
```

## File: facebookresearch_depthcontrast/datasets/collators/point_vox_moco_lidar_collator.py

Prompts

```
['run the point_moco_collator function to stack a batch of point cloud samples into tensors', 'test the point_moco_collator function with a sample batch containing data, data_moco, label, and data_valid keys', 'review the point_moco_collator function that collates point cloud batches for MoCo contrastive learning', 'refactor the point_moco_collator to support additional batch keys or different tensor stacking logic', 'summarize the point_moco_collator function that extracts and stacks points, labels, and validity flags from a batch', 'run the point_vox_moco_collator function to collate a batch of point cloud and voxel data for MoCo training', 'review the point_vox_moco_collator function to understand how it stacks points and voxels into tensors', 'test the point_vox_moco_collator function with a sample batch containing data, data_moco, vox, vox_moco, label, and data_valid keys', 'refactor the point_vox_moco_collator function to support additional batch keys or different tensor stacking logic', 'summarize the point_vox_moco_collator function which extracts and stacks point and voxel data from a batch for contrastive learning', 'build a PyTorch DataLoader collator that stacks point cloud data and concatenates voxel data across a batch', 'build a python module that collates MoCo and voxel data batches for depth contrast learning', 'create a collate function using cfl_collate_fn_factory to batch voxel and MoCo data', 'test the vox_moco_collator function with a sample batch of data points and labels', 'review the vox_moco_collator function to understand how it extracts and batches voxel data', 'refactor the vox_moco_collator to support additional batch keys beyond vox and vox_moco']
```

Usage

```
{'run_collator': 'run the point_vox_moco_collator function to collate a batch of point cloud and voxel data for MoCo training', 'build_collator': 'build a PyTorch DataLoader collator that stacks point cloud data and concatenates voxel data across a batch', 'test_collator': 'test the point_vox_moco_collator function with a sample batch containing data, data_moco, vox, and vox_moco keys', 'refactor_collator': 'refactor the point_vox_moco_collator to eliminate the duplicated voxel and vox_moco concatenation logic into a helper function', 'review_collator': 'review the point_vox_moco_collator function for the batch collation of LiDAR point clouds and voxel grids with MoCo augmentations'}
```

## File: facebookresearch_depthcontrast/datasets/collators/vox_moco_collator.py

Prompts

```
['run the point_moco_collator function to stack a batch of point cloud samples into tensors', 'test the point_moco_collator function with a sample batch containing data, data_moco, label, and data_valid keys', 'review the point_moco_collator function that collates point cloud batches for MoCo contrastive learning', 'refactor the point_moco_collator to support additional batch keys or different tensor stacking logic', 'summarize the point_moco_collator function that extracts and stacks points, labels, and validity flags from a batch', 'run the point_vox_moco_collator function to collate a batch of point cloud and voxel data for MoCo training', 'review the point_vox_moco_collator function to understand how it stacks points and voxels into tensors', 'test the point_vox_moco_collator function with a sample batch containing data, data_moco, vox, vox_moco, label, and data_valid keys', 'refactor the point_vox_moco_collator function to support additional batch keys or different tensor stacking logic', 'summarize the point_vox_moco_collator function which extracts and stacks point and voxel data from a batch for contrastive learning', 'build a PyTorch DataLoader collator that stacks point cloud data and concatenates voxel data across a batch', 'build a python module that collates MoCo and voxel data batches for depth contrast learning', 'create a collate function using cfl_collate_fn_factory to batch voxel and MoCo data', 'test the vox_moco_collator function with a sample batch of data points and labels', 'review the vox_moco_collator function to understand how it extracts and batches voxel data', 'refactor the vox_moco_collator to support additional batch keys beyond vox and vox_moco']
```

Usage

```
{'build_vox_moco_collator': 'build a python module that collates MoCo and voxel data batches for depth contrast learning', 'create_collate_fn': 'create a collate function using cfl_collate_fn_factory to batch voxel and MoCo data', 'test_vox_moco_collator': 'test the vox_moco_collator function with a sample batch of data points and labels', 'review_vox_moco_collator': 'review the vox_moco_collator function to understand how it extracts and batches voxel data', 'refactor_vox_moco_collator': 'refactor the vox_moco_collator to support additional batch keys beyond vox and vox_moco'}
```

