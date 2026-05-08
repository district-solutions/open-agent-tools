# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/optim/fp16_loss_scaler.py

Prompts

```
['create a StandardFloat16LossScaler with custom init_scale and scale_window for FP16 training', 'run an optimizer step using Float16LossScaler to get scaled gradient results', 'unscale optimizer gradients using the loss scaler before gradient clipping', 'check if an optimizer supports manual gradient scaling via supports_manual_grad_scaling', 'save and load the Float16LossScaler state dict for checkpointing training', 'review the AbstractOptimizer class and its step method for optimizer implementation patterns', 'implement a subclass of AbstractOptimizer that overrides the _do_step abstract method', 'use the AbstractOptimizer step method with an optional closure to compute loss', 'configure a ParameterCollection as an iterable of tensors or parameter group dicts', 'override the _do_step method in a custom optimizer to perform gradient updates']
```

Usage

```
{'create_standard_fp16_loss_scaler': 'create a StandardFloat16LossScaler with custom init_scale and scale_window for FP16 training', 'run_optimizer_step_with_scaler': 'run an optimizer step using Float16LossScaler to get scaled gradient results', 'unscale_gradients_before_clipping': 'unscale optimizer gradients using the loss scaler before gradient clipping', 'check_manual_grad_scaling_support': 'check if an optimizer supports manual gradient scaling via supports_manual_grad_scaling', 'save_load_scaler_state_dict': 'save and load the Float16LossScaler state dict for checkpointing training'}
```

## File: facebookresearch_fairseq2/src/fairseq2/optim/optimizer.py

Prompts

```
['create a StandardFloat16LossScaler with custom init_scale and scale_window for FP16 training', 'run an optimizer step using Float16LossScaler to get scaled gradient results', 'unscale optimizer gradients using the loss scaler before gradient clipping', 'check if an optimizer supports manual gradient scaling via supports_manual_grad_scaling', 'save and load the Float16LossScaler state dict for checkpointing training', 'review the AbstractOptimizer class and its step method for optimizer implementation patterns', 'implement a subclass of AbstractOptimizer that overrides the _do_step abstract method', 'use the AbstractOptimizer step method with an optional closure to compute loss', 'configure a ParameterCollection as an iterable of tensors or parameter group dicts', 'override the _do_step method in a custom optimizer to perform gradient updates']
```

Usage

```
{'review_AbstractOptimizer': 'review the AbstractOptimizer class and its step method for optimizer implementation patterns', 'implement_AbstractOptimizer_subclass': 'implement a subclass of AbstractOptimizer that overrides the _do_step abstract method', 'use_AbstractOptimizer_step': 'use the AbstractOptimizer step method with an optional closure to compute loss', 'configure_ParameterCollection': 'configure a ParameterCollection as an iterable of tensors or parameter group dicts', 'override_do_step': 'override the _do_step method in a custom optimizer to perform gradient updates'}
```

