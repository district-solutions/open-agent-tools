# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/data/transforms/augmentation.py

Prompts

```
['create a custom Augmentation subclass that overrides get_transform to generate image transforms', 'apply a list of Augmentation objects to a numpy image array and get transformed output', 'build an AugmentationList that chains multiple augmentation policies together for sequential application', 'create an AugInput object wrapping an image with optional boxes and semantic segmentation masks', 'review the Augmentation base class get_transform method signature and input_args attribute convention', 'build a python module that creates a Detectron2 augmentation pipeline using RandomFlip and ResizeShortestEdge for image preprocessing', 'create a RandomFlip augmentation that horizontally flips images with 50% probability for data augmentation', 'create a ResizeShortestEdge augmentation that scales the shorter edge to a target size with max size limit', 'create a RandomCrop augmentation with relative_range crop type to randomly crop regions from input images', 'create RandomBrightness, RandomContrast, and RandomSaturation augmentations to apply color jittering to RGB images', 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create a ResizeTransform to resize an image from its original dimensions to new height and width', 'create a RotationTransform to rotate an image by a given number of degrees counter clockwise around its center', 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create a PILColorTransform to apply a PIL photometric operation to a numpy array image']
```

Usage

```
{'create_augmentation_subclass': 'create a custom Augmentation subclass that overrides get_transform to generate image transforms', 'apply_augmentations_to_image': 'apply a list of Augmentation objects to a numpy image array and get transformed output', 'create_augmentation_list': 'build an AugmentationList that chains multiple augmentation policies together for sequential application', 'create_aug_input': 'create an AugInput object wrapping an image with optional boxes and semantic segmentation masks', 'review_augmentation_get_transform': 'review the Augmentation base class get_transform method signature and input_args attribute convention'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/data/transforms/augmentation_impl.py

Prompts

```
['create a custom Augmentation subclass that overrides get_transform to generate image transforms', 'apply a list of Augmentation objects to a numpy image array and get transformed output', 'build an AugmentationList that chains multiple augmentation policies together for sequential application', 'create an AugInput object wrapping an image with optional boxes and semantic segmentation masks', 'review the Augmentation base class get_transform method signature and input_args attribute convention', 'build a python module that creates a Detectron2 augmentation pipeline using RandomFlip and ResizeShortestEdge for image preprocessing', 'create a RandomFlip augmentation that horizontally flips images with 50% probability for data augmentation', 'create a ResizeShortestEdge augmentation that scales the shorter edge to a target size with max size limit', 'create a RandomCrop augmentation with relative_range crop type to randomly crop regions from input images', 'create RandomBrightness, RandomContrast, and RandomSaturation augmentations to apply color jittering to RGB images', 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create a ResizeTransform to resize an image from its original dimensions to new height and width', 'create a RotationTransform to rotate an image by a given number of degrees counter clockwise around its center', 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create a PILColorTransform to apply a PIL photometric operation to a numpy array image']
```

Usage

```
{'build_augmentation_pipeline': 'build a python module that creates a Detectron2 augmentation pipeline using RandomFlip and ResizeShortestEdge for image preprocessing', 'create_random_flip_augmentation': 'create a RandomFlip augmentation that horizontally flips images with 50% probability for data augmentation', 'create_resize_shortest_edge': 'create a ResizeShortestEdge augmentation that scales the shorter edge to a target size with max size limit', 'create_random_crop_augmentation': 'create a RandomCrop augmentation with relative_range crop type to randomly crop regions from input images', 'create_color_augmentations': 'create RandomBrightness, RandomContrast, and RandomSaturation augmentations to apply color jittering to RGB images'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/data/transforms/transform.py

Prompts

```
['create a custom Augmentation subclass that overrides get_transform to generate image transforms', 'apply a list of Augmentation objects to a numpy image array and get transformed output', 'build an AugmentationList that chains multiple augmentation policies together for sequential application', 'create an AugInput object wrapping an image with optional boxes and semantic segmentation masks', 'review the Augmentation base class get_transform method signature and input_args attribute convention', 'build a python module that creates a Detectron2 augmentation pipeline using RandomFlip and ResizeShortestEdge for image preprocessing', 'create a RandomFlip augmentation that horizontally flips images with 50% probability for data augmentation', 'create a ResizeShortestEdge augmentation that scales the shorter edge to a target size with max size limit', 'create a RandomCrop augmentation with relative_range crop type to randomly crop regions from input images', 'create RandomBrightness, RandomContrast, and RandomSaturation augmentations to apply color jittering to RGB images', 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create a ResizeTransform to resize an image from its original dimensions to new height and width', 'create a RotationTransform to rotate an image by a given number of degrees counter clockwise around its center', 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create a PILColorTransform to apply a PIL photometric operation to a numpy array image']
```

Usage

```
{'create_ExtentTransform': 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create_ResizeTransform': 'create a ResizeTransform to resize an image from its original dimensions to new height and width', 'create_RotationTransform': 'create a RotationTransform to rotate an image by a given number of degrees counter clockwise around its center', 'create_ColorTransform': 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create_PILColorTransform': 'create a PILColorTransform to apply a PIL photometric operation to a numpy array image'}
```

