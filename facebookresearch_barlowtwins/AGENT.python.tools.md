# Agent Python Tools

- repo: facebookresearch/barlowtwins
- repo_uri: https://github.com/facebookresearch/barlowtwins

## File: facebookresearch_barlowtwins/evaluate.py

Prompts

```
['run a linear classifier evaluation on ImageNet using a pretrained ResNet50 model checkpoint', 'run a finetune evaluation on ImageNet using a pretrained ResNet50 model with cosine annealing', 'run a linear evaluation on ImageNet using only 1 or 10 percent of the training set', 'review the python AverageMeter class that computes and stores average and current values for metrics', 'test the python accuracy function that computes top-k accuracy over predictions for specified k values', 'load a pretrained ResNet50 model with Barlow Twins weights from the Facebook AI model zoo', 'load a ResNet50 model without pretrained weights by passing pretrained=False to the resnet50 function', 'run inference with a Barlow Twins pretrained ResNet50 model loaded via torch hub', 'review the resnet50 function that loads state dict from a Facebook AI public files URL', 'summarize the hubconf module that exposes a Barlow Twins pretrained ResNet50 model for torch hub', 'run the Barlow Twins self-supervised training on an ImageFolder dataset with distributed GPU support', 'build a BarlowTwins model with a ResNet50 backbone and configurable MLP projector layers', 'create a LARS optimizer with adaptive learning rate and weight decay filtering for training', 'review the Transform class that applies dual augmented views with GaussianBlur and Solarization', 'summarize the off_diagonal function that extracts off-diagonal elements from a cross-correlation matrix']
```

Usage

```
{'run_linear_evaluation': 'run a linear classifier evaluation on ImageNet using a pretrained ResNet50 model checkpoint', 'run_finetune_evaluation': 'run a finetune evaluation on ImageNet using a pretrained ResNet50 model with cosine annealing', 'run_few_shot_evaluation': 'run a linear evaluation on ImageNet using only 1 or 10 percent of the training set', 'review_AverageMeter': 'review the python AverageMeter class that computes and stores average and current values for metrics', 'test_accuracy': 'test the python accuracy function that computes top-k accuracy over predictions for specified k values'}
```

## File: facebookresearch_barlowtwins/hubconf.py

Prompts

```
['run a linear classifier evaluation on ImageNet using a pretrained ResNet50 model checkpoint', 'run a finetune evaluation on ImageNet using a pretrained ResNet50 model with cosine annealing', 'run a linear evaluation on ImageNet using only 1 or 10 percent of the training set', 'review the python AverageMeter class that computes and stores average and current values for metrics', 'test the python accuracy function that computes top-k accuracy over predictions for specified k values', 'load a pretrained ResNet50 model with Barlow Twins weights from the Facebook AI model zoo', 'load a ResNet50 model without pretrained weights by passing pretrained=False to the resnet50 function', 'run inference with a Barlow Twins pretrained ResNet50 model loaded via torch hub', 'review the resnet50 function that loads state dict from a Facebook AI public files URL', 'summarize the hubconf module that exposes a Barlow Twins pretrained ResNet50 model for torch hub', 'run the Barlow Twins self-supervised training on an ImageFolder dataset with distributed GPU support', 'build a BarlowTwins model with a ResNet50 backbone and configurable MLP projector layers', 'create a LARS optimizer with adaptive learning rate and weight decay filtering for training', 'review the Transform class that applies dual augmented views with GaussianBlur and Solarization', 'summarize the off_diagonal function that extracts off-diagonal elements from a cross-correlation matrix']
```

Usage

```
{'load_resnet50_pretrained': 'load a pretrained ResNet50 model with Barlow Twins weights from the Facebook AI model zoo', 'load_resnet50_untrained': 'load a ResNet50 model without pretrained weights by passing pretrained=False to the resnet50 function', 'run_resnet50_inference': 'run inference with a Barlow Twins pretrained ResNet50 model loaded via torch hub', 'review_resnet50_function': 'review the resnet50 function that loads state dict from a Facebook AI public files URL', 'summarize_hubconf': 'summarize the hubconf module that exposes a Barlow Twins pretrained ResNet50 model for torch hub'}
```

## File: facebookresearch_barlowtwins/main.py

Prompts

```
['run a linear classifier evaluation on ImageNet using a pretrained ResNet50 model checkpoint', 'run a finetune evaluation on ImageNet using a pretrained ResNet50 model with cosine annealing', 'run a linear evaluation on ImageNet using only 1 or 10 percent of the training set', 'review the python AverageMeter class that computes and stores average and current values for metrics', 'test the python accuracy function that computes top-k accuracy over predictions for specified k values', 'load a pretrained ResNet50 model with Barlow Twins weights from the Facebook AI model zoo', 'load a ResNet50 model without pretrained weights by passing pretrained=False to the resnet50 function', 'run inference with a Barlow Twins pretrained ResNet50 model loaded via torch hub', 'review the resnet50 function that loads state dict from a Facebook AI public files URL', 'summarize the hubconf module that exposes a Barlow Twins pretrained ResNet50 model for torch hub', 'run the Barlow Twins self-supervised training on an ImageFolder dataset with distributed GPU support', 'build a BarlowTwins model with a ResNet50 backbone and configurable MLP projector layers', 'create a LARS optimizer with adaptive learning rate and weight decay filtering for training', 'review the Transform class that applies dual augmented views with GaussianBlur and Solarization', 'summarize the off_diagonal function that extracts off-diagonal elements from a cross-correlation matrix']
```

Usage

```
{'run_barlowtwins_training': 'run the Barlow Twins self-supervised training on an ImageFolder dataset with distributed GPU support', 'build_barlowtwins_model': 'build a BarlowTwins model with a ResNet50 backbone and configurable MLP projector layers', 'create_lars_optimizer': 'create a LARS optimizer with adaptive learning rate and weight decay filtering for training', 'review_transform_augmentations': 'review the Transform class that applies dual augmented views with GaussianBlur and Solarization', 'summarize_off_diagonal_function': 'summarize the off_diagonal function that extracts off-diagonal elements from a cross-correlation matrix'}
```

