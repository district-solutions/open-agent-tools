# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/core/bbox/box_np_ops.py

Prompts

```
['convert points from camera coordinates to lidar coordinates using r_rect and velo2cam transformation matrices', 'convert KITTI 3D box centers and dimensions to 8 corner points with optional rotation around a specified axis', 'calculate intersection over union between two sets of 2D axis-aligned bounding boxes using a JIT-compiled function', 'check which 3D points lie inside convex 3D polygons defined by their surface corner coordinates', 'create range-based 3D anchor boxes for a feature map with configurable sizes, rotations, and spatial extent', 'map 3D bounding boxes from testing scale back to original image scale with flip and scale adjustments', 'convert a list of 3D bounding boxes to region of interest format with batch indices prepended', 'convert 3D detection bboxes, scores, and labels into a CPU result dictionary for output', 'review the bbox3d_mapping_back function that clones and rescales 3D boxes after horizontal or vertical flips', 'review the bbox3d2roi function that concatenates batch indices with bounding box tensors into ROI format']
```

Usage

```
{'convert_camera_to_lidar': 'convert points from camera coordinates to lidar coordinates using r_rect and velo2cam transformation matrices', 'generate_3d_box_corners': 'convert KITTI 3D box centers and dimensions to 8 corner points with optional rotation around a specified axis', 'calculate_2d_box_iou': 'calculate intersection over union between two sets of 2D axis-aligned bounding boxes using a JIT-compiled function', 'check_points_in_3d_polygon': 'check which 3D points lie inside convex 3D polygons defined by their surface corner coordinates', 'create_3d_anchors': 'create range-based 3D anchor boxes for a feature map with configurable sizes, rotations, and spatial extent'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/bbox/transforms.py

Prompts

```
['convert points from camera coordinates to lidar coordinates using r_rect and velo2cam transformation matrices', 'convert KITTI 3D box centers and dimensions to 8 corner points with optional rotation around a specified axis', 'calculate intersection over union between two sets of 2D axis-aligned bounding boxes using a JIT-compiled function', 'check which 3D points lie inside convex 3D polygons defined by their surface corner coordinates', 'create range-based 3D anchor boxes for a feature map with configurable sizes, rotations, and spatial extent', 'map 3D bounding boxes from testing scale back to original image scale with flip and scale adjustments', 'convert a list of 3D bounding boxes to region of interest format with batch indices prepended', 'convert 3D detection bboxes, scores, and labels into a CPU result dictionary for output', 'review the bbox3d_mapping_back function that clones and rescales 3D boxes after horizontal or vertical flips', 'review the bbox3d2roi function that concatenates batch indices with bounding box tensors into ROI format']
```

Usage

```
{'map_3d_bboxes_back_to_original_scale': 'map 3D bounding boxes from testing scale back to original image scale with flip and scale adjustments', 'convert_3d_bboxes_to_roi_format': 'convert a list of 3D bounding boxes to region of interest format with batch indices prepended', 'convert_3d_detection_to_result_dict': 'convert 3D detection bboxes, scores, and labels into a CPU result dictionary for output', 'review_bbox3d_mapping_back': 'review the bbox3d_mapping_back function that clones and rescales 3D boxes after horizontal or vertical flips', 'review_bbox3d2roi': 'review the bbox3d2roi function that concatenates batch indices with bounding box tensors into ROI format'}
```

