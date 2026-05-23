# Agent Python Tools

- repo: facebookresearch/phosa
- repo_uri: https://github.com/facebookresearch/phosa

## File: facebookresearch_phosa/phosa/utils/bbox.py

Prompts

```
['crop an image to a bounding box using xywh format coordinates and return the cropped numpy array', 'convert a bounding box in xywh format to a square shape with optional expansion factor from center', 'convert bounding box coordinates from xyxy absolute format to xywh absolute format using detectron2 BoxMode', 'convert bounding box coordinates from xywh absolute format to xyxy absolute format using detectron2 BoxMode', 'compute the intersection over union between two bounding boxes supporting both numpy arrays and torch tensors', 'convert weak-perspective camera parameters from bounding box space to global image space', 'compute the 3x3 camera intrinsics matrix for a cropped region of interest box', 'compute 3D vertex transformation using a scaled orthographic camera model with rotation and translation', 'compute 3D vertex transformation using perspective camera with rotation and translation matrices', 'review the camera utility functions for 3D mesh transformation and coordinate conversion', 'convert a 6D rotation representation tensor to a 3x3 rotation matrix using Gram-Schmidt orthonormalization', 'convert a batch of 3x3 rotation matrices to 6D rotation representation by extracting first two columns', 'centroid-align mesh vertices and optionally flip Y axis to match image coordinate convention', 'compute the minimum Z-direction distance between two sets of 3D vertices', 'sample random 3x3 rotation matrices uniformly or with upright bias for data augmentation', 'create an OrthographicRenderer instance to render 3D mesh vertices and faces with orthographic projection', 'call the OrthographicRenderer with vertices, faces, and optional camera parameters to produce a rendered image', 'compute a scaled orthographic projection of 3D vertices using a weak-perspective camera with scale and translation', 'create a PerspectiveRenderer instance to render 3D mesh vertices and faces with perspective camera projection', 'call the PerspectiveRenderer with vertices, faces, translation, and rotation to produce a rendered image']
```

Usage

```
{'crop_image_with_bbox': 'crop an image to a bounding box using xywh format coordinates and return the cropped numpy array', 'make_bbox_square': 'convert a bounding box in xywh format to a square shape with optional expansion factor from center', 'bbox_xy_to_wh': 'convert bounding box coordinates from xyxy absolute format to xywh absolute format using detectron2 BoxMode', 'bbox_wh_to_xy': 'convert bounding box coordinates from xywh absolute format to xyxy absolute format using detectron2 BoxMode', 'compute_iou': 'compute the intersection over union between two bounding boxes supporting both numpy arrays and torch tensors'}
```

## File: facebookresearch_phosa/phosa/utils/camera.py

Prompts

```
['crop an image to a bounding box using xywh format coordinates and return the cropped numpy array', 'convert a bounding box in xywh format to a square shape with optional expansion factor from center', 'convert bounding box coordinates from xyxy absolute format to xywh absolute format using detectron2 BoxMode', 'convert bounding box coordinates from xywh absolute format to xyxy absolute format using detectron2 BoxMode', 'compute the intersection over union between two bounding boxes supporting both numpy arrays and torch tensors', 'convert weak-perspective camera parameters from bounding box space to global image space', 'compute the 3x3 camera intrinsics matrix for a cropped region of interest box', 'compute 3D vertex transformation using a scaled orthographic camera model with rotation and translation', 'compute 3D vertex transformation using perspective camera with rotation and translation matrices', 'review the camera utility functions for 3D mesh transformation and coordinate conversion', 'convert a 6D rotation representation tensor to a 3x3 rotation matrix using Gram-Schmidt orthonormalization', 'convert a batch of 3x3 rotation matrices to 6D rotation representation by extracting first two columns', 'centroid-align mesh vertices and optionally flip Y axis to match image coordinate convention', 'compute the minimum Z-direction distance between two sets of 3D vertices', 'sample random 3x3 rotation matrices uniformly or with upright bias for data augmentation', 'create an OrthographicRenderer instance to render 3D mesh vertices and faces with orthographic projection', 'call the OrthographicRenderer with vertices, faces, and optional camera parameters to produce a rendered image', 'compute a scaled orthographic projection of 3D vertices using a weak-perspective camera with scale and translation', 'create a PerspectiveRenderer instance to render 3D mesh vertices and faces with perspective camera projection', 'call the PerspectiveRenderer with vertices, faces, translation, and rotation to produce a rendered image']
```

Usage

```
{'convert_local_to_global_camera': 'convert weak-perspective camera parameters from bounding box space to global image space', 'compute_camera_intrinsics_roi': 'compute the 3x3 camera intrinsics matrix for a cropped region of interest box', 'compute_orthographic_transformation': 'compute 3D vertex transformation using a scaled orthographic camera model with rotation and translation', 'compute_perspective_transformation': 'compute 3D vertex transformation using perspective camera with rotation and translation matrices', 'review_camera_transformation_functions': 'review the camera utility functions for 3D mesh transformation and coordinate conversion'}
```

