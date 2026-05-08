# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/utils/test/test_tensor_utils.py

Prompts

```
['convert a PyTorch state dict into a single flattened column tensor in sorted key order', 'convert a flattened vector back into a state dict matching a reference state dict shape', 'generate a reproducible random permutation tensor of numbers 0 through N-1 with an optional seed', 'randomly shuffle the elements of a PyTorch tensor while preserving its original shape', 'randomly shuffle each tensor in a PyTorch state dict using per-key derived seeds']
```

Usage

```
{'vectorize_state_dict': 'convert a PyTorch state dict into a single flattened column tensor in sorted key order', 'unvectorize_tensor': 'convert a flattened vector back into a state dict matching a reference state dict shape', 'perm_generate': 'generate a reproducible random permutation tensor of numbers 0 through N-1 with an optional seed', 'shuffle_tensor_elements': 'randomly shuffle the elements of a PyTorch tensor while preserving its original shape', 'shuffle_state_dict_tensors': 'randomly shuffle each tensor in a PyTorch state dict using per-key derived seeds'}
```

