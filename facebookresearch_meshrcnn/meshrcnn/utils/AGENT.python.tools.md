# Agent Python Tools

- repo: facebookresearch/meshrcnn
- repo_uri: https://github.com/facebookresearch/meshrcnn

## File: facebookresearch_meshrcnn/meshrcnn/utils/VOCap.py

Prompts

```
['compute average precision from detection scores and labels using the VOC evaluation protocol', 'calculate VOC-style average precision from recall and precision curves using interpolation', 'test the compute_ap function with sample PyTorch tensors for scores and binary labels', 'test the xVOCap function with recall and precision tensors to verify AP calculation', 'refactor compute_ap to support batched input tensors for parallel AP computation', 'compute chamfer distance and evaluation metrics between predicted and ground truth 3D meshes', 'compute precision, recall, and F1 scores at various distance thresholds for mesh comparison', 'compute normal consistency and absolute normal consistency between predicted and ground truth meshes', 'scale predicted and ground truth meshes using a uniform scalar or bounding box normalization', 'sample uniform points and normals from mesh surfaces or use vertex positions as samples', 'build a ProjectiveTransform with a default identity 3x3 matrix for batched coordinate transformations', 'apply a forward projective transformation to batched 2D coordinates using the ProjectiveTransform callable', 'apply the inverse projective transformation to batched 2D coordinates using the inverse method', 'estimate a projective transformation matrix from source to destination coordinates using SVD method', 'center and normalize batched 2D points for improved numerical stability in transformation estimation', 'transform 3D vertices using a rotation matrix and translation vector', 'read a voxel grid from a MATLAB file and return centered normalized vertices', 'convert 2D bounding boxes with depth ranges into 3D cuboid coordinates', 'estimate projective transforms for xz and yz planes from a 3D cuboid tensor', 'review the transform_verts function to understand rotation and translation logic', 'draw text with a green background label on a BGR image at a given position', 'draw green bounding boxes on a BGR image from a Boxes object or numpy array', 'overlay a colored segmentation mask with optional contours on a BGR image', 'print a tabulated histogram of per-class instance counts and box, mask, and mesh AP scores', 'visualize detection predictions by saving overlayed mask images and OBJ mesh files to disk']
```

Usage

```
{'compute_ap': 'compute average precision from detection scores and labels using the VOC evaluation protocol', 'xVOCap': 'calculate VOC-style average precision from recall and precision curves using interpolation', 'test_compute_ap': 'test the compute_ap function with sample PyTorch tensors for scores and binary labels', 'test_xVOCap': 'test the xVOCap function with recall and precision tensors to verify AP calculation', 'refactor_compute_ap': 'refactor compute_ap to support batched input tensors for parallel AP computation'}
```

## File: facebookresearch_meshrcnn/meshrcnn/utils/metrics.py

Prompts

```
['compute average precision from detection scores and labels using the VOC evaluation protocol', 'calculate VOC-style average precision from recall and precision curves using interpolation', 'test the compute_ap function with sample PyTorch tensors for scores and binary labels', 'test the xVOCap function with recall and precision tensors to verify AP calculation', 'refactor compute_ap to support batched input tensors for parallel AP computation', 'compute chamfer distance and evaluation metrics between predicted and ground truth 3D meshes', 'compute precision, recall, and F1 scores at various distance thresholds for mesh comparison', 'compute normal consistency and absolute normal consistency between predicted and ground truth meshes', 'scale predicted and ground truth meshes using a uniform scalar or bounding box normalization', 'sample uniform points and normals from mesh surfaces or use vertex positions as samples', 'build a ProjectiveTransform with a default identity 3x3 matrix for batched coordinate transformations', 'apply a forward projective transformation to batched 2D coordinates using the ProjectiveTransform callable', 'apply the inverse projective transformation to batched 2D coordinates using the inverse method', 'estimate a projective transformation matrix from source to destination coordinates using SVD method', 'center and normalize batched 2D points for improved numerical stability in transformation estimation', 'transform 3D vertices using a rotation matrix and translation vector', 'read a voxel grid from a MATLAB file and return centered normalized vertices', 'convert 2D bounding boxes with depth ranges into 3D cuboid coordinates', 'estimate projective transforms for xz and yz planes from a 3D cuboid tensor', 'review the transform_verts function to understand rotation and translation logic', 'draw text with a green background label on a BGR image at a given position', 'draw green bounding boxes on a BGR image from a Boxes object or numpy array', 'overlay a colored segmentation mask with optional contours on a BGR image', 'print a tabulated histogram of per-class instance counts and box, mask, and mesh AP scores', 'visualize detection predictions by saving overlayed mask images and OBJ mesh files to disk']
```

