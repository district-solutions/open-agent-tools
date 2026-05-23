# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/dataset/base_dataset.py

Prompts

```
['create a Compose pipeline to apply multiple transforms sequentially on a data dict', 'build a BaseDataset subclass to load annotations from a JSON file with data_list and metainfo', 'get the data info dict for a given index from a fully initialized BaseDataset instance', 'filter a BaseDataset to a subset using get_subset or get_subset_ with integer or list indices', 'serialize a BaseDataset data_list into shared memory bytes and address arrays for multi-worker loading', 'build a ConcatDataset to concatenate multiple BaseDataset instances with lazy initialization support', 'build a RepeatDataset to repeat a BaseDataset N times for faster epoch data loading', 'build a ClassBalancedDataset to oversample rare categories using a frequency threshold', 'review the ConcatDataset metainfo property that returns a deep copy of the first dataset metadata', 'refactor the ClassBalancedDataset _get_repeat_factors method to compute per-image repeat factors from category frequency', 'create a DefaultSampler for a dataset with shuffle enabled and a fixed random seed', 'create a DefaultSampler with round_up disabled to avoid adding extra samples', 'iterate over a DefaultSampler to get shuffled dataset indices for the current rank', 'set the epoch on a DefaultSampler to ensure different shuffle order each epoch', 'create an InfiniteSampler for iteration-based training that yields indices indefinitely', 'create a worker init function that seeds numpy, random, and torch for each DataLoader subprocess', 'build a collate function that transposes a batch of data without stacking tensors', 'run a collate function that stacks tensors in a batch and converts ndarrays to tensors', 'review the worker init function that sets per-worker random seeds using rank, worker_id, and seed', 'test the pseudo collate function with a batch of dictionaries containing mixed data types']
```

Usage

```
{'create_compose_pipeline': 'create a Compose pipeline to apply multiple transforms sequentially on a data dict', 'build_base_dataset': 'build a BaseDataset subclass to load annotations from a JSON file with data_list and metainfo', 'get_data_info_by_index': 'get the data info dict for a given index from a fully initialized BaseDataset instance', 'filter_dataset_subset': 'filter a BaseDataset to a subset using get_subset or get_subset_ with integer or list indices', 'serialize_dataset_data': 'serialize a BaseDataset data_list into shared memory bytes and address arrays for multi-worker loading'}
```

## File: facebookresearch_sapiens/engine/mmengine/dataset/dataset_wrapper.py

Prompts

```
['create a Compose pipeline to apply multiple transforms sequentially on a data dict', 'build a BaseDataset subclass to load annotations from a JSON file with data_list and metainfo', 'get the data info dict for a given index from a fully initialized BaseDataset instance', 'filter a BaseDataset to a subset using get_subset or get_subset_ with integer or list indices', 'serialize a BaseDataset data_list into shared memory bytes and address arrays for multi-worker loading', 'build a ConcatDataset to concatenate multiple BaseDataset instances with lazy initialization support', 'build a RepeatDataset to repeat a BaseDataset N times for faster epoch data loading', 'build a ClassBalancedDataset to oversample rare categories using a frequency threshold', 'review the ConcatDataset metainfo property that returns a deep copy of the first dataset metadata', 'refactor the ClassBalancedDataset _get_repeat_factors method to compute per-image repeat factors from category frequency', 'create a DefaultSampler for a dataset with shuffle enabled and a fixed random seed', 'create a DefaultSampler with round_up disabled to avoid adding extra samples', 'iterate over a DefaultSampler to get shuffled dataset indices for the current rank', 'set the epoch on a DefaultSampler to ensure different shuffle order each epoch', 'create an InfiniteSampler for iteration-based training that yields indices indefinitely', 'create a worker init function that seeds numpy, random, and torch for each DataLoader subprocess', 'build a collate function that transposes a batch of data without stacking tensors', 'run a collate function that stacks tensors in a batch and converts ndarrays to tensors', 'review the worker init function that sets per-worker random seeds using rank, worker_id, and seed', 'test the pseudo collate function with a batch of dictionaries containing mixed data types']
```

Usage

```
{'build_concat_dataset': 'build a ConcatDataset to concatenate multiple BaseDataset instances with lazy initialization support', 'build_repeat_dataset': 'build a RepeatDataset to repeat a BaseDataset N times for faster epoch data loading', 'build_class_balanced_dataset': 'build a ClassBalancedDataset to oversample rare categories using a frequency threshold', 'review_concatdataset_metainfo': 'review the ConcatDataset metainfo property that returns a deep copy of the first dataset metadata', 'refactor_classbalanceddataset_repeat_factors': 'refactor the ClassBalancedDataset _get_repeat_factors method to compute per-image repeat factors from category frequency'}
```

