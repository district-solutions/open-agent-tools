# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/kernels/helion/config_manager.py

Prompts

```
['load all Helion kernel configs from JSON platform files into a ConfigSet object', 'save a ConfigSet of Helion kernel configs to JSON files on disk', 'save or merge Helion kernel configs for a specific platform, merging with existing data', 'retrieve all helion.Config objects for a kernel on a specific GPU platform', 'check whether a specific config key exists for a kernel on a given platform', 'register a Helion kernel with pre-tuned config selection and a config_picker function', 'run autotuning for a single input configuration on a registered Helion kernel', 'get a copy of all registered HelionKernelWrapper instances by name', 'retrieve a HelionKernelWrapper by its registered kernel name', 'create a Helion-decorated kernel from a raw function with settings and extra kwargs', 'get the GPU name for a given device ID using the current platform', 'canonicalize a GPU name by normalizing case and mapping variant names to their canonical form', 'get the canonical GPU name for a device by retrieving and normalizing the device name', 'review the GPU name alias mappings for H100, H200, A100, V100, and AMD ROCm variants', 'test canonicalize_gpu_name with variant names like NVIDIA H100 80GB HBM3 and AMD Instinct MI300X']
```

Usage

```
{'load_config_set': 'load all Helion kernel configs from JSON platform files into a ConfigSet object', 'save_config_set': 'save a ConfigSet of Helion kernel configs to JSON files on disk', 'save_configs': 'save or merge Helion kernel configs for a specific platform, merging with existing data', 'get_platform_configs': 'retrieve all helion.Config objects for a kernel on a specific GPU platform', 'config_exists': 'check whether a specific config key exists for a kernel on a given platform'}
```

## File: vllm-project_vllm/vllm/kernels/helion/register.py

Prompts

```
['load all Helion kernel configs from JSON platform files into a ConfigSet object', 'save a ConfigSet of Helion kernel configs to JSON files on disk', 'save or merge Helion kernel configs for a specific platform, merging with existing data', 'retrieve all helion.Config objects for a kernel on a specific GPU platform', 'check whether a specific config key exists for a kernel on a given platform', 'register a Helion kernel with pre-tuned config selection and a config_picker function', 'run autotuning for a single input configuration on a registered Helion kernel', 'get a copy of all registered HelionKernelWrapper instances by name', 'retrieve a HelionKernelWrapper by its registered kernel name', 'create a Helion-decorated kernel from a raw function with settings and extra kwargs', 'get the GPU name for a given device ID using the current platform', 'canonicalize a GPU name by normalizing case and mapping variant names to their canonical form', 'get the canonical GPU name for a device by retrieving and normalizing the device name', 'review the GPU name alias mappings for H100, H200, A100, V100, and AMD ROCm variants', 'test canonicalize_gpu_name with variant names like NVIDIA H100 80GB HBM3 and AMD Instinct MI300X']
```

Usage

```
{'register_kernel': 'register a Helion kernel with pre-tuned config selection and a config_picker function', 'run_autotune': 'run autotuning for a single input configuration on a registered Helion kernel', 'get_registered_kernels': 'get a copy of all registered HelionKernelWrapper instances by name', 'get_kernel_by_name': 'retrieve a HelionKernelWrapper by its registered kernel name', 'create_helion_decorated_kernel': 'create a Helion-decorated kernel from a raw function with settings and extra kwargs'}
```

## File: vllm-project_vllm/vllm/kernels/helion/utils.py

Prompts

```
['load all Helion kernel configs from JSON platform files into a ConfigSet object', 'save a ConfigSet of Helion kernel configs to JSON files on disk', 'save or merge Helion kernel configs for a specific platform, merging with existing data', 'retrieve all helion.Config objects for a kernel on a specific GPU platform', 'check whether a specific config key exists for a kernel on a given platform', 'register a Helion kernel with pre-tuned config selection and a config_picker function', 'run autotuning for a single input configuration on a registered Helion kernel', 'get a copy of all registered HelionKernelWrapper instances by name', 'retrieve a HelionKernelWrapper by its registered kernel name', 'create a Helion-decorated kernel from a raw function with settings and extra kwargs', 'get the GPU name for a given device ID using the current platform', 'canonicalize a GPU name by normalizing case and mapping variant names to their canonical form', 'get the canonical GPU name for a device by retrieving and normalizing the device name', 'review the GPU name alias mappings for H100, H200, A100, V100, and AMD ROCm variants', 'test canonicalize_gpu_name with variant names like NVIDIA H100 80GB HBM3 and AMD Instinct MI300X']
```

Usage

```
{'get_gpu_name': 'get the GPU name for a given device ID using the current platform', 'canonicalize_gpu_name': 'canonicalize a GPU name by normalizing case and mapping variant names to their canonical form', 'get_canonical_gpu_name': 'get the canonical GPU name for a device by retrieving and normalizing the device name', 'review_GPU_NAME_ALIASES': 'review the GPU name alias mappings for H100, H200, A100, V100, and AMD ROCm variants', 'test_canonicalize_gpu_name': 'test canonicalize_gpu_name with variant names like NVIDIA H100 80GB HBM3 and AMD Instinct MI300X'}
```

