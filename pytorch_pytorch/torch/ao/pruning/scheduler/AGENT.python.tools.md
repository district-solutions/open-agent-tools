# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/pruning/scheduler/base_scheduler.py

Prompts

```
['create a BaseScheduler instance to manage sparsity level scheduling for a PyTorch sparsifier', 'test the BaseScheduler.step method to update sparsity levels across sparsifier parameter groups', 'review the BaseScheduler.state_dict method that returns scheduler state as a dictionary excluding the sparsifier', 'refactor the BaseScheduler.load_state_dict method to restore scheduler state from a previously saved dictionary', 'summarize the BaseScheduler.get_last_sl method that returns the last computed sparsity level', 'create a CubicSL pruning scheduler with initial and final sparsity levels', 'test the CubicSL.sparsity_compute_fn static method with given sparsity parameters', 'get current sparsity levels from a CubicSL scheduler instance', 'build a cubic sparsity schedule that ramps from init_sl to final sl over total_t steps', 'review the CubicSL pruning scheduler class and its sparsity computation logic', 'create a LambdaSL pruning scheduler that applies a single lambda function to all parameter groups', 'build a LambdaSL scheduler with a list of lambda functions, one per parameter group', 'test the LambdaSL scheduler get_sl method to retrieve current sparsity levels', 'refactor the LambdaSL scheduler to enable verbose mode for printing sparsity updates', 'review the LambdaSL scheduler last_epoch parameter behavior when initialized with -1']
```

Usage

```
{'create_BaseScheduler': 'create a BaseScheduler instance to manage sparsity level scheduling for a PyTorch sparsifier', 'test_BaseScheduler_step': 'test the BaseScheduler.step method to update sparsity levels across sparsifier parameter groups', 'review_BaseScheduler_state_dict': 'review the BaseScheduler.state_dict method that returns scheduler state as a dictionary excluding the sparsifier', 'refactor_BaseScheduler_load_state_dict': 'refactor the BaseScheduler.load_state_dict method to restore scheduler state from a previously saved dictionary', 'summarize_BaseScheduler_get_last_sl': 'summarize the BaseScheduler.get_last_sl method that returns the last computed sparsity level'}
```

## File: pytorch_pytorch/torch/ao/pruning/scheduler/cubic_scheduler.py

Prompts

```
['create a BaseScheduler instance to manage sparsity level scheduling for a PyTorch sparsifier', 'test the BaseScheduler.step method to update sparsity levels across sparsifier parameter groups', 'review the BaseScheduler.state_dict method that returns scheduler state as a dictionary excluding the sparsifier', 'refactor the BaseScheduler.load_state_dict method to restore scheduler state from a previously saved dictionary', 'summarize the BaseScheduler.get_last_sl method that returns the last computed sparsity level', 'create a CubicSL pruning scheduler with initial and final sparsity levels', 'test the CubicSL.sparsity_compute_fn static method with given sparsity parameters', 'get current sparsity levels from a CubicSL scheduler instance', 'build a cubic sparsity schedule that ramps from init_sl to final sl over total_t steps', 'review the CubicSL pruning scheduler class and its sparsity computation logic', 'create a LambdaSL pruning scheduler that applies a single lambda function to all parameter groups', 'build a LambdaSL scheduler with a list of lambda functions, one per parameter group', 'test the LambdaSL scheduler get_sl method to retrieve current sparsity levels', 'refactor the LambdaSL scheduler to enable verbose mode for printing sparsity updates', 'review the LambdaSL scheduler last_epoch parameter behavior when initialized with -1']
```

Usage

```
{'create_scheduler_CubicSL': 'create a CubicSL pruning scheduler with initial and final sparsity levels', 'test_sparsity_compute_fn': 'test the CubicSL.sparsity_compute_fn static method with given sparsity parameters', 'get_sparsity_levels_CubicSL': 'get current sparsity levels from a CubicSL scheduler instance', 'build_cubic_pruning_schedule': 'build a cubic sparsity schedule that ramps from init_sl to final sl over total_t steps', 'review_CubicSL_scheduler': 'review the CubicSL pruning scheduler class and its sparsity computation logic'}
```

## File: pytorch_pytorch/torch/ao/pruning/scheduler/lambda_scheduler.py

Prompts

```
['create a BaseScheduler instance to manage sparsity level scheduling for a PyTorch sparsifier', 'test the BaseScheduler.step method to update sparsity levels across sparsifier parameter groups', 'review the BaseScheduler.state_dict method that returns scheduler state as a dictionary excluding the sparsifier', 'refactor the BaseScheduler.load_state_dict method to restore scheduler state from a previously saved dictionary', 'summarize the BaseScheduler.get_last_sl method that returns the last computed sparsity level', 'create a CubicSL pruning scheduler with initial and final sparsity levels', 'test the CubicSL.sparsity_compute_fn static method with given sparsity parameters', 'get current sparsity levels from a CubicSL scheduler instance', 'build a cubic sparsity schedule that ramps from init_sl to final sl over total_t steps', 'review the CubicSL pruning scheduler class and its sparsity computation logic', 'create a LambdaSL pruning scheduler that applies a single lambda function to all parameter groups', 'build a LambdaSL scheduler with a list of lambda functions, one per parameter group', 'test the LambdaSL scheduler get_sl method to retrieve current sparsity levels', 'refactor the LambdaSL scheduler to enable verbose mode for printing sparsity updates', 'review the LambdaSL scheduler last_epoch parameter behavior when initialized with -1']
```

Usage

```
{'create_LambdaSL_scheduler': 'create a LambdaSL pruning scheduler that applies a single lambda function to all parameter groups', 'build_LambdaSL_multi_lambda': 'build a LambdaSL scheduler with a list of lambda functions, one per parameter group', 'test_LambdaSL_get_sl': 'test the LambdaSL scheduler get_sl method to retrieve current sparsity levels', 'refactor_LambdaSL_verbose': 'refactor the LambdaSL scheduler to enable verbose mode for printing sparsity updates', 'review_LambdaSL_last_epoch': 'review the LambdaSL scheduler last_epoch parameter behavior when initialized with -1'}
```

