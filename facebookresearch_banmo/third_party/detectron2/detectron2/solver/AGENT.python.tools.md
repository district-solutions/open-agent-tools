# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/detectron2/solver/build.py

Prompts

```
['build an SGD optimizer from a Detectron2 config node and PyTorch model with gradient clipping support', 'build a learning rate scheduler with warmup multi-step or cosine decay from a Detectron2 config', 'get default optimizer parameter groups for a model with configurable weight decay for norm layers and bias', 'wrap an optimizer class to add per-parameter or global gradient clipping by value or norm', 'reduce and merge duplicated optimizer parameter groups to speed up PyTorch multi-tensor optimizer performance', 'build a learning rate scheduler using LRMultiplier with an fvcore ParamScheduler multiplier and max iterations', 'create a WarmupParamScheduler that adds a linear or constant warmup stage to an existing fvcore scheduler', 'use WarmupMultiStepLR to schedule learning rate with milestone-based decay and an initial warmup period', 'use WarmupCosineLR to schedule learning rate with a cosine annealing curve and an initial warmup period', 'review the _get_warmup_factor_at_iter function to compute warmup learning rate factors for constant or linear methods']
```

Usage

```
{'build_optimizer': 'build an SGD optimizer from a Detectron2 config node and PyTorch model with gradient clipping support', 'build_lr_scheduler': 'build a learning rate scheduler with warmup multi-step or cosine decay from a Detectron2 config', 'get_default_optimizer_params': 'get default optimizer parameter groups for a model with configurable weight decay for norm layers and bias', 'maybe_add_gradient_clipping': 'wrap an optimizer class to add per-parameter or global gradient clipping by value or norm', 'reduce_param_groups': 'reduce and merge duplicated optimizer parameter groups to speed up PyTorch multi-tensor optimizer performance'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/solver/lr_scheduler.py

Prompts

```
['build an SGD optimizer from a Detectron2 config node and PyTorch model with gradient clipping support', 'build a learning rate scheduler with warmup multi-step or cosine decay from a Detectron2 config', 'get default optimizer parameter groups for a model with configurable weight decay for norm layers and bias', 'wrap an optimizer class to add per-parameter or global gradient clipping by value or norm', 'reduce and merge duplicated optimizer parameter groups to speed up PyTorch multi-tensor optimizer performance', 'build a learning rate scheduler using LRMultiplier with an fvcore ParamScheduler multiplier and max iterations', 'create a WarmupParamScheduler that adds a linear or constant warmup stage to an existing fvcore scheduler', 'use WarmupMultiStepLR to schedule learning rate with milestone-based decay and an initial warmup period', 'use WarmupCosineLR to schedule learning rate with a cosine annealing curve and an initial warmup period', 'review the _get_warmup_factor_at_iter function to compute warmup learning rate factors for constant or linear methods']
```

Usage

```
{'build_LRMultiplier': 'build a learning rate scheduler using LRMultiplier with an fvcore ParamScheduler multiplier and max iterations', 'create_WarmupParamScheduler': 'create a WarmupParamScheduler that adds a linear or constant warmup stage to an existing fvcore scheduler', 'use_WarmupMultiStepLR': 'use WarmupMultiStepLR to schedule learning rate with milestone-based decay and an initial warmup period', 'use_WarmupCosineLR': 'use WarmupCosineLR to schedule learning rate with a cosine annealing curve and an initial warmup period', 'review_get_warmup_factor': 'review the _get_warmup_factor_at_iter function to compute warmup learning rate factors for constant or linear methods'}
```

