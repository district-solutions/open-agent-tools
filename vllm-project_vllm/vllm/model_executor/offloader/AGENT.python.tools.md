# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/offloader/base.py

Prompts

```
['create an offloader instance from an OffloadConfig with auto, prefetch, uva, or noop backend selection', 'set the global offloader singleton instance to a specific offloader implementation', 'get the current global offloader singleton instance', 'check if pinned memory should be used for weight offloading based on platform capability and env override', 'wrap a generator of nn.Module instances with offloading hooks and return the wrapped module list', 'create a PrefetchOffloader with group_size, num_in_group, and prefetch_step for async CPU offloading', 'build a StaticBufferPool with param_infos, slot_capacity, and device for pre-allocated GPU buffers', 'wrap nn.Module instances with PrefetchOffloader.wrap_modules to enable prefetch-based offloading', 'start an async H2D prefetch copy for a module layer using _ModuleOffloader.start_onload_to_static', 'sync CPU storage with current param.data after process_weights_after_loading completes', 'register custom prefetch offloader ops for torch.compile and CUDA graph compatibility', 'wait for async prefetch of a specific transformer layer to complete on the copy stream', 'start async H2D prefetch of weights for a specified transformer layer index', 'create a custom torch op that synchronizes compute and copy streams for prefetched layer weights', 'create a custom torch op that initiates async weight prefetch from host to device', 'build a UVAOffloader class to offload model parameters to pinned CPU memory using Unified Virtual Addressing', 'test the UVAOffloader class initialization with cpu_offload_max_bytes and optional cpu_offload_params', 'run UVAOffloader.wrap_modules to wrap neural network modules with zero-copy CPU offloading', 'refactor UVAOffloader._maybe_offload_to_cpu to selectively offload parameters within a byte budget', 'review the UVAOffloader class that provides UVA-based zero-copy parameter offloading with functional_call fallback']
```

Usage

```
{'create_offloader': 'create an offloader instance from an OffloadConfig with auto, prefetch, uva, or noop backend selection', 'set_offloader': 'set the global offloader singleton instance to a specific offloader implementation', 'get_offloader': 'get the current global offloader singleton instance', 'should_pin_memory': 'check if pinned memory should be used for weight offloading based on platform capability and env override', 'BaseOffloader_wrap_modules': 'wrap a generator of nn.Module instances with offloading hooks and return the wrapped module list'}
```

## File: vllm-project_vllm/vllm/model_executor/offloader/prefetch.py

Prompts

```
['create an offloader instance from an OffloadConfig with auto, prefetch, uva, or noop backend selection', 'set the global offloader singleton instance to a specific offloader implementation', 'get the current global offloader singleton instance', 'check if pinned memory should be used for weight offloading based on platform capability and env override', 'wrap a generator of nn.Module instances with offloading hooks and return the wrapped module list', 'create a PrefetchOffloader with group_size, num_in_group, and prefetch_step for async CPU offloading', 'build a StaticBufferPool with param_infos, slot_capacity, and device for pre-allocated GPU buffers', 'wrap nn.Module instances with PrefetchOffloader.wrap_modules to enable prefetch-based offloading', 'start an async H2D prefetch copy for a module layer using _ModuleOffloader.start_onload_to_static', 'sync CPU storage with current param.data after process_weights_after_loading completes', 'register custom prefetch offloader ops for torch.compile and CUDA graph compatibility', 'wait for async prefetch of a specific transformer layer to complete on the copy stream', 'start async H2D prefetch of weights for a specified transformer layer index', 'create a custom torch op that synchronizes compute and copy streams for prefetched layer weights', 'create a custom torch op that initiates async weight prefetch from host to device', 'build a UVAOffloader class to offload model parameters to pinned CPU memory using Unified Virtual Addressing', 'test the UVAOffloader class initialization with cpu_offload_max_bytes and optional cpu_offload_params', 'run UVAOffloader.wrap_modules to wrap neural network modules with zero-copy CPU offloading', 'refactor UVAOffloader._maybe_offload_to_cpu to selectively offload parameters within a byte budget', 'review the UVAOffloader class that provides UVA-based zero-copy parameter offloading with functional_call fallback']
```

Usage

```
{'create_prefetch_offloader': 'create a PrefetchOffloader with group_size, num_in_group, and prefetch_step for async CPU offloading', 'build_static_buffer_pool': 'build a StaticBufferPool with param_infos, slot_capacity, and device for pre-allocated GPU buffers', 'wrap_modules_prefetch': 'wrap nn.Module instances with PrefetchOffloader.wrap_modules to enable prefetch-based offloading', 'start_async_prefetch': 'start an async H2D prefetch copy for a module layer using _ModuleOffloader.start_onload_to_static', 'sync_cpu_storage_after_loading': 'sync CPU storage with current param.data after process_weights_after_loading completes'}
```

