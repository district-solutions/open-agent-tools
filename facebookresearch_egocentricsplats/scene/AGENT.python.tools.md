# Agent Python Tools

- repo: facebookresearch/egocentricsplats
- repo_uri: https://github.com/facebookresearch/egocentric_splats

## File: facebookresearch_egocentricsplats/scene/cameras.py

Prompts

```
['create a Camera instance with uid, w2c matrix, FoVx, FoVy, image dimensions, and optional exposure settings', 'create an AriaCamera with closed-loop trajectory, rolling shutter support, and sampled view matrices for motion compensation', 'create a CameraDataset from a list of Camera objects for training or render-only PyTorch data loading', 'interpolate a list of Camera poses into a piecewise trajectory at a target FPS using SLERP and linear translation', 'serialize a Camera object to a JSON-compatible dictionary with id, c2w, fov, fx, fy, and exposure metadata', 'read an Aria scene from an input folder and return a SceneInfo object with cameras and point cloud', 'get scene information from a scene config by dispatching to the appropriate reader based on input format', 'rectify a pinhole camera image by removing radial distortion using OpenCV distortion parameters', 'undistort a fisheye camera image to an equidistant fisheye projection using radial distortion coefficients', 'aggregate multiple SceneInfo objects into one combined scene with merged point clouds and sorted cameras']
```

Usage

```
{'create_Camera': 'create a Camera instance with uid, w2c matrix, FoVx, FoVy, image dimensions, and optional exposure settings', 'create_AriaCamera': 'create an AriaCamera with closed-loop trajectory, rolling shutter support, and sampled view matrices for motion compensation', 'create_CameraDataset': 'create a CameraDataset from a list of Camera objects for training or render-only PyTorch data loading', 'interpolate_cameras_fps': 'interpolate a list of Camera poses into a piecewise trajectory at a target FPS using SLERP and linear translation', 'convert_camera_to_JSON': 'serialize a Camera object to a JSON-compatible dictionary with id, c2w, fov, fx, fy, and exposure metadata'}
```

## File: facebookresearch_egocentricsplats/scene/dataset_readers.py

Prompts

```
['create a Camera instance with uid, w2c matrix, FoVx, FoVy, image dimensions, and optional exposure settings', 'create an AriaCamera with closed-loop trajectory, rolling shutter support, and sampled view matrices for motion compensation', 'create a CameraDataset from a list of Camera objects for training or render-only PyTorch data loading', 'interpolate a list of Camera poses into a piecewise trajectory at a target FPS using SLERP and linear translation', 'serialize a Camera object to a JSON-compatible dictionary with id, c2w, fov, fx, fy, and exposure metadata', 'read an Aria scene from an input folder and return a SceneInfo object with cameras and point cloud', 'get scene information from a scene config by dispatching to the appropriate reader based on input format', 'rectify a pinhole camera image by removing radial distortion using OpenCV distortion parameters', 'undistort a fisheye camera image to an equidistant fisheye projection using radial distortion coefficients', 'aggregate multiple SceneInfo objects into one combined scene with merged point clouds and sorted cameras']
```

Usage

```
{'readAriaSceneInfo': 'read an Aria scene from an input folder and return a SceneInfo object with cameras and point cloud', 'get_scene_info': 'get scene information from a scene config by dispatching to the appropriate reader based on input format', 'pinhole_camera_rectify': 'rectify a pinhole camera image by removing radial distortion using OpenCV distortion parameters', 'equidistant_camera_rectify': 'undistort a fisheye camera image to an equidistant fisheye projection using radial distortion coefficients', 'aggregate_scene_infos': 'aggregate multiple SceneInfo objects into one combined scene with merged point clouds and sorted cameras'}
```

