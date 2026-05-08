# Agent Python Tools

- repo: facebookresearch/jepa-intuitive-physics
- repo_uri: https://github.com/facebookresearch/jepa-intuitive-physics

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/evals/main.py

Prompts

```
['run a multi-GPU evaluation by spawning processes across specified CUDA devices using a YAML config file', 'run a single-process debug evaluation on cuda:0 without spawning new multiprocessing workers', 'run the process_main function to load a YAML config, init distributed, and launch an eval', 'run an evaluation by providing a config file path with --fname and device list with --devices', 'run init_distributed to set up inter-GPU communication within a single machine using rank and world_size', 'run distributed evaluation jobs on a SLURM cluster using YAML config files and submitit', 'launch evaluation jobs with parsed config args using submitit AutoExecutor on SLURM', 'create a Trainer instance that wraps eval arguments and calls eval_main when invoked', 'checkpoint a Trainer to resume preempted jobs using submitit DelayedSubmission', 'review the launch_evals function that parses YAML configs and submits batch jobs to SLURM']
```

Usage

```
{'run_evaluation_multi_gpu': 'run a multi-GPU evaluation by spawning processes across specified CUDA devices using a YAML config file', 'run_evaluation_debug': 'run a single-process debug evaluation on cuda:0 without spawning new multiprocessing workers', 'run_process_main': 'run the process_main function to load a YAML config, init distributed, and launch an eval', 'run_eval_with_config': 'run an evaluation by providing a config file path with --fname and device list with --devices', 'run_init_distributed': 'run init_distributed to set up inter-GPU communication within a single machine using rank and world_size'}
```

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/evals/main_distributed.py

Prompts

```
['run a multi-GPU evaluation by spawning processes across specified CUDA devices using a YAML config file', 'run a single-process debug evaluation on cuda:0 without spawning new multiprocessing workers', 'run the process_main function to load a YAML config, init distributed, and launch an eval', 'run an evaluation by providing a config file path with --fname and device list with --devices', 'run init_distributed to set up inter-GPU communication within a single machine using rank and world_size', 'run distributed evaluation jobs on a SLURM cluster using YAML config files and submitit', 'launch evaluation jobs with parsed config args using submitit AutoExecutor on SLURM', 'create a Trainer instance that wraps eval arguments and calls eval_main when invoked', 'checkpoint a Trainer to resume preempted jobs using submitit DelayedSubmission', 'review the launch_evals function that parses YAML configs and submits batch jobs to SLURM']
```

Usage

```
{'run_distributed_evals': 'run distributed evaluation jobs on a SLURM cluster using YAML config files and submitit', 'launch_evals_with_parsed_args': 'launch evaluation jobs with parsed config args using submitit AutoExecutor on SLURM', 'create_Trainer': 'create a Trainer instance that wraps eval arguments and calls eval_main when invoked', 'checkpoint_Trainer': 'checkpoint a Trainer to resume preempted jobs using submitit DelayedSubmission', 'review_launch_evals': 'review the launch_evals function that parses YAML configs and submits batch jobs to SLURM'}
```