Usage

```
{'compare_meshes_chamfer': 'compute chamfer distance and evaluation metrics between predicted and ground truth 3D meshes', 'compare_meshes_precision_recall': 'compute precision, recall, and F1 scores at various distance thresholds for mesh comparison', 'compare_meshes_normal_consistency': 'compute normal consistency and absolute normal consistency between predicted and ground truth meshes', 'scale_meshes_for_comparison': 'scale predicted and ground truth meshes using a uniform scalar or bounding box normalization', 'sample_meshes_surface_points': 'sample uniform points and normals from mesh surfaces or use vertex positions as samples'}
```

## File: facebookresearch_meshrcnn/meshrcnn/utils/projtransform.py

Prompts

```
['compute average precision from detection scores and labels using the VOC evaluation protocol', 'calculate VOC-style average precision from recall and precision curves using interpolation', 'test the compute_ap function with sample PyTorch tensors for scores and binary labels', 'test the xVOCap function with recall and precision tensors to verify AP calculation', 'refactor compute_ap to support batched input tensors for parallel AP computation', 'compute chamfer distance and evaluation metrics between predicted and ground truth 3D meshes', 'compute precision, recall, and F1 scores at various distance thresholds for mesh comparison', 'compute normal consistency and absolute normal consistency between predicted and ground truth meshes', 'scale predicted and ground truth meshes using a uniform scalar or bounding box normalization', 'sample uniform points and normals from mesh surfaces or use vertex positions as samples', 'build a ProjectiveTransform with a default identity 3x3 matrix for batched coordinate transformations', 'apply a forward projective transformation to batched 2D coordinates using the ProjectiveTransform callable', 'apply the inverse projective transformation to batched 2D coordinates using the inverse method', 'estimate a projective transformation matrix from source to destination coordinates using SVD method', 'center and normalize batched 2D points for improved numerical stability in transformation estimation', 'transform 3D vertices using a rotation matrix and translation vector', 'read a voxel grid from a MATLAB file and return centered normalized vertices', 'convert 2D bounding boxes with depth ranges into 3D cuboid coordinates', 'estimate projective transforms for xz and yz planes from a 3D cuboid tensor', 'review the transform_verts function to understand rotation and translation logic', 'draw text with a green background label on a BGR image at a given position', 'draw green bounding boxes on a BGR image from a Boxes object or numpy array', 'overlay a colored segmentation mask with optional contours on a BGR image', 'print a tabulated histogram of per-class instance counts and box, mask, and mesh AP scores', 'visualize detection predictions by saving overlayed mask images and OBJ mesh files to disk']
```

Usage

```
{'build_projective_transform_identity': 'build a ProjectiveTransform with a default identity 3x3 matrix for batched coordinate transformations', 'apply_forward_transform': 'apply a forward projective transformation to batched 2D coordinates using the ProjectiveTransform callable', 'apply_inverse_transform': 'apply the inverse projective transformation to batched 2D coordinates using the inverse method', 'estimate_transform_matrix_svd': 'estimate a projective transformation matrix from source to destination coordinates using SVD method', 'center_and_normalize_points': 'center and normalize batched 2D points for improved numerical stability in transformation estimation'}
```

## File: facebookresearch_meshrcnn/meshrcnn/utils/shape.py

Prompts

