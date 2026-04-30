# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/triton_utils/allocation.py

Prompts

```
['build a function to set a custom triton memory allocator using a specified torch device', 'create an allocation function that returns a torch tensor of given size on the specified device', 'test the set_triton_allocator function with a CUDA device', 'refactor the set_triton_allocator to support multiple device types', 'review the set_triton_allocator function and its nested alloc_fn closure', 'test the HAS_TRITON check that detects whether triton or pytorch-triton-xpu is installed', 'check active triton drivers across triton.backends and validate exactly one active driver', 'create a TritonPlaceholder module that provides dummy decorators for jit, autotune, heuristics, and Config', 'create a TritonLanguagePlaceholder module with stub attributes for constexpr, dtype, int64, int32, tensor, exp, log, log2', 'review the distributed environment check that allows zero active triton drivers when CUDA_VISIBLE_DEVICES is empty']
```

Usage

```
{'build_set_triton_allocator': 'build a function to set a custom triton memory allocator using a specified torch device', 'create_alloc_fn': 'create an allocation function that returns a torch tensor of given size on the specified device', 'test_set_triton_allocator': 'test the set_triton_allocator function with a CUDA device', 'refactor_set_triton_allocator': 'refactor the set_triton_allocator to support multiple device types', 'review_set_triton_allocator': 'review the set_triton_allocator function and its nested alloc_fn closure'}
```

## File: vllm-project_vllm/vllm/triton_utils/importing.py

Prompts

```
['build a function to set a custom triton memory allocator using a specified torch device', 'create an allocation function that returns a torch tensor of given size on the specified device', 'test the set_triton_allocator function with a CUDA device', 'refactor the set_triton_allocator to support multiple device types', 'review the set_triton_allocator function and its nested alloc_fn closure', 'test the HAS_TRITON check that detects whether triton or pytorch-triton-xpu is installed', 'check active triton drivers across triton.backends and validate exactly one active driver', 'create a TritonPlaceholder module that provides dummy decorators for jit, autotune, heuristics, and Config', 'create a TritonLanguagePlaceholder module with stub attributes for constexpr, dtype, int64, int32, tensor, exp, log, log2', 'review the distributed environment check that allows zero active triton drivers when CUDA_VISIBLE_DEVICES is empty']
```

Usage

```
{'test_HAS_TRITON': 'test the HAS_TRITON check that detects whether triton or pytorch-triton-xpu is installed', 'check_active_triton_drivers': 'check active triton drivers across triton.backends and validate exactly one active driver', 'create_TritonPlaceholder': 'create a TritonPlaceholder module that provides dummy decorators for jit, autotune, heuristics, and Config', 'create_TritonLanguagePlaceholder': 'create a TritonLanguagePlaceholder module with stub attributes for constexpr, dtype, int64, int32, tensor, exp, log, log2', 'review_distributed_env_check': 'review the distributed environment check that allows zero active triton drivers when CUDA_VISIBLE_DEVICES is empty'}
```

