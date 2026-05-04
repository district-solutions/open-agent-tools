# Agent Python Tools

- repo: google-deepmind/distributionshiftframework
- repo_uri: https://github.com/google-deepmind/distribution_shift_framework

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/core/pix/augment.py

Prompts

```
['build a python module that applies auto contrast augmentation to an RGB image with a cutoff percentage', 'build a python module that applies histogram equalization to an RGB image to cover the full scale', 'build a python module that applies posterize augmentation to an RGB image by removing least significant bits', 'build a python module that applies solarize augmentation to an RGB image by inverting pixels above a threshold', 'build a python module that shifts a specific RGB channel color by a given additive factor', 'convert an RGB image array to HSV color space using JAX', 'convert hue, saturation, value planes back to RGB color planes', 'split a 3-channel image array into individual channel arrays', 'convert separate red, green, blue planes to hue, saturation, value planes', 'review the color conversion utilities for RGB to HSV transformations', 'apply gaussian blur corruption to a JAX image array at a given severity level', 'apply zoom blur corruption to a batched JAX image array using ImageNet-C severity levels', 'add gaussian noise to a JAX image array at a configurable severity level', 'apply salt and pepper impulse noise corruption to a JAX image array', 'adjust the brightness of a JAX image array by modifying HSV value channel', 'build a python module that applies mixup augmentation to a batch of images and one-hot labels using JAX', 'create a function that interpolates pairs of images with weighted labels using a beta distribution sampling', 'test the mixup function by passing a batch of images and one-hot encoded labels with custom alpha and beta parameters', 'refactor the mixup function to accept a custom PRNG key for reproducible image interpolation results', 'summarize the mixup postprocessing step that blends image pairs and their labels using beta-distributed weights']
```

Usage

```
{'build_auto_contrast_augmentation': 'build a python module that applies auto contrast augmentation to an RGB image with a cutoff percentage', 'build_equalize_augmentation': 'build a python module that applies histogram equalization to an RGB image to cover the full scale', 'build_posterize_augmentation': 'build a python module that applies posterize augmentation to an RGB image by removing least significant bits', 'build_solarize_augmentation': 'build a python module that applies solarize augmentation to an RGB image by inverting pixels above a threshold', 'build_adjust_color_augmentation': 'build a python module that shifts a specific RGB channel color by a given additive factor'}
```

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/core/pix/color_conversion.py

Prompts

```
['build a python module that applies auto contrast augmentation to an RGB image with a cutoff percentage', 'build a python module that applies histogram equalization to an RGB image to cover the full scale', 'build a python module that applies posterize augmentation to an RGB image by removing least significant bits', 'build a python module that applies solarize augmentation to an RGB image by inverting pixels above a threshold', 'build a python module that shifts a specific RGB channel color by a given additive factor', 'convert an RGB image array to HSV color space using JAX', 'convert hue, saturation, value planes back to RGB color planes', 'split a 3-channel image array into individual channel arrays', 'convert separate red, green, blue planes to hue, saturation, value planes', 'review the color conversion utilities for RGB to HSV transformations', 'apply gaussian blur corruption to a JAX image array at a given severity level', 'apply zoom blur corruption to a batched JAX image array using ImageNet-C severity levels', 'add gaussian noise to a JAX image array at a configurable severity level', 'apply salt and pepper impulse noise corruption to a JAX image array', 'adjust the brightness of a JAX image array by modifying HSV value channel', 'build a python module that applies mixup augmentation to a batch of images and one-hot labels using JAX', 'create a function that interpolates pairs of images with weighted labels using a beta distribution sampling', 'test the mixup function by passing a batch of images and one-hot encoded labels with custom alpha and beta parameters', 'refactor the mixup function to accept a custom PRNG key for reproducible image interpolation results', 'summarize the mixup postprocessing step that blends image pairs and their labels using beta-distributed weights']
```

Usage

```
{'convert_rgb_to_hsv': 'convert an RGB image array to HSV color space using JAX', 'convert_hsv_to_rgb': 'convert hue, saturation, value planes back to RGB color planes', 'split_image_channels': 'split a 3-channel image array into individual channel arrays', 'convert_rgb_planes_to_hsv': 'convert separate red, green, blue planes to hue, saturation, value planes', 'review_color_conversion': 'review the color conversion utilities for RGB to HSV transformations'}
```

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/core/pix/corruptions.py

