# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/utils/checkpoint.py

Prompts

```
['load a state_dict into a PyTorch module with optional strict matching and mismatch warnings', 'create a PyTorch Lightning CheckpointCallback that disables checkpointing after validation to avoid DDP hanging', 'use the IncompatibleKeys namedtuple to track missing and unexpected keys when loading model state dicts', 'review the load_state_dict function strict mode behavior that raises RuntimeError on key mismatches', 'handle loading state dicts into modules wrapped in DistributedDataParallel by unwrapping before loading', 'load a YAML config file with OmegaConf interpolation and return it as a frozen yacs CfgNode', 'recursively convert an OmegaConf DictConfig or ListConfig to a plain Python dictionary resolving interpolations where possible', 'convert all keys in a dictionary to lowercase and return the new dictionary', 'review the get_config function that loads YAML configs with OmegaConf interpolation support into a yacs CfgNode', 'test the resolve_omegaconf_to_dict function with a DictConfig containing variable interpolation references', 'create a function to recursively transfer a batch of tensors to a target device like cuda or numpy', 'check if the torch distributed environment has been initialized and is available for multi-process communication', 'get the current process rank and world size as a tuple from the distributed process group', 'broadcast a tensor from a source rank to all other ranks in the distributed process group', 'collect and aggregate result lists from all distributed ranks into a single ordered list on rank zero', 'get a multi-GPU-friendly Python logger using the default module name', 'get a multi-GPU-friendly Python logger with a custom name for a specific module', 'use the returned logger to log info messages that only print on rank zero', 'use the returned logger to log debug messages that only print on rank zero', 'use the returned logger to log error messages that only print on rank zero']
```

Usage

