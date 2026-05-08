# Agent Python Tools

- repo: facebookresearch/hot3d
- repo_uri: https://github.com/facebookresearch/hot3d

## File: facebookresearch_hot3d/hot3d/Hot3DVisualizer.py

Prompts

```
['build a Hot3DVisualizer instance with a Hot3dDataProvider and optional hand type for 3D visualization', 'run log_static_assets to log camera calibration, glasses outline, and point cloud as static Rerun entities', 'run log_dynamic_assets to log device pose, hand poses, object poses, images, and eye gaze at a timestamp', 'review the log_hands static method that logs hand skeleton joints, mesh vertices, and triangular mesh faces to Rerun', 'review the log_object_poses static method that logs 3D object poses and CAD assets with caching to Rerun', 'initialize a Hot3dDataProvider from a sequence folder with an object library and optional MANO hand model', 'get a dictionary of data statistics for dynamic objects, hand poses, and box2d annotations from the provider', 'get the headset device type (Aria or Quest3) used for a recording sequence', "get the scene metadata dictionary loaded from the sequence folder's metadata JSON file", 'access the dynamic object 3D pose data provider to retrieve object pose trajectories from CSV', 'load all 3D object meshes from a HOT3D scene and return them keyed by object UID', 'add object meshes to a pyrender scene at their poses for a given timestamp', 'configure a rectilinear camera node in the scene using device calibration at a timestamp', 'add hand meshes with vertices and normals to the scene for a given timestamp', 'render color, depth, and segmentation images from a pyrender scene using an offscreen renderer', 'run the hot3d data viewer CLI to visualize a sequence folder with rerun', 'run execute_rerun to log hot3d sequence data to a rerun session or .rrd file', 'run parse_args to get command line arguments for the hot3d viewer including sequence and object library paths', 'review the Hot3dDataProvider initialization and data statistics retrieval in the viewer module', 'review the Hot3DVisualizer usage for logging static and dynamic assets to rerun']
```

Usage

```
{'build_Hot3DVisualizer': 'build a Hot3DVisualizer instance with a Hot3dDataProvider and optional hand type for 3D visualization', 'run_log_static_assets': 'run log_static_assets to log camera calibration, glasses outline, and point cloud as static Rerun entities', 'run_log_dynamic_assets': 'run log_dynamic_assets to log device pose, hand poses, object poses, images, and eye gaze at a timestamp', 'review_log_hands': 'review the log_hands static method that logs hand skeleton joints, mesh vertices, and triangular mesh faces to Rerun', 'review_log_object_poses': 'review the log_object_poses static method that logs 3D object poses and CAD assets with caching to Rerun'}
```

## File: facebookresearch_hot3d/hot3d/dataset_api.py

Prompts

```
['build a Hot3DVisualizer instance with a Hot3dDataProvider and optional hand type for 3D visualization', 'run log_static_assets to log camera calibration, glasses outline, and point cloud as static Rerun entities', 'run log_dynamic_assets to log device pose, hand poses, object poses, images, and eye gaze at a timestamp', 'review the log_hands static method that logs hand skeleton joints, mesh vertices, and triangular mesh faces to Rerun', 'review the log_object_poses static method that logs 3D object poses and CAD assets with caching to Rerun', 'initialize a Hot3dDataProvider from a sequence folder with an object library and optional MANO hand model', 'get a dictionary of data statistics for dynamic objects, hand poses, and box2d annotations from the provider', 'get the headset device type (Aria or Quest3) used for a recording sequence', "get the scene metadata dictionary loaded from the sequence folder's metadata JSON file", 'access the dynamic object 3D pose data provider to retrieve object pose trajectories from CSV', 'load all 3D object meshes from a HOT3D scene and return them keyed by object UID', 'add object meshes to a pyrender scene at their poses for a given timestamp', 'configure a rectilinear camera node in the scene using device calibration at a timestamp', 'add hand meshes with vertices and normals to the scene for a given timestamp', 'render color, depth, and segmentation images from a pyrender scene using an offscreen renderer', 'run the hot3d data viewer CLI to visualize a sequence folder with rerun', 'run execute_rerun to log hot3d sequence data to a rerun session or .rrd file', 'run parse_args to get command line arguments for the hot3d viewer including sequence and object library paths', 'review the Hot3dDataProvider initialization and data statistics retrieval in the viewer module', 'review the Hot3DVisualizer usage for logging static and dynamic assets to rerun']
```

Usage

```
{'init_hot3d_data_provider': 'initialize a Hot3dDataProvider from a sequence folder with an object library and optional MANO hand model', 'get_data_statistics': 'get a dictionary of data statistics for dynamic objects, hand poses, and box2d annotations from the provider', 'get_device_type': 'get the headset device type (Aria or Quest3) used for a recording sequence', 'get_sequence_metadata': "get the scene metadata dictionary loaded from the sequence folder's metadata JSON file", 'access_object_pose_provider': 'access the dynamic object 3D pose data provider to retrieve object pose trajectories from CSV'}
```

