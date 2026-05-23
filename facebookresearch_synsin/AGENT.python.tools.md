# Agent Python Tools

- repo: facebookresearch/synsin
- repo_uri: https://github.com/facebookresearch/synsin

## File: facebookresearch_synsin/train.py

Prompts

```
['run the training loop for a specified number of epochs with a given model and dataset', 'run the validation loop to evaluate model performance and compute PSNR loss metrics', 'save a model checkpoint with optimizer states and epoch info to a specified path', 'resume training from a saved checkpoint file and continue from the last epoch', 'handle SLURM SIGUSR1 signals to trigger job requeue and graceful checkpointing']
```

Usage

```
{'run_training_loop': 'run the training loop for a specified number of epochs with a given model and dataset', 'run_validation': 'run the validation loop to evaluate model performance and compute PSNR loss metrics', 'save_checkpoint': 'save a model checkpoint with optimizer states and epoch info to a specified path', 'resume_training': 'resume training from a saved checkpoint file and continue from the last epoch', 'handle_slurm_signals': 'handle SLURM SIGUSR1 signals to trigger job requeue and graceful checkpointing'}
```

