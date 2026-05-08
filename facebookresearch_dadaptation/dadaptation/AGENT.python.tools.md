# Agent Python Tools

- repo: facebookresearch/dadaptation
- repo_uri: https://github.com/facebookresearch/dadaptation

## File: facebookresearch_dadaptation/dadaptation/dadapt_adagrad.py

Prompts

```
['create a DAdaptAdaGrad optimizer instance with model parameters and default learning rate of 1.0', 'create a DAdaptAdaGrad optimizer with momentum enabled for smoother gradient updates across steps', 'create a DAdaptAdaGrad optimizer with L2 weight decay regularization applied to parameters', 'run a single optimization step using the DAdaptAdaGrad optimizer to update model parameters', 'configure the DAdaptAdaGrad optimizer with a custom growth rate to cap D estimate expansion', 'create a DAdaptAdam optimizer instance with automatic step-size adaptation for PyTorch model parameters', 'configure the DAdaptAdam optimizer with AdamW style decoupled weight decay enabled', 'configure the DAdaptAdam optimizer with Adam bias correction turned on for training', 'configure the DAdaptAdam optimizer with FSDP sharded parameter support for distributed training', 'create a DAdaptAdan optimizer with automatic step-size adaptation for training a PyTorch model', 'perform a single optimization step using the DAdaptAdan optimizer with an optional closure', 'restart the DAdaptAdan optimizer by resetting all internal state and momentum buffers', 'configure a DAdaptAdan optimizer with custom betas, weight decay, and growth rate parameters', 'review the DAdaptAdan optimizer class implementing Adan with D-Adaptation automatic step-sizes', 'create a DAdaptLion optimizer instance with default learning rate of 1.0 for model parameters', 'create a DAdaptLion optimizer with custom betas and weight decay for L2 regularization', 'run a DAdaptLion optimization step with a closure function that computes and returns the loss', 'review the DAdaptLion optimizer configuration including betas, d0 initial estimate, and fsdp settings', 'create a DAdaptSGD optimizer with automatic step-size adaptation for PyTorch model training', 'configure DAdaptSGD optimizer with momentum and weight decay parameters for stable training', 'run a training step with the DAdaptSGD optimizer using the step method', 'enable periodic logging of D-adaptation metrics like dlr, d_hat, and sk_norm during training', 'configure DAdaptSGD optimizer with FSDP support for sharded parameter training across GPUs']
```

Usage

```
{'create_optimizer_dadapt_adagrad': 'create a DAdaptAdaGrad optimizer instance with model parameters and default learning rate of 1.0', 'create_optimizer_with_momentum': 'create a DAdaptAdaGrad optimizer with momentum enabled for smoother gradient updates across steps', 'create_optimizer_with_weight_decay': 'create a DAdaptAdaGrad optimizer with L2 weight decay regularization applied to parameters', 'run_optimizer_step': 'run a single optimization step using the DAdaptAdaGrad optimizer to update model parameters', 'configure_optimizer_growth_rate': 'configure the DAdaptAdaGrad optimizer with a custom growth rate to cap D estimate expansion'}
```

## File: facebookresearch_dadaptation/dadaptation/dadapt_adam.py

Prompts

```
['create a DAdaptAdaGrad optimizer instance with model parameters and default learning rate of 1.0', 'create a DAdaptAdaGrad optimizer with momentum enabled for smoother gradient updates across steps', 'create a DAdaptAdaGrad optimizer with L2 weight decay regularization applied to parameters', 'run a single optimization step using the DAdaptAdaGrad optimizer to update model parameters', 'configure the DAdaptAdaGrad optimizer with a custom growth rate to cap D estimate expansion', 'create a DAdaptAdam optimizer instance with automatic step-size adaptation for PyTorch model parameters', 'configure the DAdaptAdam optimizer with AdamW style decoupled weight decay enabled', 'configure the DAdaptAdam optimizer with Adam bias correction turned on for training', 'configure the DAdaptAdam optimizer with FSDP sharded parameter support for distributed training', 'create a DAdaptAdan optimizer with automatic step-size adaptation for training a PyTorch model', 'perform a single optimization step using the DAdaptAdan optimizer with an optional closure', 'restart the DAdaptAdan optimizer by resetting all internal state and momentum buffers', 'configure a DAdaptAdan optimizer with custom betas, weight decay, and growth rate parameters', 'review the DAdaptAdan optimizer class implementing Adan with D-Adaptation automatic step-sizes', 'create a DAdaptLion optimizer instance with default learning rate of 1.0 for model parameters', 'create a DAdaptLion optimizer with custom betas and weight decay for L2 regularization', 'run a DAdaptLion optimization step with a closure function that computes and returns the loss', 'review the DAdaptLion optimizer configuration including betas, d0 initial estimate, and fsdp settings', 'create a DAdaptSGD optimizer with automatic step-size adaptation for PyTorch model training', 'configure DAdaptSGD optimizer with momentum and weight decay parameters for stable training', 'run a training step with the DAdaptSGD optimizer using the step method', 'enable periodic logging of D-adaptation metrics like dlr, d_hat, and sk_norm during training', 'configure DAdaptSGD optimizer with FSDP support for sharded parameter training across GPUs']
```

