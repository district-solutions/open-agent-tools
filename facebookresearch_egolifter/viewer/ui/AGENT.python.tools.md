# Agent Python Tools

- repo: facebookresearch/egolifter
- repo_uri: https://github.com/facebookresearch/egolifter

## File: facebookresearch_egolifter/viewer/ui/edit_panel.py

Prompts

```
['build a Viser GUI panel with point cloud, edit, and save folders for 3D gaussian editing', 'create a boolean mask to select gaussians within grid boundaries using world-to-grid transform', 'test the delete gaussians button callback that removes selected gaussians and updates the point cloud', 'refactor the save gaussian folder to export PLY and checkpoint files with validated naming', 'review the resize grid method that removes and recreates a grid with updated dimensions', 'create a Keyframe from a Viser CameraHandle with model transform and aspect ratio settings', "update a Keyframe's model sizes and poses from current slider and transform control values", 'add a Keyframe camera to a CameraPath and render its 3D frustum handle in the Viser scene', 'interpolate camera pose, FOV, model sizes, and model poses at a normalized time along the spline path', 'populate a Viser server render tab with keyframe management, playback controls, and camera path JSON export', 'create a ModelPose dataclass with wxyz quaternion and position numpy arrays', 'build a TransformPanel with viser GUI sliders, checkboxes, and vector3 inputs for model transforms', 'test set_model_transform_control_value to update a model transform controls handle wxyz and position', 'refactor quaternion_to_euler_angle_vectorized2 to convert wxyz quaternion to roll pitch yaw Euler angles in degrees', 'review TransformPanel _transform_model method that applies scale rotation and translation to a gaussian model']
```

Usage

```
{'build_edit_panel_gui': 'build a Viser GUI panel with point cloud, edit, and save folders for 3D gaussian editing', 'create_gaussian_selection_mask': 'create a boolean mask to select gaussians within grid boundaries using world-to-grid transform', 'test_delete_gaussians': 'test the delete gaussians button callback that removes selected gaussians and updates the point cloud', 'refactor_save_gaussian_checkpoint': 'refactor the save gaussian folder to export PLY and checkpoint files with validated naming', 'review_resize_grid': 'review the resize grid method that removes and recreates a grid with updated dimensions'}
```

## File: facebookresearch_egolifter/viewer/ui/render_panel.py

Prompts

```
['build a Viser GUI panel with point cloud, edit, and save folders for 3D gaussian editing', 'create a boolean mask to select gaussians within grid boundaries using world-to-grid transform', 'test the delete gaussians button callback that removes selected gaussians and updates the point cloud', 'refactor the save gaussian folder to export PLY and checkpoint files with validated naming', 'review the resize grid method that removes and recreates a grid with updated dimensions', 'create a Keyframe from a Viser CameraHandle with model transform and aspect ratio settings', "update a Keyframe's model sizes and poses from current slider and transform control values", 'add a Keyframe camera to a CameraPath and render its 3D frustum handle in the Viser scene', 'interpolate camera pose, FOV, model sizes, and model poses at a normalized time along the spline path', 'populate a Viser server render tab with keyframe management, playback controls, and camera path JSON export', 'create a ModelPose dataclass with wxyz quaternion and position numpy arrays', 'build a TransformPanel with viser GUI sliders, checkboxes, and vector3 inputs for model transforms', 'test set_model_transform_control_value to update a model transform controls handle wxyz and position', 'refactor quaternion_to_euler_angle_vectorized2 to convert wxyz quaternion to roll pitch yaw Euler angles in degrees', 'review TransformPanel _transform_model method that applies scale rotation and translation to a gaussian model']
```

Usage

```
{'create_Keyframe_from_camera': 'create a Keyframe from a Viser CameraHandle with model transform and aspect ratio settings', 'update_Keyframe_model_poses': "update a Keyframe's model sizes and poses from current slider and transform control values", 'add_camera_to_CameraPath': 'add a Keyframe camera to a CameraPath and render its 3D frustum handle in the Viser scene', 'interpolate_CameraPath_pose_and_fov': 'interpolate camera pose, FOV, model sizes, and model poses at a normalized time along the spline path', 'populate_render_tab_GUI': 'populate a Viser server render tab with keyframe management, playback controls, and camera path JSON export'}
```

## File: facebookresearch_egolifter/viewer/ui/transform_panel.py

Prompts

```
['build a Viser GUI panel with point cloud, edit, and save folders for 3D gaussian editing', 'create a boolean mask to select gaussians within grid boundaries using world-to-grid transform', 'test the delete gaussians button callback that removes selected gaussians and updates the point cloud', 'refactor the save gaussian folder to export PLY and checkpoint files with validated naming', 'review the resize grid method that removes and recreates a grid with updated dimensions', 'create a Keyframe from a Viser CameraHandle with model transform and aspect ratio settings', "update a Keyframe's model sizes and poses from current slider and transform control values", 'add a Keyframe camera to a CameraPath and render its 3D frustum handle in the Viser scene', 'interpolate camera pose, FOV, model sizes, and model poses at a normalized time along the spline path', 'populate a Viser server render tab with keyframe management, playback controls, and camera path JSON export', 'create a ModelPose dataclass with wxyz quaternion and position numpy arrays', 'build a TransformPanel with viser GUI sliders, checkboxes, and vector3 inputs for model transforms', 'test set_model_transform_control_value to update a model transform controls handle wxyz and position', 'refactor quaternion_to_euler_angle_vectorized2 to convert wxyz quaternion to roll pitch yaw Euler angles in degrees', 'review TransformPanel _transform_model method that applies scale rotation and translation to a gaussian model']
```

Usage

```
{'create_ModelPose_dataclass': 'create a ModelPose dataclass with wxyz quaternion and position numpy arrays', 'build_TransformPanel_with_gui': 'build a TransformPanel with viser GUI sliders, checkboxes, and vector3 inputs for model transforms', 'test_set_model_transform_control_value': 'test set_model_transform_control_value to update a model transform controls handle wxyz and position', 'refactor_quaternion_to_euler_angle_vectorized2': 'refactor quaternion_to_euler_angle_vectorized2 to convert wxyz quaternion to roll pitch yaw Euler angles in degrees', 'review_TransformPanel_transform_model': 'review TransformPanel _transform_model method that applies scale rotation and translation to a gaussian model'}
```

