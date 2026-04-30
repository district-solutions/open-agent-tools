# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/pipeline/sync/_balance/blockpartition.py

Prompts

```
['build a function to split a sequence into partitions that minimize variance using block partitioning', 'create a function call to solve with a list of integers and a partition count to return balanced sublists', 'test the solve function with evenly distributed integers to verify balanced partition output', 'test the solve function with uneven integers to verify minimal variance across partitions', 'test the solve function with invalid partition count to verify ValueError is raised', 'profile elapsed execution times per layer in a PyTorch sequential module with a timeout', 'profile CUDA memory usage per layer in a PyTorch sequential module with parameter scaling', 'create deep copies of sequential module layers on a target device for safe profiling', 'detach batch tensors from the autograd graph while preserving requires_grad flags', 'summarize per-layer profiling results for execution time and memory size in a PyTorch model']
```

Usage

```
{'build_block_partition': 'build a function to split a sequence into partitions that minimize variance using block partitioning', 'create_solve_partition': 'create a function call to solve with a list of integers and a partition count to return balanced sublists', 'test_solve_balanced': 'test the solve function with evenly distributed integers to verify balanced partition output', 'test_solve_uneven': 'test the solve function with uneven integers to verify minimal variance across partitions', 'test_solve_error': 'test the solve function with invalid partition count to verify ValueError is raised'}
```

## File: pytorch_pytorch/torch/distributed/pipeline/sync/_balance/profile.py

Prompts

```
['build a function to split a sequence into partitions that minimize variance using block partitioning', 'create a function call to solve with a list of integers and a partition count to return balanced sublists', 'test the solve function with evenly distributed integers to verify balanced partition output', 'test the solve function with uneven integers to verify minimal variance across partitions', 'test the solve function with invalid partition count to verify ValueError is raised', 'profile elapsed execution times per layer in a PyTorch sequential module with a timeout', 'profile CUDA memory usage per layer in a PyTorch sequential module with parameter scaling', 'create deep copies of sequential module layers on a target device for safe profiling', 'detach batch tensors from the autograd graph while preserving requires_grad flags', 'summarize per-layer profiling results for execution time and memory size in a PyTorch model']
```

Usage

```
{'profile_layer_execution_times': 'profile elapsed execution times per layer in a PyTorch sequential module with a timeout', 'profile_cuda_memory_sizes': 'profile CUDA memory usage per layer in a PyTorch sequential module with parameter scaling', 'create_layerwise_sandbox_copies': 'create deep copies of sequential module layers on a target device for safe profiling', 'detach_batch_tensors': 'detach batch tensors from the autograd graph while preserving requires_grad flags', 'summarize_profile_module': 'summarize per-layer profiling results for execution time and memory size in a PyTorch model'}
```

