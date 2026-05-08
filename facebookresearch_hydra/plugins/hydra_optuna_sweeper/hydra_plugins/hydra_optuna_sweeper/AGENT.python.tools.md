# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_optuna_sweeper/hydra_plugins/hydra_optuna_sweeper/_impl.py

Prompts

```
['create an Optuna distribution object from a config dictionary with type, low, high, and choices fields', 'create an Optuna distribution from a Hydra override object supporting choice, range, and interval sweeps', 'parse command line argument strings into Optuna search space distributions and fixed parameter dictionaries', 'run a Hyperparameter optimization sweep using Optuna with configurable trials, sampler, and objective directions', 'configure Optuna trial objects with search space distributions and fixed parameters to generate override tuples', 'create an OptunaSweeper instance with sampler config, direction, storage, study name, and trial count', 'setup the OptunaSweeper with a HydraContext, task function, and DictConfig for Hydra integration', 'sweep a list of argument strings through the OptunaSweeper to run hyperparameter optimization trials', 'review the OptunaSweeper class that interfaces Hydra with Optuna for hyperparameter search', 'summarize the OptunaSweeper init method that delegates to OptunaSweeperImpl with sampler and search space params']
```

Usage

```
{'create_optuna_distribution_from_config': 'create an Optuna distribution object from a config dictionary with type, low, high, and choices fields', 'create_optuna_distribution_from_override': 'create an Optuna distribution from a Hydra override object supporting choice, range, and interval sweeps', 'create_params_from_overrides': 'parse command line argument strings into Optuna search space distributions and fixed parameter dictionaries', 'OptunaSweeperImpl_sweep': 'run a Hyperparameter optimization sweep using Optuna with configurable trials, sampler, and objective directions', 'OptunaSweeperImpl_configure_trials': 'configure Optuna trial objects with search space distributions and fixed parameters to generate override tuples'}
```

## File: facebookresearch_hydra/plugins/hydra_optuna_sweeper/hydra_plugins/hydra_optuna_sweeper/optuna_sweeper.py

Prompts

```
['create an Optuna distribution object from a config dictionary with type, low, high, and choices fields', 'create an Optuna distribution from a Hydra override object supporting choice, range, and interval sweeps', 'parse command line argument strings into Optuna search space distributions and fixed parameter dictionaries', 'run a Hyperparameter optimization sweep using Optuna with configurable trials, sampler, and objective directions', 'configure Optuna trial objects with search space distributions and fixed parameters to generate override tuples', 'create an OptunaSweeper instance with sampler config, direction, storage, study name, and trial count', 'setup the OptunaSweeper with a HydraContext, task function, and DictConfig for Hydra integration', 'sweep a list of argument strings through the OptunaSweeper to run hyperparameter optimization trials', 'review the OptunaSweeper class that interfaces Hydra with Optuna for hyperparameter search', 'summarize the OptunaSweeper init method that delegates to OptunaSweeperImpl with sampler and search space params']
```

Usage

```
{'create_optuna_sweeper_instance': 'create an OptunaSweeper instance with sampler config, direction, storage, study name, and trial count', 'setup_optuna_sweeper': 'setup the OptunaSweeper with a HydraContext, task function, and DictConfig for Hydra integration', 'sweep_optuna_trials': 'sweep a list of argument strings through the OptunaSweeper to run hyperparameter optimization trials', 'review_optuna_sweeper_class': 'review the OptunaSweeper class that interfaces Hydra with Optuna for hyperparameter search', 'summarize_optuna_sweeper_init': 'summarize the OptunaSweeper init method that delegates to OptunaSweeperImpl with sampler and search space params'}
```

