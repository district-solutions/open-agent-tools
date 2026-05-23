# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/datasets/samplers/class_aware_sampler.py

Prompts

```
['build a class-aware sampler to balance non-uniform class distribution in detection datasets', 'create a mapping from class labels to image indices using get_cat2imgs method', 'test the ClassAwareSampler iterator to verify balanced sampling across all classes', 'refactor the ClassAwareSampler set_epoch method to ensure different random ordering per epoch', 'review the RandomCycleIter class that shuffles data and cycles through after traversal', 'create a MultiDataSampler with a dataset and dataset ratio for distributed training', 'iterate over a MultiDataSampler to get weighted shuffled indices for the current rank', 'set the epoch on a MultiDataSampler to ensure different shuffle order each epoch', 'get the number of samples for the current rank using len on MultiDataSampler', 'review the MultiDataSampler class to understand weighted sampling with dataset ratios and round up behavior', 'build a MultiSourceSampler to sample data from multiple datasets with configurable source ratios', 'build a GroupMultiSourceSampler to sample grouped data from multiple datasets by aspect ratio', 'test the MultiSourceSampler iterator to yield infinite batches from concatenated datasets', 'review the GroupMultiSourceSampler _get_source_group_info method that categorizes samples into aspect ratio groups', 'refactor the MultiSourceSampler _infinite_indices method to support custom shuffling strategies', 'create a TrackImgSampler instance with a BaseVideoDataset and optional random seed for video tracking tasks', 'iterate over a TrackImgSampler to get video-frame index tuples for distributed or non-distributed training', 'set the epoch on a TrackImgSampler to control deterministic shuffling across training epochs', 'review the TrackImgSampler constructor to understand how it handles ConcatDataset, ClassBalancedDataset, and BaseVideoDataset wrappers', 'summarize the TrackImgSampler class that provides image-level sampling for video datasets in tracking tasks with distributed support']
```

Usage

```
{'build_ClassAwareSampler': 'build a class-aware sampler to balance non-uniform class distribution in detection datasets', 'create_ClassAwareSampler_get_cat2imgs': 'create a mapping from class labels to image indices using get_cat2imgs method', 'test_ClassAwareSampler_iter': 'test the ClassAwareSampler iterator to verify balanced sampling across all classes', 'refactor_ClassAwareSampler_set_epoch': 'refactor the ClassAwareSampler set_epoch method to ensure different random ordering per epoch', 'review_RandomCycleIter': 'review the RandomCycleIter class that shuffles data and cycles through after traversal'}
```

## File: facebookresearch_sapiens/det/mmdet/datasets/samplers/multi_data_sampler.py

Prompts

```
['build a class-aware sampler to balance non-uniform class distribution in detection datasets', 'create a mapping from class labels to image indices using get_cat2imgs method', 'test the ClassAwareSampler iterator to verify balanced sampling across all classes', 'refactor the ClassAwareSampler set_epoch method to ensure different random ordering per epoch', 'review the RandomCycleIter class that shuffles data and cycles through after traversal', 'create a MultiDataSampler with a dataset and dataset ratio for distributed training', 'iterate over a MultiDataSampler to get weighted shuffled indices for the current rank', 'set the epoch on a MultiDataSampler to ensure different shuffle order each epoch', 'get the number of samples for the current rank using len on MultiDataSampler', 'review the MultiDataSampler class to understand weighted sampling with dataset ratios and round up behavior', 'build a MultiSourceSampler to sample data from multiple datasets with configurable source ratios', 'build a GroupMultiSourceSampler to sample grouped data from multiple datasets by aspect ratio', 'test the MultiSourceSampler iterator to yield infinite batches from concatenated datasets', 'review the GroupMultiSourceSampler _get_source_group_info method that categorizes samples into aspect ratio groups', 'refactor the MultiSourceSampler _infinite_indices method to support custom shuffling strategies', 'create a TrackImgSampler instance with a BaseVideoDataset and optional random seed for video tracking tasks', 'iterate over a TrackImgSampler to get video-frame index tuples for distributed or non-distributed training', 'set the epoch on a TrackImgSampler to control deterministic shuffling across training epochs', 'review the TrackImgSampler constructor to understand how it handles ConcatDataset, ClassBalancedDataset, and BaseVideoDataset wrappers', 'summarize the TrackImgSampler class that provides image-level sampling for video datasets in tracking tasks with distributed support']
```

Usage

```
{'create_multi_data_sampler': 'create a MultiDataSampler with a dataset and dataset ratio for distributed training', 'iterate_multi_data_sampler': 'iterate over a MultiDataSampler to get weighted shuffled indices for the current rank', 'set_epoch_multi_data_sampler': 'set the epoch on a MultiDataSampler to ensure different shuffle order each epoch', 'get_sampler_length': 'get the number of samples for the current rank using len on MultiDataSampler', 'review_multi_data_sampler_class': 'review the MultiDataSampler class to understand weighted sampling with dataset ratios and round up behavior'}
```

## File: facebookresearch_sapiens/det/mmdet/datasets/samplers/multi_source_sampler.py

Prompts

