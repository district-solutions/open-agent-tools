# Agent Python Tools

- repo: facebookresearch/omni3d
- repo_uri: https://github.com/facebookresearch/omni3d

## File: facebookresearch_omni3d/cubercnn/solver/build.py

Prompts

```
['build an SGD optimizer with momentum and weight decay from a detectron2 config and model', 'build an Adam optimizer with custom eps from a detectron2 config and model', 'build an AdamW optimizer with amsgrad support from a detectron2 config and model', 'freeze all BatchNorm2d layers in a PyTorch network by setting eval mode and disabling stats', 'review the build_optimizer function to understand how it groups params by norm, bias, and prior types', 'create a PeriodicCheckpointerOnlyOne instance to save only one recent checkpoint at each period interval', 'call the step method on PeriodicCheckpointerOnlyOne with an iteration number to trigger checkpoint saving', 'save a single recent model checkpoint at periodic intervals using the step method with iteration', 'save a final checkpoint when iteration reaches max_iter minus one using PeriodicCheckpointerOnlyOne', 'extend detectron2 PeriodicCheckpointer to override step and save only one recent model instead of multiple']
```

Usage

```
{'build_optimizer_sgd': 'build an SGD optimizer with momentum and weight decay from a detectron2 config and model', 'build_optimizer_adam': 'build an Adam optimizer with custom eps from a detectron2 config and model', 'build_optimizer_adamw': 'build an AdamW optimizer with amsgrad support from a detectron2 config and model', 'freeze_bn_network': 'freeze all BatchNorm2d layers in a PyTorch network by setting eval mode and disabling stats', 'review_build_optimizer_param_groups': 'review the build_optimizer function to understand how it groups params by norm, bias, and prior types'}
```

## File: facebookresearch_omni3d/cubercnn/solver/checkpoint.py

Prompts

```
['build an SGD optimizer with momentum and weight decay from a detectron2 config and model', 'build an Adam optimizer with custom eps from a detectron2 config and model', 'build an AdamW optimizer with amsgrad support from a detectron2 config and model', 'freeze all BatchNorm2d layers in a PyTorch network by setting eval mode and disabling stats', 'review the build_optimizer function to understand how it groups params by norm, bias, and prior types', 'create a PeriodicCheckpointerOnlyOne instance to save only one recent checkpoint at each period interval', 'call the step method on PeriodicCheckpointerOnlyOne with an iteration number to trigger checkpoint saving', 'save a single recent model checkpoint at periodic intervals using the step method with iteration', 'save a final checkpoint when iteration reaches max_iter minus one using PeriodicCheckpointerOnlyOne', 'extend detectron2 PeriodicCheckpointer to override step and save only one recent model instead of multiple']
```

Usage

```
{'create_PeriodicCheckpointerOnlyOne': 'create a PeriodicCheckpointerOnlyOne instance to save only one recent checkpoint at each period interval', 'call_step_method': 'call the step method on PeriodicCheckpointerOnlyOne with an iteration number to trigger checkpoint saving', 'save_recent_checkpoint': 'save a single recent model checkpoint at periodic intervals using the step method with iteration', 'save_final_checkpoint': 'save a final checkpoint when iteration reaches max_iter minus one using PeriodicCheckpointerOnlyOne', 'extend_PeriodicCheckpointer': 'extend detectron2 PeriodicCheckpointer to override step and save only one recent model instead of multiple'}
```

