# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/core/bbox/iou_calculators/builder.py

Prompts

```
['build an IoU calculator instance from a config dict using the IOU_CALCULATORS registry', 'register a custom IoU calculator class with the IOU_CALCULATORS registry for use in mmdet', 'build an IoU calculator from config with default arguments passed via default_args', 'review the IOU_CALCULATORS registry to see all registered IoU calculator types', 'summarize how build_iou_calculator delegates to mmcv build_from_cfg for config-driven instantiation', 'calculate the intersection over union (IoU) between two sets of 2D bounding boxes using bbox_overlaps', 'calculate the generalized IoU between two sets of 2D bounding boxes using bbox_overlaps with mode giou', 'calculate the intersection over foreground (IoF) between two sets of 2D bounding boxes using bbox_overlaps with mode iof', 'calculate overlaps between aligned pairs of bounding boxes using bbox_overlaps with is_aligned set to True', 'use the BboxOverlaps2D class to compute IoU between two sets of 2D bounding boxes via its callable interface']
```

Usage

```
{'build_iou_calculator_from_cfg': 'build an IoU calculator instance from a config dict using the IOU_CALCULATORS registry', 'register_iou_calculator': 'register a custom IoU calculator class with the IOU_CALCULATORS registry for use in mmdet', 'build_iou_calculator_with_defaults': 'build an IoU calculator from config with default arguments passed via default_args', 'review_iou_calculator_registry': 'review the IOU_CALCULATORS registry to see all registered IoU calculator types', 'summarize_build_iou_calculator': 'summarize how build_iou_calculator delegates to mmcv build_from_cfg for config-driven instantiation'}
```

## File: facebookresearch_generic-grouping/mmdet/core/bbox/iou_calculators/iou2d_calculator.py

Prompts

```
['build an IoU calculator instance from a config dict using the IOU_CALCULATORS registry', 'register a custom IoU calculator class with the IOU_CALCULATORS registry for use in mmdet', 'build an IoU calculator from config with default arguments passed via default_args', 'review the IOU_CALCULATORS registry to see all registered IoU calculator types', 'summarize how build_iou_calculator delegates to mmcv build_from_cfg for config-driven instantiation', 'calculate the intersection over union (IoU) between two sets of 2D bounding boxes using bbox_overlaps', 'calculate the generalized IoU between two sets of 2D bounding boxes using bbox_overlaps with mode giou', 'calculate the intersection over foreground (IoF) between two sets of 2D bounding boxes using bbox_overlaps with mode iof', 'calculate overlaps between aligned pairs of bounding boxes using bbox_overlaps with is_aligned set to True', 'use the BboxOverlaps2D class to compute IoU between two sets of 2D bounding boxes via its callable interface']
```

Usage

```
{'calculate_iou_between_bboxes': 'calculate the intersection over union (IoU) between two sets of 2D bounding boxes using bbox_overlaps', 'calculate_giou_between_bboxes': 'calculate the generalized IoU between two sets of 2D bounding boxes using bbox_overlaps with mode giou', 'calculate_iof_between_bboxes': 'calculate the intersection over foreground (IoF) between two sets of 2D bounding boxes using bbox_overlaps with mode iof', 'calculate_aligned_bbox_overlaps': 'calculate overlaps between aligned pairs of bounding boxes using bbox_overlaps with is_aligned set to True', 'use_bboxoverlaps2d_calculator': 'use the BboxOverlaps2D class to compute IoU between two sets of 2D bounding boxes via its callable interface'}
```

