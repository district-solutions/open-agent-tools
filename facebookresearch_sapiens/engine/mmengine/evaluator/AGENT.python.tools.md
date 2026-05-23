# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/evaluator/evaluator.py

Prompts

```
['build an Evaluator instance from a list of BaseMetric configs to compose multiple metrics', 'set the dataset_meta property on an Evaluator to propagate meta info to all metrics', 'process a batch of BaseDataElement predictions and data through all registered metrics', 'evaluate all registered metrics and return a dictionary of results with conflict detection', 'offline evaluate dumped predictions in chunks against validation data and return collected metrics', 'create a subclass of BaseMetric implementing process and compute_metrics methods for custom evaluation', 'call evaluate on a BaseMetric instance to collect results and compute metrics across distributed ranks', 'set and get dataset_meta property on a BaseMetric instance to pass dataset info to the metric', 'use DumpResults metric to save model predictions to a pickle file for offline evaluation', 'use _to_cpu to recursively transfer tensors and BaseDataElement objects from GPU to CPU', "get the metric value using a full name indicator like 'COCO/AP' from evaluation results", "get the metric value using a short name indicator like 'AP' from evaluation results", 'test get_metric_value with a full name indicator that matches a key in the metrics dict', 'test get_metric_value with a short name indicator that matches the suffix of a metrics key', 'test get_metric_value raises ValueError when the indicator matches no metrics in the dict']
```

Usage

```
{'build_evaluator_with_metrics': 'build an Evaluator instance from a list of BaseMetric configs to compose multiple metrics', 'set_dataset_meta': 'set the dataset_meta property on an Evaluator to propagate meta info to all metrics', 'process_data_samples': 'process a batch of BaseDataElement predictions and data through all registered metrics', 'evaluate_metrics': 'evaluate all registered metrics and return a dictionary of results with conflict detection', 'offline_evaluate_predictions': 'offline evaluate dumped predictions in chunks against validation data and return collected metrics'}
```

## File: facebookresearch_sapiens/engine/mmengine/evaluator/metric.py

Prompts

```
['build an Evaluator instance from a list of BaseMetric configs to compose multiple metrics', 'set the dataset_meta property on an Evaluator to propagate meta info to all metrics', 'process a batch of BaseDataElement predictions and data through all registered metrics', 'evaluate all registered metrics and return a dictionary of results with conflict detection', 'offline evaluate dumped predictions in chunks against validation data and return collected metrics', 'create a subclass of BaseMetric implementing process and compute_metrics methods for custom evaluation', 'call evaluate on a BaseMetric instance to collect results and compute metrics across distributed ranks', 'set and get dataset_meta property on a BaseMetric instance to pass dataset info to the metric', 'use DumpResults metric to save model predictions to a pickle file for offline evaluation', 'use _to_cpu to recursively transfer tensors and BaseDataElement objects from GPU to CPU', "get the metric value using a full name indicator like 'COCO/AP' from evaluation results", "get the metric value using a short name indicator like 'AP' from evaluation results", 'test get_metric_value with a full name indicator that matches a key in the metrics dict', 'test get_metric_value with a short name indicator that matches the suffix of a metrics key', 'test get_metric_value raises ValueError when the indicator matches no metrics in the dict']
```

Usage

```
{'create_BaseMetric_subclass': 'create a subclass of BaseMetric implementing process and compute_metrics methods for custom evaluation', 'use_BaseMetric_evaluate': 'call evaluate on a BaseMetric instance to collect results and compute metrics across distributed ranks', 'use_BaseMetric_dataset_meta': 'set and get dataset_meta property on a BaseMetric instance to pass dataset info to the metric', 'use_DumpResults_metric': 'use DumpResults metric to save model predictions to a pickle file for offline evaluation', 'use_to_cpu_helper': 'use _to_cpu to recursively transfer tensors and BaseDataElement objects from GPU to CPU'}
```

## File: facebookresearch_sapiens/engine/mmengine/evaluator/utils.py

Prompts

```
['build an Evaluator instance from a list of BaseMetric configs to compose multiple metrics', 'set the dataset_meta property on an Evaluator to propagate meta info to all metrics', 'process a batch of BaseDataElement predictions and data through all registered metrics', 'evaluate all registered metrics and return a dictionary of results with conflict detection', 'offline evaluate dumped predictions in chunks against validation data and return collected metrics', 'create a subclass of BaseMetric implementing process and compute_metrics methods for custom evaluation', 'call evaluate on a BaseMetric instance to collect results and compute metrics across distributed ranks', 'set and get dataset_meta property on a BaseMetric instance to pass dataset info to the metric', 'use DumpResults metric to save model predictions to a pickle file for offline evaluation', 'use _to_cpu to recursively transfer tensors and BaseDataElement objects from GPU to CPU', "get the metric value using a full name indicator like 'COCO/AP' from evaluation results", "get the metric value using a short name indicator like 'AP' from evaluation results", 'test get_metric_value with a full name indicator that matches a key in the metrics dict', 'test get_metric_value with a short name indicator that matches the suffix of a metrics key', 'test get_metric_value raises ValueError when the indicator matches no metrics in the dict']
```

Usage

```
{'get_metric_value_by_full_name': "get the metric value using a full name indicator like 'COCO/AP' from evaluation results", 'get_metric_value_by_short_name': "get the metric value using a short name indicator like 'AP' from evaluation results", 'test_get_metric_value_exact_match': 'test get_metric_value with a full name indicator that matches a key in the metrics dict', 'test_get_metric_value_suffix_match': 'test get_metric_value with a short name indicator that matches the suffix of a metrics key', 'test_get_metric_value_no_match': 'test get_metric_value raises ValueError when the indicator matches no metrics in the dict'}
```

