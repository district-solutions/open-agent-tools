# Agent Python Tools

- repo: facebookresearch/consistentdepth
- repo_uri: https://github.com/facebookresearch/consistent_depth

## File: facebookresearch_consistentdepth/loaders/video_dataset.py

Prompts

```
['load a color image from a file path and return a normalized torch tensor in range 0 to 1', 'load an optical flow image from a raw file path and return a 2-channel flow tensor in pixels', 'load a binary mask image from a file path and return a 0 or 1 torch tensor', 'create a PyTorch dataset that loads 3D video frame pairs with flow, mask, and camera metadata', 'create a PyTorch dataset that loads individual video frames from a formatted color file path']
```

Usage

```
{'load_color_image': 'load a color image from a file path and return a normalized torch tensor in range 0 to 1', 'load_flow_tensor': 'load an optical flow image from a raw file path and return a 2-channel flow tensor in pixels', 'load_mask_tensor': 'load a binary mask image from a file path and return a 0 or 1 torch tensor', 'create_VideoDataset': 'create a PyTorch dataset that loads 3D video frame pairs with flow, mask, and camera metadata', 'create_VideoFrameDataset': 'create a PyTorch dataset that loads individual video frames from a formatted color file path'}
```

