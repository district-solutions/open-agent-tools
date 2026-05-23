# Agent Python Tools

- repo: facebookresearch/robustcvd
- repo_uri: https://github.com/facebookresearch/robust_cvd

## File: facebookresearch_robustcvd/loaders/video_dataset.py

Prompts

```
['create a VideoDataset to load 3D video frames with flow pairs and camera metadata for consistency loss optimization', 'create a VideoFrameDataset to load individual video color frames from a directory using a format string', 'load a color image from raw or png path and return a normalized torch tensor in range 0 to 1', 'load an optical flow image from a raw path and return a 2-channel flow tensor in pixels', 'update the VideoDataset extrinsics, intrinsics, depth scales, and warp maps from a DepthVideo after pose optimization']
```

Usage

```
{'create_VideoDataset': 'create a VideoDataset to load 3D video frames with flow pairs and camera metadata for consistency loss optimization', 'create_VideoFrameDataset': 'create a VideoFrameDataset to load individual video color frames from a directory using a format string', 'load_color': 'load a color image from raw or png path and return a normalized torch tensor in range 0 to 1', 'load_flow': 'load an optical flow image from a raw path and return a 2-channel flow tensor in pixels', 'update_poses': 'update the VideoDataset extrinsics, intrinsics, depth scales, and warp maps from a DepthVideo after pose optimization'}
```

