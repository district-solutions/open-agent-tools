# Agent Python Tools

- repo: facebookresearch/open-eqa
- repo_uri: https://github.com/facebookresearch/open-eqa

## File: facebookresearch_open-eqa/data/scannet/SensorData.py

Prompts

```
['load a ScanNet .sens binary file using SensorData to parse frames and camera intrinsics', 'export depth images from a SensorData object to a directory as 16-bit PNG files', 'export color images from a SensorData object to a directory as PNG files', 'export camera-to-world pose matrices from SensorData frames to text files in a directory', 'export color and depth intrinsic and extrinsic matrices from SensorData to text files', 'run the script to extract RGB and depth frames from ScanNet sensor data files', 'run the script with --rgb-only flag to extract only color images from ScanNet scenes', 'run the script with --max-num-frames to limit frames extracted per scene', 'review the parse_args function that configures CLI arguments for dataset path, ScanNet root, and output directory', 'review the get_folder_to_scene function that maps episode history folders to ScanNet scene names']
```

Usage

```
{'load_scannet_sensor_data': 'load a ScanNet .sens binary file using SensorData to parse frames and camera intrinsics', 'export_depth_images': 'export depth images from a SensorData object to a directory as 16-bit PNG files', 'export_color_images': 'export color images from a SensorData object to a directory as PNG files', 'export_camera_poses': 'export camera-to-world pose matrices from SensorData frames to text files in a directory', 'export_camera_intrinsics': 'export color and depth intrinsic and extrinsic matrices from SensorData to text files'}
```

## File: facebookresearch_open-eqa/data/scannet/extract-frames.py

Prompts

```
['load a ScanNet .sens binary file using SensorData to parse frames and camera intrinsics', 'export depth images from a SensorData object to a directory as 16-bit PNG files', 'export color images from a SensorData object to a directory as PNG files', 'export camera-to-world pose matrices from SensorData frames to text files in a directory', 'export color and depth intrinsic and extrinsic matrices from SensorData to text files', 'run the script to extract RGB and depth frames from ScanNet sensor data files', 'run the script with --rgb-only flag to extract only color images from ScanNet scenes', 'run the script with --max-num-frames to limit frames extracted per scene', 'review the parse_args function that configures CLI arguments for dataset path, ScanNet root, and output directory', 'review the get_folder_to_scene function that maps episode history folders to ScanNet scene names']
```

Usage

```
{'run_extract_frames': 'run the script to extract RGB and depth frames from ScanNet sensor data files', 'run_extract_rgb_only': 'run the script with --rgb-only flag to extract only color images from ScanNet scenes', 'run_extract_with_max_frames': 'run the script with --max-num-frames to limit frames extracted per scene', 'review_parse_args': 'review the parse_args function that configures CLI arguments for dataset path, ScanNet root, and output directory', 'review_get_folder_to_scene': 'review the get_folder_to_scene function that maps episode history folders to ScanNet scene names'}
```

