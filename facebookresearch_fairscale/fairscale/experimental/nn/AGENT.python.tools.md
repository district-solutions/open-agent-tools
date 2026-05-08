# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/experimental/nn/auto_shard.py

Prompts

```
['shard a PyTorch nn.Module into N GraphModule shards using torch.fx tracing and automatic cutpoint detection', 'trace a PyTorch model into a GraphModule while automatically wrapping untracable submodules as leaf nodes', 'split a traced GraphModule into shard cutpoints based on parameter count and skip connection analysis', 'create a mapping from shard IDs to their total parameter counts using node-to-shard assignments', 'look up the parameter count for a node name from a param count dictionary with fallback matching', 'build a MemoryEfficientVocabOutput module with shared proj_weight and tile_factor for memory-efficient softmax', 'create a BaselineSoftmax module with shared proj_weight and optional LMCL margin and scale parameters', 'test the get_data utility function to generate random input weight and target tensors for benchmarking', 'review the MemoryEfficientVocabOutput forward method that fuses fc softmax and nll_loss in a tiled fashion', 'refactor the GetMaxFunction autograd function to compute max-per-token from input and weight tensors', 'create an OffloadModel wrapping an nn.Sequential model to offload parameters to CPU during training', 'split an nn.Sequential model into balanced shards by parameter count using the _split function', 'create a ModelShard wrapping a single model slice with forward_load and forward_drop methods', 'review the OffloadFunction autograd class that enables activation checkpointing at shard boundaries', 'review the ShardSyncLayer autograd class that synchronizes parameter loading between model shards', 'create a SyncBatchNorm layer for distributed training with a custom process group', 'convert all BatchNorm layers in a PyTorch module to SyncBatchNorm for distributed training', 'calculate mean, variance, and inverse standard deviation across distributed processes using all_reduce', 'review the _SyncBatchNormFunction backward pass to understand gradient computation across processes', 'refactor SyncBatchNorm forward to handle checkpointing and recomputing phases in activation checkpointing']
```

Usage

```
{'shard_model_split_nn_module': 'shard a PyTorch nn.Module into N GraphModule shards using torch.fx tracing and automatic cutpoint detection', 'trace_model_with_leaf_modules': 'trace a PyTorch model into a GraphModule while automatically wrapping untracable submodules as leaf nodes', 'split_nodes_find_cutpoints': 'split a traced GraphModule into shard cutpoints based on parameter count and skip connection analysis', 'create_shard_to_param_count_map': 'create a mapping from shard IDs to their total parameter counts using node-to-shard assignments', 'get_count_from_param_dict': 'look up the parameter count for a node name from a param count dictionary with fallback matching'}
```

## File: facebookresearch_fairscale/fairscale/experimental/nn/mevo.py

Prompts

```
['shard a PyTorch nn.Module into N GraphModule shards using torch.fx tracing and automatic cutpoint detection', 'trace a PyTorch model into a GraphModule while automatically wrapping untracable submodules as leaf nodes', 'split a traced GraphModule into shard cutpoints based on parameter count and skip connection analysis', 'create a mapping from shard IDs to their total parameter counts using node-to-shard assignments', 'look up the parameter count for a node name from a param count dictionary with fallback matching', 'build a MemoryEfficientVocabOutput module with shared proj_weight and tile_factor for memory-efficient softmax', 'create a BaselineSoftmax module with shared proj_weight and optional LMCL margin and scale parameters', 'test the get_data utility function to generate random input weight and target tensors for benchmarking', 'review the MemoryEfficientVocabOutput forward method that fuses fc softmax and nll_loss in a tiled fashion', 'refactor the GetMaxFunction autograd function to compute max-per-token from input and weight tensors', 'create an OffloadModel wrapping an nn.Sequential model to offload parameters to CPU during training', 'split an nn.Sequential model into balanced shards by parameter count using the _split function', 'create a ModelShard wrapping a single model slice with forward_load and forward_drop methods', 'review the OffloadFunction autograd class that enables activation checkpointing at shard boundaries', 'review the ShardSyncLayer autograd class that synchronizes parameter loading between model shards', 'create a SyncBatchNorm layer for distributed training with a custom process group', 'convert all BatchNorm layers in a PyTorch module to SyncBatchNorm for distributed training', 'calculate mean, variance, and inverse standard deviation across distributed processes using all_reduce', 'review the _SyncBatchNormFunction backward pass to understand gradient computation across processes', 'refactor SyncBatchNorm forward to handle checkpointing and recomputing phases in activation checkpointing']
```

Usage

```
{'build_memory_efficient_vocab_output': 'build a MemoryEfficientVocabOutput module with shared proj_weight and tile_factor for memory-efficient softmax', 'create_baseline_softmax': 'create a BaselineSoftmax module with shared proj_weight and optional LMCL margin and scale parameters', 'test_get_data': 'test the get_data utility function to generate random input weight and target tensors for benchmarking', 'review_memory_efficient_vocab_output_forward': 'review the MemoryEfficientVocabOutput forward method that fuses fc softmax and nll_loss in a tiled fashion', 'refactor_get_max_function': 'refactor the GetMaxFunction autograd function to compute max-per-token from input and weight tensors'}
```

