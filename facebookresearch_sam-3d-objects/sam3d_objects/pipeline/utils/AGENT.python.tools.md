# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/pipeline/utils/pointmap.py

Prompts

```
['infer camera intrinsics from a point map tensor and return points, intrinsics, depth, and mask', 'infer camera intrinsics from a point map using an optional mask tensor to filter valid regions', 'infer camera intrinsics from a point map with a specified horizontal field of view in degrees', 'infer camera intrinsics and recompute points using depth and intrinsics with force_projection enabled', 'infer camera intrinsics and apply mask to output points and depth, setting masked values to infinity']
```

Usage

```
{'infer_intrinsics_from_pointmap_basic': 'infer camera intrinsics from a point map tensor and return points, intrinsics, depth, and mask', 'infer_intrinsics_with_mask': 'infer camera intrinsics from a point map using an optional mask tensor to filter valid regions', 'infer_intrinsics_with_fov': 'infer camera intrinsics from a point map with a specified horizontal field of view in degrees', 'infer_intrinsics_force_projection': 'infer camera intrinsics and recompute points using depth and intrinsics with force_projection enabled', 'infer_intrinsics_apply_mask': 'infer camera intrinsics and apply mask to output points and depth, setting masked values to infinity'}
```

