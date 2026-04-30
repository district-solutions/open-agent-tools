# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/algorithms/_checkpoint/checkpoint_wrapper.py

Prompts

```
['wrap an nn.Module with activation checkpointing to reduce GPU memory usage during training', 'wrap an nn.Module with activation offloading to save intermediate activations on CPU', 'apply activation checkpointing to all Linear submodules within a PyTorch model', 'wrap a module with reentrant checkpoint implementation to support keyword arguments in checkpointed forward calls', 'create a CheckpointImpl enum value to select between reentrant and non-reentrant checkpoint behavior']
```

Usage

```
{'checkpoint_wrapper_module': 'wrap an nn.Module with activation checkpointing to reduce GPU memory usage during training', 'offload_wrapper_module': 'wrap an nn.Module with activation offloading to save intermediate activations on CPU', 'apply_activation_checkpointing_model': 'apply activation checkpointing to all Linear submodules within a PyTorch model', 'checkpoint_wrapper_reentrant': 'wrap a module with reentrant checkpoint implementation to support keyword arguments in checkpointed forward calls', 'checkpoint_impl_enum': 'create a CheckpointImpl enum value to select between reentrant and non-reentrant checkpoint behavior'}
```

