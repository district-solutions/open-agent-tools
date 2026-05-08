# Agent Python Tools

- repo: facebookresearch/r-mae
- repo_uri: https://github.com/facebookresearch/r-mae

## File: facebookresearch_r-mae/pretrain/optim/scheduler/cosine_scheduler.py

Prompts

```
['create a CosineAnnealingScheduler instance with config and optimizer for cosine annealing learning rate scheduling', 'review the CosineAnnealingScheduler __init__ to understand how eta_min, T_max, warmup_iterations, and warmup_factor are configured', 'summarize the get_iter_lr method that computes per-iteration learning rates using cosine annealing with optional warmup', 'test the CosineAnnealingScheduler warmup phase to verify learning rate ramps up from warmup_factor to base_lr', 'refactor the CosineAnnealingScheduler to customize how eta_mins are scaled relative to each param group base learning rate', 'create a BaseScheduler instance with a config dict and torch optimizer for learning rate scheduling', 'step the BaseScheduler forward by one iteration to update learning rates for each param group', 'step the BaseScheduler forward by one epoch to update learning rates for each param group', 'get the serializable state dict from a BaseScheduler instance excluding the optimizer and config', 'load a previously saved state dict into a BaseScheduler and restore the last epoch and iteration', 'create a MultiStepScheduler instance with a config dict and optimizer for multi-step LR scheduling', 'review the MultiStepScheduler get_iter_lr method to understand warmup and iteration-based LR decay logic', 'review the MultiStepScheduler get_epoch_lr method to understand epoch-based LR decay using bisect_right', 'refactor the MultiStepScheduler warmup logic to support a different warmup schedule formula', 'summarize the MultiStepScheduler class which implements multi-step LR decay with optional warmup in iter or epoch mode', 'create a StepScheduler with config and optimizer for step-based learning rate scheduling', 'review the StepScheduler __init__ to understand config parameters like step_size, lr_ratio, and warmup settings', 'summarize the get_epoch_lr method that computes per-epoch learning rates using step decay', 'refactor the StepScheduler warmup logic to support a different warmup schedule formula']
```

Usage

```
{'create_cosine_annealing_scheduler': 'create a CosineAnnealingScheduler instance with config and optimizer for cosine annealing learning rate scheduling', 'review_CosineAnnealingScheduler_init': 'review the CosineAnnealingScheduler __init__ to understand how eta_min, T_max, warmup_iterations, and warmup_factor are configured', 'summarize_get_iter_lr': 'summarize the get_iter_lr method that computes per-iteration learning rates using cosine annealing with optional warmup', 'test_CosineAnnealingScheduler_warmup': 'test the CosineAnnealingScheduler warmup phase to verify learning rate ramps up from warmup_factor to base_lr', 'refactor_CosineAnnealingScheduler_eta_mins': 'refactor the CosineAnnealingScheduler to customize how eta_mins are scaled relative to each param group base learning rate'}
```

## File: facebookresearch_r-mae/pretrain/optim/scheduler/lr_scheduler.py

Prompts

```
['create a CosineAnnealingScheduler instance with config and optimizer for cosine annealing learning rate scheduling', 'review the CosineAnnealingScheduler __init__ to understand how eta_min, T_max, warmup_iterations, and warmup_factor are configured', 'summarize the get_iter_lr method that computes per-iteration learning rates using cosine annealing with optional warmup', 'test the CosineAnnealingScheduler warmup phase to verify learning rate ramps up from warmup_factor to base_lr', 'refactor the CosineAnnealingScheduler to customize how eta_mins are scaled relative to each param group base learning rate', 'create a BaseScheduler instance with a config dict and torch optimizer for learning rate scheduling', 'step the BaseScheduler forward by one iteration to update learning rates for each param group', 'step the BaseScheduler forward by one epoch to update learning rates for each param group', 'get the serializable state dict from a BaseScheduler instance excluding the optimizer and config', 'load a previously saved state dict into a BaseScheduler and restore the last epoch and iteration', 'create a MultiStepScheduler instance with a config dict and optimizer for multi-step LR scheduling', 'review the MultiStepScheduler get_iter_lr method to understand warmup and iteration-based LR decay logic', 'review the MultiStepScheduler get_epoch_lr method to understand epoch-based LR decay using bisect_right', 'refactor the MultiStepScheduler warmup logic to support a different warmup schedule formula', 'summarize the MultiStepScheduler class which implements multi-step LR decay with optional warmup in iter or epoch mode', 'create a StepScheduler with config and optimizer for step-based learning rate scheduling', 'review the StepScheduler __init__ to understand config parameters like step_size, lr_ratio, and warmup settings', 'summarize the get_epoch_lr method that computes per-epoch learning rates using step decay', 'refactor the StepScheduler warmup logic to support a different warmup schedule formula']
```

Usage

```
{'create_basescheduler': 'create a BaseScheduler instance with a config dict and torch optimizer for learning rate scheduling', 'step_basescheduler': 'step the BaseScheduler forward by one iteration to update learning rates for each param group', 'step_epoch_basescheduler': 'step the BaseScheduler forward by one epoch to update learning rates for each param group', 'state_dict_basescheduler': 'get the serializable state dict from a BaseScheduler instance excluding the optimizer and config', 'load_state_dict_basescheduler': 'load a previously saved state dict into a BaseScheduler and restore the last epoch and iteration'}
```

