# Agent Python Tools

- repo: facebookresearch/attentivenas
- repo_uri: https://github.com/facebookresearch/attentivenas

## File: facebookresearch_attentivenas/data/auto_augment_tf.py

Prompts

```
['create an auto augmentation policy using auto_augment_policy with name v0 or original', 'apply auto augmentation to a PIL Image using the AutoAugment class with a policy', 'build an AutoAugmentOp with a name, probability, and magnitude for image augmentation', 'create a shear_x or shear_y augmentation function to transform a PIL Image', 'apply contrast, color, brightness, or sharpness enhancement to a PIL Image', 'build a train and validation data loader for ImageNet with distributed sampling support', 'build PyTorch DataLoaders for ImageNet train and val splits using ImageFolder datasets', 'create a data loader that applies configurable augmentation strategies like auto_augment_tf to ImageNet', 'review the build_data_loader function to understand how it dispatches to dataset-specific loaders', 'refactor the data loader to customize DistributedSampler behavior for train and validation sets', 'build a torchvision transform pipeline with random resized crop and horizontal flip for training images', 'build an ImageNet auto augment transform pipeline with random crop, flip, and augmentation policy for training', 'get a data transform pipeline by passing args, is_training flag, and augment strategy name', 'get a torchvision Normalize transform using ImageNet pixel mean and standard deviation values', 'refactor the build_default_transform function to support additional augmentation strategies beyond random crop and flip']
```

Usage

```
{'create_auto_augment_policy': 'create an auto augmentation policy using auto_augment_policy with name v0 or original', 'apply_auto_augment': 'apply auto augmentation to a PIL Image using the AutoAugment class with a policy', 'build_augment_op': 'build an AutoAugmentOp with a name, probability, and magnitude for image augmentation', 'create_shear_augmentation': 'create a shear_x or shear_y augmentation function to transform a PIL Image', 'apply_image_enhance': 'apply contrast, color, brightness, or sharpness enhancement to a PIL Image'}
```

## File: facebookresearch_attentivenas/data/data_loader.py

Prompts

```
['create an auto augmentation policy using auto_augment_policy with name v0 or original', 'apply auto augmentation to a PIL Image using the AutoAugment class with a policy', 'build an AutoAugmentOp with a name, probability, and magnitude for image augmentation', 'create a shear_x or shear_y augmentation function to transform a PIL Image', 'apply contrast, color, brightness, or sharpness enhancement to a PIL Image', 'build a train and validation data loader for ImageNet with distributed sampling support', 'build PyTorch DataLoaders for ImageNet train and val splits using ImageFolder datasets', 'create a data loader that applies configurable augmentation strategies like auto_augment_tf to ImageNet', 'review the build_data_loader function to understand how it dispatches to dataset-specific loaders', 'refactor the data loader to customize DistributedSampler behavior for train and validation sets', 'build a torchvision transform pipeline with random resized crop and horizontal flip for training images', 'build an ImageNet auto augment transform pipeline with random crop, flip, and augmentation policy for training', 'get a data transform pipeline by passing args, is_training flag, and augment strategy name', 'get a torchvision Normalize transform using ImageNet pixel mean and standard deviation values', 'refactor the build_default_transform function to support additional augmentation strategies beyond random crop and flip']
```

Usage

```
{'build_imagenet_data_loader': 'build a train and validation data loader for ImageNet with distributed sampling support', 'build_default_imagenet_data_loader': 'build PyTorch DataLoaders for ImageNet train and val splits using ImageFolder datasets', 'create_data_loader_with_augmentation': 'create a data loader that applies configurable augmentation strategies like auto_augment_tf to ImageNet', 'review_build_data_loader': 'review the build_data_loader function to understand how it dispatches to dataset-specific loaders', 'refactor_distributed_sampler': 'refactor the data loader to customize DistributedSampler behavior for train and validation sets'}
```

## File: facebookresearch_attentivenas/data/data_transform.py

Prompts

```
['create an auto augmentation policy using auto_augment_policy with name v0 or original', 'apply auto augmentation to a PIL Image using the AutoAugment class with a policy', 'build an AutoAugmentOp with a name, probability, and magnitude for image augmentation', 'create a shear_x or shear_y augmentation function to transform a PIL Image', 'apply contrast, color, brightness, or sharpness enhancement to a PIL Image', 'build a train and validation data loader for ImageNet with distributed sampling support', 'build PyTorch DataLoaders for ImageNet train and val splits using ImageFolder datasets', 'create a data loader that applies configurable augmentation strategies like auto_augment_tf to ImageNet', 'review the build_data_loader function to understand how it dispatches to dataset-specific loaders', 'refactor the data loader to customize DistributedSampler behavior for train and validation sets', 'build a torchvision transform pipeline with random resized crop and horizontal flip for training images', 'build an ImageNet auto augment transform pipeline with random crop, flip, and augmentation policy for training', 'get a data transform pipeline by passing args, is_training flag, and augment strategy name', 'get a torchvision Normalize transform using ImageNet pixel mean and standard deviation values', 'refactor the build_default_transform function to support additional augmentation strategies beyond random crop and flip']
```

Usage

```
{'build_default_transform': 'build a torchvision transform pipeline with random resized crop and horizontal flip for training images', 'build_imagenet_auto_augment_tf_transform': 'build an ImageNet auto augment transform pipeline with random crop, flip, and augmentation policy for training', 'get_data_transform': 'get a data transform pipeline by passing args, is_training flag, and augment strategy name', 'get_normalize': 'get a torchvision Normalize transform using ImageNet pixel mean and standard deviation values', 'refactor_build_default_transform': 'refactor the build_default_transform function to support additional augmentation strategies beyond random crop and flip'}
```

