# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/models/heads/camera_head.py

Prompts

```
['build a PerspectiveHead module to predict camera translation parameters s, tx, ty from pose tokens', 'create a forward pass through PerspectiveHead to predict camera parameters from decoder pose tokens', 'run perspective_projection to reproject 3D keypoints to 2D image space using predicted camera translation', 'review the PerspectiveHead constructor to configure MLP depth, dropout ratio, and default scale factor', 'test perspective_projection with 3D points and camera intrinsics to verify 2D reprojection output', 'build an MHRHead instance with input_dim and mhr_model_path to predict 3D body mesh from pose tokens', 'run mhr_forward with global_trans, global_rot, body_pose_params, and shape_params to get skinned vertices', 'create a zero-pose initialization tensor using get_zero_pose_init for pose token warm starting', 'replace hand pose parameters in full_pose_params using replace_hands_in_pose with PCA 6D hand predictions', 'forward a batch of pose tokens through MHRHead to get 3D keypoints, vertices, and joint coordinates']
```

Usage

```
{'build_PerspectiveHead': 'build a PerspectiveHead module to predict camera translation parameters s, tx, ty from pose tokens', 'create_PerspectiveHead_forward': 'create a forward pass through PerspectiveHead to predict camera parameters from decoder pose tokens', 'run_PerspectiveHead_perspective_projection': 'run perspective_projection to reproject 3D keypoints to 2D image space using predicted camera translation', 'review_PerspectiveHead_init': 'review the PerspectiveHead constructor to configure MLP depth, dropout ratio, and default scale factor', 'test_PerspectiveHead_perspective_projection': 'test perspective_projection with 3D points and camera intrinsics to verify 2D reprojection output'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/models/heads/mhr_head.py

Prompts

```
['build a PerspectiveHead module to predict camera translation parameters s, tx, ty from pose tokens', 'create a forward pass through PerspectiveHead to predict camera parameters from decoder pose tokens', 'run perspective_projection to reproject 3D keypoints to 2D image space using predicted camera translation', 'review the PerspectiveHead constructor to configure MLP depth, dropout ratio, and default scale factor', 'test perspective_projection with 3D points and camera intrinsics to verify 2D reprojection output', 'build an MHRHead instance with input_dim and mhr_model_path to predict 3D body mesh from pose tokens', 'run mhr_forward with global_trans, global_rot, body_pose_params, and shape_params to get skinned vertices', 'create a zero-pose initialization tensor using get_zero_pose_init for pose token warm starting', 'replace hand pose parameters in full_pose_params using replace_hands_in_pose with PCA 6D hand predictions', 'forward a batch of pose tokens through MHRHead to get 3D keypoints, vertices, and joint coordinates']
```

Usage

```
{'build_mhr_head_model': 'build an MHRHead instance with input_dim and mhr_model_path to predict 3D body mesh from pose tokens', 'run_mhr_forward': 'run mhr_forward with global_trans, global_rot, body_pose_params, and shape_params to get skinned vertices', 'create_zero_pose_init': 'create a zero-pose initialization tensor using get_zero_pose_init for pose token warm starting', 'replace_hands_in_pose': 'replace hand pose parameters in full_pose_params using replace_hands_in_pose with PCA 6D hand predictions', 'forward_mhr_head': 'forward a batch of pose tokens through MHRHead to get 3D keypoints, vertices, and joint coordinates'}
```

