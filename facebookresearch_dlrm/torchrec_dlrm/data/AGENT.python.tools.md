# Agent Python Tools

- repo: facebookresearch/dlrm
- repo_uri: https://github.com/facebookresearch/dlrm

## File: facebookresearch_dlrm/torchrec_dlrm/data/dlrm_dataloader.py

Prompts

```
['get a PyTorch DataLoader for train, val, or test stage using command line args and a distributed backend', 'get a DataLoader wrapping a RandomRecDataset with synthetic random Criteo-style data for the given stage', 'get a DataLoader wrapping an InMemoryBinaryCriteoIterDataPipe or MultiHotCriteoIterDataPipe from binary numpy files on disk', 'review the get_dataloader function to understand how it routes between random and in-memory data loaders based on args', 'refactor the _get_in_memory_dataloader function to support additional dataset formats beyond criteo_kaggle and criteo_1tb', 'create a MultiHotCriteoIterDataPipe datapipe instance with dense sparse and label file paths for distributed training', 'build a MultiHotCriteoIterDataPipe with mmap_mode enabled to memory map dense and label numpy arrays', 'iterate over a MultiHotCriteoIterDataPipe to yield Batch objects containing dense features sparse features and labels', 'load a sparse multi-hot feature array from an npz file using memmap via the _load_from_npz method', 'convert numpy dense sparse and label arrays into a Batch object with KeyedJaggedTensor sparse features']
```

Usage

```
{'get_dataloader': 'get a PyTorch DataLoader for train, val, or test stage using command line args and a distributed backend', 'get_random_dataloader': 'get a DataLoader wrapping a RandomRecDataset with synthetic random Criteo-style data for the given stage', 'get_in_memory_dataloader': 'get a DataLoader wrapping an InMemoryBinaryCriteoIterDataPipe or MultiHotCriteoIterDataPipe from binary numpy files on disk', 'review_get_dataloader': 'review the get_dataloader function to understand how it routes between random and in-memory data loaders based on args', 'refactor_get_in_memory_dataloader': 'refactor the _get_in_memory_dataloader function to support additional dataset formats beyond criteo_kaggle and criteo_1tb'}
```

## File: facebookresearch_dlrm/torchrec_dlrm/data/multi_hot_criteo.py

Prompts

```
['get a PyTorch DataLoader for train, val, or test stage using command line args and a distributed backend', 'get a DataLoader wrapping a RandomRecDataset with synthetic random Criteo-style data for the given stage', 'get a DataLoader wrapping an InMemoryBinaryCriteoIterDataPipe or MultiHotCriteoIterDataPipe from binary numpy files on disk', 'review the get_dataloader function to understand how it routes between random and in-memory data loaders based on args', 'refactor the _get_in_memory_dataloader function to support additional dataset formats beyond criteo_kaggle and criteo_1tb', 'create a MultiHotCriteoIterDataPipe datapipe instance with dense sparse and label file paths for distributed training', 'build a MultiHotCriteoIterDataPipe with mmap_mode enabled to memory map dense and label numpy arrays', 'iterate over a MultiHotCriteoIterDataPipe to yield Batch objects containing dense features sparse features and labels', 'load a sparse multi-hot feature array from an npz file using memmap via the _load_from_npz method', 'convert numpy dense sparse and label arrays into a Batch object with KeyedJaggedTensor sparse features']
```

Usage

```
{'create_MultiHotCriteoIterDataPipe': 'create a MultiHotCriteoIterDataPipe datapipe instance with dense sparse and label file paths for distributed training', 'build_MultiHotCriteoIterDataPipe_with_mmap': 'build a MultiHotCriteoIterDataPipe with mmap_mode enabled to memory map dense and label numpy arrays', 'iterate_MultiHotCriteoIterDataPipe_batches': 'iterate over a MultiHotCriteoIterDataPipe to yield Batch objects containing dense features sparse features and labels', 'load_sparse_from_npz': 'load a sparse multi-hot feature array from an npz file using memmap via the _load_from_npz method', 'convert_arrays_to_batch': 'convert numpy dense sparse and label arrays into a Batch object with KeyedJaggedTensor sparse features'}
```

