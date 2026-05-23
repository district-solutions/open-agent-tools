# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/data/scripts/egohumans/_init_paths.py

Prompts

```
['add a directory path to sys.path so Python can import modules from it', 'review the add_path function that conditionally inserts a path into sys.path', 'summarize the _init_paths module that adds lib and root directories to sys.path', 'test the add_path function to verify it inserts paths without duplicates', 'refactor the add_path function to support path validation before insertion', 'run the CLI to undistort EgoHuman exo camera images from source to destination directory', 'run extract_images to undistort all exo camera frames for a sequence using 10 worker processes', 'run save_frames to undistort and save all JPG frames for a single exo camera', 'run undistort_exocam to undistort a single fisheye image given intrinsics and distortion coefficients', 'run undistort_exocam_info to compute undistortion maps and new camera matrix for fisheye images']
```

Usage

```
{'add_path_to_sys': 'add a directory path to sys.path so Python can import modules from it', 'review_add_path_function': 'review the add_path function that conditionally inserts a path into sys.path', 'summarize_init_paths_module': 'summarize the _init_paths module that adds lib and root directories to sys.path', 'test_add_path_function': 'test the add_path function to verify it inserts paths without duplicates', 'refactor_add_path_function': 'refactor the add_path function to support path validation before insertion'}
```

## File: facebookresearch_sam-3d-body/data/scripts/egohumans/undistort_images.py

Prompts

```
['add a directory path to sys.path so Python can import modules from it', 'review the add_path function that conditionally inserts a path into sys.path', 'summarize the _init_paths module that adds lib and root directories to sys.path', 'test the add_path function to verify it inserts paths without duplicates', 'refactor the add_path function to support path validation before insertion', 'run the CLI to undistort EgoHuman exo camera images from source to destination directory', 'run extract_images to undistort all exo camera frames for a sequence using 10 worker processes', 'run save_frames to undistort and save all JPG frames for a single exo camera', 'run undistort_exocam to undistort a single fisheye image given intrinsics and distortion coefficients', 'run undistort_exocam_info to compute undistortion maps and new camera matrix for fisheye images']
```

Usage

```
{'run_undistort_egohumans_images': 'run the CLI to undistort EgoHuman exo camera images from source to destination directory', 'run_extract_images_parallel': 'run extract_images to undistort all exo camera frames for a sequence using 10 worker processes', 'run_save_frames_single_camera': 'run save_frames to undistort and save all JPG frames for a single exo camera', 'run_undistort_exocam_single_image': 'run undistort_exocam to undistort a single fisheye image given intrinsics and distortion coefficients', 'run_undistort_exocam_info_maps': 'run undistort_exocam_info to compute undistortion maps and new camera matrix for fisheye images'}
```

