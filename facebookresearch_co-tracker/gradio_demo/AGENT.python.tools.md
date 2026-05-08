# Agent Python Tools

- repo: facebookresearch/co-tracker
- repo_uri: https://github.com/facebookresearch/co-tracker

## File: facebookresearch_co-tracker/gradio_demo/app.py

Prompts

```
['generate a list of random RGB color tuples for visualizing N distinct tracked points', 'generate a uniform NxN grid of 2D point coordinates as a PyTorch tensor over a given extent', 'overlay colored tracked point dots onto video frames using bilinear interpolation and visibility masks', 'read a video file, resize it to preview and model input resolutions, and initialize tracking state', 'run CoTracker3 point tracking on a video using selected query points or an auto-generated grid']
```

Usage

```
{'get_colors': 'generate a list of random RGB color tuples for visualizing N distinct tracked points', 'get_points_on_a_grid': 'generate a uniform NxN grid of 2D point coordinates as a PyTorch tensor over a given extent', 'paint_point_track': 'overlay colored tracked point dots onto video frames using bilinear interpolation and visibility masks', 'preprocess_video_input': 'read a video file, resize it to preview and model input resolutions, and initialize tracking state', 'track': 'run CoTracker3 point tracking on a video using selected query points or an auto-generated grid'}
```

