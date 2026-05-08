# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/trainer/activation_checkpointing.py

Prompts

```
['add activation checkpoint config entries to a D2GO CfgNode with reentrant and auto wrap policy settings', 'apply activation checkpointing to a PyTorch model using a checkpoint wrapper function and auto wrap policy', 'apply the ActivationCheckpointModelingHook to wrap a PyTorch model with activation checkpointing based on config', 'register the ActivationCheckpointModelingHook class in the MODELING_HOOK_REGISTRY for use as a modeling hook', 'use checkpoint_wrapper with NO_REENTRANT or REENTRANT CheckpointImpl to wrap model layers for memory-efficient training', 'build a FullyShardedDataParallel wrapped model with configurable sharding strategy and mixed precision', 'add FSDP configuration options to a D2Go CfgNode for distributed training setup', 'create an FSDPWrapper instance that handles state dict types and autocast for a PyTorch model', 'apply the FSDPModelingHook to wrap a model in FSDP based on D2Go config settings', 'run a post-order traversal to wrap nested modules in FSDP for distributed initialization', 'convert a precision string like bfloat16 to a torch dtype or lightning-compatible value', "recursively find and return a module class by name from a PyTorch model's children", 'get a list of layer classes from a model matching a list of layer names', 'create an FSDP wrap policy that skips wrapping all child modules and wraps only the root', 'create an FSDP auto wrap policy that wraps modules with at least a minimum number of parameters']
```

Usage

```
{'add_activation_checkpoint_configs': 'add activation checkpoint config entries to a D2GO CfgNode with reentrant and auto wrap policy settings', 'apply_activation_checkpointing': 'apply activation checkpointing to a PyTorch model using a checkpoint wrapper function and auto wrap policy', 'ActivationCheckpointModelingHook_apply': 'apply the ActivationCheckpointModelingHook to wrap a PyTorch model with activation checkpointing based on config', 'ActivationCheckpointModelingHook_register': 'register the ActivationCheckpointModelingHook class in the MODELING_HOOK_REGISTRY for use as a modeling hook', 'checkpoint_wrapper_usage': 'use checkpoint_wrapper with NO_REENTRANT or REENTRANT CheckpointImpl to wrap model layers for memory-efficient training'}
```

## File: facebookresearch_d2go/d2go/trainer/fsdp.py

Prompts

```
['add activation checkpoint config entries to a D2GO CfgNode with reentrant and auto wrap policy settings', 'apply activation checkpointing to a PyTorch model using a checkpoint wrapper function and auto wrap policy', 'apply the ActivationCheckpointModelingHook to wrap a PyTorch model with activation checkpointing based on config', 'register the ActivationCheckpointModelingHook class in the MODELING_HOOK_REGISTRY for use as a modeling hook', 'use checkpoint_wrapper with NO_REENTRANT or REENTRANT CheckpointImpl to wrap model layers for memory-efficient training', 'build a FullyShardedDataParallel wrapped model with configurable sharding strategy and mixed precision', 'add FSDP configuration options to a D2Go CfgNode for distributed training setup', 'create an FSDPWrapper instance that handles state dict types and autocast for a PyTorch model', 'apply the FSDPModelingHook to wrap a model in FSDP based on D2Go config settings', 'run a post-order traversal to wrap nested modules in FSDP for distributed initialization', 'convert a precision string like bfloat16 to a torch dtype or lightning-compatible value', "recursively find and return a module class by name from a PyTorch model's children", 'get a list of layer classes from a model matching a list of layer names', 'create an FSDP wrap policy that skips wrapping all child modules and wraps only the root', 'create an FSDP auto wrap policy that wraps modules with at least a minimum number of parameters']
```

Usage

```
{'build_fsdp_model': 'build a FullyShardedDataParallel wrapped model with configurable sharding strategy and mixed precision', 'add_fsdp_configs': 'add FSDP configuration options to a D2Go CfgNode for distributed training setup', 'create_fsdp_wrapper': 'create an FSDPWrapper instance that handles state dict types and autocast for a PyTorch model', 'apply_fsdp_modeling_hook': 'apply the FSDPModelingHook to wrap a model in FSDP based on D2Go config settings', 'run_bottom_up_nested_fsdp': 'run a post-order traversal to wrap nested modules in FSDP for distributed initialization'}
```

## File: facebookresearch_d2go/d2go/trainer/helper.py

Prompts

```
['add activation checkpoint config entries to a D2GO CfgNode with reentrant and auto wrap policy settings', 'apply activation checkpointing to a PyTorch model using a checkpoint wrapper function and auto wrap policy', 'apply the ActivationCheckpointModelingHook to wrap a PyTorch model with activation checkpointing based on config', 'register the ActivationCheckpointModelingHook class in the MODELING_HOOK_REGISTRY for use as a modeling hook', 'use checkpoint_wrapper with NO_REENTRANT or REENTRANT CheckpointImpl to wrap model layers for memory-efficient training', 'build a FullyShardedDataParallel wrapped model with configurable sharding strategy and mixed precision', 'add FSDP configuration options to a D2Go CfgNode for distributed training setup', 'create an FSDPWrapper instance that handles state dict types and autocast for a PyTorch model', 'apply the FSDPModelingHook to wrap a model in FSDP based on D2Go config settings', 'run a post-order traversal to wrap nested modules in FSDP for distributed initialization', 'convert a precision string like bfloat16 to a torch dtype or lightning-compatible value', "recursively find and return a module class by name from a PyTorch model's children", 'get a list of layer classes from a model matching a list of layer names', 'create an FSDP wrap policy that skips wrapping all child modules and wraps only the root', 'create an FSDP auto wrap policy that wraps modules with at least a minimum number of parameters']
```

Usage

```
{'parse_precision_from_string': 'convert a precision string like bfloat16 to a torch dtype or lightning-compatible value', 'get_module_class_from_name': "recursively find and return a module class by name from a PyTorch model's children", 'get_layer_cls_from_names': 'get a list of layer classes from a model matching a list of layer names', 'never_wrap_policy': 'create an FSDP wrap policy that skips wrapping all child modules and wraps only the root', 'size_based_auto_wrap_policy': 'create an FSDP auto wrap policy that wraps modules with at least a minimum number of parameters'}
```

