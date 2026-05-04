# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/core/bbox/builder.py

Prompts

```
['build a bounding box assigner from a config dict using the BBOX_ASSIGNERS registry', 'build a bounding box sampler from a config dict using the BBOX_SAMPLERS registry', 'build a bounding box coder from a config dict using the BBOX_CODERS registry', 'review the BBOX_ASSIGNERS registry to list all registered bounding box assigner types', 'review the BBOX_SAMPLERS registry to list all registered bounding box sampler types', 'create random bounding boxes as a PyTorch tensor with a given count and scale', 'generate test bounding box tensors in x1,y1,x2,y2 format for object detection', 'ensure a numpy RandomState object from an integer seed or None', 'review the random_boxes function that generates bounding box tensors with configurable scale', 'test the ensure_rng function that normalizes seed inputs to a RandomState', 'flip bounding boxes horizontally, vertically, or diagonally given an image shape tensor', 'map bounding boxes from original image scale to testing scale with optional flip', 'convert a list of bounding box tensors to ROI format with batch indices', 'decode distance predictions from anchor points into bounding box coordinates', 'convert bounding box coordinates between xyxy and cxcywh formats']
```

Usage

```
{'build_assigner': 'build a bounding box assigner from a config dict using the BBOX_ASSIGNERS registry', 'build_sampler': 'build a bounding box sampler from a config dict using the BBOX_SAMPLERS registry', 'build_bbox_coder': 'build a bounding box coder from a config dict using the BBOX_CODERS registry', 'review_BBOX_ASSIGNERS': 'review the BBOX_ASSIGNERS registry to list all registered bounding box assigner types', 'review_BBOX_SAMPLERS': 'review the BBOX_SAMPLERS registry to list all registered bounding box sampler types'}
```

## File: facebookresearch_generic-grouping/mmdet/core/bbox/demodata.py

Prompts

```
['build a bounding box assigner from a config dict using the BBOX_ASSIGNERS registry', 'build a bounding box sampler from a config dict using the BBOX_SAMPLERS registry', 'build a bounding box coder from a config dict using the BBOX_CODERS registry', 'review the BBOX_ASSIGNERS registry to list all registered bounding box assigner types', 'review the BBOX_SAMPLERS registry to list all registered bounding box sampler types', 'create random bounding boxes as a PyTorch tensor with a given count and scale', 'generate test bounding box tensors in x1,y1,x2,y2 format for object detection', 'ensure a numpy RandomState object from an integer seed or None', 'review the random_boxes function that generates bounding box tensors with configurable scale', 'test the ensure_rng function that normalizes seed inputs to a RandomState', 'flip bounding boxes horizontally, vertically, or diagonally given an image shape tensor', 'map bounding boxes from original image scale to testing scale with optional flip', 'convert a list of bounding box tensors to ROI format with batch indices', 'decode distance predictions from anchor points into bounding box coordinates', 'convert bounding box coordinates between xyxy and cxcywh formats']
```

Usage

```
{'create_random_bounding_boxes': 'create random bounding boxes as a PyTorch tensor with a given count and scale', 'generate_test_boxes_for_detection': 'generate test bounding box tensors in x1,y1,x2,y2 format for object detection', 'ensure_numpy_random_state': 'ensure a numpy RandomState object from an integer seed or None', 'review_random_boxes_function': 'review the random_boxes function that generates bounding box tensors with configurable scale', 'test_ensure_rng_function': 'test the ensure_rng function that normalizes seed inputs to a RandomState'}
```

## File: facebookresearch_generic-grouping/mmdet/core/bbox/transforms.py

Prompts

```
['build a bounding box assigner from a config dict using the BBOX_ASSIGNERS registry', 'build a bounding box sampler from a config dict using the BBOX_SAMPLERS registry', 'build a bounding box coder from a config dict using the BBOX_CODERS registry', 'review the BBOX_ASSIGNERS registry to list all registered bounding box assigner types', 'review the BBOX_SAMPLERS registry to list all registered bounding box sampler types', 'create random bounding boxes as a PyTorch tensor with a given count and scale', 'generate test bounding box tensors in x1,y1,x2,y2 format for object detection', 'ensure a numpy RandomState object from an integer seed or None', 'review the random_boxes function that generates bounding box tensors with configurable scale', 'test the ensure_rng function that normalizes seed inputs to a RandomState', 'flip bounding boxes horizontally, vertically, or diagonally given an image shape tensor', 'map bounding boxes from original image scale to testing scale with optional flip', 'convert a list of bounding box tensors to ROI format with batch indices', 'decode distance predictions from anchor points into bounding box coordinates', 'convert bounding box coordinates between xyxy and cxcywh formats']
```

Usage

```
{'flip_bboxes': 'flip bounding boxes horizontally, vertically, or diagonally given an image shape tensor', 'map_bboxes_to_test_scale': 'map bounding boxes from original image scale to testing scale with optional flip', 'convert_bboxes_to_roi': 'convert a list of bounding box tensors to ROI format with batch indices', 'decode_distance_to_bbox': 'decode distance predictions from anchor points into bounding box coordinates', 'convert_bbox_coordinate_formats': 'convert bounding box coordinates between xyxy and cxcywh formats'}
```

