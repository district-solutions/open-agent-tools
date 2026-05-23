# Agent Python Tools

- repo: facebookresearch/pixio
- repo_uri: https://github.com/facebookresearch/pixio

## File: facebookresearch_pixio/pretraining/engine_pretrain.py

Prompts

```
['run one epoch of model pretraining with gradient accumulation and mixed precision support', 'build a pretraining loop that trains a model for one epoch using a data loader and optimizer', 'test the train_one_epoch function to verify it returns averaged loss and learning rate metrics', 'refactor the train_one_epoch function to support configurable dtype options like bf16, fp16, or fp32', 'review the train_one_epoch function and its wandb logging of train loss, learning rate, and epoch progress', 'run the Pixio pre-training script with argparse CLI to train a vision transformer model on ImageNet or WebDataset', 'run distributed multi-GPU training for Pixio with configurable batch size, learning rate, and gradient accumulation', 'resume Pixio pre-training from a saved checkpoint with the --resume flag and --start_epoch', 'run Pixio pre-training on WebDataset with tar-based image data and epoch-based shuffling', 'run Pixio pre-training on ImageNet with configurable masking ratio, mask grid, and class tokens', 'build a PixioViT encoder-decoder model for masked image pre-training with configurable patch size and depth', 'create a Pixio ViT-H/16 model with 1280-dim encoder and 512-dim decoder using the pixio_vith16 factory function', 'create a Pixio ViT-1B model with 1536-dim encoder and 48 transformer blocks using the pixio_vit1b factory function', 'create a Pixio ViT-5B model with 3072-dim encoder and 32 attention heads using the pixio_vit5b factory function', 'run the PixioViT forward pass to reconstruct masked image patches and compute masked MSE loss', 'run a multinode Pixio pre-training job on a Slurm cluster using submitit', 'submit a Trainer instance to a submitit AutoExecutor for distributed GPU training', 'parse command-line arguments for Slurm job parameters like nodes, GPUs, partition, and timeout', 'checkpoint and requeue a Trainer job by returning a DelayedSubmission with a fresh init file', 'setup GPU rank, world size, and output directory from the submitit JobEnvironment']
```

Usage

```
{'run_train_one_epoch': 'run one epoch of model pretraining with gradient accumulation and mixed precision support', 'build_pretraining_loop': 'build a pretraining loop that trains a model for one epoch using a data loader and optimizer', 'test_train_one_epoch_loss': 'test the train_one_epoch function to verify it returns averaged loss and learning rate metrics', 'refactor_train_one_epoch_autocast': 'refactor the train_one_epoch function to support configurable dtype options like bf16, fp16, or fp32', 'review_train_one_epoch_logging': 'review the train_one_epoch function and its wandb logging of train loss, learning rate, and epoch progress'}
```

## File: facebookresearch_pixio/pretraining/main_pretrain.py

Prompts

```
['run one epoch of model pretraining with gradient accumulation and mixed precision support', 'build a pretraining loop that trains a model for one epoch using a data loader and optimizer', 'test the train_one_epoch function to verify it returns averaged loss and learning rate metrics', 'refactor the train_one_epoch function to support configurable dtype options like bf16, fp16, or fp32', 'review the train_one_epoch function and its wandb logging of train loss, learning rate, and epoch progress', 'run the Pixio pre-training script with argparse CLI to train a vision transformer model on ImageNet or WebDataset', 'run distributed multi-GPU training for Pixio with configurable batch size, learning rate, and gradient accumulation', 'resume Pixio pre-training from a saved checkpoint with the --resume flag and --start_epoch', 'run Pixio pre-training on WebDataset with tar-based image data and epoch-based shuffling', 'run Pixio pre-training on ImageNet with configurable masking ratio, mask grid, and class tokens', 'build a PixioViT encoder-decoder model for masked image pre-training with configurable patch size and depth', 'create a Pixio ViT-H/16 model with 1280-dim encoder and 512-dim decoder using the pixio_vith16 factory function', 'create a Pixio ViT-1B model with 1536-dim encoder and 48 transformer blocks using the pixio_vit1b factory function', 'create a Pixio ViT-5B model with 3072-dim encoder and 32 attention heads using the pixio_vit5b factory function', 'run the PixioViT forward pass to reconstruct masked image patches and compute masked MSE loss', 'run a multinode Pixio pre-training job on a Slurm cluster using submitit', 'submit a Trainer instance to a submitit AutoExecutor for distributed GPU training', 'parse command-line arguments for Slurm job parameters like nodes, GPUs, partition, and timeout', 'checkpoint and requeue a Trainer job by returning a DelayedSubmission with a fresh init file', 'setup GPU rank, world size, and output directory from the submitit JobEnvironment']
```

Usage

```
{'run_pixio_pretraining': 'run the Pixio pre-training script with argparse CLI to train a vision transformer model on ImageNet or WebDataset', 'run_distributed_training': 'run distributed multi-GPU training for Pixio with configurable batch size, learning rate, and gradient accumulation', 'run_resumed_training': 'resume Pixio pre-training from a saved checkpoint with the --resume flag and --start_epoch', 'run_webdataset_training': 'run Pixio pre-training on WebDataset with tar-based image data and epoch-based shuffling', 'run_imagenet_pretraining': 'run Pixio pre-training on ImageNet with configurable masking ratio, mask grid, and class tokens'}
```

