# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/tools/train_utils/optimization/fastai_optim.py

Prompts

```
['create an OptimWrapper from an optimizer function with layer groups and learning rate', 'create a FastAIMixedOptim for mixed precision training with FP16 model and FP32 master parameters', 'split layer groups into batchnorm and non-batchnorm groups for differential weight decay', 'get FP16 model parameters and FP32 master parameters from layer groups for mixed precision', 'return a filter of trainable parameters from a PyTorch module that require gradients', 'create a learning rate scheduler with custom lr and momentum phases over total training steps', 'create a one-cycle learning rate scheduler with cosine annealing for lr and momentum over total steps', 'create a cosine warmup learning rate scheduler for a PyTorch optimizer with configurable T_max and eta_min', 'use the cosine annealing function to interpolate between a start and end value based on a percentage', 'test the LRSchedulerStep step method to verify lr and momentum values update correctly at each step']
```

Usage

```
{'create_OptimWrapper': 'create an OptimWrapper from an optimizer function with layer groups and learning rate', 'create_FastAIMixedOptim': 'create a FastAIMixedOptim for mixed precision training with FP16 model and FP32 master parameters', 'split_bn_bias': 'split layer groups into batchnorm and non-batchnorm groups for differential weight decay', 'get_master': 'get FP16 model parameters and FP32 master parameters from layer groups for mixed precision', 'trainable_params': 'return a filter of trainable parameters from a PyTorch module that require gradients'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/tools/train_utils/optimization/learning_schedules_fastai.py

Prompts

```
['create an OptimWrapper from an optimizer function with layer groups and learning rate', 'create a FastAIMixedOptim for mixed precision training with FP16 model and FP32 master parameters', 'split layer groups into batchnorm and non-batchnorm groups for differential weight decay', 'get FP16 model parameters and FP32 master parameters from layer groups for mixed precision', 'return a filter of trainable parameters from a PyTorch module that require gradients', 'create a learning rate scheduler with custom lr and momentum phases over total training steps', 'create a one-cycle learning rate scheduler with cosine annealing for lr and momentum over total steps', 'create a cosine warmup learning rate scheduler for a PyTorch optimizer with configurable T_max and eta_min', 'use the cosine annealing function to interpolate between a start and end value based on a percentage', 'test the LRSchedulerStep step method to verify lr and momentum values update correctly at each step']
```

Usage

```
{'create_LRSchedulerStep': 'create a learning rate scheduler with custom lr and momentum phases over total training steps', 'create_OneCycle': 'create a one-cycle learning rate scheduler with cosine annealing for lr and momentum over total steps', 'create_CosineWarmupLR': 'create a cosine warmup learning rate scheduler for a PyTorch optimizer with configurable T_max and eta_min', 'use_annealing_cos': 'use the cosine annealing function to interpolate between a start and end value based on a percentage', 'test_LRSchedulerStep_step': 'test the LRSchedulerStep step method to verify lr and momentum values update correctly at each step'}
```

