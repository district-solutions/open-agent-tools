# Agent Python Tools

- repo: facebookresearch/phosa
- repo_uri: https://github.com/facebookresearch/phosa

## File: facebookresearch_phosa/phosa/bodymocap.py

Prompts

```
['create a BodyMocap human pose estimator predictor using the regressor checkpoint and SMPL model path', 'process mocap predictions with bounding boxes to compute global camera parameters and SMPL vertices', 'render an orthographic visualization of SMPL human mesh predictions overlaid on an input image', 'review the process_mocap_predictions function that rescales cameras to HMR convention and computes global camera parameters', 'summarize the visualize_orthographic function that renders blue SMPL meshes onto an image using an orthographic renderer', 'optimize human and object 3D poses using silhouette and interaction losses over multiple iterations', 'render frontal and top-down views of an optimized PHOSA model overlaid on the input image', 'create a PHOSA neural module with learnable object translations, rotations, and intrinsic scales for optimization', 'combine multiple vertex and face lists into unified faces and texture tensors for rendering', 'project 3D mesh vertices to the 2D image plane and compute bounding boxes per body part', 'build a PointRend segmentation predictor with a configurable minimum confidence threshold and image format', 'create occlusion-aware segmentation masks and annotations for a specific class from PointRend instances', 'test the get_pointrend_predictor function by creating a predictor and running inference on a sample image', 'refactor get_class_masks_from_instances to support multiple class IDs in a single pass', 'review get_class_masks_from_instances for the ignore mask computation and bounding box expansion logic', 'compute the 2D bounding box of 3D vertices projected onto the image plane in xywh format', 'compute the optimal 3D translation to align a mesh to a target bounding box using least squares', 'compute the occlusion-aware silhouette loss including mask, chamfer, and offscreen penalty terms for pose optimization', 'find the optimal 3D pose for a single object mesh given a target mask and bounding box via multi-start optimization', 'optimize 3D poses for all detected object instances in an image using silhouette matching against instance masks']
```

Usage

```
{'get_bodymocap_predictor': 'create a BodyMocap human pose estimator predictor using the regressor checkpoint and SMPL model path', 'process_mocap_predictions': 'process mocap predictions with bounding boxes to compute global camera parameters and SMPL vertices', 'visualize_orthographic': 'render an orthographic visualization of SMPL human mesh predictions overlaid on an input image', 'review_process_mocap_predictions': 'review the process_mocap_predictions function that rescales cameras to HMR convention and computes global camera parameters', 'summarize_visualize_orthographic': 'summarize the visualize_orthographic function that renders blue SMPL meshes onto an image using an orthographic renderer'}
```

## File: facebookresearch_phosa/phosa/global_opt.py

Prompts

```
['create a BodyMocap human pose estimator predictor using the regressor checkpoint and SMPL model path', 'process mocap predictions with bounding boxes to compute global camera parameters and SMPL vertices', 'render an orthographic visualization of SMPL human mesh predictions overlaid on an input image', 'review the process_mocap_predictions function that rescales cameras to HMR convention and computes global camera parameters', 'summarize the visualize_orthographic function that renders blue SMPL meshes onto an image using an orthographic renderer', 'optimize human and object 3D poses using silhouette and interaction losses over multiple iterations', 'render frontal and top-down views of an optimized PHOSA model overlaid on the input image', 'create a PHOSA neural module with learnable object translations, rotations, and intrinsic scales for optimization', 'combine multiple vertex and face lists into unified faces and texture tensors for rendering', 'project 3D mesh vertices to the 2D image plane and compute bounding boxes per body part', 'build a PointRend segmentation predictor with a configurable minimum confidence threshold and image format', 'create occlusion-aware segmentation masks and annotations for a specific class from PointRend instances', 'test the get_pointrend_predictor function by creating a predictor and running inference on a sample image', 'refactor get_class_masks_from_instances to support multiple class IDs in a single pass', 'review get_class_masks_from_instances for the ignore mask computation and bounding box expansion logic', 'compute the 2D bounding box of 3D vertices projected onto the image plane in xywh format', 'compute the optimal 3D translation to align a mesh to a target bounding box using least squares', 'compute the occlusion-aware silhouette loss including mask, chamfer, and offscreen penalty terms for pose optimization', 'find the optimal 3D pose for a single object mesh given a target mask and bounding box via multi-start optimization', 'optimize 3D poses for all detected object instances in an image using silhouette matching against instance masks']
```

Usage

```
{'optimize_human_object': 'optimize human and object 3D poses using silhouette and interaction losses over multiple iterations', 'visualize_human_object': 'render frontal and top-down views of an optimized PHOSA model overlaid on the input image', 'create_PHOSA_model': 'create a PHOSA neural module with learnable object translations, rotations, and intrinsic scales for optimization', 'get_faces_and_textures': 'combine multiple vertex and face lists into unified faces and texture tensors for rendering', 'project_bbox': 'project 3D mesh vertices to the 2D image plane and compute bounding boxes per body part'}
```