Prompts

```
['build a python module that applies auto contrast augmentation to an RGB image with a cutoff percentage', 'build a python module that applies histogram equalization to an RGB image to cover the full scale', 'build a python module that applies posterize augmentation to an RGB image by removing least significant bits', 'build a python module that applies solarize augmentation to an RGB image by inverting pixels above a threshold', 'build a python module that shifts a specific RGB channel color by a given additive factor', 'convert an RGB image array to HSV color space using JAX', 'convert hue, saturation, value planes back to RGB color planes', 'split a 3-channel image array into individual channel arrays', 'convert separate red, green, blue planes to hue, saturation, value planes', 'review the color conversion utilities for RGB to HSV transformations', 'apply gaussian blur corruption to a JAX image array at a given severity level', 'apply zoom blur corruption to a batched JAX image array using ImageNet-C severity levels', 'add gaussian noise to a JAX image array at a configurable severity level', 'apply salt and pepper impulse noise corruption to a JAX image array', 'adjust the brightness of a JAX image array by modifying HSV value channel', 'build a python module that applies mixup augmentation to a batch of images and one-hot labels using JAX', 'create a function that interpolates pairs of images with weighted labels using a beta distribution sampling', 'test the mixup function by passing a batch of images and one-hot encoded labels with custom alpha and beta parameters', 'refactor the mixup function to accept a custom PRNG key for reproducible image interpolation results', 'summarize the mixup postprocessing step that blends image pairs and their labels using beta-distributed weights']
```

Usage

```
{'apply_gaussian_blur': 'apply gaussian blur corruption to a JAX image array at a given severity level', 'apply_zoom_blur': 'apply zoom blur corruption to a batched JAX image array using ImageNet-C severity levels', 'apply_gaussian_noise': 'add gaussian noise to a JAX image array at a configurable severity level', 'apply_impulse_noise': 'apply salt and pepper impulse noise corruption to a JAX image array', 'adjust_brightness': 'adjust the brightness of a JAX image array by modifying HSV value channel'}
```

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/core/pix/postprocessing.py

Prompts

```
['build a python module that applies auto contrast augmentation to an RGB image with a cutoff percentage', 'build a python module that applies histogram equalization to an RGB image to cover the full scale', 'build a python module that applies posterize augmentation to an RGB image by removing least significant bits', 'build a python module that applies solarize augmentation to an RGB image by inverting pixels above a threshold', 'build a python module that shifts a specific RGB channel color by a given additive factor', 'convert an RGB image array to HSV color space using JAX', 'convert hue, saturation, value planes back to RGB color planes', 'split a 3-channel image array into individual channel arrays', 'convert separate red, green, blue planes to hue, saturation, value planes', 'review the color conversion utilities for RGB to HSV transformations', 'apply gaussian blur corruption to a JAX image array at a given severity level', 'apply zoom blur corruption to a batched JAX image array using ImageNet-C severity levels', 'add gaussian noise to a JAX image array at a configurable severity level', 'apply salt and pepper impulse noise corruption to a JAX image array', 'adjust the brightness of a JAX image array by modifying HSV value channel', 'build a python module that applies mixup augmentation to a batch of images and one-hot labels using JAX', 'create a function that interpolates pairs of images with weighted labels using a beta distribution sampling', 'test the mixup function by passing a batch of images and one-hot encoded labels with custom alpha and beta parameters', 'refactor the mixup function to accept a custom PRNG key for reproducible image interpolation results', 'summarize the mixup postprocessing step that blends image pairs and their labels using beta-distributed weights']
```

Usage

```
{'build_mixup_augmentation': 'build a python module that applies mixup augmentation to a batch of images and one-hot labels using JAX', 'create_image_interpolation': 'create a function that interpolates pairs of images with weighted labels using a beta distribution sampling', 'test_mixup_function': 'test the mixup function by passing a batch of images and one-hot encoded labels with custom alpha and beta parameters', 'refactor_mixup_rng': 'refactor the mixup function to accept a custom PRNG key for reproducible image interpolation results', 'summarize_mixup_postprocessing': 'summarize the mixup postprocessing step that blends image pairs and their labels using beta-distributed weights'}
```

