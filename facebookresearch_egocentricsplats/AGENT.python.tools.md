# Agent Python Tools

- repo: facebookresearch/egocentricsplats
- repo_uri: https://github.com/facebookresearch/egocentric_splats

## File: facebookresearch_egocentricsplats/launch_viewer.py

Prompts

```
['run the 3D Gaussian Splatting viewer server with viser on a configured host and port', 'scan a model path directory and return all available training iteration checkpoint paths', 'read a cameras JSON file and return a list of Camera objects from train or root entries', 'initialize a RenderViewer instance with a Hydra config and Viser server to load Gaussian Splatting models', 'render a Gaussian Splatting scene from a camera state and return an RGB, depth, or normal image', 'run the main render pipeline to test Gaussian Splatting models with Lightning and generate output', 'create a video from a folder of PNG images using FFmpeg with configurable framerate and quality', 'render the original camera trajectory by loading a transforms.json scene and running the test loop', 'render a novel view scene by initializing render info and testing the Gaussian Splatting model', 'generate MP4 videos from rendered image, depth, normal, and ground truth output folders']
```

Usage

```
{'run_viewer_server': 'run the 3D Gaussian Splatting viewer server with viser on a configured host and port', 'scan_avail_iters': 'scan a model path directory and return all available training iteration checkpoint paths', 'read_cameras_json': 'read a cameras JSON file and return a list of Camera objects from train or root entries', 'RenderViewer_init': 'initialize a RenderViewer instance with a Hydra config and Viser server to load Gaussian Splatting models', 'RenderViewer_viewer_render_fn': 'render a Gaussian Splatting scene from a camera state and return an RGB, depth, or normal image'}
```

## File: facebookresearch_egocentricsplats/render_lightning.py

Prompts

```
['run the 3D Gaussian Splatting viewer server with viser on a configured host and port', 'scan a model path directory and return all available training iteration checkpoint paths', 'read a cameras JSON file and return a list of Camera objects from train or root entries', 'initialize a RenderViewer instance with a Hydra config and Viser server to load Gaussian Splatting models', 'render a Gaussian Splatting scene from a camera state and return an RGB, depth, or normal image', 'run the main render pipeline to test Gaussian Splatting models with Lightning and generate output', 'create a video from a folder of PNG images using FFmpeg with configurable framerate and quality', 'render the original camera trajectory by loading a transforms.json scene and running the test loop', 'render a novel view scene by initializing render info and testing the Gaussian Splatting model', 'generate MP4 videos from rendered image, depth, normal, and ground truth output folders']
```

Usage

```
{'run_render_pipeline': 'run the main render pipeline to test Gaussian Splatting models with Lightning and generate output', 'create_video_from_images': 'create a video from a folder of PNG images using FFmpeg with configurable framerate and quality', 'render_original_trajectory': 'render the original camera trajectory by loading a transforms.json scene and running the test loop', 'render_novel_view': 'render a novel view scene by initializing render info and testing the Gaussian Splatting model', 'generate_rendering_videos': 'generate MP4 videos from rendered image, depth, normal, and ground truth output folders'}
```

