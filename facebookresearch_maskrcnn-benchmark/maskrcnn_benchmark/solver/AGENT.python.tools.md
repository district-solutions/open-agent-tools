# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/solver/build.py

Prompts

```
['build an SGD optimizer with bias-specific learning rate and weight decay from a config and model', 'build a WarmupMultiStepLR scheduler with warmup factor, iters, and method from a config', 'review the make_optimizer function to understand how it separates bias parameters with different learning rates', 'review the make_lr_scheduler function to understand how it configures warmup and step decay', 'refactor make_optimizer to support additional parameter groups beyond bias with custom learning rates', 'create a WarmupMultiStepLR scheduler with optimizer, milestones, gamma, and warmup parameters for training', 'build a WarmupMultiStepLR scheduler using linear warmup method with custom warmup_iters and warmup_factor', 'test the WarmupMultiStepLR get_lr method to verify learning rate calculation during warmup and after milestones', 'review the WarmupMultiStepLR __init__ method to understand milestone validation and warmup method constraints', 'summarize the WarmupMultiStepLR class that combines multi-step LR decay with linear or constant warmup']
```

Usage

```
{'build_optimizer_sgd': 'build an SGD optimizer with bias-specific learning rate and weight decay from a config and model', 'build_lr_scheduler_warmup': 'build a WarmupMultiStepLR scheduler with warmup factor, iters, and method from a config', 'review_make_optimizer': 'review the make_optimizer function to understand how it separates bias parameters with different learning rates', 'review_make_lr_scheduler': 'review the make_lr_scheduler function to understand how it configures warmup and step decay', 'refactor_optimizer_params': 'refactor make_optimizer to support additional parameter groups beyond bias with custom learning rates'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/solver/lr_scheduler.py

Prompts

```
['build an SGD optimizer with bias-specific learning rate and weight decay from a config and model', 'build a WarmupMultiStepLR scheduler with warmup factor, iters, and method from a config', 'review the make_optimizer function to understand how it separates bias parameters with different learning rates', 'review the make_lr_scheduler function to understand how it configures warmup and step decay', 'refactor make_optimizer to support additional parameter groups beyond bias with custom learning rates', 'create a WarmupMultiStepLR scheduler with optimizer, milestones, gamma, and warmup parameters for training', 'build a WarmupMultiStepLR scheduler using linear warmup method with custom warmup_iters and warmup_factor', 'test the WarmupMultiStepLR get_lr method to verify learning rate calculation during warmup and after milestones', 'review the WarmupMultiStepLR __init__ method to understand milestone validation and warmup method constraints', 'summarize the WarmupMultiStepLR class that combines multi-step LR decay with linear or constant warmup']
```

Usage

```
{'create_WarmupMultiStepLR_scheduler': 'create a WarmupMultiStepLR scheduler with optimizer, milestones, gamma, and warmup parameters for training', 'build_WarmupMultiStepLR_with_linear_warmup': 'build a WarmupMultiStepLR scheduler using linear warmup method with custom warmup_iters and warmup_factor', 'test_WarmupMultiStepLR_get_lr': 'test the WarmupMultiStepLR get_lr method to verify learning rate calculation during warmup and after milestones', 'review_WarmupMultiStepLR_init': 'review the WarmupMultiStepLR __init__ method to understand milestone validation and warmup method constraints', 'summarize_WarmupMultiStepLR_class': 'summarize the WarmupMultiStepLR class that combines multi-step LR decay with linear or constant warmup'}
```

