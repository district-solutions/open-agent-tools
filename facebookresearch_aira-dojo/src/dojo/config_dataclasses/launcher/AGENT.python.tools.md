# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/launcher/base.py

Prompts

```
['create a LauncherConfig dataclass instance to configure job submission and monitoring behavior', 'configure LauncherConfig to set await_completion to False for non-blocking job submission', 'configure LauncherConfig to enable debug mode so commands are printed instead of submitted', 'configure LauncherConfig to disable job monitoring by setting monitor_jobs to False', 'review the LauncherConfig validate method to ensure it calls the parent BaseConfig validate', 'create a SlurmConfig dataclass instance to configure SLURM job submission with account, partition, and resource settings', 'configure SlurmConfig to set nodes, gpus_per_node, and cpus_per_task for multi-node GPU job allocation', 'configure SlurmConfig to set time limit and memory allocation per node for SLURM jobs', 'configure SlurmConfig to set array_parallelism for running multiple parallel SLURM array jobs', 'review the SlurmConfig validate method to ensure it calls the parent LauncherConfig validate']
```

Usage

```
{'create_LauncherConfig': 'create a LauncherConfig dataclass instance to configure job submission and monitoring behavior', 'configure_LauncherConfig_await_completion': 'configure LauncherConfig to set await_completion to False for non-blocking job submission', 'configure_LauncherConfig_debug': 'configure LauncherConfig to enable debug mode so commands are printed instead of submitted', 'configure_LauncherConfig_monitor_jobs': 'configure LauncherConfig to disable job monitoring by setting monitor_jobs to False', 'review_LauncherConfig_validate': 'review the LauncherConfig validate method to ensure it calls the parent BaseConfig validate'}
```

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/launcher/slurm.py

Prompts

```
['create a LauncherConfig dataclass instance to configure job submission and monitoring behavior', 'configure LauncherConfig to set await_completion to False for non-blocking job submission', 'configure LauncherConfig to enable debug mode so commands are printed instead of submitted', 'configure LauncherConfig to disable job monitoring by setting monitor_jobs to False', 'review the LauncherConfig validate method to ensure it calls the parent BaseConfig validate', 'create a SlurmConfig dataclass instance to configure SLURM job submission with account, partition, and resource settings', 'configure SlurmConfig to set nodes, gpus_per_node, and cpus_per_task for multi-node GPU job allocation', 'configure SlurmConfig to set time limit and memory allocation per node for SLURM jobs', 'configure SlurmConfig to set array_parallelism for running multiple parallel SLURM array jobs', 'review the SlurmConfig validate method to ensure it calls the parent LauncherConfig validate']
```

Usage

```
{'create_SlurmConfig': 'create a SlurmConfig dataclass instance to configure SLURM job submission with account, partition, and resource settings', 'configure_SlurmConfig_resources': 'configure SlurmConfig to set nodes, gpus_per_node, and cpus_per_task for multi-node GPU job allocation', 'configure_SlurmConfig_runtime': 'configure SlurmConfig to set time limit and memory allocation per node for SLURM jobs', 'configure_SlurmConfig_array_parallelism': 'configure SlurmConfig to set array_parallelism for running multiple parallel SLURM array jobs', 'review_SlurmConfig_validate': 'review the SlurmConfig validate method to ensure it calls the parent LauncherConfig validate'}
```

