# Agent Python Tools

- repo: facebookresearch/meshrcnn
- repo_uri: https://github.com/facebookresearch/meshrcnn

## File: facebookresearch_meshrcnn/shapenet/solver/build.py

Prompts

```
['build an SGD optimizer from config with base learning rate and momentum settings', 'build an Adam optimizer from config with the specified base learning rate', 'build a constant learning rate scheduler that maintains the base learning rate throughout training', 'build a warmup cosine learning rate scheduler with configurable warmup iterations and decay', 'review the build_optimizer function to add weight decay support for SGD and Adam optimizers', 'create a WarmupCosineLR scheduler with an optimizer, total iterations, and warmup parameters for cosine annealing', 'create a WarmupCosineLR scheduler using linear warmup method instead of the default cosine warmup', 'create a ConstantLR scheduler that maintains a fixed learning rate throughout training', 'review the WarmupCosineLR get_lr method to understand how learning rate factors are computed during warmup and decay', 'test the WarmupCosineLR scheduler with both linear and cosine warmup methods to verify correct learning rate schedules']
```

Usage

```
{'build_optimizer_sgd': 'build an SGD optimizer from config with base learning rate and momentum settings', 'build_optimizer_adam': 'build an Adam optimizer from config with the specified base learning rate', 'build_lr_scheduler_constant': 'build a constant learning rate scheduler that maintains the base learning rate throughout training', 'build_lr_scheduler_cosine': 'build a warmup cosine learning rate scheduler with configurable warmup iterations and decay', 'review_build_optimizer': 'review the build_optimizer function to add weight decay support for SGD and Adam optimizers'}
```

## File: facebookresearch_meshrcnn/shapenet/solver/lr_schedule.py

Prompts

```
['build an SGD optimizer from config with base learning rate and momentum settings', 'build an Adam optimizer from config with the specified base learning rate', 'build a constant learning rate scheduler that maintains the base learning rate throughout training', 'build a warmup cosine learning rate scheduler with configurable warmup iterations and decay', 'review the build_optimizer function to add weight decay support for SGD and Adam optimizers', 'create a WarmupCosineLR scheduler with an optimizer, total iterations, and warmup parameters for cosine annealing', 'create a WarmupCosineLR scheduler using linear warmup method instead of the default cosine warmup', 'create a ConstantLR scheduler that maintains a fixed learning rate throughout training', 'review the WarmupCosineLR get_lr method to understand how learning rate factors are computed during warmup and decay', 'test the WarmupCosineLR scheduler with both linear and cosine warmup methods to verify correct learning rate schedules']
```

Usage

```
{'create_WarmupCosineLR_scheduler': 'create a WarmupCosineLR scheduler with an optimizer, total iterations, and warmup parameters for cosine annealing', 'create_WarmupCosineLR_linear_warmup': 'create a WarmupCosineLR scheduler using linear warmup method instead of the default cosine warmup', 'create_ConstantLR_scheduler': 'create a ConstantLR scheduler that maintains a fixed learning rate throughout training', 'review_WarmupCosineLR_get_lr': 'review the WarmupCosineLR get_lr method to understand how learning rate factors are computed during warmup and decay', 'test_WarmupCosineLR_warmup_methods': 'test the WarmupCosineLR scheduler with both linear and cosine warmup methods to verify correct learning rate schedules'}
```

