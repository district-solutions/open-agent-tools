# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/cutler/data/transforms/augmentation_impl.py

Prompts

```
['create a ResizeShortestEdge augmentation that resizes images keeping aspect ratio within a target range', 'build a RandomFlip augmentation to randomly flip images horizontally or vertically with a given probability', 'create a RandomCrop augmentation to randomly crop image regions using relative or absolute sizing strategies', 'build a FixedSizeCrop augmentation that crops or pads images to a fixed target size', 'create a RandomRotation augmentation to rotate images by a random angle within a specified range', 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create a ResizeTransform to resize an image to a specified height and width with optional interpolation', 'create a RotationTransform to rotate an image by a given angle with optional expansion to fit the rotated bounds', 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create a PILColorTransform to apply a PIL-based photometric operation to a numpy array image']
```

Usage

```
{'create_resize_shortest_edge_augmentation': 'create a ResizeShortestEdge augmentation that resizes images keeping aspect ratio within a target range', 'build_random_flip_augmentation': 'build a RandomFlip augmentation to randomly flip images horizontally or vertically with a given probability', 'create_random_crop_augmentation': 'create a RandomCrop augmentation to randomly crop image regions using relative or absolute sizing strategies', 'build_fixed_size_crop_augmentation': 'build a FixedSizeCrop augmentation that crops or pads images to a fixed target size', 'create_random_rotation_augmentation': 'create a RandomRotation augmentation to rotate images by a random angle within a specified range'}
```

## File: facebookresearch_cutler/cutler/data/transforms/transform.py

Prompts

```
['create a ResizeShortestEdge augmentation that resizes images keeping aspect ratio within a target range', 'build a RandomFlip augmentation to randomly flip images horizontally or vertically with a given probability', 'create a RandomCrop augmentation to randomly crop image regions using relative or absolute sizing strategies', 'build a FixedSizeCrop augmentation that crops or pads images to a fixed target size', 'create a RandomRotation augmentation to rotate images by a random angle within a specified range', 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create a ResizeTransform to resize an image to a specified height and width with optional interpolation', 'create a RotationTransform to rotate an image by a given angle with optional expansion to fit the rotated bounds', 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create a PILColorTransform to apply a PIL-based photometric operation to a numpy array image']
```

Usage

```
{'create_ExtentTransform': 'create an ExtentTransform to extract and scale a subregion from a source image to a target output size', 'create_ResizeTransform': 'create a ResizeTransform to resize an image to a specified height and width with optional interpolation', 'create_RotationTransform': 'create a RotationTransform to rotate an image by a given angle with optional expansion to fit the rotated bounds', 'create_ColorTransform': 'create a ColorTransform to apply a callable photometric operation to an image without changing coordinates', 'create_PILColorTransform': 'create a PILColorTransform to apply a PIL-based photometric operation to a numpy array image'}
```

