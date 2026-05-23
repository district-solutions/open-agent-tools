# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/models/pose_estimators/base.py

Prompts

```
['build a pose estimator model with backbone, neck, and head components using BasePoseEstimator', 'run the forward pass in predict mode to get pose predictions from input tensors', 'extract multi-level features from input images using the backbone and neck modules', 'load and parse pose meta information including keypoints definition and properties', 'migrate old version state dict keys from keypoint_head to head format for compatibility', 'build a BottomupPoseEstimator with backbone, neck, and head configs for pose estimation', 'run the loss method on input tensors and data samples to compute training losses', 'predict keypoints and keypoint scores from input images using the bottom-up pose estimator', 'test the predict method with multiscale and flip test augmentation configurations enabled', 'review the add_pred_to_datasample method that converts keypoint coordinates from input space to image space', 'build a PoseLifter model with backbone, head, and optional trajectory model config', 'extract multi-level features from input tensor using the PoseLifter backbone and neck', 'calculate training losses from inputs and data samples for pose and trajectory heads', 'predict 3D keypoints and scores from input tensor and data samples with post-processing', 'add pose and trajectory predictions into data samples with optional keypoint filtering', 'build a TopdownPoseEstimator with backbone, neck, and head config dicts for pose estimation', 'run a single training step on batch data using the TopdownPoseEstimator train_step method', 'calculate losses from input tensors and data samples using the TopdownPoseEstimator loss method', 'parse raw loss outputs and detect NaN or spike anomalies using parse_losses', 'predict pose keypoints from input images using the TopdownPoseEstimator predict method with flip test', 'build a Pose3dTopdownEstimator with backbone, head, and pose3d_head config for 3D pose estimation', 'predict 3D pose keypoints from input tensors and data samples using the topdown estimator', 'parse a dict of loss tensors into a total loss and log vars with nan spike handling', 'add predicted keypoints and bbox info to data samples converting from input to image space']
```

Usage

```
{'build_pose_estimator': 'build a pose estimator model with backbone, neck, and head components using BasePoseEstimator', 'forward_pose_predict': 'run the forward pass in predict mode to get pose predictions from input tensors', 'extract_pose_features': 'extract multi-level features from input images using the backbone and neck modules', 'load_metainfo_pose': 'load and parse pose meta information including keypoints definition and properties', 'migrate_state_dict': 'migrate old version state dict keys from keypoint_head to head format for compatibility'}
```

## File: facebookresearch_sapiens/pose/mmpose/models/pose_estimators/bottomup.py

Prompts

```
['build a pose estimator model with backbone, neck, and head components using BasePoseEstimator', 'run the forward pass in predict mode to get pose predictions from input tensors', 'extract multi-level features from input images using the backbone and neck modules', 'load and parse pose meta information including keypoints definition and properties', 'migrate old version state dict keys from keypoint_head to head format for compatibility', 'build a BottomupPoseEstimator with backbone, neck, and head configs for pose estimation', 'run the loss method on input tensors and data samples to compute training losses', 'predict keypoints and keypoint scores from input images using the bottom-up pose estimator', 'test the predict method with multiscale and flip test augmentation configurations enabled', 'review the add_pred_to_datasample method that converts keypoint coordinates from input space to image space', 'build a PoseLifter model with backbone, head, and optional trajectory model config', 'extract multi-level features from input tensor using the PoseLifter backbone and neck', 'calculate training losses from inputs and data samples for pose and trajectory heads', 'predict 3D keypoints and scores from input tensor and data samples with post-processing', 'add pose and trajectory predictions into data samples with optional keypoint filtering', 'build a TopdownPoseEstimator with backbone, neck, and head config dicts for pose estimation', 'run a single training step on batch data using the TopdownPoseEstimator train_step method', 'calculate losses from input tensors and data samples using the TopdownPoseEstimator loss method', 'parse raw loss outputs and detect NaN or spike anomalies using parse_losses', 'predict pose keypoints from input images using the TopdownPoseEstimator predict method with flip test', 'build a Pose3dTopdownEstimator with backbone, head, and pose3d_head config for 3D pose estimation', 'predict 3D pose keypoints from input tensors and data samples using the topdown estimator', 'parse a dict of loss tensors into a total loss and log vars with nan spike handling', 'add predicted keypoints and bbox info to data samples converting from input to image space']
```

