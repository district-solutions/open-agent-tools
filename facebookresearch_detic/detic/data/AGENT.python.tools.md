# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/detic/data/custom_build_augmentation.py

Prompts

```
['build a list of augmentations using ResizeShortestEdge strategy from a detectron2 config object', 'build a list of augmentations using EfficientDetResizeCrop strategy from a detectron2 config object', 'build training augmentations that include resizing and random flip from config settings', 'build test augmentations with fixed resize and no random flip from config settings', 'review the build_custom_augmentation function to understand ResizeShortestEdge and EfficientDetResizeCrop augmentation logic', 'build a custom training data loader with multi-dataset support and configurable samplers for detectron2', 'build a multi-dataset batch data loader that groups samples by dataset source and aspect ratio', 'get detection dataset dicts annotated with a dataset_source id for each sample across multiple datasets', 'create a MultiDatasetSampler that samples from multiple datasets with configurable ratios and repeat factor sampling', 'compute repeat factors for dataset dicts based on tag frequency to oversample rare categories', 'build a CustomDatasetMapper instance from a Detectron2 config with image label and tar dataset support', 'create a CustomDatasetMapper for training with annotation types, tar dataset, and debug mode enabled', 'run the CustomDatasetMapper call method to transform a dataset dict with augmentations and annotations', 'build a DetrDatasetMapper instance with optional cropping and transform generators for DETR training', 'run the DetrDatasetMapper call method to map a dataset dict into DETR format with transforms', 'create a DiskTarDataset from tar file paths and index directory for ImageNet-21k data loading', 'get an image, label, and index from a DiskTarDataset by providing a sample index', 'create a _TarDataset to load individual tar files with optional preloading via memory mapping', 'load precomputed names and offsets numpy arrays from the tar index directory for a tar file', 'get raw image bytes from a tar file by index with automatic gzip decompression support']
```

Usage

```
{'build_augmentation_resize_shortest_edge': 'build a list of augmentations using ResizeShortestEdge strategy from a detectron2 config object', 'build_augmentation_efficientdet_resize_crop': 'build a list of augmentations using EfficientDetResizeCrop strategy from a detectron2 config object', 'build_train_augmentation_with_flip': 'build training augmentations that include resizing and random flip from config settings', 'build_test_augmentation_without_flip': 'build test augmentations with fixed resize and no random flip from config settings', 'review_build_custom_augmentation': 'review the build_custom_augmentation function to understand ResizeShortestEdge and EfficientDetResizeCrop augmentation logic'}
```

## File: facebookresearch_detic/detic/data/custom_dataset_dataloader.py

Prompts

```
['build a list of augmentations using ResizeShortestEdge strategy from a detectron2 config object', 'build a list of augmentations using EfficientDetResizeCrop strategy from a detectron2 config object', 'build training augmentations that include resizing and random flip from config settings', 'build test augmentations with fixed resize and no random flip from config settings', 'review the build_custom_augmentation function to understand ResizeShortestEdge and EfficientDetResizeCrop augmentation logic', 'build a custom training data loader with multi-dataset support and configurable samplers for detectron2', 'build a multi-dataset batch data loader that groups samples by dataset source and aspect ratio', 'get detection dataset dicts annotated with a dataset_source id for each sample across multiple datasets', 'create a MultiDatasetSampler that samples from multiple datasets with configurable ratios and repeat factor sampling', 'compute repeat factors for dataset dicts based on tag frequency to oversample rare categories', 'build a CustomDatasetMapper instance from a Detectron2 config with image label and tar dataset support', 'create a CustomDatasetMapper for training with annotation types, tar dataset, and debug mode enabled', 'run the CustomDatasetMapper call method to transform a dataset dict with augmentations and annotations', 'build a DetrDatasetMapper instance with optional cropping and transform generators for DETR training', 'run the DetrDatasetMapper call method to map a dataset dict into DETR format with transforms', 'create a DiskTarDataset from tar file paths and index directory for ImageNet-21k data loading', 'get an image, label, and index from a DiskTarDataset by providing a sample index', 'create a _TarDataset to load individual tar files with optional preloading via memory mapping', 'load precomputed names and offsets numpy arrays from the tar index directory for a tar file', 'get raw image bytes from a tar file by index with automatic gzip decompression support']
```

Usage

```
{'build_custom_train_loader': 'build a custom training data loader with multi-dataset support and configurable samplers for detectron2', 'build_multi_dataset_batch_data_loader': 'build a multi-dataset batch data loader that groups samples by dataset source and aspect ratio', 'get_detection_dataset_dicts_with_source': 'get detection dataset dicts annotated with a dataset_source id for each sample across multiple datasets', 'MultiDatasetSampler': 'create a MultiDatasetSampler that samples from multiple datasets with configurable ratios and repeat factor sampling', 'repeat_factors_from_tag_frequency': 'compute repeat factors for dataset dicts based on tag frequency to oversample rare categories'}
```

