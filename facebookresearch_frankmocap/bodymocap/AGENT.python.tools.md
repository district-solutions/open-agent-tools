# Agent Python Tools

- repo: facebookresearch/frankmocap
- repo_uri: https://github.com/facebookresearch/frankmocap

## File: facebookresearch_frankmocap/bodymocap/body_bbox_detector.py

Prompts

```
['detect body poses and bounding boxes from an input image using the BodyPoseEstimator model', 'create a BodyPoseEstimator instance that loads the pretrained MobileNet pose estimation model', 'run fast inference on an image to extract heatmaps and PAFs for pose estimation', 'load the pretrained body pose estimator checkpoint into a PoseEstimationWithMobileNet model', 'extract and group body keypoints from heatmaps and PAFs to produce pose entries and bounding boxes', 'initialize a BodyMocap instance with a regressor checkpoint and SMPL model directory for 3D body pose estimation', 'regress 3D body mesh vertices and joints from an image and list of body bounding boxes', 'extract left and right hand bounding boxes from body regression output using predicted hand joint coordinates', 'review the BodyMocap class that wraps HMR regression and SMPL/SMPLX parametric body model inference', 'summarize the regress method that processes images through HMR to predict SMPL vertices, joints, and camera parameters']
```

Usage

```
{'detect_body_pose': 'detect body poses and bounding boxes from an input image using the BodyPoseEstimator model', 'create_body_pose_estimator': 'create a BodyPoseEstimator instance that loads the pretrained MobileNet pose estimation model', 'infer_fast_heatmaps': 'run fast inference on an image to extract heatmaps and PAFs for pose estimation', 'load_body_estimator_model': 'load the pretrained body pose estimator checkpoint into a PoseEstimationWithMobileNet model', 'extract_body_keypoints': 'extract and group body keypoints from heatmaps and PAFs to produce pose entries and bounding boxes'}
```

## File: facebookresearch_frankmocap/bodymocap/body_mocap_api.py

Prompts

```
['detect body poses and bounding boxes from an input image using the BodyPoseEstimator model', 'create a BodyPoseEstimator instance that loads the pretrained MobileNet pose estimation model', 'run fast inference on an image to extract heatmaps and PAFs for pose estimation', 'load the pretrained body pose estimator checkpoint into a PoseEstimationWithMobileNet model', 'extract and group body keypoints from heatmaps and PAFs to produce pose entries and bounding boxes', 'initialize a BodyMocap instance with a regressor checkpoint and SMPL model directory for 3D body pose estimation', 'regress 3D body mesh vertices and joints from an image and list of body bounding boxes', 'extract left and right hand bounding boxes from body regression output using predicted hand joint coordinates', 'review the BodyMocap class that wraps HMR regression and SMPL/SMPLX parametric body model inference', 'summarize the regress method that processes images through HMR to predict SMPL vertices, joints, and camera parameters']
```

Usage

```
{'init_body_mocap': 'initialize a BodyMocap instance with a regressor checkpoint and SMPL model directory for 3D body pose estimation', 'regress_body_pose': 'regress 3D body mesh vertices and joints from an image and list of body bounding boxes', 'get_hand_bboxes': 'extract left and right hand bounding boxes from body regression output using predicted hand joint coordinates', 'review_BodyMocap_class': 'review the BodyMocap class that wraps HMR regression and SMPL/SMPLX parametric body model inference', 'summarize_regress_method': 'summarize the regress method that processes images through HMR to predict SMPL vertices, joints, and camera parameters'}
```