## File: facebookresearch_hot3d/hot3d/render_3d.py

Prompts

```
['build a Hot3DVisualizer instance with a Hot3dDataProvider and optional hand type for 3D visualization', 'run log_static_assets to log camera calibration, glasses outline, and point cloud as static Rerun entities', 'run log_dynamic_assets to log device pose, hand poses, object poses, images, and eye gaze at a timestamp', 'review the log_hands static method that logs hand skeleton joints, mesh vertices, and triangular mesh faces to Rerun', 'review the log_object_poses static method that logs 3D object poses and CAD assets with caching to Rerun', 'initialize a Hot3dDataProvider from a sequence folder with an object library and optional MANO hand model', 'get a dictionary of data statistics for dynamic objects, hand poses, and box2d annotations from the provider', 'get the headset device type (Aria or Quest3) used for a recording sequence', "get the scene metadata dictionary loaded from the sequence folder's metadata JSON file", 'access the dynamic object 3D pose data provider to retrieve object pose trajectories from CSV', 'load all 3D object meshes from a HOT3D scene and return them keyed by object UID', 'add object meshes to a pyrender scene at their poses for a given timestamp', 'configure a rectilinear camera node in the scene using device calibration at a timestamp', 'add hand meshes with vertices and normals to the scene for a given timestamp', 'render color, depth, and segmentation images from a pyrender scene using an offscreen renderer', 'run the hot3d data viewer CLI to visualize a sequence folder with rerun', 'run execute_rerun to log hot3d sequence data to a rerun session or .rrd file', 'run parse_args to get command line arguments for the hot3d viewer including sequence and object library paths', 'review the Hot3dDataProvider initialization and data statistics retrieval in the viewer module', 'review the Hot3DVisualizer usage for logging static and dynamic assets to rerun']
```

Usage

```
{'load_meshes_scene': 'load all 3D object meshes from a HOT3D scene and return them keyed by object UID', 'setup_objects_at_timestamp': 'add object meshes to a pyrender scene at their poses for a given timestamp', 'setup_camera_at_timestamp': 'configure a rectilinear camera node in the scene using device calibration at a timestamp', 'setup_hand_at_timestamp': 'add hand meshes with vertices and normals to the scene for a given timestamp', 'offscreen_render': 'render color, depth, and segmentation images from a pyrender scene using an offscreen renderer'}
```

## File: facebookresearch_hot3d/hot3d/viewer.py

Prompts

```
['build a Hot3DVisualizer instance with a Hot3dDataProvider and optional hand type for 3D visualization', 'run log_static_assets to log camera calibration, glasses outline, and point cloud as static Rerun entities', 'run log_dynamic_assets to log device pose, hand poses, object poses, images, and eye gaze at a timestamp', 'review the log_hands static method that logs hand skeleton joints, mesh vertices, and triangular mesh faces to Rerun', 'review the log_object_poses static method that logs 3D object poses and CAD assets with caching to Rerun', 'initialize a Hot3dDataProvider from a sequence folder with an object library and optional MANO hand model', 'get a dictionary of data statistics for dynamic objects, hand poses, and box2d annotations from the provider', 'get the headset device type (Aria or Quest3) used for a recording sequence', "get the scene metadata dictionary loaded from the sequence folder's metadata JSON file", 'access the dynamic object 3D pose data provider to retrieve object pose trajectories from CSV', 'load all 3D object meshes from a HOT3D scene and return them keyed by object UID', 'add object meshes to a pyrender scene at their poses for a given timestamp', 'configure a rectilinear camera node in the scene using device calibration at a timestamp', 'add hand meshes with vertices and normals to the scene for a given timestamp', 'render color, depth, and segmentation images from a pyrender scene using an offscreen renderer', 'run the hot3d data viewer CLI to visualize a sequence folder with rerun', 'run execute_rerun to log hot3d sequence data to a rerun session or .rrd file', 'run parse_args to get command line arguments for the hot3d viewer including sequence and object library paths', 'review the Hot3dDataProvider initialization and data statistics retrieval in the viewer module', 'review the Hot3DVisualizer usage for logging static and dynamic assets to rerun']
```

Usage

```
{'run_hot3d_viewer_cli': 'run the hot3d data viewer CLI to visualize a sequence folder with rerun', 'run_execute_rerun': 'run execute_rerun to log hot3d sequence data to a rerun session or .rrd file', 'run_parse_args': 'run parse_args to get command line arguments for the hot3d viewer including sequence and object library paths', 'review_Hot3dDataProvider': 'review the Hot3dDataProvider initialization and data statistics retrieval in the viewer module', 'review_Hot3DVisualizer': 'review the Hot3DVisualizer usage for logging static and dynamic assets to rerun'}
```

