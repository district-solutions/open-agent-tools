# Agent Python Tools

- repo: facebookresearch/assemblyhands-toolkit
- repo_uri: https://github.com/facebookresearch/assemblyhands-toolkit

## File: facebookresearch_assemblyhands-toolkit/calib/affine.py

Prompts

```
['use transform3 to apply an affine transformation matrix to an array of 3D points', 'use transform_vec3 to apply rotation and scale to 3D vectors ignoring translation', 'use as_4x4 to convert a 3x4 affine matrix into a 4x4 homogeneous matrix', 'use normalized to return unit-length copies of vectors along a specified axis', 'use transform3 with batched affine matrices and point arrays that are broadcastable', 'create an OpenCVCameraModel instance with width, height, focal length, optical center, and distortion coefficients', 'create an OV62CameraModel fisheye camera instance with width, height, focal length, center, and distortion params', 'load a CameraModel from a JSON string or dict containing calibration parameters and extrinsics', 'call world_to_window on a CameraModel to project 3D world points to 2D image coordinates', 'call update_extrinsics on a CameraModel to update the camera position and orientation in world space', 'use PerspectiveProjection.project to map 3D eye-space vectors to 2D normalized image coordinates', 'use PerspectiveProjection.project3 to project 3D vectors to 2D while preserving the Z depth component', 'use ArctanProjection.project to apply fisheye arctan projection on 3D vectors for wide FOV over 180 degrees', 'use ArctanProjection.unproject to convert 2D fisheye-projected coordinates back into 3D direction vectors', 'use OpenCVDistortion.evaluate to apply Brown-Conrady radial and tangential distortion to 2D points with k1-k3 and p1-p2 coefficients', 'use OV62Distortion.evaluate to apply OVRFisheye62 distortion with 6 radial and 2 tangential coefficients to 2D points']
```

Usage

```
{'transform_3d_points_with_affine': 'use transform3 to apply an affine transformation matrix to an array of 3D points', 'transform_3d_vectors_without_translation': 'use transform_vec3 to apply rotation and scale to 3D vectors ignoring translation', 'convert_3x4_to_4x4_homogeneous': 'use as_4x4 to convert a 3x4 affine matrix into a 4x4 homogeneous matrix', 'normalize_vectors_to_unit_length': 'use normalized to return unit-length copies of vectors along a specified axis', 'batch_transform_multiple_points': 'use transform3 with batched affine matrices and point arrays that are broadcastable'}
```

## File: facebookresearch_assemblyhands-toolkit/calib/camera.py

Prompts

```
['use transform3 to apply an affine transformation matrix to an array of 3D points', 'use transform_vec3 to apply rotation and scale to 3D vectors ignoring translation', 'use as_4x4 to convert a 3x4 affine matrix into a 4x4 homogeneous matrix', 'use normalized to return unit-length copies of vectors along a specified axis', 'use transform3 with batched affine matrices and point arrays that are broadcastable', 'create an OpenCVCameraModel instance with width, height, focal length, optical center, and distortion coefficients', 'create an OV62CameraModel fisheye camera instance with width, height, focal length, center, and distortion params', 'load a CameraModel from a JSON string or dict containing calibration parameters and extrinsics', 'call world_to_window on a CameraModel to project 3D world points to 2D image coordinates', 'call update_extrinsics on a CameraModel to update the camera position and orientation in world space', 'use PerspectiveProjection.project to map 3D eye-space vectors to 2D normalized image coordinates', 'use PerspectiveProjection.project3 to project 3D vectors to 2D while preserving the Z depth component', 'use ArctanProjection.project to apply fisheye arctan projection on 3D vectors for wide FOV over 180 degrees', 'use ArctanProjection.unproject to convert 2D fisheye-projected coordinates back into 3D direction vectors', 'use OpenCVDistortion.evaluate to apply Brown-Conrady radial and tangential distortion to 2D points with k1-k3 and p1-p2 coefficients', 'use OV62Distortion.evaluate to apply OVRFisheye62 distortion with 6 radial and 2 tangential coefficients to 2D points']
```

Usage

```
{'create_OpenCVCameraModel': 'create an OpenCVCameraModel instance with width, height, focal length, optical center, and distortion coefficients', 'create_OV62CameraModel': 'create an OV62CameraModel fisheye camera instance with width, height, focal length, center, and distortion params', 'load_camera_from_json': 'load a CameraModel from a JSON string or dict containing calibration parameters and extrinsics', 'project_world_to_window': 'call world_to_window on a CameraModel to project 3D world points to 2D image coordinates', 'update_camera_extrinsics': 'call update_extrinsics on a CameraModel to update the camera position and orientation in world space'}
```

## File: facebookresearch_assemblyhands-toolkit/calib/camera_distortion.py

Prompts

```
['use transform3 to apply an affine transformation matrix to an array of 3D points', 'use transform_vec3 to apply rotation and scale to 3D vectors ignoring translation', 'use as_4x4 to convert a 3x4 affine matrix into a 4x4 homogeneous matrix', 'use normalized to return unit-length copies of vectors along a specified axis', 'use transform3 with batched affine matrices and point arrays that are broadcastable', 'create an OpenCVCameraModel instance with width, height, focal length, optical center, and distortion coefficients', 'create an OV62CameraModel fisheye camera instance with width, height, focal length, center, and distortion params', 'load a CameraModel from a JSON string or dict containing calibration parameters and extrinsics', 'call world_to_window on a CameraModel to project 3D world points to 2D image coordinates', 'call update_extrinsics on a CameraModel to update the camera position and orientation in world space', 'use PerspectiveProjection.project to map 3D eye-space vectors to 2D normalized image coordinates', 'use PerspectiveProjection.project3 to project 3D vectors to 2D while preserving the Z depth component', 'use ArctanProjection.project to apply fisheye arctan projection on 3D vectors for wide FOV over 180 degrees', 'use ArctanProjection.unproject to convert 2D fisheye-projected coordinates back into 3D direction vectors', 'use OpenCVDistortion.evaluate to apply Brown-Conrady radial and tangential distortion to 2D points with k1-k3 and p1-p2 coefficients', 'use OV62Distortion.evaluate to apply OVRFisheye62 distortion with 6 radial and 2 tangential coefficients to 2D points']
```

Usage

```
{'project_3d_to_2d_perspective': 'use PerspectiveProjection.project to map 3D eye-space vectors to 2D normalized image coordinates', 'project_3d_with_depth_perspective': 'use PerspectiveProjection.project3 to project 3D vectors to 2D while preserving the Z depth component', 'project_fisheye_arctan': 'use ArctanProjection.project to apply fisheye arctan projection on 3D vectors for wide FOV over 180 degrees', 'unproject_fisheye_2d_to_3d': 'use ArctanProjection.unproject to convert 2D fisheye-projected coordinates back into 3D direction vectors', 'evaluate_opencv_distortion': 'use OpenCVDistortion.evaluate to apply Brown-Conrady radial and tangential distortion to 2D points with k1-k3 and p1-p2 coefficients', 'evaluate_ov62_fisheye_distortion': 'use OV62Distortion.evaluate to apply OVRFisheye62 distortion with 6 radial and 2 tangential coefficients to 2D points'}
```