Usage

```
{'build_bottomup_pose_estimator': 'build a BottomupPoseEstimator with backbone, neck, and head configs for pose estimation', 'run_loss_calculation': 'run the loss method on input tensors and data samples to compute training losses', 'predict_keypoints_bottomup': 'predict keypoints and keypoint scores from input images using the bottom-up pose estimator', 'test_multiscale_flip_prediction': 'test the predict method with multiscale and flip test augmentation configurations enabled', 'review_add_pred_to_datasample': 'review the add_pred_to_datasample method that converts keypoint coordinates from input space to image space'}
```

## File: facebookresearch_sapiens/pose/mmpose/models/pose_estimators/pose_lifter.py

Prompts

```
['build a pose estimator model with backbone, neck, and head components using BasePoseEstimator', 'run the forward pass in predict mode to get pose predictions from input tensors', 'extract multi-level features from input images using the backbone and neck modules', 'load and parse pose meta information including keypoints definition and properties', 'migrate old version state dict keys from keypoint_head to head format for compatibility', 'build a BottomupPoseEstimator with backbone, neck, and head configs for pose estimation', 'run the loss method on input tensors and data samples to compute training losses', 'predict keypoints and keypoint scores from input images using the bottom-up pose estimator', 'test the predict method with multiscale and flip test augmentation configurations enabled', 'review the add_pred_to_datasample method that converts keypoint coordinates from input space to image space', 'build a PoseLifter model with backbone, head, and optional trajectory model config', 'extract multi-level features from input tensor using the PoseLifter backbone and neck', 'calculate training losses from inputs and data samples for pose and trajectory heads', 'predict 3D keypoints and scores from input tensor and data samples with post-processing', 'add pose and trajectory predictions into data samples with optional keypoint filtering', 'build a TopdownPoseEstimator with backbone, neck, and head config dicts for pose estimation', 'run a single training step on batch data using the TopdownPoseEstimator train_step method', 'calculate losses from input tensors and data samples using the TopdownPoseEstimator loss method', 'parse raw loss outputs and detect NaN or spike anomalies using parse_losses', 'predict pose keypoints from input images using the TopdownPoseEstimator predict method with flip test', 'build a Pose3dTopdownEstimator with backbone, head, and pose3d_head config for 3D pose estimation', 'predict 3D pose keypoints from input tensors and data samples using the topdown estimator', 'parse a dict of loss tensors into a total loss and log vars with nan spike handling', 'add predicted keypoints and bbox info to data samples converting from input to image space']
```

Usage

```
{'build_PoseLifter': 'build a PoseLifter model with backbone, head, and optional trajectory model config', 'extract_feat_PoseLifter': 'extract multi-level features from input tensor using the PoseLifter backbone and neck', 'loss_PoseLifter': 'calculate training losses from inputs and data samples for pose and trajectory heads', 'predict_PoseLifter': 'predict 3D keypoints and scores from input tensor and data samples with post-processing', 'add_pred_to_datasample_PoseLifter': 'add pose and trajectory predictions into data samples with optional keypoint filtering'}
```

## File: facebookresearch_sapiens/pose/mmpose/models/pose_estimators/topdown.py

Prompts

