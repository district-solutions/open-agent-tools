# Agent Python Tools

- repo: huggingface/chug
- repo_uri: https://github.com/huggingface/chug

## File: huggingface_chug/src/chug/hfds/collate.py

Prompts

```
['create an HfCollate instance with a list of pipeline functions for use as a DataLoader collate_fn', 'use invoke to call a pipeline stage that accepts an IterableDataset, list, or callable', 'use flatten_bytes to replace nested dicts containing a bytes key with the raw bytes value', 'configure HfCollate with a custom collate function and disable automatic collation', 'enable debug mode on HfCollate to print batch item types and tensor shapes during processing', 'create a PyTorch DataLoader from a HuggingFace dataset source with a specified split and batch size', 'create a streaming DataLoader from a HuggingFace dataset with shuffling and distributed node splitting', 'create a HuggingFace dataset loader that applies a task pipeline for collation before batching', 'create a distributed DataLoader using DistributedSampler for multi-GPU training on a HuggingFace dataset', 'disable automatic decoding of Image and Audio columns in a HuggingFace dataset to reduce memory usage', 'create a SafeDataset wrapper that retries up to 10 times on corrupt data items', 'create a WrappedIterableDataset that sets epoch on the underlying dataset during iteration', 'review the SafeDataset __getitem__ method and its retry logic for handling exceptions', 'refactor the set_interval_count method to support a new shared counter type', 'test the SafeDataset retry mechanism by passing a dataset that raises exceptions on access']
```

Usage

```
{'create_HfCollate_with_pipeline': 'create an HfCollate instance with a list of pipeline functions for use as a DataLoader collate_fn', 'use_invoke_pipeline_stage': 'use invoke to call a pipeline stage that accepts an IterableDataset, list, or callable', 'flatten_bytes_nested_dicts': 'use flatten_bytes to replace nested dicts containing a bytes key with the raw bytes value', 'configure_HfCollate_custom_collate': 'configure HfCollate with a custom collate function and disable automatic collation', 'debug_HfCollate_batch_processing': 'enable debug mode on HfCollate to print batch item types and tensor shapes during processing'}
```

## File: huggingface_chug/src/chug/hfds/loader.py

Prompts

```
['create an HfCollate instance with a list of pipeline functions for use as a DataLoader collate_fn', 'use invoke to call a pipeline stage that accepts an IterableDataset, list, or callable', 'use flatten_bytes to replace nested dicts containing a bytes key with the raw bytes value', 'configure HfCollate with a custom collate function and disable automatic collation', 'enable debug mode on HfCollate to print batch item types and tensor shapes during processing', 'create a PyTorch DataLoader from a HuggingFace dataset source with a specified split and batch size', 'create a streaming DataLoader from a HuggingFace dataset with shuffling and distributed node splitting', 'create a HuggingFace dataset loader that applies a task pipeline for collation before batching', 'create a distributed DataLoader using DistributedSampler for multi-GPU training on a HuggingFace dataset', 'disable automatic decoding of Image and Audio columns in a HuggingFace dataset to reduce memory usage', 'create a SafeDataset wrapper that retries up to 10 times on corrupt data items', 'create a WrappedIterableDataset that sets epoch on the underlying dataset during iteration', 'review the SafeDataset __getitem__ method and its retry logic for handling exceptions', 'refactor the set_interval_count method to support a new shared counter type', 'test the SafeDataset retry mechanism by passing a dataset that raises exceptions on access']
```

Usage

```
{'create_hf_loader': 'create a PyTorch DataLoader from a HuggingFace dataset source with a specified split and batch size', 'create_hf_streaming_loader': 'create a streaming DataLoader from a HuggingFace dataset with shuffling and distributed node splitting', 'create_hf_loader_with_pipeline': 'create a HuggingFace dataset loader that applies a task pipeline for collation before batching', 'create_hf_distributed_loader': 'create a distributed DataLoader using DistributedSampler for multi-GPU training on a HuggingFace dataset', 'disable_decode_hf_dataset': 'disable automatic decoding of Image and Audio columns in a HuggingFace dataset to reduce memory usage'}
```

## File: huggingface_chug/src/chug/hfds/wrappers.py

Prompts

```
['create an HfCollate instance with a list of pipeline functions for use as a DataLoader collate_fn', 'use invoke to call a pipeline stage that accepts an IterableDataset, list, or callable', 'use flatten_bytes to replace nested dicts containing a bytes key with the raw bytes value', 'configure HfCollate with a custom collate function and disable automatic collation', 'enable debug mode on HfCollate to print batch item types and tensor shapes during processing', 'create a PyTorch DataLoader from a HuggingFace dataset source with a specified split and batch size', 'create a streaming DataLoader from a HuggingFace dataset with shuffling and distributed node splitting', 'create a HuggingFace dataset loader that applies a task pipeline for collation before batching', 'create a distributed DataLoader using DistributedSampler for multi-GPU training on a HuggingFace dataset', 'disable automatic decoding of Image and Audio columns in a HuggingFace dataset to reduce memory usage', 'create a SafeDataset wrapper that retries up to 10 times on corrupt data items', 'create a WrappedIterableDataset that sets epoch on the underlying dataset during iteration', 'review the SafeDataset __getitem__ method and its retry logic for handling exceptions', 'refactor the set_interval_count method to support a new shared counter type', 'test the SafeDataset retry mechanism by passing a dataset that raises exceptions on access']
```

Usage

```
{'create_safe_dataset': 'create a SafeDataset wrapper that retries up to 10 times on corrupt data items', 'create_wrapped_iterable_dataset': 'create a WrappedIterableDataset that sets epoch on the underlying dataset during iteration', 'review_safe_dataset_getitem': 'review the SafeDataset __getitem__ method and its retry logic for handling exceptions', 'refactor_wrapped_iterable_dataset_set_interval_count': 'refactor the set_interval_count method to support a new shared counter type', 'test_safe_dataset_retry': 'test the SafeDataset retry mechanism by passing a dataset that raises exceptions on access'}
```

