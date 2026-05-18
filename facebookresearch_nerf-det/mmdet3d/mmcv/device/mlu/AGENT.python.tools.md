# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/device/mlu/_functions.py

Prompts

```
['scatter a torch tensor to MLU device by calling scatter with the tensor and device list', 'scatter a list of torch tensors to MLU devices using the scatter function recursively', 'call Scatter.forward with target MLU devices and a single tensor to get a tuple output', 'call Scatter.forward with target MLU devices and a list of tensors to get scattered outputs', 'review the scatter function to understand how it handles tensor and list input types for MLU', 'build a python module that wraps an nn.Module with MLUDataParallel for single MLU training', 'create a function that uses MLUDataParallel scatter to distribute inputs across MLU devices', 'test the MLUDataParallel class by wrapping a model and running forward on MLU device 0', 'refactor the MLUDataParallel class to support configurable MLU device selection beyond device 0', 'review the MLUDataParallel scatter method and its use of scatter_kwargs for data distribution', 'build a Python module that wraps a model with MLUDistributedDataParallel for MLU-based distributed training', 'create a function that calls scatter_kwargs to distribute inputs and kwargs across MLU devices', 'test the MLUDistributedDataParallel scatter method to verify it correctly distributes tensors to multiple MLU devices', 'refactor the MLUDistributedDataParallel to_kwargs method to support additional data types beyond tensors and DataContainers', 'review the MLUDistributedDataParallel class and its override of scatter and to_kwargs for MLU device compatibility', 'scatter torch tensors, DataContainers, tuples, lists, or dicts to target MLU devices for parallel processing', 'scatter both positional inputs and kwargs dictionaries to target MLU devices with automatic length alignment', 'review the scatter function and its reference cycle avoidance pattern that sets scatter_map to None in a finally block', 'test the scatter function with DataContainer objects that have cpu_only set to True to verify CPU passthrough behavior', 'summarize the scatter_map inner function and its recursive handling of nested tuples, lists, and dicts during MLU scattering']
```

Usage

