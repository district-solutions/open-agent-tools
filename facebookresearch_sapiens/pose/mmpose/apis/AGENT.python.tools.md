# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/apis/inference.py

Prompts

```
['initialize a pose estimator model from a config file and optional checkpoint weights', 'run top-down pose estimation on an image with optional bounding boxes for human keypoints', 'run bottom-up pose estimation on an image to detect human keypoints across the whole image', 'extract dataset metainfo from a model config for train, val, or test dataloaders', 'collect multiple frames from a video reader using frame index offsets for temporal pose inference', 'convert 2D keypoints from COCO or AIC dataset format to Human36M format for 3D pose lifting', 'extract a fixed-length pose sequence centered on a target frame with padding for video frames', 'reorganize multi-frame 2D pose results into individual person pose sequences using track IDs', 'infer 3D poses from 2D pose sequences using a trained pose lifter model', 'review the inference_3d module functions for 3D pose lifting from 2D keypoints']
```

Usage

```
{'init_model_pose_estimator': 'initialize a pose estimator model from a config file and optional checkpoint weights', 'inference_topdown_pose': 'run top-down pose estimation on an image with optional bounding boxes for human keypoints', 'inference_bottomup_pose': 'run bottom-up pose estimation on an image to detect human keypoints across the whole image', 'dataset_meta_from_config': 'extract dataset metainfo from a model config for train, val, or test dataloaders', 'collect_multi_frames_video': 'collect multiple frames from a video reader using frame index offsets for temporal pose inference'}
```

## File: facebookresearch_sapiens/pose/mmpose/apis/inference_3d.py

Prompts

```
['initialize a pose estimator model from a config file and optional checkpoint weights', 'run top-down pose estimation on an image with optional bounding boxes for human keypoints', 'run bottom-up pose estimation on an image to detect human keypoints across the whole image', 'extract dataset metainfo from a model config for train, val, or test dataloaders', 'collect multiple frames from a video reader using frame index offsets for temporal pose inference', 'convert 2D keypoints from COCO or AIC dataset format to Human36M format for 3D pose lifting', 'extract a fixed-length pose sequence centered on a target frame with padding for video frames', 'reorganize multi-frame 2D pose results into individual person pose sequences using track IDs', 'infer 3D poses from 2D pose sequences using a trained pose lifter model', 'review the inference_3d module functions for 3D pose lifting from 2D keypoints']
```

Usage

```
{'convert_keypoint_definition': 'convert 2D keypoints from COCO or AIC dataset format to Human36M format for 3D pose lifting', 'extract_pose_sequence': 'extract a fixed-length pose sequence centered on a target frame with padding for video frames', 'collate_pose_sequence': 'reorganize multi-frame 2D pose results into individual person pose sequences using track IDs', 'inference_pose_lifter_model': 'infer 3D poses from 2D pose sequences using a trained pose lifter model', 'review_inference_3d_module': 'review the inference_3d module functions for 3D pose lifting from 2D keypoints'}
```

