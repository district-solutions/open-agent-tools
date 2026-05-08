# Agent Python Tools

- repo: facebookresearch/interwild
- repo_uri: https://github.com/facebookresearch/interwild

## File: facebookresearch_interwild/common/utils/dir.py

Prompts

```
['create a folder at the given path only if it does not already exist', 'add a directory to sys.path at the front if it is not already present', 'review the make_folder function that creates directories using os.makedirs when they do not exist', 'review the add_pypath function that prepends a path to sys.path to enable imports', 'refactor make_folder to use os.makedirs with exist_ok instead of a manual existence check', 'create a function that applies random scale, rotation, color, and flip augmentations to an image using a bounding box', 'build a function that extracts and extends a bounding box from valid 2D joint coordinates with configurable extension ratio', 'transform 3D joint coordinates with flip augmentation, rotation, and affine transformation for heatmap output formatting', 'generate MANO hand mesh coordinates and joint positions from pose parameters with camera extrinsic and flip support', 'compute IoU between two sets of bounding boxes supporting both xyxy and xywh coordinate formats', 'convert camera coordinates to pixel coordinates using focal length and principal point', 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'map joint coordinates from one skeleton naming convention to another dataset skeleton', 'sample image feature map values at joint positions using grid sampling', 'compute soft argmax coordinates from a 2D heatmap tensor using softmax weighted positions', 'draw colored skeleton lines and keypoints on an image using opencv', 'draw colored keypoints as circles on an image with configurable alpha blending', 'plot a 3D skeleton with colored lines and scatter points using matplotlib', 'save mesh vertices and faces to a Wavefront OBJ file', 'render a 3D mesh with a perspective camera and return images and depthmaps']
```

Usage

```
{'create_folder_if_missing': 'create a folder at the given path only if it does not already exist', 'add_path_to_sys_path': 'add a directory to sys.path at the front if it is not already present', 'review_make_folder': 'review the make_folder function that creates directories using os.makedirs when they do not exist', 'review_add_pypath': 'review the add_pypath function that prepends a path to sys.path to enable imports', 'refactor_make_folder': 'refactor make_folder to use os.makedirs with exist_ok instead of a manual existence check'}
```

## File: facebookresearch_interwild/common/utils/preprocessing.py

Prompts

```
['create a folder at the given path only if it does not already exist', 'add a directory to sys.path at the front if it is not already present', 'review the make_folder function that creates directories using os.makedirs when they do not exist', 'review the add_pypath function that prepends a path to sys.path to enable imports', 'refactor make_folder to use os.makedirs with exist_ok instead of a manual existence check', 'create a function that applies random scale, rotation, color, and flip augmentations to an image using a bounding box', 'build a function that extracts and extends a bounding box from valid 2D joint coordinates with configurable extension ratio', 'transform 3D joint coordinates with flip augmentation, rotation, and affine transformation for heatmap output formatting', 'generate MANO hand mesh coordinates and joint positions from pose parameters with camera extrinsic and flip support', 'compute IoU between two sets of bounding boxes supporting both xyxy and xywh coordinate formats', 'convert camera coordinates to pixel coordinates using focal length and principal point', 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'map joint coordinates from one skeleton naming convention to another dataset skeleton', 'sample image feature map values at joint positions using grid sampling', 'compute soft argmax coordinates from a 2D heatmap tensor using softmax weighted positions', 'draw colored skeleton lines and keypoints on an image using opencv', 'draw colored keypoints as circles on an image with configurable alpha blending', 'plot a 3D skeleton with colored lines and scatter points using matplotlib', 'save mesh vertices and faces to a Wavefront OBJ file', 'render a 3D mesh with a perspective camera and return images and depthmaps']
```

Usage

```
{'create_image_augmentation_pipeline': 'create a function that applies random scale, rotation, color, and flip augmentations to an image using a bounding box', 'build_bbox_extraction_from_joints': 'build a function that extracts and extends a bounding box from valid 2D joint coordinates with configurable extension ratio', 'transform_3d_joint_data': 'transform 3D joint coordinates with flip augmentation, rotation, and affine transformation for heatmap output formatting', 'generate_mano_hand_mesh': 'generate MANO hand mesh coordinates and joint positions from pose parameters with camera extrinsic and flip support', 'compute_bbox_intersection_over_union': 'compute IoU between two sets of bounding boxes supporting both xyxy and xywh coordinate formats'}
```

