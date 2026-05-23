# Agent Python Tools

- repo: facebookresearch/perceptionmodels
- repo_uri: https://github.com/facebookresearch/perception_models

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/util/box_ops.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to x0, y0, x1, y1 format', 'convert bounding boxes from x0, y0, x1, y1 format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union areas', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from binary segmentation masks in N, H, W format', 'update the EMA shadow model parameters towards the current model using an exponential decay factor', 'update the EMA model with a custom decay value for finer control over parameter smoothing', 'freeze all model parameters by setting requires_grad to false for inference or evaluation', 'unfreeze all model parameters by setting requires_grad to true to resume training', 'review the EMA utility functions for updating shadow models and toggling gradient requirements', 'use init_distributed_mode to set up multi-GPU distributed training with NCCL backend', 'create a NestedTensor to batch images of different sizes with padding masks', 'use MetricLogger to track and log training metrics like loss and iteration time', 'create a SmoothedValue to track running median and global average of training metrics', 'use inverse_sigmoid to compute the numerically stable inverse sigmoid of a tensor', 'plot training and test fields like class_error and mAP from detection model log files', 'plot exponential weighted smoothed mAP results from multiple COCO evaluation log files', 'plot precision vs recall curves loaded from torch detection evaluation result files', 'plot detection scores vs recall curves and print mAP and F1 metrics', 'review the plot_logs function to verify it handles single Path and list of Path inputs']
```

Usage

```
{'convert_box_cxcywh_to_xyxy': 'convert bounding boxes from center x, center y, width, height format to x0, y0, x1, y1 format', 'convert_box_xyxy_to_cxcywh': 'convert bounding boxes from x0, y0, x1, y1 format to center x, center y, width, height format', 'compute_box_iou': 'compute the intersection over union between two sets of bounding boxes and return the union areas', 'compute_generalized_box_iou': 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute_masks_to_boxes': 'compute bounding boxes in xyxy format from binary segmentation masks in N, H, W format'}
```

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/util/ema.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to x0, y0, x1, y1 format', 'convert bounding boxes from x0, y0, x1, y1 format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union areas', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from binary segmentation masks in N, H, W format', 'update the EMA shadow model parameters towards the current model using an exponential decay factor', 'update the EMA model with a custom decay value for finer control over parameter smoothing', 'freeze all model parameters by setting requires_grad to false for inference or evaluation', 'unfreeze all model parameters by setting requires_grad to true to resume training', 'review the EMA utility functions for updating shadow models and toggling gradient requirements', 'use init_distributed_mode to set up multi-GPU distributed training with NCCL backend', 'create a NestedTensor to batch images of different sizes with padding masks', 'use MetricLogger to track and log training metrics like loss and iteration time', 'create a SmoothedValue to track running median and global average of training metrics', 'use inverse_sigmoid to compute the numerically stable inverse sigmoid of a tensor', 'plot training and test fields like class_error and mAP from detection model log files', 'plot exponential weighted smoothed mAP results from multiple COCO evaluation log files', 'plot precision vs recall curves loaded from torch detection evaluation result files', 'plot detection scores vs recall curves and print mAP and F1 metrics', 'review the plot_logs function to verify it handles single Path and list of Path inputs']
```

Usage

```
{'update_ema_step_shadow_model': 'update the EMA shadow model parameters towards the current model using an exponential decay factor', 'update_ema_with_custom_decay': 'update the EMA model with a custom decay value for finer control over parameter smoothing', 'requires_grad_freeze_model': 'freeze all model parameters by setting requires_grad to false for inference or evaluation', 'requires_grad_unfreeze_model': 'unfreeze all model parameters by setting requires_grad to true to resume training', 'review_ema_utility_functions': 'review the EMA utility functions for updating shadow models and toggling gradient requirements'}
```

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/util/misc.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to x0, y0, x1, y1 format', 'convert bounding boxes from x0, y0, x1, y1 format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union areas', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from binary segmentation masks in N, H, W format', 'update the EMA shadow model parameters towards the current model using an exponential decay factor', 'update the EMA model with a custom decay value for finer control over parameter smoothing', 'freeze all model parameters by setting requires_grad to false for inference or evaluation', 'unfreeze all model parameters by setting requires_grad to true to resume training', 'review the EMA utility functions for updating shadow models and toggling gradient requirements', 'use init_distributed_mode to set up multi-GPU distributed training with NCCL backend', 'create a NestedTensor to batch images of different sizes with padding masks', 'use MetricLogger to track and log training metrics like loss and iteration time', 'create a SmoothedValue to track running median and global average of training metrics', 'use inverse_sigmoid to compute the numerically stable inverse sigmoid of a tensor', 'plot training and test fields like class_error and mAP from detection model log files', 'plot exponential weighted smoothed mAP results from multiple COCO evaluation log files', 'plot precision vs recall curves loaded from torch detection evaluation result files', 'plot detection scores vs recall curves and print mAP and F1 metrics', 'review the plot_logs function to verify it handles single Path and list of Path inputs']
```

Usage

```
{'use_distributed_helpers': 'use init_distributed_mode to set up multi-GPU distributed training with NCCL backend', 'use_nested_tensor': 'create a NestedTensor to batch images of different sizes with padding masks', 'use_metric_logger': 'use MetricLogger to track and log training metrics like loss and iteration time', 'use_smoothed_value': 'create a SmoothedValue to track running median and global average of training metrics', 'use_inverse_sigmoid': 'use inverse_sigmoid to compute the numerically stable inverse sigmoid of a tensor'}
```

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/util/plot_utils.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to x0, y0, x1, y1 format', 'convert bounding boxes from x0, y0, x1, y1 format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union areas', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from binary segmentation masks in N, H, W format', 'update the EMA shadow model parameters towards the current model using an exponential decay factor', 'update the EMA model with a custom decay value for finer control over parameter smoothing', 'freeze all model parameters by setting requires_grad to false for inference or evaluation', 'unfreeze all model parameters by setting requires_grad to true to resume training', 'review the EMA utility functions for updating shadow models and toggling gradient requirements', 'use init_distributed_mode to set up multi-GPU distributed training with NCCL backend', 'create a NestedTensor to batch images of different sizes with padding masks', 'use MetricLogger to track and log training metrics like loss and iteration time', 'create a SmoothedValue to track running median and global average of training metrics', 'use inverse_sigmoid to compute the numerically stable inverse sigmoid of a tensor', 'plot training and test fields like class_error and mAP from detection model log files', 'plot exponential weighted smoothed mAP results from multiple COCO evaluation log files', 'plot precision vs recall curves loaded from torch detection evaluation result files', 'plot detection scores vs recall curves and print mAP and F1 metrics', 'review the plot_logs function to verify it handles single Path and list of Path inputs']
```

Usage

```
{'plot_training_logs': 'plot training and test fields like class_error and mAP from detection model log files', 'plot_mAP_from_logs': 'plot exponential weighted smoothed mAP results from multiple COCO evaluation log files', 'plot_precision_recall_curves': 'plot precision vs recall curves loaded from torch detection evaluation result files', 'plot_scores_recall_curves': 'plot detection scores vs recall curves and print mAP and F1 metrics', 'review_plot_logs_function': 'review the plot_logs function to verify it handles single Path and list of Path inputs'}
```

