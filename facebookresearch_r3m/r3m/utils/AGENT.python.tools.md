# Agent Python Tools

- repo: facebookresearch/r3m
- repo_uri: https://github.com/facebookresearch/r3m

## File: facebookresearch_r3m/r3m/utils/data_loaders.py

Prompts

```
['create an R3MBuffer IterableDataset instance for Ego4D video data with configurable augmentation and alpha sampling', 'sample a tuple of five stacked video frames and a label from the R3MBuffer dataset', 'read a single indexed JPEG image from an Ego4D video directory using torchvision', 'review the R3MBuffer class RandomResizedCrop augmentation logic for rc and rctraj modes', 'refactor the R3MBuffer class to support additional datasets beyond Ego4D', 'create a Logger instance with a log directory to track training and eval metrics via CSV and W&B', 'log a scalar metric value with a train or eval prefix key and step number to the Logger', 'log a dictionary of metrics at once using log_metrics with a step and train or eval type', 'use the log_and_dump_ctx context manager to log multiple metrics and auto-dump them to CSV on exit', 'call dump on the Logger to flush all pending train and eval metrics to CSV files and the console', 'set the random seed across torch, cuda, numpy, and python random modules for reproducibility', 'perform a soft update of target network parameters using a tau interpolation factor', 'compute precision at k for classification output against target labels with configurable topk values', 'evaluate a linear or step_linear scheduling string to return a value for the given step number', 'sample from a truncated normal distribution clamped between low and high bounds with optional gradient clipping']
```

Usage

```
{'create_R3MBuffer_dataset': 'create an R3MBuffer IterableDataset instance for Ego4D video data with configurable augmentation and alpha sampling', 'sample_R3MBuffer': 'sample a tuple of five stacked video frames and a label from the R3MBuffer dataset', 'get_ind_read_image': 'read a single indexed JPEG image from an Ego4D video directory using torchvision', 'review_R3MBuffer_augmentation': 'review the R3MBuffer class RandomResizedCrop augmentation logic for rc and rctraj modes', 'refactor_R3MBuffer_datasources': 'refactor the R3MBuffer class to support additional datasets beyond Ego4D'}
```

## File: facebookresearch_r3m/r3m/utils/logger.py

Prompts

```
['create an R3MBuffer IterableDataset instance for Ego4D video data with configurable augmentation and alpha sampling', 'sample a tuple of five stacked video frames and a label from the R3MBuffer dataset', 'read a single indexed JPEG image from an Ego4D video directory using torchvision', 'review the R3MBuffer class RandomResizedCrop augmentation logic for rc and rctraj modes', 'refactor the R3MBuffer class to support additional datasets beyond Ego4D', 'create a Logger instance with a log directory to track training and eval metrics via CSV and W&B', 'log a scalar metric value with a train or eval prefix key and step number to the Logger', 'log a dictionary of metrics at once using log_metrics with a step and train or eval type', 'use the log_and_dump_ctx context manager to log multiple metrics and auto-dump them to CSV on exit', 'call dump on the Logger to flush all pending train and eval metrics to CSV files and the console', 'set the random seed across torch, cuda, numpy, and python random modules for reproducibility', 'perform a soft update of target network parameters using a tau interpolation factor', 'compute precision at k for classification output against target labels with configurable topk values', 'evaluate a linear or step_linear scheduling string to return a value for the given step number', 'sample from a truncated normal distribution clamped between low and high bounds with optional gradient clipping']
```

Usage

```
{'create_logger_for_rl_training': 'create a Logger instance with a log directory to track training and eval metrics via CSV and W&B', 'log_scalar_metric': 'log a scalar metric value with a train or eval prefix key and step number to the Logger', 'log_batch_metrics': 'log a dictionary of metrics at once using log_metrics with a step and train or eval type', 'use_log_and_dump_context': 'use the log_and_dump_ctx context manager to log multiple metrics and auto-dump them to CSV on exit', 'dump_metrics_to_csv_and_console': 'call dump on the Logger to flush all pending train and eval metrics to CSV files and the console'}
```

## File: facebookresearch_r3m/r3m/utils/utils.py

Prompts

```
['create an R3MBuffer IterableDataset instance for Ego4D video data with configurable augmentation and alpha sampling', 'sample a tuple of five stacked video frames and a label from the R3MBuffer dataset', 'read a single indexed JPEG image from an Ego4D video directory using torchvision', 'review the R3MBuffer class RandomResizedCrop augmentation logic for rc and rctraj modes', 'refactor the R3MBuffer class to support additional datasets beyond Ego4D', 'create a Logger instance with a log directory to track training and eval metrics via CSV and W&B', 'log a scalar metric value with a train or eval prefix key and step number to the Logger', 'log a dictionary of metrics at once using log_metrics with a step and train or eval type', 'use the log_and_dump_ctx context manager to log multiple metrics and auto-dump them to CSV on exit', 'call dump on the Logger to flush all pending train and eval metrics to CSV files and the console', 'set the random seed across torch, cuda, numpy, and python random modules for reproducibility', 'perform a soft update of target network parameters using a tau interpolation factor', 'compute precision at k for classification output against target labels with configurable topk values', 'evaluate a linear or step_linear scheduling string to return a value for the given step number', 'sample from a truncated normal distribution clamped between low and high bounds with optional gradient clipping']
```

Usage

```
{'set_seed_everywhere': 'set the random seed across torch, cuda, numpy, and python random modules for reproducibility', 'soft_update_params': 'perform a soft update of target network parameters using a tau interpolation factor', 'accuracy': 'compute precision at k for classification output against target labels with configurable topk values', 'schedule': 'evaluate a linear or step_linear scheduling string to return a value for the given step number', 'TruncatedNormal_sample': 'sample from a truncated normal distribution clamped between low and high bounds with optional gradient clipping'}
```

