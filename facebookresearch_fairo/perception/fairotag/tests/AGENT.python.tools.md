# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/perception/fairotag/tests/test_camera_module.py

Prompts

```
['test that CameraModule calibrates camera intrinsics from a list of Charuco board images', 'test that CameraModule detects ArUco markers and returns their IDs from an input image', 'test that registered markers have correct length and SE3 pose after detection', 'test that unregistered markers have None length and None pose after detection', 'test loading camera intrinsics from a JSON file using dict2intrinsics utility', 'create a fairotag Scene object to manage cameras, markers, and frames', 'add cameras and markers to a fairotag Scene with optional pose and frame', 'add a snapshot of detected markers from multiple cameras to the scene', 'calibrate camera extrinsics using collected marker observation snapshots', 'update marker pose estimations from newly detected marker observations']
```

Usage

```
{'test_camera_calibration': 'test that CameraModule calibrates camera intrinsics from a list of Charuco board images', 'test_marker_detection': 'test that CameraModule detects ArUco markers and returns their IDs from an input image', 'test_registered_marker_pose': 'test that registered markers have correct length and SE3 pose after detection', 'test_unregistered_marker_none': 'test that unregistered markers have None length and None pose after detection', 'test_intrinsics_from_file': 'test loading camera intrinsics from a JSON file using dict2intrinsics utility'}
```

## File: facebookresearch_fairo/perception/fairotag/tests/test_scene_module.py

Prompts

```
['test that CameraModule calibrates camera intrinsics from a list of Charuco board images', 'test that CameraModule detects ArUco markers and returns their IDs from an input image', 'test that registered markers have correct length and SE3 pose after detection', 'test that unregistered markers have None length and None pose after detection', 'test loading camera intrinsics from a JSON file using dict2intrinsics utility', 'create a fairotag Scene object to manage cameras, markers, and frames', 'add cameras and markers to a fairotag Scene with optional pose and frame', 'add a snapshot of detected markers from multiple cameras to the scene', 'calibrate camera extrinsics using collected marker observation snapshots', 'update marker pose estimations from newly detected marker observations']
```

Usage

```
{'create_scene': 'create a fairotag Scene object to manage cameras, markers, and frames', 'add_camera_and_marker': 'add cameras and markers to a fairotag Scene with optional pose and frame', 'add_snapshot': 'add a snapshot of detected markers from multiple cameras to the scene', 'calibrate_extrinsics': 'calibrate camera extrinsics using collected marker observation snapshots', 'update_pose_estimations': 'update marker pose estimations from newly detected marker observations'}
```

