# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/_composable/checkpoint_activation.py

Prompts

```
['checkpoint a PyTorch nn.Module to apply activation checkpointing without modifying model source code', 'disable checkpoint hooks during backward recomputation to avoid unintentional recursion', 'register a pre-forward hook on a module to initialize the activation checkpoint generator', 'register a post-forward hook on a module to exhaust the activation checkpoint generator', 'access checkpoint state for a module to check or modify enable_hook status', 'create a composable distributed API decorator that validates module parameters, buffers, and sub-modules are not modified', 'build a state retrieval mechanism for a decorated composable API function on an nn.Module instance', 'test the _get_registry function that returns an ordered dict of composable APIs applied to a module', 'run generate_state_key to produce a unique state key string with a UUID suffix', 'review the RegistryItem class used as a marker for tracking registered composable distributed APIs on modules', 'apply fully_shard to a PyTorch module with a policy for automatic wrapping', 'create a fully_sharded model with mixed_precision and cpu_offload options enabled', 'test the fully_shard function with forward_prefetch enabled for efficient data transfer', 'refactor fully_shard to use a custom ShardingStrategy and process_group configuration', 'summarize the pre-forward and post-forward hooks registered by fully_shard on the module', 'create a replicate-wrapped module by calling replicate() on a torch.nn.Module with optional ignored_modules and kwargs', 'test whether a module is already managed by fully_shard using _is_fully_sharded()', 'build a _ReplicateState instance to manage replication state including parameter collection and DDP initialization', 'refactor _ReplicateState._collect_params to gather module parameters while skipping ignored modules and fully_sharded modules', 'review _ReplicateState.init to initialize replication state, register forward hooks, and create an internal DistributedDataParallel instance']
```

Usage

```
{'checkpoint_module_activation': 'checkpoint a PyTorch nn.Module to apply activation checkpointing without modifying model source code', 'disable_hook_during_backward': 'disable checkpoint hooks during backward recomputation to avoid unintentional recursion', 'register_pre_forward_hook': 'register a pre-forward hook on a module to initialize the activation checkpoint generator', 'register_post_forward_hook': 'register a post-forward hook on a module to exhaust the activation checkpoint generator', 'access_checkpoint_state': 'access checkpoint state for a module to check or modify enable_hook status'}
```

## File: pytorch_pytorch/torch/distributed/_composable/contract.py

Prompts

```
['checkpoint a PyTorch nn.Module to apply activation checkpointing without modifying model source code', 'disable checkpoint hooks during backward recomputation to avoid unintentional recursion', 'register a pre-forward hook on a module to initialize the activation checkpoint generator', 'register a post-forward hook on a module to exhaust the activation checkpoint generator', 'access checkpoint state for a module to check or modify enable_hook status', 'create a composable distributed API decorator that validates module parameters, buffers, and sub-modules are not modified', 'build a state retrieval mechanism for a decorated composable API function on an nn.Module instance', 'test the _get_registry function that returns an ordered dict of composable APIs applied to a module', 'run generate_state_key to produce a unique state key string with a UUID suffix', 'review the RegistryItem class used as a marker for tracking registered composable distributed APIs on modules', 'apply fully_shard to a PyTorch module with a policy for automatic wrapping', 'create a fully_sharded model with mixed_precision and cpu_offload options enabled', 'test the fully_shard function with forward_prefetch enabled for efficient data transfer', 'refactor fully_shard to use a custom ShardingStrategy and process_group configuration', 'summarize the pre-forward and post-forward hooks registered by fully_shard on the module', 'create a replicate-wrapped module by calling replicate() on a torch.nn.Module with optional ignored_modules and kwargs', 'test whether a module is already managed by fully_shard using _is_fully_sharded()', 'build a _ReplicateState instance to manage replication state including parameter collection and DDP initialization', 'refactor _ReplicateState._collect_params to gather module parameters while skipping ignored modules and fully_sharded modules', 'review _ReplicateState.init to initialize replication state, register forward hooks, and create an internal DistributedDataParallel instance']
```

Usage

```
{'create_contract_decorator': 'create a composable distributed API decorator that validates module parameters, buffers, and sub-modules are not modified', 'build_contract_state': 'build a state retrieval mechanism for a decorated composable API function on an nn.Module instance', 'test_get_registry': 'test the _get_registry function that returns an ordered dict of composable APIs applied to a module', 'run_generate_state_key': 'run generate_state_key to produce a unique state key string with a UUID suffix', 'review_registry_item': 'review the RegistryItem class used as a marker for tracking registered composable distributed APIs on modules'}
```

## File: pytorch_pytorch/torch/distributed/_composable/fully_shard.py

