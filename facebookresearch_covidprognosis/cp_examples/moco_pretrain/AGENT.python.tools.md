# Agent Python Tools

- repo: facebookresearch/covidprognosis
- repo_uri: https://github.com/facebookresearch/covidprognosis

## File: facebookresearch_covidprognosis/cp_examples/moco_pretrain/moco_module.py

Prompts

```
['build a MoCoModule with densenet121 encoder, 256 feature dim, and 65536 queue size', 'run a training step on a batch with image0 and image1 augmented views', 'configure an SGD optimizer with cosine annealing learning rate scheduler', 'review the MoCoModule forward pass that returns output and target from the MoCo model', 'add model-specific argparse arguments for arch, feature_dim, queue_size, and learning rate', 'run MoCo self-supervised pretraining on chest X-ray datasets using PyTorch Lightning', 'build argument parser with defaults for MoCo training including GPU, epochs, and batch size', 'create an XrayDataModule with data augmentation transforms for MoCo two-image training', 'create a MoCoModule model with configurable architecture, queue size, and momentum parameters', 'resume MoCo training from the latest checkpoint in the checkpoints directory']
```

Usage

```
{'build_MocoModule': 'build a MoCoModule with densenet121 encoder, 256 feature dim, and 65536 queue size', 'run_training_step': 'run a training step on a batch with image0 and image1 augmented views', 'configure_optimizers': 'configure an SGD optimizer with cosine annealing learning rate scheduler', 'review_MocoModule_forward': 'review the MoCoModule forward pass that returns output and target from the MoCo model', 'add_model_specific_args': 'add model-specific argparse arguments for arch, feature_dim, queue_size, and learning rate'}
```

## File: facebookresearch_covidprognosis/cp_examples/moco_pretrain/train_moco.py

Prompts

```
['build a MoCoModule with densenet121 encoder, 256 feature dim, and 65536 queue size', 'run a training step on a batch with image0 and image1 augmented views', 'configure an SGD optimizer with cosine annealing learning rate scheduler', 'review the MoCoModule forward pass that returns output and target from the MoCo model', 'add model-specific argparse arguments for arch, feature_dim, queue_size, and learning rate', 'run MoCo self-supervised pretraining on chest X-ray datasets using PyTorch Lightning', 'build argument parser with defaults for MoCo training including GPU, epochs, and batch size', 'create an XrayDataModule with data augmentation transforms for MoCo two-image training', 'create a MoCoModule model with configurable architecture, queue size, and momentum parameters', 'resume MoCo training from the latest checkpoint in the checkpoints directory']
```

Usage

```
{'run_moco_pretraining': 'run MoCo self-supervised pretraining on chest X-ray datasets using PyTorch Lightning', 'build_args_moco': 'build argument parser with defaults for MoCo training including GPU, epochs, and batch size', 'create_xray_datamodule': 'create an XrayDataModule with data augmentation transforms for MoCo two-image training', 'create_moco_module': 'create a MoCoModule model with configurable architecture, queue size, and momentum parameters', 'resume_checkpoint_moco': 'resume MoCo training from the latest checkpoint in the checkpoints directory'}
```

