# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/datasets/pipelines/auto_augment.py

Prompts

```
['build an AutoAugment pipeline with multiple augmentation policies for object detection data augmentation', 'create a Shear transform to apply horizontal or vertical shear to images and bounding boxes', 'create a Rotate transform to rotate images, bboxes, masks and segmentation maps by a given angle', 'create a Translate transform to shift images and bounding boxes horizontally or vertically by an offset', 'create a ColorTransform to adjust image color, brightness, contrast, or equalize histogram for data augmentation', 'convert numpy arrays, sequences, ints, and floats to torch tensors using to_tensor', 'use the ToTensor pipeline class to convert specified result dict keys to torch tensors', 'use ImageToTensor to convert HWC images to CHW torch tensors with automatic dimension expansion', 'use DefaultFormatBundle to format img, gt_bboxes, gt_labels, gt_masks, and gt_semantic_seg fields', 'use Collect to gather specified keys and img_meta into a data dict for model input', 'create a pipeline that loads an image from disk and populates the results dict with image data and metadata', 'create a pipeline that adds image metadata to a results dict containing a preloaded webcam image', 'create a pipeline that loads multi-channel images from separate channel files and stacks them into a single array', 'create a pipeline that loads bounding boxes, labels, masks, and semantic segmentation annotations into the results dict', 'create a pipeline that filters out ground truth annotations with bounding boxes smaller than a minimum width and height', 'build a Resize transform to resize images with multi-scale mode and keep aspect ratio', 'build a RandomFlip transform to flip images horizontally or vertically with configurable probability', 'build a PhotoMetricDistortion transform to apply random brightness, contrast, saturation, and hue changes', 'build a RandomCrop transform to randomly crop images with absolute or relative crop size', 'build an Albu transform to apply Albumentations augmentations like ShiftScaleRotate and ChannelShuffle']
```

Usage

```
{'build_autoaugment_pipeline': 'build an AutoAugment pipeline with multiple augmentation policies for object detection data augmentation', 'create_shear_transform': 'create a Shear transform to apply horizontal or vertical shear to images and bounding boxes', 'create_rotate_transform': 'create a Rotate transform to rotate images, bboxes, masks and segmentation maps by a given angle', 'create_translate_transform': 'create a Translate transform to shift images and bounding boxes horizontally or vertically by an offset', 'create_color_transform': 'create a ColorTransform to adjust image color, brightness, contrast, or equalize histogram for data augmentation'}
```

## File: facebookresearch_generic-grouping/mmdet/datasets/pipelines/formating.py

Prompts

```
['build an AutoAugment pipeline with multiple augmentation policies for object detection data augmentation', 'create a Shear transform to apply horizontal or vertical shear to images and bounding boxes', 'create a Rotate transform to rotate images, bboxes, masks and segmentation maps by a given angle', 'create a Translate transform to shift images and bounding boxes horizontally or vertically by an offset', 'create a ColorTransform to adjust image color, brightness, contrast, or equalize histogram for data augmentation', 'convert numpy arrays, sequences, ints, and floats to torch tensors using to_tensor', 'use the ToTensor pipeline class to convert specified result dict keys to torch tensors', 'use ImageToTensor to convert HWC images to CHW torch tensors with automatic dimension expansion', 'use DefaultFormatBundle to format img, gt_bboxes, gt_labels, gt_masks, and gt_semantic_seg fields', 'use Collect to gather specified keys and img_meta into a data dict for model input', 'create a pipeline that loads an image from disk and populates the results dict with image data and metadata', 'create a pipeline that adds image metadata to a results dict containing a preloaded webcam image', 'create a pipeline that loads multi-channel images from separate channel files and stacks them into a single array', 'create a pipeline that loads bounding boxes, labels, masks, and semantic segmentation annotations into the results dict', 'create a pipeline that filters out ground truth annotations with bounding boxes smaller than a minimum width and height', 'build a Resize transform to resize images with multi-scale mode and keep aspect ratio', 'build a RandomFlip transform to flip images horizontally or vertically with configurable probability', 'build a PhotoMetricDistortion transform to apply random brightness, contrast, saturation, and hue changes', 'build a RandomCrop transform to randomly crop images with absolute or relative crop size', 'build an Albu transform to apply Albumentations augmentations like ShiftScaleRotate and ChannelShuffle']
```

Usage

```
{'convert_to_tensor': 'convert numpy arrays, sequences, ints, and floats to torch tensors using to_tensor', 'use_Tensor_pipeline': 'use the ToTensor pipeline class to convert specified result dict keys to torch tensors', 'convert_image_to_tensor': 'use ImageToTensor to convert HWC images to CHW torch tensors with automatic dimension expansion', 'format_detection_results': 'use DefaultFormatBundle to format img, gt_bboxes, gt_labels, gt_masks, and gt_semantic_seg fields', 'collect_pipeline_data': 'use Collect to gather specified keys and img_meta into a data dict for model input'}
```

