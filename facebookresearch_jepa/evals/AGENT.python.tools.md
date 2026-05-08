# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/evals/main.py

Prompts

```
['run a JEPA evaluation using a YAML config file across multiple GPUs', 'run a JEPA evaluation on a single GPU with the default configs.yaml file', 'run a JEPA evaluation across multiple GPUs by specifying device IDs like cuda:0 cuda:1', 'review the process_main function that loads config, initializes distributed GPUs, and launches evaluation', 'refactor the process_main function to support additional config loading formats beyond YAML', 'run distributed evaluation jobs on a SLURM cluster using YAML config files and submitit', 'launch evaluation jobs with parsed config dicts using submitit AutoExecutor on a SLURM partition', 'create a Trainer instance that wraps eval args and calls eval_main when invoked', 'review the Trainer checkpoint method that returns a DelayedSubmission for preemption recovery', 'run multiple evaluation configs from a batch YAML file as a SLURM job array']
```

Usage

```
{'run_evaluation': 'run a JEPA evaluation using a YAML config file across multiple GPUs', 'run_evaluation_single_gpu': 'run a JEPA evaluation on a single GPU with the default configs.yaml file', 'run_evaluation_multi_gpu': 'run a JEPA evaluation across multiple GPUs by specifying device IDs like cuda:0 cuda:1', 'review_process_main': 'review the process_main function that loads config, initializes distributed GPUs, and launches evaluation', 'refactor_process_main': 'refactor the process_main function to support additional config loading formats beyond YAML'}
```

## File: facebookresearch_jepa/evals/main_distributed.py

Prompts

```
['run a JEPA evaluation using a YAML config file across multiple GPUs', 'run a JEPA evaluation on a single GPU with the default configs.yaml file', 'run a JEPA evaluation across multiple GPUs by specifying device IDs like cuda:0 cuda:1', 'review the process_main function that loads config, initializes distributed GPUs, and launches evaluation', 'refactor the process_main function to support additional config loading formats beyond YAML', 'run distributed evaluation jobs on a SLURM cluster using YAML config files and submitit', 'launch evaluation jobs with parsed config dicts using submitit AutoExecutor on a SLURM partition', 'create a Trainer instance that wraps eval args and calls eval_main when invoked', 'review the Trainer checkpoint method that returns a DelayedSubmission for preemption recovery', 'run multiple evaluation configs from a batch YAML file as a SLURM job array']
```

Usage

```
{'run_distributed_evals': 'run distributed evaluation jobs on a SLURM cluster using YAML config files and submitit', 'launch_evals_with_parsed_args': 'launch evaluation jobs with parsed config dicts using submitit AutoExecutor on a SLURM partition', 'create_Trainer': 'create a Trainer instance that wraps eval args and calls eval_main when invoked', 'review_Trainer_checkpoint': 'review the Trainer checkpoint method that returns a DelayedSubmission for preemption recovery', 'run_batch_launch_evals': 'run multiple evaluation configs from a batch YAML file as a SLURM job array'}
```

