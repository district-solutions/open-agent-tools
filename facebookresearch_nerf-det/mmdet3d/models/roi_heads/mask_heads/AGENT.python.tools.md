# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/models/roi_heads/mask_heads/pointwise_semantic_head.py

Prompts

```
['build a PointwiseSemanticHead module for point-wise segmentation and part regression in PartA2', 'run the forward pass of PointwiseSemanticHead to get segmentation and part predictions from features', 'test get_targets_single to generate segmentation and part prediction targets for a single sample', 'review the get_targets method that generates batched segmentation and part prediction targets from voxels', 'refactor the loss method to compute segmentation and part prediction losses with focal and cross entropy', 'build a PrimitiveHead module for H3DNet 3D object detection with z, xy, or line primitive mode', 'run the forward pass of PrimitiveHead to generate vote points and primitive predictions from backbone features', 'compute the objectness, center, size, and semantic classification losses for the PrimitiveHead during training', 'generate ground truth targets including point masks, offsets, and primitive semantic labels for training', 'match 3D points to bounding box corner lines using distance thresholds for line primitive mode']
```

Usage

```
{'build_PointwiseSemanticHead': 'build a PointwiseSemanticHead module for point-wise segmentation and part regression in PartA2', 'run_forward_PointwiseSemanticHead': 'run the forward pass of PointwiseSemanticHead to get segmentation and part predictions from features', 'test_get_targets_single': 'test get_targets_single to generate segmentation and part prediction targets for a single sample', 'review_get_targets': 'review the get_targets method that generates batched segmentation and part prediction targets from voxels', 'refactor_loss_PointwiseSemanticHead': 'refactor the loss method to compute segmentation and part prediction losses with focal and cross entropy'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/roi_heads/mask_heads/primitive_head.py

Prompts

```
['build a PointwiseSemanticHead module for point-wise segmentation and part regression in PartA2', 'run the forward pass of PointwiseSemanticHead to get segmentation and part predictions from features', 'test get_targets_single to generate segmentation and part prediction targets for a single sample', 'review the get_targets method that generates batched segmentation and part prediction targets from voxels', 'refactor the loss method to compute segmentation and part prediction losses with focal and cross entropy', 'build a PrimitiveHead module for H3DNet 3D object detection with z, xy, or line primitive mode', 'run the forward pass of PrimitiveHead to generate vote points and primitive predictions from backbone features', 'compute the objectness, center, size, and semantic classification losses for the PrimitiveHead during training', 'generate ground truth targets including point masks, offsets, and primitive semantic labels for training', 'match 3D points to bounding box corner lines using distance thresholds for line primitive mode']
```

Usage

```
{'build_PrimitiveHead': 'build a PrimitiveHead module for H3DNet 3D object detection with z, xy, or line primitive mode', 'forward_PrimitiveHead': 'run the forward pass of PrimitiveHead to generate vote points and primitive predictions from backbone features', 'loss_PrimitiveHead': 'compute the objectness, center, size, and semantic classification losses for the PrimitiveHead during training', 'get_targets_PrimitiveHead': 'generate ground truth targets including point masks, offsets, and primitive semantic labels for training', 'match_point2line_PrimitiveHead': 'match 3D points to bounding box corner lines using distance thresholds for line primitive mode'}
```

