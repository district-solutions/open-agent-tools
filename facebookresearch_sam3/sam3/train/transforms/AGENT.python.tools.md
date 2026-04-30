# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/train/transforms/basic.py

Prompts

```
['create a RandomCrop transform that crops images to a specified size while adjusting bounding boxes and masks', 'build a RandomResize transform that randomly rescales images from a set of sizes with optional max size constraint', 'test the Normalize transform that converts bounding boxes to center-x-y-wh format and normalizes image pixel values', 'refactor the Compose class to chain multiple image and target transforms into a single pipeline', 'review the RandomHorizontalFlip transform that flips images and adjusts bounding boxes, masks, and text directions', 'create a data augmentation pipeline using RandomResizeAPI, RandomSizeCropAPI, and NormalizeAPI for SAM3 training', 'build a RandomSizeCropAPI transform that crops images while respecting bounding boxes and input points', 'run RandomHorizontalFlip with consistent_transform to apply the same flip across all frames in a video', 'test LargeScaleJitter transform with configurable scale range, aspect ratio, and crop size for data augmentation', 'summarize NormalizeAPI which converts bounding boxes to center-x-y-wh format and normalizes coordinates', 'filter find queries in a datapoint by excluding specific query text keys', 'keep at most N find queries per datapoint, optionally retaining positive queries', 'filter and remap find queries, objects, and images in a SAM3 datapoint', 'transform text-based find queries into visual queries using bounding box prompts', 'add prefix or suffix strings to find query text with optional conditional filtering', 'sample points from a COCO RLE-encoded mask using centered, random_mask, or random_box mode', 'sample points from a binary mask using centered, random_mask, or random_box sampling mode', 'sample points farthest from mask edges and each other using distance transform', 'sample positive points uniformly from a binary mask at integer pixel coordinates', 'add Gaussian noise to an annotation box while clamping to image bounds and minimum area']
```

Usage

```
{'create_transform_random_crop': 'create a RandomCrop transform that crops images to a specified size while adjusting bounding boxes and masks', 'build_transform_random_resize': 'build a RandomResize transform that randomly rescales images from a set of sizes with optional max size constraint', 'test_transform_normalize': 'test the Normalize transform that converts bounding boxes to center-x-y-wh format and normalizes image pixel values', 'refactor_transform_compose': 'refactor the Compose class to chain multiple image and target transforms into a single pipeline', 'review_transform_random_horizontal_flip': 'review the RandomHorizontalFlip transform that flips images and adjusts bounding boxes, masks, and text directions'}
```

## File: facebookresearch_sam3/sam3/train/transforms/basic_for_api.py

Prompts

```
['create a RandomCrop transform that crops images to a specified size while adjusting bounding boxes and masks', 'build a RandomResize transform that randomly rescales images from a set of sizes with optional max size constraint', 'test the Normalize transform that converts bounding boxes to center-x-y-wh format and normalizes image pixel values', 'refactor the Compose class to chain multiple image and target transforms into a single pipeline', 'review the RandomHorizontalFlip transform that flips images and adjusts bounding boxes, masks, and text directions', 'create a data augmentation pipeline using RandomResizeAPI, RandomSizeCropAPI, and NormalizeAPI for SAM3 training', 'build a RandomSizeCropAPI transform that crops images while respecting bounding boxes and input points', 'run RandomHorizontalFlip with consistent_transform to apply the same flip across all frames in a video', 'test LargeScaleJitter transform with configurable scale range, aspect ratio, and crop size for data augmentation', 'summarize NormalizeAPI which converts bounding boxes to center-x-y-wh format and normalizes coordinates', 'filter find queries in a datapoint by excluding specific query text keys', 'keep at most N find queries per datapoint, optionally retaining positive queries', 'filter and remap find queries, objects, and images in a SAM3 datapoint', 'transform text-based find queries into visual queries using bounding box prompts', 'add prefix or suffix strings to find query text with optional conditional filtering', 'sample points from a COCO RLE-encoded mask using centered, random_mask, or random_box mode', 'sample points from a binary mask using centered, random_mask, or random_box sampling mode', 'sample points farthest from mask edges and each other using distance transform', 'sample positive points uniformly from a binary mask at integer pixel coordinates', 'add Gaussian noise to an annotation box while clamping to image bounds and minimum area']
```

Usage

```
{'create_transforms_pipeline': 'create a data augmentation pipeline using RandomResizeAPI, RandomSizeCropAPI, and NormalizeAPI for SAM3 training', 'build_random_size_crop': 'build a RandomSizeCropAPI transform that crops images while respecting bounding boxes and input points', 'run_random_horizontal_flip': 'run RandomHorizontalFlip with consistent_transform to apply the same flip across all frames in a video', 'test_large_scale_jitter': 'test LargeScaleJitter transform with configurable scale range, aspect ratio, and crop size for data augmentation', 'summarize_normalize_api': 'summarize NormalizeAPI which converts bounding boxes to center-x-y-wh format and normalizes coordinates'}
```

