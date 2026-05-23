# Agent Python Tools

- repo: facebookresearch/torchdim
- repo_uri: https://github.com/facebookresearch/torchdim

## File: facebookresearch_torchdim/third_party/functorch/op_analysis/gen_data.py

Prompts

```
['generate batching rule data by calling gen_data with FuncTorchBatched ops and output file name', 'generate decomposition analysis CSV by calling gen_data with opinfo ops and decomposed ops lists', 'get all aten ops registered for a PyTorch dispatch key like CompositeImplicitAutograd or FuncTorchBatched', 'create a lambda that checks if an op name exists in a given list of names', 'create a lambda that checks if an op full name exists in a given list of names']
```

Usage

```
{'gen_data_batching_rules': 'generate batching rule data by calling gen_data with FuncTorchBatched ops and output file name', 'gen_data_decompositions': 'generate decomposition analysis CSV by calling gen_data with opinfo ops and decomposed ops lists', 'get_ops_for_key': 'get all aten ops registered for a PyTorch dispatch key like CompositeImplicitAutograd or FuncTorchBatched', 'name_check_filter': 'create a lambda that checks if an op name exists in a given list of names', 'full_name_check_filter': 'create a lambda that checks if an op full name exists in a given list of names'}
```

