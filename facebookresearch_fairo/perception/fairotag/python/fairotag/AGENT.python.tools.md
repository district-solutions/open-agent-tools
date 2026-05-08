# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/perception/fairotag/python/fairotag/camera.py

Prompts

```
['detect ArUco markers in an image and return their IDs, corners, and estimated poses', 'estimate the 3D pose of a specific registered ArUco marker from an image', 'calibrate camera intrinsics using a set of images of a ChArUco board', 'render detected ArUco marker edges, IDs, and 3D axes onto an image', 'set camera intrinsics from a CameraIntrinsics object, a 3x3 matrix, or keyword arguments', 'create a FactorGraph instance to build a pose graph optimization problem with named variables', 'initialize a named pose variable in the FactorGraph with an optional Sophus SE3 pose', 'add a prior factor to anchor a named variable to a fixed pose with optional noise', 'add a between factor observation linking two named variables with a relative transform and noise', 'optimize the FactorGraph using Levenberg-Marquardt and return optimized poses as a Sophus SE3 dictionary', 'create a Scene object and add a camera and marker to the world frame', 'add a new coordinate frame with a given SE3 pose to the scene', 'estimate relative poses between frames using detected markers and a factor graph', 'calibrate extrinsics between cameras and markers using multiple snapshots and factor graph optimization', 'visualize the scene with markers, cameras, and frame axes using SceneViz', 'convert a Sophus SO3 rotation to a numpy quaternion array using so3_to_quat', 'extract xyz position and quaternion from a Sophus SE3 pose using se3_to_xyz_quat', 'build a Sophus SE3 pose from xyz position and quaternion arrays using xyz_quat_to_se3', 'convert a Sophus pose to a GTSAM Pose3 using sophus2gtsam', 'serialize camera intrinsics to a dictionary using intrinsics2dict and back with dict2intrinsics', 'create a SceneViz instance to initialize a 3D matplotlib figure for visualization', 'draw a camera pyramid at a given pose with configurable size and color', 'draw RGB coordinate axes at a given SE3 pose with a specified length', 'draw a square marker outline at a given pose with optional ID label', 'render the 3D scene with auto-scaled axis limits and display the plot']
```

Usage

```
{'detect_aruco_markers': 'detect ArUco markers in an image and return their IDs, corners, and estimated poses', 'estimate_single_marker_pose': 'estimate the 3D pose of a specific registered ArUco marker from an image', 'calibrate_camera_charuco': 'calibrate camera intrinsics using a set of images of a ChArUco board', 'render_detected_markers': 'render detected ArUco marker edges, IDs, and 3D axes onto an image', 'set_camera_intrinsics': 'set camera intrinsics from a CameraIntrinsics object, a 3x3 matrix, or keyword arguments'}
```

## File: facebookresearch_fairo/perception/fairotag/python/fairotag/graph.py

Prompts

```
['detect ArUco markers in an image and return their IDs, corners, and estimated poses', 'estimate the 3D pose of a specific registered ArUco marker from an image', 'calibrate camera intrinsics using a set of images of a ChArUco board', 'render detected ArUco marker edges, IDs, and 3D axes onto an image', 'set camera intrinsics from a CameraIntrinsics object, a 3x3 matrix, or keyword arguments', 'create a FactorGraph instance to build a pose graph optimization problem with named variables', 'initialize a named pose variable in the FactorGraph with an optional Sophus SE3 pose', 'add a prior factor to anchor a named variable to a fixed pose with optional noise', 'add a between factor observation linking two named variables with a relative transform and noise', 'optimize the FactorGraph using Levenberg-Marquardt and return optimized poses as a Sophus SE3 dictionary', 'create a Scene object and add a camera and marker to the world frame', 'add a new coordinate frame with a given SE3 pose to the scene', 'estimate relative poses between frames using detected markers and a factor graph', 'calibrate extrinsics between cameras and markers using multiple snapshots and factor graph optimization', 'visualize the scene with markers, cameras, and frame axes using SceneViz', 'convert a Sophus SO3 rotation to a numpy quaternion array using so3_to_quat', 'extract xyz position and quaternion from a Sophus SE3 pose using se3_to_xyz_quat', 'build a Sophus SE3 pose from xyz position and quaternion arrays using xyz_quat_to_se3', 'convert a Sophus pose to a GTSAM Pose3 using sophus2gtsam', 'serialize camera intrinsics to a dictionary using intrinsics2dict and back with dict2intrinsics', 'create a SceneViz instance to initialize a 3D matplotlib figure for visualization', 'draw a camera pyramid at a given pose with configurable size and color', 'draw RGB coordinate axes at a given SE3 pose with a specified length', 'draw a square marker outline at a given pose with optional ID label', 'render the 3D scene with auto-scaled axis limits and display the plot']
```

