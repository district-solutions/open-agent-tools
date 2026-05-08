# Agent Python Tools

- repo: facebookresearch/dadaptation
- repo_uri: https://github.com/facebookresearch/dadaptation

## File: facebookresearch_dadaptation/dadaptation/experimental/dadapt_adam_preprint.py

Prompts

```
['create a DAdaptAdamPreprint optimizer instance with model parameters and default learning rate of 1.0', 'run a single optimization step using the DAdaptAdamPreprint optimizer step method', 'configure the DAdaptAdamPreprint optimizer with decoupled AdamW style weight decay enabled', 'configure the DAdaptAdamPreprint optimizer with a custom growth rate for learning rate warmup', 'review the DAdaptAdamPreprint step method to understand D-adaptation and FSDP distributed reduction logic', 'create a DAdaptAdanIP optimizer with automatic step-size adaptation for PyTorch model parameters', 'run a single optimization step using the DAdaptAdanIP optimizer with optional closure', 'restart the DAdaptAdanIP optimizer by resetting all internal state and momentum buffers', 'review the DAdaptAdanIP optimizer class implementing Adan with D-Adaptation automatic step-sizes', 'summarize the to_real utility function that extracts the real part from complex tensors']
```

Usage

```
{'create_optimizer_dadapt_adam_preprint': 'create a DAdaptAdamPreprint optimizer instance with model parameters and default learning rate of 1.0', 'run_optimizer_step': 'run a single optimization step using the DAdaptAdamPreprint optimizer step method', 'configure_optimizer_with_decoupled_decay': 'configure the DAdaptAdamPreprint optimizer with decoupled AdamW style weight decay enabled', 'configure_optimizer_with_growth_rate': 'configure the DAdaptAdamPreprint optimizer with a custom growth rate for learning rate warmup', 'review_optimizer_step_logic': 'review the DAdaptAdamPreprint step method to understand D-adaptation and FSDP distributed reduction logic'}
```

## File: facebookresearch_dadaptation/dadaptation/experimental/dadapt_adan_ip.py

Prompts

```
['create a DAdaptAdamPreprint optimizer instance with model parameters and default learning rate of 1.0', 'run a single optimization step using the DAdaptAdamPreprint optimizer step method', 'configure the DAdaptAdamPreprint optimizer with decoupled AdamW style weight decay enabled', 'configure the DAdaptAdamPreprint optimizer with a custom growth rate for learning rate warmup', 'review the DAdaptAdamPreprint step method to understand D-adaptation and FSDP distributed reduction logic', 'create a DAdaptAdanIP optimizer with automatic step-size adaptation for PyTorch model parameters', 'run a single optimization step using the DAdaptAdanIP optimizer with optional closure', 'restart the DAdaptAdanIP optimizer by resetting all internal state and momentum buffers', 'review the DAdaptAdanIP optimizer class implementing Adan with D-Adaptation automatic step-sizes', 'summarize the to_real utility function that extracts the real part from complex tensors']
```

Usage

```
{'create_optimizer_dadapt_adan_ip': 'create a DAdaptAdanIP optimizer with automatic step-size adaptation for PyTorch model parameters', 'run_step_dadapt_adan_ip': 'run a single optimization step using the DAdaptAdanIP optimizer with optional closure', 'restart_optimizer_dadapt_adan_ip': 'restart the DAdaptAdanIP optimizer by resetting all internal state and momentum buffers', 'review_class_dadapt_adan_ip': 'review the DAdaptAdanIP optimizer class implementing Adan with D-Adaptation automatic step-sizes', 'summarize_to_real_function': 'summarize the to_real utility function that extracts the real part from complex tensors'}
```

