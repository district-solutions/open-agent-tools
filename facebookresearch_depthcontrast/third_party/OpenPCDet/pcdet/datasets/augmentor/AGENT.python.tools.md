# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/datasets/augmentor/augmentor_utils.py

Prompts

```
['create a function that randomly flips ground truth boxes and point cloud data along the x-axis', 'create a function that randomly flips ground truth boxes and point cloud data along the y-axis', 'build a data augmentation module that applies random global rotation to 3D point clouds and bounding boxes', 'build a data augmentation module that applies random scaling to 3D point clouds and bounding boxes', 'test the augmentor utils module to verify random flip, rotation, and scaling augmentations work correctly on point cloud data', 'create a DataAugmentor instance with root path, augmentor configs, and class names for 3D point cloud augmentation', 'run the forward method to apply all queued augmentations to a data dict with points and gt_boxes', 'apply random_world_flip to randomly flip gt_boxes and points along specified x or y axes', 'apply random_world_rotation to randomly rotate gt_boxes and points within a configured angle range', 'apply random_world_scaling to randomly scale gt_boxes and points within a configured scale range', 'create a DataBaseSampler instance with root_path, sampler_cfg, class_names, and optional logger for 3D object augmentation', 'filter database ground truth infos by removing entries matching specified difficulty levels', 'filter database ground truth infos to keep only entries with a minimum number of points per class', 'sample a fixed number of ground truth objects from the database for a given class and sample group', 'run the DataBaseSampler on a data_dict to augment the scene with sampled 3D boxes and points']
```

Usage

```
{'create_flip_x_augmentation': 'create a function that randomly flips ground truth boxes and point cloud data along the x-axis', 'create_flip_y_augmentation': 'create a function that randomly flips ground truth boxes and point cloud data along the y-axis', 'build_global_rotation_augmentation': 'build a data augmentation module that applies random global rotation to 3D point clouds and bounding boxes', 'build_global_scaling_augmentation': 'build a data augmentation module that applies random scaling to 3D point clouds and bounding boxes', 'test_augmentor_utils': 'test the augmentor utils module to verify random flip, rotation, and scaling augmentations work correctly on point cloud data'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/datasets/augmentor/data_augmentor.py

Prompts

```
['create a function that randomly flips ground truth boxes and point cloud data along the x-axis', 'create a function that randomly flips ground truth boxes and point cloud data along the y-axis', 'build a data augmentation module that applies random global rotation to 3D point clouds and bounding boxes', 'build a data augmentation module that applies random scaling to 3D point clouds and bounding boxes', 'test the augmentor utils module to verify random flip, rotation, and scaling augmentations work correctly on point cloud data', 'create a DataAugmentor instance with root path, augmentor configs, and class names for 3D point cloud augmentation', 'run the forward method to apply all queued augmentations to a data dict with points and gt_boxes', 'apply random_world_flip to randomly flip gt_boxes and points along specified x or y axes', 'apply random_world_rotation to randomly rotate gt_boxes and points within a configured angle range', 'apply random_world_scaling to randomly scale gt_boxes and points within a configured scale range', 'create a DataBaseSampler instance with root_path, sampler_cfg, class_names, and optional logger for 3D object augmentation', 'filter database ground truth infos by removing entries matching specified difficulty levels', 'filter database ground truth infos to keep only entries with a minimum number of points per class', 'sample a fixed number of ground truth objects from the database for a given class and sample group', 'run the DataBaseSampler on a data_dict to augment the scene with sampled 3D boxes and points']
```

Usage

```
{'create_data_augmentor': 'create a DataAugmentor instance with root path, augmentor configs, and class names for 3D point cloud augmentation', 'run_forward_augmentation': 'run the forward method to apply all queued augmentations to a data dict with points and gt_boxes', 'apply_random_world_flip': 'apply random_world_flip to randomly flip gt_boxes and points along specified x or y axes', 'apply_random_world_rotation': 'apply random_world_rotation to randomly rotate gt_boxes and points within a configured angle range', 'apply_random_world_scaling': 'apply random_world_scaling to randomly scale gt_boxes and points within a configured scale range'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/datasets/augmentor/database_sampler.py

Prompts

```
['create a function that randomly flips ground truth boxes and point cloud data along the x-axis', 'create a function that randomly flips ground truth boxes and point cloud data along the y-axis', 'build a data augmentation module that applies random global rotation to 3D point clouds and bounding boxes', 'build a data augmentation module that applies random scaling to 3D point clouds and bounding boxes', 'test the augmentor utils module to verify random flip, rotation, and scaling augmentations work correctly on point cloud data', 'create a DataAugmentor instance with root path, augmentor configs, and class names for 3D point cloud augmentation', 'run the forward method to apply all queued augmentations to a data dict with points and gt_boxes', 'apply random_world_flip to randomly flip gt_boxes and points along specified x or y axes', 'apply random_world_rotation to randomly rotate gt_boxes and points within a configured angle range', 'apply random_world_scaling to randomly scale gt_boxes and points within a configured scale range', 'create a DataBaseSampler instance with root_path, sampler_cfg, class_names, and optional logger for 3D object augmentation', 'filter database ground truth infos by removing entries matching specified difficulty levels', 'filter database ground truth infos to keep only entries with a minimum number of points per class', 'sample a fixed number of ground truth objects from the database for a given class and sample group', 'run the DataBaseSampler on a data_dict to augment the scene with sampled 3D boxes and points']
```

Usage

```
{'init_database_sampler': 'create a DataBaseSampler instance with root_path, sampler_cfg, class_names, and optional logger for 3D object augmentation', 'filter_by_difficulty': 'filter database ground truth infos by removing entries matching specified difficulty levels', 'filter_by_min_points': 'filter database ground truth infos to keep only entries with a minimum number of points per class', 'sample_with_fixed_number': 'sample a fixed number of ground truth objects from the database for a given class and sample group', 'call_database_sampler': 'run the DataBaseSampler on a data_dict to augment the scene with sampled 3D boxes and points'}
```

