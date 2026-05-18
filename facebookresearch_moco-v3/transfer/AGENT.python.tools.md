# Agent Python Tools

- repo: facebookresearch/moco-v3
- repo_uri: https://github.com/facebookresearch/moco-v3

## File: facebookresearch_moco-v3/transfer/datasets.py

Prompts

```
['build a torchvision transform pipeline with random crop, flip, and normalization for training data', 'build a torchvision transform pipeline with resize, center crop, and normalization for test data', 'build a CIFAR-10 dataset with automatic download and the specified transform for training or testing', 'build a CIFAR-100 dataset with automatic download and the specified transform for training or testing', 'build an Oxford Flowers or Pets dataset with the specified transform for transfer learning']
```

Usage

```
{'build_transform_for_training': 'build a torchvision transform pipeline with random crop, flip, and normalization for training data', 'build_transform_for_testing': 'build a torchvision transform pipeline with resize, center crop, and normalization for test data', 'build_dataset_cifar10': 'build a CIFAR-10 dataset with automatic download and the specified transform for training or testing', 'build_dataset_cifar100': 'build a CIFAR-100 dataset with automatic download and the specified transform for training or testing', 'build_dataset_flowers_or_pets': 'build an Oxford Flowers or Pets dataset with the specified transform for transfer learning'}
```

