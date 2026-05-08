# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/nn/checkpoint.py

Prompts

```
['summarize the checkpoint_wrapper function that wraps a module for activation checkpointing via fairscale', 'review the checkpoint_wrapper import shim that falls back to a dummy if fairscale is missing', 'test the checkpoint_wrapper function to confirm it raises ImportError when fairscale is not installed', 'refactor the checkpoint_wrapper shim to support an alternative activation checkpointing library', 'build a python module that uses checkpoint_wrapper to enable activation checkpointing on a neural network module', 'create a learning rate scheduler using lr_scheduler_factory with an optimizer and config options', 'use ReduceOnPlateauLRScheduler to decay learning rate when validation loss plateaus during training', 'use CosineLRScheduler to decay learning rate following a cosine annealing schedule over max steps', 'use InvSqrtLRScheduler to decay learning rate at an inverse square root rate with warmup', 'use LinearLRScheduler to decay learning rate linearly from initial value to zero over max steps']
```

Usage

```
{'summarize_checkpoint_wrapper': 'summarize the checkpoint_wrapper function that wraps a module for activation checkpointing via fairscale', 'review_checkpoint_wrapper': 'review the checkpoint_wrapper import shim that falls back to a dummy if fairscale is missing', 'test_checkpoint_wrapper': 'test the checkpoint_wrapper function to confirm it raises ImportError when fairscale is not installed', 'refactor_checkpoint_wrapper': 'refactor the checkpoint_wrapper shim to support an alternative activation checkpointing library', 'build_checkpoint_wrapper': 'build a python module that uses checkpoint_wrapper to enable activation checkpointing on a neural network module'}
```

## File: facebookresearch_parlai/parlai/nn/lr_scheduler.py

Prompts

```
['summarize the checkpoint_wrapper function that wraps a module for activation checkpointing via fairscale', 'review the checkpoint_wrapper import shim that falls back to a dummy if fairscale is missing', 'test the checkpoint_wrapper function to confirm it raises ImportError when fairscale is not installed', 'refactor the checkpoint_wrapper shim to support an alternative activation checkpointing library', 'build a python module that uses checkpoint_wrapper to enable activation checkpointing on a neural network module', 'create a learning rate scheduler using lr_scheduler_factory with an optimizer and config options', 'use ReduceOnPlateauLRScheduler to decay learning rate when validation loss plateaus during training', 'use CosineLRScheduler to decay learning rate following a cosine annealing schedule over max steps', 'use InvSqrtLRScheduler to decay learning rate at an inverse square root rate with warmup', 'use LinearLRScheduler to decay learning rate linearly from initial value to zero over max steps']
```

Usage

```
{'create_lr_scheduler': 'create a learning rate scheduler using lr_scheduler_factory with an optimizer and config options', 'use_reduceonplateau_scheduler': 'use ReduceOnPlateauLRScheduler to decay learning rate when validation loss plateaus during training', 'use_cosine_scheduler': 'use CosineLRScheduler to decay learning rate following a cosine annealing schedule over max steps', 'use_invsqrt_scheduler': 'use InvSqrtLRScheduler to decay learning rate at an inverse square root rate with warmup', 'use_linear_scheduler': 'use LinearLRScheduler to decay learning rate linearly from initial value to zero over max steps'}
```

