# Agent Python Tools

- repo: facebookresearch/motif
- repo_uri: https://github.com/facebookresearch/motif

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/runner/run.py

Prompts

```
['run a reinforcement learning experiment by specifying a run module name and GPU count via CLI', 'run a reinforcement learning experiment on a SLURM cluster by setting the runner to slurm', 'run multiple parallel RL experiments across GPUs with a configurable maximum parallel limit', 'review the runner_argparser function to understand CLI arguments for configuring RL experiment runs', 'summarize the main function that dynamically imports run modules and dispatches to process or SLURM runners', 'create a ParamList to yield randomized parameter combinations from a given list', 'build a ParamGrid to recursively generate all parameter combinations for grid search', 'create an Experiment to yield command strings and names from parameter dicts', 'build a RunDescription to yield final experiment commands with train and root dirs', 'review the ParamGenerator base class and its generate_params generator interface', 'run multiple RL experiments in parallel with GPU scheduling and max parallel process limits', 'run a hyperparameter sweep across many experiment configurations using the run function', 'run experiments balanced across GPUs by setting experiments_per_gpu to distribute load evenly', 'run experiments with custom environment variables passed via exp_env_vars in the run description', 'run experiments with a configurable pause_between delay to stagger process startup timing', 'run multiple RL experiments on a SLURM cluster by submitting sbatch jobs with GPU resources', 'add SLURM-specific CLI arguments like GPUs per job and CPUs per GPU to an argparse parser', 'generate sbatch shell scripts from experiment commands using the SBATCH_TEMPLATE for hyperparameter sweeps', 'submit sbatch scripts to the SLURM scheduler and collect job IDs for monitoring and cancellation', 'cancel running SLURM jobs by generating and writing an scancel command script to the workdir']
```

Usage

```
{'run_rl_experiment': 'run a reinforcement learning experiment by specifying a run module name and GPU count via CLI', 'run_experiment_on_slurm': 'run a reinforcement learning experiment on a SLURM cluster by setting the runner to slurm', 'run_parallel_experiments': 'run multiple parallel RL experiments across GPUs with a configurable maximum parallel limit', 'review_runner_argparser': 'review the runner_argparser function to understand CLI arguments for configuring RL experiment runs', 'summarize_main': 'summarize the main function that dynamically imports run modules and dispatches to process or SLURM runners'}
```

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/runner/run_description.py

Prompts

```
['run a reinforcement learning experiment by specifying a run module name and GPU count via CLI', 'run a reinforcement learning experiment on a SLURM cluster by setting the runner to slurm', 'run multiple parallel RL experiments across GPUs with a configurable maximum parallel limit', 'review the runner_argparser function to understand CLI arguments for configuring RL experiment runs', 'summarize the main function that dynamically imports run modules and dispatches to process or SLURM runners', 'create a ParamList to yield randomized parameter combinations from a given list', 'build a ParamGrid to recursively generate all parameter combinations for grid search', 'create an Experiment to yield command strings and names from parameter dicts', 'build a RunDescription to yield final experiment commands with train and root dirs', 'review the ParamGenerator base class and its generate_params generator interface', 'run multiple RL experiments in parallel with GPU scheduling and max parallel process limits', 'run a hyperparameter sweep across many experiment configurations using the run function', 'run experiments balanced across GPUs by setting experiments_per_gpu to distribute load evenly', 'run experiments with custom environment variables passed via exp_env_vars in the run description', 'run experiments with a configurable pause_between delay to stagger process startup timing', 'run multiple RL experiments on a SLURM cluster by submitting sbatch jobs with GPU resources', 'add SLURM-specific CLI arguments like GPUs per job and CPUs per GPU to an argparse parser', 'generate sbatch shell scripts from experiment commands using the SBATCH_TEMPLATE for hyperparameter sweeps', 'submit sbatch scripts to the SLURM scheduler and collect job IDs for monitoring and cancellation', 'cancel running SLURM jobs by generating and writing an scancel command script to the workdir']
```

Usage

```
{'generate_param_list_combinations': 'create a ParamList to yield randomized parameter combinations from a given list', 'generate_param_grid_combinations': 'build a ParamGrid to recursively generate all parameter combinations for grid search', 'generate_experiment_commands': 'create an Experiment to yield command strings and names from parameter dicts', 'generate_run_experiments': 'build a RunDescription to yield final experiment commands with train and root dirs', 'review_paramgenerator_base_class': 'review the ParamGenerator base class and its generate_params generator interface'}
```

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/runner/run_processes.py

Prompts