Prompts

```
['checkpoint a PyTorch nn.Module to apply activation checkpointing without modifying model source code', 'disable checkpoint hooks during backward recomputation to avoid unintentional recursion', 'register a pre-forward hook on a module to initialize the activation checkpoint generator', 'register a post-forward hook on a module to exhaust the activation checkpoint generator', 'access checkpoint state for a module to check or modify enable_hook status', 'create a composable distributed API decorator that validates module parameters, buffers, and sub-modules are not modified', 'build a state retrieval mechanism for a decorated composable API function on an nn.Module instance', 'test the _get_registry function that returns an ordered dict of composable APIs applied to a module', 'run generate_state_key to produce a unique state key string with a UUID suffix', 'review the RegistryItem class used as a marker for tracking registered composable distributed APIs on modules', 'apply fully_shard to a PyTorch module with a policy for automatic wrapping', 'create a fully_sharded model with mixed_precision and cpu_offload options enabled', 'test the fully_shard function with forward_prefetch enabled for efficient data transfer', 'refactor fully_shard to use a custom ShardingStrategy and process_group configuration', 'summarize the pre-forward and post-forward hooks registered by fully_shard on the module', 'create a replicate-wrapped module by calling replicate() on a torch.nn.Module with optional ignored_modules and kwargs', 'test whether a module is already managed by fully_shard using _is_fully_sharded()', 'build a _ReplicateState instance to manage replication state including parameter collection and DDP initialization', 'refactor _ReplicateState._collect_params to gather module parameters while skipping ignored modules and fully_sharded modules', 'review _ReplicateState.init to initialize replication state, register forward hooks, and create an internal DistributedDataParallel instance']
```

Usage

```
{'build_fully_sharded_module': 'apply fully_shard to a PyTorch module with a policy for automatic wrapping', 'create_sharded_model': 'create a fully_sharded model with mixed_precision and cpu_offload options enabled', 'test_fully_shard_forward': 'test the fully_shard function with forward_prefetch enabled for efficient data transfer', 'refactor_fully_shard_strategy': 'refactor fully_shard to use a custom ShardingStrategy and process_group configuration', 'summarize_fully_shard_hooks': 'summarize the pre-forward and post-forward hooks registered by fully_shard on the module'}
```

## File: pytorch_pytorch/torch/distributed/_composable/replicate.py

Prompts

```
['checkpoint a PyTorch nn.Module to apply activation checkpointing without modifying model source code', 'disable checkpoint hooks during backward recomputation to avoid unintentional recursion', 'register a pre-forward hook on a module to initialize the activation checkpoint generator', 'register a post-forward hook on a module to exhaust the activation checkpoint generator', 'access checkpoint state for a module to check or modify enable_hook status', 'create a composable distributed API decorator that validates module parameters, buffers, and sub-modules are not modified', 'build a state retrieval mechanism for a decorated composable API function on an nn.Module instance', 'test the _get_registry function that returns an ordered dict of composable APIs applied to a module', 'run generate_state_key to produce a unique state key string with a UUID suffix', 'review the RegistryItem class used as a marker for tracking registered composable distributed APIs on modules', 'apply fully_shard to a PyTorch module with a policy for automatic wrapping', 'create a fully_sharded model with mixed_precision and cpu_offload options enabled', 'test the fully_shard function with forward_prefetch enabled for efficient data transfer', 'refactor fully_shard to use a custom ShardingStrategy and process_group configuration', 'summarize the pre-forward and post-forward hooks registered by fully_shard on the module', 'create a replicate-wrapped module by calling replicate() on a torch.nn.Module with optional ignored_modules and kwargs', 'test whether a module is already managed by fully_shard using _is_fully_sharded()', 'build a _ReplicateState instance to manage replication state including parameter collection and DDP initialization', 'refactor _ReplicateState._collect_params to gather module parameters while skipping ignored modules and fully_sharded modules', 'review _ReplicateState.init to initialize replication state, register forward hooks, and create an internal DistributedDataParallel instance']
```

Usage

```
{'create_replicate_module': 'create a replicate-wrapped module by calling replicate() on a torch.nn.Module with optional ignored_modules and kwargs', 'test_is_fully_sharded': 'test whether a module is already managed by fully_shard using _is_fully_sharded()', 'build_replicate_state': 'build a _ReplicateState instance to manage replication state including parameter collection and DDP initialization', 'refactor_collect_params': 'refactor _ReplicateState._collect_params to gather module parameters while skipping ignored modules and fully_sharded modules', 'review_replicate_init': 'review _ReplicateState.init to initialize replication state, register forward hooks, and create an internal DistributedDataParallel instance'}
```

