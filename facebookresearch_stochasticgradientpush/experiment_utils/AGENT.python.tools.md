# Agent Python Tools

- repo: facebookresearch/stochasticgradientpush
- repo_uri: https://github.com/facebookresearch/stochastic_gradient_push

## File: facebookresearch_stochasticgradientpush/experiment_utils/cluster_manager.py

Prompts

```
['create a ClusterManager instance to handle SLURM job preemption and checkpointing for distributed training', 'save a model checkpoint to disk with optional epoch id and automatic best model tracking', 'set the global checkpoint directory path for all ClusterManager instances before initialization', 'install SIGUSR1 and SIGTERM signal handlers to manage job preemption and graceful termination', 'handle the SIGUSR1 signal by setting a flag and triggering a callback for job relaunch', 'create a Python logger for a given rank with configurable verbose logging to stdout', 'get the active network interface name for ethernet or infiniband by querying system interfaces', 'review the make_logger function to understand how it creates rank-aware loggers with stream handlers', 'review the get_tcp_interface_name function to understand how it detects active network interfaces', 'summarize the helpers module utility functions for logging setup and network interface detection', 'create a Meter instance with a custom print tag to track benchmark timing values', 'update a Meter with new values and optional count to compute running average and standard deviation', 'reset a Meter to clear all accumulated values including average, sum, count, and standard deviation', 'format a Meter as a CSV string showing current value, average, and standard deviation or MAD', 'create a stateful Meter that tracks value history and computes mean absolute deviation over time']
```

Usage

```
{'create_cluster_manager': 'create a ClusterManager instance to handle SLURM job preemption and checkpointing for distributed training', 'save_checkpoint': 'save a model checkpoint to disk with optional epoch id and automatic best model tracking', 'set_checkpoint_dir': 'set the global checkpoint directory path for all ClusterManager instances before initialization', 'install_signal_handlers': 'install SIGUSR1 and SIGTERM signal handlers to manage job preemption and graceful termination', 'handle_sigusr1_signal': 'handle the SIGUSR1 signal by setting a flag and triggering a callback for job relaunch'}
```

## File: facebookresearch_stochasticgradientpush/experiment_utils/helpers.py

Prompts

```
['create a ClusterManager instance to handle SLURM job preemption and checkpointing for distributed training', 'save a model checkpoint to disk with optional epoch id and automatic best model tracking', 'set the global checkpoint directory path for all ClusterManager instances before initialization', 'install SIGUSR1 and SIGTERM signal handlers to manage job preemption and graceful termination', 'handle the SIGUSR1 signal by setting a flag and triggering a callback for job relaunch', 'create a Python logger for a given rank with configurable verbose logging to stdout', 'get the active network interface name for ethernet or infiniband by querying system interfaces', 'review the make_logger function to understand how it creates rank-aware loggers with stream handlers', 'review the get_tcp_interface_name function to understand how it detects active network interfaces', 'summarize the helpers module utility functions for logging setup and network interface detection', 'create a Meter instance with a custom print tag to track benchmark timing values', 'update a Meter with new values and optional count to compute running average and standard deviation', 'reset a Meter to clear all accumulated values including average, sum, count, and standard deviation', 'format a Meter as a CSV string showing current value, average, and standard deviation or MAD', 'create a stateful Meter that tracks value history and computes mean absolute deviation over time']
```

Usage

```
{'make_logger': 'create a Python logger for a given rank with configurable verbose logging to stdout', 'get_tcp_interface_name': 'get the active network interface name for ethernet or infiniband by querying system interfaces', 'review_make_logger': 'review the make_logger function to understand how it creates rank-aware loggers with stream handlers', 'review_get_tcp_interface_name': 'review the get_tcp_interface_name function to understand how it detects active network interfaces', 'summarize_helpers_module': 'summarize the helpers module utility functions for logging setup and network interface detection'}
```

## File: facebookresearch_stochasticgradientpush/experiment_utils/metering.py

Prompts

```
['create a ClusterManager instance to handle SLURM job preemption and checkpointing for distributed training', 'save a model checkpoint to disk with optional epoch id and automatic best model tracking', 'set the global checkpoint directory path for all ClusterManager instances before initialization', 'install SIGUSR1 and SIGTERM signal handlers to manage job preemption and graceful termination', 'handle the SIGUSR1 signal by setting a flag and triggering a callback for job relaunch', 'create a Python logger for a given rank with configurable verbose logging to stdout', 'get the active network interface name for ethernet or infiniband by querying system interfaces', 'review the make_logger function to understand how it creates rank-aware loggers with stream handlers', 'review the get_tcp_interface_name function to understand how it detects active network interfaces', 'summarize the helpers module utility functions for logging setup and network interface detection', 'create a Meter instance with a custom print tag to track benchmark timing values', 'update a Meter with new values and optional count to compute running average and standard deviation', 'reset a Meter to clear all accumulated values including average, sum, count, and standard deviation', 'format a Meter as a CSV string showing current value, average, and standard deviation or MAD', 'create a stateful Meter that tracks value history and computes mean absolute deviation over time']
```

Usage

```
{'create_Meter_instance': 'create a Meter instance with a custom print tag to track benchmark timing values', 'update_Meter_values': 'update a Meter with new values and optional count to compute running average and standard deviation', 'reset_Meter_state': 'reset a Meter to clear all accumulated values including average, sum, count, and standard deviation', 'format_Meter_csv_output': 'format a Meter as a CSV string showing current value, average, and standard deviation or MAD', 'create_stateful_Meter': 'create a stateful Meter that tracks value history and computes mean absolute deviation over time'}
```

