# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/ops/rotated_iou/box_intersection_2d.py

Prompts

```
['calculate the intersection area of two batches of 2D oriented rectangles using corner coordinates', 'find intersection points between edges of two sets of 2D rectangles and return a validity mask', 'check if corners of one set of boxes lie inside another set of boxes in both directions', 'build the combined vertices of an intersection area from box corners and edge intersection points', 'calculate the area of an intersection polygon from sorted vertex indices and vertex coordinates', 'create an IoU3DLoss instance to compute 3D IoU loss between predicted and target oriented bounding boxes', 'create a GIoU3DLoss instance to compute generalized 3D IoU loss for 3D object detection training', 'use the iou_3d_loss function to calculate weighted 3D IoU loss between prediction and target tensors', 'use the giou_3d_loss function to calculate weighted generalized 3D IoU loss between prediction and target tensors', 'customize an IoU3DMixin subclass with a custom loss function and configurable reduction mode and loss weight', 'build a python module to find the smallest bounding box enclosing two rotated rectangles using smallest_bounding_box', 'generate the 24 candidate hull polygon edges and remaining points using generate_table for rotated IoU', 'gather hull edge candidates and rest points from 8 corner coordinates using gather_lines_points', 'calculate the maximal perpendicular distance between points and a line using point_line_distance_range', 'calculate the maximal parallel projection distance between points and a line using point_line_projection_range', 'calculate IoU between two sets of oriented 2D bounding boxes with shape (B, N, 5)', 'calculate distance IoU loss for oriented 2D bounding boxes using smallest enclosing box', 'calculate generalized IoU loss for oriented 2D bounding boxes with configurable enclosing type', 'calculate 3D IoU for rotated bounding boxes that are only rotated around the Z axis', 'calculate 3D generalized IoU loss for rotated bounding boxes around the Z axis']
```

Usage

