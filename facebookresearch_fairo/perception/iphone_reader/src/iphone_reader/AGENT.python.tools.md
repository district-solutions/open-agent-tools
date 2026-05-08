# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/perception/iphone_reader/src/iphone_reader/api.py

Prompts

```
['create a Record3dReader instance to connect to an iPhone device for depth and color frame capture', 'start the Record3dReader session to begin capturing frames from a connected iPhone device', 'wait for the next R3dFrame with optional timeout and retrieve color and depth images', 'recenter the camera pose origin to reset tracking coordinates during an active recording session', 'get the CameraMetadata including intrinsic matrix coefficients and device type from the reader']
```

Usage

```
{'create_record3d_reader': 'create a Record3dReader instance to connect to an iPhone device for depth and color frame capture', 'start_recording_stream': 'start the Record3dReader session to begin capturing frames from a connected iPhone device', 'wait_for_frame': 'wait for the next R3dFrame with optional timeout and retrieve color and depth images', 'recenter_pose': 'recenter the camera pose origin to reset tracking coordinates during an active recording session', 'get_camera_metadata': 'get the CameraMetadata including intrinsic matrix coefficients and device type from the reader'}
```

