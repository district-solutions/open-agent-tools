# Agent Python Tools

- repo: facebookresearch/attentivenas
- repo_uri: https://github.com/facebookresearch/attentivenas

## File: facebookresearch_attentivenas/solver/build.py

Prompts

```
['build an SGD optimizer with weight decay groups for a PyTorch model using config args', 'build a warmup cosine learning rate scheduler for a PyTorch optimizer from config args', 'build a warmup multi-step exponential decay learning rate scheduler from config args', 'build a warmup linear decay learning rate scheduler for a PyTorch optimizer from config args', 'build a constant learning rate scheduler that keeps the optimizer learning rate unchanged', 'create a WarmupCosineLR scheduler with cosine annealing and linear warmup for a PyTorch optimizer', 'create a WarmupMultiStepLR scheduler that decays learning rate by gamma at specified milestones', 'create a WarmupLinearDecayLR scheduler with linear decay across milestones and warmup phase', 'create a ConstantLR scheduler that keeps the learning rate unchanged throughout training', 'review the _get_warmup_factor_at_iter function that computes warmup factor using constant or linear methods']
```

Usage

```
{'build_optimizer_sgd': 'build an SGD optimizer with weight decay groups for a PyTorch model using config args', 'build_lr_scheduler_cosine': 'build a warmup cosine learning rate scheduler for a PyTorch optimizer from config args', 'build_lr_scheduler_multistep': 'build a warmup multi-step exponential decay learning rate scheduler from config args', 'build_lr_scheduler_linear': 'build a warmup linear decay learning rate scheduler for a PyTorch optimizer from config args', 'build_lr_scheduler_constant': 'build a constant learning rate scheduler that keeps the optimizer learning rate unchanged'}
```

## File: facebookresearch_attentivenas/solver/lr_scheduler.py

Prompts

```
['build an SGD optimizer with weight decay groups for a PyTorch model using config args', 'build a warmup cosine learning rate scheduler for a PyTorch optimizer from config args', 'build a warmup multi-step exponential decay learning rate scheduler from config args', 'build a warmup linear decay learning rate scheduler for a PyTorch optimizer from config args', 'build a constant learning rate scheduler that keeps the optimizer learning rate unchanged', 'create a WarmupCosineLR scheduler with cosine annealing and linear warmup for a PyTorch optimizer', 'create a WarmupMultiStepLR scheduler that decays learning rate by gamma at specified milestones', 'create a WarmupLinearDecayLR scheduler with linear decay across milestones and warmup phase', 'create a ConstantLR scheduler that keeps the learning rate unchanged throughout training', 'review the _get_warmup_factor_at_iter function that computes warmup factor using constant or linear methods']
```

Usage

```
{'create_warmup_cosine_lr': 'create a WarmupCosineLR scheduler with cosine annealing and linear warmup for a PyTorch optimizer', 'create_warmup_multistep_lr': 'create a WarmupMultiStepLR scheduler that decays learning rate by gamma at specified milestones', 'create_warmup_linear_decay_lr': 'create a WarmupLinearDecayLR scheduler with linear decay across milestones and warmup phase', 'create_constant_lr': 'create a ConstantLR scheduler that keeps the learning rate unchanged throughout training', 'review_get_warmup_factor': 'review the _get_warmup_factor_at_iter function that computes warmup factor using constant or linear methods'}
```

