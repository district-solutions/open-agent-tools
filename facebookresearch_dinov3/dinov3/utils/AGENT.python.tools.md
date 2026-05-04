# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/utils/cluster.py

Prompts

```
['get SLURM executor parameters for a given number of nodes and GPUs per node on a cluster', 'get the SLURM account name for a specified cluster type', 'get the checkpoint directory path for a given cluster type', "get the user-specific checkpoint path under the current user's home on the cluster", 'get the SLURM partition name for a given cluster type', 'load a custom callable by name from a Python module file path', 'temporarily change the working directory and sys.path to a new directory', 'review the load_custom_callable function that dynamically imports and retrieves callables from module files', 'test the load_custom_callable function with a sample module path and callable name', 'refactor the change_working_dir_and_pythonpath context manager to support additional environment variable changes', "convert a string like 'float32' to the corresponding torch.dtype using as_torch_dtype", 'convert a numpy dtype object to the corresponding torch.dtype using as_torch_dtype', 'pass an existing torch.dtype through as_torch_dtype and get it back unchanged', 'review the as_torch_dtype function to understand how it handles str, numpy, and torch dtype inputs', 'summarize the TypeSpec type alias which accepts str, numpy dtype, or torch dtype as valid inputs', 'concatenate a list of PyTorch tensors while preserving their original shapes for later uncat', 'split a flattened tensor back into a list of tensors using previously saved shapes and token counts', 'recursively replace child modules in a PyTorch nn.Module by applying a callable function to each', 'recursively apply a callable function to each named module in a PyTorch nn.Module tree', 'fix all random seeds for PyTorch, CUDA, NumPy, and Python random to ensure reproducibility']
```

Usage

```
{'get_slurm_executor_parameters': 'get SLURM executor parameters for a given number of nodes and GPUs per node on a cluster', 'get_slurm_account': 'get the SLURM account name for a specified cluster type', 'get_checkpoint_path': 'get the checkpoint directory path for a given cluster type', 'get_user_checkpoint_path': "get the user-specific checkpoint path under the current user's home on the cluster", 'get_slurm_partition': 'get the SLURM partition name for a given cluster type'}
```

## File: facebookresearch_dinov3/dinov3/utils/custom_callable.py

Prompts

```
['get SLURM executor parameters for a given number of nodes and GPUs per node on a cluster', 'get the SLURM account name for a specified cluster type', 'get the checkpoint directory path for a given cluster type', "get the user-specific checkpoint path under the current user's home on the cluster", 'get the SLURM partition name for a given cluster type', 'load a custom callable by name from a Python module file path', 'temporarily change the working directory and sys.path to a new directory', 'review the load_custom_callable function that dynamically imports and retrieves callables from module files', 'test the load_custom_callable function with a sample module path and callable name', 'refactor the change_working_dir_and_pythonpath context manager to support additional environment variable changes', "convert a string like 'float32' to the corresponding torch.dtype using as_torch_dtype", 'convert a numpy dtype object to the corresponding torch.dtype using as_torch_dtype', 'pass an existing torch.dtype through as_torch_dtype and get it back unchanged', 'review the as_torch_dtype function to understand how it handles str, numpy, and torch dtype inputs', 'summarize the TypeSpec type alias which accepts str, numpy dtype, or torch dtype as valid inputs', 'concatenate a list of PyTorch tensors while preserving their original shapes for later uncat', 'split a flattened tensor back into a list of tensors using previously saved shapes and token counts', 'recursively replace child modules in a PyTorch nn.Module by applying a callable function to each', 'recursively apply a callable function to each named module in a PyTorch nn.Module tree', 'fix all random seeds for PyTorch, CUDA, NumPy, and Python random to ensure reproducibility']
```

Usage

```
{'load_custom_callable': 'load a custom callable by name from a Python module file path', 'change_working_dir_and_pythonpath': 'temporarily change the working directory and sys.path to a new directory', 'review_load_custom_callable': 'review the load_custom_callable function that dynamically imports and retrieves callables from module files', 'test_load_custom_callable': 'test the load_custom_callable function with a sample module path and callable name', 'refactor_change_working_dir_and_pythonpath': 'refactor the change_working_dir_and_pythonpath context manager to support additional environment variable changes'}
```

## File: facebookresearch_dinov3/dinov3/utils/dtype.py

