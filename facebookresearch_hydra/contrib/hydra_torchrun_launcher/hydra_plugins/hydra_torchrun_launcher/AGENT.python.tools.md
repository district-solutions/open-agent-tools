# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/contrib/hydra_torchrun_launcher/hydra_plugins/hydra_torchrun_launcher/_core.py

Prompts

```
['setup a TorchDistributedLauncher with Hydra context, task function, and LaunchConfig for distributed training', 'launch distributed jobs with job overrides using torchrun and return JobReturn results', 'run a wrapped task function inside distributed workers with Singleton state and env overrides', 'review the LaunchConfig setup with min_nodes, nproc_per_node, rdzv_backend, and start_method settings', 'refactor the launch function to handle sweep config overrides and job indexing for batch runs', 'review the TorchDistributedLauncher class that extends Hydra Launcher for torchrun distributed job launching', 'summarize the setup method that configures the launcher with hydra context, task function, and config', 'summarize the launch method that starts distributed jobs using job overrides and initial job index', 'refactor the TorchDistributedLauncher class to customize torchrun distributed launching behavior for Hydra jobs', 'test the TorchDistributedLauncher class setup and launch methods for Hydra torchrun distributed job execution']
```

Usage

```
{'setup_torchrun_launcher': 'setup a TorchDistributedLauncher with Hydra context, task function, and LaunchConfig for distributed training', 'launch_distributed_jobs': 'launch distributed jobs with job overrides using torchrun and return JobReturn results', 'run_wrapped_task_function': 'run a wrapped task function inside distributed workers with Singleton state and env overrides', 'review_launch_config': 'review the LaunchConfig setup with min_nodes, nproc_per_node, rdzv_backend, and start_method settings', 'refactor_launch_for_sweep': 'refactor the launch function to handle sweep config overrides and job indexing for batch runs'}
```

## File: facebookresearch_hydra/contrib/hydra_torchrun_launcher/hydra_plugins/hydra_torchrun_launcher/distributed_launcher.py

Prompts

```
['setup a TorchDistributedLauncher with Hydra context, task function, and LaunchConfig for distributed training', 'launch distributed jobs with job overrides using torchrun and return JobReturn results', 'run a wrapped task function inside distributed workers with Singleton state and env overrides', 'review the LaunchConfig setup with min_nodes, nproc_per_node, rdzv_backend, and start_method settings', 'refactor the launch function to handle sweep config overrides and job indexing for batch runs', 'review the TorchDistributedLauncher class that extends Hydra Launcher for torchrun distributed job launching', 'summarize the setup method that configures the launcher with hydra context, task function, and config', 'summarize the launch method that starts distributed jobs using job overrides and initial job index', 'refactor the TorchDistributedLauncher class to customize torchrun distributed launching behavior for Hydra jobs', 'test the TorchDistributedLauncher class setup and launch methods for Hydra torchrun distributed job execution']
```

Usage

```
{'review_TorchDistributedLauncher': 'review the TorchDistributedLauncher class that extends Hydra Launcher for torchrun distributed job launching', 'summarize_TorchDistributedLauncher_setup': 'summarize the setup method that configures the launcher with hydra context, task function, and config', 'summarize_TorchDistributedLauncher_launch': 'summarize the launch method that starts distributed jobs using job overrides and initial job index', 'refactor_TorchDistributedLauncher': 'refactor the TorchDistributedLauncher class to customize torchrun distributed launching behavior for Hydra jobs', 'test_TorchDistributedLauncher': 'test the TorchDistributedLauncher class setup and launch methods for Hydra torchrun distributed job execution'}
```

