# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/models/ema/ema.py

Prompts

```
['create an EMA object from a model and config to track exponentially decayed parameters', 'update the EMA model with new model weights after each training step', 'restore EMA model parameters from a saved state dict checkpoint', 'load EMA smoothed parameters back into a regular model for inference', 'build and store fp32 copies of EMA parameters for precision updates']
```

Usage

```
{'create_ema_model': 'create an EMA object from a model and config to track exponentially decayed parameters', 'step_ema_update': 'update the EMA model with new model weights after each training step', 'restore_ema_state': 'restore EMA model parameters from a saved state dict checkpoint', 'reverse_ema_to_model': 'load EMA smoothed parameters back into a regular model for inference', 'build_fp32_params': 'build and store fp32 copies of EMA parameters for precision updates'}
```

