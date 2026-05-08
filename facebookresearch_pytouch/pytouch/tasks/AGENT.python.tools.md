# Agent Python Tools

- repo: facebookresearch/pytouch
- repo_uri: https://github.com/facebookresearch/pytouch

## File: facebookresearch_pytouch/pytouch/tasks/slip_detect.py

Prompts

```
['build a spatial and temporal transform pipeline for slip detection video data using SlipDetect.transform', 'create spatial transforms with scale, center crop, and normalization for slip detection training data', 'test the SlipDetect.transform static method to verify it returns spatial, temporal, and target transforms', 'review the SlipDetect class and its transform method for video data augmentation and normalization', 'summarize the SlipDetect.transform method that composes torchvision transforms for slip detection tasks', 'build a Surface3D model instance with sensor params and optional model path for 3D reconstruction', 'run the point_cloud_3d method to reconstruct a 3D point cloud from a color image', 'test the normals method to predict surface normals from a color image input', 'review the normal_to_grad_depth method that converts a normal map to gradient depth values', 'summarize the depth_to_points3d method that back-projects a depth map to 3D points using camera matrices', 'create a TouchDetect model from a sensor and zoo model to classify touch on frames', 'run the is_touching method on a frame to get a touch prediction and certainty score', 'process a raw frame through the model transform pipeline and return a batched tensor', 'build a Compose transform pipeline with resize, normalization, and optional augmentation for training', 'load a custom TouchDetect model from a file path instead of the PyTouchZoo registry']
```

Usage

```
{'build_slip_detect_transform_pipeline': 'build a spatial and temporal transform pipeline for slip detection video data using SlipDetect.transform', 'create_slip_detect_spatial_transforms': 'create spatial transforms with scale, center crop, and normalization for slip detection training data', 'test_slipdetect_transform_static_method': 'test the SlipDetect.transform static method to verify it returns spatial, temporal, and target transforms', 'review_slipdetect_class': 'review the SlipDetect class and its transform method for video data augmentation and normalization', 'summarize_slipdetect_transform': 'summarize the SlipDetect.transform method that composes torchvision transforms for slip detection tasks'}
```

## File: facebookresearch_pytouch/pytouch/tasks/surface_3d.py

Prompts

```
['build a spatial and temporal transform pipeline for slip detection video data using SlipDetect.transform', 'create spatial transforms with scale, center crop, and normalization for slip detection training data', 'test the SlipDetect.transform static method to verify it returns spatial, temporal, and target transforms', 'review the SlipDetect class and its transform method for video data augmentation and normalization', 'summarize the SlipDetect.transform method that composes torchvision transforms for slip detection tasks', 'build a Surface3D model instance with sensor params and optional model path for 3D reconstruction', 'run the point_cloud_3d method to reconstruct a 3D point cloud from a color image', 'test the normals method to predict surface normals from a color image input', 'review the normal_to_grad_depth method that converts a normal map to gradient depth values', 'summarize the depth_to_points3d method that back-projects a depth map to 3D points using camera matrices', 'create a TouchDetect model from a sensor and zoo model to classify touch on frames', 'run the is_touching method on a frame to get a touch prediction and certainty score', 'process a raw frame through the model transform pipeline and return a batched tensor', 'build a Compose transform pipeline with resize, normalization, and optional augmentation for training', 'load a custom TouchDetect model from a file path instead of the PyTouchZoo registry']
```

Usage

```
{'build_surface3d_model': 'build a Surface3D model instance with sensor params and optional model path for 3D reconstruction', 'run_point_cloud_3d': 'run the point_cloud_3d method to reconstruct a 3D point cloud from a color image', 'test_normals_prediction': 'test the normals method to predict surface normals from a color image input', 'review_normal_to_grad_depth': 'review the normal_to_grad_depth method that converts a normal map to gradient depth values', 'summarize_depth_to_points3d': 'summarize the depth_to_points3d method that back-projects a depth map to 3D points using camera matrices'}
```

## File: facebookresearch_pytouch/pytouch/tasks/touch_detect.py

Prompts

```
['build a spatial and temporal transform pipeline for slip detection video data using SlipDetect.transform', 'create spatial transforms with scale, center crop, and normalization for slip detection training data', 'test the SlipDetect.transform static method to verify it returns spatial, temporal, and target transforms', 'review the SlipDetect class and its transform method for video data augmentation and normalization', 'summarize the SlipDetect.transform method that composes torchvision transforms for slip detection tasks', 'build a Surface3D model instance with sensor params and optional model path for 3D reconstruction', 'run the point_cloud_3d method to reconstruct a 3D point cloud from a color image', 'test the normals method to predict surface normals from a color image input', 'review the normal_to_grad_depth method that converts a normal map to gradient depth values', 'summarize the depth_to_points3d method that back-projects a depth map to 3D points using camera matrices', 'create a TouchDetect model from a sensor and zoo model to classify touch on frames', 'run the is_touching method on a frame to get a touch prediction and certainty score', 'process a raw frame through the model transform pipeline and return a batched tensor', 'build a Compose transform pipeline with resize, normalization, and optional augmentation for training', 'load a custom TouchDetect model from a file path instead of the PyTouchZoo registry']
```

Usage

```
{'create_touchdetect_model': 'create a TouchDetect model from a sensor and zoo model to classify touch on frames', 'run_is_touching': 'run the is_touching method on a frame to get a touch prediction and certainty score', 'process_frame': 'process a raw frame through the model transform pipeline and return a batched tensor', 'build_transform_pipeline': 'build a Compose transform pipeline with resize, normalization, and optional augmentation for training', 'load_custom_model': 'load a custom TouchDetect model from a file path instead of the PyTouchZoo registry'}
```

