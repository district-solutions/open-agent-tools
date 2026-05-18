# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/device/npu/data_parallel.py

Prompts

```
['build a python module that wraps an nn.Module with NPUDataParallel for single NPU training', 'create a function that scatters inputs and kwargs across NPU device IDs using scatter_kwargs', 'test the NPUDataParallel class initialization with a custom device_id and dim parameter', 'refactor the _check_balance monkey patch to skip balance checks in torch and mmcv modules', 'review the NPUDataParallel scatter method and how it delegates to scatter_kwargs for data distribution', 'build a python module to wrap a model with NPUDistributedDataParallel for NPU distributed training', 'create a forward pass through NPUDistributedDataParallel that scatters inputs to NPU devices before calling super forward', 'test the NPUDistributedDataParallel scatter method to verify inputs are correctly distributed across NPU device IDs', 'refactor the NPUDistributedDataParallel to_kwargs method to move tensors to a specific NPU device ID using scatter_kwargs', 'review the NPUDistributedDataParallel class and its override of forward to prevent device misalignment on NPU hardware']
```

Usage

```
{'build_NPUDataParallel_module': 'build a python module that wraps an nn.Module with NPUDataParallel for single NPU training', 'create_NPUDataParallel_scatter': 'create a function that scatters inputs and kwargs across NPU device IDs using scatter_kwargs', 'test_NPUDataParallel_init': 'test the NPUDataParallel class initialization with a custom device_id and dim parameter', 'refactor_check_balance': 'refactor the _check_balance monkey patch to skip balance checks in torch and mmcv modules', 'review_NPUDataParallel_scatter': 'review the NPUDataParallel scatter method and how it delegates to scatter_kwargs for data distribution'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/device/npu/distributed.py

Prompts

```
['build a python module that wraps an nn.Module with NPUDataParallel for single NPU training', 'create a function that scatters inputs and kwargs across NPU device IDs using scatter_kwargs', 'test the NPUDataParallel class initialization with a custom device_id and dim parameter', 'refactor the _check_balance monkey patch to skip balance checks in torch and mmcv modules', 'review the NPUDataParallel scatter method and how it delegates to scatter_kwargs for data distribution', 'build a python module to wrap a model with NPUDistributedDataParallel for NPU distributed training', 'create a forward pass through NPUDistributedDataParallel that scatters inputs to NPU devices before calling super forward', 'test the NPUDistributedDataParallel scatter method to verify inputs are correctly distributed across NPU device IDs', 'refactor the NPUDistributedDataParallel to_kwargs method to move tensors to a specific NPU device ID using scatter_kwargs', 'review the NPUDistributedDataParallel class and its override of forward to prevent device misalignment on NPU hardware']
```

Usage

```
{'build_NPUDistributedDataParallel': 'build a python module to wrap a model with NPUDistributedDataParallel for NPU distributed training', 'create_NPUDistributedDataParallel_forward': 'create a forward pass through NPUDistributedDataParallel that scatters inputs to NPU devices before calling super forward', 'test_NPUDistributedDataParallel_scatter': 'test the NPUDistributedDataParallel scatter method to verify inputs are correctly distributed across NPU device IDs', 'refactor_NPUDistributedDataParallel_to_kwargs': 'refactor the NPUDistributedDataParallel to_kwargs method to move tensors to a specific NPU device ID using scatter_kwargs', 'review_NPUDistributedDataParallel': 'review the NPUDistributedDataParallel class and its override of forward to prevent device misalignment on NPU hardware'}
```

