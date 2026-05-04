# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/scripts/aria_utils.py

Prompts

```
['interpolate a PoseSE3 from a closed-loop trajectory at a given capture timestamp in nanoseconds', 'process an AriaFrame by undistorting the image and saving the rectified output to disk', 'read a transforms.json metadata file and return a list of AriaFrame dataclass objects', 'store a point cloud with xyz coordinates and rgb colors to a PLY file on disk', 'project 3D world points into 2D image coordinates using a camera pose and intrinsic matrix', 'run the CLI to extract Aria VRS data with MPS output into JSON format with rectified images', 'run to_aria_image_frame to convert VRS sensor data into AriaImageFrame objects with interpolated poses', 'run to_frame_json to transform an AriaImageFrame into a JSON dictionary with camera intrinsics and poses', 'run visualize_frames to open a Rerun viewer showing 3D point clouds and camera frames over time', 'run run_single_sequence to process a single VRS recording end to end including rectification and JSON export']
```

Usage

```
{'interpolate_aria_pose': 'interpolate a PoseSE3 from a closed-loop trajectory at a given capture timestamp in nanoseconds', 'process_frame': 'process an AriaFrame by undistorting the image and saving the rectified output to disk', 'read_frames_from_metadata': 'read a transforms.json metadata file and return a list of AriaFrame dataclass objects', 'storePly': 'store a point cloud with xyz coordinates and rgb colors to a PLY file on disk', 'project': 'project 3D world points into 2D image coordinates using a camera pose and intrinsic matrix'}
```

## File: facebookresearch_4dgt/tlod/scripts/extract_aria_vrs.py

Prompts

```
['interpolate a PoseSE3 from a closed-loop trajectory at a given capture timestamp in nanoseconds', 'process an AriaFrame by undistorting the image and saving the rectified output to disk', 'read a transforms.json metadata file and return a list of AriaFrame dataclass objects', 'store a point cloud with xyz coordinates and rgb colors to a PLY file on disk', 'project 3D world points into 2D image coordinates using a camera pose and intrinsic matrix', 'run the CLI to extract Aria VRS data with MPS output into JSON format with rectified images', 'run to_aria_image_frame to convert VRS sensor data into AriaImageFrame objects with interpolated poses', 'run to_frame_json to transform an AriaImageFrame into a JSON dictionary with camera intrinsics and poses', 'run visualize_frames to open a Rerun viewer showing 3D point clouds and camera frames over time', 'run run_single_sequence to process a single VRS recording end to end including rectification and JSON export']
```

Usage

```
{'run_extract_aria_vrs': 'run the CLI to extract Aria VRS data with MPS output into JSON format with rectified images', 'run_to_aria_image_frame': 'run to_aria_image_frame to convert VRS sensor data into AriaImageFrame objects with interpolated poses', 'run_to_frame_json': 'run to_frame_json to transform an AriaImageFrame into a JSON dictionary with camera intrinsics and poses', 'run_visualize_frames': 'run visualize_frames to open a Rerun viewer showing 3D point clouds and camera frames over time', 'run_run_single_sequence': 'run run_single_sequence to process a single VRS recording end to end including rectification and JSON export'}
```

