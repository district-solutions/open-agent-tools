# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/data/scannet/SensorData.py

Prompts

```
['load a ScanNet .sens binary file and parse all RGBD frames with camera intrinsics and extrinsics', 'export decompressed depth images from a ScanNet sensor file to PNG files with optional resizing and frame skipping', 'export decompressed color images from a ScanNet sensor file to JPEG files with optional resizing and frame skipping', 'export camera-to-world pose matrices from each RGBD frame in a ScanNet sensor file to text files', 'export color and depth intrinsic and extrinsic camera matrices from a ScanNet sensor file to text files', 'run the script to extract point clouds from ScanNet RGB-D image pairs into PLY and NPY files', 'run the pc2obj function to write a numpy point cloud array to an OBJ file', 'create a 3D point cloud from RGB and depth images using Open3D RGBDImage fusion', 'summarize the extract_pointcloud script that samples 50k points per frame from depth scans', 'review the pc2obj function that exports point cloud vertices to OBJ format']
```

Usage

```
{'load_scannet_sensor_data': 'load a ScanNet .sens binary file and parse all RGBD frames with camera intrinsics and extrinsics', 'export_depth_images': 'export decompressed depth images from a ScanNet sensor file to PNG files with optional resizing and frame skipping', 'export_color_images': 'export decompressed color images from a ScanNet sensor file to JPEG files with optional resizing and frame skipping', 'export_camera_poses': 'export camera-to-world pose matrices from each RGBD frame in a ScanNet sensor file to text files', 'export_camera_intrinsics': 'export color and depth intrinsic and extrinsic camera matrices from a ScanNet sensor file to text files'}
```

## File: facebookresearch_depthcontrast/data/scannet/extract_pointcloud.py

Prompts

```
['load a ScanNet .sens binary file and parse all RGBD frames with camera intrinsics and extrinsics', 'export decompressed depth images from a ScanNet sensor file to PNG files with optional resizing and frame skipping', 'export decompressed color images from a ScanNet sensor file to JPEG files with optional resizing and frame skipping', 'export camera-to-world pose matrices from each RGBD frame in a ScanNet sensor file to text files', 'export color and depth intrinsic and extrinsic camera matrices from a ScanNet sensor file to text files', 'run the script to extract point clouds from ScanNet RGB-D image pairs into PLY and NPY files', 'run the pc2obj function to write a numpy point cloud array to an OBJ file', 'create a 3D point cloud from RGB and depth images using Open3D RGBDImage fusion', 'summarize the extract_pointcloud script that samples 50k points per frame from depth scans', 'review the pc2obj function that exports point cloud vertices to OBJ format']
```

Usage

```
{'run_extract_pointcloud': 'run the script to extract point clouds from ScanNet RGB-D image pairs into PLY and NPY files', 'run_pc2obj': 'run the pc2obj function to write a numpy point cloud array to an OBJ file', 'create_rgbd_pointcloud': 'create a 3D point cloud from RGB and depth images using Open3D RGBDImage fusion', 'summarize_extract_pointcloud': 'summarize the extract_pointcloud script that samples 50k points per frame from depth scans', 'review_pc2obj': 'review the pc2obj function that exports point cloud vertices to OBJ format'}
```

