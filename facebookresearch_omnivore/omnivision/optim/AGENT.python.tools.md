# Agent Python Tools

- repo: facebookresearch/omnivore
- repo_uri: https://github.com/facebookresearch/omnivore

## File: facebookresearch_omnivore/omnivision/optim/lars.py

Prompts

```
['create a LARS optimizer by wrapping a PyTorch SGD optimizer with trust coefficient and clip settings', 'step the LARS optimizer to perform an adaptive learning rate update on model parameters', 'configure LARS optimizer param groups to selectively enable or disable LARS per parameter group', 'review the LARS step method that calculates adaptive learning rates using parameter and gradient norms', 'summarize the LARS class that wraps a PyTorch optimizer with Layer-wise Adaptive Rate Scaling', 'create a ValueScaler that multiplies a scheduler output by a given float multiplier value', 'use layer_decay_param_modifier to apply layer-wise learning rate decay to scheduler configurations', 'review the ValueScaler class that wraps a scheduler and scales its return value', 'refactor the layer_decay_param_modifier function to support additional scheduler options beyond learning rate', 'test the layer decay computation that raises the decay value to a power based on layer depth', 'create an OmniOptimizer wrapping a PyTorch optimizer with optional learning rate schedulers', 'step the OmniOptimizer by calling step with the current training progress value', 'zero gradients on the wrapped optimizer via OmniOptimizer zero_grad method', 'review the OmniOptimizer step_schedulers method that updates param groups using scheduler functions', 'refactor the OmniOptimizer _validate_optimizer_schedulers method to support additional scheduler validation rules', 'construct an OmniOptimizer from a model and Hydra config with optional scheduler options and param group modifiers', 'create a LARS-wrapped optimizer by instantiating an optimizer config and wrapping it with LARS', 'validate that parameter groups are disjoint and cover all model parameters', 'match model parameter names against Unix glob patterns from a scheduler config', 'map scheduler configs to optimizer param groups by intersecting parameter name constraints']
```

Usage

```
{'create_LARS_optimizer': 'create a LARS optimizer by wrapping a PyTorch SGD optimizer with trust coefficient and clip settings', 'step_LARS_optimizer': 'step the LARS optimizer to perform an adaptive learning rate update on model parameters', 'configure_LARS_param_groups': 'configure LARS optimizer param groups to selectively enable or disable LARS per parameter group', 'review_LARS_step': 'review the LARS step method that calculates adaptive learning rates using parameter and gradient norms', 'summarize_LARS_class': 'summarize the LARS class that wraps a PyTorch optimizer with Layer-wise Adaptive Rate Scaling'}
```

## File: facebookresearch_omnivore/omnivision/optim/layer_decay_param_modifier.py

Prompts

```
['create a LARS optimizer by wrapping a PyTorch SGD optimizer with trust coefficient and clip settings', 'step the LARS optimizer to perform an adaptive learning rate update on model parameters', 'configure LARS optimizer param groups to selectively enable or disable LARS per parameter group', 'review the LARS step method that calculates adaptive learning rates using parameter and gradient norms', 'summarize the LARS class that wraps a PyTorch optimizer with Layer-wise Adaptive Rate Scaling', 'create a ValueScaler that multiplies a scheduler output by a given float multiplier value', 'use layer_decay_param_modifier to apply layer-wise learning rate decay to scheduler configurations', 'review the ValueScaler class that wraps a scheduler and scales its return value', 'refactor the layer_decay_param_modifier function to support additional scheduler options beyond learning rate', 'test the layer decay computation that raises the decay value to a power based on layer depth', 'create an OmniOptimizer wrapping a PyTorch optimizer with optional learning rate schedulers', 'step the OmniOptimizer by calling step with the current training progress value', 'zero gradients on the wrapped optimizer via OmniOptimizer zero_grad method', 'review the OmniOptimizer step_schedulers method that updates param groups using scheduler functions', 'refactor the OmniOptimizer _validate_optimizer_schedulers method to support additional scheduler validation rules', 'construct an OmniOptimizer from a model and Hydra config with optional scheduler options and param group modifiers', 'create a LARS-wrapped optimizer by instantiating an optimizer config and wrapping it with LARS', 'validate that parameter groups are disjoint and cover all model parameters', 'match model parameter names against Unix glob patterns from a scheduler config', 'map scheduler configs to optimizer param groups by intersecting parameter name constraints']
```

Usage

```
{'create_value_scaler': 'create a ValueScaler that multiplies a scheduler output by a given float multiplier value', 'use_layer_decay_modifier': 'use layer_decay_param_modifier to apply layer-wise learning rate decay to scheduler configurations', 'review_value_scaler_class': 'review the ValueScaler class that wraps a scheduler and scales its return value', 'refactor_layer_decay_modifier': 'refactor the layer_decay_param_modifier function to support additional scheduler options beyond learning rate', 'test_layer_decay_computation': 'test the layer decay computation that raises the decay value to a power based on layer depth'}
```