```
{'load_state_dict_to_module': 'load a state_dict into a PyTorch module with optional strict matching and mismatch warnings', 'create_checkpoint_callback': 'create a PyTorch Lightning CheckpointCallback that disables checkpointing after validation to avoid DDP hanging', 'use_incompatible_keys_namedtuple': 'use the IncompatibleKeys namedtuple to track missing and unexpected keys when loading model state dicts', 'review_load_state_dict_strict_mode': 'review the load_state_dict function strict mode behavior that raises RuntimeError on key mismatches', 'handle_ddp_wrapped_modules': 'handle loading state dicts into modules wrapped in DistributedDataParallel by unwrapping before loading'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/utils/config.py

Prompts

```
['load a state_dict into a PyTorch module with optional strict matching and mismatch warnings', 'create a PyTorch Lightning CheckpointCallback that disables checkpointing after validation to avoid DDP hanging', 'use the IncompatibleKeys namedtuple to track missing and unexpected keys when loading model state dicts', 'review the load_state_dict function strict mode behavior that raises RuntimeError on key mismatches', 'handle loading state dicts into modules wrapped in DistributedDataParallel by unwrapping before loading', 'load a YAML config file with OmegaConf interpolation and return it as a frozen yacs CfgNode', 'recursively convert an OmegaConf DictConfig or ListConfig to a plain Python dictionary resolving interpolations where possible', 'convert all keys in a dictionary to lowercase and return the new dictionary', 'review the get_config function that loads YAML configs with OmegaConf interpolation support into a yacs CfgNode', 'test the resolve_omegaconf_to_dict function with a DictConfig containing variable interpolation references', 'create a function to recursively transfer a batch of tensors to a target device like cuda or numpy', 'check if the torch distributed environment has been initialized and is available for multi-process communication', 'get the current process rank and world size as a tuple from the distributed process group', 'broadcast a tensor from a source rank to all other ranks in the distributed process group', 'collect and aggregate result lists from all distributed ranks into a single ordered list on rank zero', 'get a multi-GPU-friendly Python logger using the default module name', 'get a multi-GPU-friendly Python logger with a custom name for a specific module', 'use the returned logger to log info messages that only print on rank zero', 'use the returned logger to log debug messages that only print on rank zero', 'use the returned logger to log error messages that only print on rank zero']
```

Usage

```
{'get_config_from_yaml': 'load a YAML config file with OmegaConf interpolation and return it as a frozen yacs CfgNode', 'resolve_omegaconf_to_dict': 'recursively convert an OmegaConf DictConfig or ListConfig to a plain Python dictionary resolving interpolations where possible', 'to_lower_dict_keys': 'convert all keys in a dictionary to lowercase and return the new dictionary', 'review_get_config': 'review the get_config function that loads YAML configs with OmegaConf interpolation support into a yacs CfgNode', 'test_resolve_omegaconf_to_dict': 'test the resolve_omegaconf_to_dict function with a DictConfig containing variable interpolation references'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/utils/dist.py

Prompts

```
['load a state_dict into a PyTorch module with optional strict matching and mismatch warnings', 'create a PyTorch Lightning CheckpointCallback that disables checkpointing after validation to avoid DDP hanging', 'use the IncompatibleKeys namedtuple to track missing and unexpected keys when loading model state dicts', 'review the load_state_dict function strict mode behavior that raises RuntimeError on key mismatches', 'handle loading state dicts into modules wrapped in DistributedDataParallel by unwrapping before loading', 'load a YAML config file with OmegaConf interpolation and return it as a frozen yacs CfgNode', 'recursively convert an OmegaConf DictConfig or ListConfig to a plain Python dictionary resolving interpolations where possible', 'convert all keys in a dictionary to lowercase and return the new dictionary', 'review the get_config function that loads YAML configs with OmegaConf interpolation support into a yacs CfgNode', 'test the resolve_omegaconf_to_dict function with a DictConfig containing variable interpolation references', 'create a function to recursively transfer a batch of tensors to a target device like cuda or numpy', 'check if the torch distributed environment has been initialized and is available for multi-process communication', 'get the current process rank and world size as a tuple from the distributed process group', 'broadcast a tensor from a source rank to all other ranks in the distributed process group', 'collect and aggregate result lists from all distributed ranks into a single ordered list on rank zero', 'get a multi-GPU-friendly Python logger using the default module name', 'get a multi-GPU-friendly Python logger with a custom name for a specific module', 'use the returned logger to log info messages that only print on rank zero', 'use the returned logger to log debug messages that only print on rank zero', 'use the returned logger to log error messages that only print on rank zero']
```

Usage

```
{'recursive_to': 'create a function to recursively transfer a batch of tensors to a target device like cuda or numpy', 'is_distributed': 'check if the torch distributed environment has been initialized and is available for multi-process communication', 'get_dist_info': 'get the current process rank and world size as a tuple from the distributed process group', 'broadcast': 'broadcast a tensor from a source rank to all other ranks in the distributed process group', 'collect_results': 'collect and aggregate result lists from all distributed ranks into a single ordered list on rank zero'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/utils/logging.py

Prompts

```
['load a state_dict into a PyTorch module with optional strict matching and mismatch warnings', 'create a PyTorch Lightning CheckpointCallback that disables checkpointing after validation to avoid DDP hanging', 'use the IncompatibleKeys namedtuple to track missing and unexpected keys when loading model state dicts', 'review the load_state_dict function strict mode behavior that raises RuntimeError on key mismatches', 'handle loading state dicts into modules wrapped in DistributedDataParallel by unwrapping before loading', 'load a YAML config file with OmegaConf interpolation and return it as a frozen yacs CfgNode', 'recursively convert an OmegaConf DictConfig or ListConfig to a plain Python dictionary resolving interpolations where possible', 'convert all keys in a dictionary to lowercase and return the new dictionary', 'review the get_config function that loads YAML configs with OmegaConf interpolation support into a yacs CfgNode', 'test the resolve_omegaconf_to_dict function with a DictConfig containing variable interpolation references', 'create a function to recursively transfer a batch of tensors to a target device like cuda or numpy', 'check if the torch distributed environment has been initialized and is available for multi-process communication', 'get the current process rank and world size as a tuple from the distributed process group', 'broadcast a tensor from a source rank to all other ranks in the distributed process group', 'collect and aggregate result lists from all distributed ranks into a single ordered list on rank zero', 'get a multi-GPU-friendly Python logger using the default module name', 'get a multi-GPU-friendly Python logger with a custom name for a specific module', 'use the returned logger to log info messages that only print on rank zero', 'use the returned logger to log debug messages that only print on rank zero', 'use the returned logger to log error messages that only print on rank zero']
```

Usage

```
{'get_logger_default': 'get a multi-GPU-friendly Python logger using the default module name', 'get_logger_named': 'get a multi-GPU-friendly Python logger with a custom name for a specific module', 'use_logger_info': 'use the returned logger to log info messages that only print on rank zero', 'use_logger_debug': 'use the returned logger to log debug messages that only print on rank zero', 'use_logger_error': 'use the returned logger to log error messages that only print on rank zero'}
```

