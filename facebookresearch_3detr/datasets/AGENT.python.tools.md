# Agent Python Tools

- repo: facebookresearch/3detr
- repo_uri: https://github.com/facebookresearch/3detr

## File: facebookresearch_3detr/datasets/scannet.py

Prompts

```
['create a ScannetDatasetConfig instance to map 18 ScanNet object classes to NYU40 IDs and class indices', 'rotate axis-aligned 3D bounding boxes by a given rotation matrix using ScannetDatasetConfig.rotate_aligned_boxes', 'convert box center, size, and angle parameters to 3D corner coordinates using box_parametrization_to_corners_np', 'create a ScannetDetectionDataset for training 3D object detection with configurable point count, augmentation, and random cuboid sampling', 'load a ScanNet scan by index via ScannetDetectionDataset getitem to get point clouds, bounding boxes, and semantic labels', 'create a SunrgbdDetectionDataset instance to load SUN RGB-D point clouds and bounding boxes for training', 'convert a continuous heading angle to a discrete angle class and residual using SunrgbdDatasetConfig', 'convert a discrete angle class and residual back to a continuous heading angle using SunrgbdDatasetConfig', 'compute 3D bounding box corner coordinates from center, size, and heading angle using box_parametrization_to_corners_np', 'apply random flipping, rotation, scaling, and color jitter augmentation to SUN RGB-D point clouds and bounding boxes']
```

Usage

```
{'create_scannet_dataset_config': 'create a ScannetDatasetConfig instance to map 18 ScanNet object classes to NYU40 IDs and class indices', 'rotate_aligned_boxes': 'rotate axis-aligned 3D bounding boxes by a given rotation matrix using ScannetDatasetConfig.rotate_aligned_boxes', 'convert_box_param_to_corners': 'convert box center, size, and angle parameters to 3D corner coordinates using box_parametrization_to_corners_np', 'create_scannet_detection_dataset': 'create a ScannetDetectionDataset for training 3D object detection with configurable point count, augmentation, and random cuboid sampling', 'load_scannet_scan_item': 'load a ScanNet scan by index via ScannetDetectionDataset getitem to get point clouds, bounding boxes, and semantic labels'}
```

## File: facebookresearch_3detr/datasets/sunrgbd.py

Prompts

```
['create a ScannetDatasetConfig instance to map 18 ScanNet object classes to NYU40 IDs and class indices', 'rotate axis-aligned 3D bounding boxes by a given rotation matrix using ScannetDatasetConfig.rotate_aligned_boxes', 'convert box center, size, and angle parameters to 3D corner coordinates using box_parametrization_to_corners_np', 'create a ScannetDetectionDataset for training 3D object detection with configurable point count, augmentation, and random cuboid sampling', 'load a ScanNet scan by index via ScannetDetectionDataset getitem to get point clouds, bounding boxes, and semantic labels', 'create a SunrgbdDetectionDataset instance to load SUN RGB-D point clouds and bounding boxes for training', 'convert a continuous heading angle to a discrete angle class and residual using SunrgbdDatasetConfig', 'convert a discrete angle class and residual back to a continuous heading angle using SunrgbdDatasetConfig', 'compute 3D bounding box corner coordinates from center, size, and heading angle using box_parametrization_to_corners_np', 'apply random flipping, rotation, scaling, and color jitter augmentation to SUN RGB-D point clouds and bounding boxes']
```

Usage

```
{'create_dataset_loader': 'create a SunrgbdDetectionDataset instance to load SUN RGB-D point clouds and bounding boxes for training', 'convert_angle_to_class': 'convert a continuous heading angle to a discrete angle class and residual using SunrgbdDatasetConfig', 'convert_class_to_angle': 'convert a discrete angle class and residual back to a continuous heading angle using SunrgbdDatasetConfig', 'compute_box_corners': 'compute 3D bounding box corner coordinates from center, size, and heading angle using box_parametrization_to_corners_np', 'augment_point_clouds': 'apply random flipping, rotation, scaling, and color jitter augmentation to SUN RGB-D point clouds and bounding boxes'}
```