## File: facebookresearch_phosa/phosa/utils/geometry.py

Prompts

```
['crop an image to a bounding box using xywh format coordinates and return the cropped numpy array', 'convert a bounding box in xywh format to a square shape with optional expansion factor from center', 'convert bounding box coordinates from xyxy absolute format to xywh absolute format using detectron2 BoxMode', 'convert bounding box coordinates from xywh absolute format to xyxy absolute format using detectron2 BoxMode', 'compute the intersection over union between two bounding boxes supporting both numpy arrays and torch tensors', 'convert weak-perspective camera parameters from bounding box space to global image space', 'compute the 3x3 camera intrinsics matrix for a cropped region of interest box', 'compute 3D vertex transformation using a scaled orthographic camera model with rotation and translation', 'compute 3D vertex transformation using perspective camera with rotation and translation matrices', 'review the camera utility functions for 3D mesh transformation and coordinate conversion', 'convert a 6D rotation representation tensor to a 3x3 rotation matrix using Gram-Schmidt orthonormalization', 'convert a batch of 3x3 rotation matrices to 6D rotation representation by extracting first two columns', 'centroid-align mesh vertices and optionally flip Y axis to match image coordinate convention', 'compute the minimum Z-direction distance between two sets of 3D vertices', 'sample random 3x3 rotation matrices uniformly or with upright bias for data augmentation', 'create an OrthographicRenderer instance to render 3D mesh vertices and faces with orthographic projection', 'call the OrthographicRenderer with vertices, faces, and optional camera parameters to produce a rendered image', 'compute a scaled orthographic projection of 3D vertices using a weak-perspective camera with scale and translation', 'create a PerspectiveRenderer instance to render 3D mesh vertices and faces with perspective camera projection', 'call the PerspectiveRenderer with vertices, faces, translation, and rotation to produce a rendered image']
```

Usage

```
{'convert_rot6d_to_matrix': 'convert a 6D rotation representation tensor to a 3x3 rotation matrix using Gram-Schmidt orthonormalization', 'convert_matrix_to_rot6d': 'convert a batch of 3x3 rotation matrices to 6D rotation representation by extracting first two columns', 'center_mesh_vertices': 'centroid-align mesh vertices and optionally flip Y axis to match image coordinate convention', 'compute_z_distance': 'compute the minimum Z-direction distance between two sets of 3D vertices', 'sample_random_rotations': 'sample random 3x3 rotation matrices uniformly or with upright bias for data augmentation'}
```

## File: facebookresearch_phosa/phosa/utils/nmr_renderer.py

Prompts

```
['crop an image to a bounding box using xywh format coordinates and return the cropped numpy array', 'convert a bounding box in xywh format to a square shape with optional expansion factor from center', 'convert bounding box coordinates from xyxy absolute format to xywh absolute format using detectron2 BoxMode', 'convert bounding box coordinates from xywh absolute format to xyxy absolute format using detectron2 BoxMode', 'compute the intersection over union between two bounding boxes supporting both numpy arrays and torch tensors', 'convert weak-perspective camera parameters from bounding box space to global image space', 'compute the 3x3 camera intrinsics matrix for a cropped region of interest box', 'compute 3D vertex transformation using a scaled orthographic camera model with rotation and translation', 'compute 3D vertex transformation using perspective camera with rotation and translation matrices', 'review the camera utility functions for 3D mesh transformation and coordinate conversion', 'convert a 6D rotation representation tensor to a 3x3 rotation matrix using Gram-Schmidt orthonormalization', 'convert a batch of 3x3 rotation matrices to 6D rotation representation by extracting first two columns', 'centroid-align mesh vertices and optionally flip Y axis to match image coordinate convention', 'compute the minimum Z-direction distance between two sets of 3D vertices', 'sample random 3x3 rotation matrices uniformly or with upright bias for data augmentation', 'create an OrthographicRenderer instance to render 3D mesh vertices and faces with orthographic projection', 'call the OrthographicRenderer with vertices, faces, and optional camera parameters to produce a rendered image', 'compute a scaled orthographic projection of 3D vertices using a weak-perspective camera with scale and translation', 'create a PerspectiveRenderer instance to render 3D mesh vertices and faces with perspective camera projection', 'call the PerspectiveRenderer with vertices, faces, translation, and rotation to produce a rendered image']
```

Usage

```
{'create_orthographic_renderer': 'create an OrthographicRenderer instance to render 3D mesh vertices and faces with orthographic projection', 'call_orthographic_renderer': 'call the OrthographicRenderer with vertices, faces, and optional camera parameters to produce a rendered image', 'compute_orthographic_projection': 'compute a scaled orthographic projection of 3D vertices using a weak-perspective camera with scale and translation', 'create_perspective_renderer': 'create a PerspectiveRenderer instance to render 3D mesh vertices and faces with perspective camera projection', 'call_perspective_renderer': 'call the PerspectiveRenderer with vertices, faces, translation, and rotation to produce a rendered image'}
```

