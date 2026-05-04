# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/detectron2/data/transforms/augmentation.py

Prompts

```
['create a custom Augmentation subclass that overrides get_transform to generate a Transform for image data', 'apply a list of Augmentation objects to a numpy image array and return the transformed image', 'create an AugmentationList to chain multiple Augmentation or Transform objects into a single callable sequence', 'create an AugInput object with an image array and optional boxes and semantic segmentation masks', 'review the Augmentation class get_transform method to understand how it generates deterministic Transforms from input data', 'create a ResizeShortestEdge augmentation to resize images by shortest edge length with max size constraint', 'create a RandomFlip augmentation to randomly flip images horizontally or vertically with given probability', 'create a RandomCrop augmentation to randomly crop regions using relative or absolute crop size strategies', 'create a RandomBrightness augmentation to randomly adjust image brightness within a specified intensity range', 'create a FixedSizeCrop augmentation to crop or pad images to a fixed target size', 'create an ExtentTransform to extract and scale a subregion of an image to a target output size', 'create a ResizeTransform to resize an image from its original dimensions to new height and width', 'create a RotationTransform to rotate an image by a given number of degrees counter clockwise', 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create a PILColorTransform to apply a PIL photometric operation to an image array']
```

Usage

```
{'create_augmentation_subclass': 'create a custom Augmentation subclass that overrides get_transform to generate a Transform for image data', 'apply_augmentations_to_image': 'apply a list of Augmentation objects to a numpy image array and return the transformed image', 'create_augmentation_list': 'create an AugmentationList to chain multiple Augmentation or Transform objects into a single callable sequence', 'create_aug_input': 'create an AugInput object with an image array and optional boxes and semantic segmentation masks', 'review_augmentation_get_transform': 'review the Augmentation class get_transform method to understand how it generates deterministic Transforms from input data'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/data/transforms/augmentation_impl.py

Prompts

```
['create a custom Augmentation subclass that overrides get_transform to generate a Transform for image data', 'apply a list of Augmentation objects to a numpy image array and return the transformed image', 'create an AugmentationList to chain multiple Augmentation or Transform objects into a single callable sequence', 'create an AugInput object with an image array and optional boxes and semantic segmentation masks', 'review the Augmentation class get_transform method to understand how it generates deterministic Transforms from input data', 'create a ResizeShortestEdge augmentation to resize images by shortest edge length with max size constraint', 'create a RandomFlip augmentation to randomly flip images horizontally or vertically with given probability', 'create a RandomCrop augmentation to randomly crop regions using relative or absolute crop size strategies', 'create a RandomBrightness augmentation to randomly adjust image brightness within a specified intensity range', 'create a FixedSizeCrop augmentation to crop or pad images to a fixed target size', 'create an ExtentTransform to extract and scale a subregion of an image to a target output size', 'create a ResizeTransform to resize an image from its original dimensions to new height and width', 'create a RotationTransform to rotate an image by a given number of degrees counter clockwise', 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create a PILColorTransform to apply a PIL photometric operation to an image array']
```

Usage

```
{'create_resize_shortest_edge_augmentation': 'create a ResizeShortestEdge augmentation to resize images by shortest edge length with max size constraint', 'create_random_flip_augmentation': 'create a RandomFlip augmentation to randomly flip images horizontally or vertically with given probability', 'create_random_crop_augmentation': 'create a RandomCrop augmentation to randomly crop regions using relative or absolute crop size strategies', 'create_random_brightness_augmentation': 'create a RandomBrightness augmentation to randomly adjust image brightness within a specified intensity range', 'create_fixed_size_crop_augmentation': 'create a FixedSizeCrop augmentation to crop or pad images to a fixed target size'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/data/transforms/transform.py

Prompts

```
['create a custom Augmentation subclass that overrides get_transform to generate a Transform for image data', 'apply a list of Augmentation objects to a numpy image array and return the transformed image', 'create an AugmentationList to chain multiple Augmentation or Transform objects into a single callable sequence', 'create an AugInput object with an image array and optional boxes and semantic segmentation masks', 'review the Augmentation class get_transform method to understand how it generates deterministic Transforms from input data', 'create a ResizeShortestEdge augmentation to resize images by shortest edge length with max size constraint', 'create a RandomFlip augmentation to randomly flip images horizontally or vertically with given probability', 'create a RandomCrop augmentation to randomly crop regions using relative or absolute crop size strategies', 'create a RandomBrightness augmentation to randomly adjust image brightness within a specified intensity range', 'create a FixedSizeCrop augmentation to crop or pad images to a fixed target size', 'create an ExtentTransform to extract and scale a subregion of an image to a target output size', 'create a ResizeTransform to resize an image from its original dimensions to new height and width', 'create a RotationTransform to rotate an image by a given number of degrees counter clockwise', 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create a PILColorTransform to apply a PIL photometric operation to an image array']
```

Usage

```
{'create_extent_transform': 'create an ExtentTransform to extract and scale a subregion of an image to a target output size', 'create_resize_transform': 'create a ResizeTransform to resize an image from its original dimensions to new height and width', 'create_rotation_transform': 'create a RotationTransform to rotate an image by a given number of degrees counter clockwise', 'create_color_transform': 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create_pil_color_transform': 'create a PILColorTransform to apply a PIL photometric operation to an image array'}
```

