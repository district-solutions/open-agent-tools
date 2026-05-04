# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/common/compat.py

Prompts

```
['solve a linear system AX=B for square matrix A using PyTorch tensors with version-compatible dispatch', 'solve a least squares problem AX=B for non-square matrix A using PyTorch tensors with version-compatible dispatch', 'compute the QR decomposition of a PyTorch tensor matrix A with version-compatible dispatch', 'review the solve function to understand how it dispatches between torch.linalg.solve and torch.solve based on PyTorch version', 'refactor the lstsq function to handle edge cases where A has fewer columns than rows', "create a torch.device object from a device string like 'cuda' or 'cpu'", 'create a torch.device object from an existing torch.device with resolved cuda index', 'get the device of a torch.Tensor and return it as a torch.device object', 'get a device by overriding with an explicit device string or torch.device', 'get the default CPU device when input is not a tensor and no device is provided']
```

Usage

```
{'solve_linear_system': 'solve a linear system AX=B for square matrix A using PyTorch tensors with version-compatible dispatch', 'solve_lstsq': 'solve a least squares problem AX=B for non-square matrix A using PyTorch tensors with version-compatible dispatch', 'solve_qr': 'compute the QR decomposition of a PyTorch tensor matrix A with version-compatible dispatch', 'review_solve': 'review the solve function to understand how it dispatches between torch.linalg.solve and torch.solve based on PyTorch version', 'refactor_lstsq': 'refactor the lstsq function to handle edge cases where A has fewer columns than rows'}
```

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/common/types.py

Prompts

```
['solve a linear system AX=B for square matrix A using PyTorch tensors with version-compatible dispatch', 'solve a least squares problem AX=B for non-square matrix A using PyTorch tensors with version-compatible dispatch', 'compute the QR decomposition of a PyTorch tensor matrix A with version-compatible dispatch', 'review the solve function to understand how it dispatches between torch.linalg.solve and torch.solve based on PyTorch version', 'refactor the lstsq function to handle edge cases where A has fewer columns than rows', "create a torch.device object from a device string like 'cuda' or 'cpu'", 'create a torch.device object from an existing torch.device with resolved cuda index', 'get the device of a torch.Tensor and return it as a torch.device object', 'get a device by overriding with an explicit device string or torch.device', 'get the default CPU device when input is not a tensor and no device is provided']
```

Usage

```
{'make_device_from_string': "create a torch.device object from a device string like 'cuda' or 'cpu'", 'make_device_from_torch_device': 'create a torch.device object from an existing torch.device with resolved cuda index', 'get_device_from_tensor': 'get the device of a torch.Tensor and return it as a torch.device object', 'get_device_with_override': 'get a device by overriding with an explicit device string or torch.device', 'get_device_default_cpu': 'get the default CPU device when input is not a tensor and no device is provided'}
```

