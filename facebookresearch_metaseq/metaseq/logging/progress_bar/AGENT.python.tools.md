# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/logging/progress_bar/aim_progress_bar.py

Prompts

```
['create an AimProgressBarWrapper to log training and validation stats to an Aim repository', 'log intermediate training stats to Aim using the log method with a tag and step', 'print end-of-epoch stats and log them to Aim using the print method', 'update and log the latest configuration parameters to an Aim run using update_config', 'get a cached Aim Run instance by repo path and run hash using get_aim_run', 'create a BaseProgressBar subclass that implements __iter__, log, and print methods for custom progress tracking', 'format a numeric stat value using format_stat to get a compact string representation', 'format an AverageMeter or TimeMeter stat using format_stat to display its average value', 'format a PyTorch tensor stat using format_stat to convert it to a string with 3 significant figures', 'use _format_stats on a stats dictionary to produce an OrderedDict of formatted string values', 'create a JsonProgressBar instance to log training stats in JSON format', 'log intermediate training stats at configured intervals using JsonProgressBar log method', 'print end-of-epoch stats as JSON using JsonProgressBar print method', 'format stats dictionary with epoch and update info using _format_stats method', 'use rename_logger context manager to temporarily change logger name during logging', 'create a TensorboardProgressBarWrapper to log training stats to tensorboard with a specified log directory', 'log intermediate training stats like loss and accuracy to tensorboard using the log method', 'print end-of-epoch stats and log them to tensorboard using the print method', 'manage tensorboard SummaryWriter instances with automatic suffix handling to avoid clobbering reruns', 'close all open tensorboard writer instances at program exit using the registered atexit handler', 'create a WandBProgressBarWrapper to log training progress to a Weights and Biases project', 'log intermediate training stats like loss and accuracy to Weights and Biases during training', 'print end-of-epoch stats and log them to Weights and Biases for tracking', 'update the Weights and Biases run configuration with new hyperparameters or settings', 'review the WandBProgressBarWrapper class to understand how it wraps a progress bar and logs to wandb']
```

Usage

```
{'create_aim_progress_bar_wrapper': 'create an AimProgressBarWrapper to log training and validation stats to an Aim repository', 'log_stats_to_aim': 'log intermediate training stats to Aim using the log method with a tag and step', 'print_epoch_stats_to_aim': 'print end-of-epoch stats and log them to Aim using the print method', 'update_config_in_aim': 'update and log the latest configuration parameters to an Aim run using update_config', 'get_aim_run_cached': 'get a cached Aim Run instance by repo path and run hash using get_aim_run'}
```

## File: facebookresearch_metaseq/metaseq/logging/progress_bar/base_progress_bar.py

Prompts

```
['create an AimProgressBarWrapper to log training and validation stats to an Aim repository', 'log intermediate training stats to Aim using the log method with a tag and step', 'print end-of-epoch stats and log them to Aim using the print method', 'update and log the latest configuration parameters to an Aim run using update_config', 'get a cached Aim Run instance by repo path and run hash using get_aim_run', 'create a BaseProgressBar subclass that implements __iter__, log, and print methods for custom progress tracking', 'format a numeric stat value using format_stat to get a compact string representation', 'format an AverageMeter or TimeMeter stat using format_stat to display its average value', 'format a PyTorch tensor stat using format_stat to convert it to a string with 3 significant figures', 'use _format_stats on a stats dictionary to produce an OrderedDict of formatted string values', 'create a JsonProgressBar instance to log training stats in JSON format', 'log intermediate training stats at configured intervals using JsonProgressBar log method', 'print end-of-epoch stats as JSON using JsonProgressBar print method', 'format stats dictionary with epoch and update info using _format_stats method', 'use rename_logger context manager to temporarily change logger name during logging', 'create a TensorboardProgressBarWrapper to log training stats to tensorboard with a specified log directory', 'log intermediate training stats like loss and accuracy to tensorboard using the log method', 'print end-of-epoch stats and log them to tensorboard using the print method', 'manage tensorboard SummaryWriter instances with automatic suffix handling to avoid clobbering reruns', 'close all open tensorboard writer instances at program exit using the registered atexit handler', 'create a WandBProgressBarWrapper to log training progress to a Weights and Biases project', 'log intermediate training stats like loss and accuracy to Weights and Biases during training', 'print end-of-epoch stats and log them to Weights and Biases for tracking', 'update the Weights and Biases run configuration with new hyperparameters or settings', 'review the WandBProgressBarWrapper class to understand how it wraps a progress bar and logs to wandb']
```

