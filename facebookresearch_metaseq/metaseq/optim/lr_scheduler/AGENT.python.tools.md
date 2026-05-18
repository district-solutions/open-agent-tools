# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/optim/lr_scheduler/base_lr_scheduler.py

Prompts

```
['create a BaseLRScheduler instance with a config object and a BaseOptimizer instance', 'review the BaseLRScheduler add_args class method to add parser arguments from a dataclass', 'test the BaseLRScheduler state_dict method to return the best validation loss state', 'test the BaseLRScheduler load_state_dict method to restore the best validation loss from a dict', 'review the BaseLRScheduler step method to update learning rate and track best validation loss', 'build a cosine learning rate scheduler with warmup phase and cyclical cosine annealing for model training', 'create a CosineLRScheduleConfig dataclass to configure warmup updates, max lr, min lr, and period settings', 'run step_update on CosineLRSchedule to compute the learning rate after a given number of training updates', 'review the CosineLRSchedule constructor to understand how it initializes max_lr, period, and warmup parameters', 'refactor the CosineLRSchedule step method to customize epoch boundary learning rate behavior', 'build a learning rate scheduler that decays LR based on inverse square root of update number', 'create an InverseSquareRootLRScheduleConfig dataclass with warmup_updates and warmup_init_lr fields', 'test the step_update method to verify LR changes after each training update step', 'review the InverseSquareRootSchedule warmup phase that linearly increases LR from init to target', 'refactor the InverseSquareRootSchedule decay_factor calculation to use a custom exponent instead of 0.5', 'build a polynomial decay learning rate scheduler with configurable warmup updates and decay power', 'create a PolynomialDecayLRScheduleConfig dataclass with warmup updates, end learning rate, and decay power settings', 'test the step_update method to verify learning rate decays polynomially after warmup phase', 'review the get_next_lr method to understand how it handles fixed LR schedule versus forced annealing', 'refactor the step_begin_epoch method to update learning rate at the beginning of each training epoch']
```

Usage

```
{'create_BaseLRScheduler': 'create a BaseLRScheduler instance with a config object and a BaseOptimizer instance', 'review_BaseLRScheduler_add_args': 'review the BaseLRScheduler add_args class method to add parser arguments from a dataclass', 'test_BaseLRScheduler_state_dict': 'test the BaseLRScheduler state_dict method to return the best validation loss state', 'test_BaseLRScheduler_load_state_dict': 'test the BaseLRScheduler load_state_dict method to restore the best validation loss from a dict', 'review_BaseLRScheduler_step': 'review the BaseLRScheduler step method to update learning rate and track best validation loss'}
```

## File: facebookresearch_metaseq/metaseq/optim/lr_scheduler/cosine_lr_scheduler.py

Prompts

```
['create a BaseLRScheduler instance with a config object and a BaseOptimizer instance', 'review the BaseLRScheduler add_args class method to add parser arguments from a dataclass', 'test the BaseLRScheduler state_dict method to return the best validation loss state', 'test the BaseLRScheduler load_state_dict method to restore the best validation loss from a dict', 'review the BaseLRScheduler step method to update learning rate and track best validation loss', 'build a cosine learning rate scheduler with warmup phase and cyclical cosine annealing for model training', 'create a CosineLRScheduleConfig dataclass to configure warmup updates, max lr, min lr, and period settings', 'run step_update on CosineLRSchedule to compute the learning rate after a given number of training updates', 'review the CosineLRSchedule constructor to understand how it initializes max_lr, period, and warmup parameters', 'refactor the CosineLRSchedule step method to customize epoch boundary learning rate behavior', 'build a learning rate scheduler that decays LR based on inverse square root of update number', 'create an InverseSquareRootLRScheduleConfig dataclass with warmup_updates and warmup_init_lr fields', 'test the step_update method to verify LR changes after each training update step', 'review the InverseSquareRootSchedule warmup phase that linearly increases LR from init to target', 'refactor the InverseSquareRootSchedule decay_factor calculation to use a custom exponent instead of 0.5', 'build a polynomial decay learning rate scheduler with configurable warmup updates and decay power', 'create a PolynomialDecayLRScheduleConfig dataclass with warmup updates, end learning rate, and decay power settings', 'test the step_update method to verify learning rate decays polynomially after warmup phase', 'review the get_next_lr method to understand how it handles fixed LR schedule versus forced annealing', 'refactor the step_begin_epoch method to update learning rate at the beginning of each training epoch']
```

Usage

```
{'build_cosine_lr_scheduler': 'build a cosine learning rate scheduler with warmup phase and cyclical cosine annealing for model training', 'create_CosineLRScheduleConfig': 'create a CosineLRScheduleConfig dataclass to configure warmup updates, max lr, min lr, and period settings', 'run_step_update': 'run step_update on CosineLRSchedule to compute the learning rate after a given number of training updates', 'review_CosineLRSchedule_init': 'review the CosineLRSchedule constructor to understand how it initializes max_lr, period, and warmup parameters', 'refactor_CosineLRSchedule_step': 'refactor the CosineLRSchedule step method to customize epoch boundary learning rate behavior'}
```

