# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/third_party/Deformable-DETR/util/box_ops.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to x0, y0, x1, y1 format', 'convert bounding boxes from x0, y0, x1, y1 format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union areas', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from a set of 2D binary masks with shape N, H, W', 'create a SmoothedValue instance to track median and global average of training loss over a sliding window', 'build a MetricLogger to log training metrics like loss and iteration time every N steps', 'run all_gather to collect arbitrary picklable data from all distributed processes into a single list', 'test reduce_dict to average or sum dictionary values across all distributed training processes', 'init distributed mode by calling init_distributed_mode to set up multi-GPU training with NCCL backend', 'plot training and test results for specified fields from Deformable DETR training log files', 'plot mAP results from COCO evaluation logs with exponential weighted smoothing across multiple experiments', 'plot loss_bbox_unscaled and class_error from training logs with solid training and dashed test lines', 'plot precision recall and scores recall curves from COCO evaluation data files for multiple experiments', 'plot precision recall curves using experiment ID naming scheme from torch saved evaluation data files']
```

Usage

```
{'convert_box_cxcywh_to_xyxy': 'convert bounding boxes from center x, center y, width, height format to x0, y0, x1, y1 format', 'convert_box_xyxy_to_cxcywh': 'convert bounding boxes from x0, y0, x1, y1 format to center x, center y, width, height format', 'compute_box_iou': 'compute the intersection over union between two sets of bounding boxes and return the union areas', 'compute_generalized_box_iou': 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute_masks_to_boxes': 'compute bounding boxes in xyxy format from a set of 2D binary masks with shape N, H, W'}
```

## File: facebookresearch_detic/third_party/Deformable-DETR/util/misc.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to x0, y0, x1, y1 format', 'convert bounding boxes from x0, y0, x1, y1 format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union areas', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from a set of 2D binary masks with shape N, H, W', 'create a SmoothedValue instance to track median and global average of training loss over a sliding window', 'build a MetricLogger to log training metrics like loss and iteration time every N steps', 'run all_gather to collect arbitrary picklable data from all distributed processes into a single list', 'test reduce_dict to average or sum dictionary values across all distributed training processes', 'init distributed mode by calling init_distributed_mode to set up multi-GPU training with NCCL backend', 'plot training and test results for specified fields from Deformable DETR training log files', 'plot mAP results from COCO evaluation logs with exponential weighted smoothing across multiple experiments', 'plot loss_bbox_unscaled and class_error from training logs with solid training and dashed test lines', 'plot precision recall and scores recall curves from COCO evaluation data files for multiple experiments', 'plot precision recall curves using experiment ID naming scheme from torch saved evaluation data files']
```

Usage

```
{'create_smoothedvalue_tracker': 'create a SmoothedValue instance to track median and global average of training loss over a sliding window', 'build_metriclogger_for_training': 'build a MetricLogger to log training metrics like loss and iteration time every N steps', 'run_all_gather_distributed': 'run all_gather to collect arbitrary picklable data from all distributed processes into a single list', 'test_reduce_dict_across_ranks': 'test reduce_dict to average or sum dictionary values across all distributed training processes', 'init_distributed_mode_setup': 'init distributed mode by calling init_distributed_mode to set up multi-GPU training with NCCL backend'}
```

## File: facebookresearch_detic/third_party/Deformable-DETR/util/plot_utils.py

Prompts

```
['convert bounding boxes from center x, center y, width, height format to x0, y0, x1, y1 format', 'convert bounding boxes from x0, y0, x1, y1 format to center x, center y, width, height format', 'compute the intersection over union between two sets of bounding boxes and return the union areas', 'compute the generalized intersection over union between two sets of bounding boxes in xyxy format', 'compute bounding boxes in xyxy format from a set of 2D binary masks with shape N, H, W', 'create a SmoothedValue instance to track median and global average of training loss over a sliding window', 'build a MetricLogger to log training metrics like loss and iteration time every N steps', 'run all_gather to collect arbitrary picklable data from all distributed processes into a single list', 'test reduce_dict to average or sum dictionary values across all distributed training processes', 'init distributed mode by calling init_distributed_mode to set up multi-GPU training with NCCL backend', 'plot training and test results for specified fields from Deformable DETR training log files', 'plot mAP results from COCO evaluation logs with exponential weighted smoothing across multiple experiments', 'plot loss_bbox_unscaled and class_error from training logs with solid training and dashed test lines', 'plot precision recall and scores recall curves from COCO evaluation data files for multiple experiments', 'plot precision recall curves using experiment ID naming scheme from torch saved evaluation data files']
```

Usage

```
{'plot_training_logs': 'plot training and test results for specified fields from Deformable DETR training log files', 'plot_logs_mAP': 'plot mAP results from COCO evaluation logs with exponential weighted smoothing across multiple experiments', 'plot_logs_loss': 'plot loss_bbox_unscaled and class_error from training logs with solid training and dashed test lines', 'plot_precision_recall_curves': 'plot precision recall and scores recall curves from COCO evaluation data files for multiple experiments', 'plot_precision_recall_exp_id': 'plot precision recall curves using experiment ID naming scheme from torch saved evaluation data files'}
```

