# Agent Python Tools

- repo: dao-ailab/flash-attention
- repo_uri: https://github.com/dao-ailab/flash-attention

## File: dao-ailab_flash-attention/training/src/optim/param_grouping.py

Prompts

```
['group model parameters into optimizer param groups with weight decay rules for biases and normalization layers', 'create optimizer param groups with configurable bias weight decay behavior for a PyTorch model', 'build optimizer param groups that skip normalization layers like LayerNorm and BatchNorm from weight decay', 'handle parameters with special _optim attributes by creating dedicated optimizer param groups', 'review the group_parameters_for_optimizer function that separates model params into decay and no_decay buckets', "create a TimmCosineLRScheduler that wraps timm's CosineLRScheduler for PyTorch Lightning compatibility", 'step the TimmCosineLRScheduler with optional epoch argument to update learning rate', 'step the TimmCosineLRScheduler without epoch argument to auto-increment the internal epoch counter', 'resume the TimmCosineLRScheduler by passing an explicit epoch to step for checkpoint recovery', 'build a TimmCosineLRScheduler configured for step-level updates via t_in_epochs=False']
```

Usage

```
{'group_optimizer_param_groups': 'group model parameters into optimizer param groups with weight decay rules for biases and normalization layers', 'create_bias_weight_decay_config': 'create optimizer param groups with configurable bias weight decay behavior for a PyTorch model', 'build_normalization_weight_decay_groups': 'build optimizer param groups that skip normalization layers like LayerNorm and BatchNorm from weight decay', 'handle_special_param_hyperparameters': 'handle parameters with special _optim attributes by creating dedicated optimizer param groups', 'review_param_grouping_function': 'review the group_parameters_for_optimizer function that separates model params into decay and no_decay buckets'}
```

## File: dao-ailab_flash-attention/training/src/optim/timm_lr_scheduler.py

Prompts

```
['group model parameters into optimizer param groups with weight decay rules for biases and normalization layers', 'create optimizer param groups with configurable bias weight decay behavior for a PyTorch model', 'build optimizer param groups that skip normalization layers like LayerNorm and BatchNorm from weight decay', 'handle parameters with special _optim attributes by creating dedicated optimizer param groups', 'review the group_parameters_for_optimizer function that separates model params into decay and no_decay buckets', "create a TimmCosineLRScheduler that wraps timm's CosineLRScheduler for PyTorch Lightning compatibility", 'step the TimmCosineLRScheduler with optional epoch argument to update learning rate', 'step the TimmCosineLRScheduler without epoch argument to auto-increment the internal epoch counter', 'resume the TimmCosineLRScheduler by passing an explicit epoch to step for checkpoint recovery', 'build a TimmCosineLRScheduler configured for step-level updates via t_in_epochs=False']
```

Usage

```
{'create_timm_cosine_scheduler': "create a TimmCosineLRScheduler that wraps timm's CosineLRScheduler for PyTorch Lightning compatibility", 'step_scheduler_epoch': 'step the TimmCosineLRScheduler with optional epoch argument to update learning rate', 'step_scheduler_auto_epoch': 'step the TimmCosineLRScheduler without epoch argument to auto-increment the internal epoch counter', 'resume_scheduler_from_epoch': 'resume the TimmCosineLRScheduler by passing an explicit epoch to step for checkpoint recovery', 'build_cosine_lr_with_step_update': 'build a TimmCosineLRScheduler configured for step-level updates via t_in_epochs=False'}
```

