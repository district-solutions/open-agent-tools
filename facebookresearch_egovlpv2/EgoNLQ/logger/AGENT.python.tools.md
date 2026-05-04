# Agent Python Tools

- repo: facebookresearch/egovlpv2
- repo_uri: https://github.com/facebookresearch/egovlpv2

## File: facebookresearch_egovlpv2/EgoNLQ/logger/logger.py

Prompts

```
['setup logging using a JSON config file with console and rotating file handlers for a given save directory', 'setup logging with a default log level when the config file is missing', 'setup logging by pointing to a custom logger_config.json path and save directory', 'review the setup_logging function to understand how it resolves handler filenames relative to save_dir', 'refactor setup_logging to validate the JSON config before applying dictConfig', 'create a TensorboardWriter instance with a log directory, logger, and enabled flag', 'call set_step on TensorboardWriter to set the current step and train or valid mode', 'use TensorboardWriter add_scalar to log a scalar value with auto mode tagging', 'use TensorboardWriter add_image to log an image tensor with auto step and mode tagging', 'review TensorboardWriter __getattr__ which proxies TensorBoard methods like add_histogram and add_embedding']
```

Usage

```
{'setup_logging_with_config': 'setup logging using a JSON config file with console and rotating file handlers for a given save directory', 'setup_logging_default_level': 'setup logging with a default log level when the config file is missing', 'setup_logging_custom_config_path': 'setup logging by pointing to a custom logger_config.json path and save directory', 'review_setup_logging': 'review the setup_logging function to understand how it resolves handler filenames relative to save_dir', 'refactor_setup_logging': 'refactor setup_logging to validate the JSON config before applying dictConfig'}
```

## File: facebookresearch_egovlpv2/EgoNLQ/logger/visualization.py

Prompts

```
['setup logging using a JSON config file with console and rotating file handlers for a given save directory', 'setup logging with a default log level when the config file is missing', 'setup logging by pointing to a custom logger_config.json path and save directory', 'review the setup_logging function to understand how it resolves handler filenames relative to save_dir', 'refactor setup_logging to validate the JSON config before applying dictConfig', 'create a TensorboardWriter instance with a log directory, logger, and enabled flag', 'call set_step on TensorboardWriter to set the current step and train or valid mode', 'use TensorboardWriter add_scalar to log a scalar value with auto mode tagging', 'use TensorboardWriter add_image to log an image tensor with auto step and mode tagging', 'review TensorboardWriter __getattr__ which proxies TensorBoard methods like add_histogram and add_embedding']
```

Usage

```
{'create_tensorboard_writer': 'create a TensorboardWriter instance with a log directory, logger, and enabled flag', 'set_training_step': 'call set_step on TensorboardWriter to set the current step and train or valid mode', 'add_scalar_to_tensorboard': 'use TensorboardWriter add_scalar to log a scalar value with auto mode tagging', 'add_image_to_tensorboard': 'use TensorboardWriter add_image to log an image tensor with auto step and mode tagging', 'review_tensorboardwriter_getattr': 'review TensorboardWriter __getattr__ which proxies TensorBoard methods like add_histogram and add_embedding'}
```

