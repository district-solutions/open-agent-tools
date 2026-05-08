# Agent Python Tools

- repo: facebookresearch/optimizers
- repo_uri: https://github.com/facebookresearch/optimizers

## File: facebookresearch_optimizers/distributed_shampoo/distributed_shampoo.py

Prompts

```
['initialize a DistributedShampoo optimizer with custom learning rate, betas, and preconditioner config for a PyTorch model', 'perform a single optimization step with the DistributedShampoo optimizer using the step method and optional closure', 'configure DistributedShampoo with DDPDistributedConfig for multi-GPU distributed data-parallel training with AllGather communication', 'configure DistributedShampoo with FSDPDistributedConfig for fully-sharded data-parallel training with use_orig_params enabled', 'enable PyTorch 2.0 compilation for DistributedShampoo by setting shampoo_pt2_compile_config to ShampooPT2CompileConfig']
```

Usage

```
{'init_distributed_shampoo_optimizer': 'initialize a DistributedShampoo optimizer with custom learning rate, betas, and preconditioner config for a PyTorch model', 'step_distributed_shampoo': 'perform a single optimization step with the DistributedShampoo optimizer using the step method and optional closure', 'configure_shampoo_ddp': 'configure DistributedShampoo with DDPDistributedConfig for multi-GPU distributed data-parallel training with AllGather communication', 'configure_shampoo_fsdp': 'configure DistributedShampoo with FSDPDistributedConfig for fully-sharded data-parallel training with use_orig_params enabled', 'enable_shampoo_pt2_compile': 'enable PyTorch 2.0 compilation for DistributedShampoo by setting shampoo_pt2_compile_config to ShampooPT2CompileConfig'}
```