## File: facebookresearch_r-mae/pretrain/optim/scheduler/multi_step_scheduler.py

Prompts

```
['create a CosineAnnealingScheduler instance with config and optimizer for cosine annealing learning rate scheduling', 'review the CosineAnnealingScheduler __init__ to understand how eta_min, T_max, warmup_iterations, and warmup_factor are configured', 'summarize the get_iter_lr method that computes per-iteration learning rates using cosine annealing with optional warmup', 'test the CosineAnnealingScheduler warmup phase to verify learning rate ramps up from warmup_factor to base_lr', 'refactor the CosineAnnealingScheduler to customize how eta_mins are scaled relative to each param group base learning rate', 'create a BaseScheduler instance with a config dict and torch optimizer for learning rate scheduling', 'step the BaseScheduler forward by one iteration to update learning rates for each param group', 'step the BaseScheduler forward by one epoch to update learning rates for each param group', 'get the serializable state dict from a BaseScheduler instance excluding the optimizer and config', 'load a previously saved state dict into a BaseScheduler and restore the last epoch and iteration', 'create a MultiStepScheduler instance with a config dict and optimizer for multi-step LR scheduling', 'review the MultiStepScheduler get_iter_lr method to understand warmup and iteration-based LR decay logic', 'review the MultiStepScheduler get_epoch_lr method to understand epoch-based LR decay using bisect_right', 'refactor the MultiStepScheduler warmup logic to support a different warmup schedule formula', 'summarize the MultiStepScheduler class which implements multi-step LR decay with optional warmup in iter or epoch mode', 'create a StepScheduler with config and optimizer for step-based learning rate scheduling', 'review the StepScheduler __init__ to understand config parameters like step_size, lr_ratio, and warmup settings', 'summarize the get_epoch_lr method that computes per-epoch learning rates using step decay', 'refactor the StepScheduler warmup logic to support a different warmup schedule formula']
```

Usage

```
{'create_MultiStepScheduler': 'create a MultiStepScheduler instance with a config dict and optimizer for multi-step LR scheduling', 'review_MultiStepScheduler_get_iter_lr': 'review the MultiStepScheduler get_iter_lr method to understand warmup and iteration-based LR decay logic', 'review_MultiStepScheduler_get_epoch_lr': 'review the MultiStepScheduler get_epoch_lr method to understand epoch-based LR decay using bisect_right', 'refactor_MultiStepScheduler_warmup': 'refactor the MultiStepScheduler warmup logic to support a different warmup schedule formula', 'summarize_MultiStepScheduler': 'summarize the MultiStepScheduler class which implements multi-step LR decay with optional warmup in iter or epoch mode'}
```

## File: facebookresearch_r-mae/pretrain/optim/scheduler/step_scheduler.py

Prompts

```
['create a CosineAnnealingScheduler instance with config and optimizer for cosine annealing learning rate scheduling', 'review the CosineAnnealingScheduler __init__ to understand how eta_min, T_max, warmup_iterations, and warmup_factor are configured', 'summarize the get_iter_lr method that computes per-iteration learning rates using cosine annealing with optional warmup', 'test the CosineAnnealingScheduler warmup phase to verify learning rate ramps up from warmup_factor to base_lr', 'refactor the CosineAnnealingScheduler to customize how eta_mins are scaled relative to each param group base learning rate', 'create a BaseScheduler instance with a config dict and torch optimizer for learning rate scheduling', 'step the BaseScheduler forward by one iteration to update learning rates for each param group', 'step the BaseScheduler forward by one epoch to update learning rates for each param group', 'get the serializable state dict from a BaseScheduler instance excluding the optimizer and config', 'load a previously saved state dict into a BaseScheduler and restore the last epoch and iteration', 'create a MultiStepScheduler instance with a config dict and optimizer for multi-step LR scheduling', 'review the MultiStepScheduler get_iter_lr method to understand warmup and iteration-based LR decay logic', 'review the MultiStepScheduler get_epoch_lr method to understand epoch-based LR decay using bisect_right', 'refactor the MultiStepScheduler warmup logic to support a different warmup schedule formula', 'summarize the MultiStepScheduler class which implements multi-step LR decay with optional warmup in iter or epoch mode', 'create a StepScheduler with config and optimizer for step-based learning rate scheduling', 'review the StepScheduler __init__ to understand config parameters like step_size, lr_ratio, and warmup settings', 'summarize the get_epoch_lr method that computes per-epoch learning rates using step decay', 'refactor the StepScheduler warmup logic to support a different warmup schedule formula']
```

Usage

```
{'create_step_scheduler': 'create a StepScheduler with config and optimizer for step-based learning rate scheduling', 'review_step_scheduler_init': 'review the StepScheduler __init__ to understand config parameters like step_size, lr_ratio, and warmup settings', 'summarize_get_iter_lr': 'summarize the get_iter_lr method that computes per-iteration learning rates with optional warmup', 'summarize_get_epoch_lr': 'summarize the get_epoch_lr method that computes per-epoch learning rates using step decay', 'refactor_step_scheduler_warmup': 'refactor the StepScheduler warmup logic to support a different warmup schedule formula'}
```