## File: facebookresearch_sam3/sam3/train/transforms/filter_query_transforms.py

Prompts

```
['create a RandomCrop transform that crops images to a specified size while adjusting bounding boxes and masks', 'build a RandomResize transform that randomly rescales images from a set of sizes with optional max size constraint', 'test the Normalize transform that converts bounding boxes to center-x-y-wh format and normalizes image pixel values', 'refactor the Compose class to chain multiple image and target transforms into a single pipeline', 'review the RandomHorizontalFlip transform that flips images and adjusts bounding boxes, masks, and text directions', 'create a data augmentation pipeline using RandomResizeAPI, RandomSizeCropAPI, and NormalizeAPI for SAM3 training', 'build a RandomSizeCropAPI transform that crops images while respecting bounding boxes and input points', 'run RandomHorizontalFlip with consistent_transform to apply the same flip across all frames in a video', 'test LargeScaleJitter transform with configurable scale range, aspect ratio, and crop size for data augmentation', 'summarize NormalizeAPI which converts bounding boxes to center-x-y-wh format and normalizes coordinates', 'filter find queries in a datapoint by excluding specific query text keys', 'keep at most N find queries per datapoint, optionally retaining positive queries', 'filter and remap find queries, objects, and images in a SAM3 datapoint', 'transform text-based find queries into visual queries using bounding box prompts', 'add prefix or suffix strings to find query text with optional conditional filtering', 'sample points from a COCO RLE-encoded mask using centered, random_mask, or random_box mode', 'sample points from a binary mask using centered, random_mask, or random_box sampling mode', 'sample points farthest from mask edges and each other using distance transform', 'sample positive points uniformly from a binary mask at integer pixel coordinates', 'add Gaussian noise to an annotation box while clamping to image bounds and minimum area']
```

Usage

```
{'filter_find_queries_by_text': 'filter find queries in a datapoint by excluding specific query text keys', 'keep_max_num_find_queries': 'keep at most N find queries per datapoint, optionally retaining positive queries', 'filter_datapoint_queries': 'filter and remap find queries, objects, and images in a SAM3 datapoint', 'transform_text_query_to_visual': 'transform text-based find queries into visual queries using bounding box prompts', 'add_prefix_suffix_to_find_text': 'add prefix or suffix strings to find query text with optional conditional filtering'}
```

## File: facebookresearch_sam3/sam3/train/transforms/point_sampling.py

Prompts

```
['create a RandomCrop transform that crops images to a specified size while adjusting bounding boxes and masks', 'build a RandomResize transform that randomly rescales images from a set of sizes with optional max size constraint', 'test the Normalize transform that converts bounding boxes to center-x-y-wh format and normalizes image pixel values', 'refactor the Compose class to chain multiple image and target transforms into a single pipeline', 'review the RandomHorizontalFlip transform that flips images and adjusts bounding boxes, masks, and text directions', 'create a data augmentation pipeline using RandomResizeAPI, RandomSizeCropAPI, and NormalizeAPI for SAM3 training', 'build a RandomSizeCropAPI transform that crops images while respecting bounding boxes and input points', 'run RandomHorizontalFlip with consistent_transform to apply the same flip across all frames in a video', 'test LargeScaleJitter transform with configurable scale range, aspect ratio, and crop size for data augmentation', 'summarize NormalizeAPI which converts bounding boxes to center-x-y-wh format and normalizes coordinates', 'filter find queries in a datapoint by excluding specific query text keys', 'keep at most N find queries per datapoint, optionally retaining positive queries', 'filter and remap find queries, objects, and images in a SAM3 datapoint', 'transform text-based find queries into visual queries using bounding box prompts', 'add prefix or suffix strings to find query text with optional conditional filtering', 'sample points from a COCO RLE-encoded mask using centered, random_mask, or random_box mode', 'sample points from a binary mask using centered, random_mask, or random_box sampling mode', 'sample points farthest from mask edges and each other using distance transform', 'sample positive points uniformly from a binary mask at integer pixel coordinates', 'add Gaussian noise to an annotation box while clamping to image bounds and minimum area']
```

Usage

```
{'sample_points_from_rle': 'sample points from a COCO RLE-encoded mask using centered, random_mask, or random_box mode', 'sample_points_from_mask': 'sample points from a binary mask using centered, random_mask, or random_box sampling mode', 'center_positive_sample': 'sample points farthest from mask edges and each other using distance transform', 'uniform_positive_sample': 'sample positive points uniformly from a binary mask at integer pixel coordinates', 'noise_box': 'add Gaussian noise to an annotation box while clamping to image bounds and minimum area'}
```

