# Agent Python Tools

- repo: facebookresearch/kats
- repo_uri: https://github.com/facebookresearch/kats

## File: facebookresearch_kats/kats/metrics/metadata.py

Prompts

```
['inspect a Kats metric by name to get its type, directionality, and bounds', 'create a MetricMetadata dataclass with type, direction, lower_bound, and upper_bound fields', 'use the MetricType enum to classify metrics as SCORE, ERROR, or NONE', 'use the Directionality enum to indicate whether larger or smaller metric values are better', 'list all registered Kats metrics and their metadata including aliases like mae, rmse, and r2', 'compute the mean absolute error between actual and predicted values using mean_absolute_error', 'compute the root mean squared error between actual and predicted values using root_mean_squared_error', 'compute the mean absolute percentage error between actual and predicted values using mean_absolute_percentage_error', 'compute the symmetric mean absolute percentage error between actual and predicted values using symmetric_mean_absolute_percentage_error', 'look up a metric function by name or abbreviation using the metric convenience method']
```

Usage

```
{'inspect_metric_metadata': 'inspect a Kats metric by name to get its type, directionality, and bounds', 'create_metric_metadata_dataclass': 'create a MetricMetadata dataclass with type, direction, lower_bound, and upper_bound fields', 'use_metrictype_enum': 'use the MetricType enum to classify metrics as SCORE, ERROR, or NONE', 'use_directionality_enum': 'use the Directionality enum to indicate whether larger or smaller metric values are better', 'list_all_metric_metadata': 'list all registered Kats metrics and their metadata including aliases like mae, rmse, and r2'}
```

## File: facebookresearch_kats/kats/metrics/metrics.py

Prompts

```
['inspect a Kats metric by name to get its type, directionality, and bounds', 'create a MetricMetadata dataclass with type, direction, lower_bound, and upper_bound fields', 'use the MetricType enum to classify metrics as SCORE, ERROR, or NONE', 'use the Directionality enum to indicate whether larger or smaller metric values are better', 'list all registered Kats metrics and their metadata including aliases like mae, rmse, and r2', 'compute the mean absolute error between actual and predicted values using mean_absolute_error', 'compute the root mean squared error between actual and predicted values using root_mean_squared_error', 'compute the mean absolute percentage error between actual and predicted values using mean_absolute_percentage_error', 'compute the symmetric mean absolute percentage error between actual and predicted values using symmetric_mean_absolute_percentage_error', 'look up a metric function by name or abbreviation using the metric convenience method']
```

Usage

```
{'compute_mae': 'compute the mean absolute error between actual and predicted values using mean_absolute_error', 'compute_rmse': 'compute the root mean squared error between actual and predicted values using root_mean_squared_error', 'compute_mape': 'compute the mean absolute percentage error between actual and predicted values using mean_absolute_percentage_error', 'compute_smape': 'compute the symmetric mean absolute percentage error between actual and predicted values using symmetric_mean_absolute_percentage_error', 'lookup_metric_by_name': 'look up a metric function by name or abbreviation using the metric convenience method'}
```

