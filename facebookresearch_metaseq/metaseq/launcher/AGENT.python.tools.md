# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/launcher/opt_baselines.py

Prompts

```
['run an OPT baseline training sweep using the cli_main entry point with a specified model size', 'run a synthetic data benchmark with 50 training steps using the --benchmark flag', 'build a hyperparameter grid for transformer_lm_megatron training via the get_grid function', 'add extra CLI arguments like --model-size and --benchmark to an argparse parser via add_extra_options_func', 'review the get_grid function to understand how GPU counts and model parallelism are validated', 'create a Size dataclass instance with n_layers, emb_size, n_heads, d_head, batch_size, lr, and model_parallel', 'access the ffn_size property on a Size instance to get 4 times the embedding size', 'lookup a model configuration by name from the MODEL_SIZES dictionary such as 13b or 175b', 'use the ComputeEnvs enum to reference AWS, AZURE, FAIR, or RSC compute environments', 'access the VALID_SUBSETS list to get available dataset names like CommonCrawl or Wikipedia_en', 'run a hyperparameter sweep across a grid of configs using SLURM batch jobs', 'copy all Python files from a source directory into a timestamped snapshot for reproducibility', 'generate the training command with distributed settings, save directory, and hyperparameter CLI args', 'generate an sbatch command string with GPU, node, partition, and memory constraints for SLURM', 'check whether a training job in a save directory has finished, failed, or already started', 'run a grid search over hyperparameter configurations using the main sweep launcher function', 'create a hyperparam object with a name and list of values to sweep over', 'get the CLI argument list from a hyperparam instance for a given current value', 'get the save directory key string from a hyperparam instance using its save_dir_key function', 'parse sweep CLI arguments including grid, prefix, num-trials, num-gpus, and environment flags', 'start a background process that monitors SLURM job tombstone files and cancels jobs', 'run the loop that watches for tombstone files and calls scancel on a SLURM job', 'create a scancel tombstone file to trigger cancellation of a running SLURM job', 'create a requeuehold tombstone file to trigger scontrol requeuehold on a SLURM job', 'review the list of SLURM job state codes used to validate job status']
```

Usage

```
{'run_opt_baseline_training': 'run an OPT baseline training sweep using the cli_main entry point with a specified model size', 'run_benchmark_mode': 'run a synthetic data benchmark with 50 training steps using the --benchmark flag', 'build_hyperparameter_grid': 'build a hyperparameter grid for transformer_lm_megatron training via the get_grid function', 'add_cli_options': 'add extra CLI arguments like --model-size and --benchmark to an argparse parser via add_extra_options_func', 'review_get_grid': 'review the get_grid function to understand how GPU counts and model parallelism are validated'}
```

## File: facebookresearch_metaseq/metaseq/launcher/opt_job_constants.py

Prompts

```
['run an OPT baseline training sweep using the cli_main entry point with a specified model size', 'run a synthetic data benchmark with 50 training steps using the --benchmark flag', 'build a hyperparameter grid for transformer_lm_megatron training via the get_grid function', 'add extra CLI arguments like --model-size and --benchmark to an argparse parser via add_extra_options_func', 'review the get_grid function to understand how GPU counts and model parallelism are validated', 'create a Size dataclass instance with n_layers, emb_size, n_heads, d_head, batch_size, lr, and model_parallel', 'access the ffn_size property on a Size instance to get 4 times the embedding size', 'lookup a model configuration by name from the MODEL_SIZES dictionary such as 13b or 175b', 'use the ComputeEnvs enum to reference AWS, AZURE, FAIR, or RSC compute environments', 'access the VALID_SUBSETS list to get available dataset names like CommonCrawl or Wikipedia_en', 'run a hyperparameter sweep across a grid of configs using SLURM batch jobs', 'copy all Python files from a source directory into a timestamped snapshot for reproducibility', 'generate the training command with distributed settings, save directory, and hyperparameter CLI args', 'generate an sbatch command string with GPU, node, partition, and memory constraints for SLURM', 'check whether a training job in a save directory has finished, failed, or already started', 'run a grid search over hyperparameter configurations using the main sweep launcher function', 'create a hyperparam object with a name and list of values to sweep over', 'get the CLI argument list from a hyperparam instance for a given current value', 'get the save directory key string from a hyperparam instance using its save_dir_key function', 'parse sweep CLI arguments including grid, prefix, num-trials, num-gpus, and environment flags', 'start a background process that monitors SLURM job tombstone files and cancels jobs', 'run the loop that watches for tombstone files and calls scancel on a SLURM job', 'create a scancel tombstone file to trigger cancellation of a running SLURM job', 'create a requeuehold tombstone file to trigger scontrol requeuehold on a SLURM job', 'review the list of SLURM job state codes used to validate job status']
```

