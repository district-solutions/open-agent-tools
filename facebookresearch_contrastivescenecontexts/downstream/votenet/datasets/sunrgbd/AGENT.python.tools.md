# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/datasets/sunrgbd/model_util_sunrgbd.py

Prompts

```
['create a SunrgbdDatasetConfig instance to access 10-class SUN RGB-D object type mappings and mean size arrays', 'convert a 3D bounding box size to its discrete size class and residual using SunrgbdDatasetConfig', 'convert a continuous heading angle to a discrete class ID and residual angle using SunrgbdDatasetConfig', 'reconstruct a 7D oriented bounding box from center, heading class, heading residual, size class, and size residual', 'invert a discrete heading class ID and residual back to a continuous angle using SunrgbdDatasetConfig', 'extract SUN RGB-D scene point clouds and bounding boxes from an index file to an output folder', 'visualize SUN RGB-D data by projecting depth points onto images and drawing 2D and 3D bounding boxes', 'compute median 3D bounding box sizes for each object class in the SUN RGB-D dataset', 'generate SUN RGB-D V1 dataset with 50k point clouds, bounding boxes, and ground truth votes', 'generate SUN RGB-D V2 dataset with 50k point clouds, bounding boxes, and ground truth votes', 'create a SunrgbdDetectionVotesDataset instance with train split, 20000 points, and augmentation enabled', 'load a point cloud sample with bounding boxes and vote labels from the dataset by index', 'visualize point votes and vote mask labels by writing PLY files for object points and three vote targets', 'visualize oriented bounding box ground truth by reconstructing OBBs from heading and size class labels', 'compute the number of objects for each semantic class across all scans in the dataset', 'create a SUNObject3d object by parsing a space-delimited label line with class name, 2D box, centroid, dimensions, and orientation', 'create a SUNRGBD_Calibration object from a calibration file containing Rtilt rotation matrix and camera intrinsic matrix K', 'compute 3D bounding box corners and project them to 2D image coordinates using a SUNObject3d and calibration object', 'draw a 3D bounding box projected to 2D on an image using eight vertex coordinates and optional color and thickness', 'extract point cloud points that fall inside a 3D bounding box defined by eight corner vertices using Delaunay hull']
```

Usage

