# Agent Python Tools

- repo: facebookresearch/interhand2.6m
- repo_uri: https://github.com/facebookresearch/interhand2.6m

## File: facebookresearch_interhand2.6m/common/utils/dir.py

Prompts

```
['create a directory at the given path if it does not already exist', 'create nested directories recursively for a given folder path that does not exist', 'add a directory to the front of sys.path if it is not already present', 'prepend a custom path to sys.path so Python can import modules from it', 'review the make_folder and add_pypath utility functions for directory and path management', 'load an image from a file path and convert it to RGB float32 format', 'load a skeleton definition file and build a joint hierarchy with parent and child IDs', 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and its joint coordinates', 'compute a bounding box from valid 2D joint coordinates with a 20 percent padding margin', 'crop and warp an image patch from a bounding box with optional flip, scale, and rotation transforms', 'convert camera coordinates to pixel coordinates using focal length and principal point parameters', 'convert pixel coordinates back to camera coordinates using focal length and principal point parameters', 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'create a multi-dimensional meshgrid from multiple tensor arguments for broadcasting operations', 'flip a PyTorch tensor along specified dimensions while preserving device and gradient state', 'get RGB color tuples for hand skeleton joint names from a skeleton definition', 'visualize 2D hand keypoints on an image with colored lines and circles and save', 'visualize 3D hand keypoints in a 3D plot with colored lines and scatter points', 'review the vis_keypoints function to understand how it draws skeleton joints on images', 'refactor the get_keypoint_rgb function to use a data-driven color mapping instead of if-elif chains']
```

Usage

```
{'make_folder_create_directory': 'create a directory at the given path if it does not already exist', 'make_folder_create_nested_directory': 'create nested directories recursively for a given folder path that does not exist', 'add_pypath_prepend_to_sys_path': 'add a directory to the front of sys.path if it is not already present', 'add_pypath_add_module_search_path': 'prepend a custom path to sys.path so Python can import modules from it', 'review_make_folder_and_add_pypath': 'review the make_folder and add_pypath utility functions for directory and path management'}
```

## File: facebookresearch_interhand2.6m/common/utils/preprocessing.py

Prompts

```
['create a directory at the given path if it does not already exist', 'create nested directories recursively for a given folder path that does not exist', 'add a directory to the front of sys.path if it is not already present', 'prepend a custom path to sys.path so Python can import modules from it', 'review the make_folder and add_pypath utility functions for directory and path management', 'load an image from a file path and convert it to RGB float32 format', 'load a skeleton definition file and build a joint hierarchy with parent and child IDs', 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and its joint coordinates', 'compute a bounding box from valid 2D joint coordinates with a 20 percent padding margin', 'crop and warp an image patch from a bounding box with optional flip, scale, and rotation transforms', 'convert camera coordinates to pixel coordinates using focal length and principal point parameters', 'convert pixel coordinates back to camera coordinates using focal length and principal point parameters', 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'create a multi-dimensional meshgrid from multiple tensor arguments for broadcasting operations', 'flip a PyTorch tensor along specified dimensions while preserving device and gradient state', 'get RGB color tuples for hand skeleton joint names from a skeleton definition', 'visualize 2D hand keypoints on an image with colored lines and circles and save', 'visualize 3D hand keypoints in a 3D plot with colored lines and scatter points', 'review the vis_keypoints function to understand how it draws skeleton joints on images', 'refactor the get_keypoint_rgb function to use a data-driven color mapping instead of if-elif chains']
```

Usage

```
{'load_img': 'load an image from a file path and convert it to RGB float32 format', 'load_skeleton': 'load a skeleton definition file and build a joint hierarchy with parent and child IDs', 'augmentation': 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and its joint coordinates', 'get_bbox': 'compute a bounding box from valid 2D joint coordinates with a 20 percent padding margin', 'generate_patch_image': 'crop and warp an image patch from a bounding box with optional flip, scale, and rotation transforms'}
```