## File: facebookresearch_interwild/common/utils/transforms.py

Prompts

```
['create a folder at the given path only if it does not already exist', 'add a directory to sys.path at the front if it is not already present', 'review the make_folder function that creates directories using os.makedirs when they do not exist', 'review the add_pypath function that prepends a path to sys.path to enable imports', 'refactor make_folder to use os.makedirs with exist_ok instead of a manual existence check', 'create a function that applies random scale, rotation, color, and flip augmentations to an image using a bounding box', 'build a function that extracts and extends a bounding box from valid 2D joint coordinates with configurable extension ratio', 'transform 3D joint coordinates with flip augmentation, rotation, and affine transformation for heatmap output formatting', 'generate MANO hand mesh coordinates and joint positions from pose parameters with camera extrinsic and flip support', 'compute IoU between two sets of bounding boxes supporting both xyxy and xywh coordinate formats', 'convert camera coordinates to pixel coordinates using focal length and principal point', 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'map joint coordinates from one skeleton naming convention to another dataset skeleton', 'sample image feature map values at joint positions using grid sampling', 'compute soft argmax coordinates from a 2D heatmap tensor using softmax weighted positions', 'draw colored skeleton lines and keypoints on an image using opencv', 'draw colored keypoints as circles on an image with configurable alpha blending', 'plot a 3D skeleton with colored lines and scatter points using matplotlib', 'save mesh vertices and faces to a Wavefront OBJ file', 'render a 3D mesh with a perspective camera and return images and depthmaps']
```

Usage

```
{'compute_cam2pixel': 'convert camera coordinates to pixel coordinates using focal length and principal point', 'compute_world2cam': 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'transform_joint_to_other_db': 'map joint coordinates from one skeleton naming convention to another dataset skeleton', 'sample_joint_features': 'sample image feature map values at joint positions using grid sampling', 'compute_soft_argmax_2d': 'compute soft argmax coordinates from a 2D heatmap tensor using softmax weighted positions'}
```

## File: facebookresearch_interwild/common/utils/vis.py

Prompts

```
['create a folder at the given path only if it does not already exist', 'add a directory to sys.path at the front if it is not already present', 'review the make_folder function that creates directories using os.makedirs when they do not exist', 'review the add_pypath function that prepends a path to sys.path to enable imports', 'refactor make_folder to use os.makedirs with exist_ok instead of a manual existence check', 'create a function that applies random scale, rotation, color, and flip augmentations to an image using a bounding box', 'build a function that extracts and extends a bounding box from valid 2D joint coordinates with configurable extension ratio', 'transform 3D joint coordinates with flip augmentation, rotation, and affine transformation for heatmap output formatting', 'generate MANO hand mesh coordinates and joint positions from pose parameters with camera extrinsic and flip support', 'compute IoU between two sets of bounding boxes supporting both xyxy and xywh coordinate formats', 'convert camera coordinates to pixel coordinates using focal length and principal point', 'transform world coordinates to camera coordinates using rotation matrix and translation vector', 'map joint coordinates from one skeleton naming convention to another dataset skeleton', 'sample image feature map values at joint positions using grid sampling', 'compute soft argmax coordinates from a 2D heatmap tensor using softmax weighted positions', 'draw colored skeleton lines and keypoints on an image using opencv', 'draw colored keypoints as circles on an image with configurable alpha blending', 'plot a 3D skeleton with colored lines and scatter points using matplotlib', 'save mesh vertices and faces to a Wavefront OBJ file', 'render a 3D mesh with a perspective camera and return images and depthmaps']
```

Usage

```
{'vis_keypoints_with_skeleton': 'draw colored skeleton lines and keypoints on an image using opencv', 'vis_keypoints': 'draw colored keypoints as circles on an image with configurable alpha blending', 'vis_3d_skeleton': 'plot a 3D skeleton with colored lines and scatter points using matplotlib', 'save_obj': 'save mesh vertices and faces to a Wavefront OBJ file', 'render_mesh_perspective': 'render a 3D mesh with a perspective camera and return images and depthmaps'}
```

