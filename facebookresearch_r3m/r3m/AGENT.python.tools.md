# Agent Python Tools

- repo: facebookresearch/r3m
- repo_uri: https://github.com/facebookresearch/r3m

## File: facebookresearch_r3m/r3m/train_representation.py

Prompts

```
['run the main training loop for R3M representation learning on the ego4d dataset using hydra config', 'create a Workspace instance that sets up dataloaders, initializes the model, and prepares the training environment', 'run the Workspace train method to execute the training loop with periodic evaluation and snapshot saving', 'create a DataParallel model from a hydra config and move it to the GPU for training', 'review the Workspace save_snapshot method that persists the model state dict and global step to disk', 'run a training step on the R3M model using the Trainer update method with a batch', 'run an evaluation step on the R3M model using Trainer update with eval set to true', 'review the Trainer update method to understand how LP, language, and TCN losses are computed', 'refactor the Trainer update method to use a context manager for timing instead of manual timestamps', 'summarize the Trainer update method which computes L1/L2/L0 norm losses, InfoNCE language loss, and TCN temporal consistency loss']
```

Usage

```
{'run_train_representation_main': 'run the main training loop for R3M representation learning on the ego4d dataset using hydra config', 'create_workspace': 'create a Workspace instance that sets up dataloaders, initializes the model, and prepares the training environment', 'run_workspace_train': 'run the Workspace train method to execute the training loop with periodic evaluation and snapshot saving', 'create_make_network': 'create a DataParallel model from a hydra config and move it to the GPU for training', 'review_workspace_save_snapshot': 'review the Workspace save_snapshot method that persists the model state dict and global step to disk'}
```

## File: facebookresearch_r3m/r3m/trainer.py

Prompts

```
['run the main training loop for R3M representation learning on the ego4d dataset using hydra config', 'create a Workspace instance that sets up dataloaders, initializes the model, and prepares the training environment', 'run the Workspace train method to execute the training loop with periodic evaluation and snapshot saving', 'create a DataParallel model from a hydra config and move it to the GPU for training', 'review the Workspace save_snapshot method that persists the model state dict and global step to disk', 'run a training step on the R3M model using the Trainer update method with a batch', 'run an evaluation step on the R3M model using Trainer update with eval set to true', 'review the Trainer update method to understand how LP, language, and TCN losses are computed', 'refactor the Trainer update method to use a context manager for timing instead of manual timestamps', 'summarize the Trainer update method which computes L1/L2/L0 norm losses, InfoNCE language loss, and TCN temporal consistency loss']
```

Usage

```
{'run_Trainer_update': 'run a training step on the R3M model using the Trainer update method with a batch', 'run_Trainer_eval': 'run an evaluation step on the R3M model using Trainer update with eval set to true', 'review_Trainer_update_loss': 'review the Trainer update method to understand how LP, language, and TCN losses are computed', 'refactor_Trainer_update_timing': 'refactor the Trainer update method to use a context manager for timing instead of manual timestamps', 'summarize_Trainer_update': 'summarize the Trainer update method which computes L1/L2/L0 norm losses, InfoNCE language loss, and TCN temporal consistency loss'}
```

