# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/nn/data_parallel/fsdp_optim_utils.py

Prompts

```
['shard a full optimizer state dict for FSDP by mapping global param IDs to local ones', 'validate that the number of FSDP instances matches the optimizer state param count before sharding', 'build an unflattened non-sharded optimizer state dict from gathered per-rank FSDP state dicts on rank 0', 'check if a PyTorch tensor is dimensionless with zero dimensions for FSDP optimizer state handling', 'convert optimizer state for flattened FSDP parameters back into original unflattened parameter shapes', 'wrap a PyTorch nn.Module with FullyShardedDataParallel to shard parameters across data parallel workers', 'run a forward pass with FSDP wrapped module using mixed precision FP16 computation and FP32 master weights', 'gather the full consolidated optimizer state dict from all FSDP ranks using gather_full_optim_state_dict', 'consolidate sharded checkpoint weights from multiple ranks into a single unsharded state dict using consolidate_shard_weights', 'auto wrap all BatchNorm layers in a module with a special single-rank FSDP instance using auto_wrap_bn', 'build a ShardedDataParallel wrapper around a PyTorch module with an OSS sharded optimizer for gradient sharding', 'create a forward pass through a ShardedDataParallel model that primes automatic gradient reduction to the correct rank', 'test the ShardedDataParallel refresh_trainable method to update assumptions after freezing or unfreezing model parameters', 'review the ShardedDataParallel no_sync context manager to disable gradient synchronization for gradient accumulation', 'summarize the ShardedDataParallel sync_buffers method which broadcasts model buffers including batch norm statistics across ranks']
```

Usage

```
{'flatten_optim_state_dict': 'shard a full optimizer state dict for FSDP by mapping global param IDs to local ones', 'check_param_counts_before_sharding': 'validate that the number of FSDP instances matches the optimizer state param count before sharding', 'build_unflat_state_dict': 'build an unflattened non-sharded optimizer state dict from gathered per-rank FSDP state dicts on rank 0', 'is_singleton_tensor': 'check if a PyTorch tensor is dimensionless with zero dimensions for FSDP optimizer state handling', 'unflatten_optim_state': 'convert optimizer state for flattened FSDP parameters back into original unflattened parameter shapes'}
```

## File: facebookresearch_fairscale/fairscale/nn/data_parallel/fully_sharded_data_parallel.py

Prompts

```
['shard a full optimizer state dict for FSDP by mapping global param IDs to local ones', 'validate that the number of FSDP instances matches the optimizer state param count before sharding', 'build an unflattened non-sharded optimizer state dict from gathered per-rank FSDP state dicts on rank 0', 'check if a PyTorch tensor is dimensionless with zero dimensions for FSDP optimizer state handling', 'convert optimizer state for flattened FSDP parameters back into original unflattened parameter shapes', 'wrap a PyTorch nn.Module with FullyShardedDataParallel to shard parameters across data parallel workers', 'run a forward pass with FSDP wrapped module using mixed precision FP16 computation and FP32 master weights', 'gather the full consolidated optimizer state dict from all FSDP ranks using gather_full_optim_state_dict', 'consolidate sharded checkpoint weights from multiple ranks into a single unsharded state dict using consolidate_shard_weights', 'auto wrap all BatchNorm layers in a module with a special single-rank FSDP instance using auto_wrap_bn', 'build a ShardedDataParallel wrapper around a PyTorch module with an OSS sharded optimizer for gradient sharding', 'create a forward pass through a ShardedDataParallel model that primes automatic gradient reduction to the correct rank', 'test the ShardedDataParallel refresh_trainable method to update assumptions after freezing or unfreezing model parameters', 'review the ShardedDataParallel no_sync context manager to disable gradient synchronization for gradient accumulation', 'summarize the ShardedDataParallel sync_buffers method which broadcasts model buffers including batch norm statistics across ranks']
```

Usage

```
{'wrap_module_with_fsdp': 'wrap a PyTorch nn.Module with FullyShardedDataParallel to shard parameters across data parallel workers', 'fsdp_mixed_precision_forward': 'run a forward pass with FSDP wrapped module using mixed precision FP16 computation and FP32 master weights', 'fsdp_gather_full_optim_state': 'gather the full consolidated optimizer state dict from all FSDP ranks using gather_full_optim_state_dict', 'fsdp_consolidate_shard_weights': 'consolidate sharded checkpoint weights from multiple ranks into a single unsharded state dict using consolidate_shard_weights', 'fsdp_auto_wrap_batchnorm': 'auto wrap all BatchNorm layers in a module with a special single-rank FSDP instance using auto_wrap_bn'}
```

## File: facebookresearch_fairscale/fairscale/nn/data_parallel/sharded_ddp.py

Prompts

```
['shard a full optimizer state dict for FSDP by mapping global param IDs to local ones', 'validate that the number of FSDP instances matches the optimizer state param count before sharding', 'build an unflattened non-sharded optimizer state dict from gathered per-rank FSDP state dicts on rank 0', 'check if a PyTorch tensor is dimensionless with zero dimensions for FSDP optimizer state handling', 'convert optimizer state for flattened FSDP parameters back into original unflattened parameter shapes', 'wrap a PyTorch nn.Module with FullyShardedDataParallel to shard parameters across data parallel workers', 'run a forward pass with FSDP wrapped module using mixed precision FP16 computation and FP32 master weights', 'gather the full consolidated optimizer state dict from all FSDP ranks using gather_full_optim_state_dict', 'consolidate sharded checkpoint weights from multiple ranks into a single unsharded state dict using consolidate_shard_weights', 'auto wrap all BatchNorm layers in a module with a special single-rank FSDP instance using auto_wrap_bn', 'build a ShardedDataParallel wrapper around a PyTorch module with an OSS sharded optimizer for gradient sharding', 'create a forward pass through a ShardedDataParallel model that primes automatic gradient reduction to the correct rank', 'test the ShardedDataParallel refresh_trainable method to update assumptions after freezing or unfreezing model parameters', 'review the ShardedDataParallel no_sync context manager to disable gradient synchronization for gradient accumulation', 'summarize the ShardedDataParallel sync_buffers method which broadcasts model buffers including batch norm statistics across ranks']
```

Usage

```
{'build_sharded_ddp_wrapper': 'build a ShardedDataParallel wrapper around a PyTorch module with an OSS sharded optimizer for gradient sharding', 'create_sdp_forward_pass': 'create a forward pass through a ShardedDataParallel model that primes automatic gradient reduction to the correct rank', 'test_refresh_trainable': 'test the ShardedDataParallel refresh_trainable method to update assumptions after freezing or unfreezing model parameters', 'review_no_sync_context': 'review the ShardedDataParallel no_sync context manager to disable gradient synchronization for gradient accumulation', 'summarize_sync_buffers': 'summarize the ShardedDataParallel sync_buffers method which broadcasts model buffers including batch norm statistics across ranks'}
```

