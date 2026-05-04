# Agent Python Tools

- repo: facebookresearch/assemblyhands-toolkit
- repo_uri: https://github.com/facebookresearch/assemblyhands-toolkit

## File: facebookresearch_assemblyhands-toolkit/src/common/utils/dir.py

Prompts

```
['create a folder at a given path if it does not already exist', 'add a directory to sys.path so Python can import modules from it', 'ensure an output directory exists before writing files to it', 'enable importing from a custom directory by adding it to sys.path', 'create a project directory and add it to sys.path for imports', 'load an image from a file path and return it as a float32 numpy array in RGB order', 'load an image, crop it by a bounding box, and update joint coordinates and camera parameters', 'load a skeleton definition file and return a list of joints with name, parent, and child IDs', 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and joints', 'load camera calibration intrinsics and extrinsics from a JSON or text file for ego or exo view types', 'create a Camera object with intrinsic matrix K and extrinsic matrix Rt for 3D to 2D projection', 'convert 3D world coordinates to 2D pixel coordinates using the world2pixel function with a KRT matrix', 'convert camera coordinates to pixel coordinates using cam2pixel with focal length and principal point', 'factorize the Camera projection matrix into K, R, and t components using the factor method', 'flip a PyTorch tensor along specified dimensions using the flip function with multi_meshgrid indexing', 'draw 2D hand skeleton keypoints on an image using a skeleton definition and confidence scores', 'render 3D hand skeleton keypoints as a matplotlib 3D plot and save or return as image array', 'get a dictionary mapping hand joint names to RGB colors based on finger and joint type', 'draw colored bounding box rectangles on an image using OpenCV for hand detection visualization', 'convert a matplotlib figure canvas into a numpy uint8 image array for further processing']
```

Usage

```
{'make_folder_create_dir': 'create a folder at a given path if it does not already exist', 'add_pypath_insert_path': 'add a directory to sys.path so Python can import modules from it', 'make_folder_ensure_output_dir': 'ensure an output directory exists before writing files to it', 'add_pypath_enable_imports': 'enable importing from a custom directory by adding it to sys.path', 'make_folder_and_add_pypath_setup': 'create a project directory and add it to sys.path for imports'}
```

## File: facebookresearch_assemblyhands-toolkit/src/common/utils/preprocessing.py

Prompts

```
['create a folder at a given path if it does not already exist', 'add a directory to sys.path so Python can import modules from it', 'ensure an output directory exists before writing files to it', 'enable importing from a custom directory by adding it to sys.path', 'create a project directory and add it to sys.path for imports', 'load an image from a file path and return it as a float32 numpy array in RGB order', 'load an image, crop it by a bounding box, and update joint coordinates and camera parameters', 'load a skeleton definition file and return a list of joints with name, parent, and child IDs', 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and joints', 'load camera calibration intrinsics and extrinsics from a JSON or text file for ego or exo view types', 'create a Camera object with intrinsic matrix K and extrinsic matrix Rt for 3D to 2D projection', 'convert 3D world coordinates to 2D pixel coordinates using the world2pixel function with a KRT matrix', 'convert camera coordinates to pixel coordinates using cam2pixel with focal length and principal point', 'factorize the Camera projection matrix into K, R, and t components using the factor method', 'flip a PyTorch tensor along specified dimensions using the flip function with multi_meshgrid indexing', 'draw 2D hand skeleton keypoints on an image using a skeleton definition and confidence scores', 'render 3D hand skeleton keypoints as a matplotlib 3D plot and save or return as image array', 'get a dictionary mapping hand joint names to RGB colors based on finger and joint type', 'draw colored bounding box rectangles on an image using OpenCV for hand detection visualization', 'convert a matplotlib figure canvas into a numpy uint8 image array for further processing']
```

Usage

```
{'load_img': 'load an image from a file path and return it as a float32 numpy array in RGB order', 'load_crop_img': 'load an image, crop it by a bounding box, and update joint coordinates and camera parameters', 'load_skeleton': 'load a skeleton definition file and return a list of joints with name, parent, and child IDs', 'augmentation': 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and joints', 'get_calib': 'load camera calibration intrinsics and extrinsics from a JSON or text file for ego or exo view types'}
```

## File: facebookresearch_assemblyhands-toolkit/src/common/utils/transforms.py

Prompts