## File: facebookresearch_sapiens/engine/mmengine/dataset/sampler.py

Prompts

```
['create a Compose pipeline to apply multiple transforms sequentially on a data dict', 'build a BaseDataset subclass to load annotations from a JSON file with data_list and metainfo', 'get the data info dict for a given index from a fully initialized BaseDataset instance', 'filter a BaseDataset to a subset using get_subset or get_subset_ with integer or list indices', 'serialize a BaseDataset data_list into shared memory bytes and address arrays for multi-worker loading', 'build a ConcatDataset to concatenate multiple BaseDataset instances with lazy initialization support', 'build a RepeatDataset to repeat a BaseDataset N times for faster epoch data loading', 'build a ClassBalancedDataset to oversample rare categories using a frequency threshold', 'review the ConcatDataset metainfo property that returns a deep copy of the first dataset metadata', 'refactor the ClassBalancedDataset _get_repeat_factors method to compute per-image repeat factors from category frequency', 'create a DefaultSampler for a dataset with shuffle enabled and a fixed random seed', 'create a DefaultSampler with round_up disabled to avoid adding extra samples', 'iterate over a DefaultSampler to get shuffled dataset indices for the current rank', 'set the epoch on a DefaultSampler to ensure different shuffle order each epoch', 'create an InfiniteSampler for iteration-based training that yields indices indefinitely', 'create a worker init function that seeds numpy, random, and torch for each DataLoader subprocess', 'build a collate function that transposes a batch of data without stacking tensors', 'run a collate function that stacks tensors in a batch and converts ndarrays to tensors', 'review the worker init function that sets per-worker random seeds using rank, worker_id, and seed', 'test the pseudo collate function with a batch of dictionaries containing mixed data types']
```

Usage

```
{'create_default_sampler': 'create a DefaultSampler for a dataset with shuffle enabled and a fixed random seed', 'create_default_sampler_no_roundup': 'create a DefaultSampler with round_up disabled to avoid adding extra samples', 'iterate_default_sampler': 'iterate over a DefaultSampler to get shuffled dataset indices for the current rank', 'set_epoch_default_sampler': 'set the epoch on a DefaultSampler to ensure different shuffle order each epoch', 'create_infinite_sampler': 'create an InfiniteSampler for iteration-based training that yields indices indefinitely'}
```

## File: facebookresearch_sapiens/engine/mmengine/dataset/utils.py

Prompts

```
['create a Compose pipeline to apply multiple transforms sequentially on a data dict', 'build a BaseDataset subclass to load annotations from a JSON file with data_list and metainfo', 'get the data info dict for a given index from a fully initialized BaseDataset instance', 'filter a BaseDataset to a subset using get_subset or get_subset_ with integer or list indices', 'serialize a BaseDataset data_list into shared memory bytes and address arrays for multi-worker loading', 'build a ConcatDataset to concatenate multiple BaseDataset instances with lazy initialization support', 'build a RepeatDataset to repeat a BaseDataset N times for faster epoch data loading', 'build a ClassBalancedDataset to oversample rare categories using a frequency threshold', 'review the ConcatDataset metainfo property that returns a deep copy of the first dataset metadata', 'refactor the ClassBalancedDataset _get_repeat_factors method to compute per-image repeat factors from category frequency', 'create a DefaultSampler for a dataset with shuffle enabled and a fixed random seed', 'create a DefaultSampler with round_up disabled to avoid adding extra samples', 'iterate over a DefaultSampler to get shuffled dataset indices for the current rank', 'set the epoch on a DefaultSampler to ensure different shuffle order each epoch', 'create an InfiniteSampler for iteration-based training that yields indices indefinitely', 'create a worker init function that seeds numpy, random, and torch for each DataLoader subprocess', 'build a collate function that transposes a batch of data without stacking tensors', 'run a collate function that stacks tensors in a batch and converts ndarrays to tensors', 'review the worker init function that sets per-worker random seeds using rank, worker_id, and seed', 'test the pseudo collate function with a batch of dictionaries containing mixed data types']
```

Usage

```
{'create_worker_init_fn': 'create a worker init function that seeds numpy, random, and torch for each DataLoader subprocess', 'build_pseudo_collate': 'build a collate function that transposes a batch of data without stacking tensors', 'run_default_collate': 'run a collate function that stacks tensors in a batch and converts ndarrays to tensors', 'review_worker_init_fn': 'review the worker init function that sets per-worker random seeds using rank, worker_id, and seed', 'test_pseudo_collate': 'test the pseudo collate function with a batch of dictionaries containing mixed data types'}
```