## File: facebookresearch_metaseq/metaseq/optim/lr_scheduler/inverse_square_root_schedule.py

Prompts

```
['create a BaseLRScheduler instance with a config object and a BaseOptimizer instance', 'review the BaseLRScheduler add_args class method to add parser arguments from a dataclass', 'test the BaseLRScheduler state_dict method to return the best validation loss state', 'test the BaseLRScheduler load_state_dict method to restore the best validation loss from a dict', 'review the BaseLRScheduler step method to update learning rate and track best validation loss', 'build a cosine learning rate scheduler with warmup phase and cyclical cosine annealing for model training', 'create a CosineLRScheduleConfig dataclass to configure warmup updates, max lr, min lr, and period settings', 'run step_update on CosineLRSchedule to compute the learning rate after a given number of training updates', 'review the CosineLRSchedule constructor to understand how it initializes max_lr, period, and warmup parameters', 'refactor the CosineLRSchedule step method to customize epoch boundary learning rate behavior', 'build a learning rate scheduler that decays LR based on inverse square root of update number', 'create an InverseSquareRootLRScheduleConfig dataclass with warmup_updates and warmup_init_lr fields', 'test the step_update method to verify LR changes after each training update step', 'review the InverseSquareRootSchedule warmup phase that linearly increases LR from init to target', 'refactor the InverseSquareRootSchedule decay_factor calculation to use a custom exponent instead of 0.5', 'build a polynomial decay learning rate scheduler with configurable warmup updates and decay power', 'create a PolynomialDecayLRScheduleConfig dataclass with warmup updates, end learning rate, and decay power settings', 'test the step_update method to verify learning rate decays polynomially after warmup phase', 'review the get_next_lr method to understand how it handles fixed LR schedule versus forced annealing', 'refactor the step_begin_epoch method to update learning rate at the beginning of each training epoch']
```

Usage

```
{'build_inverse_sqrt_lr_scheduler': 'build a learning rate scheduler that decays LR based on inverse square root of update number', 'create_inverse_sqrt_config': 'create an InverseSquareRootLRScheduleConfig dataclass with warmup_updates and warmup_init_lr fields', 'test_step_update_lr': 'test the step_update method to verify LR changes after each training update step', 'review_warmup_phase': 'review the InverseSquareRootSchedule warmup phase that linearly increases LR from init to target', 'refactor_decay_factor': 'refactor the InverseSquareRootSchedule decay_factor calculation to use a custom exponent instead of 0.5'}
```

## File: facebookresearch_metaseq/metaseq/optim/lr_scheduler/polynomial_decay_schedule.py

Prompts

```
['create a BaseLRScheduler instance with a config object and a BaseOptimizer instance', 'review the BaseLRScheduler add_args class method to add parser arguments from a dataclass', 'test the BaseLRScheduler state_dict method to return the best validation loss state', 'test the BaseLRScheduler load_state_dict method to restore the best validation loss from a dict', 'review the BaseLRScheduler step method to update learning rate and track best validation loss', 'build a cosine learning rate scheduler with warmup phase and cyclical cosine annealing for model training', 'create a CosineLRScheduleConfig dataclass to configure warmup updates, max lr, min lr, and period settings', 'run step_update on CosineLRSchedule to compute the learning rate after a given number of training updates', 'review the CosineLRSchedule constructor to understand how it initializes max_lr, period, and warmup parameters', 'refactor the CosineLRSchedule step method to customize epoch boundary learning rate behavior', 'build a learning rate scheduler that decays LR based on inverse square root of update number', 'create an InverseSquareRootLRScheduleConfig dataclass with warmup_updates and warmup_init_lr fields', 'test the step_update method to verify LR changes after each training update step', 'review the InverseSquareRootSchedule warmup phase that linearly increases LR from init to target', 'refactor the InverseSquareRootSchedule decay_factor calculation to use a custom exponent instead of 0.5', 'build a polynomial decay learning rate scheduler with configurable warmup updates and decay power', 'create a PolynomialDecayLRScheduleConfig dataclass with warmup updates, end learning rate, and decay power settings', 'test the step_update method to verify learning rate decays polynomially after warmup phase', 'review the get_next_lr method to understand how it handles fixed LR schedule versus forced annealing', 'refactor the step_begin_epoch method to update learning rate at the beginning of each training epoch']
```

Usage

```
{'build_polynomial_decay_lr_scheduler': 'build a polynomial decay learning rate scheduler with configurable warmup updates and decay power', 'create_PolynomialDecayLRScheduleConfig': 'create a PolynomialDecayLRScheduleConfig dataclass with warmup updates, end learning rate, and decay power settings', 'test_step_update': 'test the step_update method to verify learning rate decays polynomially after warmup phase', 'review_get_next_lr': 'review the get_next_lr method to understand how it handles fixed LR schedule versus forced annealing', 'refactor_step_begin_epoch': 'refactor the step_begin_epoch method to update learning rate at the beginning of each training epoch'}
```