```
['run a reinforcement learning experiment by specifying a run module name and GPU count via CLI', 'run a reinforcement learning experiment on a SLURM cluster by setting the runner to slurm', 'run multiple parallel RL experiments across GPUs with a configurable maximum parallel limit', 'review the runner_argparser function to understand CLI arguments for configuring RL experiment runs', 'summarize the main function that dynamically imports run modules and dispatches to process or SLURM runners', 'create a ParamList to yield randomized parameter combinations from a given list', 'build a ParamGrid to recursively generate all parameter combinations for grid search', 'create an Experiment to yield command strings and names from parameter dicts', 'build a RunDescription to yield final experiment commands with train and root dirs', 'review the ParamGenerator base class and its generate_params generator interface', 'run multiple RL experiments in parallel with GPU scheduling and max parallel process limits', 'run a hyperparameter sweep across many experiment configurations using the run function', 'run experiments balanced across GPUs by setting experiments_per_gpu to distribute load evenly', 'run experiments with custom environment variables passed via exp_env_vars in the run description', 'run experiments with a configurable pause_between delay to stagger process startup timing', 'run multiple RL experiments on a SLURM cluster by submitting sbatch jobs with GPU resources', 'add SLURM-specific CLI arguments like GPUs per job and CPUs per GPU to an argparse parser', 'generate sbatch shell scripts from experiment commands using the SBATCH_TEMPLATE for hyperparameter sweeps', 'submit sbatch scripts to the SLURM scheduler and collect job IDs for monitoring and cancellation', 'cancel running SLURM jobs by generating and writing an scancel command script to the workdir']
```

Usage

```
{'run_experiments': 'run multiple RL experiments in parallel with GPU scheduling and max parallel process limits', 'run_hyperparameter_sweep': 'run a hyperparameter sweep across many experiment configurations using the run function', 'run_gpu_balanced': 'run experiments balanced across GPUs by setting experiments_per_gpu to distribute load evenly', 'run_with_env_vars': 'run experiments with custom environment variables passed via exp_env_vars in the run description', 'run_with_pause': 'run experiments with a configurable pause_between delay to stagger process startup timing'}
```

## File: facebookresearch_motif/rl_baseline/sample-factory/sample_factory/runner/run_slurm.py

Prompts

```
['run a reinforcement learning experiment by specifying a run module name and GPU count via CLI', 'run a reinforcement learning experiment on a SLURM cluster by setting the runner to slurm', 'run multiple parallel RL experiments across GPUs with a configurable maximum parallel limit', 'review the runner_argparser function to understand CLI arguments for configuring RL experiment runs', 'summarize the main function that dynamically imports run modules and dispatches to process or SLURM runners', 'create a ParamList to yield randomized parameter combinations from a given list', 'build a ParamGrid to recursively generate all parameter combinations for grid search', 'create an Experiment to yield command strings and names from parameter dicts', 'build a RunDescription to yield final experiment commands with train and root dirs', 'review the ParamGenerator base class and its generate_params generator interface', 'run multiple RL experiments in parallel with GPU scheduling and max parallel process limits', 'run a hyperparameter sweep across many experiment configurations using the run function', 'run experiments balanced across GPUs by setting experiments_per_gpu to distribute load evenly', 'run experiments with custom environment variables passed via exp_env_vars in the run description', 'run experiments with a configurable pause_between delay to stagger process startup timing', 'run multiple RL experiments on a SLURM cluster by submitting sbatch jobs with GPU resources', 'add SLURM-specific CLI arguments like GPUs per job and CPUs per GPU to an argparse parser', 'generate sbatch shell scripts from experiment commands using the SBATCH_TEMPLATE for hyperparameter sweeps', 'submit sbatch scripts to the SLURM scheduler and collect job IDs for monitoring and cancellation', 'cancel running SLURM jobs by generating and writing an scancel command script to the workdir']
```

Usage

```
{'run_slurm_experiments': 'run multiple RL experiments on a SLURM cluster by submitting sbatch jobs with GPU resources', 'add_slurm_args_parser': 'add SLURM-specific CLI arguments like GPUs per job and CPUs per GPU to an argparse parser', 'generate_sbatch_scripts': 'generate sbatch shell scripts from experiment commands using the SBATCH_TEMPLATE for hyperparameter sweeps', 'submit_slurm_jobs': 'submit sbatch scripts to the SLURM scheduler and collect job IDs for monitoring and cancellation', 'cancel_slurm_jobs': 'cancel running SLURM jobs by generating and writing an scancel command script to the workdir'}
```

