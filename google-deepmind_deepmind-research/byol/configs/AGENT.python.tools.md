# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/byol/configs/byol.py

Prompts

```
['get a BYOL training config dict with hyperparameters for a given number of epochs and batch size', 'review the get_config function to understand BYOL hyperparameter defaults for ResNet50 encoder training', 'summarize the learning rate preset values mapped to epoch counts 40, 100, 300, and 1000', 'summarize the EMA decay preset values mapped to epoch counts 40, 100, 300, and 1000', 'build a python argparse cli module that calls get_config with num_epochs and batch_size arguments', 'build a config dict for linear evaluation of a BYOL checkpoint with ResNet50 encoder', 'build a config dict for fine-tuning a BYOL checkpoint by setting freeze_backbone to False', 'run get_config with a checkpoint path and batch size to produce an evaluation config', 'summarize the get_config function which returns a BYOL linear evaluation configuration dictionary']
```

Usage

```
{'get_byol_config': 'get a BYOL training config dict with hyperparameters for a given number of epochs and batch size', 'review_get_config': 'review the get_config function to understand BYOL hyperparameter defaults for ResNet50 encoder training', 'summarize_lr_presets': 'summarize the learning rate preset values mapped to epoch counts 40, 100, 300, and 1000', 'summarize_ema_presets': 'summarize the EMA decay preset values mapped to epoch counts 40, 100, 300, and 1000', 'build_byol_cli': 'build a python argparse cli module that calls get_config with num_epochs and batch_size arguments'}
```

## File: google-deepmind_deepmind-research/byol/configs/eval.py

Prompts

```
['get a BYOL training config dict with hyperparameters for a given number of epochs and batch size', 'review the get_config function to understand BYOL hyperparameter defaults for ResNet50 encoder training', 'summarize the learning rate preset values mapped to epoch counts 40, 100, 300, and 1000', 'summarize the EMA decay preset values mapped to epoch counts 40, 100, 300, and 1000', 'build a python argparse cli module that calls get_config with num_epochs and batch_size arguments', 'build a config dict for linear evaluation of a BYOL checkpoint with ResNet50 encoder', 'build a config dict for fine-tuning a BYOL checkpoint by setting freeze_backbone to False', 'run get_config with a checkpoint path and batch size to produce an evaluation config', 'summarize the get_config function which returns a BYOL linear evaluation configuration dictionary']
```

Usage

```
{'build_config_linear_eval': 'build a config dict for linear evaluation of a BYOL checkpoint with ResNet50 encoder', 'build_config_finetune': 'build a config dict for fine-tuning a BYOL checkpoint by setting freeze_backbone to False', 'run_get_config': 'run get_config with a checkpoint path and batch size to produce an evaluation config', 'review_get_config': 'review the get_config function to verify optimizer and learning rate schedule settings', 'summarize_get_config': 'summarize the get_config function which returns a BYOL linear evaluation configuration dictionary'}
```