## File: facebookresearch_generic-grouping/mmdet/datasets/pipelines/loading.py

Prompts

```
['build an AutoAugment pipeline with multiple augmentation policies for object detection data augmentation', 'create a Shear transform to apply horizontal or vertical shear to images and bounding boxes', 'create a Rotate transform to rotate images, bboxes, masks and segmentation maps by a given angle', 'create a Translate transform to shift images and bounding boxes horizontally or vertically by an offset', 'create a ColorTransform to adjust image color, brightness, contrast, or equalize histogram for data augmentation', 'convert numpy arrays, sequences, ints, and floats to torch tensors using to_tensor', 'use the ToTensor pipeline class to convert specified result dict keys to torch tensors', 'use ImageToTensor to convert HWC images to CHW torch tensors with automatic dimension expansion', 'use DefaultFormatBundle to format img, gt_bboxes, gt_labels, gt_masks, and gt_semantic_seg fields', 'use Collect to gather specified keys and img_meta into a data dict for model input', 'create a pipeline that loads an image from disk and populates the results dict with image data and metadata', 'create a pipeline that adds image metadata to a results dict containing a preloaded webcam image', 'create a pipeline that loads multi-channel images from separate channel files and stacks them into a single array', 'create a pipeline that loads bounding boxes, labels, masks, and semantic segmentation annotations into the results dict', 'create a pipeline that filters out ground truth annotations with bounding boxes smaller than a minimum width and height', 'build a Resize transform to resize images with multi-scale mode and keep aspect ratio', 'build a RandomFlip transform to flip images horizontally or vertically with configurable probability', 'build a PhotoMetricDistortion transform to apply random brightness, contrast, saturation, and hue changes', 'build a RandomCrop transform to randomly crop images with absolute or relative crop size', 'build an Albu transform to apply Albumentations augmentations like ShiftScaleRotate and ChannelShuffle']
```

Usage

```
{'load_image_from_file': 'create a pipeline that loads an image from disk and populates the results dict with image data and metadata', 'load_image_from_webcam': 'create a pipeline that adds image metadata to a results dict containing a preloaded webcam image', 'load_multichannel_image_from_files': 'create a pipeline that loads multi-channel images from separate channel files and stacks them into a single array', 'load_annotations': 'create a pipeline that loads bounding boxes, labels, masks, and semantic segmentation annotations into the results dict', 'filter_annotations': 'create a pipeline that filters out ground truth annotations with bounding boxes smaller than a minimum width and height'}
```

## File: facebookresearch_generic-grouping/mmdet/datasets/pipelines/transforms.py

Prompts

```
['build an AutoAugment pipeline with multiple augmentation policies for object detection data augmentation', 'create a Shear transform to apply horizontal or vertical shear to images and bounding boxes', 'create a Rotate transform to rotate images, bboxes, masks and segmentation maps by a given angle', 'create a Translate transform to shift images and bounding boxes horizontally or vertically by an offset', 'create a ColorTransform to adjust image color, brightness, contrast, or equalize histogram for data augmentation', 'convert numpy arrays, sequences, ints, and floats to torch tensors using to_tensor', 'use the ToTensor pipeline class to convert specified result dict keys to torch tensors', 'use ImageToTensor to convert HWC images to CHW torch tensors with automatic dimension expansion', 'use DefaultFormatBundle to format img, gt_bboxes, gt_labels, gt_masks, and gt_semantic_seg fields', 'use Collect to gather specified keys and img_meta into a data dict for model input', 'create a pipeline that loads an image from disk and populates the results dict with image data and metadata', 'create a pipeline that adds image metadata to a results dict containing a preloaded webcam image', 'create a pipeline that loads multi-channel images from separate channel files and stacks them into a single array', 'create a pipeline that loads bounding boxes, labels, masks, and semantic segmentation annotations into the results dict', 'create a pipeline that filters out ground truth annotations with bounding boxes smaller than a minimum width and height', 'build a Resize transform to resize images with multi-scale mode and keep aspect ratio', 'build a RandomFlip transform to flip images horizontally or vertically with configurable probability', 'build a PhotoMetricDistortion transform to apply random brightness, contrast, saturation, and hue changes', 'build a RandomCrop transform to randomly crop images with absolute or relative crop size', 'build an Albu transform to apply Albumentations augmentations like ShiftScaleRotate and ChannelShuffle']
```

Usage

```
{'build_resize_pipeline': 'build a Resize transform to resize images with multi-scale mode and keep aspect ratio', 'build_randomflip_pipeline': 'build a RandomFlip transform to flip images horizontally or vertically with configurable probability', 'build_photometricdistortion_pipeline': 'build a PhotoMetricDistortion transform to apply random brightness, contrast, saturation, and hue changes', 'build_randomcrop_pipeline': 'build a RandomCrop transform to randomly crop images with absolute or relative crop size', 'build_albu_pipeline': 'build an Albu transform to apply Albumentations augmentations like ShiftScaleRotate and ChannelShuffle'}
```

