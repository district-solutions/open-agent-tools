# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/models/ema/ema.py

Prompts

```
['build an EMA object from a Fairseq model and config to track exponentially decayed model params', 'step the EMA model with new model weights after each training update', 'restore the EMA model from a saved state dict checkpoint', 'reverse EMA params into a model for inference or fine-tuning from the smoothed weights', 'build fp32 copies of EMA params for higher precision exponential moving average updates']
```

Usage

```
{'build_ema_model': 'build an EMA object from a Fairseq model and config to track exponentially decayed model params', 'step_ema_update': 'step the EMA model with new model weights after each training update', 'restore_ema_state': 'restore the EMA model from a saved state dict checkpoint', 'reverse_ema_to_model': 'reverse EMA params into a model for inference or fine-tuning from the smoothed weights', 'build_fp32_ema_params': 'build fp32 copies of EMA params for higher precision exponential moving average updates'}
```

