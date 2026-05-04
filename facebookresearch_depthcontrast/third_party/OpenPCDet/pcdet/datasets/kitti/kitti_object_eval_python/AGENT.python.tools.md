# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/datasets/kitti/kitti_object_eval_python/eval.py

Prompts

```
['run the KITTI official object detection evaluation on ground truth and detection annotations for car, pedestrian, cyclist classes', 'run COCO-style mAP evaluation with configurable IoU overlap ranges on KITTI ground truth and detection annotations', 'calculate IoU overlaps between ground truth and detection bounding boxes using image, BEV, or 3D metric', 'compute 2D image bounding box overlap IoU matrix between two sets of axis-aligned boxes using numba JIT', 'compute 3D bounding box overlap IoU using rotated BEV IoU and depth intersection with numba JIT acceleration', 'build a python module that loads KITTI image info with labels, calibration matrices, and velodyne paths for a dataset directory', 'create a function that reads all KITTI label annotation files from a folder and returns parsed annotation dictionaries', 'build a python module that filters KITTI annotations by object class, difficulty level, and dontcare IoU threshold', 'create a function that computes pairwise intersection-over-union scores between two sets of 2D bounding boxes', 'build a python module that formats a detection result dictionary into a KITTI evaluation result line string', 'build a python module that computes rotated bounding box IoU on GPU using rotate_iou_gpu_eval', 'create a function that evaluates IoU between two sets of rotated 3D boxes on GPU', 'test the rotate_iou_gpu_eval function with sample numpy arrays of rotated boxes', 'refactor the devRotateIoUEval CUDA device function to support additional IoU criteria', 'review the rbbox_to_corners function that converts rotated box parameters to corner coordinates']
```

Usage

```
{'run_kitti_official_eval': 'run the KITTI official object detection evaluation on ground truth and detection annotations for car, pedestrian, cyclist classes', 'run_coco_style_eval': 'run COCO-style mAP evaluation with configurable IoU overlap ranges on KITTI ground truth and detection annotations', 'calculate_iou_partly': 'calculate IoU overlaps between ground truth and detection bounding boxes using image, BEV, or 3D metric', 'compute_image_box_overlap': 'compute 2D image bounding box overlap IoU matrix between two sets of axis-aligned boxes using numba JIT', 'compute_d3_box_overlap': 'compute 3D bounding box overlap IoU using rotated BEV IoU and depth intersection with numba JIT acceleration'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/datasets/kitti/kitti_object_eval_python/kitti_common.py

Prompts

```
['run the KITTI official object detection evaluation on ground truth and detection annotations for car, pedestrian, cyclist classes', 'run COCO-style mAP evaluation with configurable IoU overlap ranges on KITTI ground truth and detection annotations', 'calculate IoU overlaps between ground truth and detection bounding boxes using image, BEV, or 3D metric', 'compute 2D image bounding box overlap IoU matrix between two sets of axis-aligned boxes using numba JIT', 'compute 3D bounding box overlap IoU using rotated BEV IoU and depth intersection with numba JIT acceleration', 'build a python module that loads KITTI image info with labels, calibration matrices, and velodyne paths for a dataset directory', 'create a function that reads all KITTI label annotation files from a folder and returns parsed annotation dictionaries', 'build a python module that filters KITTI annotations by object class, difficulty level, and dontcare IoU threshold', 'create a function that computes pairwise intersection-over-union scores between two sets of 2D bounding boxes', 'build a python module that formats a detection result dictionary into a KITTI evaluation result line string', 'build a python module that computes rotated bounding box IoU on GPU using rotate_iou_gpu_eval', 'create a function that evaluates IoU between two sets of rotated 3D boxes on GPU', 'test the rotate_iou_gpu_eval function with sample numpy arrays of rotated boxes', 'refactor the devRotateIoUEval CUDA device function to support additional IoU criteria', 'review the rbbox_to_corners function that converts rotated box parameters to corner coordinates']
```

Usage

```
{'get_kitti_image_info': 'build a python module that loads KITTI image info with labels, calibration matrices, and velodyne paths for a dataset directory', 'get_label_annos': 'create a function that reads all KITTI label annotation files from a folder and returns parsed annotation dictionaries', 'filter_kitti_anno': 'build a python module that filters KITTI annotations by object class, difficulty level, and dontcare IoU threshold', 'iou': 'create a function that computes pairwise intersection-over-union scores between two sets of 2D bounding boxes', 'kitti_result_line': 'build a python module that formats a detection result dictionary into a KITTI evaluation result line string'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/datasets/kitti/kitti_object_eval_python/rotate_iou.py

Prompts

```
['run the KITTI official object detection evaluation on ground truth and detection annotations for car, pedestrian, cyclist classes', 'run COCO-style mAP evaluation with configurable IoU overlap ranges on KITTI ground truth and detection annotations', 'calculate IoU overlaps between ground truth and detection bounding boxes using image, BEV, or 3D metric', 'compute 2D image bounding box overlap IoU matrix between two sets of axis-aligned boxes using numba JIT', 'compute 3D bounding box overlap IoU using rotated BEV IoU and depth intersection with numba JIT acceleration', 'build a python module that loads KITTI image info with labels, calibration matrices, and velodyne paths for a dataset directory', 'create a function that reads all KITTI label annotation files from a folder and returns parsed annotation dictionaries', 'build a python module that filters KITTI annotations by object class, difficulty level, and dontcare IoU threshold', 'create a function that computes pairwise intersection-over-union scores between two sets of 2D bounding boxes', 'build a python module that formats a detection result dictionary into a KITTI evaluation result line string', 'build a python module that computes rotated bounding box IoU on GPU using rotate_iou_gpu_eval', 'create a function that evaluates IoU between two sets of rotated 3D boxes on GPU', 'test the rotate_iou_gpu_eval function with sample numpy arrays of rotated boxes', 'refactor the devRotateIoUEval CUDA device function to support additional IoU criteria', 'review the rbbox_to_corners function that converts rotated box parameters to corner coordinates']
```

Usage

```
{'build_gpu_rotated_iou': 'build a python module that computes rotated bounding box IoU on GPU using rotate_iou_gpu_eval', 'create_iou_evaluation': 'create a function that evaluates IoU between two sets of rotated 3D boxes on GPU', 'test_rotate_iou_gpu_eval': 'test the rotate_iou_gpu_eval function with sample numpy arrays of rotated boxes', 'refactor_devRotateIoUEval': 'refactor the devRotateIoUEval CUDA device function to support additional IoU criteria', 'review_rbbox_to_corners': 'review the rbbox_to_corners function that converts rotated box parameters to corner coordinates'}
```

