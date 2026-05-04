# Agent Python Tools

- repo: facebookresearch/flashy
- repo_uri: https://github.com/facebookresearch/flashy

## File: facebookresearch_flashy/flashy/loggers/base.py

Prompts

```
['implement a subclass of ExperimentLogger that provides concrete logging methods for hyperparams, metrics, audio, image, and text', 'log experiment hyperparameters as a dictionary or argparse Namespace with optional final metrics to the ExperimentLogger', 'log a dictionary of metrics with optional name prefixes and step numbers to the ExperimentLogger', 'log an audio tensor with a key, sample rate, and optional step number to the ExperimentLogger', 'log an image tensor with a key and optional step number to the ExperimentLogger', 'create a LocalFSLogger instance to log experiment data to a local filesystem directory', 'log text messages as TXT files using the LocalFSLogger log_text method', 'create a TensorboardLogger instance with a save directory and optional media logging flag', 'log audio tensors, image tensors, or text strings to Tensorboard with step tracking', 'create a TensorboardLogger from the current dora experiment folder with optional sub directory', 'create a WandbLogger instance with a save directory, project name, and optional resume flag']
```

Usage

```
{'implement_ExperimentLogger_subclass': 'implement a subclass of ExperimentLogger that provides concrete logging methods for hyperparams, metrics, audio, image, and text', 'log_hyperparams': 'log experiment hyperparameters as a dictionary or argparse Namespace with optional final metrics to the ExperimentLogger', 'log_metrics': 'log a dictionary of metrics with optional name prefixes and step numbers to the ExperimentLogger', 'log_audio': 'log an audio tensor with a key, sample rate, and optional step number to the ExperimentLogger', 'log_image': 'log an image tensor with a key and optional step number to the ExperimentLogger'}
```

## File: facebookresearch_flashy/flashy/loggers/localfs.py

Prompts

```
['implement a subclass of ExperimentLogger that provides concrete logging methods for hyperparams, metrics, audio, image, and text', 'log experiment hyperparameters as a dictionary or argparse Namespace with optional final metrics to the ExperimentLogger', 'log a dictionary of metrics with optional name prefixes and step numbers to the ExperimentLogger', 'log an audio tensor with a key, sample rate, and optional step number to the ExperimentLogger', 'log an image tensor with a key and optional step number to the ExperimentLogger', 'create a LocalFSLogger instance to log experiment data to a local filesystem directory', 'log text messages as TXT files using the LocalFSLogger log_text method', 'create a TensorboardLogger instance with a save directory and optional media logging flag', 'log audio tensors, image tensors, or text strings to Tensorboard with step tracking', 'create a TensorboardLogger from the current dora experiment folder with optional sub directory', 'create a WandbLogger instance with a save directory, project name, and optional resume flag']
```

Usage

```
{'create_localfs_logger': 'create a LocalFSLogger instance to log experiment data to a local filesystem directory', 'log_hyperparams': 'log experiment hyperparameters as a JSON file using the LocalFSLogger log_hyperparams method', 'log_audio': 'log audio waveforms as WAV files using the LocalFSLogger log_audio method with torchaudio', 'log_image': 'log images as PNG files using the LocalFSLogger log_image method with torchvision', 'log_text': 'log text messages as TXT files using the LocalFSLogger log_text method'}
```

## File: facebookresearch_flashy/flashy/loggers/tensorboard.py

Prompts

```
['implement a subclass of ExperimentLogger that provides concrete logging methods for hyperparams, metrics, audio, image, and text', 'log experiment hyperparameters as a dictionary or argparse Namespace with optional final metrics to the ExperimentLogger', 'log a dictionary of metrics with optional name prefixes and step numbers to the ExperimentLogger', 'log an audio tensor with a key, sample rate, and optional step number to the ExperimentLogger', 'log an image tensor with a key and optional step number to the ExperimentLogger', 'create a LocalFSLogger instance to log experiment data to a local filesystem directory', 'log text messages as TXT files using the LocalFSLogger log_text method', 'create a TensorboardLogger instance with a save directory and optional media logging flag', 'log audio tensors, image tensors, or text strings to Tensorboard with step tracking', 'create a TensorboardLogger from the current dora experiment folder with optional sub directory', 'create a WandbLogger instance with a save directory, project name, and optional resume flag']
```

Usage

```
{'create_tensorboard_logger': 'create a TensorboardLogger instance with a save directory and optional media logging flag', 'log_hyperparams': 'log experiment hyperparameters and optional metrics to the Tensorboard SummaryWriter', 'log_metrics': 'log scalar metrics with optional prefix and step number to Tensorboard', 'log_audio_image_text': 'log audio tensors, image tensors, or text strings to Tensorboard with step tracking', 'from_xp': 'create a TensorboardLogger from the current dora experiment folder with optional sub directory'}
```

## File: facebookresearch_flashy/flashy/loggers/wandb.py

Prompts

```
['implement a subclass of ExperimentLogger that provides concrete logging methods for hyperparams, metrics, audio, image, and text', 'log experiment hyperparameters as a dictionary or argparse Namespace with optional final metrics to the ExperimentLogger', 'log a dictionary of metrics with optional name prefixes and step numbers to the ExperimentLogger', 'log an audio tensor with a key, sample rate, and optional step number to the ExperimentLogger', 'log an image tensor with a key and optional step number to the ExperimentLogger', 'create a LocalFSLogger instance to log experiment data to a local filesystem directory', 'log text messages as TXT files using the LocalFSLogger log_text method', 'create a TensorboardLogger instance with a save directory and optional media logging flag', 'log audio tensors, image tensors, or text strings to Tensorboard with step tracking', 'create a TensorboardLogger from the current dora experiment folder with optional sub directory', 'create a WandbLogger instance with a save directory, project name, and optional resume flag']
```

Usage

```
{'init_WandbLogger': 'create a WandbLogger instance with a save directory, project name, and optional resume flag', 'log_hyperparams': 'log experiment hyperparameters as a dictionary or argparse Namespace into the wandb run config', 'log_metrics': 'log a dictionary of metrics with optional prefix and step number to wandb', 'log_audio': 'log a torch tensor audio clip with sample rate to wandb as a wandb.Audio object', 'from_xp': 'create a WandbLogger from a dora experiment context with automatic resume and config detection'}
```

