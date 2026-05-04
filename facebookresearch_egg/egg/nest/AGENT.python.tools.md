# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/nest/common.py

Prompts

```
['parse a JSON config dict into all permutations of CLI argument lists for hyperparameter sweeps', 'read a JSON config file and generate all CLI argument permutations for running experiment sweeps', 'build a JSON config with multiple values per key to generate all combinations of CLI arguments', 'test parse_json_sweep with a config dict containing int, float, bool, and string values', 'refactor the to_arg helper to support additional types like lists or nested dicts', 'run the grid function to generate parameter combinations for hyperparameter sweeps', 'run dict2string to convert a dictionary of hyperparameters into CLI argument strings', 'test the grid function to verify it yields parameter strings for all combinations', 'test dict2string with int, float, bool, and string values to verify CLI output', 'refactor the grid function to support dynamic parameter ranges instead of hardcoded values', 'build a SlurmWrapper to wrap a runnable callable for SLURM job submission with checkpointing support', 'run the SlurmWrapper checkpoint method to return a DelayedSubmission for submitit checkpointing', 'build a ConcurrentWrapper to run a callable with per-job stdout and stderr logging to a directory', 'run the ConcurrentWrapper to execute a runnable on a round-robin assigned CUDA device', 'review the SlurmWrapper and ConcurrentWrapper classes for wrapping callables in distributed training environments']
```

Usage

```
{'parse_json_sweep_config': 'parse a JSON config dict into all permutations of CLI argument lists for hyperparameter sweeps', 'sweep_from_file': 'read a JSON config file and generate all CLI argument permutations for running experiment sweeps', 'build_sweep_config': 'build a JSON config with multiple values per key to generate all combinations of CLI arguments', 'test_parse_json_sweep': 'test parse_json_sweep with a config dict containing int, float, bool, and string values', 'refactor_to_arg': 'refactor the to_arg helper to support additional types like lists or nested dicts'}
```

## File: facebookresearch_egg/egg/nest/example.py

Prompts

```
['parse a JSON config dict into all permutations of CLI argument lists for hyperparameter sweeps', 'read a JSON config file and generate all CLI argument permutations for running experiment sweeps', 'build a JSON config with multiple values per key to generate all combinations of CLI arguments', 'test parse_json_sweep with a config dict containing int, float, bool, and string values', 'refactor the to_arg helper to support additional types like lists or nested dicts', 'run the grid function to generate parameter combinations for hyperparameter sweeps', 'run dict2string to convert a dictionary of hyperparameters into CLI argument strings', 'test the grid function to verify it yields parameter strings for all combinations', 'test dict2string with int, float, bool, and string values to verify CLI output', 'refactor the grid function to support dynamic parameter ranges instead of hardcoded values', 'build a SlurmWrapper to wrap a runnable callable for SLURM job submission with checkpointing support', 'run the SlurmWrapper checkpoint method to return a DelayedSubmission for submitit checkpointing', 'build a ConcurrentWrapper to run a callable with per-job stdout and stderr logging to a directory', 'run the ConcurrentWrapper to execute a runnable on a round-robin assigned CUDA device', 'review the SlurmWrapper and ConcurrentWrapper classes for wrapping callables in distributed training environments']
```

Usage

```
{'run_grid': 'run the grid function to generate parameter combinations for hyperparameter sweeps', 'run_dict2string': 'run dict2string to convert a dictionary of hyperparameters into CLI argument strings', 'test_grid': 'test the grid function to verify it yields parameter strings for all combinations', 'test_dict2string': 'test dict2string with int, float, bool, and string values to verify CLI output', 'refactor_grid': 'refactor the grid function to support dynamic parameter ranges instead of hardcoded values'}
```

## File: facebookresearch_egg/egg/nest/wrappers.py

Prompts

```
['parse a JSON config dict into all permutations of CLI argument lists for hyperparameter sweeps', 'read a JSON config file and generate all CLI argument permutations for running experiment sweeps', 'build a JSON config with multiple values per key to generate all combinations of CLI arguments', 'test parse_json_sweep with a config dict containing int, float, bool, and string values', 'refactor the to_arg helper to support additional types like lists or nested dicts', 'run the grid function to generate parameter combinations for hyperparameter sweeps', 'run dict2string to convert a dictionary of hyperparameters into CLI argument strings', 'test the grid function to verify it yields parameter strings for all combinations', 'test dict2string with int, float, bool, and string values to verify CLI output', 'refactor the grid function to support dynamic parameter ranges instead of hardcoded values', 'build a SlurmWrapper to wrap a runnable callable for SLURM job submission with checkpointing support', 'run the SlurmWrapper checkpoint method to return a DelayedSubmission for submitit checkpointing', 'build a ConcurrentWrapper to run a callable with per-job stdout and stderr logging to a directory', 'run the ConcurrentWrapper to execute a runnable on a round-robin assigned CUDA device', 'review the SlurmWrapper and ConcurrentWrapper classes for wrapping callables in distributed training environments']
```

Usage

```
{'build_slurm_wrapper': 'build a SlurmWrapper to wrap a runnable callable for SLURM job submission with checkpointing support', 'run_slurm_wrapper_checkpoint': 'run the SlurmWrapper checkpoint method to return a DelayedSubmission for submitit checkpointing', 'build_concurrent_wrapper': 'build a ConcurrentWrapper to run a callable with per-job stdout and stderr logging to a directory', 'run_concurrent_wrapper_cuda': 'run the ConcurrentWrapper to execute a runnable on a round-robin assigned CUDA device', 'review_wrappers_classes': 'review the SlurmWrapper and ConcurrentWrapper classes for wrapping callables in distributed training environments'}
```

