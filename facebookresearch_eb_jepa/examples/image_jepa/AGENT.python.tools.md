# Agent Python Tools

- repo: facebookresearch/eb/jepa
- repo_uri: https://github.com/facebookresearch/eb_jepa

## File: facebookresearch_eb_jepa/examples/image_jepa/dataset.py

Prompts

```
['create a Compose transform pipeline with random crop, color jitter, grayscale, solarization, and flip for training', 'create a Compose transform pipeline with ToTensor and Normalize for validation', 'build a PyTorch Dataset wrapper that applies a transform multiple times to create augmented views', 'review the RandomResizedCrop, ColorJitter, Grayscale, Solarization, and HorizontalFlip augmentation classes', 'refactor the ColorJitter, Grayscale, Solarization, or HorizontalFlip class to change its probability threshold', 'create a LinearProbe classifier with a given feature dimension and number of classes', 'build a forward pass through the LinearProbe classifier to get class logits', 'evaluate a linear probe on a validation set and return accuracy and average loss', 'run the linear probe evaluation with automatic mixed precision enabled on CUDA', 'test the linear probe evaluation using cross entropy loss on a validation dataloader', 'run the image JEPA training script on CIFAR-10 with a YAML config file and optional overrides', 'create a ResNet-18 backbone model that outputs 512-dimensional features without a classification head', 'build an ImageSSL model with a backbone and MLP projector for self-supervised learning', 'test the LARS optimizer with learning rate scaling and weight decay on model parameters', 'review the WarmupCosineScheduler class that implements linear warmup followed by cosine annealing']
```

Usage

```
{'create_train_transforms': 'create a Compose transform pipeline with random crop, color jitter, grayscale, solarization, and flip for training', 'create_val_transforms': 'create a Compose transform pipeline with ToTensor and Normalize for validation', 'build_imagedataset': 'build a PyTorch Dataset wrapper that applies a transform multiple times to create augmented views', 'review_augmentation_classes': 'review the RandomResizedCrop, ColorJitter, Grayscale, Solarization, and HorizontalFlip augmentation classes', 'refactor_augmentation_probs': 'refactor the ColorJitter, Grayscale, Solarization, or HorizontalFlip class to change its probability threshold'}
```

## File: facebookresearch_eb_jepa/examples/image_jepa/eval.py

Prompts

```
['create a Compose transform pipeline with random crop, color jitter, grayscale, solarization, and flip for training', 'create a Compose transform pipeline with ToTensor and Normalize for validation', 'build a PyTorch Dataset wrapper that applies a transform multiple times to create augmented views', 'review the RandomResizedCrop, ColorJitter, Grayscale, Solarization, and HorizontalFlip augmentation classes', 'refactor the ColorJitter, Grayscale, Solarization, or HorizontalFlip class to change its probability threshold', 'create a LinearProbe classifier with a given feature dimension and number of classes', 'build a forward pass through the LinearProbe classifier to get class logits', 'evaluate a linear probe on a validation set and return accuracy and average loss', 'run the linear probe evaluation with automatic mixed precision enabled on CUDA', 'test the linear probe evaluation using cross entropy loss on a validation dataloader', 'run the image JEPA training script on CIFAR-10 with a YAML config file and optional overrides', 'create a ResNet-18 backbone model that outputs 512-dimensional features without a classification head', 'build an ImageSSL model with a backbone and MLP projector for self-supervised learning', 'test the LARS optimizer with learning rate scaling and weight decay on model parameters', 'review the WarmupCosineScheduler class that implements linear warmup followed by cosine annealing']
```

Usage

```
{'create_linear_probe_classifier': 'create a LinearProbe classifier with a given feature dimension and number of classes', 'build_linear_probe_forward': 'build a forward pass through the LinearProbe classifier to get class logits', 'evaluate_linear_probe_accuracy': 'evaluate a linear probe on a validation set and return accuracy and average loss', 'run_linear_probe_with_amp': 'run the linear probe evaluation with automatic mixed precision enabled on CUDA', 'test_linear_probe_cross_entropy': 'test the linear probe evaluation using cross entropy loss on a validation dataloader'}
```

## File: facebookresearch_eb_jepa/examples/image_jepa/main.py

Prompts

```
['create a Compose transform pipeline with random crop, color jitter, grayscale, solarization, and flip for training', 'create a Compose transform pipeline with ToTensor and Normalize for validation', 'build a PyTorch Dataset wrapper that applies a transform multiple times to create augmented views', 'review the RandomResizedCrop, ColorJitter, Grayscale, Solarization, and HorizontalFlip augmentation classes', 'refactor the ColorJitter, Grayscale, Solarization, or HorizontalFlip class to change its probability threshold', 'create a LinearProbe classifier with a given feature dimension and number of classes', 'build a forward pass through the LinearProbe classifier to get class logits', 'evaluate a linear probe on a validation set and return accuracy and average loss', 'run the linear probe evaluation with automatic mixed precision enabled on CUDA', 'test the linear probe evaluation using cross entropy loss on a validation dataloader', 'run the image JEPA training script on CIFAR-10 with a YAML config file and optional overrides', 'create a ResNet-18 backbone model that outputs 512-dimensional features without a classification head', 'build an ImageSSL model with a backbone and MLP projector for self-supervised learning', 'test the LARS optimizer with learning rate scaling and weight decay on model parameters', 'review the WarmupCosineScheduler class that implements linear warmup followed by cosine annealing']
```

Usage

```
{'run_train_image_jepa': 'run the image JEPA training script on CIFAR-10 with a YAML config file and optional overrides', 'create_resnet18_backbone': 'create a ResNet-18 backbone model that outputs 512-dimensional features without a classification head', 'build_image_ssl_model': 'build an ImageSSL model with a backbone and MLP projector for self-supervised learning', 'test_lars_optimizer': 'test the LARS optimizer with learning rate scaling and weight decay on model parameters', 'review_warmup_cosine_scheduler': 'review the WarmupCosineScheduler class that implements linear warmup followed by cosine annealing'}
```

