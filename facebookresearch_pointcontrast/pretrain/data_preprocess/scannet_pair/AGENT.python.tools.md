# Agent Python Tools

- repo: facebookresearch/pointcontrast
- repo_uri: https://github.com/facebookresearch/pointcontrast

## File: facebookresearch_pointcontrast/pretrain/data_preprocess/scannet_pair/SensorData.py

Prompts

```
['load a Scannet sensor data file and parse all RGBD frames with camera intrinsics and extrinsics', 'export decompressed depth images from Scannet sensor data frames to a directory as PNG files', 'export decompressed color images from Scannet sensor data frames to a directory as PNG files', 'export camera-to-world pose matrices from each RGBD frame to text files in a directory', 'export color and depth intrinsic and extrinsic camera matrices to text files in a directory', 'run the script to compute pairwise overlap ratios for all point cloud NPZ files in a directory', 'run the script to create an Open3D point cloud from XYZ coordinates with optional voxel downsampling', 'run the script to compute the overlap ratio between two Open3D point clouds using voxel-based matching', 'run the script to find matching point indices between a source point cloud and a KDTree within a search radius', 'review the script that loads NPZ point clouds, computes pairwise overlap, and writes results to overlap.txt', 'read a PLY file from disk using PlyData.read and access element data by name', 'write PLY data to a file using PlyData.write with text or binary format', 'construct a PlyElement from a numpy structured array using PlyElement.describe', 'create a PlyData object from PlyElement instances with specified byte order and comments', 'convert an array of arrays into a 2D numpy array using make2d', 'run the script to extract point clouds from ScanNet depth images and poses into PLY files', 'run the script with --save_npz to extract point clouds and save them as NPZ files', 'create a function that writes an Nx3 numpy array of 3D points to a PLY file', 'refactor the write_ply function to support additional point attributes like color or normals', 'review the depth image to 3D point cloud projection logic using camera intrinsics and poses']
```

Usage

```
{'load_scannet_sensor_data': 'load a Scannet sensor data file and parse all RGBD frames with camera intrinsics and extrinsics', 'export_depth_images': 'export decompressed depth images from Scannet sensor data frames to a directory as PNG files', 'export_color_images': 'export decompressed color images from Scannet sensor data frames to a directory as PNG files', 'export_camera_poses': 'export camera-to-world pose matrices from each RGBD frame to text files in a directory', 'export_camera_intrinsics': 'export color and depth intrinsic and extrinsic camera matrices to text files in a directory'}
```

## File: facebookresearch_pointcontrast/pretrain/data_preprocess/scannet_pair/compute_full_overlapping.py

Prompts

```
['load a Scannet sensor data file and parse all RGBD frames with camera intrinsics and extrinsics', 'export decompressed depth images from Scannet sensor data frames to a directory as PNG files', 'export decompressed color images from Scannet sensor data frames to a directory as PNG files', 'export camera-to-world pose matrices from each RGBD frame to text files in a directory', 'export color and depth intrinsic and extrinsic camera matrices to text files in a directory', 'run the script to compute pairwise overlap ratios for all point cloud NPZ files in a directory', 'run the script to create an Open3D point cloud from XYZ coordinates with optional voxel downsampling', 'run the script to compute the overlap ratio between two Open3D point clouds using voxel-based matching', 'run the script to find matching point indices between a source point cloud and a KDTree within a search radius', 'review the script that loads NPZ point clouds, computes pairwise overlap, and writes results to overlap.txt', 'read a PLY file from disk using PlyData.read and access element data by name', 'write PLY data to a file using PlyData.write with text or binary format', 'construct a PlyElement from a numpy structured array using PlyElement.describe', 'create a PlyData object from PlyElement instances with specified byte order and comments', 'convert an array of arrays into a 2D numpy array using make2d', 'run the script to extract point clouds from ScanNet depth images and poses into PLY files', 'run the script with --save_npz to extract point clouds and save them as NPZ files', 'create a function that writes an Nx3 numpy array of 3D points to a PLY file', 'refactor the write_ply function to support additional point attributes like color or normals', 'review the depth image to 3D point cloud projection logic using camera intrinsics and poses']
```

Usage

```
{'run_compute_overlap': 'run the script to compute pairwise overlap ratios for all point cloud NPZ files in a directory', 'run_make_open3d_point_cloud': 'run the script to create an Open3D point cloud from XYZ coordinates with optional voxel downsampling', 'run_compute_overlap_ratio': 'run the script to compute the overlap ratio between two Open3D point clouds using voxel-based matching', 'run_get_matching_indices': 'run the script to find matching point indices between a source point cloud and a KDTree within a search radius', 'review_compute_full_overlapping': 'review the script that loads NPZ point clouds, computes pairwise overlap, and writes results to overlap.txt'}
```

