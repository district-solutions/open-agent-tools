# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/device/_functions.py

Prompts

```
['create a function that scatters a torch tensor to the current device using scatter', 'build a python module that scatters a list of tensors to devices recursively', 'run Scatter.forward to scatter a single tensor to target devices and return a tuple', 'test Scatter.forward with a list of tensors to get scattered outputs as a tuple', 'review the scatter function and how it handles device placement based on the devices list', 'scatter torch tensors to target GPU devices for distributed training', 'scatter DataContainer objects to target devices with cpu_only support', 'scatter nested tuples lists and dicts of tensors to target devices', 'scatter both positional inputs and kwargs dicts to target devices together', 'scatter tensors for CPU inference using self-implemented Scatter forward pass', 'get the currently available device type string such as cuda mlu mps npu or cpu', 'test the get_device function to verify it returns the correct device type string', 'review the get_device function to understand device detection priority logic', 'summarize the get_device function which checks NPU CUDA MLU MPS availability in order', 'refactor the get_device function to support additional device types beyond npu cuda mlu mps']
```

Usage

```
{'scatter_tensor_to_device': 'create a function that scatters a torch tensor to the current device using scatter', 'scatter_list_of_tensors': 'build a python module that scatters a list of tensors to devices recursively', 'Scatter_forward_single_tensor': 'run Scatter.forward to scatter a single tensor to target devices and return a tuple', 'Scatter_forward_list_input': 'test Scatter.forward with a list of tensors to get scattered outputs as a tuple', 'review_scatter_device_handling': 'review the scatter function and how it handles device placement based on the devices list'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/device/scatter_gather.py

Prompts

```
['create a function that scatters a torch tensor to the current device using scatter', 'build a python module that scatters a list of tensors to devices recursively', 'run Scatter.forward to scatter a single tensor to target devices and return a tuple', 'test Scatter.forward with a list of tensors to get scattered outputs as a tuple', 'review the scatter function and how it handles device placement based on the devices list', 'scatter torch tensors to target GPU devices for distributed training', 'scatter DataContainer objects to target devices with cpu_only support', 'scatter nested tuples lists and dicts of tensors to target devices', 'scatter both positional inputs and kwargs dicts to target devices together', 'scatter tensors for CPU inference using self-implemented Scatter forward pass', 'get the currently available device type string such as cuda mlu mps npu or cpu', 'test the get_device function to verify it returns the correct device type string', 'review the get_device function to understand device detection priority logic', 'summarize the get_device function which checks NPU CUDA MLU MPS availability in order', 'refactor the get_device function to support additional device types beyond npu cuda mlu mps']
```

Usage

```
{'scatter_tensors_to_devices': 'scatter torch tensors to target GPU devices for distributed training', 'scatter_datacontainers_to_devices': 'scatter DataContainer objects to target devices with cpu_only support', 'scatter_nested_structures': 'scatter nested tuples lists and dicts of tensors to target devices', 'scatter_kwargs_for_distributed': 'scatter both positional inputs and kwargs dicts to target devices together', 'scatter_cpu_inference': 'scatter tensors for CPU inference using self-implemented Scatter forward pass'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/device/utils.py

Prompts

```
['create a function that scatters a torch tensor to the current device using scatter', 'build a python module that scatters a list of tensors to devices recursively', 'run Scatter.forward to scatter a single tensor to target devices and return a tuple', 'test Scatter.forward with a list of tensors to get scattered outputs as a tuple', 'review the scatter function and how it handles device placement based on the devices list', 'scatter torch tensors to target GPU devices for distributed training', 'scatter DataContainer objects to target devices with cpu_only support', 'scatter nested tuples lists and dicts of tensors to target devices', 'scatter both positional inputs and kwargs dicts to target devices together', 'scatter tensors for CPU inference using self-implemented Scatter forward pass', 'get the currently available device type string such as cuda mlu mps npu or cpu', 'test the get_device function to verify it returns the correct device type string', 'review the get_device function to understand device detection priority logic', 'summarize the get_device function which checks NPU CUDA MLU MPS availability in order', 'refactor the get_device function to support additional device types beyond npu cuda mlu mps']
```

Usage

```
{'get_device': 'get the currently available device type string such as cuda mlu mps npu or cpu', 'test_get_device': 'test the get_device function to verify it returns the correct device type string', 'review_get_device': 'review the get_device function to understand device detection priority logic', 'summarize_get_device': 'summarize the get_device function which checks NPU CUDA MLU MPS availability in order', 'refactor_get_device': 'refactor the get_device function to support additional device types beyond npu cuda mlu mps'}
```

