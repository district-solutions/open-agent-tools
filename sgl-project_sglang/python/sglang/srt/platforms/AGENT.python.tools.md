# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/platforms/device_mixin.py

Prompts

```
['create a PlatformEnum instance representing a hardware platform type like CUDA or ROCm', 'build a DeviceCapability namedtuple from major and minor version integers', 'test whether a DeviceMixin instance reports is_cuda as true', 'test whether a DeviceMixin instance reports is_rocm as true', 'test whether a DeviceMixin instance reports is_cpu as true', 'test whether a DeviceMixin instance reports is_cuda_alike as true for CUDA, ROCm, or MUSA', 'summarize device memory by calling get_device_total_memory and get_current_memory_usage on a DeviceMixin instance', 'review the DeviceCapability class methods as_version_str and to_int for correct conversion behavior', 'run get_cpu_architecture on DeviceMixin to detect whether the host is X86 or ARM', 'build a platform subclass that returns the default attention backend name', 'test whether a hardware platform supports FP8 quantization', 'create a platform backend that enables CUDA graph capture and replay', 'review the one-time backend initialization method for SRT platform workers', 'summarize how get_dispatch_key_name selects forward methods for MultiPlatformOp']
```

Usage

```
{'create_platform_enum': 'create a PlatformEnum instance representing a hardware platform type like CUDA or ROCm', 'build_device_capability': 'build a DeviceCapability namedtuple from major and minor version integers', 'test_device_is_cuda': 'test whether a DeviceMixin instance reports is_cuda as true', 'test_device_is_rocm': 'test whether a DeviceMixin instance reports is_rocm as true', 'test_device_is_cpu': 'test whether a DeviceMixin instance reports is_cpu as true', 'test_device_is_cuda_alike': 'test whether a DeviceMixin instance reports is_cuda_alike as true for CUDA, ROCm, or MUSA', 'summarize_device_memory': 'summarize device memory by calling get_device_total_memory and get_current_memory_usage on a DeviceMixin instance', 'review_device_capability_methods': 'review the DeviceCapability class methods as_version_str and to_int for correct conversion behavior', 'run_cpu_architecture_detect': 'run get_cpu_architecture on DeviceMixin to detect whether the host is X86 or ARM'}
```

## File: sgl-project_sglang/python/sglang/srt/platforms/interface.py

Prompts

```
['create a PlatformEnum instance representing a hardware platform type like CUDA or ROCm', 'build a DeviceCapability namedtuple from major and minor version integers', 'test whether a DeviceMixin instance reports is_cuda as true', 'test whether a DeviceMixin instance reports is_rocm as true', 'test whether a DeviceMixin instance reports is_cpu as true', 'test whether a DeviceMixin instance reports is_cuda_alike as true for CUDA, ROCm, or MUSA', 'summarize device memory by calling get_device_total_memory and get_current_memory_usage on a DeviceMixin instance', 'review the DeviceCapability class methods as_version_str and to_int for correct conversion behavior', 'run get_cpu_architecture on DeviceMixin to detect whether the host is X86 or ARM', 'build a platform subclass that returns the default attention backend name', 'test whether a hardware platform supports FP8 quantization', 'create a platform backend that enables CUDA graph capture and replay', 'review the one-time backend initialization method for SRT platform workers', 'summarize how get_dispatch_key_name selects forward methods for MultiPlatformOp']
```

Usage

```
{'build_platform_get_attention_backend': 'build a platform subclass that returns the default attention backend name', 'test_platform_supports_fp8': 'test whether a hardware platform supports FP8 quantization', 'create_platform_cuda_graph': 'create a platform backend that enables CUDA graph capture and replay', 'review_platform_init_backend': 'review the one-time backend initialization method for SRT platform workers', 'summarize_platform_dispatch_key': 'summarize how get_dispatch_key_name selects forward methods for MultiPlatformOp'}
```

