# Agent Python Tools

- repo: facebookresearch/flowmatching
- repo_uri: https://github.com/facebookresearch/flow_matching

## File: facebookresearch_flowmatching/examples/text/utils/checkpointing.py

Prompts

```
['load an OmegaConf configuration from a Hydra config.yaml file given a work directory path', 'load a Transformer model wrapped in DDP from a checkpoint file using a given config and vocab size', 'get a WorkDirectory dataclass with paths for samples and checkpoints and create directories for rank 0', 'review the WorkDirectory dataclass that holds root, checkpoint, and samples Path fields with metadata', 'summarize the load_model_from_path function that constructs a Transformer, wraps it in DDP, and loads weights', 'create a TrainLogger instance with a log directory, rank, and config for training runs', 'log a metric value with name, stage, and step to both text and wandb loggers', 'log the current learning rate value to wandb at a given training step', 'get a configured logger with file and console handlers for a given log path and rank', 'log available CUDA device names, memory, and CPU count to a logger']
```

Usage

```
{'load_cfg_from_path': 'load an OmegaConf configuration from a Hydra config.yaml file given a work directory path', 'load_model_from_path': 'load a Transformer model wrapped in DDP from a checkpoint file using a given config and vocab size', 'get_work_dirs': 'get a WorkDirectory dataclass with paths for samples and checkpoints and create directories for rank 0', 'review_WorkDirectory': 'review the WorkDirectory dataclass that holds root, checkpoint, and samples Path fields with metadata', 'summarize_load_model_from_path': 'summarize the load_model_from_path function that constructs a Transformer, wraps it in DDP, and loads weights'}
```

## File: facebookresearch_flowmatching/examples/text/utils/logging.py

Prompts

```
['load an OmegaConf configuration from a Hydra config.yaml file given a work directory path', 'load a Transformer model wrapped in DDP from a checkpoint file using a given config and vocab size', 'get a WorkDirectory dataclass with paths for samples and checkpoints and create directories for rank 0', 'review the WorkDirectory dataclass that holds root, checkpoint, and samples Path fields with metadata', 'summarize the load_model_from_path function that constructs a Transformer, wraps it in DDP, and loads weights', 'create a TrainLogger instance with a log directory, rank, and config for training runs', 'log a metric value with name, stage, and step to both text and wandb loggers', 'log the current learning rate value to wandb at a given training step', 'get a configured logger with file and console handlers for a given log path and rank', 'log available CUDA device names, memory, and CPU count to a logger']
```

Usage

```
{'create_train_logger': 'create a TrainLogger instance with a log directory, rank, and config for training runs', 'log_metric_value': 'log a metric value with name, stage, and step to both text and wandb loggers', 'log_learning_rate': 'log the current learning rate value to wandb at a given training step', 'get_logger_with_handlers': 'get a configured logger with file and console handlers for a given log path and rank', 'log_gpu_devices': 'log available CUDA device names, memory, and CPU count to a logger'}
```