## File: facebookresearch_phosa/phosa/pointrend.py

Prompts

```
['create a BodyMocap human pose estimator predictor using the regressor checkpoint and SMPL model path', 'process mocap predictions with bounding boxes to compute global camera parameters and SMPL vertices', 'render an orthographic visualization of SMPL human mesh predictions overlaid on an input image', 'review the process_mocap_predictions function that rescales cameras to HMR convention and computes global camera parameters', 'summarize the visualize_orthographic function that renders blue SMPL meshes onto an image using an orthographic renderer', 'optimize human and object 3D poses using silhouette and interaction losses over multiple iterations', 'render frontal and top-down views of an optimized PHOSA model overlaid on the input image', 'create a PHOSA neural module with learnable object translations, rotations, and intrinsic scales for optimization', 'combine multiple vertex and face lists into unified faces and texture tensors for rendering', 'project 3D mesh vertices to the 2D image plane and compute bounding boxes per body part', 'build a PointRend segmentation predictor with a configurable minimum confidence threshold and image format', 'create occlusion-aware segmentation masks and annotations for a specific class from PointRend instances', 'test the get_pointrend_predictor function by creating a predictor and running inference on a sample image', 'refactor get_class_masks_from_instances to support multiple class IDs in a single pass', 'review get_class_masks_from_instances for the ignore mask computation and bounding box expansion logic', 'compute the 2D bounding box of 3D vertices projected onto the image plane in xywh format', 'compute the optimal 3D translation to align a mesh to a target bounding box using least squares', 'compute the occlusion-aware silhouette loss including mask, chamfer, and offscreen penalty terms for pose optimization', 'find the optimal 3D pose for a single object mesh given a target mask and bounding box via multi-start optimization', 'optimize 3D poses for all detected object instances in an image using silhouette matching against instance masks']
```

Usage

```
{'build_pointrend_predictor': 'build a PointRend segmentation predictor with a configurable minimum confidence threshold and image format', 'create_class_masks': 'create occlusion-aware segmentation masks and annotations for a specific class from PointRend instances', 'test_get_pointrend_predictor': 'test the get_pointrend_predictor function by creating a predictor and running inference on a sample image', 'refactor_get_class_masks_from_instances': 'refactor get_class_masks_from_instances to support multiple class IDs in a single pass', 'review_get_class_masks_from_instances': 'review get_class_masks_from_instances for the ignore mask computation and bounding box expansion logic'}
```

## File: facebookresearch_phosa/phosa/pose_optimization.py

Prompts

```
['create a BodyMocap human pose estimator predictor using the regressor checkpoint and SMPL model path', 'process mocap predictions with bounding boxes to compute global camera parameters and SMPL vertices', 'render an orthographic visualization of SMPL human mesh predictions overlaid on an input image', 'review the process_mocap_predictions function that rescales cameras to HMR convention and computes global camera parameters', 'summarize the visualize_orthographic function that renders blue SMPL meshes onto an image using an orthographic renderer', 'optimize human and object 3D poses using silhouette and interaction losses over multiple iterations', 'render frontal and top-down views of an optimized PHOSA model overlaid on the input image', 'create a PHOSA neural module with learnable object translations, rotations, and intrinsic scales for optimization', 'combine multiple vertex and face lists into unified faces and texture tensors for rendering', 'project 3D mesh vertices to the 2D image plane and compute bounding boxes per body part', 'build a PointRend segmentation predictor with a configurable minimum confidence threshold and image format', 'create occlusion-aware segmentation masks and annotations for a specific class from PointRend instances', 'test the get_pointrend_predictor function by creating a predictor and running inference on a sample image', 'refactor get_class_masks_from_instances to support multiple class IDs in a single pass', 'review get_class_masks_from_instances for the ignore mask computation and bounding box expansion logic', 'compute the 2D bounding box of 3D vertices projected onto the image plane in xywh format', 'compute the optimal 3D translation to align a mesh to a target bounding box using least squares', 'compute the occlusion-aware silhouette loss including mask, chamfer, and offscreen penalty terms for pose optimization', 'find the optimal 3D pose for a single object mesh given a target mask and bounding box via multi-start optimization', 'optimize 3D poses for all detected object instances in an image using silhouette matching against instance masks']
```

Usage

```
{'compute_bbox_proj': 'compute the 2D bounding box of 3D vertices projected onto the image plane in xywh format', 'compute_optimal_translation': 'compute the optimal 3D translation to align a mesh to a target bounding box using least squares', 'PoseOptimizer_forward': 'compute the occlusion-aware silhouette loss including mask, chamfer, and offscreen penalty terms for pose optimization', 'find_optimal_pose': 'find the optimal 3D pose for a single object mesh given a target mask and bounding box via multi-start optimization', 'find_optimal_poses': 'optimize 3D poses for all detected object instances in an image using silhouette matching against instance masks'}
```

