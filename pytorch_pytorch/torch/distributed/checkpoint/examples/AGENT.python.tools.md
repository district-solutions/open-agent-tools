# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/checkpoint/examples/async_checkpointing_example.py

Prompts

```
['build an async distributed checkpointing trainer with FSDP model, async save, and fault recovery', 'create a PyTorch model wrapped in FSDP with async filesystem checkpointing and state dict patching', 'run distributed training with async periodic checkpointing, fault injection, and checkpoint reload recovery', 'test async checkpoint save and load with _FileSystemCheckpointer for model and optimizer state dicts', 'review _init_model function that sets up device mesh, FSDP wrapping, optimizer, and state dict patching', 'save a sharded FSDP model and optimizer state dict to a filesystem checkpoint directory', 'load a sharded FSDP model state dict from a filesystem checkpoint directory', 'load a sharded optimizer state dict from a distributed checkpoint storage reader', 'create a FSDP state dict context manager using SHARDED_STATE_DICT type for checkpointing', 'spawn distributed FSDP checkpoint processes using torch.multiprocessing across CUDA devices', 'save a stateful FSDP model and optimizer checkpoint to the filesystem using _FileSystemCheckpointer', 'load a stateful FSDP model and optimizer checkpoint from the filesystem using _FileSystemCheckpointer', 'make a PyTorch model and optimizer stateful for distributed checkpointing with _patch_model_state_dict and _patch_optimizer_state_dict', 'initialize a FullyShardedDataParallel model with device mesh and Adam optimizer for distributed training']
```

Usage

```
{'build_async_checkpointing_trainer': 'build an async distributed checkpointing trainer with FSDP model, async save, and fault recovery', 'create_model_fsdp_checkpoint': 'create a PyTorch model wrapped in FSDP with async filesystem checkpointing and state dict patching', 'run_distributed_training': 'run distributed training with async periodic checkpointing, fault injection, and checkpoint reload recovery', 'test_checkpoint_save_load': 'test async checkpoint save and load with _FileSystemCheckpointer for model and optimizer state dicts', 'review_init_model_setup': 'review _init_model function that sets up device mesh, FSDP wrapping, optimizer, and state dict patching'}
```

## File: pytorch_pytorch/torch/distributed/checkpoint/examples/fsdp_checkpoint_example.py

Prompts

```
['build an async distributed checkpointing trainer with FSDP model, async save, and fault recovery', 'create a PyTorch model wrapped in FSDP with async filesystem checkpointing and state dict patching', 'run distributed training with async periodic checkpointing, fault injection, and checkpoint reload recovery', 'test async checkpoint save and load with _FileSystemCheckpointer for model and optimizer state dicts', 'review _init_model function that sets up device mesh, FSDP wrapping, optimizer, and state dict patching', 'save a sharded FSDP model and optimizer state dict to a filesystem checkpoint directory', 'load a sharded FSDP model state dict from a filesystem checkpoint directory', 'load a sharded optimizer state dict from a distributed checkpoint storage reader', 'create a FSDP state dict context manager using SHARDED_STATE_DICT type for checkpointing', 'spawn distributed FSDP checkpoint processes using torch.multiprocessing across CUDA devices', 'save a stateful FSDP model and optimizer checkpoint to the filesystem using _FileSystemCheckpointer', 'load a stateful FSDP model and optimizer checkpoint from the filesystem using _FileSystemCheckpointer', 'make a PyTorch model and optimizer stateful for distributed checkpointing with _patch_model_state_dict and _patch_optimizer_state_dict', 'initialize a FullyShardedDataParallel model with device mesh and Adam optimizer for distributed training']
```

Usage

```
{'save_fsdp_sharded_checkpoint': 'save a sharded FSDP model and optimizer state dict to a filesystem checkpoint directory', 'load_fsdp_sharded_checkpoint': 'load a sharded FSDP model state dict from a filesystem checkpoint directory', 'load_sharded_optimizer_state_dict': 'load a sharded optimizer state dict from a distributed checkpoint storage reader', 'create_fsdp_state_dict_type': 'create a FSDP state dict context manager using SHARDED_STATE_DICT type for checkpointing', 'spawn_fsdp_checkpoint_process': 'spawn distributed FSDP checkpoint processes using torch.multiprocessing across CUDA devices'}
```

## File: pytorch_pytorch/torch/distributed/checkpoint/examples/stateful_example.py

Prompts

```
['build an async distributed checkpointing trainer with FSDP model, async save, and fault recovery', 'create a PyTorch model wrapped in FSDP with async filesystem checkpointing and state dict patching', 'run distributed training with async periodic checkpointing, fault injection, and checkpoint reload recovery', 'test async checkpoint save and load with _FileSystemCheckpointer for model and optimizer state dicts', 'review _init_model function that sets up device mesh, FSDP wrapping, optimizer, and state dict patching', 'save a sharded FSDP model and optimizer state dict to a filesystem checkpoint directory', 'load a sharded FSDP model state dict from a filesystem checkpoint directory', 'load a sharded optimizer state dict from a distributed checkpoint storage reader', 'create a FSDP state dict context manager using SHARDED_STATE_DICT type for checkpointing', 'spawn distributed FSDP checkpoint processes using torch.multiprocessing across CUDA devices', 'save a stateful FSDP model and optimizer checkpoint to the filesystem using _FileSystemCheckpointer', 'load a stateful FSDP model and optimizer checkpoint from the filesystem using _FileSystemCheckpointer', 'make a PyTorch model and optimizer stateful for distributed checkpointing with _patch_model_state_dict and _patch_optimizer_state_dict', 'initialize a FullyShardedDataParallel model with device mesh and Adam optimizer for distributed training']
```

Usage

```
{'save_stateful_checkpoint': 'save a stateful FSDP model and optimizer checkpoint to the filesystem using _FileSystemCheckpointer', 'load_stateful_checkpoint': 'load a stateful FSDP model and optimizer checkpoint from the filesystem using _FileSystemCheckpointer', 'make_stateful_model': 'make a PyTorch model and optimizer stateful for distributed checkpointing with _patch_model_state_dict and _patch_optimizer_state_dict', 'initialize_fsdp_model': 'initialize a FullyShardedDataParallel model with device mesh and Adam optimizer for distributed training', 'run_distributed_training': 'run distributed multi-process training with torch.multiprocessing.spawn and FSDP checkpointing'}
```