Usage

```
{'create_Size_dataclass': 'create a Size dataclass instance with n_layers, emb_size, n_heads, d_head, batch_size, lr, and model_parallel', 'access_Size_ffn_size_property': 'access the ffn_size property on a Size instance to get 4 times the embedding size', 'lookup_MODEL_SIZES': 'lookup a model configuration by name from the MODEL_SIZES dictionary such as 13b or 175b', 'use_ComputeEnvs_enum': 'use the ComputeEnvs enum to reference AWS, AZURE, FAIR, or RSC compute environments', 'access_VALID_SUBSETS': 'access the VALID_SUBSETS list to get available dataset names like CommonCrawl or Wikipedia_en'}
```

## File: facebookresearch_metaseq/metaseq/launcher/slurm.py

Prompts

```
['run an OPT baseline training sweep using the cli_main entry point with a specified model size', 'run a synthetic data benchmark with 50 training steps using the --benchmark flag', 'build a hyperparameter grid for transformer_lm_megatron training via the get_grid function', 'add extra CLI arguments like --model-size and --benchmark to an argparse parser via add_extra_options_func', 'review the get_grid function to understand how GPU counts and model parallelism are validated', 'create a Size dataclass instance with n_layers, emb_size, n_heads, d_head, batch_size, lr, and model_parallel', 'access the ffn_size property on a Size instance to get 4 times the embedding size', 'lookup a model configuration by name from the MODEL_SIZES dictionary such as 13b or 175b', 'use the ComputeEnvs enum to reference AWS, AZURE, FAIR, or RSC compute environments', 'access the VALID_SUBSETS list to get available dataset names like CommonCrawl or Wikipedia_en', 'run a hyperparameter sweep across a grid of configs using SLURM batch jobs', 'copy all Python files from a source directory into a timestamped snapshot for reproducibility', 'generate the training command with distributed settings, save directory, and hyperparameter CLI args', 'generate an sbatch command string with GPU, node, partition, and memory constraints for SLURM', 'check whether a training job in a save directory has finished, failed, or already started', 'run a grid search over hyperparameter configurations using the main sweep launcher function', 'create a hyperparam object with a name and list of values to sweep over', 'get the CLI argument list from a hyperparam instance for a given current value', 'get the save directory key string from a hyperparam instance using its save_dir_key function', 'parse sweep CLI arguments including grid, prefix, num-trials, num-gpus, and environment flags', 'start a background process that monitors SLURM job tombstone files and cancels jobs', 'run the loop that watches for tombstone files and calls scancel on a SLURM job', 'create a scancel tombstone file to trigger cancellation of a running SLURM job', 'create a requeuehold tombstone file to trigger scontrol requeuehold on a SLURM job', 'review the list of SLURM job state codes used to validate job status']
```

Usage

```
{'run_slurm_sweep': 'run a hyperparameter sweep across a grid of configs using SLURM batch jobs', 'copy_python_snapshot': 'copy all Python files from a source directory into a timestamped snapshot for reproducibility', 'generate_train_command': 'generate the training command with distributed settings, save directory, and hyperparameter CLI args', 'generate_sbatch_command': 'generate an sbatch command string with GPU, node, partition, and memory constraints for SLURM', 'check_job_status': 'check whether a training job in a save directory has finished, failed, or already started'}
```

## File: facebookresearch_metaseq/metaseq/launcher/sweep.py

Prompts

