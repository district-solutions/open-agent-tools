# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/secure_aggregation/tests/test_secagg_integration.py

Prompts

```
['test that training with secure aggregation produces a different model than training without secure aggregation', 'test that secure aggregation produces different results even with a large fixed point range and scaling factor of 1', 'test that overflow parameters are reported correctly in stdout and tensorboard results during secure aggregation training', 'train a federated learning model with secure aggregation enabled using FixedPointConfig and SyncSecAggServerConfig', 'load a dummy alphabet dataset for N users with configurable shard size and local batch size for FL training', 'test the FixedPointConverter initialization with num_bytes and scaling_factor config values', 'test converting floating point tensors to fixed point using FixedPointConverter with clamping', 'test converting fixed point tensors back to floating point using FixedPointConverter', 'test the SecureAggregator params_to_fixedpoint and params_to_float methods on model parameters', 'test the SyncSecAggServer step method with client updates and fixed point aggregation']
```

Usage

```
{'test_secagg_produces_different_model': 'test that training with secure aggregation produces a different model than training without secure aggregation', 'test_secagg_large_range_rounding': 'test that secure aggregation produces different results even with a large fixed point range and scaling factor of 1', 'test_overflow_reporting_metrics': 'test that overflow parameters are reported correctly in stdout and tensorboard results during secure aggregation training', 'train_fl_model_with_secagg': 'train a federated learning model with secure aggregation enabled using FixedPointConfig and SyncSecAggServerConfig', 'load_dummy_alphabet_data': 'load a dummy alphabet dataset for N users with configurable shard size and local batch size for FL training'}
```

## File: facebookresearch_flsim/flsim/secure_aggregation/tests/test_secure_aggregation.py

Prompts

```
['test that training with secure aggregation produces a different model than training without secure aggregation', 'test that secure aggregation produces different results even with a large fixed point range and scaling factor of 1', 'test that overflow parameters are reported correctly in stdout and tensorboard results during secure aggregation training', 'train a federated learning model with secure aggregation enabled using FixedPointConfig and SyncSecAggServerConfig', 'load a dummy alphabet dataset for N users with configurable shard size and local batch size for FL training', 'test the FixedPointConverter initialization with num_bytes and scaling_factor config values', 'test converting floating point tensors to fixed point using FixedPointConverter with clamping', 'test converting fixed point tensors back to floating point using FixedPointConverter', 'test the SecureAggregator params_to_fixedpoint and params_to_float methods on model parameters', 'test the SyncSecAggServer step method with client updates and fixed point aggregation']
```

Usage

```
{'test_fixedpoint_converter_init': 'test the FixedPointConverter initialization with num_bytes and scaling_factor config values', 'test_floating_to_fixedpoint_conversion': 'test converting floating point tensors to fixed point using FixedPointConverter with clamping', 'test_fixed_to_floating_conversion': 'test converting fixed point tensors back to floating point using FixedPointConverter', 'test_secure_aggregator_params_conversion': 'test the SecureAggregator params_to_fixedpoint and params_to_float methods on model parameters', 'test_secure_aggregator_step': 'test the SyncSecAggServer step method with client updates and fixed point aggregation'}
```

