# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/metrics/aggregation.py

Prompts

```
['create a Min metric instance to track the minimum value across updates', 'create a Max metric instance to track the maximum value across updates', 'create a Mean metric instance to compute the running average of values', 'create a Sum metric instance to accumulate the sum of values with optional weights', 'update a Min Max Mean or Sum metric with an int float or Tensor value', 'create a MetricBag instance on a device to hold training or validation metrics', 'add a named torcheval Metric to a MetricBag which moves it to the bag device', 'get a named metric from a MetricBag with type checking against an expected class', 'sync metrics across all processes via a Gang and compute their final values', 'begin transactional updates on a MetricBag then rollback to discard pending changes', 'add the negative log-likelihood loss metric to a MetricBag for tracking mean NLL during training', 'update the NLL loss metric in a MetricBag with a loss tensor and optional target count', 'add sequence batch metrics like num_examples, num_elements, and padding to a MetricBag', 'update sequence batch metrics in a MetricBag using a SequenceBatch with example and element counts', 'extend batch metric values with derived metrics like batch_size, elements_per_second, and padding_ratio', 'create a python module that formats a metric value as an integer with optional postfix', 'create a python module that formats a metric value as a duration in seconds', 'create a python module that formats a metric value as a float with optional postfix', 'create a python module that formats a metric value as a percentage string', 'create a python module that formats a metric value in human readable byte units']
```

Usage

```
{'create_Min_metric': 'create a Min metric instance to track the minimum value across updates', 'create_Max_metric': 'create a Max metric instance to track the maximum value across updates', 'create_Mean_metric': 'create a Mean metric instance to compute the running average of values', 'create_Sum_metric': 'create a Sum metric instance to accumulate the sum of values with optional weights', 'update_metric_with_value': 'update a Min Max Mean or Sum metric with an int float or Tensor value'}
```

## File: facebookresearch_fairseq2/src/fairseq2/metrics/bag.py

Prompts

```
['create a Min metric instance to track the minimum value across updates', 'create a Max metric instance to track the maximum value across updates', 'create a Mean metric instance to compute the running average of values', 'create a Sum metric instance to accumulate the sum of values with optional weights', 'update a Min Max Mean or Sum metric with an int float or Tensor value', 'create a MetricBag instance on a device to hold training or validation metrics', 'add a named torcheval Metric to a MetricBag which moves it to the bag device', 'get a named metric from a MetricBag with type checking against an expected class', 'sync metrics across all processes via a Gang and compute their final values', 'begin transactional updates on a MetricBag then rollback to discard pending changes', 'add the negative log-likelihood loss metric to a MetricBag for tracking mean NLL during training', 'update the NLL loss metric in a MetricBag with a loss tensor and optional target count', 'add sequence batch metrics like num_examples, num_elements, and padding to a MetricBag', 'update sequence batch metrics in a MetricBag using a SequenceBatch with example and element counts', 'extend batch metric values with derived metrics like batch_size, elements_per_second, and padding_ratio', 'create a python module that formats a metric value as an integer with optional postfix', 'create a python module that formats a metric value as a duration in seconds', 'create a python module that formats a metric value as a float with optional postfix', 'create a python module that formats a metric value as a percentage string', 'create a python module that formats a metric value in human readable byte units']
```

Usage

```
{'create_metric_bag': 'create a MetricBag instance on a device to hold training or validation metrics', 'add_metric_to_bag': 'add a named torcheval Metric to a MetricBag which moves it to the bag device', 'get_metric_from_bag': 'get a named metric from a MetricBag with type checking against an expected class', 'sync_and_compute_metrics': 'sync metrics across all processes via a Gang and compute their final values', 'rollback_metric_updates': 'begin transactional updates on a MetricBag then rollback to discard pending changes'}
```

## File: facebookresearch_fairseq2/src/fairseq2/metrics/common.py

Prompts

```
['create a Min metric instance to track the minimum value across updates', 'create a Max metric instance to track the maximum value across updates', 'create a Mean metric instance to compute the running average of values', 'create a Sum metric instance to accumulate the sum of values with optional weights', 'update a Min Max Mean or Sum metric with an int float or Tensor value', 'create a MetricBag instance on a device to hold training or validation metrics', 'add a named torcheval Metric to a MetricBag which moves it to the bag device', 'get a named metric from a MetricBag with type checking against an expected class', 'sync metrics across all processes via a Gang and compute their final values', 'begin transactional updates on a MetricBag then rollback to discard pending changes', 'add the negative log-likelihood loss metric to a MetricBag for tracking mean NLL during training', 'update the NLL loss metric in a MetricBag with a loss tensor and optional target count', 'add sequence batch metrics like num_examples, num_elements, and padding to a MetricBag', 'update sequence batch metrics in a MetricBag using a SequenceBatch with example and element counts', 'extend batch metric values with derived metrics like batch_size, elements_per_second, and padding_ratio', 'create a python module that formats a metric value as an integer with optional postfix', 'create a python module that formats a metric value as a duration in seconds', 'create a python module that formats a metric value as a float with optional postfix', 'create a python module that formats a metric value as a percentage string', 'create a python module that formats a metric value in human readable byte units']
```

Usage

```
{'add_nll_loss_metric': 'add the negative log-likelihood loss metric to a MetricBag for tracking mean NLL during training', 'update_nll_loss_metric': 'update the NLL loss metric in a MetricBag with a loss tensor and optional target count', 'add_seq_batch_metrics': 'add sequence batch metrics like num_examples, num_elements, and padding to a MetricBag', 'update_seq_batch_metrics': 'update sequence batch metrics in a MetricBag using a SequenceBatch with example and element counts', 'extend_batch_metric_values': 'extend batch metric values with derived metrics like batch_size, elements_per_second, and padding_ratio'}
```

## File: facebookresearch_fairseq2/src/fairseq2/metrics/formatters.py

Prompts

```
['create a Min metric instance to track the minimum value across updates', 'create a Max metric instance to track the maximum value across updates', 'create a Mean metric instance to compute the running average of values', 'create a Sum metric instance to accumulate the sum of values with optional weights', 'update a Min Max Mean or Sum metric with an int float or Tensor value', 'create a MetricBag instance on a device to hold training or validation metrics', 'add a named torcheval Metric to a MetricBag which moves it to the bag device', 'get a named metric from a MetricBag with type checking against an expected class', 'sync metrics across all processes via a Gang and compute their final values', 'begin transactional updates on a MetricBag then rollback to discard pending changes', 'add the negative log-likelihood loss metric to a MetricBag for tracking mean NLL during training', 'update the NLL loss metric in a MetricBag with a loss tensor and optional target count', 'add sequence batch metrics like num_examples, num_elements, and padding to a MetricBag', 'update sequence batch metrics in a MetricBag using a SequenceBatch with example and element counts', 'extend batch metric values with derived metrics like batch_size, elements_per_second, and padding_ratio', 'create a python module that formats a metric value as an integer with optional postfix', 'create a python module that formats a metric value as a duration in seconds', 'create a python module that formats a metric value as a float with optional postfix', 'create a python module that formats a metric value as a percentage string', 'create a python module that formats a metric value in human readable byte units']
```

Usage

```
{'format_metric_as_int': 'create a python module that formats a metric value as an integer with optional postfix', 'format_metric_as_seconds': 'create a python module that formats a metric value as a duration in seconds', 'format_metric_as_float': 'create a python module that formats a metric value as a float with optional postfix', 'format_metric_as_percentage': 'create a python module that formats a metric value as a percentage string', 'format_metric_as_byte_size': 'create a python module that formats a metric value in human readable byte units'}
```

