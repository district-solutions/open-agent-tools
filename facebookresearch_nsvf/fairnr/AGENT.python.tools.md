# Agent Python Tools

- repo: facebookresearch/nsvf
- repo_uri: https://github.com/facebookresearch/nsvf

## File: facebookresearch_nsvf/fairnr/options.py

Prompts

```
['get a rendering argument parser with default task single_object_rendering for 3D object rendering', 'add rendering CLI arguments like beam size, resolution, path style, and output types to an argparse parser', 'parse command line arguments and architecture config by delegating to fairseq options module', 'render 3D objects using custom camera poses loaded from a text file for testing trajectories', 'render 3D objects with output types including color, depth, normal, voxel, and point predictions', 'create a NeuralRenderer instance with custom resolution, frames, speed, and output directory settings', 'generate camera rays and inverse rotation-translation matrices for a given timestep and intrinsics', 'generate rendered frames from a neural field model by iterating over camera poses and saving images', 'save rendered image files as timestamped MP4 videos with optional combined output for all types', 'merge multiple timestamped MP4 video files into a single combined video and remove originals']
```

Usage

```
{'get_rendering_parser': 'get a rendering argument parser with default task single_object_rendering for 3D object rendering', 'add_rendering_args': 'add rendering CLI arguments like beam size, resolution, path style, and output types to an argparse parser', 'parse_args_and_arch': 'parse command line arguments and architecture config by delegating to fairseq options module', 'render_camera_poses': 'render 3D objects using custom camera poses loaded from a text file for testing trajectories', 'render_output_types': 'render 3D objects with output types including color, depth, normal, voxel, and point predictions'}
```

## File: facebookresearch_nsvf/fairnr/renderer.py

Prompts

```
['get a rendering argument parser with default task single_object_rendering for 3D object rendering', 'add rendering CLI arguments like beam size, resolution, path style, and output types to an argparse parser', 'parse command line arguments and architecture config by delegating to fairseq options module', 'render 3D objects using custom camera poses loaded from a text file for testing trajectories', 'render 3D objects with output types including color, depth, normal, voxel, and point predictions', 'create a NeuralRenderer instance with custom resolution, frames, speed, and output directory settings', 'generate camera rays and inverse rotation-translation matrices for a given timestep and intrinsics', 'generate rendered frames from a neural field model by iterating over camera poses and saving images', 'save rendered image files as timestamped MP4 videos with optional combined output for all types', 'merge multiple timestamped MP4 video files into a single combined video and remove originals']
```

Usage

```
{'create_NeuralRenderer': 'create a NeuralRenderer instance with custom resolution, frames, speed, and output directory settings', 'generate_rays': 'generate camera rays and inverse rotation-translation matrices for a given timestep and intrinsics', 'generate': 'generate rendered frames from a neural field model by iterating over camera poses and saving images', 'save_images': 'save rendered image files as timestamped MP4 videos with optional combined output for all types', 'merge_videos': 'merge multiple timestamped MP4 video files into a single combined video and remove originals'}
```