Prompts

```
['get SLURM executor parameters for a given number of nodes and GPUs per node on a cluster', 'get the SLURM account name for a specified cluster type', 'get the checkpoint directory path for a given cluster type', "get the user-specific checkpoint path under the current user's home on the cluster", 'get the SLURM partition name for a given cluster type', 'load a custom callable by name from a Python module file path', 'temporarily change the working directory and sys.path to a new directory', 'review the load_custom_callable function that dynamically imports and retrieves callables from module files', 'test the load_custom_callable function with a sample module path and callable name', 'refactor the change_working_dir_and_pythonpath context manager to support additional environment variable changes', "convert a string like 'float32' to the corresponding torch.dtype using as_torch_dtype", 'convert a numpy dtype object to the corresponding torch.dtype using as_torch_dtype', 'pass an existing torch.dtype through as_torch_dtype and get it back unchanged', 'review the as_torch_dtype function to understand how it handles str, numpy, and torch dtype inputs', 'summarize the TypeSpec type alias which accepts str, numpy dtype, or torch dtype as valid inputs', 'concatenate a list of PyTorch tensors while preserving their original shapes for later uncat', 'split a flattened tensor back into a list of tensors using previously saved shapes and token counts', 'recursively replace child modules in a PyTorch nn.Module by applying a callable function to each', 'recursively apply a callable function to each named module in a PyTorch nn.Module tree', 'fix all random seeds for PyTorch, CUDA, NumPy, and Python random to ensure reproducibility']
```

Usage

```
{'convert_string_to_torch_dtype': "convert a string like 'float32' to the corresponding torch.dtype using as_torch_dtype", 'convert_numpy_to_torch_dtype': 'convert a numpy dtype object to the corresponding torch.dtype using as_torch_dtype', 'pass_torch_dtype_through': 'pass an existing torch.dtype through as_torch_dtype and get it back unchanged', 'review_as_torch_dtype': 'review the as_torch_dtype function to understand how it handles str, numpy, and torch dtype inputs', 'summarize_TypeSpec': 'summarize the TypeSpec type alias which accepts str, numpy dtype, or torch dtype as valid inputs'}
```

## File: facebookresearch_dinov3/dinov3/utils/utils.py

Prompts

```
['get SLURM executor parameters for a given number of nodes and GPUs per node on a cluster', 'get the SLURM account name for a specified cluster type', 'get the checkpoint directory path for a given cluster type', "get the user-specific checkpoint path under the current user's home on the cluster", 'get the SLURM partition name for a given cluster type', 'load a custom callable by name from a Python module file path', 'temporarily change the working directory and sys.path to a new directory', 'review the load_custom_callable function that dynamically imports and retrieves callables from module files', 'test the load_custom_callable function with a sample module path and callable name', 'refactor the change_working_dir_and_pythonpath context manager to support additional environment variable changes', "convert a string like 'float32' to the corresponding torch.dtype using as_torch_dtype", 'convert a numpy dtype object to the corresponding torch.dtype using as_torch_dtype', 'pass an existing torch.dtype through as_torch_dtype and get it back unchanged', 'review the as_torch_dtype function to understand how it handles str, numpy, and torch dtype inputs', 'summarize the TypeSpec type alias which accepts str, numpy dtype, or torch dtype as valid inputs', 'concatenate a list of PyTorch tensors while preserving their original shapes for later uncat', 'split a flattened tensor back into a list of tensors using previously saved shapes and token counts', 'recursively replace child modules in a PyTorch nn.Module by applying a callable function to each', 'recursively apply a callable function to each named module in a PyTorch nn.Module tree', 'fix all random seeds for PyTorch, CUDA, NumPy, and Python random to ensure reproducibility']
```

Usage

```
{'cat_keep_shapes_tensors': 'concatenate a list of PyTorch tensors while preserving their original shapes for later uncat', 'uncat_with_shapes_tensors': 'split a flattened tensor back into a list of tensors using previously saved shapes and token counts', 'named_replace_module': 'recursively replace child modules in a PyTorch nn.Module by applying a callable function to each', 'named_apply_module': 'recursively apply a callable function to each named module in a PyTorch nn.Module tree', 'fix_random_seeds': 'fix all random seeds for PyTorch, CUDA, NumPy, and Python random to ensure reproducibility'}
```

