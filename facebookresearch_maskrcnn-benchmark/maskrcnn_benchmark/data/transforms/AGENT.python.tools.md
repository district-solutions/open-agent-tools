# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/data/transforms/build.py

Prompts

```
['build a transforms pipeline for training with color jitter, resize, flip, and normalization from config', 'build a transforms pipeline for testing with resize, to tensor, and normalization from config', 'review the build_transforms function to understand how it composes augmentation transforms from a config object', 'refactor build_transforms to support additional augmentation transforms like random crop or rotation', 'summarize the build_transforms function that creates a Compose pipeline with Resize, Flip, ColorJitter, and Normalize', 'build a Compose pipeline that chains Resize, RandomHorizontalFlip, and Normalize transforms for image and target', 'create a Resize transform that resizes images to a random min_size while respecting max_size', 'create a RandomHorizontalFlip or RandomVerticalFlip transform to augment images and transpose targets', 'create a ColorJitter transform to randomly adjust brightness, contrast, saturation, and hue of images', 'create a Normalize transform that converts BGR to RGB, scales to 255, and normalizes with mean and std']
```

Usage

```
{'build_transforms_train': 'build a transforms pipeline for training with color jitter, resize, flip, and normalization from config', 'build_transforms_test': 'build a transforms pipeline for testing with resize, to tensor, and normalization from config', 'review_build_transforms': 'review the build_transforms function to understand how it composes augmentation transforms from a config object', 'refactor_build_transforms': 'refactor build_transforms to support additional augmentation transforms like random crop or rotation', 'summarize_build_transforms': 'summarize the build_transforms function that creates a Compose pipeline with Resize, Flip, ColorJitter, and Normalize'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/data/transforms/transforms.py

Prompts

```
['build a transforms pipeline for training with color jitter, resize, flip, and normalization from config', 'build a transforms pipeline for testing with resize, to tensor, and normalization from config', 'review the build_transforms function to understand how it composes augmentation transforms from a config object', 'refactor build_transforms to support additional augmentation transforms like random crop or rotation', 'summarize the build_transforms function that creates a Compose pipeline with Resize, Flip, ColorJitter, and Normalize', 'build a Compose pipeline that chains Resize, RandomHorizontalFlip, and Normalize transforms for image and target', 'create a Resize transform that resizes images to a random min_size while respecting max_size', 'create a RandomHorizontalFlip or RandomVerticalFlip transform to augment images and transpose targets', 'create a ColorJitter transform to randomly adjust brightness, contrast, saturation, and hue of images', 'create a Normalize transform that converts BGR to RGB, scales to 255, and normalizes with mean and std']
```

Usage

```
{'build_compose_transform_pipeline': 'build a Compose pipeline that chains Resize, RandomHorizontalFlip, and Normalize transforms for image and target', 'create_resize_transform': 'create a Resize transform that resizes images to a random min_size while respecting max_size', 'create_flip_augmentation': 'create a RandomHorizontalFlip or RandomVerticalFlip transform to augment images and transpose targets', 'create_color_jitter_transform': 'create a ColorJitter transform to randomly adjust brightness, contrast, saturation, and hue of images', 'create_normalize_transform': 'create a Normalize transform that converts BGR to RGB, scales to 255, and normalizes with mean and std'}
```

