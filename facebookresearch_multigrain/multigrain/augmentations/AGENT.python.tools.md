# Agent Python Tools

- repo: facebookresearch/multigrain
- repo_uri: https://github.com/facebookresearch/multigrain

## File: facebookresearch_multigrain/multigrain/augmentations/autoaugment.py

Prompts

```
['apply the ImageNetPolicy auto augmentation to a PIL image for data augmentation', 'apply the CIFAR10Policy auto augmentation to a PIL image for CIFAR10 data augmentation', 'apply the SVHNPolicy auto augmentation to a PIL image for SVHN data augmentation', 'create a SubPolicy with two image operations, magnitudes, and probabilities for custom augmentation', 'customize the fill color for ImageNetPolicy, CIFAR10Policy, or SVHNPolicy augmentation policies', 'build a python module to get train and val image transforms for ImageNet with full augmentation pipeline', 'create a custom Resize transform that resizes images to a target size without cropping by largest side', 'build a PCA jitter transform that applies random lighting augmentation to image tensors using eigenvalues and eigenvectors', 'create a tensor clamping transform that bounds pixel values between a lower and upper threshold', 'build a python module to get image transforms with custom mean and std for pnasnet5large or nasnetamobile backbones']
```

Usage

```
{'apply_imagenet_policy': 'apply the ImageNetPolicy auto augmentation to a PIL image for data augmentation', 'apply_cifar10_policy': 'apply the CIFAR10Policy auto augmentation to a PIL image for CIFAR10 data augmentation', 'apply_svhn_policy': 'apply the SVHNPolicy auto augmentation to a PIL image for SVHN data augmentation', 'create_subpolicy': 'create a SubPolicy with two image operations, magnitudes, and probabilities for custom augmentation', 'customize_fillcolor': 'customize the fill color for ImageNetPolicy, CIFAR10Policy, or SVHNPolicy augmentation policies'}
```

## File: facebookresearch_multigrain/multigrain/augmentations/transforms.py

Prompts

```
['apply the ImageNetPolicy auto augmentation to a PIL image for data augmentation', 'apply the CIFAR10Policy auto augmentation to a PIL image for CIFAR10 data augmentation', 'apply the SVHNPolicy auto augmentation to a PIL image for SVHN data augmentation', 'create a SubPolicy with two image operations, magnitudes, and probabilities for custom augmentation', 'customize the fill color for ImageNetPolicy, CIFAR10Policy, or SVHNPolicy augmentation policies', 'build a python module to get train and val image transforms for ImageNet with full augmentation pipeline', 'create a custom Resize transform that resizes images to a target size without cropping by largest side', 'build a PCA jitter transform that applies random lighting augmentation to image tensors using eigenvalues and eigenvectors', 'create a tensor clamping transform that bounds pixel values between a lower and upper threshold', 'build a python module to get image transforms with custom mean and std for pnasnet5large or nasnetamobile backbones']
```

Usage

```
{'get_transforms_train_val': 'build a python module to get train and val image transforms for ImageNet with full augmentation pipeline', 'Resize_class': 'create a custom Resize transform that resizes images to a target size without cropping by largest side', 'Lighting_class': 'build a PCA jitter transform that applies random lighting augmentation to image tensors using eigenvalues and eigenvectors', 'Bound_class': 'create a tensor clamping transform that bounds pixel values between a lower and upper threshold', 'get_transforms_backbone': 'build a python module to get image transforms with custom mean and std for pnasnet5large or nasnetamobile backbones'}
```

