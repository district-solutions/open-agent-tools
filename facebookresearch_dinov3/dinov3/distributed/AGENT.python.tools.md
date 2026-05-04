# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/distributed/torch_distributed_primitives.py

Prompts

```
['reduce a dictionary of torch tensors across all DDP processes and return averaged results', 'reduce a dictionary of torch tensors across all DDP processes and return summed results without averaging', 'gather all tensors from multiple DDP processes into a single list broadcasted to all processes', 'gather tensors of varying shapes from DDP processes by padding to max size then truncating', 'gather scalar tensors from all DDP processes into a list using simple all_gather', 'enable distributed training with NCCL backend and auto-detect TorchElastic, Slurm, or manual environment', 'disable distributed training and destroy all process groups and restore builtin print', 'check if distributed training is currently enabled and initialized', 'get the current process rank and world size for the default or specified process group', 'create new process subgroups from a sequence of rank sequences for subgroup communication']
```

Usage

```
{'reduce_dict_average': 'reduce a dictionary of torch tensors across all DDP processes and return averaged results', 'reduce_dict_sum': 'reduce a dictionary of torch tensors across all DDP processes and return summed results without averaging', 'gather_all_tensors_equal_shape': 'gather all tensors from multiple DDP processes into a single list broadcasted to all processes', 'gather_all_tensors_variable_shape': 'gather tensors of varying shapes from DDP processes by padding to max size then truncating', 'gather_all_tensors_scalar': 'gather scalar tensors from all DDP processes into a list using simple all_gather'}
```

## File: facebookresearch_dinov3/dinov3/distributed/torch_distributed_wrapper.py

Prompts

```
['reduce a dictionary of torch tensors across all DDP processes and return averaged results', 'reduce a dictionary of torch tensors across all DDP processes and return summed results without averaging', 'gather all tensors from multiple DDP processes into a single list broadcasted to all processes', 'gather tensors of varying shapes from DDP processes by padding to max size then truncating', 'gather scalar tensors from all DDP processes into a list using simple all_gather', 'enable distributed training with NCCL backend and auto-detect TorchElastic, Slurm, or manual environment', 'disable distributed training and destroy all process groups and restore builtin print', 'check if distributed training is currently enabled and initialized', 'get the current process rank and world size for the default or specified process group', 'create new process subgroups from a sequence of rank sequences for subgroup communication']
```

Usage

```
{'enable_distributed_training': 'enable distributed training with NCCL backend and auto-detect TorchElastic, Slurm, or manual environment', 'disable_distributed_training': 'disable distributed training and destroy all process groups and restore builtin print', 'check_distributed_enabled': 'check if distributed training is currently enabled and initialized', 'get_rank_and_world_size': 'get the current process rank and world size for the default or specified process group', 'create_process_subgroups': 'create new process subgroups from a sequence of rank sequences for subgroup communication'}
```

