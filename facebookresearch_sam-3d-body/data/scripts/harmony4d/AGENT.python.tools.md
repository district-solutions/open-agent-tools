# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/data/scripts/harmony4d/_init_paths.py

Prompts

```
['add a directory path to sys.path if it is not already present', 'review the add_path function that inserts a path into sys.path at index 0', 'summarize the _init_paths module that adds lib and root directories to sys.path', 'run the CLI to undistort all Harmony4D exo camera images from a source directory to a destination', 'run extract_images to undistort all exo camera frames for a sequence using 10 parallel workers', 'create an undistorted image from a fisheye exo camera using intrinsics and distortion coefficients', 'create undistortion remap matrices and new camera matrix for fisheye camera calibration parameters', 'review the save_frames function that loads camera intrinsics and undistorts all JPG frames for a camera']
```

Usage

```
{'add_path': 'add a directory path to sys.path if it is not already present', 'review_add_path': 'review the add_path function that inserts a path into sys.path at index 0', 'summarize_init_paths': 'summarize the _init_paths module that adds lib and root directories to sys.path'}
```

## File: facebookresearch_sam-3d-body/data/scripts/harmony4d/undistort_images.py

Prompts

```
['add a directory path to sys.path if it is not already present', 'review the add_path function that inserts a path into sys.path at index 0', 'summarize the _init_paths module that adds lib and root directories to sys.path', 'run the CLI to undistort all Harmony4D exo camera images from a source directory to a destination', 'run extract_images to undistort all exo camera frames for a sequence using 10 parallel workers', 'create an undistorted image from a fisheye exo camera using intrinsics and distortion coefficients', 'create undistortion remap matrices and new camera matrix for fisheye camera calibration parameters', 'review the save_frames function that loads camera intrinsics and undistorts all JPG frames for a camera']
```

Usage

```
{'run_undistort_harmony4d_images': 'run the CLI to undistort all Harmony4D exo camera images from a source directory to a destination', 'run_extract_images_parallel': 'run extract_images to undistort all exo camera frames for a sequence using 10 parallel workers', 'create_undistort_single_image': 'create an undistorted image from a fisheye exo camera using intrinsics and distortion coefficients', 'create_undistort_maps': 'create undistortion remap matrices and new camera matrix for fisheye camera calibration parameters', 'review_save_frames': 'review the save_frames function that loads camera intrinsics and undistorts all JPG frames for a camera'}
```

