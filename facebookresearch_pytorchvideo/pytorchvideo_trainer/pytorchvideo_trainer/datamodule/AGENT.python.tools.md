# Agent Python Tools

- repo: facebookresearch/pytorchvideo
- repo_uri: https://github.com/facebookresearch/pytorchvideo

## File: facebookresearch_pytorchvideo/pytorchvideo_trainer/pytorchvideo_trainer/datamodule/collators.py

Prompts

```
['build a collator function by name using build_collator_from_name to get a collator callable from the registry', 'collate a batch of multi-sample dictionaries using multiple_samples_collate for repeated augmentation data', 'register a custom collator function in the _COLLATORS dictionary for use with build_collator_from_name', 'review the multiple_samples_collate function to understand how it flattens and collates multi-sample batches', 'test build_collator_from_name with valid and invalid names to verify collator lookup and error handling', 'create a PyTorchVideoDataModule instance with dataloader and transforms config for video classification training', 'setup the PyTorchVideoDataModule datasets for train, val, or test phases using the setup method', 'get the train DataLoader from PyTorchVideoDataModule with distributed sampler epoch support for video data', 'build a DataLoaderConf dataclass with train, val, and test PhaseDataLoaderConf settings for each phase', 'register the VideoClassificationDataModuleConf schema in Hydra ConfigStore for video classification data module configuration', 'build a composed video transform pipeline from a list of Hydra config objects', 'build a single transform from a Hydra config object with nested transform composition', 'apply a transform to each item in a list stored under a dictionary key', 'create a SlowFast pathway transform that splits video frames into slow and fast clips', 'create a color jitter transform with blur and grayscale for self-supervised learning video augmentation']
```

Usage

```
{'build_collator_from_name': 'build a collator function by name using build_collator_from_name to get a collator callable from the registry', 'collate_multiple_samples_batch': 'collate a batch of multi-sample dictionaries using multiple_samples_collate for repeated augmentation data', 'register_custom_collator': 'register a custom collator function in the _COLLATORS dictionary for use with build_collator_from_name', 'review_multiple_samples_collate': 'review the multiple_samples_collate function to understand how it flattens and collates multi-sample batches', 'test_build_collator_from_name': 'test build_collator_from_name with valid and invalid names to verify collator lookup and error handling'}
```

## File: facebookresearch_pytorchvideo/pytorchvideo_trainer/pytorchvideo_trainer/datamodule/datamodule.py

Prompts

```
['build a collator function by name using build_collator_from_name to get a collator callable from the registry', 'collate a batch of multi-sample dictionaries using multiple_samples_collate for repeated augmentation data', 'register a custom collator function in the _COLLATORS dictionary for use with build_collator_from_name', 'review the multiple_samples_collate function to understand how it flattens and collates multi-sample batches', 'test build_collator_from_name with valid and invalid names to verify collator lookup and error handling', 'create a PyTorchVideoDataModule instance with dataloader and transforms config for video classification training', 'setup the PyTorchVideoDataModule datasets for train, val, or test phases using the setup method', 'get the train DataLoader from PyTorchVideoDataModule with distributed sampler epoch support for video data', 'build a DataLoaderConf dataclass with train, val, and test PhaseDataLoaderConf settings for each phase', 'register the VideoClassificationDataModuleConf schema in Hydra ConfigStore for video classification data module configuration', 'build a composed video transform pipeline from a list of Hydra config objects', 'build a single transform from a Hydra config object with nested transform composition', 'apply a transform to each item in a list stored under a dictionary key', 'create a SlowFast pathway transform that splits video frames into slow and fast clips', 'create a color jitter transform with blur and grayscale for self-supervised learning video augmentation']
```

Usage

```
{'create_PyTorchVideoDataModule': 'create a PyTorchVideoDataModule instance with dataloader and transforms config for video classification training', 'setup_PyTorchVideoDataModule': 'setup the PyTorchVideoDataModule datasets for train, val, or test phases using the setup method', 'get_train_dataloader': 'get the train DataLoader from PyTorchVideoDataModule with distributed sampler epoch support for video data', 'build_DataLoaderConf': 'build a DataLoaderConf dataclass with train, val, and test PhaseDataLoaderConf settings for each phase', 'register_VideoClassificationDataModuleConf': 'register the VideoClassificationDataModuleConf schema in Hydra ConfigStore for video classification data module configuration'}
```

## File: facebookresearch_pytorchvideo/pytorchvideo_trainer/pytorchvideo_trainer/datamodule/transforms.py

Prompts

```
['build a collator function by name using build_collator_from_name to get a collator callable from the registry', 'collate a batch of multi-sample dictionaries using multiple_samples_collate for repeated augmentation data', 'register a custom collator function in the _COLLATORS dictionary for use with build_collator_from_name', 'review the multiple_samples_collate function to understand how it flattens and collates multi-sample batches', 'test build_collator_from_name with valid and invalid names to verify collator lookup and error handling', 'create a PyTorchVideoDataModule instance with dataloader and transforms config for video classification training', 'setup the PyTorchVideoDataModule datasets for train, val, or test phases using the setup method', 'get the train DataLoader from PyTorchVideoDataModule with distributed sampler epoch support for video data', 'build a DataLoaderConf dataclass with train, val, and test PhaseDataLoaderConf settings for each phase', 'register the VideoClassificationDataModuleConf schema in Hydra ConfigStore for video classification data module configuration', 'build a composed video transform pipeline from a list of Hydra config objects', 'build a single transform from a Hydra config object with nested transform composition', 'apply a transform to each item in a list stored under a dictionary key', 'create a SlowFast pathway transform that splits video frames into slow and fast clips', 'create a color jitter transform with blur and grayscale for self-supervised learning video augmentation']
```

Usage

```
{'build_transforms_from_config': 'build a composed video transform pipeline from a list of Hydra config objects', 'build_single_transform_from_config': 'build a single transform from a Hydra config object with nested transform composition', 'apply_transform_to_key_on_list': 'apply a transform to each item in a list stored under a dictionary key', 'create_slowfast_pathway_transform': 'create a SlowFast pathway transform that splits video frames into slow and fast clips', 'create_color_jitter_video_ssl': 'create a color jitter transform with blur and grayscale for self-supervised learning video augmentation'}
```

