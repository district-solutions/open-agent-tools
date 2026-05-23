# Agent Python Tools

- repo: facebookresearch/phyre
- repo_uri: https://github.com/facebookresearch/phyre

## File: facebookresearch_phyre/scripts/offline_simulation/compress_partial_simuations.py

Prompts

```
['run the script to compress partial PHYRE simulation cache files into consolidated cache files', 'run main_tier to compress simulation data for a specific action tier like ball or two_balls', 'run main to compress all partial simulations across tiers using a specified number of actions', 'review main_tier which loads partial simulation files per task and dumps a consolidated cache', 'review main which groups tasks by action tier and delegates compression to main_tier', 'run a multiprocessing simulation for a PHYRE task and save action statuses to a cache file', 'run a worker process that simulates a subset of actions for a given PHYRE task and returns statuses', 'get the SLURM job ID from environment variables for array or standard jobs', 'get a task ID from a file using the SLURM array task index', 'install signal handlers for SLURM time limit and preemption events to requeue jobs']
```

Usage

```
{'run_compress_partial_simulations': 'run the script to compress partial PHYRE simulation cache files into consolidated cache files', 'run_main_tier': 'run main_tier to compress simulation data for a specific action tier like ball or two_balls', 'run_main': 'run main to compress all partial simulations across tiers using a specified number of actions', 'review_main_tier': 'review main_tier which loads partial simulation files per task and dumps a consolidated cache', 'review_main': 'review main which groups tasks by action tier and delegates compression to main_tier'}
```

## File: facebookresearch_phyre/scripts/offline_simulation/save_partial_simulation.py

Prompts

```
['run the script to compress partial PHYRE simulation cache files into consolidated cache files', 'run main_tier to compress simulation data for a specific action tier like ball or two_balls', 'run main to compress all partial simulations across tiers using a specified number of actions', 'review main_tier which loads partial simulation files per task and dumps a consolidated cache', 'review main which groups tasks by action tier and delegates compression to main_tier', 'run a multiprocessing simulation for a PHYRE task and save action statuses to a cache file', 'run a worker process that simulates a subset of actions for a given PHYRE task and returns statuses', 'get the SLURM job ID from environment variables for array or standard jobs', 'get a task ID from a file using the SLURM array task index', 'install signal handlers for SLURM time limit and preemption events to requeue jobs']
```

Usage

```
{'run_partial_simulation': 'run a multiprocessing simulation for a PHYRE task and save action statuses to a cache file', 'run_worker_simulation': 'run a worker process that simulates a subset of actions for a given PHYRE task and returns statuses', 'get_slurm_job_id': 'get the SLURM job ID from environment variables for array or standard jobs', 'get_task_id_from_slurm': 'get a task ID from a file using the SLURM array task index', 'init_signal_handler': 'install signal handlers for SLURM time limit and preemption events to requeue jobs'}
```

