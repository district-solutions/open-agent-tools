# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/detectron2/data/transforms/augmentation.py

Prompts

```
['create a subclass of Augmentation that defines get_transform to generate a Transform for image data augmentation', 'build an AugmentationList to apply a sequence of augmentations in order to an AugInput object', 'create an AugInput object with an image ndarray and optional boxes and semantic segmentation mask', 'apply a list of augmentations to an image or AugInput and return the transformed inputs and transforms', 'test AugInput.transform to in-place transform image, boxes, and semantic segmentation with a Transform', 'build a data augmentation pipeline that resizes images while preserving aspect ratio with random short edge sampling', 'create a random crop augmentation with relative, absolute, or relative_range crop types for image datasets', 'build color jitter augmentations including random brightness, contrast, and saturation transformations on RGB images', 'build AlexNet-style lighting augmentation with PCA-based color jitter on RGB images', 'create a minimum IoU random crop augmentation that crops images while preserving bounding box overlap constraints', 'create a ResizeTransform to resize an image from original dimensions to a target size with bilinear interpolation', 'create a RotationTransform to rotate an image by a given angle around its center with expand', 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create a ColorTransform to apply a photometric operation to an image without changing coordinates', 'apply horizontal flip and resize transforms on rotated bounding boxes in x_center y_center width height angle format']
```

Usage

```
{'create_augmentation_subclass': 'create a subclass of Augmentation that defines get_transform to generate a Transform for image data augmentation', 'build_augmentation_list': 'build an AugmentationList to apply a sequence of augmentations in order to an AugInput object', 'create_aug_input': 'create an AugInput object with an image ndarray and optional boxes and semantic segmentation mask', 'apply_augmentations': 'apply a list of augmentations to an image or AugInput and return the transformed inputs and transforms', 'test_aug_input_transform': 'test AugInput.transform to in-place transform image, boxes, and semantic segmentation with a Transform'}
```

## File: facebookresearch_detectron2/detectron2/data/transforms/augmentation_impl.py

Prompts

```
['create a subclass of Augmentation that defines get_transform to generate a Transform for image data augmentation', 'build an AugmentationList to apply a sequence of augmentations in order to an AugInput object', 'create an AugInput object with an image ndarray and optional boxes and semantic segmentation mask', 'apply a list of augmentations to an image or AugInput and return the transformed inputs and transforms', 'test AugInput.transform to in-place transform image, boxes, and semantic segmentation with a Transform', 'build a data augmentation pipeline that resizes images while preserving aspect ratio with random short edge sampling', 'create a random crop augmentation with relative, absolute, or relative_range crop types for image datasets', 'build color jitter augmentations including random brightness, contrast, and saturation transformations on RGB images', 'build AlexNet-style lighting augmentation with PCA-based color jitter on RGB images', 'create a minimum IoU random crop augmentation that crops images while preserving bounding box overlap constraints', 'create a ResizeTransform to resize an image from original dimensions to a target size with bilinear interpolation', 'create a RotationTransform to rotate an image by a given angle around its center with expand', 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create a ColorTransform to apply a photometric operation to an image without changing coordinates', 'apply horizontal flip and resize transforms on rotated bounding boxes in x_center y_center width height angle format']
```

Usage

```
{'build_augmentation_resize_shortest_edge': 'build a data augmentation pipeline that resizes images while preserving aspect ratio with random short edge sampling', 'create_random_crop_augmentation': 'create a random crop augmentation with relative, absolute, or relative_range crop types for image datasets', 'build_color_jitter_augmentations': 'build color jitter augmentations including random brightness, contrast, and saturation transformations on RGB images', 'build_lighting_augmentation': 'build AlexNet-style lighting augmentation with PCA-based color jitter on RGB images', 'create_min_iou_random_crop': 'create a minimum IoU random crop augmentation that crops images while preserving bounding box overlap constraints'}
```

## File: facebookresearch_detectron2/detectron2/data/transforms/transform.py

Prompts

```
['create a subclass of Augmentation that defines get_transform to generate a Transform for image data augmentation', 'build an AugmentationList to apply a sequence of augmentations in order to an AugInput object', 'create an AugInput object with an image ndarray and optional boxes and semantic segmentation mask', 'apply a list of augmentations to an image or AugInput and return the transformed inputs and transforms', 'test AugInput.transform to in-place transform image, boxes, and semantic segmentation with a Transform', 'build a data augmentation pipeline that resizes images while preserving aspect ratio with random short edge sampling', 'create a random crop augmentation with relative, absolute, or relative_range crop types for image datasets', 'build color jitter augmentations including random brightness, contrast, and saturation transformations on RGB images', 'build AlexNet-style lighting augmentation with PCA-based color jitter on RGB images', 'create a minimum IoU random crop augmentation that crops images while preserving bounding box overlap constraints', 'create a ResizeTransform to resize an image from original dimensions to a target size with bilinear interpolation', 'create a RotationTransform to rotate an image by a given angle around its center with expand', 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create a ColorTransform to apply a photometric operation to an image without changing coordinates', 'apply horizontal flip and resize transforms on rotated bounding boxes in x_center y_center width height angle format']
```

Usage

```
{'create_resize_transform': 'create a ResizeTransform to resize an image from original dimensions to a target size with bilinear interpolation', 'create_rotation_transform': 'create a RotationTransform to rotate an image by a given angle around its center with expand', 'create_extent_transform': 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create_color_transform': 'create a ColorTransform to apply a photometric operation to an image without changing coordinates', 'apply_rotated_box_transforms': 'apply horizontal flip and resize transforms on rotated bounding boxes in x_center y_center width height angle format'}
```

