# Agent Python Tools

- repo: facebookresearch/pixio
- repo_uri: https://github.com/facebookresearch/pixio

## File: facebookresearch_pixio/distillation/util/loss.py

Prompts

```
['build a feature alignment loss function that computes cosine, l1, or mse loss between student and teacher features', 'create a feature alignment loss using cosine similarity for both class and patch tokens between student and teacher models', 'test the feature alignment loss function with l1 loss for class tokens and mse loss for patch tokens', 'refactor the feature alignment loss to support weighted sum fusion of class and patch token losses', 'review the feature alignment loss function and its handling of ids_keep for teacher patch token gathering', 'adjust the learning rate of an optimizer using half-cycle cosine decay after a warmup phase', 'create an optimizer schedule that linearly warms up the learning rate over initial epochs', 'build a learning rate scheduler that decays from peak to minimum using a cosine curve', 'review the adjust_learning_rate function to understand how it handles param groups with lr_scale', 'test the cosine learning rate decay formula across epochs after the warmup period ends', 'create a MetricLogger to track training metrics like loss and accuracy with smoothed values', 'init distributed training mode from SLURM or environment variables for multi-GPU training', 'save model checkpoint with optimizer state, epoch, and scaler to output directory', 'load model checkpoint from file or URL to resume training from a previous epoch', 'use NativeScalerWithGradNormCount to handle AMP gradient scaling and clipping during training', 'build a python module that splits model parameters into weight decay and no decay groups', 'create param groups separating bias and 1D params from weight decay for an optimizer', 'test the param_groups_weight_decay function to verify correct separation of decay and no-decay parameters', 'refactor param_groups_weight_decay to support additional no-weight-decry criteria beyond bias and 1D params', 'review the param_groups_weight_decay function and its handling of the no_weight_decay_list parameter']
```

Usage

```
{'build_feat_align_loss': 'build a feature alignment loss function that computes cosine, l1, or mse loss between student and teacher features', 'create_feat_align_loss_cosine': 'create a feature alignment loss using cosine similarity for both class and patch tokens between student and teacher models', 'test_feat_align_loss_l1': 'test the feature alignment loss function with l1 loss for class tokens and mse loss for patch tokens', 'refactor_feat_align_loss_fuse': 'refactor the feature alignment loss to support weighted sum fusion of class and patch token losses', 'review_feat_align_loss_ids_keep': 'review the feature alignment loss function and its handling of ids_keep for teacher patch token gathering'}
```

## File: facebookresearch_pixio/distillation/util/lr_sched.py

Prompts

```
['build a feature alignment loss function that computes cosine, l1, or mse loss between student and teacher features', 'create a feature alignment loss using cosine similarity for both class and patch tokens between student and teacher models', 'test the feature alignment loss function with l1 loss for class tokens and mse loss for patch tokens', 'refactor the feature alignment loss to support weighted sum fusion of class and patch token losses', 'review the feature alignment loss function and its handling of ids_keep for teacher patch token gathering', 'adjust the learning rate of an optimizer using half-cycle cosine decay after a warmup phase', 'create an optimizer schedule that linearly warms up the learning rate over initial epochs', 'build a learning rate scheduler that decays from peak to minimum using a cosine curve', 'review the adjust_learning_rate function to understand how it handles param groups with lr_scale', 'test the cosine learning rate decay formula across epochs after the warmup period ends', 'create a MetricLogger to track training metrics like loss and accuracy with smoothed values', 'init distributed training mode from SLURM or environment variables for multi-GPU training', 'save model checkpoint with optimizer state, epoch, and scaler to output directory', 'load model checkpoint from file or URL to resume training from a previous epoch', 'use NativeScalerWithGradNormCount to handle AMP gradient scaling and clipping during training', 'build a python module that splits model parameters into weight decay and no decay groups', 'create param groups separating bias and 1D params from weight decay for an optimizer', 'test the param_groups_weight_decay function to verify correct separation of decay and no-decay parameters', 'refactor param_groups_weight_decay to support additional no-weight-decry criteria beyond bias and 1D params', 'review the param_groups_weight_decay function and its handling of the no_weight_decay_list parameter']
```

Usage

```
{'adjust_learning_rate_cosine_decay': 'adjust the learning rate of an optimizer using half-cycle cosine decay after a warmup phase', 'create_optimizer_with_warmup': 'create an optimizer schedule that linearly warms up the learning rate over initial epochs', 'build_lr_scheduler': 'build a learning rate scheduler that decays from peak to minimum using a cosine curve', 'review_adjust_learning_rate': 'review the adjust_learning_rate function to understand how it handles param groups with lr_scale', 'test_cosine_lr_decay': 'test the cosine learning rate decay formula across epochs after the warmup period ends'}
```

