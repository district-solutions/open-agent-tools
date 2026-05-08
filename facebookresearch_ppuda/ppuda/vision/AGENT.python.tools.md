# Agent Python Tools

- repo: facebookresearch/ppuda
- repo_uri: https://github.com/facebookresearch/ppuda

## File: facebookresearch_ppuda/ppuda/vision/imagenet.py

Prompts

```
['split a list of (sample, class) tuples into train and validation sets with 50 samples per class for validation', 'create an ImageNetDataset instance from a root directory with a specified train or val split and optional transform', 'get the number of examples in an ImageNetDataset by accessing the num_examples property', 'get the SHA-256 checksum of an ImageNetDataset samples as an integer for verifying dataset integrity', 'review the ImageNetDataset __init__ method to understand how it handles train/val splitting with the has_validation flag', 'create PyTorch DataLoaders for ImageNet training and validation with configurable batch size and transforms', 'create PyTorch DataLoaders for CIFAR-10 or CIFAR-100 datasets with optional Cutout augmentation and noise', 'create distributed PyTorch DataLoaders using DistributedSampler for multi-GPU training with DistributedDataParallel', 'convert a torchvision dataset to a few-shot learning dataset with N samples per class', 'create PyTorch DataLoaders with custom train and validation transforms passed as a tuple', 'create a Cutout transform that randomly masks a square region of a tensor image', 'create a Noise transform that adds Gaussian noise to images with a configurable standard deviation', 'build train and validation transform pipelines for CIFAR-10 with optional cutout and noise augmentation', 'build train and validation transform pipelines for ImageNet with optional noise and cifar-style cropping', 'refactor the transforms_cifar function to support custom normalization values or additional augmentation steps']
```

Usage

```
{'split_train_and_val': 'split a list of (sample, class) tuples into train and validation sets with 50 samples per class for validation', 'create_ImageNetDataset': 'create an ImageNetDataset instance from a root directory with a specified train or val split and optional transform', 'get_num_examples': 'get the number of examples in an ImageNetDataset by accessing the num_examples property', 'get_dataset_checksum': 'get the SHA-256 checksum of an ImageNetDataset samples as an integer for verifying dataset integrity', 'review_ImageNetDataset_init': 'review the ImageNetDataset __init__ method to understand how it handles train/val splitting with the has_validation flag'}
```

## File: facebookresearch_ppuda/ppuda/vision/loader.py

Prompts

```
['split a list of (sample, class) tuples into train and validation sets with 50 samples per class for validation', 'create an ImageNetDataset instance from a root directory with a specified train or val split and optional transform', 'get the number of examples in an ImageNetDataset by accessing the num_examples property', 'get the SHA-256 checksum of an ImageNetDataset samples as an integer for verifying dataset integrity', 'review the ImageNetDataset __init__ method to understand how it handles train/val splitting with the has_validation flag', 'create PyTorch DataLoaders for ImageNet training and validation with configurable batch size and transforms', 'create PyTorch DataLoaders for CIFAR-10 or CIFAR-100 datasets with optional Cutout augmentation and noise', 'create distributed PyTorch DataLoaders using DistributedSampler for multi-GPU training with DistributedDataParallel', 'convert a torchvision dataset to a few-shot learning dataset with N samples per class', 'create PyTorch DataLoaders with custom train and validation transforms passed as a tuple', 'create a Cutout transform that randomly masks a square region of a tensor image', 'create a Noise transform that adds Gaussian noise to images with a configurable standard deviation', 'build train and validation transform pipelines for CIFAR-10 with optional cutout and noise augmentation', 'build train and validation transform pipelines for ImageNet with optional noise and cifar-style cropping', 'refactor the transforms_cifar function to support custom normalization values or additional augmentation steps']
```

Usage

```
{'create_dataloader_imagenet': 'create PyTorch DataLoaders for ImageNet training and validation with configurable batch size and transforms', 'create_dataloader_cifar': 'create PyTorch DataLoaders for CIFAR-10 or CIFAR-100 datasets with optional Cutout augmentation and noise', 'create_dataloader_ddp': 'create distributed PyTorch DataLoaders using DistributedSampler for multi-GPU training with DistributedDataParallel', 'convert_to_few_shot': 'convert a torchvision dataset to a few-shot learning dataset with N samples per class', 'create_dataloader_custom_transforms': 'create PyTorch DataLoaders with custom train and validation transforms passed as a tuple'}
```

## File: facebookresearch_ppuda/ppuda/vision/transforms.py

Prompts

```
['split a list of (sample, class) tuples into train and validation sets with 50 samples per class for validation', 'create an ImageNetDataset instance from a root directory with a specified train or val split and optional transform', 'get the number of examples in an ImageNetDataset by accessing the num_examples property', 'get the SHA-256 checksum of an ImageNetDataset samples as an integer for verifying dataset integrity', 'review the ImageNetDataset __init__ method to understand how it handles train/val splitting with the has_validation flag', 'create PyTorch DataLoaders for ImageNet training and validation with configurable batch size and transforms', 'create PyTorch DataLoaders for CIFAR-10 or CIFAR-100 datasets with optional Cutout augmentation and noise', 'create distributed PyTorch DataLoaders using DistributedSampler for multi-GPU training with DistributedDataParallel', 'convert a torchvision dataset to a few-shot learning dataset with N samples per class', 'create PyTorch DataLoaders with custom train and validation transforms passed as a tuple', 'create a Cutout transform that randomly masks a square region of a tensor image', 'create a Noise transform that adds Gaussian noise to images with a configurable standard deviation', 'build train and validation transform pipelines for CIFAR-10 with optional cutout and noise augmentation', 'build train and validation transform pipelines for ImageNet with optional noise and cifar-style cropping', 'refactor the transforms_cifar function to support custom normalization values or additional augmentation steps']
```

Usage

```
{'create_cutout_augmentation': 'create a Cutout transform that randomly masks a square region of a tensor image', 'create_noise_augmentation': 'create a Noise transform that adds Gaussian noise to images with a configurable standard deviation', 'build_cifar_transforms': 'build train and validation transform pipelines for CIFAR-10 with optional cutout and noise augmentation', 'build_imagenet_transforms': 'build train and validation transform pipelines for ImageNet with optional noise and cifar-style cropping', 'refactor_transforms_cifar': 'refactor the transforms_cifar function to support custom normalization values or additional augmentation steps'}
```