Usage

```
{'create_base_progress_bar': 'create a BaseProgressBar subclass that implements __iter__, log, and print methods for custom progress tracking', 'format_stat_numbers': 'format a numeric stat value using format_stat to get a compact string representation', 'format_stat_meters': 'format an AverageMeter or TimeMeter stat using format_stat to display its average value', 'format_stat_tensors': 'format a PyTorch tensor stat using format_stat to convert it to a string with 3 significant figures', 'format_stats_postfix': 'use _format_stats on a stats dictionary to produce an OrderedDict of formatted string values'}
```

## File: facebookresearch_metaseq/metaseq/logging/progress_bar/json_progress_bar.py

Prompts

```
['create an AimProgressBarWrapper to log training and validation stats to an Aim repository', 'log intermediate training stats to Aim using the log method with a tag and step', 'print end-of-epoch stats and log them to Aim using the print method', 'update and log the latest configuration parameters to an Aim run using update_config', 'get a cached Aim Run instance by repo path and run hash using get_aim_run', 'create a BaseProgressBar subclass that implements __iter__, log, and print methods for custom progress tracking', 'format a numeric stat value using format_stat to get a compact string representation', 'format an AverageMeter or TimeMeter stat using format_stat to display its average value', 'format a PyTorch tensor stat using format_stat to convert it to a string with 3 significant figures', 'use _format_stats on a stats dictionary to produce an OrderedDict of formatted string values', 'create a JsonProgressBar instance to log training stats in JSON format', 'log intermediate training stats at configured intervals using JsonProgressBar log method', 'print end-of-epoch stats as JSON using JsonProgressBar print method', 'format stats dictionary with epoch and update info using _format_stats method', 'use rename_logger context manager to temporarily change logger name during logging', 'create a TensorboardProgressBarWrapper to log training stats to tensorboard with a specified log directory', 'log intermediate training stats like loss and accuracy to tensorboard using the log method', 'print end-of-epoch stats and log them to tensorboard using the print method', 'manage tensorboard SummaryWriter instances with automatic suffix handling to avoid clobbering reruns', 'close all open tensorboard writer instances at program exit using the registered atexit handler', 'create a WandBProgressBarWrapper to log training progress to a Weights and Biases project', 'log intermediate training stats like loss and accuracy to Weights and Biases during training', 'print end-of-epoch stats and log them to Weights and Biases for tracking', 'update the Weights and Biases run configuration with new hyperparameters or settings', 'review the WandBProgressBarWrapper class to understand how it wraps a progress bar and logs to wandb']
```

Usage

```
{'create_json_progress_bar': 'create a JsonProgressBar instance to log training stats in JSON format', 'log_intermediate_stats': 'log intermediate training stats at configured intervals using JsonProgressBar log method', 'print_epoch_stats': 'print end-of-epoch stats as JSON using JsonProgressBar print method', 'format_stats_with_epoch': 'format stats dictionary with epoch and update info using _format_stats method', 'rename_logger_context': 'use rename_logger context manager to temporarily change logger name during logging'}
```

## File: facebookresearch_metaseq/metaseq/logging/progress_bar/tensorboard_progress_bar.py

Prompts