## File: facebookresearch_pointcontrast/pretrain/data_preprocess/scannet_pair/plyfile.py

Prompts

```
['load a Scannet sensor data file and parse all RGBD frames with camera intrinsics and extrinsics', 'export decompressed depth images from Scannet sensor data frames to a directory as PNG files', 'export decompressed color images from Scannet sensor data frames to a directory as PNG files', 'export camera-to-world pose matrices from each RGBD frame to text files in a directory', 'export color and depth intrinsic and extrinsic camera matrices to text files in a directory', 'run the script to compute pairwise overlap ratios for all point cloud NPZ files in a directory', 'run the script to create an Open3D point cloud from XYZ coordinates with optional voxel downsampling', 'run the script to compute the overlap ratio between two Open3D point clouds using voxel-based matching', 'run the script to find matching point indices between a source point cloud and a KDTree within a search radius', 'review the script that loads NPZ point clouds, computes pairwise overlap, and writes results to overlap.txt', 'read a PLY file from disk using PlyData.read and access element data by name', 'write PLY data to a file using PlyData.write with text or binary format', 'construct a PlyElement from a numpy structured array using PlyElement.describe', 'create a PlyData object from PlyElement instances with specified byte order and comments', 'convert an array of arrays into a 2D numpy array using make2d', 'run the script to extract point clouds from ScanNet depth images and poses into PLY files', 'run the script with --save_npz to extract point clouds and save them as NPZ files', 'create a function that writes an Nx3 numpy array of 3D points to a PLY file', 'refactor the write_ply function to support additional point attributes like color or normals', 'review the depth image to 3D point cloud projection logic using camera intrinsics and poses']
```

Usage

```
{'read_ply_file': 'read a PLY file from disk using PlyData.read and access element data by name', 'write_ply_file': 'write PLY data to a file using PlyData.write with text or binary format', 'describe_ply_element': 'construct a PlyElement from a numpy structured array using PlyElement.describe', 'create_ply_data': 'create a PlyData object from PlyElement instances with specified byte order and comments', 'make2d_array': 'convert an array of arrays into a 2D numpy array using make2d'}
```

## File: facebookresearch_pointcontrast/pretrain/data_preprocess/scannet_pair/point_cloud_extractor.py

Prompts

```
['load a Scannet sensor data file and parse all RGBD frames with camera intrinsics and extrinsics', 'export decompressed depth images from Scannet sensor data frames to a directory as PNG files', 'export decompressed color images from Scannet sensor data frames to a directory as PNG files', 'export camera-to-world pose matrices from each RGBD frame to text files in a directory', 'export color and depth intrinsic and extrinsic camera matrices to text files in a directory', 'run the script to compute pairwise overlap ratios for all point cloud NPZ files in a directory', 'run the script to create an Open3D point cloud from XYZ coordinates with optional voxel downsampling', 'run the script to compute the overlap ratio between two Open3D point clouds using voxel-based matching', 'run the script to find matching point indices between a source point cloud and a KDTree within a search radius', 'review the script that loads NPZ point clouds, computes pairwise overlap, and writes results to overlap.txt', 'read a PLY file from disk using PlyData.read and access element data by name', 'write PLY data to a file using PlyData.write with text or binary format', 'construct a PlyElement from a numpy structured array using PlyElement.describe', 'create a PlyData object from PlyElement instances with specified byte order and comments', 'convert an array of arrays into a 2D numpy array using make2d', 'run the script to extract point clouds from ScanNet depth images and poses into PLY files', 'run the script with --save_npz to extract point clouds and save them as NPZ files', 'create a function that writes an Nx3 numpy array of 3D points to a PLY file', 'refactor the write_ply function to support additional point attributes like color or normals', 'review the depth image to 3D point cloud projection logic using camera intrinsics and poses']
```

Usage

```
{'run_point_cloud_extractor': 'run the script to extract point clouds from ScanNet depth images and poses into PLY files', 'run_point_cloud_extractor_npz': 'run the script with --save_npz to extract point clouds and save them as NPZ files', 'create_write_ply_function': 'create a function that writes an Nx3 numpy array of 3D points to a PLY file', 'refactor_write_ply': 'refactor the write_ply function to support additional point attributes like color or normals', 'review_depth_to_point_cloud': 'review the depth image to 3D point cloud projection logic using camera intrinsics and poses'}
```

