# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/third_party/CenterNet2/centernet/data/custom_build_augmentation.py

Prompts

```
['build a Detectron2 augmentation list using ResizeShortestEdge from config for training or testing', 'build a Detectron2 augmentation list using EfficientDetResizeCrop with configurable scale and size from config', 'use the build_custom_transform_gen alias to create augmentation pipelines for backward compatibility', 'review the build_custom_augmentation function to understand how it selects ResizeShortestEdge or EfficientDetResizeCrop based on config', 'refactor build_custom_augmentation to add or remove RandomFlip augmentation for training pipelines', 'build a custom training data loader with configurable samplers for Detectron2 object detection datasets', 'create a class-aware sampler that weights images by inverse category frequency for balanced training', 'create a multi-dataset sampler that samples from multiple datasets with configurable ratio weights', 'get detection dataset dicts annotated with a dataset_source ID for multi-dataset training', 'review the ClassAwareSampler method that computes per-image sampling weights from category frequency']
```

Usage

```
{'build_augmentation_resize_shortest_edge': 'build a Detectron2 augmentation list using ResizeShortestEdge from config for training or testing', 'build_augmentation_efficientdet_resize_crop': 'build a Detectron2 augmentation list using EfficientDetResizeCrop with configurable scale and size from config', 'build_transform_gen_alias': 'use the build_custom_transform_gen alias to create augmentation pipelines for backward compatibility', 'review_build_custom_augmentation': 'review the build_custom_augmentation function to understand how it selects ResizeShortestEdge or EfficientDetResizeCrop based on config', 'refactor_augmentation_random_flip': 'refactor build_custom_augmentation to add or remove RandomFlip augmentation for training pipelines'}
```

## File: facebookresearch_detic/third_party/CenterNet2/centernet/data/custom_dataset_dataloader.py

Prompts

```
['build a Detectron2 augmentation list using ResizeShortestEdge from config for training or testing', 'build a Detectron2 augmentation list using EfficientDetResizeCrop with configurable scale and size from config', 'use the build_custom_transform_gen alias to create augmentation pipelines for backward compatibility', 'review the build_custom_augmentation function to understand how it selects ResizeShortestEdge or EfficientDetResizeCrop based on config', 'refactor build_custom_augmentation to add or remove RandomFlip augmentation for training pipelines', 'build a custom training data loader with configurable samplers for Detectron2 object detection datasets', 'create a class-aware sampler that weights images by inverse category frequency for balanced training', 'create a multi-dataset sampler that samples from multiple datasets with configurable ratio weights', 'get detection dataset dicts annotated with a dataset_source ID for multi-dataset training', 'review the ClassAwareSampler method that computes per-image sampling weights from category frequency']
```

Usage

```
{'build_custom_train_loader': 'build a custom training data loader with configurable samplers for Detectron2 object detection datasets', 'create_ClassAwareSampler': 'create a class-aware sampler that weights images by inverse category frequency for balanced training', 'create_MultiDatasetSampler': 'create a multi-dataset sampler that samples from multiple datasets with configurable ratio weights', 'get_detection_dataset_dicts_with_source': 'get detection dataset dicts annotated with a dataset_source ID for multi-dataset training', 'review_ClassAwareSampler_get_class_balance_factor': 'review the ClassAwareSampler method that computes per-image sampling weights from category frequency'}
```

