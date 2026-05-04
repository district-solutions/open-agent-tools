# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/secure_aggregation/secure_aggregator.py

Prompts

```
['create a FixedPointConverter and convert a PyTorch tensor from floating point to fixed point using to_fixedpoint', 'use FixedPointConverter to_float to convert a fixed point tensor back to floating point', 'build a SecureAggregator and convert all trainable model parameters from floating point to fixed point', 'use SecureAggregator params_to_float to convert all model parameters from fixed point back to floating point', 'call update_aggr_overflow_and_model to track overflow during aggregation and clamp model values to fixed point range']
```

Usage

```
{'convert_float_tensor_to_fixedpoint': 'create a FixedPointConverter and convert a PyTorch tensor from floating point to fixed point using to_fixedpoint', 'convert_fixedpoint_tensor_to_float': 'use FixedPointConverter to_float to convert a fixed point tensor back to floating point', 'convert_model_params_to_fixedpoint': 'build a SecureAggregator and convert all trainable model parameters from floating point to fixed point', 'convert_model_params_to_float': 'use SecureAggregator params_to_float to convert all model parameters from fixed point back to floating point', 'track_aggregation_overflow_and_clamp_model': 'call update_aggr_overflow_and_model to track overflow during aggregation and clamp model values to fixed point range'}
```