## File: facebookresearch_pixio/distillation/util/misc.py

Prompts

```
['build a feature alignment loss function that computes cosine, l1, or mse loss between student and teacher features', 'create a feature alignment loss using cosine similarity for both class and patch tokens between student and teacher models', 'test the feature alignment loss function with l1 loss for class tokens and mse loss for patch tokens', 'refactor the feature alignment loss to support weighted sum fusion of class and patch token losses', 'review the feature alignment loss function and its handling of ids_keep for teacher patch token gathering', 'adjust the learning rate of an optimizer using half-cycle cosine decay after a warmup phase', 'create an optimizer schedule that linearly warms up the learning rate over initial epochs', 'build a learning rate scheduler that decays from peak to minimum using a cosine curve', 'review the adjust_learning_rate function to understand how it handles param groups with lr_scale', 'test the cosine learning rate decay formula across epochs after the warmup period ends', 'create a MetricLogger to track training metrics like loss and accuracy with smoothed values', 'init distributed training mode from SLURM or environment variables for multi-GPU training', 'save model checkpoint with optimizer state, epoch, and scaler to output directory', 'load model checkpoint from file or URL to resume training from a previous epoch', 'use NativeScalerWithGradNormCount to handle AMP gradient scaling and clipping during training', 'build a python module that splits model parameters into weight decay and no decay groups', 'create param groups separating bias and 1D params from weight decay for an optimizer', 'test the param_groups_weight_decay function to verify correct separation of decay and no-decay parameters', 'refactor param_groups_weight_decay to support additional no-weight-decry criteria beyond bias and 1D params', 'review the param_groups_weight_decay function and its handling of the no_weight_decay_list parameter']
```

Usage

```
{'create_MetricLogger': 'create a MetricLogger to track training metrics like loss and accuracy with smoothed values', 'init_distributed_mode': 'init distributed training mode from SLURM or environment variables for multi-GPU training', 'save_model': 'save model checkpoint with optimizer state, epoch, and scaler to output directory', 'load_model': 'load model checkpoint from file or URL to resume training from a previous epoch', 'use_NativeScalerWithGradNormCount': 'use NativeScalerWithGradNormCount to handle AMP gradient scaling and clipping during training'}
```

## File: facebookresearch_pixio/distillation/util/optim_factory.py

Prompts

```
['build a feature alignment loss function that computes cosine, l1, or mse loss between student and teacher features', 'create a feature alignment loss using cosine similarity for both class and patch tokens between student and teacher models', 'test the feature alignment loss function with l1 loss for class tokens and mse loss for patch tokens', 'refactor the feature alignment loss to support weighted sum fusion of class and patch token losses', 'review the feature alignment loss function and its handling of ids_keep for teacher patch token gathering', 'adjust the learning rate of an optimizer using half-cycle cosine decay after a warmup phase', 'create an optimizer schedule that linearly warms up the learning rate over initial epochs', 'build a learning rate scheduler that decays from peak to minimum using a cosine curve', 'review the adjust_learning_rate function to understand how it handles param groups with lr_scale', 'test the cosine learning rate decay formula across epochs after the warmup period ends', 'create a MetricLogger to track training metrics like loss and accuracy with smoothed values', 'init distributed training mode from SLURM or environment variables for multi-GPU training', 'save model checkpoint with optimizer state, epoch, and scaler to output directory', 'load model checkpoint from file or URL to resume training from a previous epoch', 'use NativeScalerWithGradNormCount to handle AMP gradient scaling and clipping during training', 'build a python module that splits model parameters into weight decay and no decay groups', 'create param groups separating bias and 1D params from weight decay for an optimizer', 'test the param_groups_weight_decay function to verify correct separation of decay and no-decay parameters', 'refactor param_groups_weight_decay to support additional no-weight-decry criteria beyond bias and 1D params', 'review the param_groups_weight_decay function and its handling of the no_weight_decay_list parameter']
```

Usage

```
{'build_param_groups_weight_decay': 'build a python module that splits model parameters into weight decay and no decay groups', 'create_param_groups_for_optimizer': 'create param groups separating bias and 1D params from weight decay for an optimizer', 'test_param_groups_weight_decay': 'test the param_groups_weight_decay function to verify correct separation of decay and no-decay parameters', 'refactor_param_groups_weight_decay': 'refactor param_groups_weight_decay to support additional no-weight-decry criteria beyond bias and 1D params', 'review_param_groups_weight_decay': 'review the param_groups_weight_decay function and its handling of the no_weight_decay_list parameter'}
```

