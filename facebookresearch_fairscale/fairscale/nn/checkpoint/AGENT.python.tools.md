# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/nn/checkpoint/checkpoint_activations.py

Prompts

```
['wrap a PyTorch nn.Module with activation checkpointing to reduce GPU memory usage during training', 'use the disable_checkpointing context manager to temporarily skip activation checkpointing in a code block', 'check whether the current forward pass is running under activation checkpointing', 'check whether the current forward pass is recomputing activations to avoid duplicate side effects', 'use the CheckpointFunction autograd class to perform custom activation checkpointing with non-tensor output support', "patch all batchnorm instances in a PyTorch module so they don't track running stats during torch.no_grad()", 'review the patch_batchnorm function to understand how it hooks pre and post forward on batchnorm layers', 'refactor patch_batchnorm to support additional normalization layers beyond _BatchNorm', 'test patch_batchnorm by applying it to a module with BatchNorm1d, BatchNorm2d, and SyncBatchNorm layers', 'summarize how patch_batchnorm prevents incorrect running stats tracking during activation checkpointing']
```

Usage

```
{'checkpoint_wrapper_module': 'wrap a PyTorch nn.Module with activation checkpointing to reduce GPU memory usage during training', 'disable_checkpointing_context': 'use the disable_checkpointing context manager to temporarily skip activation checkpointing in a code block', 'is_checkpointing_check': 'check whether the current forward pass is running under activation checkpointing', 'is_recomputing_check': 'check whether the current forward pass is recomputing activations to avoid duplicate side effects', 'CheckpointFunction_autograd': 'use the CheckpointFunction autograd class to perform custom activation checkpointing with non-tensor output support'}
```

## File: facebookresearch_fairscale/fairscale/nn/checkpoint/checkpoint_utils.py

Prompts

```
['wrap a PyTorch nn.Module with activation checkpointing to reduce GPU memory usage during training', 'use the disable_checkpointing context manager to temporarily skip activation checkpointing in a code block', 'check whether the current forward pass is running under activation checkpointing', 'check whether the current forward pass is recomputing activations to avoid duplicate side effects', 'use the CheckpointFunction autograd class to perform custom activation checkpointing with non-tensor output support', "patch all batchnorm instances in a PyTorch module so they don't track running stats during torch.no_grad()", 'review the patch_batchnorm function to understand how it hooks pre and post forward on batchnorm layers', 'refactor patch_batchnorm to support additional normalization layers beyond _BatchNorm', 'test patch_batchnorm by applying it to a module with BatchNorm1d, BatchNorm2d, and SyncBatchNorm layers', 'summarize how patch_batchnorm prevents incorrect running stats tracking during activation checkpointing']
```

Usage

```
{'patch_batchnorm_module': "patch all batchnorm instances in a PyTorch module so they don't track running stats during torch.no_grad()", 'review_patch_batchnorm': 'review the patch_batchnorm function to understand how it hooks pre and post forward on batchnorm layers', 'refactor_patch_batchnorm': 'refactor patch_batchnorm to support additional normalization layers beyond _BatchNorm', 'test_patch_batchnorm': 'test patch_batchnorm by applying it to a module with BatchNorm1d, BatchNorm2d, and SyncBatchNorm layers', 'summarize_patch_batchnorm': 'summarize how patch_batchnorm prevents incorrect running stats tracking during activation checkpointing'}
```

