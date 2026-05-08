# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/utils/tensor_utils.py

Prompts

```
['convert a PyTorch state dict into a single flattened column tensor in a repeatable sorted way', 'convert a flattened vector back into a state dict matching the shapes of a reference state dict', 'generate a tensor with numbers 0 through N-1 ordered randomly using an optional seed for reproducibility', 'randomly shuffle the elements of a PyTorch tensor while preserving its original shape', 'randomly shuffle each tensor in a PyTorch state dict using incrementing seeds per key']
```

Usage

```
{'vectorize_state_dict': 'convert a PyTorch state dict into a single flattened column tensor in a repeatable sorted way', 'unvectorize_to_state_dict': 'convert a flattened vector back into a state dict matching the shapes of a reference state dict', 'generate_permutation_tensor': 'generate a tensor with numbers 0 through N-1 ordered randomly using an optional seed for reproducibility', 'shuffle_tensor_elements': 'randomly shuffle the elements of a PyTorch tensor while preserving its original shape', 'shuffle_state_dict_tensors': 'randomly shuffle each tensor in a PyTorch state dict using incrementing seeds per key'}
```

