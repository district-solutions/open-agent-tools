# Agent Python Tools

- repo: facebookresearch/projectariatools
- repo_uri: https://github.com/facebookresearch/projectaria_tools

## File: facebookresearch_projectariatools/projectaria_tools/utils/calibration_utils.py

Prompts

```
['undistort a camera image and return the updated pinhole calibration using projectaria_tools', 'undistort an image from a distorted camera model to a pinhole model and get the new calibration', 'rotate an image 270 degrees clockwise and update the camera calibration intrinsics and extrinsics', 'rotate a camera calibration clockwise 90 degrees to match an upright rotated image', 'review the undistort_image_and_calibration function to understand how it converts distorted images to pinhole', 'convert a Sophus SE3 pose to a Rerun Transform3D object for 3D visualization', 'create a labeled 3D box with a custom size for Rerun visualization', 'generate a list of 3D points outlining an Aria glasses device from its calibration data', 'create hand skeleton line segments from landmark locations and landmark name pairs', 'create a complete hand skeleton outline from 3D or 2D hand landmark locations']
```

Usage

```
{'undistort_image': 'undistort a camera image and return the updated pinhole calibration using projectaria_tools', 'undistort_and_update_calibration': 'undistort an image from a distorted camera model to a pinhole model and get the new calibration', 'rotate_image_upright': 'rotate an image 270 degrees clockwise and update the camera calibration intrinsics and extrinsics', 'rotate_calibration_cw90': 'rotate a camera calibration clockwise 90 degrees to match an upright rotated image', 'review_undistort_function': 'review the undistort_image_and_calibration function to understand how it converts distorted images to pinhole'}
```

## File: facebookresearch_projectariatools/projectaria_tools/utils/rerun_helpers.py

Prompts

```
['undistort a camera image and return the updated pinhole calibration using projectaria_tools', 'undistort an image from a distorted camera model to a pinhole model and get the new calibration', 'rotate an image 270 degrees clockwise and update the camera calibration intrinsics and extrinsics', 'rotate a camera calibration clockwise 90 degrees to match an upright rotated image', 'review the undistort_image_and_calibration function to understand how it converts distorted images to pinhole', 'convert a Sophus SE3 pose to a Rerun Transform3D object for 3D visualization', 'create a labeled 3D box with a custom size for Rerun visualization', 'generate a list of 3D points outlining an Aria glasses device from its calibration data', 'create hand skeleton line segments from landmark locations and landmark name pairs', 'create a complete hand skeleton outline from 3D or 2D hand landmark locations']
```

Usage

```
{'convert_SE3_to_rerun_Transform3D': 'convert a Sophus SE3 pose to a Rerun Transform3D object for 3D visualization', 'create_rerun_Box3D': 'create a labeled 3D box with a custom size for Rerun visualization', 'generate_Aria_glasses_outline': 'generate a list of 3D points outlining an Aria glasses device from its calibration data', 'create_hand_skeleton_segments': 'create hand skeleton line segments from landmark locations and landmark name pairs', 'create_full_hand_skeleton': 'create a complete hand skeleton outline from 3D or 2D hand landmark locations'}
```

