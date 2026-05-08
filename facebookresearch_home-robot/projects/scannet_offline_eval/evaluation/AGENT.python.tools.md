# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/scannet_offline_eval/evaluation/obj_det.py

Prompts

```
['compute average precision and recall for 3D object detection across multiple scenes and IoU thresholds', 'evaluate 3D bounding box detections and print an ASCII table of AP and recall metrics per class', 'assign predicted 3D bounding boxes to ground truth boxes based on IoU thresholds and confidence scores', 'compute average precision and recall from true positive/false positive boolean matrices and detection scores', 'calculate average precision from recall and precision arrays using area or 11-point interpolation mode', 'evaluate 3D bounding box predictions against ground truth using IoU metrics for referring expression object selection', 'compute summary IoU statistics at multiple thresholds including proportion above threshold and mean IoU given threshold', 'find indices where a tensor matches given values using torch nonzero comparison', 'review the eval_obj_selection_bboxes function for 3D bounding box IoU evaluation metrics and threshold breakdown', 'refactor the get_stats_ious_at_thresh function to support additional IoU threshold categories or output formats']
```

Usage

```
{'compute_box_det_ap_recall': 'compute average precision and recall for 3D object detection across multiple scenes and IoU thresholds', 'eval_bboxes_and_print': 'evaluate 3D bounding box detections and print an ASCII table of AP and recall metrics per class', 'get_det_assignments_to_gt': 'assign predicted 3D bounding boxes to ground truth boxes based on IoU thresholds and confidence scores', 'compute_ap_recall': 'compute average precision and recall from true positive/false positive boolean matrices and detection scores', 'average_precision': 'calculate average precision from recall and precision arrays using area or 11-point interpolation mode'}
```

## File: facebookresearch_home-robot/projects/scannet_offline_eval/evaluation/refer_exp.py

Prompts

```
['compute average precision and recall for 3D object detection across multiple scenes and IoU thresholds', 'evaluate 3D bounding box detections and print an ASCII table of AP and recall metrics per class', 'assign predicted 3D bounding boxes to ground truth boxes based on IoU thresholds and confidence scores', 'compute average precision and recall from true positive/false positive boolean matrices and detection scores', 'calculate average precision from recall and precision arrays using area or 11-point interpolation mode', 'evaluate 3D bounding box predictions against ground truth using IoU metrics for referring expression object selection', 'compute summary IoU statistics at multiple thresholds including proportion above threshold and mean IoU given threshold', 'find indices where a tensor matches given values using torch nonzero comparison', 'review the eval_obj_selection_bboxes function for 3D bounding box IoU evaluation metrics and threshold breakdown', 'refactor the get_stats_ious_at_thresh function to support additional IoU threshold categories or output formats']
```

Usage

```
{'eval_obj_selection_bboxes': 'evaluate 3D bounding box predictions against ground truth using IoU metrics for referring expression object selection', 'get_stats_ious_at_thresh': 'compute summary IoU statistics at multiple thresholds including proportion above threshold and mean IoU given threshold', 'find_tensor_matches': 'find indices where a tensor matches given values using torch nonzero comparison', 'review_eval_obj_selection_bboxes': 'review the eval_obj_selection_bboxes function for 3D bounding box IoU evaluation metrics and threshold breakdown', 'refactor_get_stats_ious_at_thresh': 'refactor the get_stats_ious_at_thresh function to support additional IoU threshold categories or output formats'}
```

