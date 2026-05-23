# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/datasets/builder.py

Prompts

```
['build a dataset from a config dict using build_dataset with type and annotation file keys', 'build a ConcatDataset from multiple config dicts by passing a list of dataset configs to build_dataset', 'build a RepeatDataset that repeats a base dataset N times using build_dataset with RepeatDataset type', 'build a concatenated dataset from multiple annotation files by passing a list of ann_file paths in the config', 'init random seeds for PyTorch data loader workers using worker_init_fn with worker_id, num_workers, rank, and seed', 'build a CombinedDataset that merges multiple pose estimation datasets with a shared processing pipeline', 'test the _get_subset_index method to map a global index to a sub-dataset and local index', 'review the prepare_data method that filters samples by minimum visible keypoints threshold', 'summarize the get_data_info method that retrieves annotations and enriches them with metainfo keys', 'refactor the full_init method to lazily initialize all sub-datasets in the combined dataset', 'create a MultiSourceSampler to sample data from multiple datasets with configurable source ratios', 'build a MultiSourceSampler with shuffle enabled to randomly sample from combined datasets', 'test the MultiSourceSampler __iter__ method to verify batch buffer generation across sources', 'review the _infinite_indices method to understand how shuffled or sequential indices are yielded', 'refactor the _indices_of_rank method to customize distributed sampling slice logic']
```

Usage

```
{'build_dataset_from_cfg': 'build a dataset from a config dict using build_dataset with type and annotation file keys', 'build_concat_dataset': 'build a ConcatDataset from multiple config dicts by passing a list of dataset configs to build_dataset', 'build_repeat_dataset': 'build a RepeatDataset that repeats a base dataset N times using build_dataset with RepeatDataset type', 'build_multi_ann_dataset': 'build a concatenated dataset from multiple annotation files by passing a list of ann_file paths in the config', 'init_worker_seeds': 'init random seeds for PyTorch data loader workers using worker_init_fn with worker_id, num_workers, rank, and seed'}
```

## File: facebookresearch_sapiens/pose/mmpose/datasets/dataset_wrappers.py

Prompts

```
['build a dataset from a config dict using build_dataset with type and annotation file keys', 'build a ConcatDataset from multiple config dicts by passing a list of dataset configs to build_dataset', 'build a RepeatDataset that repeats a base dataset N times using build_dataset with RepeatDataset type', 'build a concatenated dataset from multiple annotation files by passing a list of ann_file paths in the config', 'init random seeds for PyTorch data loader workers using worker_init_fn with worker_id, num_workers, rank, and seed', 'build a CombinedDataset that merges multiple pose estimation datasets with a shared processing pipeline', 'test the _get_subset_index method to map a global index to a sub-dataset and local index', 'review the prepare_data method that filters samples by minimum visible keypoints threshold', 'summarize the get_data_info method that retrieves annotations and enriches them with metainfo keys', 'refactor the full_init method to lazily initialize all sub-datasets in the combined dataset', 'create a MultiSourceSampler to sample data from multiple datasets with configurable source ratios', 'build a MultiSourceSampler with shuffle enabled to randomly sample from combined datasets', 'test the MultiSourceSampler __iter__ method to verify batch buffer generation across sources', 'review the _infinite_indices method to understand how shuffled or sequential indices are yielded', 'refactor the _indices_of_rank method to customize distributed sampling slice logic']
```

Usage

```
{'build_CombinedDataset': 'build a CombinedDataset that merges multiple pose estimation datasets with a shared processing pipeline', 'test_get_subset_index': 'test the _get_subset_index method to map a global index to a sub-dataset and local index', 'review_prepare_data': 'review the prepare_data method that filters samples by minimum visible keypoints threshold', 'summarize_get_data_info': 'summarize the get_data_info method that retrieves annotations and enriches them with metainfo keys', 'refactor_CombinedDataset_full_init': 'refactor the full_init method to lazily initialize all sub-datasets in the combined dataset'}
```

## File: facebookresearch_sapiens/pose/mmpose/datasets/samplers.py

Prompts

```
['build a dataset from a config dict using build_dataset with type and annotation file keys', 'build a ConcatDataset from multiple config dicts by passing a list of dataset configs to build_dataset', 'build a RepeatDataset that repeats a base dataset N times using build_dataset with RepeatDataset type', 'build a concatenated dataset from multiple annotation files by passing a list of ann_file paths in the config', 'init random seeds for PyTorch data loader workers using worker_init_fn with worker_id, num_workers, rank, and seed', 'build a CombinedDataset that merges multiple pose estimation datasets with a shared processing pipeline', 'test the _get_subset_index method to map a global index to a sub-dataset and local index', 'review the prepare_data method that filters samples by minimum visible keypoints threshold', 'summarize the get_data_info method that retrieves annotations and enriches them with metainfo keys', 'refactor the full_init method to lazily initialize all sub-datasets in the combined dataset', 'create a MultiSourceSampler to sample data from multiple datasets with configurable source ratios', 'build a MultiSourceSampler with shuffle enabled to randomly sample from combined datasets', 'test the MultiSourceSampler __iter__ method to verify batch buffer generation across sources', 'review the _infinite_indices method to understand how shuffled or sequential indices are yielded', 'refactor the _indices_of_rank method to customize distributed sampling slice logic']
```

Usage

```
{'create_multisource_sampler': 'create a MultiSourceSampler to sample data from multiple datasets with configurable source ratios', 'build_sampler_with_shuffle': 'build a MultiSourceSampler with shuffle enabled to randomly sample from combined datasets', 'test_multisource_sampler_iteration': 'test the MultiSourceSampler __iter__ method to verify batch buffer generation across sources', 'review_infinite_indices': 'review the _infinite_indices method to understand how shuffled or sequential indices are yielded', 'refactor_indices_of_rank': 'refactor the _indices_of_rank method to customize distributed sampling slice logic'}
```

