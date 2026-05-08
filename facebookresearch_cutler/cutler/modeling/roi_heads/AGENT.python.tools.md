# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/cutler/modeling/roi_heads/custom_cascade_rcnn.py

Prompts

```
['build a CustomCascadeROIHeads model with multiple cascade stages for object detection using detectron2 config', 'review the CustomCascadeROIHeads forward method to understand cascade stage processing and loss computation', 'test the _match_and_label_boxes method to verify proposal matching with ground truth at each cascade stage', 'refactor the _ScaleGradient autograd function to scale gradients by a configurable factor during backpropagation', 'summarize the _init_box_head class method that builds box poolers, heads, predictors, and matchers from config', 'run fast_rcnn_inference to apply NMS and score thresholding on predicted boxes and scores across a batch of images', 'build a FastRCNNOutputLayers module with configurable classification and box regression heads for object detection', 'test fast_rcnn_inference_single_image to filter and apply NMS on boxes and scores for a single image', 'review the FastRCNNOutputLayers losses method to compute classification and box regression losses with optional federated loss', 'refactor the sigmoid_cross_entropy_loss method to customize federated loss class sampling and weighting', 'build ROIHeads from a detectron2 config and input shape using the ROI_HEADS_REGISTRY', 'select foreground proposals from a list of Instances by filtering out background and ignore labels', 'filter proposals to keep only those with at least one visible keypoint inside the box', 'review the Res5ROIHeads forward method that pools features through res5 and predicts boxes and masks', 'review the CustomStandardROIHeads forward method that independently processes box, mask, and keypoint heads with optional droploss']
```

Usage

```
{'build_CustomCascadeROIHeads': 'build a CustomCascadeROIHeads model with multiple cascade stages for object detection using detectron2 config', 'review_CustomCascadeROIHeads_forward': 'review the CustomCascadeROIHeads forward method to understand cascade stage processing and loss computation', 'test_match_and_label_boxes': 'test the _match_and_label_boxes method to verify proposal matching with ground truth at each cascade stage', 'refactor_ScaleGradient': 'refactor the _ScaleGradient autograd function to scale gradients by a configurable factor during backpropagation', 'summarize_init_box_head': 'summarize the _init_box_head class method that builds box poolers, heads, predictors, and matchers from config'}
```

## File: facebookresearch_cutler/cutler/modeling/roi_heads/fast_rcnn.py

Prompts

```
['build a CustomCascadeROIHeads model with multiple cascade stages for object detection using detectron2 config', 'review the CustomCascadeROIHeads forward method to understand cascade stage processing and loss computation', 'test the _match_and_label_boxes method to verify proposal matching with ground truth at each cascade stage', 'refactor the _ScaleGradient autograd function to scale gradients by a configurable factor during backpropagation', 'summarize the _init_box_head class method that builds box poolers, heads, predictors, and matchers from config', 'run fast_rcnn_inference to apply NMS and score thresholding on predicted boxes and scores across a batch of images', 'build a FastRCNNOutputLayers module with configurable classification and box regression heads for object detection', 'test fast_rcnn_inference_single_image to filter and apply NMS on boxes and scores for a single image', 'review the FastRCNNOutputLayers losses method to compute classification and box regression losses with optional federated loss', 'refactor the sigmoid_cross_entropy_loss method to customize federated loss class sampling and weighting', 'build ROIHeads from a detectron2 config and input shape using the ROI_HEADS_REGISTRY', 'select foreground proposals from a list of Instances by filtering out background and ignore labels', 'filter proposals to keep only those with at least one visible keypoint inside the box', 'review the Res5ROIHeads forward method that pools features through res5 and predicts boxes and masks', 'review the CustomStandardROIHeads forward method that independently processes box, mask, and keypoint heads with optional droploss']
```

Usage

```
{'run_fast_rcnn_inference': 'run fast_rcnn_inference to apply NMS and score thresholding on predicted boxes and scores across a batch of images', 'build_FastRCNNOutputLayers': 'build a FastRCNNOutputLayers module with configurable classification and box regression heads for object detection', 'test_fast_rcnn_inference_single_image': 'test fast_rcnn_inference_single_image to filter and apply NMS on boxes and scores for a single image', 'review_FastRCNNOutputLayers_losses': 'review the FastRCNNOutputLayers losses method to compute classification and box regression losses with optional federated loss', 'refactor_FastRCNNOutputLayers_sigmoid_cross_entropy_loss': 'refactor the sigmoid_cross_entropy_loss method to customize federated loss class sampling and weighting'}
```

## File: facebookresearch_cutler/cutler/modeling/roi_heads/roi_heads.py

Prompts

```
['build a CustomCascadeROIHeads model with multiple cascade stages for object detection using detectron2 config', 'review the CustomCascadeROIHeads forward method to understand cascade stage processing and loss computation', 'test the _match_and_label_boxes method to verify proposal matching with ground truth at each cascade stage', 'refactor the _ScaleGradient autograd function to scale gradients by a configurable factor during backpropagation', 'summarize the _init_box_head class method that builds box poolers, heads, predictors, and matchers from config', 'run fast_rcnn_inference to apply NMS and score thresholding on predicted boxes and scores across a batch of images', 'build a FastRCNNOutputLayers module with configurable classification and box regression heads for object detection', 'test fast_rcnn_inference_single_image to filter and apply NMS on boxes and scores for a single image', 'review the FastRCNNOutputLayers losses method to compute classification and box regression losses with optional federated loss', 'refactor the sigmoid_cross_entropy_loss method to customize federated loss class sampling and weighting', 'build ROIHeads from a detectron2 config and input shape using the ROI_HEADS_REGISTRY', 'select foreground proposals from a list of Instances by filtering out background and ignore labels', 'filter proposals to keep only those with at least one visible keypoint inside the box', 'review the Res5ROIHeads forward method that pools features through res5 and predicts boxes and masks', 'review the CustomStandardROIHeads forward method that independently processes box, mask, and keypoint heads with optional droploss']
```

Usage

```
{'build_roi_heads': 'build ROIHeads from a detectron2 config and input shape using the ROI_HEADS_REGISTRY', 'select_foreground_proposals': 'select foreground proposals from a list of Instances by filtering out background and ignore labels', 'select_proposals_with_visible_keypoints': 'filter proposals to keep only those with at least one visible keypoint inside the box', 'review_Res5ROIHeads_forward': 'review the Res5ROIHeads forward method that pools features through res5 and predicts boxes and masks', 'review_CustomStandardROIHeads_forward': 'review the CustomStandardROIHeads forward method that independently processes box, mask, and keypoint heads with optional droploss'}
```

