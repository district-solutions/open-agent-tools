# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/third_party/CenterNet2/centernet/data/transforms/custom_augmentation_impl.py

Prompts

```
['build a python module that creates an EfficientDetResizeCrop augmentation with a target size and random scale range', 'create an EfficientDetResizeCrop augmentation instance with a specified size and scale tuple for data augmentation', 'test the EfficientDetResizeCrop get_transform method by passing a numpy image array and verifying the returned transform', 'review the EfficientDetResizeCrop class and its scaling logic that computes img_scale from image dimensions and target size', 'refactor the EfficientDetResizeCrop class to support additional interpolation methods beyond PIL BILINEAR', 'create an EfficientDetResizeCropTransform instance with scaled dimensions, offset, and target size for image preprocessing', 'apply the EfficientDetResizeCropTransform to resize a numpy image array and crop to target size', 'apply coordinate scaling and offset adjustment to 2D coordinate arrays using img_scale and offset values', 'apply segmentation mask transformation using nearest neighbor interpolation via the apply_segmentation method', 'review the EfficientDetResizeCropTransform class and its image resizing, cropping, and coordinate transformation methods']
```

Usage

```
{'build_EfficientDetResizeCrop_augmentation': 'build a python module that creates an EfficientDetResizeCrop augmentation with a target size and random scale range', 'create_EfficientDetResizeCrop_with_scale': 'create an EfficientDetResizeCrop augmentation instance with a specified size and scale tuple for data augmentation', 'test_EfficientDetResizeCrop_get_transform': 'test the EfficientDetResizeCrop get_transform method by passing a numpy image array and verifying the returned transform', 'review_EfficientDetResizeCrop_scaling_logic': 'review the EfficientDetResizeCrop class and its scaling logic that computes img_scale from image dimensions and target size', 'refactor_EfficientDetResizeCrop_interp': 'refactor the EfficientDetResizeCrop class to support additional interpolation methods beyond PIL BILINEAR'}
```

## File: facebookresearch_detic/third_party/CenterNet2/centernet/data/transforms/custom_transform.py

Prompts

```
['build a python module that creates an EfficientDetResizeCrop augmentation with a target size and random scale range', 'create an EfficientDetResizeCrop augmentation instance with a specified size and scale tuple for data augmentation', 'test the EfficientDetResizeCrop get_transform method by passing a numpy image array and verifying the returned transform', 'review the EfficientDetResizeCrop class and its scaling logic that computes img_scale from image dimensions and target size', 'refactor the EfficientDetResizeCrop class to support additional interpolation methods beyond PIL BILINEAR', 'create an EfficientDetResizeCropTransform instance with scaled dimensions, offset, and target size for image preprocessing', 'apply the EfficientDetResizeCropTransform to resize a numpy image array and crop to target size', 'apply coordinate scaling and offset adjustment to 2D coordinate arrays using img_scale and offset values', 'apply segmentation mask transformation using nearest neighbor interpolation via the apply_segmentation method', 'review the EfficientDetResizeCropTransform class and its image resizing, cropping, and coordinate transformation methods']
```

Usage

```
{'create_EfficientDetResizeCropTransform': 'create an EfficientDetResizeCropTransform instance with scaled dimensions, offset, and target size for image preprocessing', 'apply_image_resize_and_crop': 'apply the EfficientDetResizeCropTransform to resize a numpy image array and crop to target size', 'apply_coords_scale_and_offset': 'apply coordinate scaling and offset adjustment to 2D coordinate arrays using img_scale and offset values', 'apply_segmentation_nearest_interp': 'apply segmentation mask transformation using nearest neighbor interpolation via the apply_segmentation method', 'review_EfficientDetResizeCropTransform_class': 'review the EfficientDetResizeCropTransform class and its image resizing, cropping, and coordinate transformation methods'}
```

