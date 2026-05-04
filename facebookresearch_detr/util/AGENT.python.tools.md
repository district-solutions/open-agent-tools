# Agent Python Tools

- repo: facebookresearch/detr
- repo_uri: https://github.com/facebookresearch/detr.git

## File: facebookresearch_detr/util/box_ops.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to xyxy format', 'convert bounding boxes from xyxy format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union area', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from binary segmentation masks in N, H, W format', 'create a SmoothedValue instance to track running median and global average of training loss values', 'build a MetricLogger to log and print training metrics every N iterations with ETA', 'run all_gather to collect arbitrary picklable data from all GPU ranks in a distributed job', 'test the collate_fn and NestedTensor to pad a list of images into a batched tensor with masks', 'review the init_distributed_mode and is_main_process helpers for multi-GPU training setup', 'plot training and test results from DETR log files using exponential weighted smoothing', 'plot specific fields like class_error and mAP from multiple DETR training log directories', 'plot precision recall and scores recall curves from COCO evaluation torch files', 'compare multiple DETR training runs side by side with color coded log plots', 'visualize mAP precision recall and f1 scores from COCO evaluation checkpoint files']
```

Usage

```
{'convert_cxcywh_to_xyxy': 'convert bounding boxes from center x, center y, width, height format to xyxy format', 'convert_xyxy_to_cxcywh': 'convert bounding boxes from xyxy format to center x, center y, width, height format', 'compute_box_iou': 'compute the intersection over union between two sets of bounding boxes and return the union area', 'compute_generalized_box_iou': 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute_boxes_from_masks': 'compute bounding boxes in xyxy format from binary segmentation masks in N, H, W format'}
```

## File: facebookresearch_detr/util/misc.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to xyxy format', 'convert bounding boxes from xyxy format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union area', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from binary segmentation masks in N, H, W format', 'create a SmoothedValue instance to track running median and global average of training loss values', 'build a MetricLogger to log and print training metrics every N iterations with ETA', 'run all_gather to collect arbitrary picklable data from all GPU ranks in a distributed job', 'test the collate_fn and NestedTensor to pad a list of images into a batched tensor with masks', 'review the init_distributed_mode and is_main_process helpers for multi-GPU training setup', 'plot training and test results from DETR log files using exponential weighted smoothing', 'plot specific fields like class_error and mAP from multiple DETR training log directories', 'plot precision recall and scores recall curves from COCO evaluation torch files', 'compare multiple DETR training runs side by side with color coded log plots', 'visualize mAP precision recall and f1 scores from COCO evaluation checkpoint files']
```

Usage

```
{'create_smoothedvalue_tracker': 'create a SmoothedValue instance to track running median and global average of training loss values', 'build_metriclogger_for_training': 'build a MetricLogger to log and print training metrics every N iterations with ETA', 'run_all_gather_distributed': 'run all_gather to collect arbitrary picklable data from all GPU ranks in a distributed job', 'test_nested_tensor_collation': 'test the collate_fn and NestedTensor to pad a list of images into a batched tensor with masks', 'review_distributed_setup_helpers': 'review the init_distributed_mode and is_main_process helpers for multi-GPU training setup'}
```

## File: facebookresearch_detr/util/plot_utils.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to xyxy format', 'convert bounding boxes from xyxy format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union area', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from binary segmentation masks in N, H, W format', 'create a SmoothedValue instance to track running median and global average of training loss values', 'build a MetricLogger to log and print training metrics every N iterations with ETA', 'run all_gather to collect arbitrary picklable data from all GPU ranks in a distributed job', 'test the collate_fn and NestedTensor to pad a list of images into a batched tensor with masks', 'review the init_distributed_mode and is_main_process helpers for multi-GPU training setup', 'plot training and test results from DETR log files using exponential weighted smoothing', 'plot specific fields like class_error and mAP from multiple DETR training log directories', 'plot precision recall and scores recall curves from COCO evaluation torch files', 'compare multiple DETR training runs side by side with color coded log plots', 'visualize mAP precision recall and f1 scores from COCO evaluation checkpoint files']
```

Usage

```
{'plot_training_logs': 'plot training and test results from DETR log files using exponential weighted smoothing', 'plot_logs_with_custom_fields': 'plot specific fields like class_error and mAP from multiple DETR training log directories', 'plot_precision_recall_curves': 'plot precision recall and scores recall curves from COCO evaluation torch files', 'compare_multiple_training_runs': 'compare multiple DETR training runs side by side with color coded log plots', 'visualize_coco_eval_metrics': 'visualize mAP precision recall and f1 scores from COCO evaluation checkpoint files'}
```

