# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/mapanything/datasets/base/base_dataset.py

Prompts

```
['create a subclass of BaseDataset that implements _get_views to return multi-view image dicts for a custom scene dataset', 'use _crop_resize_if_necessary to downscale and crop images with depthmaps and intrinsics to a target resolution', 'use _random_walk_sampling to sample connected view indices from a scene covisibility matrix via random walk with backtracking', 'configure BaseDataset with transform and data_norm_type to apply image normalization and augmentation like color jitter or grayscale', 'use is_good_type to check if a numpy or torch tensor value has an acceptable dtype for dataset processing', 'create a BatchedRandomSampler that samples batches where each sample shares the same randomly chosen feature index from a pool', 'create a BatchedMultiFeatureRandomSampler that samples batches where each sample shares the same indices from multiple feature pools', 'create a DynamicBatchedMultiFeatureRandomSampler that dynamically adjusts batch size based on a feature-to-batch-size mapping for GPU memory optimization', 'use round_by to round a number to the nearest multiple of another number with optional rounding up', 'use set_epoch on a batched sampler to set the epoch number for reproducible shuffling across training epochs', 'concatenate two EasyDataset instances using the plus operator to create a CatDataset', 'multiply a dataset by an integer factor using the rmul operator to duplicate each element', 'resize a dataset to a specific size using the rmatmul operator with random sampling', 'create a dynamic or static sampler for an EasyDataset using make_sampler with batch size and world size', 'set the epoch on a ResizedDataset or CatDataset to generate new random index mappings']
```

Usage

```
{'create_dataset_subclass': 'create a subclass of BaseDataset that implements _get_views to return multi-view image dicts for a custom scene dataset', 'crop_resize_images': 'use _crop_resize_if_necessary to downscale and crop images with depthmaps and intrinsics to a target resolution', 'sample_connected_views': 'use _random_walk_sampling to sample connected view indices from a scene covisibility matrix via random walk with backtracking', 'normalize_and_transform_images': 'configure BaseDataset with transform and data_norm_type to apply image normalization and augmentation like color jitter or grayscale', 'validate_view_types': 'use is_good_type to check if a numpy or torch tensor value has an acceptable dtype for dataset processing'}
```

## File: facebookresearch_map-anything/mapanything/datasets/base/batched_sampler.py

Prompts

```
['create a subclass of BaseDataset that implements _get_views to return multi-view image dicts for a custom scene dataset', 'use _crop_resize_if_necessary to downscale and crop images with depthmaps and intrinsics to a target resolution', 'use _random_walk_sampling to sample connected view indices from a scene covisibility matrix via random walk with backtracking', 'configure BaseDataset with transform and data_norm_type to apply image normalization and augmentation like color jitter or grayscale', 'use is_good_type to check if a numpy or torch tensor value has an acceptable dtype for dataset processing', 'create a BatchedRandomSampler that samples batches where each sample shares the same randomly chosen feature index from a pool', 'create a BatchedMultiFeatureRandomSampler that samples batches where each sample shares the same indices from multiple feature pools', 'create a DynamicBatchedMultiFeatureRandomSampler that dynamically adjusts batch size based on a feature-to-batch-size mapping for GPU memory optimization', 'use round_by to round a number to the nearest multiple of another number with optional rounding up', 'use set_epoch on a batched sampler to set the epoch number for reproducible shuffling across training epochs', 'concatenate two EasyDataset instances using the plus operator to create a CatDataset', 'multiply a dataset by an integer factor using the rmul operator to duplicate each element', 'resize a dataset to a specific size using the rmatmul operator with random sampling', 'create a dynamic or static sampler for an EasyDataset using make_sampler with batch size and world size', 'set the epoch on a ResizedDataset or CatDataset to generate new random index mappings']
```

Usage

```
{'create_BatchedRandomSampler': 'create a BatchedRandomSampler that samples batches where each sample shares the same randomly chosen feature index from a pool', 'create_BatchedMultiFeatureRandomSampler': 'create a BatchedMultiFeatureRandomSampler that samples batches where each sample shares the same indices from multiple feature pools', 'create_DynamicBatchedMultiFeatureRandomSampler': 'create a DynamicBatchedMultiFeatureRandomSampler that dynamically adjusts batch size based on a feature-to-batch-size mapping for GPU memory optimization', 'use_round_by': 'use round_by to round a number to the nearest multiple of another number with optional rounding up', 'use_set_epoch': 'use set_epoch on a batched sampler to set the epoch number for reproducible shuffling across training epochs'}
```

## File: facebookresearch_map-anything/mapanything/datasets/base/easy_dataset.py

Prompts

```
['create a subclass of BaseDataset that implements _get_views to return multi-view image dicts for a custom scene dataset', 'use _crop_resize_if_necessary to downscale and crop images with depthmaps and intrinsics to a target resolution', 'use _random_walk_sampling to sample connected view indices from a scene covisibility matrix via random walk with backtracking', 'configure BaseDataset with transform and data_norm_type to apply image normalization and augmentation like color jitter or grayscale', 'use is_good_type to check if a numpy or torch tensor value has an acceptable dtype for dataset processing', 'create a BatchedRandomSampler that samples batches where each sample shares the same randomly chosen feature index from a pool', 'create a BatchedMultiFeatureRandomSampler that samples batches where each sample shares the same indices from multiple feature pools', 'create a DynamicBatchedMultiFeatureRandomSampler that dynamically adjusts batch size based on a feature-to-batch-size mapping for GPU memory optimization', 'use round_by to round a number to the nearest multiple of another number with optional rounding up', 'use set_epoch on a batched sampler to set the epoch number for reproducible shuffling across training epochs', 'concatenate two EasyDataset instances using the plus operator to create a CatDataset', 'multiply a dataset by an integer factor using the rmul operator to duplicate each element', 'resize a dataset to a specific size using the rmatmul operator with random sampling', 'create a dynamic or static sampler for an EasyDataset using make_sampler with batch size and world size', 'set the epoch on a ResizedDataset or CatDataset to generate new random index mappings']
```

Usage

```
{'concatenate_datasets': 'concatenate two EasyDataset instances using the plus operator to create a CatDataset', 'multiply_dataset': 'multiply a dataset by an integer factor using the rmul operator to duplicate each element', 'resize_dataset': 'resize a dataset to a specific size using the rmatmul operator with random sampling', 'create_sampler': 'create a dynamic or static sampler for an EasyDataset using make_sampler with batch size and world size', 'set_epoch': 'set the epoch on a ResizedDataset or CatDataset to generate new random index mappings'}
```