Usage

```
{'create_factor_graph': 'create a FactorGraph instance to build a pose graph optimization problem with named variables', 'init_variable_in_graph': 'initialize a named pose variable in the FactorGraph with an optional Sophus SE3 pose', 'add_prior_factor': 'add a prior factor to anchor a named variable to a fixed pose with optional noise', 'add_observation_between_factor': 'add a between factor observation linking two named variables with a relative transform and noise', 'optimize_pose_graph': 'optimize the FactorGraph using Levenberg-Marquardt and return optimized poses as a Sophus SE3 dictionary'}
```

## File: facebookresearch_fairo/perception/fairotag/python/fairotag/scene.py

Prompts

```
['detect ArUco markers in an image and return their IDs, corners, and estimated poses', 'estimate the 3D pose of a specific registered ArUco marker from an image', 'calibrate camera intrinsics using a set of images of a ChArUco board', 'render detected ArUco marker edges, IDs, and 3D axes onto an image', 'set camera intrinsics from a CameraIntrinsics object, a 3x3 matrix, or keyword arguments', 'create a FactorGraph instance to build a pose graph optimization problem with named variables', 'initialize a named pose variable in the FactorGraph with an optional Sophus SE3 pose', 'add a prior factor to anchor a named variable to a fixed pose with optional noise', 'add a between factor observation linking two named variables with a relative transform and noise', 'optimize the FactorGraph using Levenberg-Marquardt and return optimized poses as a Sophus SE3 dictionary', 'create a Scene object and add a camera and marker to the world frame', 'add a new coordinate frame with a given SE3 pose to the scene', 'estimate relative poses between frames using detected markers and a factor graph', 'calibrate extrinsics between cameras and markers using multiple snapshots and factor graph optimization', 'visualize the scene with markers, cameras, and frame axes using SceneViz', 'convert a Sophus SO3 rotation to a numpy quaternion array using so3_to_quat', 'extract xyz position and quaternion from a Sophus SE3 pose using se3_to_xyz_quat', 'build a Sophus SE3 pose from xyz position and quaternion arrays using xyz_quat_to_se3', 'convert a Sophus pose to a GTSAM Pose3 using sophus2gtsam', 'serialize camera intrinsics to a dictionary using intrinsics2dict and back with dict2intrinsics', 'create a SceneViz instance to initialize a 3D matplotlib figure for visualization', 'draw a camera pyramid at a given pose with configurable size and color', 'draw RGB coordinate axes at a given SE3 pose with a specified length', 'draw a square marker outline at a given pose with optional ID label', 'render the 3D scene with auto-scaled axis limits and display the plot']
```

Usage

```
{'create_scene_with_camera_and_marker': 'create a Scene object and add a camera and marker to the world frame', 'add_frame_to_scene': 'add a new coordinate frame with a given SE3 pose to the scene', 'update_pose_estimations': 'estimate relative poses between frames using detected markers and a factor graph', 'calibrate_extrinsics': 'calibrate extrinsics between cameras and markers using multiple snapshots and factor graph optimization', 'visualize_scene': 'visualize the scene with markers, cameras, and frame axes using SceneViz'}
```

## File: facebookresearch_fairo/perception/fairotag/python/fairotag/utils.py

Prompts

