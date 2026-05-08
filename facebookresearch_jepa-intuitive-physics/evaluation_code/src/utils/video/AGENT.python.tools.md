# Agent Python Tools

- repo: facebookresearch/jepa-intuitive-physics
- repo_uri: https://github.com/facebookresearch/jepa-intuitive-physics

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/utils/video/functional.py

Prompts

```
['crop a video clip by specifying min_h, min_w, height, and width for numpy, PIL, or tensor frames', 'resize a video clip to a target size using bilinear or nearest interpolation for numpy, PIL, or tensor frames', 'compute new height and width for resizing an image while preserving its aspect ratio', 'normalize a 4D tensor video clip using mean and std values with optional inplace operation', 'check if a given clip is a 4D PyTorch tensor suitable for video processing', 'create a RandAugment transform from a config string like rand-m9-n3-mstd0.5', 'apply an AugmentOp to a single PIL image or list of images with configurable probability', 'build a list of AugmentOp instances for use with RandAugment data augmentation', 'review the shear_x, shear_y, translate, and rotate image transformation functions', 'refactor the LEVEL_TO_ARG dictionary to add new augmentation level-to-argument mappings', 'create a random augmentation transform for video frames using rand-m7-n4-mstd0.5-inc1 parameters', 'build a function that crops video frames to a random size and aspect ratio then resizes', 'create a function that crops video frames with linearly interpolated shifting across frames', 'build a function that applies brightness contrast and saturation jitter to video frames', 'create a function that performs AlexNet-style PCA jitter on video frames using eigenvalues and eigenvectors']
```

Usage

```
{'crop_clip': 'crop a video clip by specifying min_h, min_w, height, and width for numpy, PIL, or tensor frames', 'resize_clip': 'resize a video clip to a target size using bilinear or nearest interpolation for numpy, PIL, or tensor frames', 'get_resize_sizes': 'compute new height and width for resizing an image while preserving its aspect ratio', 'normalize_clip': 'normalize a 4D tensor video clip using mean and std values with optional inplace operation', 'is_tensor_clip': 'check if a given clip is a 4D PyTorch tensor suitable for video processing'}
```

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/utils/video/randaugment.py

Prompts

```
['crop a video clip by specifying min_h, min_w, height, and width for numpy, PIL, or tensor frames', 'resize a video clip to a target size using bilinear or nearest interpolation for numpy, PIL, or tensor frames', 'compute new height and width for resizing an image while preserving its aspect ratio', 'normalize a 4D tensor video clip using mean and std values with optional inplace operation', 'check if a given clip is a 4D PyTorch tensor suitable for video processing', 'create a RandAugment transform from a config string like rand-m9-n3-mstd0.5', 'apply an AugmentOp to a single PIL image or list of images with configurable probability', 'build a list of AugmentOp instances for use with RandAugment data augmentation', 'review the shear_x, shear_y, translate, and rotate image transformation functions', 'refactor the LEVEL_TO_ARG dictionary to add new augmentation level-to-argument mappings', 'create a random augmentation transform for video frames using rand-m7-n4-mstd0.5-inc1 parameters', 'build a function that crops video frames to a random size and aspect ratio then resizes', 'create a function that crops video frames with linearly interpolated shifting across frames', 'build a function that applies brightness contrast and saturation jitter to video frames', 'create a function that performs AlexNet-style PCA jitter on video frames using eigenvalues and eigenvectors']
```

Usage

```
{'create_randaugment_transform': 'create a RandAugment transform from a config string like rand-m9-n3-mstd0.5', 'apply_augmentop_to_images': 'apply an AugmentOp to a single PIL image or list of images with configurable probability', 'build_rand_augment_ops': 'build a list of AugmentOp instances for use with RandAugment data augmentation', 'review_shear_translate_rotate_ops': 'review the shear_x, shear_y, translate, and rotate image transformation functions', 'refactor_LEVEL_TO_ARG_mapping': 'refactor the LEVEL_TO_ARG dictionary to add new augmentation level-to-argument mappings'}
```

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/utils/video/transforms.py

Prompts

```
['crop a video clip by specifying min_h, min_w, height, and width for numpy, PIL, or tensor frames', 'resize a video clip to a target size using bilinear or nearest interpolation for numpy, PIL, or tensor frames', 'compute new height and width for resizing an image while preserving its aspect ratio', 'normalize a 4D tensor video clip using mean and std values with optional inplace operation', 'check if a given clip is a 4D PyTorch tensor suitable for video processing', 'create a RandAugment transform from a config string like rand-m9-n3-mstd0.5', 'apply an AugmentOp to a single PIL image or list of images with configurable probability', 'build a list of AugmentOp instances for use with RandAugment data augmentation', 'review the shear_x, shear_y, translate, and rotate image transformation functions', 'refactor the LEVEL_TO_ARG dictionary to add new augmentation level-to-argument mappings', 'create a random augmentation transform for video frames using rand-m7-n4-mstd0.5-inc1 parameters', 'build a function that crops video frames to a random size and aspect ratio then resizes', 'create a function that crops video frames with linearly interpolated shifting across frames', 'build a function that applies brightness contrast and saturation jitter to video frames', 'create a function that performs AlexNet-style PCA jitter on video frames using eigenvalues and eigenvectors']
```

Usage

```
{'create_random_augment': 'create a random augmentation transform for video frames using rand-m7-n4-mstd0.5-inc1 parameters', 'random_resized_crop': 'build a function that crops video frames to a random size and aspect ratio then resizes', 'random_resized_crop_with_shift': 'create a function that crops video frames with linearly interpolated shifting across frames', 'color_jitter': 'build a function that applies brightness contrast and saturation jitter to video frames', 'lighting_jitter': 'create a function that performs AlexNet-style PCA jitter on video frames using eigenvalues and eigenvectors'}
```

