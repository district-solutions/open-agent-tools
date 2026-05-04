# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/fbpcp/metrics/emitter.py

Prompts

```
['review the MetricsEmitter abstract base class and its count and gauge abstract methods', 'summarize the MetricsEmitter ABC that defines the count and gauge interface for metrics emission', 'create a concrete implementation of the MetricsEmitter ABC with count and gauge methods', 'refactor the MetricsEmitter ABC to add additional abstract methods like histogram or timer', 'test a concrete MetricsEmitter subclass to verify count and gauge emit correctly', 'create a concrete subclass of MetricsGetter that implements has_metrics and get_metrics methods', 'review the MetricsGetter abstract base class and its two abstract methods for correctness', 'summarize the MetricsGetter ABC interface that defines has_metrics and get_metrics contracts', 'test a custom MetricsGetter subclass to verify has_metrics returns bool and get_metrics returns MetricsEmitter', 'refactor code that uses MetricsGetter to properly check has_metrics before calling get_metrics']
```

Usage

```
{'review_MetricsEmitter': 'review the MetricsEmitter abstract base class and its count and gauge abstract methods', 'summarize_MetricsEmitter': 'summarize the MetricsEmitter ABC that defines the count and gauge interface for metrics emission', 'create_MetricsEmitter_implementation': 'create a concrete implementation of the MetricsEmitter ABC with count and gauge methods', 'refactor_MetricsEmitter': 'refactor the MetricsEmitter ABC to add additional abstract methods like histogram or timer', 'test_MetricsEmitter_implementation': 'test a concrete MetricsEmitter subclass to verify count and gauge emit correctly'}
```

## File: facebookresearch_fbpcp/fbpcp/metrics/getter.py

Prompts

```
['review the MetricsEmitter abstract base class and its count and gauge abstract methods', 'summarize the MetricsEmitter ABC that defines the count and gauge interface for metrics emission', 'create a concrete implementation of the MetricsEmitter ABC with count and gauge methods', 'refactor the MetricsEmitter ABC to add additional abstract methods like histogram or timer', 'test a concrete MetricsEmitter subclass to verify count and gauge emit correctly', 'create a concrete subclass of MetricsGetter that implements has_metrics and get_metrics methods', 'review the MetricsGetter abstract base class and its two abstract methods for correctness', 'summarize the MetricsGetter ABC interface that defines has_metrics and get_metrics contracts', 'test a custom MetricsGetter subclass to verify has_metrics returns bool and get_metrics returns MetricsEmitter', 'refactor code that uses MetricsGetter to properly check has_metrics before calling get_metrics']
```

Usage

```
{'implement_metricsgetter_subclass': 'create a concrete subclass of MetricsGetter that implements has_metrics and get_metrics methods', 'review_metricsgetter_abc': 'review the MetricsGetter abstract base class and its two abstract methods for correctness', 'summarize_metricsgetter_interface': 'summarize the MetricsGetter ABC interface that defines has_metrics and get_metrics contracts', 'test_metricsgetter_subclass': 'test a custom MetricsGetter subclass to verify has_metrics returns bool and get_metrics returns MetricsEmitter', 'refactor_metricsgetter_usage': 'refactor code that uses MetricsGetter to properly check has_metrics before calling get_metrics'}
```

