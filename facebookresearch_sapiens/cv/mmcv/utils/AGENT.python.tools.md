# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/cv/mmcv/utils/env.py

Prompts

```
['run collect_env to gather Python, CUDA, PyTorch, and MMCV environment details into a dictionary', 'use collect_env to retrieve the NVCC or HIP compiler version from the current environment', 'call collect_env to get the installed MMCV version and its compiler details', 'run collect_env to diagnose GPU device types and CUDA availability for debugging', 'summarize the collect_env function which returns a dict of platform, Python, CUDA, PyTorch, and MMCV info', 'load a mmcv extension module by name and verify all required functions exist', 'load mmcv parrots extensions with fallback fake functions for missing ops', 'check if the mmcv compiled C++ extension module is available on this system', 'create a stub function that warns and raises an exception for unsupported parrots ops', 'review the list of parrots ops that return values versus in-place operations', 'use the jit decorator to wrap a function for Parrots JIT compilation or pass-through', 'use the skip_no_elena decorator to conditionally skip tests when Elena backend is unavailable', 'check the parrots_jit_option variable to see if PARROTS_JIT_OPTION env var is set', 'summarize the jit decorator which provides a no-op fallback when Parrots Torch is not in use', 'review the skip_no_elena decorator which imports from parrots or falls back to a pass-through wrapper']
```

Usage

```
{'collect_env_info': 'run collect_env to gather Python, CUDA, PyTorch, and MMCV environment details into a dictionary', 'check_cuda_compiler': 'use collect_env to retrieve the NVCC or HIP compiler version from the current environment', 'check_mmcv_version': 'call collect_env to get the installed MMCV version and its compiler details', 'debug_gpu_setup': 'run collect_env to diagnose GPU device types and CUDA availability for debugging', 'summarize_collect_env': 'summarize the collect_env function which returns a dict of platform, Python, CUDA, PyTorch, and MMCV info'}
```

## File: facebookresearch_sapiens/cv/mmcv/utils/ext_loader.py

Prompts

```
['run collect_env to gather Python, CUDA, PyTorch, and MMCV environment details into a dictionary', 'use collect_env to retrieve the NVCC or HIP compiler version from the current environment', 'call collect_env to get the installed MMCV version and its compiler details', 'run collect_env to diagnose GPU device types and CUDA availability for debugging', 'summarize the collect_env function which returns a dict of platform, Python, CUDA, PyTorch, and MMCV info', 'load a mmcv extension module by name and verify all required functions exist', 'load mmcv parrots extensions with fallback fake functions for missing ops', 'check if the mmcv compiled C++ extension module is available on this system', 'create a stub function that warns and raises an exception for unsupported parrots ops', 'review the list of parrots ops that return values versus in-place operations', 'use the jit decorator to wrap a function for Parrots JIT compilation or pass-through', 'use the skip_no_elena decorator to conditionally skip tests when Elena backend is unavailable', 'check the parrots_jit_option variable to see if PARROTS_JIT_OPTION env var is set', 'summarize the jit decorator which provides a no-op fallback when Parrots Torch is not in use', 'review the skip_no_elena decorator which imports from parrots or falls back to a pass-through wrapper']
```

Usage

```
{'load_ext_standard': 'load a mmcv extension module by name and verify all required functions exist', 'load_ext_parrots': 'load mmcv parrots extensions with fallback fake functions for missing ops', 'check_ops_exist': 'check if the mmcv compiled C++ extension module is available on this system', 'get_fake_func': 'create a stub function that warns and raises an exception for unsupported parrots ops', 'has_return_value_ops': 'review the list of parrots ops that return values versus in-place operations'}
```

## File: facebookresearch_sapiens/cv/mmcv/utils/parrots_jit.py

Prompts

```
['run collect_env to gather Python, CUDA, PyTorch, and MMCV environment details into a dictionary', 'use collect_env to retrieve the NVCC or HIP compiler version from the current environment', 'call collect_env to get the installed MMCV version and its compiler details', 'run collect_env to diagnose GPU device types and CUDA availability for debugging', 'summarize the collect_env function which returns a dict of platform, Python, CUDA, PyTorch, and MMCV info', 'load a mmcv extension module by name and verify all required functions exist', 'load mmcv parrots extensions with fallback fake functions for missing ops', 'check if the mmcv compiled C++ extension module is available on this system', 'create a stub function that warns and raises an exception for unsupported parrots ops', 'review the list of parrots ops that return values versus in-place operations', 'use the jit decorator to wrap a function for Parrots JIT compilation or pass-through', 'use the skip_no_elena decorator to conditionally skip tests when Elena backend is unavailable', 'check the parrots_jit_option variable to see if PARROTS_JIT_OPTION env var is set', 'summarize the jit decorator which provides a no-op fallback when Parrots Torch is not in use', 'review the skip_no_elena decorator which imports from parrots or falls back to a pass-through wrapper']
```

Usage

```
{'use_jit_decorator': 'use the jit decorator to wrap a function for Parrots JIT compilation or pass-through', 'use_skip_no_elena_decorator': 'use the skip_no_elena decorator to conditionally skip tests when Elena backend is unavailable', 'check_parrots_jit_option': 'check the parrots_jit_option variable to see if PARROTS_JIT_OPTION env var is set', 'summarize_jit_decorator': 'summarize the jit decorator which provides a no-op fallback when Parrots Torch is not in use', 'review_skip_no_elena': 'review the skip_no_elena decorator which imports from parrots or falls back to a pass-through wrapper'}
```

