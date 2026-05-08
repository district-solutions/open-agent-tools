# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/common/compat.py

Prompts

```
['use meshgrid_ij to create a meshgrid with ij indexing across PyTorch versions', 'use prod to compute the product of an iterable with an optional start value', 'test meshgrid_ij with multiple 1D tensors to verify ij indexing output', 'test prod with a list of integers and a custom start value', 'review the compat module for PyTorch and Python version compatibility functions', "create a torch.device object from a device string like 'cuda' or 'cpu' with automatic index resolution", 'convert a torch.device object to a resolved device with explicit CUDA index if needed', 'get the device of a torch.Tensor and return it as a torch.device object', 'get the device from a tensor or fall back to a specified default or CPU', 'override the device detection by providing an explicit device string or torch.device', 'create a LinearWithRepeat module with specified in_features and out_features for efficient repeated linear transforms', 'run the LinearWithRepeat forward pass with a tuple of two tensors as input', 'reset the LinearWithRepeat weight and bias parameters using Kaiming uniform initialization', 'review the LinearWithRepeat class to avoid expensive tensor concatenation and expansion in ray marching', 'build a LinearWithRepeat layer to apply a linear transform on per-position and per-ray features together']
```

Usage

```
{'use_meshgrid_ij': 'use meshgrid_ij to create a meshgrid with ij indexing across PyTorch versions', 'use_prod': 'use prod to compute the product of an iterable with an optional start value', 'test_meshgrid_ij': 'test meshgrid_ij with multiple 1D tensors to verify ij indexing output', 'test_prod': 'test prod with a list of integers and a custom start value', 'review_compat': 'review the compat module for PyTorch and Python version compatibility functions'}
```

## File: facebookresearch_pytorch3d/pytorch3d/common/datatypes.py

Prompts

```
['use meshgrid_ij to create a meshgrid with ij indexing across PyTorch versions', 'use prod to compute the product of an iterable with an optional start value', 'test meshgrid_ij with multiple 1D tensors to verify ij indexing output', 'test prod with a list of integers and a custom start value', 'review the compat module for PyTorch and Python version compatibility functions', "create a torch.device object from a device string like 'cuda' or 'cpu' with automatic index resolution", 'convert a torch.device object to a resolved device with explicit CUDA index if needed', 'get the device of a torch.Tensor and return it as a torch.device object', 'get the device from a tensor or fall back to a specified default or CPU', 'override the device detection by providing an explicit device string or torch.device', 'create a LinearWithRepeat module with specified in_features and out_features for efficient repeated linear transforms', 'run the LinearWithRepeat forward pass with a tuple of two tensors as input', 'reset the LinearWithRepeat weight and bias parameters using Kaiming uniform initialization', 'review the LinearWithRepeat class to avoid expensive tensor concatenation and expansion in ray marching', 'build a LinearWithRepeat layer to apply a linear transform on per-position and per-ray features together']
```

Usage

```
{'make_device_from_string': "create a torch.device object from a device string like 'cuda' or 'cpu' with automatic index resolution", 'make_device_from_torch_device': 'convert a torch.device object to a resolved device with explicit CUDA index if needed', 'get_device_from_tensor': 'get the device of a torch.Tensor and return it as a torch.device object', 'get_device_with_fallback': 'get the device from a tensor or fall back to a specified default or CPU', 'get_device_override': 'override the device detection by providing an explicit device string or torch.device'}
```

## File: facebookresearch_pytorch3d/pytorch3d/common/linear_with_repeat.py

Prompts

```
['use meshgrid_ij to create a meshgrid with ij indexing across PyTorch versions', 'use prod to compute the product of an iterable with an optional start value', 'test meshgrid_ij with multiple 1D tensors to verify ij indexing output', 'test prod with a list of integers and a custom start value', 'review the compat module for PyTorch and Python version compatibility functions', "create a torch.device object from a device string like 'cuda' or 'cpu' with automatic index resolution", 'convert a torch.device object to a resolved device with explicit CUDA index if needed', 'get the device of a torch.Tensor and return it as a torch.device object', 'get the device from a tensor or fall back to a specified default or CPU', 'override the device detection by providing an explicit device string or torch.device', 'create a LinearWithRepeat module with specified in_features and out_features for efficient repeated linear transforms', 'run the LinearWithRepeat forward pass with a tuple of two tensors as input', 'reset the LinearWithRepeat weight and bias parameters using Kaiming uniform initialization', 'review the LinearWithRepeat class to avoid expensive tensor concatenation and expansion in ray marching', 'build a LinearWithRepeat layer to apply a linear transform on per-position and per-ray features together']
```

Usage

```
{'create_LinearWithRepeat': 'create a LinearWithRepeat module with specified in_features and out_features for efficient repeated linear transforms', 'run_LinearWithRepeat_forward': 'run the LinearWithRepeat forward pass with a tuple of two tensors as input', 'reset_LinearWithRepeat_parameters': 'reset the LinearWithRepeat weight and bias parameters using Kaiming uniform initialization', 'review_LinearWithRepeat_efficiency': 'review the LinearWithRepeat class to avoid expensive tensor concatenation and expansion in ray marching', 'build_LinearWithRepeat_layer': 'build a LinearWithRepeat layer to apply a linear transform on per-position and per-ray features together'}
```

