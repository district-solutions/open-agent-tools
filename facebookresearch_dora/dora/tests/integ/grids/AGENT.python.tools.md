# Agent Python Tools

- repo: facebookresearch/dora
- repo_uri: https://github.com/facebookresearch/dora

## File: facebookresearch_dora/dora/tests/integ/grids/test.py

Prompts

```
['run a DORA grid search explorer that launches experiments with varying hyperparameters using the launcher', 'create a custom Explorer subclass that overrides get_grid_metrics to return loss as a grid metric', 'launch a grid of experiments by calling the launcher with different parameter values in a loop', 'bind default parameters to the launcher so all subsequent calls inherit those parameter values', 'schedule a SLURM job array of experiments using launcher.job_array context manager with slurm config']
```

Usage

```
{'run_grid_search_explorer': 'run a DORA grid search explorer that launches experiments with varying hyperparameters using the launcher', 'create_custom_explorer_class': 'create a custom Explorer subclass that overrides get_grid_metrics to return loss as a grid metric', 'launch_experiment_grid': 'launch a grid of experiments by calling the launcher with different parameter values in a loop', 'bind_launcher_parameters': 'bind default parameters to the launcher so all subsequent calls inherit those parameter values', 'schedule_slurm_job_array': 'schedule a SLURM job array of experiments using launcher.job_array context manager with slurm config'}
```

