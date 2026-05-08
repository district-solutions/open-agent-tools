# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/pretrain/scannet_pair/SensorData.py

Prompts

```
['load a Scannet .sens file and parse all RGBD frames with camera intrinsics and extrinsics', 'export decompressed depth images from a SensorData object to a directory as PNG files', 'export decompressed color images from a SensorData object to a directory as PNG files', 'export camera-to-world pose matrices for each frame to text files in a directory', 'export color and depth intrinsic and extrinsic matrices to text files in a directory', 'run the script to compute pairwise overlap ratios for all point cloud NPZ files in a directory', 'run make_open3d_point_cloud to create an Open3D point cloud from XYZ numpy array with optional voxel downsampling', 'run compute_overlap_ratio to calculate the overlap ratio between two Open3D point clouds using voxel-based matching', 'run get_matching_indices to find matching point index pairs between a source point cloud and a KDTree within a search radius', 'review the script that loads NPZ point clouds, computes pairwise overlap, and writes results to overlap.txt', 'read a PLY file from a path or stream using PlyData.read and access element data', 'write PLY data to a file by creating PlyData with PlyElement.describe and calling write', 'construct a PlyElement from a numpy structured array using PlyElement.describe for writing PLY files', 'convert an array of arrays into a 2D numpy array using the make2d helper function', 'parse a PLY file header from a stream using PlyData._parse_header to inspect format and elements']
```

Usage

```
{'load_scannet_sensor_data': 'load a Scannet .sens file and parse all RGBD frames with camera intrinsics and extrinsics', 'export_depth_images': 'export decompressed depth images from a SensorData object to a directory as PNG files', 'export_color_images': 'export decompressed color images from a SensorData object to a directory as PNG files', 'export_camera_poses': 'export camera-to-world pose matrices for each frame to text files in a directory', 'export_camera_intrinsics': 'export color and depth intrinsic and extrinsic matrices to text files in a directory'}
```

## File: facebookresearch_contrastivescenecontexts/pretrain/scannet_pair/compute_full_overlapping.py

Prompts

```
['load a Scannet .sens file and parse all RGBD frames with camera intrinsics and extrinsics', 'export decompressed depth images from a SensorData object to a directory as PNG files', 'export decompressed color images from a SensorData object to a directory as PNG files', 'export camera-to-world pose matrices for each frame to text files in a directory', 'export color and depth intrinsic and extrinsic matrices to text files in a directory', 'run the script to compute pairwise overlap ratios for all point cloud NPZ files in a directory', 'run make_open3d_point_cloud to create an Open3D point cloud from XYZ numpy array with optional voxel downsampling', 'run compute_overlap_ratio to calculate the overlap ratio between two Open3D point clouds using voxel-based matching', 'run get_matching_indices to find matching point index pairs between a source point cloud and a KDTree within a search radius', 'review the script that loads NPZ point clouds, computes pairwise overlap, and writes results to overlap.txt', 'read a PLY file from a path or stream using PlyData.read and access element data', 'write PLY data to a file by creating PlyData with PlyElement.describe and calling write', 'construct a PlyElement from a numpy structured array using PlyElement.describe for writing PLY files', 'convert an array of arrays into a 2D numpy array using the make2d helper function', 'parse a PLY file header from a stream using PlyData._parse_header to inspect format and elements']
```

Usage

```
{'run_compute_overlap': 'run the script to compute pairwise overlap ratios for all point cloud NPZ files in a directory', 'run_make_open3d_point_cloud': 'run make_open3d_point_cloud to create an Open3D point cloud from XYZ numpy array with optional voxel downsampling', 'run_compute_overlap_ratio': 'run compute_overlap_ratio to calculate the overlap ratio between two Open3D point clouds using voxel-based matching', 'run_get_matching_indices': 'run get_matching_indices to find matching point index pairs between a source point cloud and a KDTree within a search radius', 'review_compute_full_overlapping': 'review the script that loads NPZ point clouds, computes pairwise overlap, and writes results to overlap.txt'}
```

## File: facebookresearch_contrastivescenecontexts/pretrain/scannet_pair/plyfile.py

Prompts

```
['load a Scannet .sens file and parse all RGBD frames with camera intrinsics and extrinsics', 'export decompressed depth images from a SensorData object to a directory as PNG files', 'export decompressed color images from a SensorData object to a directory as PNG files', 'export camera-to-world pose matrices for each frame to text files in a directory', 'export color and depth intrinsic and extrinsic matrices to text files in a directory', 'run the script to compute pairwise overlap ratios for all point cloud NPZ files in a directory', 'run make_open3d_point_cloud to create an Open3D point cloud from XYZ numpy array with optional voxel downsampling', 'run compute_overlap_ratio to calculate the overlap ratio between two Open3D point clouds using voxel-based matching', 'run get_matching_indices to find matching point index pairs between a source point cloud and a KDTree within a search radius', 'review the script that loads NPZ point clouds, computes pairwise overlap, and writes results to overlap.txt', 'read a PLY file from a path or stream using PlyData.read and access element data', 'write PLY data to a file by creating PlyData with PlyElement.describe and calling write', 'construct a PlyElement from a numpy structured array using PlyElement.describe for writing PLY files', 'convert an array of arrays into a 2D numpy array using the make2d helper function', 'parse a PLY file header from a stream using PlyData._parse_header to inspect format and elements']
```

Usage

```
{'read_ply_file': 'read a PLY file from a path or stream using PlyData.read and access element data', 'write_ply_file': 'write PLY data to a file by creating PlyData with PlyElement.describe and calling write', 'describe_ply_element': 'construct a PlyElement from a numpy structured array using PlyElement.describe for writing PLY files', 'make2d_array': 'convert an array of arrays into a 2D numpy array using the make2d helper function', 'parse_ply_header': 'parse a PLY file header from a stream using PlyData._parse_header to inspect format and elements'}
```

