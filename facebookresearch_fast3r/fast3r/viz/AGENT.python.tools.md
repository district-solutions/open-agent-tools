# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/viz/demo.py

Prompts

```
['run the Fast3R 3D reconstruction demo with a checkpoint directory and output directory via argparse', 'create a Gradio demo interface for 3D reconstruction from images or video using a model checkpoint', 'process uploaded images or video frames through the Fast3R model and launch a 3D visualization server', 'launch a viser visualization server in a separate process and return its share URL via a pipe', 'manage multiple viser visualization server processes by session using launch, terminate, and session cleanup commands', 'extract frames from a video file at 1 FPS and save them as JPEG images', 'extract frames from a WebM video file using FFmpeg and save as JPEG images', 'extract frames from a video using OpenCV with automatic fallback for WebM files', 'review the extract_frames_from_video function to understand its FFmpeg and OpenCV extraction logic', 'refactor extract_frames_from_video to support configurable FPS and output image quality settings', 'start a viser 3D visualization server to interactively view multi-view point clouds and camera frustums', 'detect sky pixels in an RGB image using HSV color space and morphological operations', 'determine if a scene is outdoor by analyzing sky pixel ratios across multiple frames', 'generate binary PLY file bytes from 3D point cloud coordinates and their RGB colors', 'collect all visible 3D points and colors from frame data up to a given timestep']
```

Usage

```
{'run_demo_cli': 'run the Fast3R 3D reconstruction demo with a checkpoint directory and output directory via argparse', 'create_demo_gradio': 'create a Gradio demo interface for 3D reconstruction from images or video using a model checkpoint', 'process_images_inference': 'process uploaded images or video frames through the Fast3R model and launch a 3D visualization server', 'launch_viser_server': 'launch a viser visualization server in a separate process and return its share URL via a pipe', 'manage_viser_servers': 'manage multiple viser visualization server processes by session using launch, terminate, and session cleanup commands'}
```

## File: facebookresearch_fast3r/fast3r/viz/video_utils.py

Prompts

```
['run the Fast3R 3D reconstruction demo with a checkpoint directory and output directory via argparse', 'create a Gradio demo interface for 3D reconstruction from images or video using a model checkpoint', 'process uploaded images or video frames through the Fast3R model and launch a 3D visualization server', 'launch a viser visualization server in a separate process and return its share URL via a pipe', 'manage multiple viser visualization server processes by session using launch, terminate, and session cleanup commands', 'extract frames from a video file at 1 FPS and save them as JPEG images', 'extract frames from a WebM video file using FFmpeg and save as JPEG images', 'extract frames from a video using OpenCV with automatic fallback for WebM files', 'review the extract_frames_from_video function to understand its FFmpeg and OpenCV extraction logic', 'refactor extract_frames_from_video to support configurable FPS and output image quality settings', 'start a viser 3D visualization server to interactively view multi-view point clouds and camera frustums', 'detect sky pixels in an RGB image using HSV color space and morphological operations', 'determine if a scene is outdoor by analyzing sky pixel ratios across multiple frames', 'generate binary PLY file bytes from 3D point cloud coordinates and their RGB colors', 'collect all visible 3D points and colors from frame data up to a given timestep']
```

Usage

```
{'extract_frames_video': 'extract frames from a video file at 1 FPS and save them as JPEG images', 'extract_frames_webm': 'extract frames from a WebM video file using FFmpeg and save as JPEG images', 'extract_frames_fallback': 'extract frames from a video using OpenCV with automatic fallback for WebM files', 'review_extract_frames': 'review the extract_frames_from_video function to understand its FFmpeg and OpenCV extraction logic', 'refactor_extract_frames': 'refactor extract_frames_from_video to support configurable FPS and output image quality settings'}
```

## File: facebookresearch_fast3r/fast3r/viz/viser_visualizer.py

Prompts

```
['run the Fast3R 3D reconstruction demo with a checkpoint directory and output directory via argparse', 'create a Gradio demo interface for 3D reconstruction from images or video using a model checkpoint', 'process uploaded images or video frames through the Fast3R model and launch a 3D visualization server', 'launch a viser visualization server in a separate process and return its share URL via a pipe', 'manage multiple viser visualization server processes by session using launch, terminate, and session cleanup commands', 'extract frames from a video file at 1 FPS and save them as JPEG images', 'extract frames from a WebM video file using FFmpeg and save as JPEG images', 'extract frames from a video using OpenCV with automatic fallback for WebM files', 'review the extract_frames_from_video function to understand its FFmpeg and OpenCV extraction logic', 'refactor extract_frames_from_video to support configurable FPS and output image quality settings', 'start a viser 3D visualization server to interactively view multi-view point clouds and camera frustums', 'detect sky pixels in an RGB image using HSV color space and morphological operations', 'determine if a scene is outdoor by analyzing sky pixel ratios across multiple frames', 'generate binary PLY file bytes from 3D point cloud coordinates and their RGB colors', 'collect all visible 3D points and colors from frame data up to a given timestep']
```

Usage

```
{'start_visualization': 'start a viser 3D visualization server to interactively view multi-view point clouds and camera frustums', 'detect_sky_mask': 'detect sky pixels in an RGB image using HSV color space and morphological operations', 'is_outdoor_scene': 'determine if a scene is outdoor by analyzing sky pixel ratios across multiple frames', 'generate_ply_bytes': 'generate binary PLY file bytes from 3D point cloud coordinates and their RGB colors', 'collect_visible_points': 'collect all visible 3D points and colors from frame data up to a given timestep'}
```