## File: facebookresearch_detic/detic/data/custom_dataset_mapper.py

Prompts

```
['build a list of augmentations using ResizeShortestEdge strategy from a detectron2 config object', 'build a list of augmentations using EfficientDetResizeCrop strategy from a detectron2 config object', 'build training augmentations that include resizing and random flip from config settings', 'build test augmentations with fixed resize and no random flip from config settings', 'review the build_custom_augmentation function to understand ResizeShortestEdge and EfficientDetResizeCrop augmentation logic', 'build a custom training data loader with multi-dataset support and configurable samplers for detectron2', 'build a multi-dataset batch data loader that groups samples by dataset source and aspect ratio', 'get detection dataset dicts annotated with a dataset_source id for each sample across multiple datasets', 'create a MultiDatasetSampler that samples from multiple datasets with configurable ratios and repeat factor sampling', 'compute repeat factors for dataset dicts based on tag frequency to oversample rare categories', 'build a CustomDatasetMapper instance from a Detectron2 config with image label and tar dataset support', 'create a CustomDatasetMapper for training with annotation types, tar dataset, and debug mode enabled', 'run the CustomDatasetMapper call method to transform a dataset dict with augmentations and annotations', 'build a DetrDatasetMapper instance with optional cropping and transform generators for DETR training', 'run the DetrDatasetMapper call method to map a dataset dict into DETR format with transforms', 'create a DiskTarDataset from tar file paths and index directory for ImageNet-21k data loading', 'get an image, label, and index from a DiskTarDataset by providing a sample index', 'create a _TarDataset to load individual tar files with optional preloading via memory mapping', 'load precomputed names and offsets numpy arrays from the tar index directory for a tar file', 'get raw image bytes from a tar file by index with automatic gzip decompression support']
```

Usage

```
{'build_CustomDatasetMapper_from_config': 'build a CustomDatasetMapper instance from a Detectron2 config with image label and tar dataset support', 'create_CustomDatasetMapper_for_training': 'create a CustomDatasetMapper for training with annotation types, tar dataset, and debug mode enabled', 'run_CustomDatasetMapper_call': 'run the CustomDatasetMapper call method to transform a dataset dict with augmentations and annotations', 'build_DetrDatasetMapper_for_training': 'build a DetrDatasetMapper instance with optional cropping and transform generators for DETR training', 'run_DetrDatasetMapper_call': 'run the DetrDatasetMapper call method to map a dataset dict into DETR format with transforms'}
```

## File: facebookresearch_detic/detic/data/tar_dataset.py

Prompts

```
['build a list of augmentations using ResizeShortestEdge strategy from a detectron2 config object', 'build a list of augmentations using EfficientDetResizeCrop strategy from a detectron2 config object', 'build training augmentations that include resizing and random flip from config settings', 'build test augmentations with fixed resize and no random flip from config settings', 'review the build_custom_augmentation function to understand ResizeShortestEdge and EfficientDetResizeCrop augmentation logic', 'build a custom training data loader with multi-dataset support and configurable samplers for detectron2', 'build a multi-dataset batch data loader that groups samples by dataset source and aspect ratio', 'get detection dataset dicts annotated with a dataset_source id for each sample across multiple datasets', 'create a MultiDatasetSampler that samples from multiple datasets with configurable ratios and repeat factor sampling', 'compute repeat factors for dataset dicts based on tag frequency to oversample rare categories', 'build a CustomDatasetMapper instance from a Detectron2 config with image label and tar dataset support', 'create a CustomDatasetMapper for training with annotation types, tar dataset, and debug mode enabled', 'run the CustomDatasetMapper call method to transform a dataset dict with augmentations and annotations', 'build a DetrDatasetMapper instance with optional cropping and transform generators for DETR training', 'run the DetrDatasetMapper call method to map a dataset dict into DETR format with transforms', 'create a DiskTarDataset from tar file paths and index directory for ImageNet-21k data loading', 'get an image, label, and index from a DiskTarDataset by providing a sample index', 'create a _TarDataset to load individual tar files with optional preloading via memory mapping', 'load precomputed names and offsets numpy arrays from the tar index directory for a tar file', 'get raw image bytes from a tar file by index with automatic gzip decompression support']
```

Usage

```
{'create_disktar_dataset': 'create a DiskTarDataset from tar file paths and index directory for ImageNet-21k data loading', 'getitem_disktar_dataset': 'get an image, label, and index from a DiskTarDataset by providing a sample index', 'create_tar_dataset': 'create a _TarDataset to load individual tar files with optional preloading via memory mapping', 'load_tar_index': 'load precomputed names and offsets numpy arrays from the tar index directory for a tar file', 'getitem_tar_dataset': 'get raw image bytes from a tar file by index with automatic gzip decompression support'}
```