```
['create a folder at a given path if it does not already exist', 'add a directory to sys.path so Python can import modules from it', 'ensure an output directory exists before writing files to it', 'enable importing from a custom directory by adding it to sys.path', 'create a project directory and add it to sys.path for imports', 'load an image from a file path and return it as a float32 numpy array in RGB order', 'load an image, crop it by a bounding box, and update joint coordinates and camera parameters', 'load a skeleton definition file and return a list of joints with name, parent, and child IDs', 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and joints', 'load camera calibration intrinsics and extrinsics from a JSON or text file for ego or exo view types', 'create a Camera object with intrinsic matrix K and extrinsic matrix Rt for 3D to 2D projection', 'convert 3D world coordinates to 2D pixel coordinates using the world2pixel function with a KRT matrix', 'convert camera coordinates to pixel coordinates using cam2pixel with focal length and principal point', 'factorize the Camera projection matrix into K, R, and t components using the factor method', 'flip a PyTorch tensor along specified dimensions using the flip function with multi_meshgrid indexing', 'draw 2D hand skeleton keypoints on an image using a skeleton definition and confidence scores', 'render 3D hand skeleton keypoints as a matplotlib 3D plot and save or return as image array', 'get a dictionary mapping hand joint names to RGB colors based on finger and joint type', 'draw colored bounding box rectangles on an image using OpenCV for hand detection visualization', 'convert a matplotlib figure canvas into a numpy uint8 image array for further processing']
```

Usage

```
{'create_camera_object': 'create a Camera object with intrinsic matrix K and extrinsic matrix Rt for 3D to 2D projection', 'convert_world_to_pixel': 'convert 3D world coordinates to 2D pixel coordinates using the world2pixel function with a KRT matrix', 'convert_cam_to_pixel': 'convert camera coordinates to pixel coordinates using cam2pixel with focal length and principal point', 'factorize_camera_matrix': 'factorize the Camera projection matrix into K, R, and t components using the factor method', 'flip_tensor_along_dims': 'flip a PyTorch tensor along specified dimensions using the flip function with multi_meshgrid indexing'}
```

## File: facebookresearch_assemblyhands-toolkit/src/common/utils/vis.py

Prompts

```
['create a folder at a given path if it does not already exist', 'add a directory to sys.path so Python can import modules from it', 'ensure an output directory exists before writing files to it', 'enable importing from a custom directory by adding it to sys.path', 'create a project directory and add it to sys.path for imports', 'load an image from a file path and return it as a float32 numpy array in RGB order', 'load an image, crop it by a bounding box, and update joint coordinates and camera parameters', 'load a skeleton definition file and return a list of joints with name, parent, and child IDs', 'apply random data augmentation including translation, scaling, rotation, flipping, and color jitter to an image and joints', 'load camera calibration intrinsics and extrinsics from a JSON or text file for ego or exo view types', 'create a Camera object with intrinsic matrix K and extrinsic matrix Rt for 3D to 2D projection', 'convert 3D world coordinates to 2D pixel coordinates using the world2pixel function with a KRT matrix', 'convert camera coordinates to pixel coordinates using cam2pixel with focal length and principal point', 'factorize the Camera projection matrix into K, R, and t components using the factor method', 'flip a PyTorch tensor along specified dimensions using the flip function with multi_meshgrid indexing', 'draw 2D hand skeleton keypoints on an image using a skeleton definition and confidence scores', 'render 3D hand skeleton keypoints as a matplotlib 3D plot and save or return as image array', 'get a dictionary mapping hand joint names to RGB colors based on finger and joint type', 'draw colored bounding box rectangles on an image using OpenCV for hand detection visualization', 'convert a matplotlib figure canvas into a numpy uint8 image array for further processing']
```

Usage

```
{'vis_keypoints_draw_2d_hand_skeleton': 'draw 2D hand skeleton keypoints on an image using a skeleton definition and confidence scores', 'vis_3d_keypoints_render_3d_hand_skeleton': 'render 3D hand skeleton keypoints as a matplotlib 3D plot and save or return as image array', 'get_keypoint_rgb_map_joint_colors': 'get a dictionary mapping hand joint names to RGB colors based on finger and joint type', 'draw_bbox_on_image_draw_rectangles': 'draw colored bounding box rectangles on an image using OpenCV for hand detection visualization', 'fig2img_convert_matplotlib_figure_to_numpy': 'convert a matplotlib figure canvas into a numpy uint8 image array for further processing'}
```