```
{'scatter_tensor_to_mlu': 'scatter a torch tensor to MLU device by calling scatter with the tensor and device list', 'scatter_list_of_tensors': 'scatter a list of torch tensors to MLU devices using the scatter function recursively', 'Scatter_forward_single_tensor': 'call Scatter.forward with target MLU devices and a single tensor to get a tuple output', 'Scatter_forward_list_of_tensors': 'call Scatter.forward with target MLU devices and a list of tensors to get scattered outputs', 'review_scatter_function': 'review the scatter function to understand how it handles tensor and list input types for MLU'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/device/mlu/data_parallel.py

Prompts

```
['scatter a torch tensor to MLU device by calling scatter with the tensor and device list', 'scatter a list of torch tensors to MLU devices using the scatter function recursively', 'call Scatter.forward with target MLU devices and a single tensor to get a tuple output', 'call Scatter.forward with target MLU devices and a list of tensors to get scattered outputs', 'review the scatter function to understand how it handles tensor and list input types for MLU', 'build a python module that wraps an nn.Module with MLUDataParallel for single MLU training', 'create a function that uses MLUDataParallel scatter to distribute inputs across MLU devices', 'test the MLUDataParallel class by wrapping a model and running forward on MLU device 0', 'refactor the MLUDataParallel class to support configurable MLU device selection beyond device 0', 'review the MLUDataParallel scatter method and its use of scatter_kwargs for data distribution', 'build a Python module that wraps a model with MLUDistributedDataParallel for MLU-based distributed training', 'create a function that calls scatter_kwargs to distribute inputs and kwargs across MLU devices', 'test the MLUDistributedDataParallel scatter method to verify it correctly distributes tensors to multiple MLU devices', 'refactor the MLUDistributedDataParallel to_kwargs method to support additional data types beyond tensors and DataContainers', 'review the MLUDistributedDataParallel class and its override of scatter and to_kwargs for MLU device compatibility', 'scatter torch tensors, DataContainers, tuples, lists, or dicts to target MLU devices for parallel processing', 'scatter both positional inputs and kwargs dictionaries to target MLU devices with automatic length alignment', 'review the scatter function and its reference cycle avoidance pattern that sets scatter_map to None in a finally block', 'test the scatter function with DataContainer objects that have cpu_only set to True to verify CPU passthrough behavior', 'summarize the scatter_map inner function and its recursive handling of nested tuples, lists, and dicts during MLU scattering']
```

Usage

```
{'build_MLUDataParallel': 'build a python module that wraps an nn.Module with MLUDataParallel for single MLU training', 'create_MLUDataParallel_scatter': 'create a function that uses MLUDataParallel scatter to distribute inputs across MLU devices', 'test_MLUDataParallel': 'test the MLUDataParallel class by wrapping a model and running forward on MLU device 0', 'refactor_MLUDataParallel': 'refactor the MLUDataParallel class to support configurable MLU device selection beyond device 0', 'review_MLUDataParallel_scatter': 'review the MLUDataParallel scatter method and its use of scatter_kwargs for data distribution'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/device/mlu/distributed.py

Prompts

```
['scatter a torch tensor to MLU device by calling scatter with the tensor and device list', 'scatter a list of torch tensors to MLU devices using the scatter function recursively', 'call Scatter.forward with target MLU devices and a single tensor to get a tuple output', 'call Scatter.forward with target MLU devices and a list of tensors to get scattered outputs', 'review the scatter function to understand how it handles tensor and list input types for MLU', 'build a python module that wraps an nn.Module with MLUDataParallel for single MLU training', 'create a function that uses MLUDataParallel scatter to distribute inputs across MLU devices', 'test the MLUDataParallel class by wrapping a model and running forward on MLU device 0', 'refactor the MLUDataParallel class to support configurable MLU device selection beyond device 0', 'review the MLUDataParallel scatter method and its use of scatter_kwargs for data distribution', 'build a Python module that wraps a model with MLUDistributedDataParallel for MLU-based distributed training', 'create a function that calls scatter_kwargs to distribute inputs and kwargs across MLU devices', 'test the MLUDistributedDataParallel scatter method to verify it correctly distributes tensors to multiple MLU devices', 'refactor the MLUDistributedDataParallel to_kwargs method to support additional data types beyond tensors and DataContainers', 'review the MLUDistributedDataParallel class and its override of scatter and to_kwargs for MLU device compatibility', 'scatter torch tensors, DataContainers, tuples, lists, or dicts to target MLU devices for parallel processing', 'scatter both positional inputs and kwargs dictionaries to target MLU devices with automatic length alignment', 'review the scatter function and its reference cycle avoidance pattern that sets scatter_map to None in a finally block', 'test the scatter function with DataContainer objects that have cpu_only set to True to verify CPU passthrough behavior', 'summarize the scatter_map inner function and its recursive handling of nested tuples, lists, and dicts during MLU scattering']
```

Usage

```
{'build_MLU_DDP_wrapper': 'build a Python module that wraps a model with MLUDistributedDataParallel for MLU-based distributed training', 'create_scatter_kwargs_call': 'create a function that calls scatter_kwargs to distribute inputs and kwargs across MLU devices', 'test_MLUDistributedDataParallel_scatter': 'test the MLUDistributedDataParallel scatter method to verify it correctly distributes tensors to multiple MLU devices', 'refactor_MLUDistributedDataParallel_to_kwargs': 'refactor the MLUDistributedDataParallel to_kwargs method to support additional data types beyond tensors and DataContainers', 'review_MLUDistributedDataParallel_class': 'review the MLUDistributedDataParallel class and its override of scatter and to_kwargs for MLU device compatibility'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/device/mlu/scatter_gather.py

Prompts

```
['scatter a torch tensor to MLU device by calling scatter with the tensor and device list', 'scatter a list of torch tensors to MLU devices using the scatter function recursively', 'call Scatter.forward with target MLU devices and a single tensor to get a tuple output', 'call Scatter.forward with target MLU devices and a list of tensors to get scattered outputs', 'review the scatter function to understand how it handles tensor and list input types for MLU', 'build a python module that wraps an nn.Module with MLUDataParallel for single MLU training', 'create a function that uses MLUDataParallel scatter to distribute inputs across MLU devices', 'test the MLUDataParallel class by wrapping a model and running forward on MLU device 0', 'refactor the MLUDataParallel class to support configurable MLU device selection beyond device 0', 'review the MLUDataParallel scatter method and its use of scatter_kwargs for data distribution', 'build a Python module that wraps a model with MLUDistributedDataParallel for MLU-based distributed training', 'create a function that calls scatter_kwargs to distribute inputs and kwargs across MLU devices', 'test the MLUDistributedDataParallel scatter method to verify it correctly distributes tensors to multiple MLU devices', 'refactor the MLUDistributedDataParallel to_kwargs method to support additional data types beyond tensors and DataContainers', 'review the MLUDistributedDataParallel class and its override of scatter and to_kwargs for MLU device compatibility', 'scatter torch tensors, DataContainers, tuples, lists, or dicts to target MLU devices for parallel processing', 'scatter both positional inputs and kwargs dictionaries to target MLU devices with automatic length alignment', 'review the scatter function and its reference cycle avoidance pattern that sets scatter_map to None in a finally block', 'test the scatter function with DataContainer objects that have cpu_only set to True to verify CPU passthrough behavior', 'summarize the scatter_map inner function and its recursive handling of nested tuples, lists, and dicts during MLU scattering']
```

Usage

```
{'scatter_inputs_to_mlus': 'scatter torch tensors, DataContainers, tuples, lists, or dicts to target MLU devices for parallel processing', 'scatter_kwargs_for_mlus': 'scatter both positional inputs and kwargs dictionaries to target MLU devices with automatic length alignment', 'review_scatter_closure_cleanup': 'review the scatter function and its reference cycle avoidance pattern that sets scatter_map to None in a finally block', 'test_scatter_with_cpu_only': 'test the scatter function with DataContainer objects that have cpu_only set to True to verify CPU passthrough behavior', 'summarize_scatter_map_recursion': 'summarize the scatter_map inner function and its recursive handling of nested tuples, lists, and dicts during MLU scattering'}
```

