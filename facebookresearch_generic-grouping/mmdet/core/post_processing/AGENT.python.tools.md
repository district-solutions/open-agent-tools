# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/core/post_processing/bbox_nms.py

Prompts

```
['run multiclass NMS on multi-class bounding boxes with score threshold and IoU config', 'run fast NMS from YOLACT on bounding boxes with mask coefficients and score threshold', 'test the multiclass_nms function with sample bboxes, scores, and NMS configuration parameters', 'test the fast_nms function with bboxes, scores, coefficients, and IoU threshold parameters', 'refactor the multiclass_nms function to add size check before feeding into batched_nms', 'merge augmented RPN proposals from multiscale and flip testing schemes using NMS and score sorting', 'merge augmented detection bounding boxes and scores by averaging across multiple test augmentations', 'merge augmented bounding box scores by computing the mean across multiple test augmentations', 'merge augmented mask predictions by reversing flips and averaging or weighting mask arrays', 'review the merge_augs module to understand how augmented proposals, bboxes, scores, and masks are merged']
```

Usage

```
{'run_multiclass_nms': 'run multiclass NMS on multi-class bounding boxes with score threshold and IoU config', 'run_fast_nms': 'run fast NMS from YOLACT on bounding boxes with mask coefficients and score threshold', 'test_multiclass_nms': 'test the multiclass_nms function with sample bboxes, scores, and NMS configuration parameters', 'test_fast_nms': 'test the fast_nms function with bboxes, scores, coefficients, and IoU threshold parameters', 'refactor_multiclass_nms': 'refactor the multiclass_nms function to add size check before feeding into batched_nms'}
```

## File: facebookresearch_generic-grouping/mmdet/core/post_processing/merge_augs.py

Prompts

```
['run multiclass NMS on multi-class bounding boxes with score threshold and IoU config', 'run fast NMS from YOLACT on bounding boxes with mask coefficients and score threshold', 'test the multiclass_nms function with sample bboxes, scores, and NMS configuration parameters', 'test the fast_nms function with bboxes, scores, coefficients, and IoU threshold parameters', 'refactor the multiclass_nms function to add size check before feeding into batched_nms', 'merge augmented RPN proposals from multiscale and flip testing schemes using NMS and score sorting', 'merge augmented detection bounding boxes and scores by averaging across multiple test augmentations', 'merge augmented bounding box scores by computing the mean across multiple test augmentations', 'merge augmented mask predictions by reversing flips and averaging or weighting mask arrays', 'review the merge_augs module to understand how augmented proposals, bboxes, scores, and masks are merged']
```

Usage

```
{'merge_aug_proposals': 'merge augmented RPN proposals from multiscale and flip testing schemes using NMS and score sorting', 'merge_aug_bboxes': 'merge augmented detection bounding boxes and scores by averaging across multiple test augmentations', 'merge_aug_scores': 'merge augmented bounding box scores by computing the mean across multiple test augmentations', 'merge_aug_masks': 'merge augmented mask predictions by reversing flips and averaging or weighting mask arrays', 'review_merge_augs': 'review the merge_augs module to understand how augmented proposals, bboxes, scores, and masks are merged'}
```

