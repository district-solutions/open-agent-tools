# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/experimental/optim/dynamic_loss_scaler.py

Prompts

```
['create a DynamicLossScaler instance with custom init_scale and scale_factor parameters', 'scale the model loss outputs by multiplying with the current loss_scale factor', 'unscale gradients and step the optimizer using the scaler step method', 'update the loss scale factor after a successful optimizer step completes', 'unscale the optimizer gradients by dividing them by the current loss scale']
```

Usage

```
{'create_dynamic_loss_scaler': 'create a DynamicLossScaler instance with custom init_scale and scale_factor parameters', 'scale_loss_outputs': 'scale the model loss outputs by multiplying with the current loss_scale factor', 'step_optimizer_with_scaler': 'unscale gradients and step the optimizer using the scaler step method', 'update_scaler_after_step': 'update the loss scale factor after a successful optimizer step completes', 'unscale_optimizer_gradients': 'unscale the optimizer gradients by dividing them by the current loss scale'}
```

