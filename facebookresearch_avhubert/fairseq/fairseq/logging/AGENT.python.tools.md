# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/logging/meters.py

Prompts

```
['create an AverageMeter to track and compute running averages of updated values with optional rounding', 'create a SumMeter to accumulate and store the running sum of updated values with optional rounding', 'create a TimeMeter to compute the average rate of events per second since initialization', 'create a StopwatchMeter to measure cumulative and average duration of timed events using start and stop', 'create a MetersDict to manage a priority-sorted collection of Meter instances with serialization support', 'create a named aggregation context to collect and aggregate metrics during training or validation loops', 'log a scalar metric value with optional weight and priority into all active aggregators', 'log a derived metric computed from other meters using a callable function', 'log the start and stop time of an event to measure duration in seconds', 'get all smoothed metric values aggregated under a given named aggregator context', 'build a progress bar from an argparse.Namespace and iterator with configurable log format', 'create a progress bar wrapping an iterator with json, simple, tqdm, or none log format', 'use JsonProgressBar to log training stats as JSON lines at regular intervals', 'use TensorboardProgressBarWrapper to log training metrics to TensorBoard scalars', 'use WandBProgressBarWrapper to log training metrics to Weights and Biases']
```

Usage

```
{'create_AverageMeter': 'create an AverageMeter to track and compute running averages of updated values with optional rounding', 'create_SumMeter': 'create a SumMeter to accumulate and store the running sum of updated values with optional rounding', 'create_TimeMeter': 'create a TimeMeter to compute the average rate of events per second since initialization', 'create_StopwatchMeter': 'create a StopwatchMeter to measure cumulative and average duration of timed events using start and stop', 'create_MetersDict': 'create a MetersDict to manage a priority-sorted collection of Meter instances with serialization support'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/logging/metrics.py

Prompts

```
['create an AverageMeter to track and compute running averages of updated values with optional rounding', 'create a SumMeter to accumulate and store the running sum of updated values with optional rounding', 'create a TimeMeter to compute the average rate of events per second since initialization', 'create a StopwatchMeter to measure cumulative and average duration of timed events using start and stop', 'create a MetersDict to manage a priority-sorted collection of Meter instances with serialization support', 'create a named aggregation context to collect and aggregate metrics during training or validation loops', 'log a scalar metric value with optional weight and priority into all active aggregators', 'log a derived metric computed from other meters using a callable function', 'log the start and stop time of an event to measure duration in seconds', 'get all smoothed metric values aggregated under a given named aggregator context', 'build a progress bar from an argparse.Namespace and iterator with configurable log format', 'create a progress bar wrapping an iterator with json, simple, tqdm, or none log format', 'use JsonProgressBar to log training stats as JSON lines at regular intervals', 'use TensorboardProgressBarWrapper to log training metrics to TensorBoard scalars', 'use WandBProgressBarWrapper to log training metrics to Weights and Biases']
```

Usage

```
{'create_aggregate_context': 'create a named aggregation context to collect and aggregate metrics during training or validation loops', 'log_scalar_values': 'log a scalar metric value with optional weight and priority into all active aggregators', 'log_derived_metrics': 'log a derived metric computed from other meters using a callable function', 'log_timing_metrics': 'log the start and stop time of an event to measure duration in seconds', 'get_smoothed_values': 'get all smoothed metric values aggregated under a given named aggregator context'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/logging/progress_bar.py

Prompts

```
['create an AverageMeter to track and compute running averages of updated values with optional rounding', 'create a SumMeter to accumulate and store the running sum of updated values with optional rounding', 'create a TimeMeter to compute the average rate of events per second since initialization', 'create a StopwatchMeter to measure cumulative and average duration of timed events using start and stop', 'create a MetersDict to manage a priority-sorted collection of Meter instances with serialization support', 'create a named aggregation context to collect and aggregate metrics during training or validation loops', 'log a scalar metric value with optional weight and priority into all active aggregators', 'log a derived metric computed from other meters using a callable function', 'log the start and stop time of an event to measure duration in seconds', 'get all smoothed metric values aggregated under a given named aggregator context', 'build a progress bar from an argparse.Namespace and iterator with configurable log format', 'create a progress bar wrapping an iterator with json, simple, tqdm, or none log format', 'use JsonProgressBar to log training stats as JSON lines at regular intervals', 'use TensorboardProgressBarWrapper to log training metrics to TensorBoard scalars', 'use WandBProgressBarWrapper to log training metrics to Weights and Biases']
```

Usage

```
{'build_progress_bar_from_args': 'build a progress bar from an argparse.Namespace and iterator with configurable log format', 'create_progress_bar_with_format': 'create a progress bar wrapping an iterator with json, simple, tqdm, or none log format', 'use_json_progress_bar': 'use JsonProgressBar to log training stats as JSON lines at regular intervals', 'use_tensorboard_wrapper': 'use TensorboardProgressBarWrapper to log training metrics to TensorBoard scalars', 'use_wandb_wrapper': 'use WandBProgressBarWrapper to log training metrics to Weights and Biases'}
```

