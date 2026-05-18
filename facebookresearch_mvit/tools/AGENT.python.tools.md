# Agent Python Tools

- repo: facebookresearch/mvit
- repo_uri: https://github.com/facebookresearch/mvit

## File: facebookresearch_mvit/tools/engine.py

Prompts

```
['run the train function to train an MViT model on a dataset using the provided config', 'run the test function to evaluate a pretrained MViT model on a test set', 'run the train_epoch function to perform one epoch of training with mixed precision and mixup support', 'run the eval_epoch function to evaluate the model on a validation set and compute top1 and top5 errors', 'review the train function which orchestrates distributed training with checkpointing, evaluation, and epoch timing', 'run the MVIT model training pipeline using a config YAML file and distributed shard arguments', 'run the MVIT model testing pipeline using a config YAML file and distributed shard arguments', 'run the main entry point to launch training or testing based on config flags', 'parse command line arguments for shard ID, number of shards, init method, config file, and opts', 'load and initialize MVIT configuration from a YAML file and override with command line opts']
```

Usage

```
{'run_train': 'run the train function to train an MViT model on a dataset using the provided config', 'run_test': 'run the test function to evaluate a pretrained MViT model on a test set', 'run_train_epoch': 'run the train_epoch function to perform one epoch of training with mixed precision and mixup support', 'run_eval_epoch': 'run the eval_epoch function to evaluate the model on a validation set and compute top1 and top5 errors', 'review_train': 'review the train function which orchestrates distributed training with checkpointing, evaluation, and epoch timing'}
```

## File: facebookresearch_mvit/tools/main.py

Prompts

```
['run the train function to train an MViT model on a dataset using the provided config', 'run the test function to evaluate a pretrained MViT model on a test set', 'run the train_epoch function to perform one epoch of training with mixed precision and mixup support', 'run the eval_epoch function to evaluate the model on a validation set and compute top1 and top5 errors', 'review the train function which orchestrates distributed training with checkpointing, evaluation, and epoch timing', 'run the MVIT model training pipeline using a config YAML file and distributed shard arguments', 'run the MVIT model testing pipeline using a config YAML file and distributed shard arguments', 'run the main entry point to launch training or testing based on config flags', 'parse command line arguments for shard ID, number of shards, init method, config file, and opts', 'load and initialize MVIT configuration from a YAML file and override with command line opts']
```

Usage

```
{'run_train_mvit_model': 'run the MVIT model training pipeline using a config YAML file and distributed shard arguments', 'run_test_mvit_model': 'run the MVIT model testing pipeline using a config YAML file and distributed shard arguments', 'run_mvit_main_entry': 'run the main entry point to launch training or testing based on config flags', 'parse_args_mvit_cli': 'parse command line arguments for shard ID, number of shards, init method, config file, and opts', 'load_config_mvit': 'load and initialize MVIT configuration from a YAML file and override with command line opts'}
```

