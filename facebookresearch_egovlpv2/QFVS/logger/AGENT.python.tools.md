# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/QFVS/logger/logger.py

Prompts

```
['setup logging using a JSON config file and a custom save directory for log output', 'setup logging with a default log level when no config file is available', 'setup logging by pointing to a custom log_config JSON path and save directory', 'review the setup_logging function to understand how it rewrites handler filenames based on save_dir', 'refactor setup_logging to support additional handler configuration options beyond filename rewriting', 'create a TensorboardWriter instance with a log directory, logger, and enabled flag for experiment logging', 'call set_step on TensorboardWriter to set the training step and mode for logging', 'use TensorboardWriter add_scalar to log scalar values like loss or accuracy to Tensorboard', 'use TensorboardWriter add_image to log image data with tags and steps to Tensorboard', 'review the TensorboardWriter __getattr__ method that proxies Tensorboard writer calls with automatic step and mode tagging']
```

Usage

```
{'setup_logging_with_config': 'setup logging using a JSON config file and a custom save directory for log output', 'setup_logging_default_level': 'setup logging with a default log level when no config file is available', 'setup_logging_custom_config_path': 'setup logging by pointing to a custom log_config JSON path and save directory', 'review_setup_logging': 'review the setup_logging function to understand how it rewrites handler filenames based on save_dir', 'refactor_setup_logging': 'refactor setup_logging to support additional handler configuration options beyond filename rewriting'}
```

## File: facebookresearch_egovlpv2/QFVS/logger/visualization.py

Prompts

```
['setup logging using a JSON config file and a custom save directory for log output', 'setup logging with a default log level when no config file is available', 'setup logging by pointing to a custom log_config JSON path and save directory', 'review the setup_logging function to understand how it rewrites handler filenames based on save_dir', 'refactor setup_logging to support additional handler configuration options beyond filename rewriting', 'create a TensorboardWriter instance with a log directory, logger, and enabled flag for experiment logging', 'call set_step on TensorboardWriter to set the training step and mode for logging', 'use TensorboardWriter add_scalar to log scalar values like loss or accuracy to Tensorboard', 'use TensorboardWriter add_image to log image data with tags and steps to Tensorboard', 'review the TensorboardWriter __getattr__ method that proxies Tensorboard writer calls with automatic step and mode tagging']
```

Usage

```
{'create_tensorboardwriter': 'create a TensorboardWriter instance with a log directory, logger, and enabled flag for experiment logging', 'set_step_train_mode': 'call set_step on TensorboardWriter to set the training step and mode for logging', 'add_scalar_to_tensorboard': 'use TensorboardWriter add_scalar to log scalar values like loss or accuracy to Tensorboard', 'add_image_to_tensorboard': 'use TensorboardWriter add_image to log image data with tags and steps to Tensorboard', 'review_tensorboardwriter_getattr': 'review the TensorboardWriter __getattr__ method that proxies Tensorboard writer calls with automatic step and mode tagging'}
```

