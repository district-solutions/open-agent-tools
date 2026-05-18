# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/trainers/lightning_core/loop_callback.py

Prompts

```
['create a LightningLoopCallback instance with a lightning trainer to manage training and validation loop callbacks', 'review the on_train_batch_end method to understand how training reports are aggregated and logged per batch', 'review the on_validation_batch_end method to see how validation outputs are aggregated and metrics are computed', 'test the _update_and_create_report method to verify loss normalization and report accumulation across gradient batches', 'summarize the _train_log method to understand how training metrics, learning rate, and ETA are logged to TensorBoard', 'create a LightningTorchMetricsCallback instance with a lightning trainer to track torchmetrics during training', 'review the on_validation_end method that logs validation metrics and resets torchmetrics after evaluation', 'test the get_optimizer method that retrieves the single optimizer from a PyTorch Lightning trainer', 'refactor the _log_metrics_and_extra method to support custom metric formatting and TensorBoard logging', 'create a LightningTorchMetrics instance from a list of metric configurations with type and params', 'update all registered torchmetrics with a new SampleList and model output dictionary', 'compute and return a dictionary of all registered metric results as tensors', 'reset all registered torchmetrics to their initial state for a new evaluation epoch', 'compute metrics and return only scalar tensor values as a flat dictionary']
```

Usage

```
{'create_LightningLoopCallback': 'create a LightningLoopCallback instance with a lightning trainer to manage training and validation loop callbacks', 'review_on_train_batch_end': 'review the on_train_batch_end method to understand how training reports are aggregated and logged per batch', 'review_on_validation_batch_end': 'review the on_validation_batch_end method to see how validation outputs are aggregated and metrics are computed', 'test_update_and_create_report': 'test the _update_and_create_report method to verify loss normalization and report accumulation across gradient batches', 'summarize_train_log': 'summarize the _train_log method to understand how training metrics, learning rate, and ETA are logged to TensorBoard'}
```

## File: facebookresearch_mmf/mmf/trainers/lightning_core/loop_callback_with_torchmetrics.py

Prompts

```
['create a LightningLoopCallback instance with a lightning trainer to manage training and validation loop callbacks', 'review the on_train_batch_end method to understand how training reports are aggregated and logged per batch', 'review the on_validation_batch_end method to see how validation outputs are aggregated and metrics are computed', 'test the _update_and_create_report method to verify loss normalization and report accumulation across gradient batches', 'summarize the _train_log method to understand how training metrics, learning rate, and ETA are logged to TensorBoard', 'create a LightningTorchMetricsCallback instance with a lightning trainer to track torchmetrics during training', 'review the on_validation_end method that logs validation metrics and resets torchmetrics after evaluation', 'test the get_optimizer method that retrieves the single optimizer from a PyTorch Lightning trainer', 'refactor the _log_metrics_and_extra method to support custom metric formatting and TensorBoard logging', 'create a LightningTorchMetrics instance from a list of metric configurations with type and params', 'update all registered torchmetrics with a new SampleList and model output dictionary', 'compute and return a dictionary of all registered metric results as tensors', 'reset all registered torchmetrics to their initial state for a new evaluation epoch', 'compute metrics and return only scalar tensor values as a flat dictionary']
```

Usage

```
{'create_LightningTorchMetricsCallback': 'create a LightningTorchMetricsCallback instance with a lightning trainer to track torchmetrics during training', 'review_on_train_batch_end': 'review the on_train_batch_end method that updates metrics and logs training progress periodically', 'review_on_validation_end': 'review the on_validation_end method that logs validation metrics and resets torchmetrics after evaluation', 'test_get_optimizer': 'test the get_optimizer method that retrieves the single optimizer from a PyTorch Lightning trainer', 'refactor__log_metrics_and_extra': 'refactor the _log_metrics_and_extra method to support custom metric formatting and TensorBoard logging'}
```

## File: facebookresearch_mmf/mmf/trainers/lightning_core/torchmetric.py

Prompts

```
['create a LightningLoopCallback instance with a lightning trainer to manage training and validation loop callbacks', 'review the on_train_batch_end method to understand how training reports are aggregated and logged per batch', 'review the on_validation_batch_end method to see how validation outputs are aggregated and metrics are computed', 'test the _update_and_create_report method to verify loss normalization and report accumulation across gradient batches', 'summarize the _train_log method to understand how training metrics, learning rate, and ETA are logged to TensorBoard', 'create a LightningTorchMetricsCallback instance with a lightning trainer to track torchmetrics during training', 'review the on_validation_end method that logs validation metrics and resets torchmetrics after evaluation', 'test the get_optimizer method that retrieves the single optimizer from a PyTorch Lightning trainer', 'refactor the _log_metrics_and_extra method to support custom metric formatting and TensorBoard logging', 'create a LightningTorchMetrics instance from a list of metric configurations with type and params', 'update all registered torchmetrics with a new SampleList and model output dictionary', 'compute and return a dictionary of all registered metric results as tensors', 'reset all registered torchmetrics to their initial state for a new evaluation epoch', 'compute metrics and return only scalar tensor values as a flat dictionary']
```

Usage

```
{'init_LightningTorchMetrics': 'create a LightningTorchMetrics instance from a list of metric configurations with type and params', 'update_metrics': 'update all registered torchmetrics with a new SampleList and model output dictionary', 'compute_metrics': 'compute and return a dictionary of all registered metric results as tensors', 'reset_metrics': 'reset all registered torchmetrics to their initial state for a new evaluation epoch', 'get_scalar_dict': 'compute metrics and return only scalar tensor values as a flat dictionary'}
```