## File: facebookresearch_omnivore/omnivision/optim/omni_optimizer.py

Prompts

```
['create a LARS optimizer by wrapping a PyTorch SGD optimizer with trust coefficient and clip settings', 'step the LARS optimizer to perform an adaptive learning rate update on model parameters', 'configure LARS optimizer param groups to selectively enable or disable LARS per parameter group', 'review the LARS step method that calculates adaptive learning rates using parameter and gradient norms', 'summarize the LARS class that wraps a PyTorch optimizer with Layer-wise Adaptive Rate Scaling', 'create a ValueScaler that multiplies a scheduler output by a given float multiplier value', 'use layer_decay_param_modifier to apply layer-wise learning rate decay to scheduler configurations', 'review the ValueScaler class that wraps a scheduler and scales its return value', 'refactor the layer_decay_param_modifier function to support additional scheduler options beyond learning rate', 'test the layer decay computation that raises the decay value to a power based on layer depth', 'create an OmniOptimizer wrapping a PyTorch optimizer with optional learning rate schedulers', 'step the OmniOptimizer by calling step with the current training progress value', 'zero gradients on the wrapped optimizer via OmniOptimizer zero_grad method', 'review the OmniOptimizer step_schedulers method that updates param groups using scheduler functions', 'refactor the OmniOptimizer _validate_optimizer_schedulers method to support additional scheduler validation rules', 'construct an OmniOptimizer from a model and Hydra config with optional scheduler options and param group modifiers', 'create a LARS-wrapped optimizer by instantiating an optimizer config and wrapping it with LARS', 'validate that parameter groups are disjoint and cover all model parameters', 'match model parameter names against Unix glob patterns from a scheduler config', 'map scheduler configs to optimizer param groups by intersecting parameter name constraints']
```

Usage

```
{'create_OmniOptimizer': 'create an OmniOptimizer wrapping a PyTorch optimizer with optional learning rate schedulers', 'step_OmniOptimizer': 'step the OmniOptimizer by calling step with the current training progress value', 'zero_grad_OmniOptimizer': 'zero gradients on the wrapped optimizer via OmniOptimizer zero_grad method', 'review_OmniOptimizer_step_schedulers': 'review the OmniOptimizer step_schedulers method that updates param groups using scheduler functions', 'refactor_OmniOptimizer_validate': 'refactor the OmniOptimizer _validate_optimizer_schedulers method to support additional scheduler validation rules'}
```

## File: facebookresearch_omnivore/omnivision/optim/optimizer.py

Prompts

```
['create a LARS optimizer by wrapping a PyTorch SGD optimizer with trust coefficient and clip settings', 'step the LARS optimizer to perform an adaptive learning rate update on model parameters', 'configure LARS optimizer param groups to selectively enable or disable LARS per parameter group', 'review the LARS step method that calculates adaptive learning rates using parameter and gradient norms', 'summarize the LARS class that wraps a PyTorch optimizer with Layer-wise Adaptive Rate Scaling', 'create a ValueScaler that multiplies a scheduler output by a given float multiplier value', 'use layer_decay_param_modifier to apply layer-wise learning rate decay to scheduler configurations', 'review the ValueScaler class that wraps a scheduler and scales its return value', 'refactor the layer_decay_param_modifier function to support additional scheduler options beyond learning rate', 'test the layer decay computation that raises the decay value to a power based on layer depth', 'create an OmniOptimizer wrapping a PyTorch optimizer with optional learning rate schedulers', 'step the OmniOptimizer by calling step with the current training progress value', 'zero gradients on the wrapped optimizer via OmniOptimizer zero_grad method', 'review the OmniOptimizer step_schedulers method that updates param groups using scheduler functions', 'refactor the OmniOptimizer _validate_optimizer_schedulers method to support additional scheduler validation rules', 'construct an OmniOptimizer from a model and Hydra config with optional scheduler options and param group modifiers', 'create a LARS-wrapped optimizer by instantiating an optimizer config and wrapping it with LARS', 'validate that parameter groups are disjoint and cover all model parameters', 'match model parameter names against Unix glob patterns from a scheduler config', 'map scheduler configs to optimizer param groups by intersecting parameter name constraints']
```

Usage

```
{'construct_optimizer': 'construct an OmniOptimizer from a model and Hydra config with optional scheduler options and param group modifiers', 'create_lars_optimizer': 'create a LARS-wrapped optimizer by instantiating an optimizer config and wrapping it with LARS', 'validate_param_group_params': 'validate that parameter groups are disjoint and cover all model parameters', 'unix_param_pattern_to_parameter_names': 'match model parameter names against Unix glob patterns from a scheduler config', 'map_scheduler_cfgs_to_param_groups': 'map scheduler configs to optimizer param groups by intersecting parameter name constraints'}
```