## File: facebookresearch_interhand2.6m/common/utils/transforms.py

Prompts

```
['create a directory at the given path if it does not already exist', 'create nested directories recursively for a given folder path that does not exist', 'add a directory to the front of sys.path if it is not already present', 'prepend a custom path to sys.path so Python can import modules from it', 'review the make_folder and add_pypath utility functions for directory and path management', 'load an image from a file path and convert it to RGB float32 format', 'load a skeleton definition file and build a joint hierarchy with parent and child IDs', 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and its joint coordinates', 'compute a bounding box from valid 2D joint coordinates with a 20 percent padding margin', 'crop and warp an image patch from a bounding box with optional flip, scale, and rotation transforms', 'convert camera coordinates to pixel coordinates using focal length and principal point parameters', 'convert pixel coordinates back to camera coordinates using focal length and principal point parameters', 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'create a multi-dimensional meshgrid from multiple tensor arguments for broadcasting operations', 'flip a PyTorch tensor along specified dimensions while preserving device and gradient state', 'get RGB color tuples for hand skeleton joint names from a skeleton definition', 'visualize 2D hand keypoints on an image with colored lines and circles and save', 'visualize 3D hand keypoints in a 3D plot with colored lines and scatter points', 'review the vis_keypoints function to understand how it draws skeleton joints on images', 'refactor the get_keypoint_rgb function to use a data-driven color mapping instead of if-elif chains']
```

Usage

```
{'convert_camera_to_pixel_coords': 'convert camera coordinates to pixel coordinates using focal length and principal point parameters', 'convert_pixel_to_camera_coords': 'convert pixel coordinates back to camera coordinates using focal length and principal point parameters', 'transform_world_to_camera_coords': 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'create_multi_dimensional_meshgrid': 'create a multi-dimensional meshgrid from multiple tensor arguments for broadcasting operations', 'flip_tensor_along_dimensions': 'flip a PyTorch tensor along specified dimensions while preserving device and gradient state'}
```

## File: facebookresearch_interhand2.6m/common/utils/vis.py

Prompts

```
['create a directory at the given path if it does not already exist', 'create nested directories recursively for a given folder path that does not exist', 'add a directory to the front of sys.path if it is not already present', 'prepend a custom path to sys.path so Python can import modules from it', 'review the make_folder and add_pypath utility functions for directory and path management', 'load an image from a file path and convert it to RGB float32 format', 'load a skeleton definition file and build a joint hierarchy with parent and child IDs', 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and its joint coordinates', 'compute a bounding box from valid 2D joint coordinates with a 20 percent padding margin', 'crop and warp an image patch from a bounding box with optional flip, scale, and rotation transforms', 'convert camera coordinates to pixel coordinates using focal length and principal point parameters', 'convert pixel coordinates back to camera coordinates using focal length and principal point parameters', 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'create a multi-dimensional meshgrid from multiple tensor arguments for broadcasting operations', 'flip a PyTorch tensor along specified dimensions while preserving device and gradient state', 'get RGB color tuples for hand skeleton joint names from a skeleton definition', 'visualize 2D hand keypoints on an image with colored lines and circles and save', 'visualize 3D hand keypoints in a 3D plot with colored lines and scatter points', 'review the vis_keypoints function to understand how it draws skeleton joints on images', 'refactor the get_keypoint_rgb function to use a data-driven color mapping instead of if-elif chains']
```

Usage

```
{'get_keypoint_rgb': 'get RGB color tuples for hand skeleton joint names from a skeleton definition', 'vis_keypoints_2d': 'visualize 2D hand keypoints on an image with colored lines and circles and save', 'vis_3d_keypoints': 'visualize 3D hand keypoints in a 3D plot with colored lines and scatter points', 'review_vis_keypoints': 'review the vis_keypoints function to understand how it draws skeleton joints on images', 'refactor_get_keypoint_rgb': 'refactor the get_keypoint_rgb function to use a data-driven color mapping instead of if-elif chains'}
```

