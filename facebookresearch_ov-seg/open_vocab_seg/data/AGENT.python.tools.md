# Agent Python Tools

- repo: facebookresearch/ov-seg
- repo_uri: https://github.com/facebookresearch/ov-seg

## File: facebookresearch_ov-seg/open_vocab_seg/data/augmentations.py

Prompts

```
['create a function that computes the bounding box from a binary segmentation mask', 'create a function that expands a bounding box by a given ratio with image boundary clamping', 'create a detectron2 augmentation that crops an image around a semantic segmentation mask region', 'create a detectron2 augmentation that crops an image around a given bounding box with expand ratio', 'create a detectron2 augmentation that performs random resized crop with configurable scale and aspect ratio', 'build a detection training dataloader with configurable sampler, mapper, and batch size for object detection models', 'build a detection test dataloader with inference sampler and configurable samples per GPU for evaluation', 'load and prepare dataset dicts for detection or segmentation with optional filtering and proposal files', 'print a histogram table showing the distribution of classification instances across all categories', 'wrap dataset dicts with metadata kwargs assigning extra attributes to each sample in the dataset']
```

Usage

```
{'create_mask2box': 'create a function that computes the bounding box from a binary segmentation mask', 'create_expand_box': 'create a function that expands a bounding box by a given ratio with image boundary clamping', 'create_CropImageWithMask': 'create a detectron2 augmentation that crops an image around a semantic segmentation mask region', 'create_CropImageWithBox': 'create a detectron2 augmentation that crops an image around a given bounding box with expand ratio', 'create_RandomResizedCrop': 'create a detectron2 augmentation that performs random resized crop with configurable scale and aspect ratio'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/data/build.py

Prompts

```
['create a function that computes the bounding box from a binary segmentation mask', 'create a function that expands a bounding box by a given ratio with image boundary clamping', 'create a detectron2 augmentation that crops an image around a semantic segmentation mask region', 'create a detectron2 augmentation that crops an image around a given bounding box with expand ratio', 'create a detectron2 augmentation that performs random resized crop with configurable scale and aspect ratio', 'build a detection training dataloader with configurable sampler, mapper, and batch size for object detection models', 'build a detection test dataloader with inference sampler and configurable samples per GPU for evaluation', 'load and prepare dataset dicts for detection or segmentation with optional filtering and proposal files', 'print a histogram table showing the distribution of classification instances across all categories', 'wrap dataset dicts with metadata kwargs assigning extra attributes to each sample in the dataset']
```

Usage

```
{'build_detection_train_loader': 'build a detection training dataloader with configurable sampler, mapper, and batch size for object detection models', 'build_detection_test_loader': 'build a detection test dataloader with inference sampler and configurable samples per GPU for evaluation', 'get_detection_dataset_dicts': 'load and prepare dataset dicts for detection or segmentation with optional filtering and proposal files', 'print_classification_instances_class_histogram': 'print a histogram table showing the distribution of classification instances across all categories', 'wrap_metas': 'wrap dataset dicts with metadata kwargs assigning extra attributes to each sample in the dataset'}
```

