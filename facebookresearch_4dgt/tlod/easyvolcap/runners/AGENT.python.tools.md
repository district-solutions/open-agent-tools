# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/easyvolcap/runners/optimizers.py

Prompts

```
['build a configurable optimizer with per-parameter learning rate tables using ConfigurableOptimizer', 'create a MyFusedAdam optimizer that reduces CUDA kernel launches for Adam training steps', 'register a custom optimizer class with the OPTIMIZERS registry using the register_module decorator', 'review the MyFusedAdam step method that batches parameter updates via _single_tensor_adam', 'refactor ConfigurableOptimizer to group parameters by shared learning rate instead of creating one group per parameter']
```

Usage

```
{'build_optimizer_with_configurable_lr': 'build a configurable optimizer with per-parameter learning rate tables using ConfigurableOptimizer', 'create_fused_adam_optimizer': 'create a MyFusedAdam optimizer that reduces CUDA kernel launches for Adam training steps', 'register_custom_optimizer': 'register a custom optimizer class with the OPTIMIZERS registry using the register_module decorator', 'review_MyFusedAdam_step': 'review the MyFusedAdam step method that batches parameter updates via _single_tensor_adam', 'refactor_ConfigurableOptimizer_param_groups': 'refactor ConfigurableOptimizer to group parameters by shared learning rate instead of creating one group per parameter'}
```

