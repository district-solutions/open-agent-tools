# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/kernels/aiter_ops.py

Prompts

```
['test if the aiter package is installed using is_aiter_found', 'create a rms_norm implementation for float16 and bfloat16 tensors using aiter kernels', 'register a custom aiter op with direct_register_aiter_op using an implementation and fake impl', 'build a torch Library fragment for wrapped aiter ops invisible to torch.compile', 'run rms_norm on multi-dimensional tensors by reshaping to 2D before applying normalization', 'test the has_oink_op function to check if a specific oink op is registered', 'test the _can_view_as_2d function to verify if a tensor can be reshaped without copying', 'test the _is_oink_stride_compatible_2d function to check if a tensor meets Oink stride constraints', 'test the oink_rms_supported lambda to validate input compatibility for Oink RMS normalization', 'run the rms_norm function to apply Oink-based RMS normalization on a 2D-like tensor', 'test the rms_norm function with a tensor input, weight tensor, and epsilon value', 'refactor the rms_norm function to support variance_size override parameter', 'review the rms_no_var_size lambda predicate used for rms_norm kernel argument validation', 'create a vLLM kernel implementation registered under the rms_norm operation with CUDA-alike platform support', 'test the is_xpu_kernels_found function to check if vLLM XPU kernels are installed', 'build a check using is_xpu_kernels_found to verify XPU kernel availability before use', 'review the rms_norm implementation that delegates to torch.ops._C.rms_norm for XPU acceleration', 'test the XPU_KERNELS_SUPPORTED constant to determine if XPU kernels are available']
```

Usage

```
{'test_is_aiter_found': 'test if the aiter package is installed using is_aiter_found', 'create_rms_norm': 'create a rms_norm implementation for float16 and bfloat16 tensors using aiter kernels', 'register_aiter_custom_op': 'register a custom aiter op with direct_register_aiter_op using an implementation and fake impl', 'build_rms_norm_with_library': 'build a torch Library fragment for wrapped aiter ops invisible to torch.compile', 'run_rms_norm_reshape': 'run rms_norm on multi-dimensional tensors by reshaping to 2D before applying normalization'}
```

## File: vllm-project_vllm/vllm/kernels/oink_ops.py

Prompts

```
['test if the aiter package is installed using is_aiter_found', 'create a rms_norm implementation for float16 and bfloat16 tensors using aiter kernels', 'register a custom aiter op with direct_register_aiter_op using an implementation and fake impl', 'build a torch Library fragment for wrapped aiter ops invisible to torch.compile', 'run rms_norm on multi-dimensional tensors by reshaping to 2D before applying normalization', 'test the has_oink_op function to check if a specific oink op is registered', 'test the _can_view_as_2d function to verify if a tensor can be reshaped without copying', 'test the _is_oink_stride_compatible_2d function to check if a tensor meets Oink stride constraints', 'test the oink_rms_supported lambda to validate input compatibility for Oink RMS normalization', 'run the rms_norm function to apply Oink-based RMS normalization on a 2D-like tensor', 'test the rms_norm function with a tensor input, weight tensor, and epsilon value', 'refactor the rms_norm function to support variance_size override parameter', 'review the rms_no_var_size lambda predicate used for rms_norm kernel argument validation', 'create a vLLM kernel implementation registered under the rms_norm operation with CUDA-alike platform support', 'test the is_xpu_kernels_found function to check if vLLM XPU kernels are installed', 'build a check using is_xpu_kernels_found to verify XPU kernel availability before use', 'review the rms_norm implementation that delegates to torch.ops._C.rms_norm for XPU acceleration', 'test the XPU_KERNELS_SUPPORTED constant to determine if XPU kernels are available']
```

Usage

```
{'test_has_oink_op': 'test the has_oink_op function to check if a specific oink op is registered', 'test_can_view_as_2d': 'test the _can_view_as_2d function to verify if a tensor can be reshaped without copying', 'test_is_oink_stride_compatible_2d': 'test the _is_oink_stride_compatible_2d function to check if a tensor meets Oink stride constraints', 'test_oink_rms_supported': 'test the oink_rms_supported lambda to validate input compatibility for Oink RMS normalization', 'run_rms_norm': 'run the rms_norm function to apply Oink-based RMS normalization on a 2D-like tensor'}
```

