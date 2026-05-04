# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/image/utils/bboxes.py

Prompts

```
['create a function that renormalizes a bounding box after an image is cropped using crop_bboxes_helper', 'build a module that horizontally flips a normalized bounding box using hflip_bboxes_helper', 'build a module that vertically flips a normalized bounding box using vflip_bboxes_helper', 'create a function that computes the enclosing bounding box after rotating an image using rotate_bboxes_helper', 'build a module that transforms a bounding box after a perspective transform using perspective_transform_bboxes_helper', 'normalize a bounding box from pascal_voc, coco, or yolo format to normalized coordinates', 'validate and normalize a list of bounding boxes to normalized coordinates between 0 and 1', 'convert normalized bounding boxes back to pascal_voc, coco, or yolo format after augmentation', 'check transformed bounding boxes and return None for boxes cropped out or inverted after augmentation', 'transform bounding boxes to match an augmented image using a helper function and format conversion', 'create a python module that loads an image from a file path or validates a PIL Image object', 'build a python script that saves a PIL Image to disk with optional color mode conversion', 'create a function that computes the largest axis-aligned rectangle dimensions within a rotated rectangle', 'build a python module that resizes, pads with black, or crops an image to fit target dimensions', 'create a numpy binary mask with diagonal, horizontal, or vertical stripe patterns given width, angle, and density']
```

Usage

```
{'transform_bbox_after_crop': 'create a function that renormalizes a bounding box after an image is cropped using crop_bboxes_helper', 'flip_bbox_horizontally': 'build a module that horizontally flips a normalized bounding box using hflip_bboxes_helper', 'flip_bbox_vertically': 'build a module that vertically flips a normalized bounding box using vflip_bboxes_helper', 'transform_bbox_after_rotation': 'create a function that computes the enclosing bounding box after rotating an image using rotate_bboxes_helper', 'transform_bbox_after_perspective': 'build a module that transforms a bounding box after a perspective transform using perspective_transform_bboxes_helper'}
```

## File: facebookresearch_augly/augly/image/utils/metadata.py

Prompts

```
['create a function that renormalizes a bounding box after an image is cropped using crop_bboxes_helper', 'build a module that horizontally flips a normalized bounding box using hflip_bboxes_helper', 'build a module that vertically flips a normalized bounding box using vflip_bboxes_helper', 'create a function that computes the enclosing bounding box after rotating an image using rotate_bboxes_helper', 'build a module that transforms a bounding box after a perspective transform using perspective_transform_bboxes_helper', 'normalize a bounding box from pascal_voc, coco, or yolo format to normalized coordinates', 'validate and normalize a list of bounding boxes to normalized coordinates between 0 and 1', 'convert normalized bounding boxes back to pascal_voc, coco, or yolo format after augmentation', 'check transformed bounding boxes and return None for boxes cropped out or inverted after augmentation', 'transform bounding boxes to match an augmented image using a helper function and format conversion', 'create a python module that loads an image from a file path or validates a PIL Image object', 'build a python script that saves a PIL Image to disk with optional color mode conversion', 'create a function that computes the largest axis-aligned rectangle dimensions within a rotated rectangle', 'build a python module that resizes, pads with black, or crops an image to fit target dimensions', 'create a numpy binary mask with diagonal, horizontal, or vertical stripe patterns given width, angle, and density']
```

Usage

```
{'normalize_bbox': 'normalize a bounding box from pascal_voc, coco, or yolo format to normalized coordinates', 'validate_and_normalize_bboxes': 'validate and normalize a list of bounding boxes to normalized coordinates between 0 and 1', 'convert_bboxes': 'convert normalized bounding boxes back to pascal_voc, coco, or yolo format after augmentation', 'check_for_gone_bboxes': 'check transformed bounding boxes and return None for boxes cropped out or inverted after augmentation', 'transform_bboxes': 'transform bounding boxes to match an augmented image using a helper function and format conversion'}
```

## File: facebookresearch_augly/augly/image/utils/utils.py

Prompts

```
['create a function that renormalizes a bounding box after an image is cropped using crop_bboxes_helper', 'build a module that horizontally flips a normalized bounding box using hflip_bboxes_helper', 'build a module that vertically flips a normalized bounding box using vflip_bboxes_helper', 'create a function that computes the enclosing bounding box after rotating an image using rotate_bboxes_helper', 'build a module that transforms a bounding box after a perspective transform using perspective_transform_bboxes_helper', 'normalize a bounding box from pascal_voc, coco, or yolo format to normalized coordinates', 'validate and normalize a list of bounding boxes to normalized coordinates between 0 and 1', 'convert normalized bounding boxes back to pascal_voc, coco, or yolo format after augmentation', 'check transformed bounding boxes and return None for boxes cropped out or inverted after augmentation', 'transform bounding boxes to match an augmented image using a helper function and format conversion', 'create a python module that loads an image from a file path or validates a PIL Image object', 'build a python script that saves a PIL Image to disk with optional color mode conversion', 'create a function that computes the largest axis-aligned rectangle dimensions within a rotated rectangle', 'build a python module that resizes, pads with black, or crops an image to fit target dimensions', 'create a numpy binary mask with diagonal, horizontal, or vertical stripe patterns given width, angle, and density']
```

Usage

```
{'load_and_validate_image': 'create a python module that loads an image from a file path or validates a PIL Image object', 'save_image_with_mode_conversion': 'build a python script that saves a PIL Image to disk with optional color mode conversion', 'compute_rotated_rect_max_area': 'create a function that computes the largest axis-aligned rectangle dimensions within a rotated rectangle', 'resize_pad_or_crop_image': 'build a python module that resizes, pads with black, or crops an image to fit target dimensions', 'compute_stripe_mask': 'create a numpy binary mask with diagonal, horizontal, or vertical stripe patterns given width, angle, and density'}
```

