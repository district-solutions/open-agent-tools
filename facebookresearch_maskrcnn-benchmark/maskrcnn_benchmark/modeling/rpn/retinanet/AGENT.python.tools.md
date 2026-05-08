# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/rpn/retinanet/inference.py

Prompts

```
['create a RetinaNetPostProcessor instance with pre_nms_thresh, nms_thresh, and num_classes parameters', 'run forward_for_single_feature_map to process anchors, box_cls, and box_regression tensors into detections', 'run select_over_all_levels to apply per-class NMS and limit detections across all FPN levels', 'build a RetinaNetPostProcessor from a config object using make_retinanet_postprocessor factory function', 'review the RetinaNetPostProcessor class and its NMS thresholding and box decoding logic', 'build a RetinaNetLossComputation instance with a matcher, box coder, and focal loss function', 'run RetinaNetLossComputation on anchors, box classifications, box regression, and targets to get losses', 'create a RetinaNet loss evaluator from a config object and box coder using make_retinanet_loss_evaluator', 'review the generate_retinanet_labels function that extracts labels from matched targets BoxList', 'refactor the RetinaNet regression loss computation using smooth L1 loss with configurable beta', 'build a RetinaNetModule from config and input channels using build_retinanet', 'create a RetinaNetHead with classification and regression towers for object detection', 'test the RetinaNetModule forward pass with images, features, and optional targets', 'review the RetinaNetHead forward method that returns logits and bbox regression per feature level', 'summarize how the RetinaNetModule computes classification and regression losses during training']
```

Usage

```
{'create_retinanet_postprocessor': 'create a RetinaNetPostProcessor instance with pre_nms_thresh, nms_thresh, and num_classes parameters', 'run_forward_single_feature_map': 'run forward_for_single_feature_map to process anchors, box_cls, and box_regression tensors into detections', 'run_select_over_all_levels': 'run select_over_all_levels to apply per-class NMS and limit detections across all FPN levels', 'build_retinanet_postprocessor_from_config': 'build a RetinaNetPostProcessor from a config object using make_retinanet_postprocessor factory function', 'review_retinanet_inference_pipeline': 'review the RetinaNetPostProcessor class and its NMS thresholding and box decoding logic'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/rpn/retinanet/loss.py

Prompts

```
['create a RetinaNetPostProcessor instance with pre_nms_thresh, nms_thresh, and num_classes parameters', 'run forward_for_single_feature_map to process anchors, box_cls, and box_regression tensors into detections', 'run select_over_all_levels to apply per-class NMS and limit detections across all FPN levels', 'build a RetinaNetPostProcessor from a config object using make_retinanet_postprocessor factory function', 'review the RetinaNetPostProcessor class and its NMS thresholding and box decoding logic', 'build a RetinaNetLossComputation instance with a matcher, box coder, and focal loss function', 'run RetinaNetLossComputation on anchors, box classifications, box regression, and targets to get losses', 'create a RetinaNet loss evaluator from a config object and box coder using make_retinanet_loss_evaluator', 'review the generate_retinanet_labels function that extracts labels from matched targets BoxList', 'refactor the RetinaNet regression loss computation using smooth L1 loss with configurable beta', 'build a RetinaNetModule from config and input channels using build_retinanet', 'create a RetinaNetHead with classification and regression towers for object detection', 'test the RetinaNetModule forward pass with images, features, and optional targets', 'review the RetinaNetHead forward method that returns logits and bbox regression per feature level', 'summarize how the RetinaNetModule computes classification and regression losses during training']
```

Usage

```
{'build_retinanet_loss_computation': 'build a RetinaNetLossComputation instance with a matcher, box coder, and focal loss function', 'run_retinanet_loss_call': 'run RetinaNetLossComputation on anchors, box classifications, box regression, and targets to get losses', 'create_retinanet_loss_evaluator': 'create a RetinaNet loss evaluator from a config object and box coder using make_retinanet_loss_evaluator', 'review_retinanet_labels_generation': 'review the generate_retinanet_labels function that extracts labels from matched targets BoxList', 'refactor_retinanet_regression_loss': 'refactor the RetinaNet regression loss computation using smooth L1 loss with configurable beta'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/rpn/retinanet/retinanet.py

Prompts

```
['create a RetinaNetPostProcessor instance with pre_nms_thresh, nms_thresh, and num_classes parameters', 'run forward_for_single_feature_map to process anchors, box_cls, and box_regression tensors into detections', 'run select_over_all_levels to apply per-class NMS and limit detections across all FPN levels', 'build a RetinaNetPostProcessor from a config object using make_retinanet_postprocessor factory function', 'review the RetinaNetPostProcessor class and its NMS thresholding and box decoding logic', 'build a RetinaNetLossComputation instance with a matcher, box coder, and focal loss function', 'run RetinaNetLossComputation on anchors, box classifications, box regression, and targets to get losses', 'create a RetinaNet loss evaluator from a config object and box coder using make_retinanet_loss_evaluator', 'review the generate_retinanet_labels function that extracts labels from matched targets BoxList', 'refactor the RetinaNet regression loss computation using smooth L1 loss with configurable beta', 'build a RetinaNetModule from config and input channels using build_retinanet', 'create a RetinaNetHead with classification and regression towers for object detection', 'test the RetinaNetModule forward pass with images, features, and optional targets', 'review the RetinaNetHead forward method that returns logits and bbox regression per feature level', 'summarize how the RetinaNetModule computes classification and regression losses during training']
```

Usage

```
{'build_retinanet_module': 'build a RetinaNetModule from config and input channels using build_retinanet', 'create_retinanet_head': 'create a RetinaNetHead with classification and regression towers for object detection', 'test_retinanet_forward': 'test the RetinaNetModule forward pass with images, features, and optional targets', 'review_retinanet_head_forward': 'review the RetinaNetHead forward method that returns logits and bbox regression per feature level', 'summarize_retinanet_loss_evaluator': 'summarize how the RetinaNetModule computes classification and regression losses during training'}
```

