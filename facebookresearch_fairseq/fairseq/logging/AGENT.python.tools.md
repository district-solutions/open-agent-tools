# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/logging/meters.py

Prompts

```
['create an AverageMeter to track running averages of values with optional rounding', 'create a SumMeter to accumulate and store the sum of updated values', 'create a TimeMeter to compute the average rate of events per second', 'create a StopwatchMeter to measure the duration of events with start and stop', 'create a MetersDict to manage a priority-sorted collection of Meter instances', 'create a named aggregation context to collect metrics under a specific name like train or valid', 'log a scalar value with optional weight and priority into all active metric aggregators', 'log a derived metric value computed from a function that takes the current meters dict', 'get all smoothed metric values aggregated under a named aggregation context like train', 'reset all metrics aggregators and reinitialize the default aggregator for fresh metric collection', 'build a progress bar from an iterator with tqdm, json, or simple log format', 'build a progress bar from an argparse.Namespace and iterator using build_progress_bar', 'create a JsonProgressBar to log training stats as JSON lines at intervals', 'create a TensorboardProgressBarWrapper to log training metrics to TensorBoard', 'create a WandBProgressBarWrapper to log training metrics to Weights and Biases']
```

Usage

```
{'create_average_meter': 'create an AverageMeter to track running averages of values with optional rounding', 'create_sum_meter': 'create a SumMeter to accumulate and store the sum of updated values', 'create_time_meter': 'create a TimeMeter to compute the average rate of events per second', 'create_stopwatch_meter': 'create a StopwatchMeter to measure the duration of events with start and stop', 'create_meters_dict': 'create a MetersDict to manage a priority-sorted collection of Meter instances'}
```

## File: facebookresearch_fairseq/fairseq/logging/metrics.py

Prompts

```
['create an AverageMeter to track running averages of values with optional rounding', 'create a SumMeter to accumulate and store the sum of updated values', 'create a TimeMeter to compute the average rate of events per second', 'create a StopwatchMeter to measure the duration of events with start and stop', 'create a MetersDict to manage a priority-sorted collection of Meter instances', 'create a named aggregation context to collect metrics under a specific name like train or valid', 'log a scalar value with optional weight and priority into all active metric aggregators', 'log a derived metric value computed from a function that takes the current meters dict', 'get all smoothed metric values aggregated under a named aggregation context like train', 'reset all metrics aggregators and reinitialize the default aggregator for fresh metric collection', 'build a progress bar from an iterator with tqdm, json, or simple log format', 'build a progress bar from an argparse.Namespace and iterator using build_progress_bar', 'create a JsonProgressBar to log training stats as JSON lines at intervals', 'create a TensorboardProgressBarWrapper to log training metrics to TensorBoard', 'create a WandBProgressBarWrapper to log training metrics to Weights and Biases']
```

Usage

```
{'create_aggregate_context': 'create a named aggregation context to collect metrics under a specific name like train or valid', 'log_scalar_value': 'log a scalar value with optional weight and priority into all active metric aggregators', 'log_derived_metric': 'log a derived metric value computed from a function that takes the current meters dict', 'get_smoothed_values': 'get all smoothed metric values aggregated under a named aggregation context like train', 'reset_all_metrics': 'reset all metrics aggregators and reinitialize the default aggregator for fresh metric collection'}
```

## File: facebookresearch_fairseq/fairseq/logging/progress_bar.py

Prompts

```
['create an AverageMeter to track running averages of values with optional rounding', 'create a SumMeter to accumulate and store the sum of updated values', 'create a TimeMeter to compute the average rate of events per second', 'create a StopwatchMeter to measure the duration of events with start and stop', 'create a MetersDict to manage a priority-sorted collection of Meter instances', 'create a named aggregation context to collect metrics under a specific name like train or valid', 'log a scalar value with optional weight and priority into all active metric aggregators', 'log a derived metric value computed from a function that takes the current meters dict', 'get all smoothed metric values aggregated under a named aggregation context like train', 'reset all metrics aggregators and reinitialize the default aggregator for fresh metric collection', 'build a progress bar from an iterator with tqdm, json, or simple log format', 'build a progress bar from an argparse.Namespace and iterator using build_progress_bar', 'create a JsonProgressBar to log training stats as JSON lines at intervals', 'create a TensorboardProgressBarWrapper to log training metrics to TensorBoard', 'create a WandBProgressBarWrapper to log training metrics to Weights and Biases']
```

Usage

```
{'build_progress_bar': 'build a progress bar from an iterator with tqdm, json, or simple log format', 'build_legacy_progress_bar': 'build a progress bar from an argparse.Namespace and iterator using build_progress_bar', 'create_json_progress_bar': 'create a JsonProgressBar to log training stats as JSON lines at intervals', 'create_tensorboard_wrapper': 'create a TensorboardProgressBarWrapper to log training metrics to TensorBoard', 'create_wandb_wrapper': 'create a WandBProgressBarWrapper to log training metrics to Weights and Biases'}
```

