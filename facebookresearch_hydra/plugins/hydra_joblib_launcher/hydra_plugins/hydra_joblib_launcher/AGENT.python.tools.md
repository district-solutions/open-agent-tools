# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_joblib_launcher/hydra_plugins/hydra_joblib_launcher/_core.py

Prompts

```
['run multiple Hydra sweep jobs in parallel using joblib with the loky backend', 'execute a single Hydra job with overrides and return the JobReturn result', 'process a joblib config dict and convert pre_dispatch, batch_size, and max_nbytes to integers', 'review the launch function that orchestrates parallel Hydra job execution via joblib Parallel', 'refactor the execute_job function to customize sweep config job id and num assignment', 'review the JoblibLauncher class that extends Hydra Launcher to run parallel jobs via Joblib', 'run the JoblibLauncher launch method to execute sweep jobs in parallel using Joblib.Parallel', 'configure the JobLibLauncherConf dataclass with n_jobs, backend, verbose, and timeout settings for parallel sweeps', 'test the execute_job function that runs a single Hydra sweep job with overrides in a parallel worker', 'refactor the process_joblib_cfg function to convert string config values to integers for joblib parameters']
```

Usage

```
{'run_parallel_hydra_jobs': 'run multiple Hydra sweep jobs in parallel using joblib with the loky backend', 'execute_single_hydra_job': 'execute a single Hydra job with overrides and return the JobReturn result', 'process_joblib_config': 'process a joblib config dict and convert pre_dispatch, batch_size, and max_nbytes to integers', 'review_launch_function': 'review the launch function that orchestrates parallel Hydra job execution via joblib Parallel', 'refactor_execute_job': 'refactor the execute_job function to customize sweep config job id and num assignment'}
```

## File: facebookresearch_hydra/plugins/hydra_joblib_launcher/hydra_plugins/hydra_joblib_launcher/joblib_launcher.py

Prompts

```
['run multiple Hydra sweep jobs in parallel using joblib with the loky backend', 'execute a single Hydra job with overrides and return the JobReturn result', 'process a joblib config dict and convert pre_dispatch, batch_size, and max_nbytes to integers', 'review the launch function that orchestrates parallel Hydra job execution via joblib Parallel', 'refactor the execute_job function to customize sweep config job id and num assignment', 'review the JoblibLauncher class that extends Hydra Launcher to run parallel jobs via Joblib', 'run the JoblibLauncher launch method to execute sweep jobs in parallel using Joblib.Parallel', 'configure the JobLibLauncherConf dataclass with n_jobs, backend, verbose, and timeout settings for parallel sweeps', 'test the execute_job function that runs a single Hydra sweep job with overrides in a parallel worker', 'refactor the process_joblib_cfg function to convert string config values to integers for joblib parameters']
```

Usage

```
{'review_JoblibLauncher_class': 'review the JoblibLauncher class that extends Hydra Launcher to run parallel jobs via Joblib', 'run_JoblibLauncher_launch': 'run the JoblibLauncher launch method to execute sweep jobs in parallel using Joblib.Parallel', 'configure_JobLibLauncherConf': 'configure the JobLibLauncherConf dataclass with n_jobs, backend, verbose, and timeout settings for parallel sweeps', 'test_execute_job': 'test the execute_job function that runs a single Hydra sweep job with overrides in a parallel worker', 'refactor_process_joblib_cfg': 'refactor the process_joblib_cfg function to convert string config values to integers for joblib parameters'}
```

