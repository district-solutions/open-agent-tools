# Agent Python Tools

- repo: facebookresearch/perceptionmodels
- repo_uri: https://github.com/facebookresearch/perception_models

## File: facebookresearch_perceptionmodels/core/transforms/image_transform.py

Prompts

```
['create an ImageTransform that resizes a PIL image to a fixed size and normalizes it', 'create a VariableSizeImageTransform that dynamically tiles an image into chunks based on aspect ratio', 'get an image transform by vision input type returning either vanilla or thumb+tile transform', 'review the ImageTransform call method that resizes, converts to tensor, and normalizes a PIL image', 'review the VariableSizeImageTransform call method that splits an image into tiles and optionally adds a thumbnail', 'create a RegionTransform instance to normalize bounding box regions and replace bbox tokens in conversation text', 'build a region transform that converts xywh bounding boxes to normalized xyxy format with 3-digit coordinate encoding', 'format a list of normalized bounding box coordinates into a zero-padded string representation', 'transform conversation text by replacing bbox placeholder tokens with their corresponding formatted region strings', 'get a configured RegionTransform instance using the factory function with custom region format and coordinate settings', 'build a python module to create a VideoTransform instance with a specified image resolution and normalization', 'build a python module to transform video frames by loading, sampling, and normalizing frames from a video file', 'build a python module to load a video and extract uniformly sampled frames within a time range', 'build a python module to draw red bounding boxes on selected video frames from a tensor', 'build a python module to uniformly sample n indices from a range of m positions']
```

Usage

```
{'create_image_transform': 'create an ImageTransform that resizes a PIL image to a fixed size and normalizes it', 'create_variable_size_transform': 'create a VariableSizeImageTransform that dynamically tiles an image into chunks based on aspect ratio', 'get_image_transform': 'get an image transform by vision input type returning either vanilla or thumb+tile transform', 'review_ImageTransform_call': 'review the ImageTransform call method that resizes, converts to tensor, and normalizes a PIL image', 'review_VariableSizeImageTransform_call': 'review the VariableSizeImageTransform call method that splits an image into tiles and optionally adds a thumbnail'}
```

## File: facebookresearch_perceptionmodels/core/transforms/region_transform.py

Prompts

```
['create an ImageTransform that resizes a PIL image to a fixed size and normalizes it', 'create a VariableSizeImageTransform that dynamically tiles an image into chunks based on aspect ratio', 'get an image transform by vision input type returning either vanilla or thumb+tile transform', 'review the ImageTransform call method that resizes, converts to tensor, and normalizes a PIL image', 'review the VariableSizeImageTransform call method that splits an image into tiles and optionally adds a thumbnail', 'create a RegionTransform instance to normalize bounding box regions and replace bbox tokens in conversation text', 'build a region transform that converts xywh bounding boxes to normalized xyxy format with 3-digit coordinate encoding', 'format a list of normalized bounding box coordinates into a zero-padded string representation', 'transform conversation text by replacing bbox placeholder tokens with their corresponding formatted region strings', 'get a configured RegionTransform instance using the factory function with custom region format and coordinate settings', 'build a python module to create a VideoTransform instance with a specified image resolution and normalization', 'build a python module to transform video frames by loading, sampling, and normalizing frames from a video file', 'build a python module to load a video and extract uniformly sampled frames within a time range', 'build a python module to draw red bounding boxes on selected video frames from a tensor', 'build a python module to uniformly sample n indices from a range of m positions']
```

Usage

```
{'create_region_transform': 'create a RegionTransform instance to normalize bounding box regions and replace bbox tokens in conversation text', 'build_bbox_transform': 'build a region transform that converts xywh bounding boxes to normalized xyxy format with 3-digit coordinate encoding', 'format_bounding_box': 'format a list of normalized bounding box coordinates into a zero-padded string representation', 'transform_conv_regions': 'transform conversation text by replacing bbox placeholder tokens with their corresponding formatted region strings', 'get_region_transform': 'get a configured RegionTransform instance using the factory function with custom region format and coordinate settings'}
```

## File: facebookresearch_perceptionmodels/core/transforms/video_transform.py

Prompts

```
['create an ImageTransform that resizes a PIL image to a fixed size and normalizes it', 'create a VariableSizeImageTransform that dynamically tiles an image into chunks based on aspect ratio', 'get an image transform by vision input type returning either vanilla or thumb+tile transform', 'review the ImageTransform call method that resizes, converts to tensor, and normalizes a PIL image', 'review the VariableSizeImageTransform call method that splits an image into tiles and optionally adds a thumbnail', 'create a RegionTransform instance to normalize bounding box regions and replace bbox tokens in conversation text', 'build a region transform that converts xywh bounding boxes to normalized xyxy format with 3-digit coordinate encoding', 'format a list of normalized bounding box coordinates into a zero-padded string representation', 'transform conversation text by replacing bbox placeholder tokens with their corresponding formatted region strings', 'get a configured RegionTransform instance using the factory function with custom region format and coordinate settings', 'build a python module to create a VideoTransform instance with a specified image resolution and normalization', 'build a python module to transform video frames by loading, sampling, and normalizing frames from a video file', 'build a python module to load a video and extract uniformly sampled frames within a time range', 'build a python module to draw red bounding boxes on selected video frames from a tensor', 'build a python module to uniformly sample n indices from a range of m positions']
```

Usage

```
{'get_video_transform': 'build a python module to create a VideoTransform instance with a specified image resolution and normalization', 'VideoTransform_call': 'build a python module to transform video frames by loading, sampling, and normalizing frames from a video file', 'VideoTransform_load_video': 'build a python module to load a video and extract uniformly sampled frames within a time range', 'VideoTransform_draw_bounding_boxes': 'build a python module to draw red bounding boxes on selected video frames from a tensor', 'VideoTransform_uniform_sample': 'build a python module to uniformly sample n indices from a range of m positions'}
```

