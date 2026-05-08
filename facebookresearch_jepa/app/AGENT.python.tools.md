# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/app/main.py

Prompts

```
['run the JEPA training pipeline by spawning one process per GPU device using a YAML config file', 'run the per-process entry point that loads a config, initializes distributed training, and launches the app scaffold', 'run multi-GPU training by passing a list of CUDA devices via the --devices argument', 'run the JEPA app using a custom YAML config file specified with the --fname argument', 'review the process_main function that handles CUDA device assignment, config loading, and distributed init', 'run distributed JEPA training jobs on a SLURM cluster using submitit with yaml config files', 'batch launch multiple training configs from a yaml list file using the --batch-launch flag', 'run a single training job by passing a yaml config file path with the --fname argument', 'review the Trainer class that wraps pretraining params and launches the app via app_main', 'review the launch_app_with_parsed_args function that creates a submitit AutoExecutor and batch submits Trainer jobs']
```

Usage

```
{'run_jepa_training': 'run the JEPA training pipeline by spawning one process per GPU device using a YAML config file', 'run_process_main': 'run the per-process entry point that loads a config, initializes distributed training, and launches the app scaffold', 'run_multi_gpu': 'run multi-GPU training by passing a list of CUDA devices via the --devices argument', 'run_with_config': 'run the JEPA app using a custom YAML config file specified with the --fname argument', 'review_process_main': 'review the process_main function that handles CUDA device assignment, config loading, and distributed init'}
```

## File: facebookresearch_jepa/app/main_distributed.py

Prompts

```
['run the JEPA training pipeline by spawning one process per GPU device using a YAML config file', 'run the per-process entry point that loads a config, initializes distributed training, and launches the app scaffold', 'run multi-GPU training by passing a list of CUDA devices via the --devices argument', 'run the JEPA app using a custom YAML config file specified with the --fname argument', 'review the process_main function that handles CUDA device assignment, config loading, and distributed init', 'run distributed JEPA training jobs on a SLURM cluster using submitit with yaml config files', 'batch launch multiple training configs from a yaml list file using the --batch-launch flag', 'run a single training job by passing a yaml config file path with the --fname argument', 'review the Trainer class that wraps pretraining params and launches the app via app_main', 'review the launch_app_with_parsed_args function that creates a submitit AutoExecutor and batch submits Trainer jobs']
```

Usage

```
{'run_distributed_training': 'run distributed JEPA training jobs on a SLURM cluster using submitit with yaml config files', 'run_batch_launch': 'batch launch multiple training configs from a yaml list file using the --batch-launch flag', 'run_single_config': 'run a single training job by passing a yaml config file path with the --fname argument', 'review_Trainer_class': 'review the Trainer class that wraps pretraining params and launches the app via app_main', 'review_launch_app_with_parsed_args': 'review the launch_app_with_parsed_args function that creates a submitit AutoExecutor and batch submits Trainer jobs'}
```