## File: facebookresearch_pixio/pretraining/models_pixio.py

Prompts

```
['run one epoch of model pretraining with gradient accumulation and mixed precision support', 'build a pretraining loop that trains a model for one epoch using a data loader and optimizer', 'test the train_one_epoch function to verify it returns averaged loss and learning rate metrics', 'refactor the train_one_epoch function to support configurable dtype options like bf16, fp16, or fp32', 'review the train_one_epoch function and its wandb logging of train loss, learning rate, and epoch progress', 'run the Pixio pre-training script with argparse CLI to train a vision transformer model on ImageNet or WebDataset', 'run distributed multi-GPU training for Pixio with configurable batch size, learning rate, and gradient accumulation', 'resume Pixio pre-training from a saved checkpoint with the --resume flag and --start_epoch', 'run Pixio pre-training on WebDataset with tar-based image data and epoch-based shuffling', 'run Pixio pre-training on ImageNet with configurable masking ratio, mask grid, and class tokens', 'build a PixioViT encoder-decoder model for masked image pre-training with configurable patch size and depth', 'create a Pixio ViT-H/16 model with 1280-dim encoder and 512-dim decoder using the pixio_vith16 factory function', 'create a Pixio ViT-1B model with 1536-dim encoder and 48 transformer blocks using the pixio_vit1b factory function', 'create a Pixio ViT-5B model with 3072-dim encoder and 32 attention heads using the pixio_vit5b factory function', 'run the PixioViT forward pass to reconstruct masked image patches and compute masked MSE loss', 'run a multinode Pixio pre-training job on a Slurm cluster using submitit', 'submit a Trainer instance to a submitit AutoExecutor for distributed GPU training', 'parse command-line arguments for Slurm job parameters like nodes, GPUs, partition, and timeout', 'checkpoint and requeue a Trainer job by returning a DelayedSubmission with a fresh init file', 'setup GPU rank, world size, and output directory from the submitit JobEnvironment']
```

Usage

```
{'build_pixio_vit_model': 'build a PixioViT encoder-decoder model for masked image pre-training with configurable patch size and depth', 'create_pixio_vith16_variant': 'create a Pixio ViT-H/16 model with 1280-dim encoder and 512-dim decoder using the pixio_vith16 factory function', 'create_pixio_vit1b_variant': 'create a Pixio ViT-1B model with 1536-dim encoder and 48 transformer blocks using the pixio_vit1b factory function', 'create_pixio_vit5b_variant': 'create a Pixio ViT-5B model with 3072-dim encoder and 32 attention heads using the pixio_vit5b factory function', 'run_pixio_masked_reconstruction': 'run the PixioViT forward pass to reconstruct masked image patches and compute masked MSE loss'}
```

## File: facebookresearch_pixio/pretraining/submitit_pretrain.py

Prompts

```
['run one epoch of model pretraining with gradient accumulation and mixed precision support', 'build a pretraining loop that trains a model for one epoch using a data loader and optimizer', 'test the train_one_epoch function to verify it returns averaged loss and learning rate metrics', 'refactor the train_one_epoch function to support configurable dtype options like bf16, fp16, or fp32', 'review the train_one_epoch function and its wandb logging of train loss, learning rate, and epoch progress', 'run the Pixio pre-training script with argparse CLI to train a vision transformer model on ImageNet or WebDataset', 'run distributed multi-GPU training for Pixio with configurable batch size, learning rate, and gradient accumulation', 'resume Pixio pre-training from a saved checkpoint with the --resume flag and --start_epoch', 'run Pixio pre-training on WebDataset with tar-based image data and epoch-based shuffling', 'run Pixio pre-training on ImageNet with configurable masking ratio, mask grid, and class tokens', 'build a PixioViT encoder-decoder model for masked image pre-training with configurable patch size and depth', 'create a Pixio ViT-H/16 model with 1280-dim encoder and 512-dim decoder using the pixio_vith16 factory function', 'create a Pixio ViT-1B model with 1536-dim encoder and 48 transformer blocks using the pixio_vit1b factory function', 'create a Pixio ViT-5B model with 3072-dim encoder and 32 attention heads using the pixio_vit5b factory function', 'run the PixioViT forward pass to reconstruct masked image patches and compute masked MSE loss', 'run a multinode Pixio pre-training job on a Slurm cluster using submitit', 'submit a Trainer instance to a submitit AutoExecutor for distributed GPU training', 'parse command-line arguments for Slurm job parameters like nodes, GPUs, partition, and timeout', 'checkpoint and requeue a Trainer job by returning a DelayedSubmission with a fresh init file', 'setup GPU rank, world size, and output directory from the submitit JobEnvironment']
```

Usage

```
{'run_multinode_pretraining_job': 'run a multinode Pixio pre-training job on a Slurm cluster using submitit', 'submit_Trainer_with_executor': 'submit a Trainer instance to a submitit AutoExecutor for distributed GPU training', 'parse_args_for_slurm': 'parse command-line arguments for Slurm job parameters like nodes, GPUs, partition, and timeout', 'checkpoint_Trainer_for_requeuing': 'checkpoint and requeue a Trainer job by returning a DelayedSubmission with a fresh init file', 'setup_gpu_args_from_job_env': 'setup GPU rank, world size, and output directory from the submitit JobEnvironment'}
```

