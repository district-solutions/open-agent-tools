# Agent Python Tools

- repo: facebookresearch/stochasticgradientpush
- repo_uri: https://github.com/facebookresearch/stochastic_gradient_push

## File: facebookresearch_stochasticgradientpush/gossip/utils/helpers.py

Prompts

```
['flatten a list of PyTorch tensors into a single contiguous 1D buffer for batch operations', 'unflatten a 1D tensor buffer back into individual tensors using reference tensor shapes', 'group tensors by dtype, flatten each group, apply a distributed communication op, and unflatten results', 'create and lazy-initialize a new PyTorch distributed process group for a given list of ranks', 'group a list of PyTorch tensors by their data type into a dictionary', 'create a Meter instance with a custom print tag to track benchmark timing values', 'update a Meter with new values and optional count to compute running average and standard deviation', 'reset a Meter to clear all accumulated values including average, sum, count, and standard deviation', 'format a Meter as a CSV string showing current value, average, and standard deviation or MAD', 'create a stateful Meter that tracks value history and computes mean absolute deviation over time']
```

Usage

```
{'flatten_tensors': 'flatten a list of PyTorch tensors into a single contiguous 1D buffer for batch operations', 'unflatten_tensors': 'unflatten a 1D tensor buffer back into individual tensors using reference tensor shapes', 'communicate_tensors': 'group tensors by dtype, flatten each group, apply a distributed communication op, and unflatten results', 'create_process_group': 'create and lazy-initialize a new PyTorch distributed process group for a given list of ranks', 'group_by_dtype': 'group a list of PyTorch tensors by their data type into a dictionary'}
```

## File: facebookresearch_stochasticgradientpush/gossip/utils/metering.py

Prompts

```
['flatten a list of PyTorch tensors into a single contiguous 1D buffer for batch operations', 'unflatten a 1D tensor buffer back into individual tensors using reference tensor shapes', 'group tensors by dtype, flatten each group, apply a distributed communication op, and unflatten results', 'create and lazy-initialize a new PyTorch distributed process group for a given list of ranks', 'group a list of PyTorch tensors by their data type into a dictionary', 'create a Meter instance with a custom print tag to track benchmark timing values', 'update a Meter with new values and optional count to compute running average and standard deviation', 'reset a Meter to clear all accumulated values including average, sum, count, and standard deviation', 'format a Meter as a CSV string showing current value, average, and standard deviation or MAD', 'create a stateful Meter that tracks value history and computes mean absolute deviation over time']
```

Usage

```
{'create_Meter_instance': 'create a Meter instance with a custom print tag to track benchmark timing values', 'update_Meter_values': 'update a Meter with new values and optional count to compute running average and standard deviation', 'reset_Meter_state': 'reset a Meter to clear all accumulated values including average, sum, count, and standard deviation', 'format_Meter_csv': 'format a Meter as a CSV string showing current value, average, and standard deviation or MAD', 'create_stateful_Meter': 'create a stateful Meter that tracks value history and computes mean absolute deviation over time'}
```

