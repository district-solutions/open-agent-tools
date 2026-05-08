# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/evaluation/metric.py

Prompts

```
['create a MetricReporter instance with a name, scope, and aggregator functions to track gym environment metrics', 'report a metric value to the MetricCore buffer by calling the report method with the value', 'get the aggregated episode metric values by calling get_episode_metric on a MetricReporter instance', 'get multi-episode aggregated metrics by calling get_multi_ep_metric with episodic metric data as input', 'reset the episode data buffer by calling reset_episode on a MetricReporter to clear stored values', 'create a MetricLogger instance to manage and track evaluation metrics for gym environments', 'create a new metric with custom single and multi episode aggregators via MetricLogger.create_metric', 'create a scalar metric using MetricLogger.create_scalar_metric with a single episode aggregator function', 'get all registered metrics for the current episode by calling MetricLogger.get_episode_metrics', 'compute mean max min and std statistics from a sequence of float values using common_stats', 'create a MetricStats instance from a sequence of numeric data values', 'compute the average of metric data using the MetricStats avg property', 'find the minimum value in metric data using the MetricStats min property', 'find the maximum value in metric data using the MetricStats max property', 'sum all values in metric data using the MetricStats sum property']
```

Usage

```
{'create_metric_reporter': 'create a MetricReporter instance with a name, scope, and aggregator functions to track gym environment metrics', 'report_metric_value': 'report a metric value to the MetricCore buffer by calling the report method with the value', 'get_episode_metric': 'get the aggregated episode metric values by calling get_episode_metric on a MetricReporter instance', 'get_multi_ep_metric': 'get multi-episode aggregated metrics by calling get_multi_ep_metric with episodic metric data as input', 'reset_episode_data': 'reset the episode data buffer by calling reset_episode on a MetricReporter to clear stored values'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/evaluation/metric_logger.py

Prompts

```
['create a MetricReporter instance with a name, scope, and aggregator functions to track gym environment metrics', 'report a metric value to the MetricCore buffer by calling the report method with the value', 'get the aggregated episode metric values by calling get_episode_metric on a MetricReporter instance', 'get multi-episode aggregated metrics by calling get_multi_ep_metric with episodic metric data as input', 'reset the episode data buffer by calling reset_episode on a MetricReporter to clear stored values', 'create a MetricLogger instance to manage and track evaluation metrics for gym environments', 'create a new metric with custom single and multi episode aggregators via MetricLogger.create_metric', 'create a scalar metric using MetricLogger.create_scalar_metric with a single episode aggregator function', 'get all registered metrics for the current episode by calling MetricLogger.get_episode_metrics', 'compute mean max min and std statistics from a sequence of float values using common_stats', 'create a MetricStats instance from a sequence of numeric data values', 'compute the average of metric data using the MetricStats avg property', 'find the minimum value in metric data using the MetricStats min property', 'find the maximum value in metric data using the MetricStats max property', 'sum all values in metric data using the MetricStats sum property']
```

Usage

```
{'create_metric_logger': 'create a MetricLogger instance to manage and track evaluation metrics for gym environments', 'create_metric': 'create a new metric with custom single and multi episode aggregators via MetricLogger.create_metric', 'create_scalar_metric': 'create a scalar metric using MetricLogger.create_scalar_metric with a single episode aggregator function', 'get_episode_metrics': 'get all registered metrics for the current episode by calling MetricLogger.get_episode_metrics', 'common_stats': 'compute mean max min and std statistics from a sequence of float values using common_stats'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/evaluation/metric_utils.py

Prompts

```
['create a MetricReporter instance with a name, scope, and aggregator functions to track gym environment metrics', 'report a metric value to the MetricCore buffer by calling the report method with the value', 'get the aggregated episode metric values by calling get_episode_metric on a MetricReporter instance', 'get multi-episode aggregated metrics by calling get_multi_ep_metric with episodic metric data as input', 'reset the episode data buffer by calling reset_episode on a MetricReporter to clear stored values', 'create a MetricLogger instance to manage and track evaluation metrics for gym environments', 'create a new metric with custom single and multi episode aggregators via MetricLogger.create_metric', 'create a scalar metric using MetricLogger.create_scalar_metric with a single episode aggregator function', 'get all registered metrics for the current episode by calling MetricLogger.get_episode_metrics', 'compute mean max min and std statistics from a sequence of float values using common_stats', 'create a MetricStats instance from a sequence of numeric data values', 'compute the average of metric data using the MetricStats avg property', 'find the minimum value in metric data using the MetricStats min property', 'find the maximum value in metric data using the MetricStats max property', 'sum all values in metric data using the MetricStats sum property']
```

Usage

```
{'create_metric_stats_instance': 'create a MetricStats instance from a sequence of numeric data values', 'compute_average_metric': 'compute the average of metric data using the MetricStats avg property', 'find_min_metric': 'find the minimum value in metric data using the MetricStats min property', 'find_max_metric': 'find the maximum value in metric data using the MetricStats max property', 'sum_metric_data': 'sum all values in metric data using the MetricStats sum property'}
```

