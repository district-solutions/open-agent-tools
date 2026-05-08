# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/logging/meters.py

Prompts

```
['create an AverageMeter to track and compute running averages of updated values', 'create a TimeMeter to compute the average occurrence rate of events per second', 'create a StopwatchMeter to measure the sum and average duration of timed events', 'create a MetersDict to manage a priority-sorted collection of Meter instances', 'use safe_round to round numbers, torch tensors, or numpy scalars to N decimal places', 'create a named aggregation context to collect and aggregate metrics during training or validation', 'log a scalar value like loss or accuracy into all active metrics aggregators with optional weight', 'log a derived metric computed from other meters using a callable function', 'log the rate of a quantity per second using a time-based meter for throughput tracking', 'get all smoothed metric values aggregated under a given name like train or valid', 'build a tqdm progress bar wrapper around an iterator with epoch and prefix logging', 'build a JSON format progress bar that logs stats at configurable intervals during iteration', 'create a TensorBoard progress bar wrapper that logs scalar metrics to a log directory', 'create a Weights and Biases progress bar wrapper that logs training stats to a W&B project', 'refactor the format_stat function to convert AverageMeter, TimeMeter, and tensor stats to strings']
```

Usage

```
{'create_average_meter': 'create an AverageMeter to track and compute running averages of updated values', 'create_time_meter': 'create a TimeMeter to compute the average occurrence rate of events per second', 'create_stopwatch_meter': 'create a StopwatchMeter to measure the sum and average duration of timed events', 'create_meters_dict': 'create a MetersDict to manage a priority-sorted collection of Meter instances', 'use_safe_round': 'use safe_round to round numbers, torch tensors, or numpy scalars to N decimal places'}
```

## File: facebookresearch_mega/fairseq/logging/metrics.py

Prompts

```
['create an AverageMeter to track and compute running averages of updated values', 'create a TimeMeter to compute the average occurrence rate of events per second', 'create a StopwatchMeter to measure the sum and average duration of timed events', 'create a MetersDict to manage a priority-sorted collection of Meter instances', 'use safe_round to round numbers, torch tensors, or numpy scalars to N decimal places', 'create a named aggregation context to collect and aggregate metrics during training or validation', 'log a scalar value like loss or accuracy into all active metrics aggregators with optional weight', 'log a derived metric computed from other meters using a callable function', 'log the rate of a quantity per second using a time-based meter for throughput tracking', 'get all smoothed metric values aggregated under a given name like train or valid', 'build a tqdm progress bar wrapper around an iterator with epoch and prefix logging', 'build a JSON format progress bar that logs stats at configurable intervals during iteration', 'create a TensorBoard progress bar wrapper that logs scalar metrics to a log directory', 'create a Weights and Biases progress bar wrapper that logs training stats to a W&B project', 'refactor the format_stat function to convert AverageMeter, TimeMeter, and tensor stats to strings']
```

Usage

```
{'create_aggregate_context': 'create a named aggregation context to collect and aggregate metrics during training or validation', 'log_scalar_values': 'log a scalar value like loss or accuracy into all active metrics aggregators with optional weight', 'log_derived_metric': 'log a derived metric computed from other meters using a callable function', 'log_speed_meter': 'log the rate of a quantity per second using a time-based meter for throughput tracking', 'get_smoothed_values': 'get all smoothed metric values aggregated under a given name like train or valid'}
```

## File: facebookresearch_mega/fairseq/logging/progress_bar.py

Prompts

```
['create an AverageMeter to track and compute running averages of updated values', 'create a TimeMeter to compute the average occurrence rate of events per second', 'create a StopwatchMeter to measure the sum and average duration of timed events', 'create a MetersDict to manage a priority-sorted collection of Meter instances', 'use safe_round to round numbers, torch tensors, or numpy scalars to N decimal places', 'create a named aggregation context to collect and aggregate metrics during training or validation', 'log a scalar value like loss or accuracy into all active metrics aggregators with optional weight', 'log a derived metric computed from other meters using a callable function', 'log the rate of a quantity per second using a time-based meter for throughput tracking', 'get all smoothed metric values aggregated under a given name like train or valid', 'build a tqdm progress bar wrapper around an iterator with epoch and prefix logging', 'build a JSON format progress bar that logs stats at configurable intervals during iteration', 'create a TensorBoard progress bar wrapper that logs scalar metrics to a log directory', 'create a Weights and Biases progress bar wrapper that logs training stats to a W&B project', 'refactor the format_stat function to convert AverageMeter, TimeMeter, and tensor stats to strings']
```

Usage

```
{'build_progress_bar_tqdm': 'build a tqdm progress bar wrapper around an iterator with epoch and prefix logging', 'build_progress_bar_json': 'build a JSON format progress bar that logs stats at configurable intervals during iteration', 'create_progress_bar_tensorboard': 'create a TensorBoard progress bar wrapper that logs scalar metrics to a log directory', 'create_progress_bar_wandb': 'create a Weights and Biases progress bar wrapper that logs training stats to a W&B project', 'refactor_format_stat': 'refactor the format_stat function to convert AverageMeter, TimeMeter, and tensor stats to strings'}
```

