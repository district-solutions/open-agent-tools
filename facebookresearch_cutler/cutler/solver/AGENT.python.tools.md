# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/cutler/solver/build.py

Prompts

```
['build an SGD optimizer from a detectron2 config node and torch model', 'build a WarmupMultiStepLR or WarmupCosineLR scheduler from config and optimizer', 'get default optimizer parameter groups with weight decay and lr overrides for a model', 'wrap an optimizer class with gradient clipping by value or norm based on config', 'merge duplicated parameter groups to optimize PyTorch multi-tensor optimizer performance']
```

Usage

```
{'build_optimizer_from_cfg': 'build an SGD optimizer from a detectron2 config node and torch model', 'build_lr_scheduler_from_cfg': 'build a WarmupMultiStepLR or WarmupCosineLR scheduler from config and optimizer', 'get_default_optimizer_params': 'get default optimizer parameter groups with weight decay and lr overrides for a model', 'maybe_add_gradient_clipping': 'wrap an optimizer class with gradient clipping by value or norm based on config', 'reduce_param_groups': 'merge duplicated parameter groups to optimize PyTorch multi-tensor optimizer performance'}
```