```
['build a pose estimator model with backbone, neck, and head components using BasePoseEstimator', 'run the forward pass in predict mode to get pose predictions from input tensors', 'extract multi-level features from input images using the backbone and neck modules', 'load and parse pose meta information including keypoints definition and properties', 'migrate old version state dict keys from keypoint_head to head format for compatibility', 'build a BottomupPoseEstimator with backbone, neck, and head configs for pose estimation', 'run the loss method on input tensors and data samples to compute training losses', 'predict keypoints and keypoint scores from input images using the bottom-up pose estimator', 'test the predict method with multiscale and flip test augmentation configurations enabled', 'review the add_pred_to_datasample method that converts keypoint coordinates from input space to image space', 'build a PoseLifter model with backbone, head, and optional trajectory model config', 'extract multi-level features from input tensor using the PoseLifter backbone and neck', 'calculate training losses from inputs and data samples for pose and trajectory heads', 'predict 3D keypoints and scores from input tensor and data samples with post-processing', 'add pose and trajectory predictions into data samples with optional keypoint filtering', 'build a TopdownPoseEstimator with backbone, neck, and head config dicts for pose estimation', 'run a single training step on batch data using the TopdownPoseEstimator train_step method', 'calculate losses from input tensors and data samples using the TopdownPoseEstimator loss method', 'parse raw loss outputs and detect NaN or spike anomalies using parse_losses', 'predict pose keypoints from input images using the TopdownPoseEstimator predict method with flip test', 'build a Pose3dTopdownEstimator with backbone, head, and pose3d_head config for 3D pose estimation', 'predict 3D pose keypoints from input tensors and data samples using the topdown estimator', 'parse a dict of loss tensors into a total loss and log vars with nan spike handling', 'add predicted keypoints and bbox info to data samples converting from input to image space']
```

Usage

```
{'build_topdown_pose_estimator': 'build a TopdownPoseEstimator with backbone, neck, and head config dicts for pose estimation', 'run_train_step': 'run a single training step on batch data using the TopdownPoseEstimator train_step method', 'calculate_loss': 'calculate losses from input tensors and data samples using the TopdownPoseEstimator loss method', 'parse_losses_with_spike_detection': 'parse raw loss outputs and detect NaN or spike anomalies using parse_losses', 'predict_pose_keypoints': 'predict pose keypoints from input images using the TopdownPoseEstimator predict method with flip test'}
```

## File: facebookresearch_sapiens/pose/mmpose/models/pose_estimators/topdown3d.py

Prompts

```
['build a pose estimator model with backbone, neck, and head components using BasePoseEstimator', 'run the forward pass in predict mode to get pose predictions from input tensors', 'extract multi-level features from input images using the backbone and neck modules', 'load and parse pose meta information including keypoints definition and properties', 'migrate old version state dict keys from keypoint_head to head format for compatibility', 'build a BottomupPoseEstimator with backbone, neck, and head configs for pose estimation', 'run the loss method on input tensors and data samples to compute training losses', 'predict keypoints and keypoint scores from input images using the bottom-up pose estimator', 'test the predict method with multiscale and flip test augmentation configurations enabled', 'review the add_pred_to_datasample method that converts keypoint coordinates from input space to image space', 'build a PoseLifter model with backbone, head, and optional trajectory model config', 'extract multi-level features from input tensor using the PoseLifter backbone and neck', 'calculate training losses from inputs and data samples for pose and trajectory heads', 'predict 3D keypoints and scores from input tensor and data samples with post-processing', 'add pose and trajectory predictions into data samples with optional keypoint filtering', 'build a TopdownPoseEstimator with backbone, neck, and head config dicts for pose estimation', 'run a single training step on batch data using the TopdownPoseEstimator train_step method', 'calculate losses from input tensors and data samples using the TopdownPoseEstimator loss method', 'parse raw loss outputs and detect NaN or spike anomalies using parse_losses', 'predict pose keypoints from input images using the TopdownPoseEstimator predict method with flip test', 'build a Pose3dTopdownEstimator with backbone, head, and pose3d_head config for 3D pose estimation', 'predict 3D pose keypoints from input tensors and data samples using the topdown estimator', 'parse a dict of loss tensors into a total loss and log vars with nan spike handling', 'add predicted keypoints and bbox info to data samples converting from input to image space']
```

Usage

```
{'build_pose3d_estimator': 'build a Pose3dTopdownEstimator with backbone, head, and pose3d_head config for 3D pose estimation', 'run_train_step': 'run a training step with data and optim_wrapper to compute losses and update model parameters', 'predict_3d_pose': 'predict 3D pose keypoints from input tensors and data samples using the topdown estimator', 'parse_losses_nan_handling': 'parse a dict of loss tensors into a total loss and log vars with nan spike handling', 'add_pred_to_datasample': 'add predicted keypoints and bbox info to data samples converting from input to image space'}
```

