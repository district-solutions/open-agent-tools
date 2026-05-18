# Agent Python Tools

- repo: facebookresearch/metaclip
- repo_uri: https://github.com/facebookresearch/metaclip

## File: facebookresearch_metaclip/apps/mode/src/training/data.py

Prompts

```
['build a python module to load train, val, and imagenet datasets using get_data with args and preprocess functions', 'create a function that builds an ImageNet train or val dataloader with optional subset sampling per class', 'test the get_dataset_fn function to return the correct dataset loader based on dataset type and data path', 'refactor the get_metaclip_dataset function to support additional webdataset iterator configurations', 'review the DataInfo dataclass to understand how dataloader and sampler are structured for distributed training', 'build an IterableDataset subclass that iterates over tarball shards yielding image-text pairs', 'review the IterativeMoDEWebDataset dataset_filter method that filters tar members by cluster assignment', 'create a DataLoader with IterativeMoDEWebDataset for MoDE training using cluster-aware shard filtering', 'refactor the IterativeMoDEWebDataset constructor to load cluster hierarchy and coarse index assignments', 'test the IterativeWebDataset set_epoch method that shuffles shard order per training epoch']
```

Usage

```
{'build_get_data': 'build a python module to load train, val, and imagenet datasets using get_data with args and preprocess functions', 'create_get_imagenet': 'create a function that builds an ImageNet train or val dataloader with optional subset sampling per class', 'test_get_dataset_fn': 'test the get_dataset_fn function to return the correct dataset loader based on dataset type and data path', 'refactor_get_metaclip_dataset': 'refactor the get_metaclip_dataset function to support additional webdataset iterator configurations', 'review_DataInfo': 'review the DataInfo dataclass to understand how dataloader and sampler are structured for distributed training'}
```

## File: facebookresearch_metaclip/apps/mode/src/training/mode_wds.py

Prompts

```
['build a python module to load train, val, and imagenet datasets using get_data with args and preprocess functions', 'create a function that builds an ImageNet train or val dataloader with optional subset sampling per class', 'test the get_dataset_fn function to return the correct dataset loader based on dataset type and data path', 'refactor the get_metaclip_dataset function to support additional webdataset iterator configurations', 'review the DataInfo dataclass to understand how dataloader and sampler are structured for distributed training', 'build an IterableDataset subclass that iterates over tarball shards yielding image-text pairs', 'review the IterativeMoDEWebDataset dataset_filter method that filters tar members by cluster assignment', 'create a DataLoader with IterativeMoDEWebDataset for MoDE training using cluster-aware shard filtering', 'refactor the IterativeMoDEWebDataset constructor to load cluster hierarchy and coarse index assignments', 'test the IterativeWebDataset set_epoch method that shuffles shard order per training epoch']
```

Usage

```
{'build_iterative_webdataset': 'build an IterableDataset subclass that iterates over tarball shards yielding image-text pairs', 'review_iterativemode_webdataset_dataset_filter': 'review the IterativeMoDEWebDataset dataset_filter method that filters tar members by cluster assignment', 'create_get_mode_iter_wds_dataset': 'create a DataLoader with IterativeMoDEWebDataset for MoDE training using cluster-aware shard filtering', 'refactor_iterativemode_webdataset_init': 'refactor the IterativeMoDEWebDataset constructor to load cluster hierarchy and coarse index assignments', 'test_iterative_webdataset_set_epoch': 'test the IterativeWebDataset set_epoch method that shuffles shard order per training epoch'}
```