Usage

```
{'create_optimizer_dadapt_adam': 'create a DAdaptAdam optimizer instance with automatic step-size adaptation for PyTorch model parameters', 'run_optimizer_step': 'run a single optimization step using the DAdaptAdam optimizer with optional closure function', 'configure_decoupled_weight_decay': 'configure the DAdaptAdam optimizer with AdamW style decoupled weight decay enabled', 'configure_bias_correction': 'configure the DAdaptAdam optimizer with Adam bias correction turned on for training', 'configure_fsdp_support': 'configure the DAdaptAdam optimizer with FSDP sharded parameter support for distributed training'}
```

## File: facebookresearch_dadaptation/dadaptation/dadapt_adan.py

Prompts

```
['create a DAdaptAdaGrad optimizer instance with model parameters and default learning rate of 1.0', 'create a DAdaptAdaGrad optimizer with momentum enabled for smoother gradient updates across steps', 'create a DAdaptAdaGrad optimizer with L2 weight decay regularization applied to parameters', 'run a single optimization step using the DAdaptAdaGrad optimizer to update model parameters', 'configure the DAdaptAdaGrad optimizer with a custom growth rate to cap D estimate expansion', 'create a DAdaptAdam optimizer instance with automatic step-size adaptation for PyTorch model parameters', 'configure the DAdaptAdam optimizer with AdamW style decoupled weight decay enabled', 'configure the DAdaptAdam optimizer with Adam bias correction turned on for training', 'configure the DAdaptAdam optimizer with FSDP sharded parameter support for distributed training', 'create a DAdaptAdan optimizer with automatic step-size adaptation for training a PyTorch model', 'perform a single optimization step using the DAdaptAdan optimizer with an optional closure', 'restart the DAdaptAdan optimizer by resetting all internal state and momentum buffers', 'configure a DAdaptAdan optimizer with custom betas, weight decay, and growth rate parameters', 'review the DAdaptAdan optimizer class implementing Adan with D-Adaptation automatic step-sizes', 'create a DAdaptLion optimizer instance with default learning rate of 1.0 for model parameters', 'create a DAdaptLion optimizer with custom betas and weight decay for L2 regularization', 'run a DAdaptLion optimization step with a closure function that computes and returns the loss', 'review the DAdaptLion optimizer configuration including betas, d0 initial estimate, and fsdp settings', 'create a DAdaptSGD optimizer with automatic step-size adaptation for PyTorch model training', 'configure DAdaptSGD optimizer with momentum and weight decay parameters for stable training', 'run a training step with the DAdaptSGD optimizer using the step method', 'enable periodic logging of D-adaptation metrics like dlr, d_hat, and sk_norm during training', 'configure DAdaptSGD optimizer with FSDP support for sharded parameter training across GPUs']
```

Usage

```
{'create_optimizer_dadapt_adan': 'create a DAdaptAdan optimizer with automatic step-size adaptation for training a PyTorch model', 'step_optimizer_dadapt_adan': 'perform a single optimization step using the DAdaptAdan optimizer with an optional closure', 'restart_optimizer_dadapt_adan': 'restart the DAdaptAdan optimizer by resetting all internal state and momentum buffers', 'configure_optimizer_dadapt_adan': 'configure a DAdaptAdan optimizer with custom betas, weight decay, and growth rate parameters', 'review_class_dadapt_adan': 'review the DAdaptAdan optimizer class implementing Adan with D-Adaptation automatic step-sizes'}
```

## File: facebookresearch_dadaptation/dadaptation/dadapt_lion.py

Prompts

