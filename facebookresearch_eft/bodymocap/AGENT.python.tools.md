# Agent Python Tools

- repo: facebookresearch/eft
- repo_uri: https://github.com/facebookresearch/eft

## File: facebookresearch_eft/bodymocap/mocap_api.py

Prompts

```
['create a BodyMocap instance with an SMPL model using a regressor checkpoint and SMPL model directory', 'create a BodyMocap instance with an SMPLX model by setting bUseSMPLX to True', 'run the regress method on a BGR image with a bounding box to predict 3D body mesh vertices', 'run the regress method with bExport True to also get rotation matrices, betas, and camera parameters', 'review the BodyMocap class and its regress method for 3D human pose estimation from images']
```

Usage

```
{'init_bodymocap_with_smpl': 'create a BodyMocap instance with an SMPL model using a regressor checkpoint and SMPL model directory', 'init_bodymocap_with_smplx': 'create a BodyMocap instance with an SMPLX model by setting bUseSMPLX to True', 'regress_body_pose_from_image': 'run the regress method on a BGR image with a bounding box to predict 3D body mesh vertices', 'regress_with_export': 'run the regress method with bExport True to also get rotation matrices, betas, and camera parameters', 'review_bodymocap_class': 'review the BodyMocap class and its regress method for 3D human pose estimation from images'}
```

