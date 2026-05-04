# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/image/functional.py

Prompts

```
['apply a custom lambda function to augment a PIL image with user-defined transformations', 'blur a PIL image using Gaussian blur with a configurable radius parameter', 'overlay social-media-style text with a background box on an image simulating viral post overlays', 'apply a perspective transform to an image so it looks like a photo taken from another device', 'resize a PIL image to specified width and height or crop it to relative coordinates', 'run an image augmentation function on a numpy array and return the augmented numpy array', 'fit text into an image bounding box by adjusting font size and coordinates', 'wrap text into lines that fit within a maximum width using a given font', 'compute the blur intensity score from a given radius value normalized to 0-100', 'compute the color jitter intensity from brightness, contrast, and saturation factors', 'compute the resize intensity from metadata comparing source and destination image areas', 'compute the overlay media intensity from opacity and content size factors', 'compute the rotation intensity score from degrees of rotation normalized to 0-100', 'create a Blur transform class with a specified radius to blur a PIL Image', 'create a Brightness transform class with a factor to brighten or darken a PIL Image', 'create a Crop transform class with x1, y1, x2, y2 coordinates to crop a PIL Image', 'create a Rotate transform class with degrees to rotate a PIL Image counter clockwise', 'create a composition of multiple transform classes like Blur, Brightness, and Crop to apply sequentially']
```

Usage

```
{'apply_lambda_augmentation': 'apply a custom lambda function to augment a PIL image with user-defined transformations', 'blur_image': 'blur a PIL image using Gaussian blur with a configurable radius parameter', 'overlay_random_text_with_background': 'overlay social-media-style text with a background box on an image simulating viral post overlays', 'perspective_transform_image': 'apply a perspective transform to an image so it looks like a photo taken from another device', 'resize_and_crop_image': 'resize a PIL image to specified width and height or crop it to relative coordinates'}
```

## File: facebookresearch_augly/augly/image/helpers.py

Prompts

```
['apply a custom lambda function to augment a PIL image with user-defined transformations', 'blur a PIL image using Gaussian blur with a configurable radius parameter', 'overlay social-media-style text with a background box on an image simulating viral post overlays', 'apply a perspective transform to an image so it looks like a photo taken from another device', 'resize a PIL image to specified width and height or crop it to relative coordinates', 'run an image augmentation function on a numpy array and return the augmented numpy array', 'fit text into an image bounding box by adjusting font size and coordinates', 'wrap text into lines that fit within a maximum width using a given font', 'compute the blur intensity score from a given radius value normalized to 0-100', 'compute the color jitter intensity from brightness, contrast, and saturation factors', 'compute the resize intensity from metadata comparing source and destination image areas', 'compute the overlay media intensity from opacity and content size factors', 'compute the rotation intensity score from degrees of rotation normalized to 0-100', 'create a Blur transform class with a specified radius to blur a PIL Image', 'create a Brightness transform class with a factor to brighten or darken a PIL Image', 'create a Crop transform class with x1, y1, x2, y2 coordinates to crop a PIL Image', 'create a Rotate transform class with degrees to rotate a PIL Image counter clockwise', 'create a composition of multiple transform classes like Blur, Brightness, and Crop to apply sequentially']
```

Usage

```
{'run_aug_np_wrapper': 'run an image augmentation function on a numpy array and return the augmented numpy array', 'run_fit_text_in_bbox': 'fit text into an image bounding box by adjusting font size and coordinates', 'run_wrap_text_for_image_overlay': 'wrap text into lines that fit within a maximum width using a given font'}
```

## File: facebookresearch_augly/augly/image/intensity.py

Prompts

```
['apply a custom lambda function to augment a PIL image with user-defined transformations', 'blur a PIL image using Gaussian blur with a configurable radius parameter', 'overlay social-media-style text with a background box on an image simulating viral post overlays', 'apply a perspective transform to an image so it looks like a photo taken from another device', 'resize a PIL image to specified width and height or crop it to relative coordinates', 'run an image augmentation function on a numpy array and return the augmented numpy array', 'fit text into an image bounding box by adjusting font size and coordinates', 'wrap text into lines that fit within a maximum width using a given font', 'compute the blur intensity score from a given radius value normalized to 0-100', 'compute the color jitter intensity from brightness, contrast, and saturation factors', 'compute the resize intensity from metadata comparing source and destination image areas', 'compute the overlay media intensity from opacity and content size factors', 'compute the rotation intensity score from degrees of rotation normalized to 0-100', 'create a Blur transform class with a specified radius to blur a PIL Image', 'create a Brightness transform class with a factor to brighten or darken a PIL Image', 'create a Crop transform class with x1, y1, x2, y2 coordinates to crop a PIL Image', 'create a Rotate transform class with degrees to rotate a PIL Image counter clockwise', 'create a composition of multiple transform classes like Blur, Brightness, and Crop to apply sequentially']
```

Usage

```
{'compute_blur_intensity': 'compute the blur intensity score from a given radius value normalized to 0-100', 'compute_color_jitter_intensity': 'compute the color jitter intensity from brightness, contrast, and saturation factors', 'compute_resize_intensity': 'compute the resize intensity from metadata comparing source and destination image areas', 'compute_overlay_intensity': 'compute the overlay media intensity from opacity and content size factors', 'compute_rotation_intensity': 'compute the rotation intensity score from degrees of rotation normalized to 0-100'}
```

## File: facebookresearch_augly/augly/image/transforms.py

Prompts

```
['apply a custom lambda function to augment a PIL image with user-defined transformations', 'blur a PIL image using Gaussian blur with a configurable radius parameter', 'overlay social-media-style text with a background box on an image simulating viral post overlays', 'apply a perspective transform to an image so it looks like a photo taken from another device', 'resize a PIL image to specified width and height or crop it to relative coordinates', 'run an image augmentation function on a numpy array and return the augmented numpy array', 'fit text into an image bounding box by adjusting font size and coordinates', 'wrap text into lines that fit within a maximum width using a given font', 'compute the blur intensity score from a given radius value normalized to 0-100', 'compute the color jitter intensity from brightness, contrast, and saturation factors', 'compute the resize intensity from metadata comparing source and destination image areas', 'compute the overlay media intensity from opacity and content size factors', 'compute the rotation intensity score from degrees of rotation normalized to 0-100', 'create a Blur transform class with a specified radius to blur a PIL Image', 'create a Brightness transform class with a factor to brighten or darken a PIL Image', 'create a Crop transform class with x1, y1, x2, y2 coordinates to crop a PIL Image', 'create a Rotate transform class with degrees to rotate a PIL Image counter clockwise', 'create a composition of multiple transform classes like Blur, Brightness, and Crop to apply sequentially']
```

Usage

```
{'create_blur_transform': 'create a Blur transform class with a specified radius to blur a PIL Image', 'create_brightness_transform': 'create a Brightness transform class with a factor to brighten or darken a PIL Image', 'create_crop_transform': 'create a Crop transform class with x1, y1, x2, y2 coordinates to crop a PIL Image', 'create_rotate_transform': 'create a Rotate transform class with degrees to rotate a PIL Image counter clockwise', 'create_compose_transforms': 'create a composition of multiple transform classes like Blur, Brightness, and Crop to apply sequentially'}
```

