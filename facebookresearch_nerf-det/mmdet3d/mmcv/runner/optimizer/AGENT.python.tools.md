# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/runner/optimizer/builder.py

Prompts

```
['build an optimizer for a PyTorch model using a config dictionary with constructor and paramwise settings', 'build an optimizer constructor from a config dict using the OPTIMIZER_BUILDERS registry', 'register all torch.optim optimizer classes into the OPTIMIZERS registry automatically', 'review the OPTIMIZERS Registry containing all registered PyTorch optimizer classes', 'review the OPTIMIZER_BUILDERS Registry containing registered optimizer builder classes', 'build an optimizer using DefaultOptimizerConstructor with custom_keys to set different lr_mult and decay_mult for backbone parameters', 'build an optimizer with DefaultOptimizerConstructor setting norm_decay_mult to zero for normalization layer weight decay', 'build an optimizer using DefaultOptimizerConstructor with bias_lr_mult to apply a different learning rate to all bias parameters', 'build an optimizer using DefaultOptimizerConstructor with dcn_offset_lr_mult to control deformable conv offset layer learning rate', 'build an optimizer using DefaultOptimizerConstructor with dwconv_decay_mult to apply custom weight decay for depthwise convolution layers']
```

Usage

```
{'build_optimizer': 'build an optimizer for a PyTorch model using a config dictionary with constructor and paramwise settings', 'build_optimizer_constructor': 'build an optimizer constructor from a config dict using the OPTIMIZER_BUILDERS registry', 'register_torch_optimizers': 'register all torch.optim optimizer classes into the OPTIMIZERS registry automatically', 'review_OPTIMIZERS_registry': 'review the OPTIMIZERS Registry containing all registered PyTorch optimizer classes', 'review_OPTIMIZER_BUILDERS_registry': 'review the OPTIMIZER_BUILDERS Registry containing registered optimizer builder classes'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/runner/optimizer/default_constructor.py

Prompts

```
['build an optimizer for a PyTorch model using a config dictionary with constructor and paramwise settings', 'build an optimizer constructor from a config dict using the OPTIMIZER_BUILDERS registry', 'register all torch.optim optimizer classes into the OPTIMIZERS registry automatically', 'review the OPTIMIZERS Registry containing all registered PyTorch optimizer classes', 'review the OPTIMIZER_BUILDERS Registry containing registered optimizer builder classes', 'build an optimizer using DefaultOptimizerConstructor with custom_keys to set different lr_mult and decay_mult for backbone parameters', 'build an optimizer with DefaultOptimizerConstructor setting norm_decay_mult to zero for normalization layer weight decay', 'build an optimizer using DefaultOptimizerConstructor with bias_lr_mult to apply a different learning rate to all bias parameters', 'build an optimizer using DefaultOptimizerConstructor with dcn_offset_lr_mult to control deformable conv offset layer learning rate', 'build an optimizer using DefaultOptimizerConstructor with dwconv_decay_mult to apply custom weight decay for depthwise convolution layers']
```

Usage

```
{'build_optimizer_with_paramwise_cfg': 'build an optimizer using DefaultOptimizerConstructor with custom_keys to set different lr_mult and decay_mult for backbone parameters', 'build_optimizer_with_norm_decay': 'build an optimizer with DefaultOptimizerConstructor setting norm_decay_mult to zero for normalization layer weight decay', 'build_optimizer_with_bias_lr_mult': 'build an optimizer using DefaultOptimizerConstructor with bias_lr_mult to apply a different learning rate to all bias parameters', 'build_optimizer_with_dcn_offset_lr': 'build an optimizer using DefaultOptimizerConstructor with dcn_offset_lr_mult to control deformable conv offset layer learning rate', 'build_optimizer_with_dwconv_decay': 'build an optimizer using DefaultOptimizerConstructor with dwconv_decay_mult to apply custom weight decay for depthwise convolution layers'}
```