## File: vllm-project_vllm/vllm/model_executor/offloader/prefetch_ops.py

Prompts

```
['create an offloader instance from an OffloadConfig with auto, prefetch, uva, or noop backend selection', 'set the global offloader singleton instance to a specific offloader implementation', 'get the current global offloader singleton instance', 'check if pinned memory should be used for weight offloading based on platform capability and env override', 'wrap a generator of nn.Module instances with offloading hooks and return the wrapped module list', 'create a PrefetchOffloader with group_size, num_in_group, and prefetch_step for async CPU offloading', 'build a StaticBufferPool with param_infos, slot_capacity, and device for pre-allocated GPU buffers', 'wrap nn.Module instances with PrefetchOffloader.wrap_modules to enable prefetch-based offloading', 'start an async H2D prefetch copy for a module layer using _ModuleOffloader.start_onload_to_static', 'sync CPU storage with current param.data after process_weights_after_loading completes', 'register custom prefetch offloader ops for torch.compile and CUDA graph compatibility', 'wait for async prefetch of a specific transformer layer to complete on the copy stream', 'start async H2D prefetch of weights for a specified transformer layer index', 'create a custom torch op that synchronizes compute and copy streams for prefetched layer weights', 'create a custom torch op that initiates async weight prefetch from host to device', 'build a UVAOffloader class to offload model parameters to pinned CPU memory using Unified Virtual Addressing', 'test the UVAOffloader class initialization with cpu_offload_max_bytes and optional cpu_offload_params', 'run UVAOffloader.wrap_modules to wrap neural network modules with zero-copy CPU offloading', 'refactor UVAOffloader._maybe_offload_to_cpu to selectively offload parameters within a byte budget', 'review the UVAOffloader class that provides UVA-based zero-copy parameter offloading with functional_call fallback']
```

Usage

```
{'register_prefetch_offloader_ops': 'register custom prefetch offloader ops for torch.compile and CUDA graph compatibility', 'wait_prefetch_layer': 'wait for async prefetch of a specific transformer layer to complete on the copy stream', 'start_prefetch_layer': 'start async H2D prefetch of weights for a specified transformer layer index', 'create_custom_op_wait_prefetch': 'create a custom torch op that synchronizes compute and copy streams for prefetched layer weights', 'create_custom_op_start_prefetch': 'create a custom torch op that initiates async weight prefetch from host to device'}
```

## File: vllm-project_vllm/vllm/model_executor/offloader/uva.py

Prompts

```
['create an offloader instance from an OffloadConfig with auto, prefetch, uva, or noop backend selection', 'set the global offloader singleton instance to a specific offloader implementation', 'get the current global offloader singleton instance', 'check if pinned memory should be used for weight offloading based on platform capability and env override', 'wrap a generator of nn.Module instances with offloading hooks and return the wrapped module list', 'create a PrefetchOffloader with group_size, num_in_group, and prefetch_step for async CPU offloading', 'build a StaticBufferPool with param_infos, slot_capacity, and device for pre-allocated GPU buffers', 'wrap nn.Module instances with PrefetchOffloader.wrap_modules to enable prefetch-based offloading', 'start an async H2D prefetch copy for a module layer using _ModuleOffloader.start_onload_to_static', 'sync CPU storage with current param.data after process_weights_after_loading completes', 'register custom prefetch offloader ops for torch.compile and CUDA graph compatibility', 'wait for async prefetch of a specific transformer layer to complete on the copy stream', 'start async H2D prefetch of weights for a specified transformer layer index', 'create a custom torch op that synchronizes compute and copy streams for prefetched layer weights', 'create a custom torch op that initiates async weight prefetch from host to device', 'build a UVAOffloader class to offload model parameters to pinned CPU memory using Unified Virtual Addressing', 'test the UVAOffloader class initialization with cpu_offload_max_bytes and optional cpu_offload_params', 'run UVAOffloader.wrap_modules to wrap neural network modules with zero-copy CPU offloading', 'refactor UVAOffloader._maybe_offload_to_cpu to selectively offload parameters within a byte budget', 'review the UVAOffloader class that provides UVA-based zero-copy parameter offloading with functional_call fallback']
```

Usage

```
{'build_UVAOffloader_class': 'build a UVAOffloader class to offload model parameters to pinned CPU memory using Unified Virtual Addressing', 'test_UVAOffloader_init': 'test the UVAOffloader class initialization with cpu_offload_max_bytes and optional cpu_offload_params', 'run_UVAOffloader_wrap_modules': 'run UVAOffloader.wrap_modules to wrap neural network modules with zero-copy CPU offloading', 'refactor_UVAOffloader__maybe_offload_to_cpu': 'refactor UVAOffloader._maybe_offload_to_cpu to selectively offload parameters within a byte budget', 'review_UVAOffloader_class': 'review the UVAOffloader class that provides UVA-based zero-copy parameter offloading with functional_call fallback'}
```

