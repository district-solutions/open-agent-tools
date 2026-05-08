# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/cli/arg_utils.py

Prompts

```
['use maybe_get_arg to parse an optional string argument from the command line by name', 'use maybe_get_arg with boolean_arg=True to parse a boolean flag from the command line', 'use maybe_get_arg with positional=True to parse a positional argument from the command line', 'use maybe_get_arg with positional=True and position to parse a positional argument at a specific index', 'use maybe_get_arg to safely parse a CLI argument that may not be present without raising errors', 'get a Runner class by name from the registered runners dictionary using get()', 'run a standard model training experiment using the TrainingRunner registered under the train key', 'run a lottery ticket hypothesis experiment with iterative pruning using the LotteryRunner registered under the lottery key', 'run a lottery branch experiment using the BranchRunner registered under the lottery_branch key', 'inspect the registered_runners dictionary to see available runner types: train, lottery, and lottery_branch', 'create a JobArgs dataclass instance with replicate, quiet, and evaluate_only_at_end settings', 'configure a JobArgs instance to run a specific replicate of a lottery ticket experiment', 'configure a JobArgs instance with quiet mode to suppress training status logging', 'configure a JobArgs instance to evaluate the test set only before and after training', 'run maybe_get_default_hparams to fetch default hyperparameters from the model registry']
```

Usage

```
{'maybe_get_arg_optional_string': 'use maybe_get_arg to parse an optional string argument from the command line by name', 'maybe_get_arg_boolean_flag': 'use maybe_get_arg with boolean_arg=True to parse a boolean flag from the command line', 'maybe_get_arg_positional': 'use maybe_get_arg with positional=True to parse a positional argument from the command line', 'maybe_get_arg_positional_indexed': 'use maybe_get_arg with positional=True and position to parse a positional argument at a specific index', 'maybe_get_arg_safe_parse': 'use maybe_get_arg to safely parse a CLI argument that may not be present without raising errors'}
```

## File: facebookresearch_openlth/cli/runner_registry.py

Prompts

```
['use maybe_get_arg to parse an optional string argument from the command line by name', 'use maybe_get_arg with boolean_arg=True to parse a boolean flag from the command line', 'use maybe_get_arg with positional=True to parse a positional argument from the command line', 'use maybe_get_arg with positional=True and position to parse a positional argument at a specific index', 'use maybe_get_arg to safely parse a CLI argument that may not be present without raising errors', 'get a Runner class by name from the registered runners dictionary using get()', 'run a standard model training experiment using the TrainingRunner registered under the train key', 'run a lottery ticket hypothesis experiment with iterative pruning using the LotteryRunner registered under the lottery key', 'run a lottery branch experiment using the BranchRunner registered under the lottery_branch key', 'inspect the registered_runners dictionary to see available runner types: train, lottery, and lottery_branch', 'create a JobArgs dataclass instance with replicate, quiet, and evaluate_only_at_end settings', 'configure a JobArgs instance to run a specific replicate of a lottery ticket experiment', 'configure a JobArgs instance with quiet mode to suppress training status logging', 'configure a JobArgs instance to evaluate the test set only before and after training', 'run maybe_get_default_hparams to fetch default hyperparameters from the model registry']
```

Usage

```
{'get_runner_by_name': 'get a Runner class by name from the registered runners dictionary using get()', 'run_training_experiment': 'run a standard model training experiment using the TrainingRunner registered under the train key', 'run_lottery_ticket_experiment': 'run a lottery ticket hypothesis experiment with iterative pruning using the LotteryRunner registered under the lottery key', 'run_lottery_branch_experiment': 'run a lottery branch experiment using the BranchRunner registered under the lottery_branch key', 'list_registered_runners': 'inspect the registered_runners dictionary to see available runner types: train, lottery, and lottery_branch'}
```

## File: facebookresearch_openlth/cli/shared_args.py

Prompts

```
['use maybe_get_arg to parse an optional string argument from the command line by name', 'use maybe_get_arg with boolean_arg=True to parse a boolean flag from the command line', 'use maybe_get_arg with positional=True to parse a positional argument from the command line', 'use maybe_get_arg with positional=True and position to parse a positional argument at a specific index', 'use maybe_get_arg to safely parse a CLI argument that may not be present without raising errors', 'get a Runner class by name from the registered runners dictionary using get()', 'run a standard model training experiment using the TrainingRunner registered under the train key', 'run a lottery ticket hypothesis experiment with iterative pruning using the LotteryRunner registered under the lottery key', 'run a lottery branch experiment using the BranchRunner registered under the lottery_branch key', 'inspect the registered_runners dictionary to see available runner types: train, lottery, and lottery_branch', 'create a JobArgs dataclass instance with replicate, quiet, and evaluate_only_at_end settings', 'configure a JobArgs instance to run a specific replicate of a lottery ticket experiment', 'configure a JobArgs instance with quiet mode to suppress training status logging', 'configure a JobArgs instance to evaluate the test set only before and after training', 'run maybe_get_default_hparams to fetch default hyperparameters from the model registry']
```

Usage

```
{'create_jobargs_dataclass': 'create a JobArgs dataclass instance with replicate, quiet, and evaluate_only_at_end settings', 'configure_jobargs_replicate': 'configure a JobArgs instance to run a specific replicate of a lottery ticket experiment', 'configure_jobargs_quiet': 'configure a JobArgs instance with quiet mode to suppress training status logging', 'configure_jobargs_evaluate_only_at_end': 'configure a JobArgs instance to evaluate the test set only before and after training', 'run_maybe_get_default_hparams': 'run maybe_get_default_hparams to fetch default hyperparameters from the model registry'}
```