```
['build a class-aware sampler to balance non-uniform class distribution in detection datasets', 'create a mapping from class labels to image indices using get_cat2imgs method', 'test the ClassAwareSampler iterator to verify balanced sampling across all classes', 'refactor the ClassAwareSampler set_epoch method to ensure different random ordering per epoch', 'review the RandomCycleIter class that shuffles data and cycles through after traversal', 'create a MultiDataSampler with a dataset and dataset ratio for distributed training', 'iterate over a MultiDataSampler to get weighted shuffled indices for the current rank', 'set the epoch on a MultiDataSampler to ensure different shuffle order each epoch', 'get the number of samples for the current rank using len on MultiDataSampler', 'review the MultiDataSampler class to understand weighted sampling with dataset ratios and round up behavior', 'build a MultiSourceSampler to sample data from multiple datasets with configurable source ratios', 'build a GroupMultiSourceSampler to sample grouped data from multiple datasets by aspect ratio', 'test the MultiSourceSampler iterator to yield infinite batches from concatenated datasets', 'review the GroupMultiSourceSampler _get_source_group_info method that categorizes samples into aspect ratio groups', 'refactor the MultiSourceSampler _infinite_indices method to support custom shuffling strategies', 'create a TrackImgSampler instance with a BaseVideoDataset and optional random seed for video tracking tasks', 'iterate over a TrackImgSampler to get video-frame index tuples for distributed or non-distributed training', 'set the epoch on a TrackImgSampler to control deterministic shuffling across training epochs', 'review the TrackImgSampler constructor to understand how it handles ConcatDataset, ClassBalancedDataset, and BaseVideoDataset wrappers', 'summarize the TrackImgSampler class that provides image-level sampling for video datasets in tracking tasks with distributed support']
```

Usage

```
{'build_MultiSourceSampler': 'build a MultiSourceSampler to sample data from multiple datasets with configurable source ratios', 'build_GroupMultiSourceSampler': 'build a GroupMultiSourceSampler to sample grouped data from multiple datasets by aspect ratio', 'test_MultiSourceSampler_iter': 'test the MultiSourceSampler iterator to yield infinite batches from concatenated datasets', 'review_GroupMultiSourceSampler_get_source_group_info': 'review the GroupMultiSourceSampler _get_source_group_info method that categorizes samples into aspect ratio groups', 'refactor_MultiSourceSampler_infinite_indices': 'refactor the MultiSourceSampler _infinite_indices method to support custom shuffling strategies'}
```

## File: facebookresearch_sapiens/det/mmdet/datasets/samplers/track_img_sampler.py

Prompts

```
['build a class-aware sampler to balance non-uniform class distribution in detection datasets', 'create a mapping from class labels to image indices using get_cat2imgs method', 'test the ClassAwareSampler iterator to verify balanced sampling across all classes', 'refactor the ClassAwareSampler set_epoch method to ensure different random ordering per epoch', 'review the RandomCycleIter class that shuffles data and cycles through after traversal', 'create a MultiDataSampler with a dataset and dataset ratio for distributed training', 'iterate over a MultiDataSampler to get weighted shuffled indices for the current rank', 'set the epoch on a MultiDataSampler to ensure different shuffle order each epoch', 'get the number of samples for the current rank using len on MultiDataSampler', 'review the MultiDataSampler class to understand weighted sampling with dataset ratios and round up behavior', 'build a MultiSourceSampler to sample data from multiple datasets with configurable source ratios', 'build a GroupMultiSourceSampler to sample grouped data from multiple datasets by aspect ratio', 'test the MultiSourceSampler iterator to yield infinite batches from concatenated datasets', 'review the GroupMultiSourceSampler _get_source_group_info method that categorizes samples into aspect ratio groups', 'refactor the MultiSourceSampler _infinite_indices method to support custom shuffling strategies', 'create a TrackImgSampler instance with a BaseVideoDataset and optional random seed for video tracking tasks', 'iterate over a TrackImgSampler to get video-frame index tuples for distributed or non-distributed training', 'set the epoch on a TrackImgSampler to control deterministic shuffling across training epochs', 'review the TrackImgSampler constructor to understand how it handles ConcatDataset, ClassBalancedDataset, and BaseVideoDataset wrappers', 'summarize the TrackImgSampler class that provides image-level sampling for video datasets in tracking tasks with distributed support']
```

Usage

```
{'create_TrackImgSampler': 'create a TrackImgSampler instance with a BaseVideoDataset and optional random seed for video tracking tasks', 'iterate_TrackImgSampler': 'iterate over a TrackImgSampler to get video-frame index tuples for distributed or non-distributed training', 'set_epoch_TrackImgSampler': 'set the epoch on a TrackImgSampler to control deterministic shuffling across training epochs', 'review_TrackImgSampler_init': 'review the TrackImgSampler constructor to understand how it handles ConcatDataset, ClassBalancedDataset, and BaseVideoDataset wrappers', 'summarize_TrackImgSampler': 'summarize the TrackImgSampler class that provides image-level sampling for video datasets in tracking tasks with distributed support'}
```

