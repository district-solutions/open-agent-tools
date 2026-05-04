# Agent Python Tools

- repo: facebookresearch/dora
- repo_uri: https://github.com/facebookresearch/dora

## File: facebookresearch_dora/examples/pl/data.py

Prompts

```
['create a PyTorch Lightning DataModule for CIFAR10 with configurable root path and batch size', 'get CIFAR10 train and test datasets with augmentation transforms and normalization applied', 'setup the DataModule to load CIFAR10 train and test splits for a given stage', 'return a DataLoader for CIFAR10 training data with the specified batch size and 10 workers', 'prepare CIFAR10 data by downloading datasets to the specified root directory on a single machine', 'run a PyTorch Lightning training loop for a ResNet18 model on MNIST data with Dora experiment tracking', 'create a PyTorch Lightning module wrapping a ResNet18 model with training and validation steps', 'configure a ModelCheckpoint callback to save the best model based on validation loss', 'set up a Dora experiment with argparse arguments and distributed training support for PyTorch Lightning', 'log training and validation metrics like loss and accuracy to Dora Link with distributed sync']
```

Usage

```
{'create_datamodule_cifar10': 'create a PyTorch Lightning DataModule for CIFAR10 with configurable root path and batch size', 'get_datasets_cifar10': 'get CIFAR10 train and test datasets with augmentation transforms and normalization applied', 'setup_datamodule': 'setup the DataModule to load CIFAR10 train and test splits for a given stage', 'train_dataloader': 'return a DataLoader for CIFAR10 training data with the specified batch size and 10 workers', 'prepare_data': 'prepare CIFAR10 data by downloading datasets to the specified root directory on a single machine'}
```

## File: facebookresearch_dora/examples/pl/train.py

Prompts

```
['create a PyTorch Lightning DataModule for CIFAR10 with configurable root path and batch size', 'get CIFAR10 train and test datasets with augmentation transforms and normalization applied', 'setup the DataModule to load CIFAR10 train and test splits for a given stage', 'return a DataLoader for CIFAR10 training data with the specified batch size and 10 workers', 'prepare CIFAR10 data by downloading datasets to the specified root directory on a single machine', 'run a PyTorch Lightning training loop for a ResNet18 model on MNIST data with Dora experiment tracking', 'create a PyTorch Lightning module wrapping a ResNet18 model with training and validation steps', 'configure a ModelCheckpoint callback to save the best model based on validation loss', 'set up a Dora experiment with argparse arguments and distributed training support for PyTorch Lightning', 'log training and validation metrics like loss and accuracy to Dora Link with distributed sync']
```

Usage

```
{'run_resnet18_training': 'run a PyTorch Lightning training loop for a ResNet18 model on MNIST data with Dora experiment tracking', 'create_lightning_module': 'create a PyTorch Lightning module wrapping a ResNet18 model with training and validation steps', 'configure_model_checkpointing': 'configure a ModelCheckpoint callback to save the best model based on validation loss', 'setup_dora_experiment': 'set up a Dora experiment with argparse arguments and distributed training support for PyTorch Lightning', 'log_training_metrics': 'log training and validation metrics like loss and accuracy to Dora Link with distributed sync'}
```

