# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/RoDynRF/camera.py

Prompts

```
['create a camera pose from rotation matrix R and translation vector t using the Pose class', 'invert a camera pose by transposing rotation and computing negative translation with the Pose class', 'compose a sequence of camera poses together to create a new combined pose using Pose.compose', 'convert an SO(3) Lie algebra vector to a 3x3 rotation matrix using Lie.so3_to_SO3', 'convert an SE(3) Lie algebra vector to a 3x4 transformation matrix using Lie.se3_to_SE3', 'convert a [H,W,2] optical flow numpy array into a color-coded [H,W,3] visualization image', 'convert an optical flow array to a BGR visualization image with optional clipping of max flow values', 'generate a 55x3 color wheel numpy array for optical flow visualization using the Middlebury standard', 'apply the flow color wheel to horizontal and vertical flow components to produce a color image', 'summarize the optical flow visualization module that converts flow vectors into color-coded images']
```

Usage

```
{'create_camera_pose_from_rotation_translation': 'create a camera pose from rotation matrix R and translation vector t using the Pose class', 'invert_camera_pose': 'invert a camera pose by transposing rotation and computing negative translation with the Pose class', 'compose_camera_poses': 'compose a sequence of camera poses together to create a new combined pose using Pose.compose', 'convert_so3_to_rotation_matrix': 'convert an SO(3) Lie algebra vector to a 3x3 rotation matrix using Lie.so3_to_SO3', 'convert_se3_to_se3_matrix': 'convert an SE(3) Lie algebra vector to a 3x4 transformation matrix using Lie.se3_to_SE3'}
```

## File: facebookresearch_omnimatterf/third_party/RoDynRF/flow_viz.py

Prompts

```
['create a camera pose from rotation matrix R and translation vector t using the Pose class', 'invert a camera pose by transposing rotation and computing negative translation with the Pose class', 'compose a sequence of camera poses together to create a new combined pose using Pose.compose', 'convert an SO(3) Lie algebra vector to a 3x3 rotation matrix using Lie.so3_to_SO3', 'convert an SE(3) Lie algebra vector to a 3x4 transformation matrix using Lie.se3_to_SE3', 'convert a [H,W,2] optical flow numpy array into a color-coded [H,W,3] visualization image', 'convert an optical flow array to a BGR visualization image with optional clipping of max flow values', 'generate a 55x3 color wheel numpy array for optical flow visualization using the Middlebury standard', 'apply the flow color wheel to horizontal and vertical flow components to produce a color image', 'summarize the optical flow visualization module that converts flow vectors into color-coded images']
```

Usage

```
{'convert_flow_to_image': 'convert a [H,W,2] optical flow numpy array into a color-coded [H,W,3] visualization image', 'convert_flow_to_bgr_image': 'convert an optical flow array to a BGR visualization image with optional clipping of max flow values', 'generate_colorwheel': 'generate a 55x3 color wheel numpy array for optical flow visualization using the Middlebury standard', 'apply_colorwheel_to_flow': 'apply the flow color wheel to horizontal and vertical flow components to produce a color image', 'summarize_flow_viz_module': 'summarize the optical flow visualization module that converts flow vectors into color-coded images'}
```

