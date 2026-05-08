# Agent Python Tools

- repo: facebookresearch/pytorchvideo
- repo_uri: https://github.com/facebookresearch/pytorchvideo

## File: facebookresearch_pytorchvideo/projects/video_nerf/dataset.py

Prompts

```
['get training, validation, and test datasets for the objectron dataset with specified image size', 'get nerf datasets from a custom data root path with bundle adjusted camera parameters', 'return an uncollated batch as-is for use with PyTorch DataLoader collate_fn', 'review the get_nerf_datasets function that loads video frames and builds PerspectiveCameras per frame', 'refactor the trivial_collate function to support basic batch stacking for tensor images', 'convert Objectron rotation and translation matrices to PyTorch3D world coordinate system', 'generate shuffled train, validation, and test index splits from a list of image indices', 'parse Objectron protobuf metadata files to extract camera projection and view matrices per frame', 'resize a list of image frames to a target size with isotropic bilinear interpolation', 'review the dataset utility functions for coordinate transforms, data splitting, geometry parsing, and image resizing']
```

Usage

```
{'get_nerf_datasets_objectron': 'get training, validation, and test datasets for the objectron dataset with specified image size', 'get_nerf_datasets_custom_root': 'get nerf datasets from a custom data root path with bundle adjusted camera parameters', 'trivial_collate_batch': 'return an uncollated batch as-is for use with PyTorch DataLoader collate_fn', 'review_get_nerf_datasets': 'review the get_nerf_datasets function that loads video frames and builds PerspectiveCameras per frame', 'refactor_trivial_collate': 'refactor the trivial_collate function to support basic batch stacking for tensor images'}
```

## File: facebookresearch_pytorchvideo/projects/video_nerf/dataset_utils.py

Prompts

```
['get training, validation, and test datasets for the objectron dataset with specified image size', 'get nerf datasets from a custom data root path with bundle adjusted camera parameters', 'return an uncollated batch as-is for use with PyTorch DataLoader collate_fn', 'review the get_nerf_datasets function that loads video frames and builds PerspectiveCameras per frame', 'refactor the trivial_collate function to support basic batch stacking for tensor images', 'convert Objectron rotation and translation matrices to PyTorch3D world coordinate system', 'generate shuffled train, validation, and test index splits from a list of image indices', 'parse Objectron protobuf metadata files to extract camera projection and view matrices per frame', 'resize a list of image frames to a target size with isotropic bilinear interpolation', 'review the dataset utility functions for coordinate transforms, data splitting, geometry parsing, and image resizing']
```

Usage

```
{'convert_objectron_to_pytorch3d': 'convert Objectron rotation and translation matrices to PyTorch3D world coordinate system', 'generate_train_val_test_splits': 'generate shuffled train, validation, and test index splits from a list of image indices', 'parse_objectron_geometry_data': 'parse Objectron protobuf metadata files to extract camera projection and view matrices per frame', 'resize_image_frames': 'resize a list of image frames to a target size with isotropic bilinear interpolation', 'review_dataset_utils': 'review the dataset utility functions for coordinate transforms, data splitting, geometry parsing, and image resizing'}
```