```
{'calculate_oriented_box_intersection_2d': 'calculate the intersection area of two batches of 2D oriented rectangles using corner coordinates', 'find_box_intersection_points': 'find intersection points between edges of two sets of 2D rectangles and return a validity mask', 'check_box_containment': 'check if corners of one set of boxes lie inside another set of boxes in both directions', 'build_intersection_vertices': 'build the combined vertices of an intersection area from box corners and edge intersection points', 'calculate_polygon_area': 'calculate the area of an intersection polygon from sorted vertex indices and vertex coordinates'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/rotated_iou/iou3d_loss.py

Prompts

```
['calculate the intersection area of two batches of 2D oriented rectangles using corner coordinates', 'find intersection points between edges of two sets of 2D rectangles and return a validity mask', 'check if corners of one set of boxes lie inside another set of boxes in both directions', 'build the combined vertices of an intersection area from box corners and edge intersection points', 'calculate the area of an intersection polygon from sorted vertex indices and vertex coordinates', 'create an IoU3DLoss instance to compute 3D IoU loss between predicted and target oriented bounding boxes', 'create a GIoU3DLoss instance to compute generalized 3D IoU loss for 3D object detection training', 'use the iou_3d_loss function to calculate weighted 3D IoU loss between prediction and target tensors', 'use the giou_3d_loss function to calculate weighted generalized 3D IoU loss between prediction and target tensors', 'customize an IoU3DMixin subclass with a custom loss function and configurable reduction mode and loss weight', 'build a python module to find the smallest bounding box enclosing two rotated rectangles using smallest_bounding_box', 'generate the 24 candidate hull polygon edges and remaining points using generate_table for rotated IoU', 'gather hull edge candidates and rest points from 8 corner coordinates using gather_lines_points', 'calculate the maximal perpendicular distance between points and a line using point_line_distance_range', 'calculate the maximal parallel projection distance between points and a line using point_line_projection_range', 'calculate IoU between two sets of oriented 2D bounding boxes with shape (B, N, 5)', 'calculate distance IoU loss for oriented 2D bounding boxes using smallest enclosing box', 'calculate generalized IoU loss for oriented 2D bounding boxes with configurable enclosing type', 'calculate 3D IoU for rotated bounding boxes that are only rotated around the Z axis', 'calculate 3D generalized IoU loss for rotated bounding boxes around the Z axis']
```

Usage

```
{'create_iou3dloss_for_3d_box_regression': 'create an IoU3DLoss instance to compute 3D IoU loss between predicted and target oriented bounding boxes', 'create_giou3dloss_for_generalized_3d_iou': 'create a GIoU3DLoss instance to compute generalized 3D IoU loss for 3D object detection training', 'use_iou_3d_loss_function': 'use the iou_3d_loss function to calculate weighted 3D IoU loss between prediction and target tensors', 'use_giou_3d_loss_function': 'use the giou_3d_loss function to calculate weighted generalized 3D IoU loss between prediction and target tensors', 'customize_iou3dmixin_with_reduction': 'customize an IoU3DMixin subclass with a custom loss function and configurable reduction mode and loss weight'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/rotated_iou/min_enclosing_box.py

Prompts

```
['calculate the intersection area of two batches of 2D oriented rectangles using corner coordinates', 'find intersection points between edges of two sets of 2D rectangles and return a validity mask', 'check if corners of one set of boxes lie inside another set of boxes in both directions', 'build the combined vertices of an intersection area from box corners and edge intersection points', 'calculate the area of an intersection polygon from sorted vertex indices and vertex coordinates', 'create an IoU3DLoss instance to compute 3D IoU loss between predicted and target oriented bounding boxes', 'create a GIoU3DLoss instance to compute generalized 3D IoU loss for 3D object detection training', 'use the iou_3d_loss function to calculate weighted 3D IoU loss between prediction and target tensors', 'use the giou_3d_loss function to calculate weighted generalized 3D IoU loss between prediction and target tensors', 'customize an IoU3DMixin subclass with a custom loss function and configurable reduction mode and loss weight', 'build a python module to find the smallest bounding box enclosing two rotated rectangles using smallest_bounding_box', 'generate the 24 candidate hull polygon edges and remaining points using generate_table for rotated IoU', 'gather hull edge candidates and rest points from 8 corner coordinates using gather_lines_points', 'calculate the maximal perpendicular distance between points and a line using point_line_distance_range', 'calculate the maximal parallel projection distance between points and a line using point_line_projection_range', 'calculate IoU between two sets of oriented 2D bounding boxes with shape (B, N, 5)', 'calculate distance IoU loss for oriented 2D bounding boxes using smallest enclosing box', 'calculate generalized IoU loss for oriented 2D bounding boxes with configurable enclosing type', 'calculate 3D IoU for rotated bounding boxes that are only rotated around the Z axis', 'calculate 3D generalized IoU loss for rotated bounding boxes around the Z axis']
```

Usage

```
{'build_smallest_bounding_box': 'build a python module to find the smallest bounding box enclosing two rotated rectangles using smallest_bounding_box', 'generate_table_candidates': 'generate the 24 candidate hull polygon edges and remaining points using generate_table for rotated IoU', 'gather_lines_points': 'gather hull edge candidates and rest points from 8 corner coordinates using gather_lines_points', 'calculate_point_line_distance': 'calculate the maximal perpendicular distance between points and a line using point_line_distance_range', 'calculate_point_line_projection': 'calculate the maximal parallel projection distance between points and a line using point_line_projection_range'}
```

## File: facebookresearch_nerf-det/mmdet3d/ops/rotated_iou/oriented_iou_loss.py

Prompts

```
['calculate the intersection area of two batches of 2D oriented rectangles using corner coordinates', 'find intersection points between edges of two sets of 2D rectangles and return a validity mask', 'check if corners of one set of boxes lie inside another set of boxes in both directions', 'build the combined vertices of an intersection area from box corners and edge intersection points', 'calculate the area of an intersection polygon from sorted vertex indices and vertex coordinates', 'create an IoU3DLoss instance to compute 3D IoU loss between predicted and target oriented bounding boxes', 'create a GIoU3DLoss instance to compute generalized 3D IoU loss for 3D object detection training', 'use the iou_3d_loss function to calculate weighted 3D IoU loss between prediction and target tensors', 'use the giou_3d_loss function to calculate weighted generalized 3D IoU loss between prediction and target tensors', 'customize an IoU3DMixin subclass with a custom loss function and configurable reduction mode and loss weight', 'build a python module to find the smallest bounding box enclosing two rotated rectangles using smallest_bounding_box', 'generate the 24 candidate hull polygon edges and remaining points using generate_table for rotated IoU', 'gather hull edge candidates and rest points from 8 corner coordinates using gather_lines_points', 'calculate the maximal perpendicular distance between points and a line using point_line_distance_range', 'calculate the maximal parallel projection distance between points and a line using point_line_projection_range', 'calculate IoU between two sets of oriented 2D bounding boxes with shape (B, N, 5)', 'calculate distance IoU loss for oriented 2D bounding boxes using smallest enclosing box', 'calculate generalized IoU loss for oriented 2D bounding boxes with configurable enclosing type', 'calculate 3D IoU for rotated bounding boxes that are only rotated around the Z axis', 'calculate 3D generalized IoU loss for rotated bounding boxes around the Z axis']
```

Usage

```
{'cal_iou_oriented_boxes': 'calculate IoU between two sets of oriented 2D bounding boxes with shape (B, N, 5)', 'cal_diou_oriented_boxes': 'calculate distance IoU loss for oriented 2D bounding boxes using smallest enclosing box', 'cal_giou_oriented_boxes': 'calculate generalized IoU loss for oriented 2D bounding boxes with configurable enclosing type', 'cal_iou_3d_rotated_boxes': 'calculate 3D IoU for rotated bounding boxes that are only rotated around the Z axis', 'cal_giou_3d_rotated_boxes': 'calculate 3D generalized IoU loss for rotated bounding boxes around the Z axis'}
```

