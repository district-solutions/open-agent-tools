# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/core/evaluation/kitti_utils/eval.py

Prompts

```
['run KITTI object detection evaluation on ground truth and detection annotations for bbox bev and 3d metrics', 'run COCO-style KITTI evaluation with varying IoU overlap ranges for car pedestrian and cyclist classes', 'run KITTI evaluation for specified classes and metrics returning mAP for bbox bev 3d and aos', 'review the numba-jitted image_box_overlap function that computes 2D bounding box IoU matrices between two box sets', 'review the d3_box_overlap function that computes 3D bounding box overlap using rotated IoU on GPU then depth intersection', 'build a python module to compute rotated box IoU on GPU using rotate_iou_gpu_eval', 'create a CUDA kernel to evaluate rotated IoU between two sets of 2D bounding boxes', 'test the device function devRotateIoUEval to compute IoU between two rotated boxes', 'refactor the quadrilateral_intersection function to compute intersection points of two rotated quadrilaterals', 'summarize the rbbox_to_corners function that converts rotated box parameters to corner coordinates']
```

Usage

```
{'run_kitti_eval': 'run KITTI object detection evaluation on ground truth and detection annotations for bbox bev and 3d metrics', 'run_kitti_eval_coco_style': 'run COCO-style KITTI evaluation with varying IoU overlap ranges for car pedestrian and cyclist classes', 'run_do_eval': 'run KITTI evaluation for specified classes and metrics returning mAP for bbox bev 3d and aos', 'review_image_box_overlap': 'review the numba-jitted image_box_overlap function that computes 2D bounding box IoU matrices between two box sets', 'review_d3_box_overlap': 'review the d3_box_overlap function that computes 3D bounding box overlap using rotated IoU on GPU then depth intersection'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/evaluation/kitti_utils/rotate_iou.py

Prompts

```
['run KITTI object detection evaluation on ground truth and detection annotations for bbox bev and 3d metrics', 'run COCO-style KITTI evaluation with varying IoU overlap ranges for car pedestrian and cyclist classes', 'run KITTI evaluation for specified classes and metrics returning mAP for bbox bev 3d and aos', 'review the numba-jitted image_box_overlap function that computes 2D bounding box IoU matrices between two box sets', 'review the d3_box_overlap function that computes 3D bounding box overlap using rotated IoU on GPU then depth intersection', 'build a python module to compute rotated box IoU on GPU using rotate_iou_gpu_eval', 'create a CUDA kernel to evaluate rotated IoU between two sets of 2D bounding boxes', 'test the device function devRotateIoUEval to compute IoU between two rotated boxes', 'refactor the quadrilateral_intersection function to compute intersection points of two rotated quadrilaterals', 'summarize the rbbox_to_corners function that converts rotated box parameters to corner coordinates']
```

Usage

```
{'build_rotate_iou_gpu_eval': 'build a python module to compute rotated box IoU on GPU using rotate_iou_gpu_eval', 'create_rotate_iou_kernel': 'create a CUDA kernel to evaluate rotated IoU between two sets of 2D bounding boxes', 'test_devRotateIoUEval': 'test the device function devRotateIoUEval to compute IoU between two rotated boxes', 'refactor_quadrilateral_intersection': 'refactor the quadrilateral_intersection function to compute intersection points of two rotated quadrilaterals', 'summarize_rbbox_to_corners': 'summarize the rbbox_to_corners function that converts rotated box parameters to corner coordinates'}
```

