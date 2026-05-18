# Agent Python Tools

- repo: facebookresearch/metaclip
- repo_uri: https://github.com/facebookresearch/metaclip

## File: facebookresearch_metaclip/apps/mode/move2root/configs_mode.py

Prompts

```
['create a Config dataclass instance with training hyperparameters and model settings for MetaCLIP mode training', 'review the Config __post_init__ method that auto-fills default params and resolves data paths for mode configs', 'run parse_start_end to extract start and end shard indices from a glob-style shard path string', 'run search_config to dynamically discover and instantiate a named config class from run_configs modules', 'refactor the Config dataclass to add or modify default hyperparameter values for training runs', 'submit a multinode training job to a SLURM cluster using submitit with GPU and node configuration', 'run the Trainer callable to set up GPU args and start training via training.main', 'checkpoint the Trainer and requeue a DelayedSubmission to resume training from the latest epoch checkpoint', 'parse command line arguments for config name, GPUs, nodes, timeout, partition, and scheduler comment', 'get a unique initialization file URI for distributed training process group coordination']
```

Usage

```
{'create_Config_dataclass': 'create a Config dataclass instance with training hyperparameters and model settings for MetaCLIP mode training', 'review_Config_post_init': 'review the Config __post_init__ method that auto-fills default params and resolves data paths for mode configs', 'run_parse_start_end': 'run parse_start_end to extract start and end shard indices from a glob-style shard path string', 'run_search_config': 'run search_config to dynamically discover and instantiate a named config class from run_configs modules', 'refactor_Config_defaults': 'refactor the Config dataclass to add or modify default hyperparameter values for training runs'}
```

## File: facebookresearch_metaclip/apps/mode/move2root/submitit_mode.py

Prompts

```
['create a Config dataclass instance with training hyperparameters and model settings for MetaCLIP mode training', 'review the Config __post_init__ method that auto-fills default params and resolves data paths for mode configs', 'run parse_start_end to extract start and end shard indices from a glob-style shard path string', 'run search_config to dynamically discover and instantiate a named config class from run_configs modules', 'refactor the Config dataclass to add or modify default hyperparameter values for training runs', 'submit a multinode training job to a SLURM cluster using submitit with GPU and node configuration', 'run the Trainer callable to set up GPU args and start training via training.main', 'checkpoint the Trainer and requeue a DelayedSubmission to resume training from the latest epoch checkpoint', 'parse command line arguments for config name, GPUs, nodes, timeout, partition, and scheduler comment', 'get a unique initialization file URI for distributed training process group coordination']
```

Usage

```
{'submit_multinode_training_job': 'submit a multinode training job to a SLURM cluster using submitit with GPU and node configuration', 'run_trainer_call': 'run the Trainer callable to set up GPU args and start training via training.main', 'checkpoint_trainer_requeue': 'checkpoint the Trainer and requeue a DelayedSubmission to resume training from the latest epoch checkpoint', 'parse_args_submitit': 'parse command line arguments for config name, GPUs, nodes, timeout, partition, and scheduler comment', 'get_init_file_dist_url': 'get a unique initialization file URI for distributed training process group coordination'}
```