## File: facebookresearch_fairscale/fairscale/experimental/nn/offload.py

Prompts

```
['shard a PyTorch nn.Module into N GraphModule shards using torch.fx tracing and automatic cutpoint detection', 'trace a PyTorch model into a GraphModule while automatically wrapping untracable submodules as leaf nodes', 'split a traced GraphModule into shard cutpoints based on parameter count and skip connection analysis', 'create a mapping from shard IDs to their total parameter counts using node-to-shard assignments', 'look up the parameter count for a node name from a param count dictionary with fallback matching', 'build a MemoryEfficientVocabOutput module with shared proj_weight and tile_factor for memory-efficient softmax', 'create a BaselineSoftmax module with shared proj_weight and optional LMCL margin and scale parameters', 'test the get_data utility function to generate random input weight and target tensors for benchmarking', 'review the MemoryEfficientVocabOutput forward method that fuses fc softmax and nll_loss in a tiled fashion', 'refactor the GetMaxFunction autograd function to compute max-per-token from input and weight tensors', 'create an OffloadModel wrapping an nn.Sequential model to offload parameters to CPU during training', 'split an nn.Sequential model into balanced shards by parameter count using the _split function', 'create a ModelShard wrapping a single model slice with forward_load and forward_drop methods', 'review the OffloadFunction autograd class that enables activation checkpointing at shard boundaries', 'review the ShardSyncLayer autograd class that synchronizes parameter loading between model shards', 'create a SyncBatchNorm layer for distributed training with a custom process group', 'convert all BatchNorm layers in a PyTorch module to SyncBatchNorm for distributed training', 'calculate mean, variance, and inverse standard deviation across distributed processes using all_reduce', 'review the _SyncBatchNormFunction backward pass to understand gradient computation across processes', 'refactor SyncBatchNorm forward to handle checkpointing and recomputing phases in activation checkpointing']
```

Usage

```
{'create_offload_model': 'create an OffloadModel wrapping an nn.Sequential model to offload parameters to CPU during training', 'split_sequential_model': 'split an nn.Sequential model into balanced shards by parameter count using the _split function', 'create_model_shard': 'create a ModelShard wrapping a single model slice with forward_load and forward_drop methods', 'review_offload_function': 'review the OffloadFunction autograd class that enables activation checkpointing at shard boundaries', 'review_shard_sync_layer': 'review the ShardSyncLayer autograd class that synchronizes parameter loading between model shards'}
```

## File: facebookresearch_fairscale/fairscale/experimental/nn/sync_batchnorm.py

Prompts

```
['shard a PyTorch nn.Module into N GraphModule shards using torch.fx tracing and automatic cutpoint detection', 'trace a PyTorch model into a GraphModule while automatically wrapping untracable submodules as leaf nodes', 'split a traced GraphModule into shard cutpoints based on parameter count and skip connection analysis', 'create a mapping from shard IDs to their total parameter counts using node-to-shard assignments', 'look up the parameter count for a node name from a param count dictionary with fallback matching', 'build a MemoryEfficientVocabOutput module with shared proj_weight and tile_factor for memory-efficient softmax', 'create a BaselineSoftmax module with shared proj_weight and optional LMCL margin and scale parameters', 'test the get_data utility function to generate random input weight and target tensors for benchmarking', 'review the MemoryEfficientVocabOutput forward method that fuses fc softmax and nll_loss in a tiled fashion', 'refactor the GetMaxFunction autograd function to compute max-per-token from input and weight tensors', 'create an OffloadModel wrapping an nn.Sequential model to offload parameters to CPU during training', 'split an nn.Sequential model into balanced shards by parameter count using the _split function', 'create a ModelShard wrapping a single model slice with forward_load and forward_drop methods', 'review the OffloadFunction autograd class that enables activation checkpointing at shard boundaries', 'review the ShardSyncLayer autograd class that synchronizes parameter loading between model shards', 'create a SyncBatchNorm layer for distributed training with a custom process group', 'convert all BatchNorm layers in a PyTorch module to SyncBatchNorm for distributed training', 'calculate mean, variance, and inverse standard deviation across distributed processes using all_reduce', 'review the _SyncBatchNormFunction backward pass to understand gradient computation across processes', 'refactor SyncBatchNorm forward to handle checkpointing and recomputing phases in activation checkpointing']
```

Usage

```
{'create_sync_batchnorm_layer': 'create a SyncBatchNorm layer for distributed training with a custom process group', 'convert_sync_batchnorm': 'convert all BatchNorm layers in a PyTorch module to SyncBatchNorm for distributed training', 'calculate_stats_distributed': 'calculate mean, variance, and inverse standard deviation across distributed processes using all_reduce', 'review_sync_batchnorm_backward': 'review the _SyncBatchNormFunction backward pass to understand gradient computation across processes', 'refactor_sync_batchnorm_checkpointing': 'refactor SyncBatchNorm forward to handle checkpointing and recomputing phases in activation checkpointing'}
```