```
['detect ArUco markers in an image and return their IDs, corners, and estimated poses', 'estimate the 3D pose of a specific registered ArUco marker from an image', 'calibrate camera intrinsics using a set of images of a ChArUco board', 'render detected ArUco marker edges, IDs, and 3D axes onto an image', 'set camera intrinsics from a CameraIntrinsics object, a 3x3 matrix, or keyword arguments', 'create a FactorGraph instance to build a pose graph optimization problem with named variables', 'initialize a named pose variable in the FactorGraph with an optional Sophus SE3 pose', 'add a prior factor to anchor a named variable to a fixed pose with optional noise', 'add a between factor observation linking two named variables with a relative transform and noise', 'optimize the FactorGraph using Levenberg-Marquardt and return optimized poses as a Sophus SE3 dictionary', 'create a Scene object and add a camera and marker to the world frame', 'add a new coordinate frame with a given SE3 pose to the scene', 'estimate relative poses between frames using detected markers and a factor graph', 'calibrate extrinsics between cameras and markers using multiple snapshots and factor graph optimization', 'visualize the scene with markers, cameras, and frame axes using SceneViz', 'convert a Sophus SO3 rotation to a numpy quaternion array using so3_to_quat', 'extract xyz position and quaternion from a Sophus SE3 pose using se3_to_xyz_quat', 'build a Sophus SE3 pose from xyz position and quaternion arrays using xyz_quat_to_se3', 'convert a Sophus pose to a GTSAM Pose3 using sophus2gtsam', 'serialize camera intrinsics to a dictionary using intrinsics2dict and back with dict2intrinsics', 'create a SceneViz instance to initialize a 3D matplotlib figure for visualization', 'draw a camera pyramid at a given pose with configurable size and color', 'draw RGB coordinate axes at a given SE3 pose with a specified length', 'draw a square marker outline at a given pose with optional ID label', 'render the 3D scene with auto-scaled axis limits and display the plot']
```

Usage

```
{'convert_so3_to_quaternion': 'convert a Sophus SO3 rotation to a numpy quaternion array using so3_to_quat', 'convert_se3_to_xyz_quat': 'extract xyz position and quaternion from a Sophus SE3 pose using se3_to_xyz_quat', 'convert_xyz_quat_to_se3': 'build a Sophus SE3 pose from xyz position and quaternion arrays using xyz_quat_to_se3', 'convert_sophus_to_gtsam_pose': 'convert a Sophus pose to a GTSAM Pose3 using sophus2gtsam', 'convert_intrinsics_to_dict': 'serialize camera intrinsics to a dictionary using intrinsics2dict and back with dict2intrinsics'}
```

## File: facebookresearch_fairo/perception/fairotag/python/fairotag/viz.py

Prompts

```
['detect ArUco markers in an image and return their IDs, corners, and estimated poses', 'estimate the 3D pose of a specific registered ArUco marker from an image', 'calibrate camera intrinsics using a set of images of a ChArUco board', 'render detected ArUco marker edges, IDs, and 3D axes onto an image', 'set camera intrinsics from a CameraIntrinsics object, a 3x3 matrix, or keyword arguments', 'create a FactorGraph instance to build a pose graph optimization problem with named variables', 'initialize a named pose variable in the FactorGraph with an optional Sophus SE3 pose', 'add a prior factor to anchor a named variable to a fixed pose with optional noise', 'add a between factor observation linking two named variables with a relative transform and noise', 'optimize the FactorGraph using Levenberg-Marquardt and return optimized poses as a Sophus SE3 dictionary', 'create a Scene object and add a camera and marker to the world frame', 'add a new coordinate frame with a given SE3 pose to the scene', 'estimate relative poses between frames using detected markers and a factor graph', 'calibrate extrinsics between cameras and markers using multiple snapshots and factor graph optimization', 'visualize the scene with markers, cameras, and frame axes using SceneViz', 'convert a Sophus SO3 rotation to a numpy quaternion array using so3_to_quat', 'extract xyz position and quaternion from a Sophus SE3 pose using se3_to_xyz_quat', 'build a Sophus SE3 pose from xyz position and quaternion arrays using xyz_quat_to_se3', 'convert a Sophus pose to a GTSAM Pose3 using sophus2gtsam', 'serialize camera intrinsics to a dictionary using intrinsics2dict and back with dict2intrinsics', 'create a SceneViz instance to initialize a 3D matplotlib figure for visualization', 'draw a camera pyramid at a given pose with configurable size and color', 'draw RGB coordinate axes at a given SE3 pose with a specified length', 'draw a square marker outline at a given pose with optional ID label', 'render the 3D scene with auto-scaled axis limits and display the plot']
```

Usage

```
{'create_scene_viz': 'create a SceneViz instance to initialize a 3D matplotlib figure for visualization', 'draw_camera_pyramid': 'draw a camera pyramid at a given pose with configurable size and color', 'draw_axes_at_pose': 'draw RGB coordinate axes at a given SE3 pose with a specified length', 'draw_marker_outline': 'draw a square marker outline at a given pose with optional ID label', 'show_3d_scene': 'render the 3D scene with auto-scaled axis limits and display the plot'}
```

