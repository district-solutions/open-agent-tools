# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/detic/data/transforms/custom_augmentation_impl.py

Prompts

```
['create an EfficientDetResizeCrop augmentation with a target size and random scale range for image preprocessing', 'build a data augmentation pipeline using EfficientDetResizeCrop with configurable scale factors for training images', 'test the EfficientDetResizeCrop get_transform method on a numpy image array to verify random scaling and cropping', 'review the EfficientDetResizeCrop class to understand how it computes random scale factors and offset-based cropping', 'refactor the EfficientDetResizeCrop initialization to use a different PIL interpolation method instead of bilinear', 'create an EfficientDetResizeCropTransform instance with scaled dimensions, offsets, image scale, and target size', 'apply image resize and crop transformation using bilinear or bicubic interpolation on uint8 or float arrays', 'apply coordinate scaling and offset transformation to 2D coordinate arrays for bounding box adjustment', 'apply segmentation mask transformation using nearest neighbor interpolation via the apply_image method', 'inverse transform bounding boxes by reversing offset and scale operations to recover original coordinates']
```

Usage

```
{'create_EfficientDetResizeCrop_augmentation': 'create an EfficientDetResizeCrop augmentation with a target size and random scale range for image preprocessing', 'build_EfficientDetResizeCrop_with_scale': 'build a data augmentation pipeline using EfficientDetResizeCrop with configurable scale factors for training images', 'test_EfficientDetResizeCrop_get_transform': 'test the EfficientDetResizeCrop get_transform method on a numpy image array to verify random scaling and cropping', 'review_EfficientDetResizeCrop_class': 'review the EfficientDetResizeCrop class to understand how it computes random scale factors and offset-based cropping', 'refactor_EfficientDetResizeCrop_interp': 'refactor the EfficientDetResizeCrop initialization to use a different PIL interpolation method instead of bilinear'}
```

## File: facebookresearch_detic/detic/data/transforms/custom_transform.py

Prompts

```
['create an EfficientDetResizeCrop augmentation with a target size and random scale range for image preprocessing', 'build a data augmentation pipeline using EfficientDetResizeCrop with configurable scale factors for training images', 'test the EfficientDetResizeCrop get_transform method on a numpy image array to verify random scaling and cropping', 'review the EfficientDetResizeCrop class to understand how it computes random scale factors and offset-based cropping', 'refactor the EfficientDetResizeCrop initialization to use a different PIL interpolation method instead of bilinear', 'create an EfficientDetResizeCropTransform instance with scaled dimensions, offsets, image scale, and target size', 'apply image resize and crop transformation using bilinear or bicubic interpolation on uint8 or float arrays', 'apply coordinate scaling and offset transformation to 2D coordinate arrays for bounding box adjustment', 'apply segmentation mask transformation using nearest neighbor interpolation via the apply_image method', 'inverse transform bounding boxes by reversing offset and scale operations to recover original coordinates']
```

Usage

```
{'create_EfficientDetResizeCropTransform': 'create an EfficientDetResizeCropTransform instance with scaled dimensions, offsets, image scale, and target size', 'apply_image_resize_and_crop': 'apply image resize and crop transformation using bilinear or bicubic interpolation on uint8 or float arrays', 'apply_coords_scale_and_offset': 'apply coordinate scaling and offset transformation to 2D coordinate arrays for bounding box adjustment', 'apply_segmentation_nearest_interp': 'apply segmentation mask transformation using nearest neighbor interpolation via the apply_image method', 'inverse_apply_box_transform': 'inverse transform bounding boxes by reversing offset and scale operations to recover original coordinates'}
```