```
['compute average precision from detection scores and labels using the VOC evaluation protocol', 'calculate VOC-style average precision from recall and precision curves using interpolation', 'test the compute_ap function with sample PyTorch tensors for scores and binary labels', 'test the xVOCap function with recall and precision tensors to verify AP calculation', 'refactor compute_ap to support batched input tensors for parallel AP computation', 'compute chamfer distance and evaluation metrics between predicted and ground truth 3D meshes', 'compute precision, recall, and F1 scores at various distance thresholds for mesh comparison', 'compute normal consistency and absolute normal consistency between predicted and ground truth meshes', 'scale predicted and ground truth meshes using a uniform scalar or bounding box normalization', 'sample uniform points and normals from mesh surfaces or use vertex positions as samples', 'build a ProjectiveTransform with a default identity 3x3 matrix for batched coordinate transformations', 'apply a forward projective transformation to batched 2D coordinates using the ProjectiveTransform callable', 'apply the inverse projective transformation to batched 2D coordinates using the inverse method', 'estimate a projective transformation matrix from source to destination coordinates using SVD method', 'center and normalize batched 2D points for improved numerical stability in transformation estimation', 'transform 3D vertices using a rotation matrix and translation vector', 'read a voxel grid from a MATLAB file and return centered normalized vertices', 'convert 2D bounding boxes with depth ranges into 3D cuboid coordinates', 'estimate projective transforms for xz and yz planes from a 3D cuboid tensor', 'review the transform_verts function to understand rotation and translation logic', 'draw text with a green background label on a BGR image at a given position', 'draw green bounding boxes on a BGR image from a Boxes object or numpy array', 'overlay a colored segmentation mask with optional contours on a BGR image', 'print a tabulated histogram of per-class instance counts and box, mask, and mesh AP scores', 'visualize detection predictions by saving overlayed mask images and OBJ mesh files to disk']
```

Usage

```
{'transform_verts_with_rotation_and_translation': 'transform 3D vertices using a rotation matrix and translation vector', 'read_voxel_from_matlab_file': 'read a voxel grid from a MATLAB file and return centered normalized vertices', 'convert_2d_boxes_to_3d_cuboids': 'convert 2D bounding boxes with depth ranges into 3D cuboid coordinates', 'estimate_projective_transforms_from_cuboid': 'estimate projective transforms for xz and yz planes from a 3D cuboid tensor', 'review_transform_verts_function': 'review the transform_verts function to understand rotation and translation logic'}
```

## File: facebookresearch_meshrcnn/meshrcnn/utils/vis.py

Prompts

```
['compute average precision from detection scores and labels using the VOC evaluation protocol', 'calculate VOC-style average precision from recall and precision curves using interpolation', 'test the compute_ap function with sample PyTorch tensors for scores and binary labels', 'test the xVOCap function with recall and precision tensors to verify AP calculation', 'refactor compute_ap to support batched input tensors for parallel AP computation', 'compute chamfer distance and evaluation metrics between predicted and ground truth 3D meshes', 'compute precision, recall, and F1 scores at various distance thresholds for mesh comparison', 'compute normal consistency and absolute normal consistency between predicted and ground truth meshes', 'scale predicted and ground truth meshes using a uniform scalar or bounding box normalization', 'sample uniform points and normals from mesh surfaces or use vertex positions as samples', 'build a ProjectiveTransform with a default identity 3x3 matrix for batched coordinate transformations', 'apply a forward projective transformation to batched 2D coordinates using the ProjectiveTransform callable', 'apply the inverse projective transformation to batched 2D coordinates using the inverse method', 'estimate a projective transformation matrix from source to destination coordinates using SVD method', 'center and normalize batched 2D points for improved numerical stability in transformation estimation', 'transform 3D vertices using a rotation matrix and translation vector', 'read a voxel grid from a MATLAB file and return centered normalized vertices', 'convert 2D bounding boxes with depth ranges into 3D cuboid coordinates', 'estimate projective transforms for xz and yz planes from a 3D cuboid tensor', 'review the transform_verts function to understand rotation and translation logic', 'draw text with a green background label on a BGR image at a given position', 'draw green bounding boxes on a BGR image from a Boxes object or numpy array', 'overlay a colored segmentation mask with optional contours on a BGR image', 'print a tabulated histogram of per-class instance counts and box, mask, and mesh AP scores', 'visualize detection predictions by saving overlayed mask images and OBJ mesh files to disk']
```

Usage

```
{'draw_text_on_image': 'draw text with a green background label on a BGR image at a given position', 'draw_boxes_on_image': 'draw green bounding boxes on a BGR image from a Boxes object or numpy array', 'draw_mask_on_image': 'overlay a colored segmentation mask with optional contours on a BGR image', 'print_class_histogram': 'print a tabulated histogram of per-class instance counts and box, mask, and mesh AP scores', 'visualize_predictions': 'visualize detection predictions by saving overlayed mask images and OBJ mesh files to disk'}
```

