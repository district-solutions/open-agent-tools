# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/utils/logger.py

Prompts

```
['create a Logger instance with quiet mode to write log lines to a file instead of stdout', 'add a line of content to the Logger which writes to file or prints depending on quiet mode', 'create a ProgressMeter to track training batches with meters for a given phase and epoch', 'display the current batch progress with meter values to stdout or a Logger instance', 'synchronize meter averages across all GPUs using torch distributed all_gather in a multi-GPU setup', 'build a PyTorch model from a config dictionary using the build_model function', 'build an SGD or Adam optimizer with a cosine or multistep learning rate scheduler from config', 'build a data loader from a dataset config using build_dataloader with num workers and distributed flag', 'initialize a PyTorch distributed process group for multi-GPU training with the given args and GPU count', 'recursively copy nested lists, tuples, and dicts of tensors to GPU with non-blocking transfers', 'compute top-k classification accuracy for PyTorch model output predictions against target labels', 'create an AverageMeter instance to track running average and current values of a metric', 'update an AverageMeter with a new value and optional sample count for running average tracking', 'reset an AverageMeter to clear all accumulated values and start fresh tracking', 'create an AverageMeter with a sliding window size to track recent metric averages']
```

Usage

```
{'create_logger_instance': 'create a Logger instance with quiet mode to write log lines to a file instead of stdout', 'add_line_to_logger': 'add a line of content to the Logger which writes to file or prints depending on quiet mode', 'create_progress_meter': 'create a ProgressMeter to track training batches with meters for a given phase and epoch', 'display_progress_meter': 'display the current batch progress with meter values to stdout or a Logger instance', 'synchronize_meters_across_gpus': 'synchronize meter averages across all GPUs using torch distributed all_gather in a multi-GPU setup'}
```

## File: facebookresearch_depthcontrast/utils/main_utils.py

Prompts

```
['create a Logger instance with quiet mode to write log lines to a file instead of stdout', 'add a line of content to the Logger which writes to file or prints depending on quiet mode', 'create a ProgressMeter to track training batches with meters for a given phase and epoch', 'display the current batch progress with meter values to stdout or a Logger instance', 'synchronize meter averages across all GPUs using torch distributed all_gather in a multi-GPU setup', 'build a PyTorch model from a config dictionary using the build_model function', 'build an SGD or Adam optimizer with a cosine or multistep learning rate scheduler from config', 'build a data loader from a dataset config using build_dataloader with num workers and distributed flag', 'initialize a PyTorch distributed process group for multi-GPU training with the given args and GPU count', 'recursively copy nested lists, tuples, and dicts of tensors to GPU with non-blocking transfers', 'compute top-k classification accuracy for PyTorch model output predictions against target labels', 'create an AverageMeter instance to track running average and current values of a metric', 'update an AverageMeter with a new value and optional sample count for running average tracking', 'reset an AverageMeter to clear all accumulated values and start fresh tracking', 'create an AverageMeter with a sliding window size to track recent metric averages']
```

Usage

```
{'build_model_from_config': 'build a PyTorch model from a config dictionary using the build_model function', 'build_optimizer_and_scheduler': 'build an SGD or Adam optimizer with a cosine or multistep learning rate scheduler from config', 'build_dataloader_from_config': 'build a data loader from a dataset config using build_dataloader with num workers and distributed flag', 'initialize_distributed_backend': 'initialize a PyTorch distributed process group for multi-GPU training with the given args and GPU count', 'recursive_copy_to_gpu': 'recursively copy nested lists, tuples, and dicts of tensors to GPU with non-blocking transfers'}
```

## File: facebookresearch_depthcontrast/utils/metrics_utils.py

Prompts

```
['create a Logger instance with quiet mode to write log lines to a file instead of stdout', 'add a line of content to the Logger which writes to file or prints depending on quiet mode', 'create a ProgressMeter to track training batches with meters for a given phase and epoch', 'display the current batch progress with meter values to stdout or a Logger instance', 'synchronize meter averages across all GPUs using torch distributed all_gather in a multi-GPU setup', 'build a PyTorch model from a config dictionary using the build_model function', 'build an SGD or Adam optimizer with a cosine or multistep learning rate scheduler from config', 'build a data loader from a dataset config using build_dataloader with num workers and distributed flag', 'initialize a PyTorch distributed process group for multi-GPU training with the given args and GPU count', 'recursively copy nested lists, tuples, and dicts of tensors to GPU with non-blocking transfers', 'compute top-k classification accuracy for PyTorch model output predictions against target labels', 'create an AverageMeter instance to track running average and current values of a metric', 'update an AverageMeter with a new value and optional sample count for running average tracking', 'reset an AverageMeter to clear all accumulated values and start fresh tracking', 'create an AverageMeter with a sliding window size to track recent metric averages']
```

Usage

```
{'compute_topk_accuracy': 'compute top-k classification accuracy for PyTorch model output predictions against target labels', 'create_average_meter': 'create an AverageMeter instance to track running average and current values of a metric', 'update_average_meter': 'update an AverageMeter with a new value and optional sample count for running average tracking', 'reset_average_meter': 'reset an AverageMeter to clear all accumulated values and start fresh tracking', 'use_average_meter_with_window': 'create an AverageMeter with a sliding window size to track recent metric averages'}
```

