# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/detectron2/solver/build.py

Prompts

```
['build an SGD optimizer from a detectron2 CfgNode config and a torch.nn.Module model', 'build a learning rate scheduler (WarmupMultiStepLR, WarmupCosineLR, or WarmupStepWithFixedGammaLR) from config', 'add gradient clipping to an optimizer based on detectron2 config options', 'get default optimizer parameter groups with support for weight decay normalization and bias overrides', 'reduce and merge parameter groups to minimize the number of groups for efficient multi-tensor optimizer use', 'build a PyTorch LRMultiplier scheduler with fvcore ParamScheduler to multiply learning rates during training', 'create a WarmupParamScheduler that adds an initial warmup stage to any fvcore ParamScheduler', 'test the _get_warmup_factor_at_iter function for linear and constant warmup methods', 'review the deprecated WarmupMultiStepLR class that combines warmup with multi-step learning rate decay', 'review the deprecated WarmupCosineLR class that combines warmup with cosine annealing learning rate schedule']
```

Usage

```
{'build_optimizer': 'build an SGD optimizer from a detectron2 CfgNode config and a torch.nn.Module model', 'build_lr_scheduler': 'build a learning rate scheduler (WarmupMultiStepLR, WarmupCosineLR, or WarmupStepWithFixedGammaLR) from config', 'maybe_add_gradient_clipping': 'add gradient clipping to an optimizer based on detectron2 config options', 'get_default_optimizer_params': 'get default optimizer parameter groups with support for weight decay normalization and bias overrides', 'reduce_param_groups': 'reduce and merge parameter groups to minimize the number of groups for efficient multi-tensor optimizer use'}
```

## File: facebookresearch_detectron2/detectron2/solver/lr_scheduler.py

Prompts

```
['build an SGD optimizer from a detectron2 CfgNode config and a torch.nn.Module model', 'build a learning rate scheduler (WarmupMultiStepLR, WarmupCosineLR, or WarmupStepWithFixedGammaLR) from config', 'add gradient clipping to an optimizer based on detectron2 config options', 'get default optimizer parameter groups with support for weight decay normalization and bias overrides', 'reduce and merge parameter groups to minimize the number of groups for efficient multi-tensor optimizer use', 'build a PyTorch LRMultiplier scheduler with fvcore ParamScheduler to multiply learning rates during training', 'create a WarmupParamScheduler that adds an initial warmup stage to any fvcore ParamScheduler', 'test the _get_warmup_factor_at_iter function for linear and constant warmup methods', 'review the deprecated WarmupMultiStepLR class that combines warmup with multi-step learning rate decay', 'review the deprecated WarmupCosineLR class that combines warmup with cosine annealing learning rate schedule']
```

Usage

```
{'build_lr_multiplier_scheduler': 'build a PyTorch LRMultiplier scheduler with fvcore ParamScheduler to multiply learning rates during training', 'create_warmup_param_scheduler': 'create a WarmupParamScheduler that adds an initial warmup stage to any fvcore ParamScheduler', 'test_warmup_factor_at_iter': 'test the _get_warmup_factor_at_iter function for linear and constant warmup methods', 'review_warmup_multistep_lr': 'review the deprecated WarmupMultiStepLR class that combines warmup with multi-step learning rate decay', 'review_warmup_cosine_lr': 'review the deprecated WarmupCosineLR class that combines warmup with cosine annealing learning rate schedule'}
```