```
['create a DAdaptAdaGrad optimizer instance with model parameters and default learning rate of 1.0', 'create a DAdaptAdaGrad optimizer with momentum enabled for smoother gradient updates across steps', 'create a DAdaptAdaGrad optimizer with L2 weight decay regularization applied to parameters', 'run a single optimization step using the DAdaptAdaGrad optimizer to update model parameters', 'configure the DAdaptAdaGrad optimizer with a custom growth rate to cap D estimate expansion', 'create a DAdaptAdam optimizer instance with automatic step-size adaptation for PyTorch model parameters', 'configure the DAdaptAdam optimizer with AdamW style decoupled weight decay enabled', 'configure the DAdaptAdam optimizer with Adam bias correction turned on for training', 'configure the DAdaptAdam optimizer with FSDP sharded parameter support for distributed training', 'create a DAdaptAdan optimizer with automatic step-size adaptation for training a PyTorch model', 'perform a single optimization step using the DAdaptAdan optimizer with an optional closure', 'restart the DAdaptAdan optimizer by resetting all internal state and momentum buffers', 'configure a DAdaptAdan optimizer with custom betas, weight decay, and growth rate parameters', 'review the DAdaptAdan optimizer class implementing Adan with D-Adaptation automatic step-sizes', 'create a DAdaptLion optimizer instance with default learning rate of 1.0 for model parameters', 'create a DAdaptLion optimizer with custom betas and weight decay for L2 regularization', 'run a DAdaptLion optimization step with a closure function that computes and returns the loss', 'review the DAdaptLion optimizer configuration including betas, d0 initial estimate, and fsdp settings', 'create a DAdaptSGD optimizer with automatic step-size adaptation for PyTorch model training', 'configure DAdaptSGD optimizer with momentum and weight decay parameters for stable training', 'run a training step with the DAdaptSGD optimizer using the step method', 'enable periodic logging of D-adaptation metrics like dlr, d_hat, and sk_norm during training', 'configure DAdaptSGD optimizer with FSDP support for sharded parameter training across GPUs']
```

Usage

```
{'create_optimizer_dadaptlion': 'create a DAdaptLion optimizer instance with default learning rate of 1.0 for model parameters', 'create_optimizer_dadaptlion_with_weight_decay': 'create a DAdaptLion optimizer with custom betas and weight decay for L2 regularization', 'run_optimizer_step': 'run a single optimization step using DAdaptLion to update model parameters with automatic step-size', 'run_optimizer_step_with_closure': 'run a DAdaptLion optimization step with a closure function that computes and returns the loss', 'review_optimizer_dadaptlion_config': 'review the DAdaptLion optimizer configuration including betas, d0 initial estimate, and fsdp settings'}
```

## File: facebookresearch_dadaptation/dadaptation/dadapt_sgd.py

Prompts

```
['create a DAdaptAdaGrad optimizer instance with model parameters and default learning rate of 1.0', 'create a DAdaptAdaGrad optimizer with momentum enabled for smoother gradient updates across steps', 'create a DAdaptAdaGrad optimizer with L2 weight decay regularization applied to parameters', 'run a single optimization step using the DAdaptAdaGrad optimizer to update model parameters', 'configure the DAdaptAdaGrad optimizer with a custom growth rate to cap D estimate expansion', 'create a DAdaptAdam optimizer instance with automatic step-size adaptation for PyTorch model parameters', 'configure the DAdaptAdam optimizer with AdamW style decoupled weight decay enabled', 'configure the DAdaptAdam optimizer with Adam bias correction turned on for training', 'configure the DAdaptAdam optimizer with FSDP sharded parameter support for distributed training', 'create a DAdaptAdan optimizer with automatic step-size adaptation for training a PyTorch model', 'perform a single optimization step using the DAdaptAdan optimizer with an optional closure', 'restart the DAdaptAdan optimizer by resetting all internal state and momentum buffers', 'configure a DAdaptAdan optimizer with custom betas, weight decay, and growth rate parameters', 'review the DAdaptAdan optimizer class implementing Adan with D-Adaptation automatic step-sizes', 'create a DAdaptLion optimizer instance with default learning rate of 1.0 for model parameters', 'create a DAdaptLion optimizer with custom betas and weight decay for L2 regularization', 'run a DAdaptLion optimization step with a closure function that computes and returns the loss', 'review the DAdaptLion optimizer configuration including betas, d0 initial estimate, and fsdp settings', 'create a DAdaptSGD optimizer with automatic step-size adaptation for PyTorch model training', 'configure DAdaptSGD optimizer with momentum and weight decay parameters for stable training', 'run a training step with the DAdaptSGD optimizer using the step method', 'enable periodic logging of D-adaptation metrics like dlr, d_hat, and sk_norm during training', 'configure DAdaptSGD optimizer with FSDP support for sharded parameter training across GPUs']
```

Usage

```
{'create_DAdaptSGD_optimizer': 'create a DAdaptSGD optimizer with automatic step-size adaptation for PyTorch model training', 'configure_DAdaptSGD_momentum': 'configure DAdaptSGD optimizer with momentum and weight decay parameters for stable training', 'run_DAdaptSGD_step': 'run a training step with the DAdaptSGD optimizer using the step method', 'enable_DAdaptSGD_logging': 'enable periodic logging of D-adaptation metrics like dlr, d_hat, and sk_norm during training', 'configure_DAdaptSGD_fsdp': 'configure DAdaptSGD optimizer with FSDP support for sharded parameter training across GPUs'}
```