## File: vllm-project_vllm/vllm/kernels/vllm_c.py

Prompts

```
['test if the aiter package is installed using is_aiter_found', 'create a rms_norm implementation for float16 and bfloat16 tensors using aiter kernels', 'register a custom aiter op with direct_register_aiter_op using an implementation and fake impl', 'build a torch Library fragment for wrapped aiter ops invisible to torch.compile', 'run rms_norm on multi-dimensional tensors by reshaping to 2D before applying normalization', 'test the has_oink_op function to check if a specific oink op is registered', 'test the _can_view_as_2d function to verify if a tensor can be reshaped without copying', 'test the _is_oink_stride_compatible_2d function to check if a tensor meets Oink stride constraints', 'test the oink_rms_supported lambda to validate input compatibility for Oink RMS normalization', 'run the rms_norm function to apply Oink-based RMS normalization on a 2D-like tensor', 'test the rms_norm function with a tensor input, weight tensor, and epsilon value', 'refactor the rms_norm function to support variance_size override parameter', 'review the rms_no_var_size lambda predicate used for rms_norm kernel argument validation', 'create a vLLM kernel implementation registered under the rms_norm operation with CUDA-alike platform support', 'test the is_xpu_kernels_found function to check if vLLM XPU kernels are installed', 'build a check using is_xpu_kernels_found to verify XPU kernel availability before use', 'review the rms_norm implementation that delegates to torch.ops._C.rms_norm for XPU acceleration', 'test the XPU_KERNELS_SUPPORTED constant to determine if XPU kernels are available']
```

Usage

```
{'run_rms_norm': 'run the rms_norm kernel on a tensor with weight and epsilon parameters for CUDA-alike platforms', 'test_rms_norm': 'test the rms_norm function with a tensor input, weight tensor, and epsilon value', 'refactor_rms_norm': 'refactor the rms_norm function to support variance_size override parameter', 'review_rms_no_var_size': 'review the rms_no_var_size lambda predicate used for rms_norm kernel argument validation', 'create_rms_norm_impl': 'create a vLLM kernel implementation registered under the rms_norm operation with CUDA-alike platform support'}
```

## File: vllm-project_vllm/vllm/kernels/xpu_ops.py

Prompts

```
['test if the aiter package is installed using is_aiter_found', 'create a rms_norm implementation for float16 and bfloat16 tensors using aiter kernels', 'register a custom aiter op with direct_register_aiter_op using an implementation and fake impl', 'build a torch Library fragment for wrapped aiter ops invisible to torch.compile', 'run rms_norm on multi-dimensional tensors by reshaping to 2D before applying normalization', 'test the has_oink_op function to check if a specific oink op is registered', 'test the _can_view_as_2d function to verify if a tensor can be reshaped without copying', 'test the _is_oink_stride_compatible_2d function to check if a tensor meets Oink stride constraints', 'test the oink_rms_supported lambda to validate input compatibility for Oink RMS normalization', 'run the rms_norm function to apply Oink-based RMS normalization on a 2D-like tensor', 'test the rms_norm function with a tensor input, weight tensor, and epsilon value', 'refactor the rms_norm function to support variance_size override parameter', 'review the rms_no_var_size lambda predicate used for rms_norm kernel argument validation', 'create a vLLM kernel implementation registered under the rms_norm operation with CUDA-alike platform support', 'test the is_xpu_kernels_found function to check if vLLM XPU kernels are installed', 'build a check using is_xpu_kernels_found to verify XPU kernel availability before use', 'review the rms_norm implementation that delegates to torch.ops._C.rms_norm for XPU acceleration', 'test the XPU_KERNELS_SUPPORTED constant to determine if XPU kernels are available']
```

Usage

```
{'test_is_xpu_kernels_found': 'test the is_xpu_kernels_found function to check if vLLM XPU kernels are installed', 'run_rms_norm': 'run the rms_norm function to apply RMS normalization with optional weight tensor and epsilon', 'build_xpu_kernel_check': 'build a check using is_xpu_kernels_found to verify XPU kernel availability before use', 'review_rms_norm': 'review the rms_norm implementation that delegates to torch.ops._C.rms_norm for XPU acceleration', 'test_XPU_KERNELS_SUPPORTED': 'test the XPU_KERNELS_SUPPORTED constant to determine if XPU kernels are available'}
```

