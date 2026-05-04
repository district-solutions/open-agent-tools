# Agent Python Tools

- repo: facebookresearch/frankmocap
- repo_uri: https://github.com/facebookresearch/frankmocap

## File: facebookresearch_frankmocap/bodymocap/utils/geometry.py

Prompts

```
['convert a batch of axis-angle vectors to 3x3 rotation matrices using Rodrigues formula', 'convert a batch of quaternion coefficients to 3x3 rotation matrices', 'convert a batch of 6D rotation representations to 3x3 rotation matrices', 'compute the perspective projection of 3D points given camera rotation, translation, focal length, and center', 'estimate camera translation that brings 3D joints closest to corresponding 2D joint locations', 'crop an image using center and scale to extract a person bounding box region', 'transform pixel coordinates between image reference frames using get_transform and transform', 'flip keypoints and SMPL pose parameters for data augmentation using flip_kp and flip_pose', 'compute bounding box center and scale from 2D keypoints or openpose JSON detections', 'process and normalize an image with keypoints or bbox into a PyTorch tensor for model input']
```

Usage

```
{'convert_axis_angle_to_rotation_matrix': 'convert a batch of axis-angle vectors to 3x3 rotation matrices using Rodrigues formula', 'convert_quaternion_to_rotation_matrix': 'convert a batch of quaternion coefficients to 3x3 rotation matrices', 'convert_6d_to_rotation_matrix': 'convert a batch of 6D rotation representations to 3x3 rotation matrices', 'compute_perspective_projection': 'compute the perspective projection of 3D points given camera rotation, translation, focal length, and center', 'estimate_camera_translation': 'estimate camera translation that brings 3D joints closest to corresponding 2D joint locations'}
```

## File: facebookresearch_frankmocap/bodymocap/utils/imutils.py

Prompts

```
['convert a batch of axis-angle vectors to 3x3 rotation matrices using Rodrigues formula', 'convert a batch of quaternion coefficients to 3x3 rotation matrices', 'convert a batch of 6D rotation representations to 3x3 rotation matrices', 'compute the perspective projection of 3D points given camera rotation, translation, focal length, and center', 'estimate camera translation that brings 3D joints closest to corresponding 2D joint locations', 'crop an image using center and scale to extract a person bounding box region', 'transform pixel coordinates between image reference frames using get_transform and transform', 'flip keypoints and SMPL pose parameters for data augmentation using flip_kp and flip_pose', 'compute bounding box center and scale from 2D keypoints or openpose JSON detections', 'process and normalize an image with keypoints or bbox into a PyTorch tensor for model input']
```

Usage

```
{'crop_image_by_bbox': 'crop an image using center and scale to extract a person bounding box region', 'transform_pixel_coords': 'transform pixel coordinates between image reference frames using get_transform and transform', 'flip_keypoints_and_pose': 'flip keypoints and SMPL pose parameters for data augmentation using flip_kp and flip_pose', 'compute_bbox_from_keypoints': 'compute bounding box center and scale from 2D keypoints or openpose JSON detections', 'process_image_for_model': 'process and normalize an image with keypoints or bbox into a PyTorch tensor for model input'}
```

