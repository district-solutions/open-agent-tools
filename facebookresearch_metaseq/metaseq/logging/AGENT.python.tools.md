# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/logging/meters.py

Prompts

```
['create an AverageMeter to track and compute the running average of updated values with optional rounding', 'create a TimeMeter to compute the average rate of events per second since initialization', 'create a StopwatchMeter to measure the sum and average duration of timed events using start and stop', 'create a MetersDict to manage a priority-sorted collection of Meter instances with state serialization support', 'use safe_round to round numbers, PyTorch tensors, or NumPy scalars to a specified number of decimal places', 'use the aggregate context manager to create a named aggregation scope for logging metrics', 'call log_scalar to record a weighted scalar value like loss under the active aggregation context', 'call log_speed to record the rate of a quantity per second under the active aggregation context', 'call get_smoothed_values to retrieve all smoothed metric values aggregated under a given name', 'call nvidia_smi_gpu_memory_stats to parse nvidia-smi output and return GPU memory usage in GB']
```

Usage

```
{'create_average_meter': 'create an AverageMeter to track and compute the running average of updated values with optional rounding', 'create_time_meter': 'create a TimeMeter to compute the average rate of events per second since initialization', 'create_stopwatch_meter': 'create a StopwatchMeter to measure the sum and average duration of timed events using start and stop', 'create_meters_dict': 'create a MetersDict to manage a priority-sorted collection of Meter instances with state serialization support', 'use_safe_round': 'use safe_round to round numbers, PyTorch tensors, or NumPy scalars to a specified number of decimal places'}
```

## File: facebookresearch_metaseq/metaseq/logging/metrics.py

Prompts

```
['create an AverageMeter to track and compute the running average of updated values with optional rounding', 'create a TimeMeter to compute the average rate of events per second since initialization', 'create a StopwatchMeter to measure the sum and average duration of timed events using start and stop', 'create a MetersDict to manage a priority-sorted collection of Meter instances with state serialization support', 'use safe_round to round numbers, PyTorch tensors, or NumPy scalars to a specified number of decimal places', 'use the aggregate context manager to create a named aggregation scope for logging metrics', 'call log_scalar to record a weighted scalar value like loss under the active aggregation context', 'call log_speed to record the rate of a quantity per second under the active aggregation context', 'call get_smoothed_values to retrieve all smoothed metric values aggregated under a given name', 'call nvidia_smi_gpu_memory_stats to parse nvidia-smi output and return GPU memory usage in GB']
```

Usage

```
{'aggregate_metrics': 'use the aggregate context manager to create a named aggregation scope for logging metrics', 'log_scalar_values': 'call log_scalar to record a weighted scalar value like loss under the active aggregation context', 'log_speed_rate': 'call log_speed to record the rate of a quantity per second under the active aggregation context', 'get_smoothed_values': 'call get_smoothed_values to retrieve all smoothed metric values aggregated under a given name', 'query_gpu_memory': 'call nvidia_smi_gpu_memory_stats to parse nvidia-smi output and return GPU memory usage in GB'}
```

