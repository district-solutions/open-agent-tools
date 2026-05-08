# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_nevergrad_sweeper/hydra_plugins/hydra_nevergrad_sweeper/_impl.py

Prompts

```
['create a nevergrad Choice parameter from a list or ListConfig of candidate values', 'create a nevergrad Scalar or Log parameter from a config dict with init, lower, upper, step, and integer fields', 'create a nevergrad parameter from a Hydra override supporting choice, range, and interval sweeps', 'setup the NevergradSweeperImpl with a Hydra context, task function, and config to instantiate the launcher', 'run a Nevergrad optimization sweep over a parameter space using a specified optimizer, budget, and number of workers', 'create a NevergradSweeper instance with an OptimConf and optional parametrization DictConfig', 'setup the NevergradSweeper with a HydraContext, TaskFunction, and DictConfig before sweeping', 'run a hyperparameter sweep using Nevergrad optimizer with a list of string arguments', 'review the NevergradSweeper class that interfaces Hydra with Nevergrad for optimization', 'refactor the NevergradSweeper sweep method to support custom failure handling logic']
```

Usage

```
{'create_nevergrad_choice_param': 'create a nevergrad Choice parameter from a list or ListConfig of candidate values', 'create_nevergrad_scalar_param': 'create a nevergrad Scalar or Log parameter from a config dict with init, lower, upper, step, and integer fields', 'create_nevergrad_param_from_override': 'create a nevergrad parameter from a Hydra override supporting choice, range, and interval sweeps', 'setup_nevergrad_sweeper': 'setup the NevergradSweeperImpl with a Hydra context, task function, and config to instantiate the launcher', 'run_nevergrad_sweep': 'run a Nevergrad optimization sweep over a parameter space using a specified optimizer, budget, and number of workers'}
```

## File: facebookresearch_hydra/plugins/hydra_nevergrad_sweeper/hydra_plugins/hydra_nevergrad_sweeper/nevergrad_sweeper.py

Prompts

```
['create a nevergrad Choice parameter from a list or ListConfig of candidate values', 'create a nevergrad Scalar or Log parameter from a config dict with init, lower, upper, step, and integer fields', 'create a nevergrad parameter from a Hydra override supporting choice, range, and interval sweeps', 'setup the NevergradSweeperImpl with a Hydra context, task function, and config to instantiate the launcher', 'run a Nevergrad optimization sweep over a parameter space using a specified optimizer, budget, and number of workers', 'create a NevergradSweeper instance with an OptimConf and optional parametrization DictConfig', 'setup the NevergradSweeper with a HydraContext, TaskFunction, and DictConfig before sweeping', 'run a hyperparameter sweep using Nevergrad optimizer with a list of string arguments', 'review the NevergradSweeper class that interfaces Hydra with Nevergrad for optimization', 'refactor the NevergradSweeper sweep method to support custom failure handling logic']
```

Usage

```
{'init_NevergradSweeper': 'create a NevergradSweeper instance with an OptimConf and optional parametrization DictConfig', 'setup_NevergradSweeper': 'setup the NevergradSweeper with a HydraContext, TaskFunction, and DictConfig before sweeping', 'sweep_NevergradSweeper': 'run a hyperparameter sweep using Nevergrad optimizer with a list of string arguments', 'review_NevergradSweeper_class': 'review the NevergradSweeper class that interfaces Hydra with Nevergrad for optimization', 'refactor_NevergradSweeper_sweep': 'refactor the NevergradSweeper sweep method to support custom failure handling logic'}
```

