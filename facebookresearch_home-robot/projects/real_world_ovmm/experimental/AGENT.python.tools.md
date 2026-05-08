# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/real_world_ovmm/experimental/demo_sam.py

Prompts

```
['run the SAM segmentation demo on a Stretch robot camera image and display masks', 'create a SamAutomaticMaskGenerator from a SAM checkpoint to generate segmentation masks on images', 'visualize segmentation annotation masks with random color overlays on a matplotlib axis', 'load a Segment Anything Model from a checkpoint file using sam_model_registry for inference', 'capture an image from a Stretch robot head camera using the StretchClient API', 'run the stretch robot trajectory execution CLI with --wait or --dry-run flags', 'parse a tab-delimited text file into goal names and coordinate trajectory lists', 'wait for the robot to approximately reach a target x, y, theta pose within a threshold', 'navigate the stretch robot through a list of waypoints using blocking or non-blocking mode', 'compute the robot head tilt angle based on distance to a target and head height', 'run the mapping CLI script to explore with a Stretch robot and build a voxel map', 'run SAM segmentation on an image to get everything prompt annotations and masks', 'visualize a 3D point cloud map with robot geometry using Open3D', 'check for collisions between a robot mesh and environment point cloud using a KDTree']
```

Usage

```
{'run_sam_segmentation_demo': 'run the SAM segmentation demo on a Stretch robot camera image and display masks', 'create_mask_generator': 'create a SamAutomaticMaskGenerator from a SAM checkpoint to generate segmentation masks on images', 'show_anns_visualize_masks': 'visualize segmentation annotation masks with random color overlays on a matplotlib axis', 'load_sam_model': 'load a Segment Anything Model from a checkpoint file using sam_model_registry for inference', 'capture_robot_image': 'capture an image from a Stretch robot head camera using the StretchClient API'}
```

## File: facebookresearch_home-robot/projects/real_world_ovmm/experimental/execute_trajectory.py

Prompts

```
['run the SAM segmentation demo on a Stretch robot camera image and display masks', 'create a SamAutomaticMaskGenerator from a SAM checkpoint to generate segmentation masks on images', 'visualize segmentation annotation masks with random color overlays on a matplotlib axis', 'load a Segment Anything Model from a checkpoint file using sam_model_registry for inference', 'capture an image from a Stretch robot head camera using the StretchClient API', 'run the stretch robot trajectory execution CLI with --wait or --dry-run flags', 'parse a tab-delimited text file into goal names and coordinate trajectory lists', 'wait for the robot to approximately reach a target x, y, theta pose within a threshold', 'navigate the stretch robot through a list of waypoints using blocking or non-blocking mode', 'compute the robot head tilt angle based on distance to a target and head height', 'run the mapping CLI script to explore with a Stretch robot and build a voxel map', 'run SAM segmentation on an image to get everything prompt annotations and masks', 'visualize a 3D point cloud map with robot geometry using Open3D', 'check for collisions between a robot mesh and environment point cloud using a KDTree']
```

Usage

```
{'run_trajectory_execution': 'run the stretch robot trajectory execution CLI with --wait or --dry-run flags', 'parse_txt_to_trajectory': 'parse a tab-delimited text file into goal names and coordinate trajectory lists', 'loose_wait_robot_pose': 'wait for the robot to approximately reach a target x, y, theta pose within a threshold', 'navigate_to_waypoints': 'navigate the stretch robot through a list of waypoints using blocking or non-blocking mode', 'compute_head_tilt': 'compute the robot head tilt angle based on distance to a target and head height'}
```

## File: facebookresearch_home-robot/projects/real_world_ovmm/experimental/mapping.py

Prompts

```
['run the SAM segmentation demo on a Stretch robot camera image and display masks', 'create a SamAutomaticMaskGenerator from a SAM checkpoint to generate segmentation masks on images', 'visualize segmentation annotation masks with random color overlays on a matplotlib axis', 'load a Segment Anything Model from a checkpoint file using sam_model_registry for inference', 'capture an image from a Stretch robot head camera using the StretchClient API', 'run the stretch robot trajectory execution CLI with --wait or --dry-run flags', 'parse a tab-delimited text file into goal names and coordinate trajectory lists', 'wait for the robot to approximately reach a target x, y, theta pose within a threshold', 'navigate the stretch robot through a list of waypoints using blocking or non-blocking mode', 'compute the robot head tilt angle based on distance to a target and head height', 'run the mapping CLI script to explore with a Stretch robot and build a voxel map', 'run SAM segmentation on an image to get everything prompt annotations and masks', 'visualize a 3D point cloud map with robot geometry using Open3D', 'check for collisions between a robot mesh and environment point cloud using a KDTree']
```

Usage

```
{'run_mapping_cli': 'run the mapping CLI script to explore with a Stretch robot and build a voxel map', 'load_sam_model': 'load a FastSAM segmentation model from a weights file path for object detection', 'try_sam': 'run SAM segmentation on an image to get everything prompt annotations and masks', 'show_map': 'visualize a 3D point cloud map with robot geometry using Open3D', 'check_collision': 'check for collisions between a robot mesh and environment point cloud using a KDTree'}
```

