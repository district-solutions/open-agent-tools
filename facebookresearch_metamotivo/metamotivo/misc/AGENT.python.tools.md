# Agent Python Tools

- repo: facebookresearch/metamotivo
- repo_uri: https://github.com/facebookresearch/metamotivo

## File: facebookresearch_metamotivo/metamotivo/misc/zbuffer.py

Prompts

```
['create a ZBuffer with a given capacity, dimension, and device for storing PyTorch tensors', 'add a batch of PyTorch tensor data to the ZBuffer, wrapping around when full', 'sample a random subset of stored tensors from the ZBuffer and move them to a target device', 'check the current number of elements stored in the ZBuffer using the len function', 'check whether the ZBuffer is empty before attempting to sample or add data']
```

Usage

```
{'create_zbuffer_instance': 'create a ZBuffer with a given capacity, dimension, and device for storing PyTorch tensors', 'add_data_to_zbuffer': 'add a batch of PyTorch tensor data to the ZBuffer, wrapping around when full', 'sample_from_zbuffer': 'sample a random subset of stored tensors from the ZBuffer and move them to a target device', 'check_zbuffer_length': 'check the current number of elements stored in the ZBuffer using the len function', 'check_zbuffer_empty': 'check whether the ZBuffer is empty before attempting to sample or add data'}
```

