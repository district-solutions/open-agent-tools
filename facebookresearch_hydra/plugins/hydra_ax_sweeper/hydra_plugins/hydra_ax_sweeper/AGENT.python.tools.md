# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_ax_sweeper/hydra_plugins/hydra_ax_sweeper/_core.py

Prompts

```
['run a Hydra Ax sweeper to optimize hyperparameters using the Ax platform', 'create a batch of parallel trials from an AxClient with configurable parallelism', 'parse Hydra command line sweep overrides into Ax parameter dictionaries', 'convert a dictionary of parameters into a list of key=value string arguments', 'encode a list of Ax parameter dicts into a human-readable log string', 'create an EarlyStopper instance configured to minimize a loss value with a given epsilon threshold', 'create an EarlyStopper instance configured to maximize a reward value with a given epsilon threshold', 'check if the optimization process should stop based on the current best value and parameters', 'review the EarlyStopper class and its epsilon-based improvement detection logic for minimization and maximization', 'refactor the EarlyStopper class to customize the logging messages for new best values and early stopping', 'create an AxSweeper instance with an AxConfig and optional max_batch_size for Hydra Ax integration', 'setup the AxSweeper with a HydraContext, TaskFunction, and DictConfig before starting a sweep', 'sweep a list of string arguments using the AxSweeper to run Ax Platform optimization trials', 'review the AxSweeper class that interfaces with the Ax Platform for hyperparameter optimization', 'summarize the AxSweeper setup method that delegates configuration to the CoreAxSweeper internal sweeper']
```

Usage

```
{'run_ax_sweep': 'run a Hydra Ax sweeper to optimize hyperparameters using the Ax platform', 'create_trial_batch': 'create a batch of parallel trials from an AxClient with configurable parallelism', 'parse_commandline_args': 'parse Hydra command line sweep overrides into Ax parameter dictionaries', 'map_params_to_arg_list': 'convert a dictionary of parameters into a list of key=value string arguments', 'encode_parameters_to_string': 'encode a list of Ax parameter dicts into a human-readable log string'}
```

## File: facebookresearch_hydra/plugins/hydra_ax_sweeper/hydra_plugins/hydra_ax_sweeper/_earlystopper.py

Prompts

```
['run a Hydra Ax sweeper to optimize hyperparameters using the Ax platform', 'create a batch of parallel trials from an AxClient with configurable parallelism', 'parse Hydra command line sweep overrides into Ax parameter dictionaries', 'convert a dictionary of parameters into a list of key=value string arguments', 'encode a list of Ax parameter dicts into a human-readable log string', 'create an EarlyStopper instance configured to minimize a loss value with a given epsilon threshold', 'create an EarlyStopper instance configured to maximize a reward value with a given epsilon threshold', 'check if the optimization process should stop based on the current best value and parameters', 'review the EarlyStopper class and its epsilon-based improvement detection logic for minimization and maximization', 'refactor the EarlyStopper class to customize the logging messages for new best values and early stopping', 'create an AxSweeper instance with an AxConfig and optional max_batch_size for Hydra Ax integration', 'setup the AxSweeper with a HydraContext, TaskFunction, and DictConfig before starting a sweep', 'sweep a list of string arguments using the AxSweeper to run Ax Platform optimization trials', 'review the AxSweeper class that interfaces with the Ax Platform for hyperparameter optimization', 'summarize the AxSweeper setup method that delegates configuration to the CoreAxSweeper internal sweeper']
```

Usage

```
{'create_early_stopper_minimize': 'create an EarlyStopper instance configured to minimize a loss value with a given epsilon threshold', 'create_early_stopper_maximize': 'create an EarlyStopper instance configured to maximize a reward value with a given epsilon threshold', 'should_stop_check': 'check if the optimization process should stop based on the current best value and parameters', 'review_early_stopper_logic': 'review the EarlyStopper class and its epsilon-based improvement detection logic for minimization and maximization', 'refactor_early_stopper_logging': 'refactor the EarlyStopper class to customize the logging messages for new best values and early stopping'}
```

## File: facebookresearch_hydra/plugins/hydra_ax_sweeper/hydra_plugins/hydra_ax_sweeper/ax_sweeper.py

Prompts

```
['run a Hydra Ax sweeper to optimize hyperparameters using the Ax platform', 'create a batch of parallel trials from an AxClient with configurable parallelism', 'parse Hydra command line sweep overrides into Ax parameter dictionaries', 'convert a dictionary of parameters into a list of key=value string arguments', 'encode a list of Ax parameter dicts into a human-readable log string', 'create an EarlyStopper instance configured to minimize a loss value with a given epsilon threshold', 'create an EarlyStopper instance configured to maximize a reward value with a given epsilon threshold', 'check if the optimization process should stop based on the current best value and parameters', 'review the EarlyStopper class and its epsilon-based improvement detection logic for minimization and maximization', 'refactor the EarlyStopper class to customize the logging messages for new best values and early stopping', 'create an AxSweeper instance with an AxConfig and optional max_batch_size for Hydra Ax integration', 'setup the AxSweeper with a HydraContext, TaskFunction, and DictConfig before starting a sweep', 'sweep a list of string arguments using the AxSweeper to run Ax Platform optimization trials', 'review the AxSweeper class that interfaces with the Ax Platform for hyperparameter optimization', 'summarize the AxSweeper setup method that delegates configuration to the CoreAxSweeper internal sweeper']
```

Usage

```
{'create_ax_sweeper_instance': 'create an AxSweeper instance with an AxConfig and optional max_batch_size for Hydra Ax integration', 'setup_ax_sweeper': 'setup the AxSweeper with a HydraContext, TaskFunction, and DictConfig before starting a sweep', 'sweep_with_ax': 'sweep a list of string arguments using the AxSweeper to run Ax Platform optimization trials', 'review_ax_sweeper_class': 'review the AxSweeper class that interfaces with the Ax Platform for hyperparameter optimization', 'summarize_ax_sweeper_setup': 'summarize the AxSweeper setup method that delegates configuration to the CoreAxSweeper internal sweeper'}
```

