# Agent Python Tools

- repo: facebookresearch/omni3d
- repo_uri: https://github.com/facebookresearch/omni3d

## File: facebookresearch_omni3d/cubercnn/modeling/roi_heads/cube_head.py

Prompts

```
['build a CubeHead instance from a Detectron2 config and input shape using build_cube_head', 'create a CubeHead neural network module that predicts 3D bounding box dimensions, center, depth, and pose', 'review the CubeHead forward pass that returns 2D deltas, Z depth, dimensions, pose matrix, and uncertainty', 'refactor the CubeHead to support additional pose representations beyond 6D, quaternion, and Euler angles', 'test the CubeHead shared versus separate feature generator branches for 3D cuboid prediction', 'run Fast R-CNN inference on a batch of predicted boxes and scores with NMS', 'run Fast R-CNN inference on a single image with score thresholding and NMS', 'test the FastRCNNOutputs class inference method on proposals to get detections', 'test the FastRCNNOutputs class losses method to compute classification and box regression losses', 'review the FastRCNNOutputs box_reg_loss method for smooth_l1 and GIoU loss computation', 'build ROIHeads from config using build_roi_heads with cfg, input_shape, and optional priors', 'review the ROIHeads3D class that extends StandardROIHeads for 3D cuboid detection and pose estimation', 'review the _forward_cube method that predicts 3D cuboid centers, dimensions, depth, and pose from features', 'review the chamfer_loss method that computes bidirectional L1 distance between predicted and target cuboid corners', 'review the label_and_sample_proposals method that matches proposals to ground truth and samples foreground and background']
```

Usage

```
{'build_cube_head_from_cfg': 'build a CubeHead instance from a Detectron2 config and input shape using build_cube_head', 'create_cube_head_module': 'create a CubeHead neural network module that predicts 3D bounding box dimensions, center, depth, and pose', 'review_cube_head_forward': 'review the CubeHead forward pass that returns 2D deltas, Z depth, dimensions, pose matrix, and uncertainty', 'refactor_cube_head_pose_type': 'refactor the CubeHead to support additional pose representations beyond 6D, quaternion, and Euler angles', 'test_cube_head_shared_fc': 'test the CubeHead shared versus separate feature generator branches for 3D cuboid prediction'}
```

## File: facebookresearch_omni3d/cubercnn/modeling/roi_heads/fast_rcnn.py

Prompts

```
['build a CubeHead instance from a Detectron2 config and input shape using build_cube_head', 'create a CubeHead neural network module that predicts 3D bounding box dimensions, center, depth, and pose', 'review the CubeHead forward pass that returns 2D deltas, Z depth, dimensions, pose matrix, and uncertainty', 'refactor the CubeHead to support additional pose representations beyond 6D, quaternion, and Euler angles', 'test the CubeHead shared versus separate feature generator branches for 3D cuboid prediction', 'run Fast R-CNN inference on a batch of predicted boxes and scores with NMS', 'run Fast R-CNN inference on a single image with score thresholding and NMS', 'test the FastRCNNOutputs class inference method on proposals to get detections', 'test the FastRCNNOutputs class losses method to compute classification and box regression losses', 'review the FastRCNNOutputs box_reg_loss method for smooth_l1 and GIoU loss computation', 'build ROIHeads from config using build_roi_heads with cfg, input_shape, and optional priors', 'review the ROIHeads3D class that extends StandardROIHeads for 3D cuboid detection and pose estimation', 'review the _forward_cube method that predicts 3D cuboid centers, dimensions, depth, and pose from features', 'review the chamfer_loss method that computes bidirectional L1 distance between predicted and target cuboid corners', 'review the label_and_sample_proposals method that matches proposals to ground truth and samples foreground and background']
```

Usage

```
{'run_fast_rcnn_inference': 'run Fast R-CNN inference on a batch of predicted boxes and scores with NMS', 'run_fast_rcnn_inference_single_image': 'run Fast R-CNN inference on a single image with score thresholding and NMS', 'test_FastRCNNOutputs_inference': 'test the FastRCNNOutputs class inference method on proposals to get detections', 'test_FastRCNNOutputs_losses': 'test the FastRCNNOutputs class losses method to compute classification and box regression losses', 'review_FastRCNNOutputs_box_reg_loss': 'review the FastRCNNOutputs box_reg_loss method for smooth_l1 and GIoU loss computation'}
```

## File: facebookresearch_omni3d/cubercnn/modeling/roi_heads/roi_heads.py

Prompts

```
['build a CubeHead instance from a Detectron2 config and input shape using build_cube_head', 'create a CubeHead neural network module that predicts 3D bounding box dimensions, center, depth, and pose', 'review the CubeHead forward pass that returns 2D deltas, Z depth, dimensions, pose matrix, and uncertainty', 'refactor the CubeHead to support additional pose representations beyond 6D, quaternion, and Euler angles', 'test the CubeHead shared versus separate feature generator branches for 3D cuboid prediction', 'run Fast R-CNN inference on a batch of predicted boxes and scores with NMS', 'run Fast R-CNN inference on a single image with score thresholding and NMS', 'test the FastRCNNOutputs class inference method on proposals to get detections', 'test the FastRCNNOutputs class losses method to compute classification and box regression losses', 'review the FastRCNNOutputs box_reg_loss method for smooth_l1 and GIoU loss computation', 'build ROIHeads from config using build_roi_heads with cfg, input_shape, and optional priors', 'review the ROIHeads3D class that extends StandardROIHeads for 3D cuboid detection and pose estimation', 'review the _forward_cube method that predicts 3D cuboid centers, dimensions, depth, and pose from features', 'review the chamfer_loss method that computes bidirectional L1 distance between predicted and target cuboid corners', 'review the label_and_sample_proposals method that matches proposals to ground truth and samples foreground and background']
```

Usage

```
{'build_roi_heads': 'build ROIHeads from config using build_roi_heads with cfg, input_shape, and optional priors', 'review_ROIHeads3D_class': 'review the ROIHeads3D class that extends StandardROIHeads for 3D cuboid detection and pose estimation', 'review_forward_cube': 'review the _forward_cube method that predicts 3D cuboid centers, dimensions, depth, and pose from features', 'review_chamfer_loss': 'review the chamfer_loss method that computes bidirectional L1 distance between predicted and target cuboid corners', 'review_label_and_sample_proposals': 'review the label_and_sample_proposals method that matches proposals to ground truth and samples foreground and background'}
```