```
{'create_SunrgbdDatasetConfig': 'create a SunrgbdDatasetConfig instance to access 10-class SUN RGB-D object type mappings and mean size arrays', 'convert_size2class': 'convert a 3D bounding box size to its discrete size class and residual using SunrgbdDatasetConfig', 'convert_angle2class': 'convert a continuous heading angle to a discrete class ID and residual angle using SunrgbdDatasetConfig', 'reconstruct_obb_from_params': 'reconstruct a 7D oriented bounding box from center, heading class, heading residual, size class, and size residual', 'invert_class2angle': 'invert a discrete heading class ID and residual back to a continuous angle using SunrgbdDatasetConfig'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/datasets/sunrgbd/sunrgbd_data.py

Prompts

```
['create a SunrgbdDatasetConfig instance to access 10-class SUN RGB-D object type mappings and mean size arrays', 'convert a 3D bounding box size to its discrete size class and residual using SunrgbdDatasetConfig', 'convert a continuous heading angle to a discrete class ID and residual angle using SunrgbdDatasetConfig', 'reconstruct a 7D oriented bounding box from center, heading class, heading residual, size class, and size residual', 'invert a discrete heading class ID and residual back to a continuous angle using SunrgbdDatasetConfig', 'extract SUN RGB-D scene point clouds and bounding boxes from an index file to an output folder', 'visualize SUN RGB-D data by projecting depth points onto images and drawing 2D and 3D bounding boxes', 'compute median 3D bounding box sizes for each object class in the SUN RGB-D dataset', 'generate SUN RGB-D V1 dataset with 50k point clouds, bounding boxes, and ground truth votes', 'generate SUN RGB-D V2 dataset with 50k point clouds, bounding boxes, and ground truth votes', 'create a SunrgbdDetectionVotesDataset instance with train split, 20000 points, and augmentation enabled', 'load a point cloud sample with bounding boxes and vote labels from the dataset by index', 'visualize point votes and vote mask labels by writing PLY files for object points and three vote targets', 'visualize oriented bounding box ground truth by reconstructing OBBs from heading and size class labels', 'compute the number of objects for each semantic class across all scans in the dataset', 'create a SUNObject3d object by parsing a space-delimited label line with class name, 2D box, centroid, dimensions, and orientation', 'create a SUNRGBD_Calibration object from a calibration file containing Rtilt rotation matrix and camera intrinsic matrix K', 'compute 3D bounding box corners and project them to 2D image coordinates using a SUNObject3d and calibration object', 'draw a 3D bounding box projected to 2D on an image using eight vertex coordinates and optional color and thickness', 'extract point cloud points that fall inside a 3D bounding box defined by eight corner vertices using Delaunay hull']
```

Usage

```
{'run_extract_sunrgbd_data': 'extract SUN RGB-D scene point clouds and bounding boxes from an index file to an output folder', 'run_data_viz': 'visualize SUN RGB-D data by projecting depth points onto images and drawing 2D and 3D bounding boxes', 'run_compute_median_size': 'compute median 3D bounding box sizes for each object class in the SUN RGB-D dataset', 'run_gen_v1_data': 'generate SUN RGB-D V1 dataset with 50k point clouds, bounding boxes, and ground truth votes', 'run_gen_v2_data': 'generate SUN RGB-D V2 dataset with 50k point clouds, bounding boxes, and ground truth votes'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/datasets/sunrgbd/sunrgbd_detection_dataset.py

Prompts

```
['create a SunrgbdDatasetConfig instance to access 10-class SUN RGB-D object type mappings and mean size arrays', 'convert a 3D bounding box size to its discrete size class and residual using SunrgbdDatasetConfig', 'convert a continuous heading angle to a discrete class ID and residual angle using SunrgbdDatasetConfig', 'reconstruct a 7D oriented bounding box from center, heading class, heading residual, size class, and size residual', 'invert a discrete heading class ID and residual back to a continuous angle using SunrgbdDatasetConfig', 'extract SUN RGB-D scene point clouds and bounding boxes from an index file to an output folder', 'visualize SUN RGB-D data by projecting depth points onto images and drawing 2D and 3D bounding boxes', 'compute median 3D bounding box sizes for each object class in the SUN RGB-D dataset', 'generate SUN RGB-D V1 dataset with 50k point clouds, bounding boxes, and ground truth votes', 'generate SUN RGB-D V2 dataset with 50k point clouds, bounding boxes, and ground truth votes', 'create a SunrgbdDetectionVotesDataset instance with train split, 20000 points, and augmentation enabled', 'load a point cloud sample with bounding boxes and vote labels from the dataset by index', 'visualize point votes and vote mask labels by writing PLY files for object points and three vote targets', 'visualize oriented bounding box ground truth by reconstructing OBBs from heading and size class labels', 'compute the number of objects for each semantic class across all scans in the dataset', 'create a SUNObject3d object by parsing a space-delimited label line with class name, 2D box, centroid, dimensions, and orientation', 'create a SUNRGBD_Calibration object from a calibration file containing Rtilt rotation matrix and camera intrinsic matrix K', 'compute 3D bounding box corners and project them to 2D image coordinates using a SUNObject3d and calibration object', 'draw a 3D bounding box projected to 2D on an image using eight vertex coordinates and optional color and thickness', 'extract point cloud points that fall inside a 3D bounding box defined by eight corner vertices using Delaunay hull']
```

Usage

```
{'create_dataset_instance': 'create a SunrgbdDetectionVotesDataset instance with train split, 20000 points, and augmentation enabled', 'load_point_cloud_sample': 'load a point cloud sample with bounding boxes and vote labels from the dataset by index', 'visualize_point_votes': 'visualize point votes and vote mask labels by writing PLY files for object points and three vote targets', 'visualize_oriented_bounding_boxes': 'visualize oriented bounding box ground truth by reconstructing OBBs from heading and size class labels', 'compute_semantic_class_statistics': 'compute the number of objects for each semantic class across all scans in the dataset'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/datasets/sunrgbd/sunrgbd_utils.py

Prompts

```
['create a SunrgbdDatasetConfig instance to access 10-class SUN RGB-D object type mappings and mean size arrays', 'convert a 3D bounding box size to its discrete size class and residual using SunrgbdDatasetConfig', 'convert a continuous heading angle to a discrete class ID and residual angle using SunrgbdDatasetConfig', 'reconstruct a 7D oriented bounding box from center, heading class, heading residual, size class, and size residual', 'invert a discrete heading class ID and residual back to a continuous angle using SunrgbdDatasetConfig', 'extract SUN RGB-D scene point clouds and bounding boxes from an index file to an output folder', 'visualize SUN RGB-D data by projecting depth points onto images and drawing 2D and 3D bounding boxes', 'compute median 3D bounding box sizes for each object class in the SUN RGB-D dataset', 'generate SUN RGB-D V1 dataset with 50k point clouds, bounding boxes, and ground truth votes', 'generate SUN RGB-D V2 dataset with 50k point clouds, bounding boxes, and ground truth votes', 'create a SunrgbdDetectionVotesDataset instance with train split, 20000 points, and augmentation enabled', 'load a point cloud sample with bounding boxes and vote labels from the dataset by index', 'visualize point votes and vote mask labels by writing PLY files for object points and three vote targets', 'visualize oriented bounding box ground truth by reconstructing OBBs from heading and size class labels', 'compute the number of objects for each semantic class across all scans in the dataset', 'create a SUNObject3d object by parsing a space-delimited label line with class name, 2D box, centroid, dimensions, and orientation', 'create a SUNRGBD_Calibration object from a calibration file containing Rtilt rotation matrix and camera intrinsic matrix K', 'compute 3D bounding box corners and project them to 2D image coordinates using a SUNObject3d and calibration object', 'draw a 3D bounding box projected to 2D on an image using eight vertex coordinates and optional color and thickness', 'extract point cloud points that fall inside a 3D bounding box defined by eight corner vertices using Delaunay hull']
```

Usage

```
{'create_SUNObject3d_from_label_line': 'create a SUNObject3d object by parsing a space-delimited label line with class name, 2D box, centroid, dimensions, and orientation', 'create_SUNRGBD_Calibration_from_file': 'create a SUNRGBD_Calibration object from a calibration file containing Rtilt rotation matrix and camera intrinsic matrix K', 'compute_box_3d_corners': 'compute 3D bounding box corners and project them to 2D image coordinates using a SUNObject3d and calibration object', 'draw_projected_box3d_on_image': 'draw a 3D bounding box projected to 2D on an image using eight vertex coordinates and optional color and thickness', 'extract_pc_in_box3d': 'extract point cloud points that fall inside a 3D bounding box defined by eight corner vertices using Delaunay hull'}
```

