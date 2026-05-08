# Agent Python Tools

- repo: facebookresearch/imvotenet
- repo_uri: https://github.com/facebookresearch/imvotenet

## File: facebookresearch_imvotenet/sunrgbd/model_util_sunrgbd.py

Prompts

```
['create a SunrgbdDatasetConfig instance with 10 object classes and 12 heading bins for SUNRGB-D dataset', 'convert a 3D bounding box size to its discrete size class and residual using SunrgbdDatasetConfig', 'convert a continuous heading angle to a discrete class ID and residual angle using SunrgbdDatasetConfig', 'reconstruct a 7D oriented bounding box from center, heading class, heading residual, size class, and size residual', 'convert a discrete heading class ID and residual back to a continuous angle using SunrgbdDatasetConfig', 'create a SunrgbdDetectionVotesDataset instance with color, height, and augmentation enabled for training', 'get a data sample from the dataset including point clouds, votes, and bounding box labels', 'pre-load 2D bounding box detections and class scores from text files into memory maps', 'visualize point votes and vote masks by writing PLY files for voted point clouds', 'visualize oriented bounding box ground truth labels and centroids as PLY files', 'parse SUN RGB-D label file lines into SUNObject3d objects with 2D/3D bounding box data', 'project upright depth point cloud coordinates to 2D image UV coordinates using calibration matrix', 'compute 3D bounding box corners from a SUNObject3d object and project them to 2D image coordinates', 'draw a 3D bounding box projected onto a 2D image using OpenCV line drawing', 'flip point cloud axis coordinates between camera and depth coordinate systems']
```

Usage

```
{'create_sunrgbd_config': 'create a SunrgbdDatasetConfig instance with 10 object classes and 12 heading bins for SUNRGB-D dataset', 'convert_size_to_class': 'convert a 3D bounding box size to its discrete size class and residual using SunrgbdDatasetConfig', 'convert_angle_to_class': 'convert a continuous heading angle to a discrete class ID and residual angle using SunrgbdDatasetConfig', 'reconstruct_obb_from_params': 'reconstruct a 7D oriented bounding box from center, heading class, heading residual, size class, and size residual', 'convert_class_to_angle': 'convert a discrete heading class ID and residual back to a continuous angle using SunrgbdDatasetConfig'}
```

## File: facebookresearch_imvotenet/sunrgbd/sunrgbd_detection_dataset.py

Prompts

```
['create a SunrgbdDatasetConfig instance with 10 object classes and 12 heading bins for SUNRGB-D dataset', 'convert a 3D bounding box size to its discrete size class and residual using SunrgbdDatasetConfig', 'convert a continuous heading angle to a discrete class ID and residual angle using SunrgbdDatasetConfig', 'reconstruct a 7D oriented bounding box from center, heading class, heading residual, size class, and size residual', 'convert a discrete heading class ID and residual back to a continuous angle using SunrgbdDatasetConfig', 'create a SunrgbdDetectionVotesDataset instance with color, height, and augmentation enabled for training', 'get a data sample from the dataset including point clouds, votes, and bounding box labels', 'pre-load 2D bounding box detections and class scores from text files into memory maps', 'visualize point votes and vote masks by writing PLY files for voted point clouds', 'visualize oriented bounding box ground truth labels and centroids as PLY files', 'parse SUN RGB-D label file lines into SUNObject3d objects with 2D/3D bounding box data', 'project upright depth point cloud coordinates to 2D image UV coordinates using calibration matrix', 'compute 3D bounding box corners from a SUNObject3d object and project them to 2D image coordinates', 'draw a 3D bounding box projected onto a 2D image using OpenCV line drawing', 'flip point cloud axis coordinates between camera and depth coordinate systems']
```

Usage

```
{'create_dataset_instance': 'create a SunrgbdDetectionVotesDataset instance with color, height, and augmentation enabled for training', 'get_dataset_item': 'get a data sample from the dataset including point clouds, votes, and bounding box labels', 'preload_2d_bboxes': 'pre-load 2D bounding box detections and class scores from text files into memory maps', 'visualize_votes': 'visualize point votes and vote masks by writing PLY files for voted point clouds', 'visualize_obb': 'visualize oriented bounding box ground truth labels and centroids as PLY files'}
```

## File: facebookresearch_imvotenet/sunrgbd/sunrgbd_utils.py

Prompts

```
['create a SunrgbdDatasetConfig instance with 10 object classes and 12 heading bins for SUNRGB-D dataset', 'convert a 3D bounding box size to its discrete size class and residual using SunrgbdDatasetConfig', 'convert a continuous heading angle to a discrete class ID and residual angle using SunrgbdDatasetConfig', 'reconstruct a 7D oriented bounding box from center, heading class, heading residual, size class, and size residual', 'convert a discrete heading class ID and residual back to a continuous angle using SunrgbdDatasetConfig', 'create a SunrgbdDetectionVotesDataset instance with color, height, and augmentation enabled for training', 'get a data sample from the dataset including point clouds, votes, and bounding box labels', 'pre-load 2D bounding box detections and class scores from text files into memory maps', 'visualize point votes and vote masks by writing PLY files for voted point clouds', 'visualize oriented bounding box ground truth labels and centroids as PLY files', 'parse SUN RGB-D label file lines into SUNObject3d objects with 2D/3D bounding box data', 'project upright depth point cloud coordinates to 2D image UV coordinates using calibration matrix', 'compute 3D bounding box corners from a SUNObject3d object and project them to 2D image coordinates', 'draw a 3D bounding box projected onto a 2D image using OpenCV line drawing', 'flip point cloud axis coordinates between camera and depth coordinate systems']
```

Usage

```
{'parse_sunrgbd_3d_objects': 'parse SUN RGB-D label file lines into SUNObject3d objects with 2D/3D bounding box data', 'project_point_cloud_to_image': 'project upright depth point cloud coordinates to 2D image UV coordinates using calibration matrix', 'compute_3d_bounding_box': 'compute 3D bounding box corners from a SUNObject3d object and project them to 2D image coordinates', 'draw_projected_3d_box': 'draw a 3D bounding box projected onto a 2D image using OpenCV line drawing', 'flip_point_cloud_axes': 'flip point cloud axis coordinates between camera and depth coordinate systems'}
```

