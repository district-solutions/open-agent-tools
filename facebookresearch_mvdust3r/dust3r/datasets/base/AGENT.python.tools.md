# Agent Python Tools

- repo: facebookresearch/mvdust3r
- repo_uri: https://github.com/facebookresearch/mvdust3r

## File: facebookresearch_mvdust3r/dust3r/datasets/base/base_stereo_view_dataset.py

Prompts

```
['create a subclass of BaseStereoViewDataset that overrides _get_views to return custom stereo image pairs', 'review the BaseStereoViewDataset __getitem__ method to understand how views are fetched, transformed, and validated', 'test the _crop_resize_if_necessary method to verify it correctly crops and resizes images with depthmaps', 'summarize the is_good_type function that validates numpy and torch tensor data types for dataset views', 'refactor the transpose_to_landscape function to handle additional tensor fields when converting portrait views to landscape', 'create a BatchedRandomSampler to sample dataset indices with shared feature constraints per batch', 'iterate over a BatchedRandomSampler to yield tuples of sample and feature indices for each batch', 'set the epoch on a BatchedRandomSampler to control deterministic random seeding across training epochs', 'use the round_by function to round a total number down to the nearest multiple', 'review the BatchedRandomSampler class and its distributed sampling logic for multi-GPU training', 'create a subclass of EasyDataset to build a custom dataset with resize and combine support', 'use MulDataset to duplicate each element of a dataset by a given integer factor', 'use ResizedDataset to set a dataset to a specific size with random sampling and epoch-based shuffling', 'use CatDataset to concatenate multiple EasyDataset instances into a single combined dataset', 'use make_sampler on an EasyDataset to create a BatchedRandomSampler for distributed training']
```

Usage

```
{'create_stereo_dataset_subclass': 'create a subclass of BaseStereoViewDataset that overrides _get_views to return custom stereo image pairs', 'review_BaseStereoViewDataset_getitem': 'review the BaseStereoViewDataset __getitem__ method to understand how views are fetched, transformed, and validated', 'test_crop_resize_if_necessary': 'test the _crop_resize_if_necessary method to verify it correctly crops and resizes images with depthmaps', 'summarize_is_good_type': 'summarize the is_good_type function that validates numpy and torch tensor data types for dataset views', 'refactor_transpose_to_landscape': 'refactor the transpose_to_landscape function to handle additional tensor fields when converting portrait views to landscape'}
```

## File: facebookresearch_mvdust3r/dust3r/datasets/base/batched_sampler.py

Prompts

```
['create a subclass of BaseStereoViewDataset that overrides _get_views to return custom stereo image pairs', 'review the BaseStereoViewDataset __getitem__ method to understand how views are fetched, transformed, and validated', 'test the _crop_resize_if_necessary method to verify it correctly crops and resizes images with depthmaps', 'summarize the is_good_type function that validates numpy and torch tensor data types for dataset views', 'refactor the transpose_to_landscape function to handle additional tensor fields when converting portrait views to landscape', 'create a BatchedRandomSampler to sample dataset indices with shared feature constraints per batch', 'iterate over a BatchedRandomSampler to yield tuples of sample and feature indices for each batch', 'set the epoch on a BatchedRandomSampler to control deterministic random seeding across training epochs', 'use the round_by function to round a total number down to the nearest multiple', 'review the BatchedRandomSampler class and its distributed sampling logic for multi-GPU training', 'create a subclass of EasyDataset to build a custom dataset with resize and combine support', 'use MulDataset to duplicate each element of a dataset by a given integer factor', 'use ResizedDataset to set a dataset to a specific size with random sampling and epoch-based shuffling', 'use CatDataset to concatenate multiple EasyDataset instances into a single combined dataset', 'use make_sampler on an EasyDataset to create a BatchedRandomSampler for distributed training']
```

Usage

```
{'create_batched_random_sampler': 'create a BatchedRandomSampler to sample dataset indices with shared feature constraints per batch', 'iterate_batched_random_sampler': 'iterate over a BatchedRandomSampler to yield tuples of sample and feature indices for each batch', 'set_epoch_batched_random_sampler': 'set the epoch on a BatchedRandomSampler to control deterministic random seeding across training epochs', 'use_round_by_function': 'use the round_by function to round a total number down to the nearest multiple', 'review_batched_random_sampler_class': 'review the BatchedRandomSampler class and its distributed sampling logic for multi-GPU training'}
```

## File: facebookresearch_mvdust3r/dust3r/datasets/base/easy_dataset.py

Prompts

```
['create a subclass of BaseStereoViewDataset that overrides _get_views to return custom stereo image pairs', 'review the BaseStereoViewDataset __getitem__ method to understand how views are fetched, transformed, and validated', 'test the _crop_resize_if_necessary method to verify it correctly crops and resizes images with depthmaps', 'summarize the is_good_type function that validates numpy and torch tensor data types for dataset views', 'refactor the transpose_to_landscape function to handle additional tensor fields when converting portrait views to landscape', 'create a BatchedRandomSampler to sample dataset indices with shared feature constraints per batch', 'iterate over a BatchedRandomSampler to yield tuples of sample and feature indices for each batch', 'set the epoch on a BatchedRandomSampler to control deterministic random seeding across training epochs', 'use the round_by function to round a total number down to the nearest multiple', 'review the BatchedRandomSampler class and its distributed sampling logic for multi-GPU training', 'create a subclass of EasyDataset to build a custom dataset with resize and combine support', 'use MulDataset to duplicate each element of a dataset by a given integer factor', 'use ResizedDataset to set a dataset to a specific size with random sampling and epoch-based shuffling', 'use CatDataset to concatenate multiple EasyDataset instances into a single combined dataset', 'use make_sampler on an EasyDataset to create a BatchedRandomSampler for distributed training']
```

Usage

```
{'create_EasyDataset_subclass': 'create a subclass of EasyDataset to build a custom dataset with resize and combine support', 'use_MulDataset_duplicate': 'use MulDataset to duplicate each element of a dataset by a given integer factor', 'use_ResizedDataset_resize': 'use ResizedDataset to set a dataset to a specific size with random sampling and epoch-based shuffling', 'use_CatDataset_concatenate': 'use CatDataset to concatenate multiple EasyDataset instances into a single combined dataset', 'use_EasyDataset_make_sampler': 'use make_sampler on an EasyDataset to create a BatchedRandomSampler for distributed training'}
```