```
['run an OPT baseline training sweep using the cli_main entry point with a specified model size', 'run a synthetic data benchmark with 50 training steps using the --benchmark flag', 'build a hyperparameter grid for transformer_lm_megatron training via the get_grid function', 'add extra CLI arguments like --model-size and --benchmark to an argparse parser via add_extra_options_func', 'review the get_grid function to understand how GPU counts and model parallelism are validated', 'create a Size dataclass instance with n_layers, emb_size, n_heads, d_head, batch_size, lr, and model_parallel', 'access the ffn_size property on a Size instance to get 4 times the embedding size', 'lookup a model configuration by name from the MODEL_SIZES dictionary such as 13b or 175b', 'use the ComputeEnvs enum to reference AWS, AZURE, FAIR, or RSC compute environments', 'access the VALID_SUBSETS list to get available dataset names like CommonCrawl or Wikipedia_en', 'run a hyperparameter sweep across a grid of configs using SLURM batch jobs', 'copy all Python files from a source directory into a timestamped snapshot for reproducibility', 'generate the training command with distributed settings, save directory, and hyperparameter CLI args', 'generate an sbatch command string with GPU, node, partition, and memory constraints for SLURM', 'check whether a training job in a save directory has finished, failed, or already started', 'run a grid search over hyperparameter configurations using the main sweep launcher function', 'create a hyperparam object with a name and list of values to sweep over', 'get the CLI argument list from a hyperparam instance for a given current value', 'get the save directory key string from a hyperparam instance using its save_dir_key function', 'parse sweep CLI arguments including grid, prefix, num-trials, num-gpus, and environment flags', 'start a background process that monitors SLURM job tombstone files and cancels jobs', 'run the loop that watches for tombstone files and calls scancel on a SLURM job', 'create a scancel tombstone file to trigger cancellation of a running SLURM job', 'create a requeuehold tombstone file to trigger scontrol requeuehold on a SLURM job', 'review the list of SLURM job state codes used to validate job status']
```

Usage

```
{'run_hyperparameter_sweep': 'run a grid search over hyperparameter configurations using the main sweep launcher function', 'create_hyperparam_instance': 'create a hyperparam object with a name and list of values to sweep over', 'get_cli_args_hyperparam': 'get the CLI argument list from a hyperparam instance for a given current value', 'get_save_dir_key_hyperparam': 'get the save directory key string from a hyperparam instance using its save_dir_key function', 'parse_sweep_args': 'parse sweep CLI arguments including grid, prefix, num-trials, num-gpus, and environment flags'}
```

## File: facebookresearch_metaseq/metaseq/launcher/tombyard.py

Prompts

```
['run an OPT baseline training sweep using the cli_main entry point with a specified model size', 'run a synthetic data benchmark with 50 training steps using the --benchmark flag', 'build a hyperparameter grid for transformer_lm_megatron training via the get_grid function', 'add extra CLI arguments like --model-size and --benchmark to an argparse parser via add_extra_options_func', 'review the get_grid function to understand how GPU counts and model parallelism are validated', 'create a Size dataclass instance with n_layers, emb_size, n_heads, d_head, batch_size, lr, and model_parallel', 'access the ffn_size property on a Size instance to get 4 times the embedding size', 'lookup a model configuration by name from the MODEL_SIZES dictionary such as 13b or 175b', 'use the ComputeEnvs enum to reference AWS, AZURE, FAIR, or RSC compute environments', 'access the VALID_SUBSETS list to get available dataset names like CommonCrawl or Wikipedia_en', 'run a hyperparameter sweep across a grid of configs using SLURM batch jobs', 'copy all Python files from a source directory into a timestamped snapshot for reproducibility', 'generate the training command with distributed settings, save directory, and hyperparameter CLI args', 'generate an sbatch command string with GPU, node, partition, and memory constraints for SLURM', 'check whether a training job in a save directory has finished, failed, or already started', 'run a grid search over hyperparameter configurations using the main sweep launcher function', 'create a hyperparam object with a name and list of values to sweep over', 'get the CLI argument list from a hyperparam instance for a given current value', 'get the save directory key string from a hyperparam instance using its save_dir_key function', 'parse sweep CLI arguments including grid, prefix, num-trials, num-gpus, and environment flags', 'start a background process that monitors SLURM job tombstone files and cancels jobs', 'run the loop that watches for tombstone files and calls scancel on a SLURM job', 'create a scancel tombstone file to trigger cancellation of a running SLURM job', 'create a requeuehold tombstone file to trigger scontrol requeuehold on a SLURM job', 'review the list of SLURM job state codes used to validate job status']
```

Usage

```
{'run_tombstones_monitor': 'start a background process that monitors SLURM job tombstone files and cancels jobs', 'run_tombstones_procedure': 'run the loop that watches for tombstone files and calls scancel on a SLURM job', 'create_tombstone_scancel': 'create a scancel tombstone file to trigger cancellation of a running SLURM job', 'create_tombstone_requeuehold': 'create a requeuehold tombstone file to trigger scontrol requeuehold on a SLURM job', 'review_JOB_STATE_CODES': 'review the list of SLURM job state codes used to validate job status'}
```

