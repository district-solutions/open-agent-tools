# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/models/roi_heads/bbox_heads/bbox_head.py

Prompts

```
['build a BBoxHead instance with configurable classification and regression fc layers for RoI features', 'run the BBoxHead forward pass to get cls_score and bbox_pred from RoI feature tensors', 'get bounding box targets and labels from sampling results for training the RoI head', 'compute classification and bounding box regression losses given predicted scores and targets', 'refine bounding boxes during training by regressing by class and filtering ground truth boxes', 'build a ConvFCBBoxHead with configurable shared conv and fc layers for object detection', 'build a Shared2FCBBoxHead with two shared fully connected layers for bbox regression', 'build a Shared4Conv1FCBBoxHead with four shared conv layers and one fc layer', 'review the ConvFCBBoxHead forward method that returns cls_score and bbox_pred tensors', 'refactor ConvFCBBoxHead to enable stop_grad_reg for detached regression branch gradients', 'build a ConvFCBBoxScoreHead with BoxIoU scoring type and L1 loss for OLN-Box object proposal detection', 'build a Shared2FCBBoxScoreHead with 2 shared FC layers and 1024 output channels for ROI head', 'test the get_targets method to compute labels, bbox_targets, and bbox_score_targets from sampling results', 'review the loss method to compute cls, bbox, and bbox_score losses with reduction override support']
```

Usage

```
{'build_bbox_head': 'build a BBoxHead instance with configurable classification and regression fc layers for RoI features', 'run_forward_pass': 'run the BBoxHead forward pass to get cls_score and bbox_pred from RoI feature tensors', 'get_bbox_targets': 'get bounding box targets and labels from sampling results for training the RoI head', 'compute_bbox_loss': 'compute classification and bounding box regression losses given predicted scores and targets', 'refine_bboxes': 'refine bounding boxes during training by regressing by class and filtering ground truth boxes'}
```

## File: facebookresearch_generic-grouping/mmdet/models/roi_heads/bbox_heads/convfc_bbox_head.py

Prompts

```
['build a BBoxHead instance with configurable classification and regression fc layers for RoI features', 'run the BBoxHead forward pass to get cls_score and bbox_pred from RoI feature tensors', 'get bounding box targets and labels from sampling results for training the RoI head', 'compute classification and bounding box regression losses given predicted scores and targets', 'refine bounding boxes during training by regressing by class and filtering ground truth boxes', 'build a ConvFCBBoxHead with configurable shared conv and fc layers for object detection', 'build a Shared2FCBBoxHead with two shared fully connected layers for bbox regression', 'build a Shared4Conv1FCBBoxHead with four shared conv layers and one fc layer', 'review the ConvFCBBoxHead forward method that returns cls_score and bbox_pred tensors', 'refactor ConvFCBBoxHead to enable stop_grad_reg for detached regression branch gradients', 'build a ConvFCBBoxScoreHead with BoxIoU scoring type and L1 loss for OLN-Box object proposal detection', 'build a Shared2FCBBoxScoreHead with 2 shared FC layers and 1024 output channels for ROI head', 'test the get_targets method to compute labels, bbox_targets, and bbox_score_targets from sampling results', 'review the loss method to compute cls, bbox, and bbox_score losses with reduction override support']
```

Usage

```
{'build_ConvFCBBoxHead': 'build a ConvFCBBoxHead with configurable shared conv and fc layers for object detection', 'build_Shared2FCBBoxHead': 'build a Shared2FCBBoxHead with two shared fully connected layers for bbox regression', 'build_Shared4Conv1FCBBoxHead': 'build a Shared4Conv1FCBBoxHead with four shared conv layers and one fc layer', 'review_ConvFCBBoxHead_forward': 'review the ConvFCBBoxHead forward method that returns cls_score and bbox_pred tensors', 'refactor_ConvFCBBoxHead_stop_grad': 'refactor ConvFCBBoxHead to enable stop_grad_reg for detached regression branch gradients'}
```

## File: facebookresearch_generic-grouping/mmdet/models/roi_heads/bbox_heads/convfc_bbox_score_head.py

Prompts

```
['build a BBoxHead instance with configurable classification and regression fc layers for RoI features', 'run the BBoxHead forward pass to get cls_score and bbox_pred from RoI feature tensors', 'get bounding box targets and labels from sampling results for training the RoI head', 'compute classification and bounding box regression losses given predicted scores and targets', 'refine bounding boxes during training by regressing by class and filtering ground truth boxes', 'build a ConvFCBBoxHead with configurable shared conv and fc layers for object detection', 'build a Shared2FCBBoxHead with two shared fully connected layers for bbox regression', 'build a Shared4Conv1FCBBoxHead with four shared conv layers and one fc layer', 'review the ConvFCBBoxHead forward method that returns cls_score and bbox_pred tensors', 'refactor ConvFCBBoxHead to enable stop_grad_reg for detached regression branch gradients', 'build a ConvFCBBoxScoreHead with BoxIoU scoring type and L1 loss for OLN-Box object proposal detection', 'build a Shared2FCBBoxScoreHead with 2 shared FC layers and 1024 output channels for ROI head', 'test the get_targets method to compute labels, bbox_targets, and bbox_score_targets from sampling results', 'review the loss method to compute cls, bbox, and bbox_score losses with reduction override support']
```

Usage

```
{'build_ConvFCBBoxScoreHead': 'build a ConvFCBBoxScoreHead with BoxIoU scoring type and L1 loss for OLN-Box object proposal detection', 'build_Shared2FCBBoxScoreHead': 'build a Shared2FCBBoxScoreHead with 2 shared FC layers and 1024 output channels for ROI head', 'run_forward_pass': 'run a forward pass through ConvFCBBoxScoreHead to get cls_score, bbox_pred, and bbox_score outputs', 'test_get_targets': 'test the get_targets method to compute labels, bbox_targets, and bbox_score_targets from sampling results', 'review_loss_computation': 'review the loss method to compute cls, bbox, and bbox_score losses with reduction override support'}
```

