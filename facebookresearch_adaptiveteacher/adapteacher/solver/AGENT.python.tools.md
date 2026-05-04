# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/adapteacher/solver/build.py

Prompts

```
['build a learning rate scheduler from a detectron2 config node and optimizer', 'build a WarmupMultiStepLR scheduler using config steps, gamma, and warmup parameters', 'build a WarmupCosineLR scheduler using config max_iter and warmup parameters', 'build a WarmupTwoStageMultiStepLR scheduler using config steps, factor_list, gamma, and warmup parameters', 'review the build_lr_scheduler function to understand supported scheduler types and config requirements', 'create a WarmupTwoStageMultiStepLR scheduler with milestones, factor_list, and warmup parameters for a PyTorch optimizer', 'build a learning rate scheduler with linear warmup and multi-step decay using WarmupTwoStageMultiStepLR', 'test the WarmupTwoStageMultiStepLR get_lr method to verify correct learning rate computation at each epoch', 'review the WarmupTwoStageMultiStepLR constructor to understand milestone validation and factor_list length checks', 'refactor the WarmupTwoStageMultiStepLR class to support additional warmup methods or decay strategies']
```

Usage

```
{'build_lr_scheduler': 'build a learning rate scheduler from a detectron2 config node and optimizer', 'build_warmup_multistep_lr': 'build a WarmupMultiStepLR scheduler using config steps, gamma, and warmup parameters', 'build_warmup_cosine_lr': 'build a WarmupCosineLR scheduler using config max_iter and warmup parameters', 'build_warmup_twostage_multistep_lr': 'build a WarmupTwoStageMultiStepLR scheduler using config steps, factor_list, gamma, and warmup parameters', 'review_build_lr_scheduler': 'review the build_lr_scheduler function to understand supported scheduler types and config requirements'}
```

## File: facebookresearch_adaptiveteacher/adapteacher/solver/lr_scheduler.py

Prompts

```
['build a learning rate scheduler from a detectron2 config node and optimizer', 'build a WarmupMultiStepLR scheduler using config steps, gamma, and warmup parameters', 'build a WarmupCosineLR scheduler using config max_iter and warmup parameters', 'build a WarmupTwoStageMultiStepLR scheduler using config steps, factor_list, gamma, and warmup parameters', 'review the build_lr_scheduler function to understand supported scheduler types and config requirements', 'create a WarmupTwoStageMultiStepLR scheduler with milestones, factor_list, and warmup parameters for a PyTorch optimizer', 'build a learning rate scheduler with linear warmup and multi-step decay using WarmupTwoStageMultiStepLR', 'test the WarmupTwoStageMultiStepLR get_lr method to verify correct learning rate computation at each epoch', 'review the WarmupTwoStageMultiStepLR constructor to understand milestone validation and factor_list length checks', 'refactor the WarmupTwoStageMultiStepLR class to support additional warmup methods or decay strategies']
```

Usage

```
{'create_WarmupTwoStageMultiStepLR': 'create a WarmupTwoStageMultiStepLR scheduler with milestones, factor_list, and warmup parameters for a PyTorch optimizer', 'build_lr_scheduler_with_warmup': 'build a learning rate scheduler with linear warmup and multi-step decay using WarmupTwoStageMultiStepLR', 'test_WarmupTwoStageMultiStepLR_get_lr': 'test the WarmupTwoStageMultiStepLR get_lr method to verify correct learning rate computation at each epoch', 'review_WarmupTwoStageMultiStepLR_init': 'review the WarmupTwoStageMultiStepLR constructor to understand milestone validation and factor_list length checks', 'refactor_WarmupTwoStageMultiStepLR': 'refactor the WarmupTwoStageMultiStepLR class to support additional warmup methods or decay strategies'}
```

