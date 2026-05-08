# Agent Python Tools

- repo: facebookresearch/hrvit
- repo_uri: https://github.com/facebookresearch/hrvit

## File: facebookresearch_hrvit/checkpoint_saver.py

Prompts

```
['create a CheckpointSaver instance with a model, optimizer, and checkpoint directory for saving training checkpoints', 'save a model checkpoint at a given epoch with an optional metric for tracking best performance', 'save a recovery checkpoint at a given epoch and batch index for resuming interrupted training', 'find the earliest recovery checkpoint file in the recovery directory to resume training', 'cleanup old checkpoint files beyond the max_history limit to free disk space', 'create an McDataset instance from a data root and file list for ImageNet training', 'load an image file from a filepath and convert it to RGB format', 'get an image and its label by index from the McDataset with fallback retry', 'load an image by index from McDataset applying optional transforms and returning the label', 'review the McDataset class and its Dataset inheritance for PyTorch data loading patterns', 'run the HRViT model training loop with distributed DDP across multiple GPUs using argparse CLI', 'run the HRViT model evaluation on a checkpoint using --eval_checkpoint to print top-1 accuracy', 'resume HRViT training from a saved checkpoint with optimizer state using the --resume flag', 'run HRViT training with a YAML config file via the -c flag to override default arguments', 'run HRViT training with model exponential moving average enabled using the --model-ema flag']
```

Usage

```
{'create_CheckpointSaver': 'create a CheckpointSaver instance with a model, optimizer, and checkpoint directory for saving training checkpoints', 'save_checkpoint_method': 'save a model checkpoint at a given epoch with an optional metric for tracking best performance', 'save_recovery_method': 'save a recovery checkpoint at a given epoch and batch index for resuming interrupted training', 'find_recovery_method': 'find the earliest recovery checkpoint file in the recovery directory to resume training', 'cleanup_checkpoints_method': 'cleanup old checkpoint files beyond the max_history limit to free disk space'}
```

## File: facebookresearch_hrvit/labeled_memcached_dataset.py

Prompts

```
['create a CheckpointSaver instance with a model, optimizer, and checkpoint directory for saving training checkpoints', 'save a model checkpoint at a given epoch with an optional metric for tracking best performance', 'save a recovery checkpoint at a given epoch and batch index for resuming interrupted training', 'find the earliest recovery checkpoint file in the recovery directory to resume training', 'cleanup old checkpoint files beyond the max_history limit to free disk space', 'create an McDataset instance from a data root and file list for ImageNet training', 'load an image file from a filepath and convert it to RGB format', 'get an image and its label by index from the McDataset with fallback retry', 'load an image by index from McDataset applying optional transforms and returning the label', 'review the McDataset class and its Dataset inheritance for PyTorch data loading patterns', 'run the HRViT model training loop with distributed DDP across multiple GPUs using argparse CLI', 'run the HRViT model evaluation on a checkpoint using --eval_checkpoint to print top-1 accuracy', 'resume HRViT training from a saved checkpoint with optimizer state using the --resume flag', 'run HRViT training with a YAML config file via the -c flag to override default arguments', 'run HRViT training with model exponential moving average enabled using the --model-ema flag']
```

Usage

```
{'create_McDataset': 'create an McDataset instance from a data root and file list for ImageNet training', 'load_img_function': 'load an image file from a filepath and convert it to RGB format', 'getitem_McDataset': 'get an image and its label by index from the McDataset with fallback retry', 'load_img_McDataset_method': 'load an image by index from McDataset applying optional transforms and returning the label', 'review_McDataset_class': 'review the McDataset class and its Dataset inheritance for PyTorch data loading patterns'}
```

## File: facebookresearch_hrvit/pretrain.py

Prompts

```
['create a CheckpointSaver instance with a model, optimizer, and checkpoint directory for saving training checkpoints', 'save a model checkpoint at a given epoch with an optional metric for tracking best performance', 'save a recovery checkpoint at a given epoch and batch index for resuming interrupted training', 'find the earliest recovery checkpoint file in the recovery directory to resume training', 'cleanup old checkpoint files beyond the max_history limit to free disk space', 'create an McDataset instance from a data root and file list for ImageNet training', 'load an image file from a filepath and convert it to RGB format', 'get an image and its label by index from the McDataset with fallback retry', 'load an image by index from McDataset applying optional transforms and returning the label', 'review the McDataset class and its Dataset inheritance for PyTorch data loading patterns', 'run the HRViT model training loop with distributed DDP across multiple GPUs using argparse CLI', 'run the HRViT model evaluation on a checkpoint using --eval_checkpoint to print top-1 accuracy', 'resume HRViT training from a saved checkpoint with optimizer state using the --resume flag', 'run HRViT training with a YAML config file via the -c flag to override default arguments', 'run HRViT training with model exponential moving average enabled using the --model-ema flag']
```

Usage

```
{'run_HRViT_training': 'run the HRViT model training loop with distributed DDP across multiple GPUs using argparse CLI', 'run_HRViT_evaluation': 'run the HRViT model evaluation on a checkpoint using --eval_checkpoint to print top-1 accuracy', 'run_HRViT_resume': 'resume HRViT training from a saved checkpoint with optimizer state using the --resume flag', 'run_HRViT_config': 'run HRViT training with a YAML config file via the -c flag to override default arguments', 'run_HRViT_ema': 'run HRViT training with model exponential moving average enabled using the --model-ema flag'}
```

