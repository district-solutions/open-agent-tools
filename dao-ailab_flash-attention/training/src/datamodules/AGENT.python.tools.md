# Agent Python Tools

- repo: dao-ailab/flash-attention
- repo_uri: https://github.com/dao-ailab/flash-attention

## File: dao-ailab_flash-attention/training/src/datamodules/fault_tolerant_sampler.py

Prompts

```
['create a RandomFaultTolerantSampler instance for fault-tolerant random data sampling in PyTorch', 'build a FaultTolerantDistributedSampler for fault-tolerant distributed data sampling across multiple GPUs', 'test the state_dict and load_state_dict methods for checkpointing and resuming sampler state', 'review the __iter__ methods that resume sampling from the last checkpointed position after restart', 'summarize the fault-tolerant sampling capabilities for PyTorch DataLoader restart scenarios', 'build an ImagenetDataModule LightningDataModule for training with configurable transforms and batch size', 'create train, val, and test DataLoaders from ImagenetDataModule with distributed sampler support', 'test the imagenet_normalization transform with ImageNet mean and std values', 'refactor ImagenetDataModule to convert image tensors to float16 or bfloat16 dtype', 'review Imagenet21kPDataModule that extends ImagenetDataModule with 10450 classes', 'build an LMDataModule to tokenize and cache a HuggingFace dataset for language modeling training', 'create a SHMArray subclass to wrap numpy arrays backed by shared memory for efficient multi-process access', 'run process_dataset to tokenize, concatenate, and cache HuggingFace dataset input_ids in shared memory or disk', 'test loading LMDataModule fault-tolerant state from a PyTorch Lightning checkpoint for resuming training', 'review LMDataModule train, val, and test dataloader methods with fault-tolerant distributed sampling support']
```

Usage

```
{'create_random_fault_tolerant_sampler': 'create a RandomFaultTolerantSampler instance for fault-tolerant random data sampling in PyTorch', 'build_fault_tolerant_distributed_sampler': 'build a FaultTolerantDistributedSampler for fault-tolerant distributed data sampling across multiple GPUs', 'test_state_dict_serialization': 'test the state_dict and load_state_dict methods for checkpointing and resuming sampler state', 'review_fault_tolerant_iteration': 'review the __iter__ methods that resume sampling from the last checkpointed position after restart', 'summarize_sampler_capabilities': 'summarize the fault-tolerant sampling capabilities for PyTorch DataLoader restart scenarios'}
```

## File: dao-ailab_flash-attention/training/src/datamodules/imagenet.py

Prompts

```
['create a RandomFaultTolerantSampler instance for fault-tolerant random data sampling in PyTorch', 'build a FaultTolerantDistributedSampler for fault-tolerant distributed data sampling across multiple GPUs', 'test the state_dict and load_state_dict methods for checkpointing and resuming sampler state', 'review the __iter__ methods that resume sampling from the last checkpointed position after restart', 'summarize the fault-tolerant sampling capabilities for PyTorch DataLoader restart scenarios', 'build an ImagenetDataModule LightningDataModule for training with configurable transforms and batch size', 'create train, val, and test DataLoaders from ImagenetDataModule with distributed sampler support', 'test the imagenet_normalization transform with ImageNet mean and std values', 'refactor ImagenetDataModule to convert image tensors to float16 or bfloat16 dtype', 'review Imagenet21kPDataModule that extends ImagenetDataModule with 10450 classes', 'build an LMDataModule to tokenize and cache a HuggingFace dataset for language modeling training', 'create a SHMArray subclass to wrap numpy arrays backed by shared memory for efficient multi-process access', 'run process_dataset to tokenize, concatenate, and cache HuggingFace dataset input_ids in shared memory or disk', 'test loading LMDataModule fault-tolerant state from a PyTorch Lightning checkpoint for resuming training', 'review LMDataModule train, val, and test dataloader methods with fault-tolerant distributed sampling support']
```

Usage

```
{'build_imagenet_datamodule': 'build an ImagenetDataModule LightningDataModule for training with configurable transforms and batch size', 'create_imagenet_dataloaders': 'create train, val, and test DataLoaders from ImagenetDataModule with distributed sampler support', 'test_imagenet_normalization': 'test the imagenet_normalization transform with ImageNet mean and std values', 'refactor_imagenet_datamodule_dtype': 'refactor ImagenetDataModule to convert image tensors to float16 or bfloat16 dtype', 'review_imagenet21k_datamodule': 'review Imagenet21kPDataModule that extends ImagenetDataModule with 10450 classes'}
```

## File: dao-ailab_flash-attention/training/src/datamodules/language_modeling_hf.py

Prompts

```
['create a RandomFaultTolerantSampler instance for fault-tolerant random data sampling in PyTorch', 'build a FaultTolerantDistributedSampler for fault-tolerant distributed data sampling across multiple GPUs', 'test the state_dict and load_state_dict methods for checkpointing and resuming sampler state', 'review the __iter__ methods that resume sampling from the last checkpointed position after restart', 'summarize the fault-tolerant sampling capabilities for PyTorch DataLoader restart scenarios', 'build an ImagenetDataModule LightningDataModule for training with configurable transforms and batch size', 'create train, val, and test DataLoaders from ImagenetDataModule with distributed sampler support', 'test the imagenet_normalization transform with ImageNet mean and std values', 'refactor ImagenetDataModule to convert image tensors to float16 or bfloat16 dtype', 'review Imagenet21kPDataModule that extends ImagenetDataModule with 10450 classes', 'build an LMDataModule to tokenize and cache a HuggingFace dataset for language modeling training', 'create a SHMArray subclass to wrap numpy arrays backed by shared memory for efficient multi-process access', 'run process_dataset to tokenize, concatenate, and cache HuggingFace dataset input_ids in shared memory or disk', 'test loading LMDataModule fault-tolerant state from a PyTorch Lightning checkpoint for resuming training', 'review LMDataModule train, val, and test dataloader methods with fault-tolerant distributed sampling support']
```

Usage

```
{'build_lm_datamodule': 'build an LMDataModule to tokenize and cache a HuggingFace dataset for language modeling training', 'create_shm_array': 'create a SHMArray subclass to wrap numpy arrays backed by shared memory for efficient multi-process access', 'run_process_dataset': 'run process_dataset to tokenize, concatenate, and cache HuggingFace dataset input_ids in shared memory or disk', 'test_load_datamodule_state': 'test loading LMDataModule fault-tolerant state from a PyTorch Lightning checkpoint for resuming training', 'review_lm_data_loaders': 'review LMDataModule train, val, and test dataloader methods with fault-tolerant distributed sampling support'}
```