```
['create an AimProgressBarWrapper to log training and validation stats to an Aim repository', 'log intermediate training stats to Aim using the log method with a tag and step', 'print end-of-epoch stats and log them to Aim using the print method', 'update and log the latest configuration parameters to an Aim run using update_config', 'get a cached Aim Run instance by repo path and run hash using get_aim_run', 'create a BaseProgressBar subclass that implements __iter__, log, and print methods for custom progress tracking', 'format a numeric stat value using format_stat to get a compact string representation', 'format an AverageMeter or TimeMeter stat using format_stat to display its average value', 'format a PyTorch tensor stat using format_stat to convert it to a string with 3 significant figures', 'use _format_stats on a stats dictionary to produce an OrderedDict of formatted string values', 'create a JsonProgressBar instance to log training stats in JSON format', 'log intermediate training stats at configured intervals using JsonProgressBar log method', 'print end-of-epoch stats as JSON using JsonProgressBar print method', 'format stats dictionary with epoch and update info using _format_stats method', 'use rename_logger context manager to temporarily change logger name during logging', 'create a TensorboardProgressBarWrapper to log training stats to tensorboard with a specified log directory', 'log intermediate training stats like loss and accuracy to tensorboard using the log method', 'print end-of-epoch stats and log them to tensorboard using the print method', 'manage tensorboard SummaryWriter instances with automatic suffix handling to avoid clobbering reruns', 'close all open tensorboard writer instances at program exit using the registered atexit handler', 'create a WandBProgressBarWrapper to log training progress to a Weights and Biases project', 'log intermediate training stats like loss and accuracy to Weights and Biases during training', 'print end-of-epoch stats and log them to Weights and Biases for tracking', 'update the Weights and Biases run configuration with new hyperparameters or settings', 'review the WandBProgressBarWrapper class to understand how it wraps a progress bar and logs to wandb']
```

Usage

```
{'create_tensorboard_progress_bar_wrapper': 'create a TensorboardProgressBarWrapper to log training stats to tensorboard with a specified log directory', 'log_stats_to_tensorboard': 'log intermediate training stats like loss and accuracy to tensorboard using the log method', 'print_epoch_stats_to_tensorboard': 'print end-of-epoch stats and log them to tensorboard using the print method', 'manage_tensorboard_writers': 'manage tensorboard SummaryWriter instances with automatic suffix handling to avoid clobbering reruns', 'close_tensorboard_writers': 'close all open tensorboard writer instances at program exit using the registered atexit handler'}
```

## File: facebookresearch_metaseq/metaseq/logging/progress_bar/wandb_progress_bar.py

Prompts

```
['create an AimProgressBarWrapper to log training and validation stats to an Aim repository', 'log intermediate training stats to Aim using the log method with a tag and step', 'print end-of-epoch stats and log them to Aim using the print method', 'update and log the latest configuration parameters to an Aim run using update_config', 'get a cached Aim Run instance by repo path and run hash using get_aim_run', 'create a BaseProgressBar subclass that implements __iter__, log, and print methods for custom progress tracking', 'format a numeric stat value using format_stat to get a compact string representation', 'format an AverageMeter or TimeMeter stat using format_stat to display its average value', 'format a PyTorch tensor stat using format_stat to convert it to a string with 3 significant figures', 'use _format_stats on a stats dictionary to produce an OrderedDict of formatted string values', 'create a JsonProgressBar instance to log training stats in JSON format', 'log intermediate training stats at configured intervals using JsonProgressBar log method', 'print end-of-epoch stats as JSON using JsonProgressBar print method', 'format stats dictionary with epoch and update info using _format_stats method', 'use rename_logger context manager to temporarily change logger name during logging', 'create a TensorboardProgressBarWrapper to log training stats to tensorboard with a specified log directory', 'log intermediate training stats like loss and accuracy to tensorboard using the log method', 'print end-of-epoch stats and log them to tensorboard using the print method', 'manage tensorboard SummaryWriter instances with automatic suffix handling to avoid clobbering reruns', 'close all open tensorboard writer instances at program exit using the registered atexit handler', 'create a WandBProgressBarWrapper to log training progress to a Weights and Biases project', 'log intermediate training stats like loss and accuracy to Weights and Biases during training', 'print end-of-epoch stats and log them to Weights and Biases for tracking', 'update the Weights and Biases run configuration with new hyperparameters or settings', 'review the WandBProgressBarWrapper class to understand how it wraps a progress bar and logs to wandb']
```

Usage

```
{'init_WandBProgressBarWrapper': 'create a WandBProgressBarWrapper to log training progress to a Weights and Biases project', 'log_stats_to_wandb': 'log intermediate training stats like loss and accuracy to Weights and Biases during training', 'print_epoch_stats_to_wandb': 'print end-of-epoch stats and log them to Weights and Biases for tracking', 'update_wandb_config': 'update the Weights and Biases run configuration with new hyperparameters or settings', 'review_WandBProgressBarWrapper': 'review the WandBProgressBarWrapper class to understand how it wraps a progress bar and logs to wandb'}
```

