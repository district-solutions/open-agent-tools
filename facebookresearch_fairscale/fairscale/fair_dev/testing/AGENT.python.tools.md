# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/fair_dev/testing/testing.py

Prompts

```
['set a random seed across python, numpy, and torch for reproducible testing', 'initialize torch distributed process group and rpc for multi-gpu testing across ranks', 'spawn a pytest test across multiple world sizes using torch multiprocessing', 'compare two objects including tensors, dicts, and lists for equality with tolerance', 'assert two torch nn modules have identical parameters and buffers', 'find a torch.nn.parameter.Parameter tensor on the heap matching a specific target shape', 'find any tensor on the heap matching a specific target shape including non-parameter tensors', 'test the find_tensor_by_shape function to verify it locates tensors of a given shape on the heap', 'review the find_tensor_by_shape function and its garbage collection heap scanning logic', 'refactor the find_tensor_by_shape function to return matching tensors instead of a boolean']
```

Usage

```
{'set_random_seed': 'set a random seed across python, numpy, and torch for reproducible testing', 'dist_init': 'initialize torch distributed process group and rpc for multi-gpu testing across ranks', 'torch_spawn': 'spawn a pytest test across multiple world sizes using torch multiprocessing', 'objects_are_equal': 'compare two objects including tensors, dicts, and lists for equality with tolerance', 'check_same_model_params': 'assert two torch nn modules have identical parameters and buffers'}
```

## File: facebookresearch_fairscale/fairscale/fair_dev/testing/testing_memory.py

Prompts

```
['set a random seed across python, numpy, and torch for reproducible testing', 'initialize torch distributed process group and rpc for multi-gpu testing across ranks', 'spawn a pytest test across multiple world sizes using torch multiprocessing', 'compare two objects including tensors, dicts, and lists for equality with tolerance', 'assert two torch nn modules have identical parameters and buffers', 'find a torch.nn.parameter.Parameter tensor on the heap matching a specific target shape', 'find any tensor on the heap matching a specific target shape including non-parameter tensors', 'test the find_tensor_by_shape function to verify it locates tensors of a given shape on the heap', 'review the find_tensor_by_shape function and its garbage collection heap scanning logic', 'refactor the find_tensor_by_shape function to return matching tensors instead of a boolean']
```

Usage

```
{'find_tensor_by_shape_param': 'find a torch.nn.parameter.Parameter tensor on the heap matching a specific target shape', 'find_tensor_by_shape_any': 'find any tensor on the heap matching a specific target shape including non-parameter tensors', 'test_find_tensor_by_shape': 'test the find_tensor_by_shape function to verify it locates tensors of a given shape on the heap', 'review_find_tensor_by_shape': 'review the find_tensor_by_shape function and its garbage collection heap scanning logic', 'refactor_find_tensor_by_shape': 'refactor the find_tensor_by_shape function to return matching tensors instead of a boolean'}
```

