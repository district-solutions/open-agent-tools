# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/lora/ops/triton_ops/fp8_kernel_utils.py

Prompts

```
['build an FP8-compatible matrix multiplication kernel with quantization support for Triton GPU execution', 'run the LoRA shrink kernel that computes matrix product and stores results with FP8 quantization support', 'run the LoRA expand kernel that computes FP8 matrix product with dequantization and stores results', 'test the core matrix multiplication accumulation logic with block-wise and tensor-wise quantization paths', 'refactor the FP8 kernel utilities to support configurable block-wise quantization group sizes', 'run the mm_k Triton kernel to compute partial or complete matrix block products with split-K support', 'run the do_expand_kernel Triton kernel for LoRA expand matrix multiplication without split-K reduction', 'run the do_shrink_kernel Triton kernel for LoRA shrink matrix multiplication with split-K atomic reduction', 'review the mm_k Triton kernel that iterates through the K dimension with masking, casting, and GDC support', 'review the do_expand_kernel Triton kernel that computes LoRA expand matrix product with block pointer construction', 'create LoRAKernelMeta instance with make(max_loras, max_num_tokens, device) to prepare kernel metadata tensors', 'build LoRA kernel metadata tensors by calling prepare_tensors(token_lora_mapping) for a forward pass', 'test LoRAKernelMeta._reset method clears active_lora_ids, num_tokens_per_lora, and lora_token_start_loc to defaults', 'refactor LoRAKernelMeta.meta_args to return kernel metadata tuple with optional cudagraph specialization', 'review LoRAKernelMeta cudagraph specialization that rounds up num_active_loras to nearest captured_lora_counts value', 'build LoRA A pointer metadata from a list of weight tensors and a CUDA device for Triton grouped GEMM', 'build LoRA B pointer metadata with slice offsets, strides, and hidden sizes for Triton grouped GEMM', 'run LoRA kernel config lookup by operation type, batch size, hidden size, rank, and number of slices', 'test whether the current CUDA device supports programmatic dependent launch (PDL) with SM90+', 'test whether the current CUDA device supports tensor memory aliasing (TMA) with SM90+']
```

Usage

```
{'build_fp8_mm_kernel': 'build an FP8-compatible matrix multiplication kernel with quantization support for Triton GPU execution', 'run_shrink_kernel_fp8': 'run the LoRA shrink kernel that computes matrix product and stores results with FP8 quantization support', 'run_expand_kernel_fp8': 'run the LoRA expand kernel that computes FP8 matrix product with dequantization and stores results', 'test_accumulate_mm': 'test the core matrix multiplication accumulation logic with block-wise and tensor-wise quantization paths', 'refactor_fp8_kernel': 'refactor the FP8 kernel utilities to support configurable block-wise quantization group sizes'}
```

## File: vllm-project_vllm/vllm/lora/ops/triton_ops/kernel_utils.py

Prompts

```
['build an FP8-compatible matrix multiplication kernel with quantization support for Triton GPU execution', 'run the LoRA shrink kernel that computes matrix product and stores results with FP8 quantization support', 'run the LoRA expand kernel that computes FP8 matrix product with dequantization and stores results', 'test the core matrix multiplication accumulation logic with block-wise and tensor-wise quantization paths', 'refactor the FP8 kernel utilities to support configurable block-wise quantization group sizes', 'run the mm_k Triton kernel to compute partial or complete matrix block products with split-K support', 'run the do_expand_kernel Triton kernel for LoRA expand matrix multiplication without split-K reduction', 'run the do_shrink_kernel Triton kernel for LoRA shrink matrix multiplication with split-K atomic reduction', 'review the mm_k Triton kernel that iterates through the K dimension with masking, casting, and GDC support', 'review the do_expand_kernel Triton kernel that computes LoRA expand matrix product with block pointer construction', 'create LoRAKernelMeta instance with make(max_loras, max_num_tokens, device) to prepare kernel metadata tensors', 'build LoRA kernel metadata tensors by calling prepare_tensors(token_lora_mapping) for a forward pass', 'test LoRAKernelMeta._reset method clears active_lora_ids, num_tokens_per_lora, and lora_token_start_loc to defaults', 'refactor LoRAKernelMeta.meta_args to return kernel metadata tuple with optional cudagraph specialization', 'review LoRAKernelMeta cudagraph specialization that rounds up num_active_loras to nearest captured_lora_counts value', 'build LoRA A pointer metadata from a list of weight tensors and a CUDA device for Triton grouped GEMM', 'build LoRA B pointer metadata with slice offsets, strides, and hidden sizes for Triton grouped GEMM', 'run LoRA kernel config lookup by operation type, batch size, hidden size, rank, and number of slices', 'test whether the current CUDA device supports programmatic dependent launch (PDL) with SM90+', 'test whether the current CUDA device supports tensor memory aliasing (TMA) with SM90+']
```

Usage

```
{'run_mm_k': 'run the mm_k Triton kernel to compute partial or complete matrix block products with split-K support', 'run_do_expand_kernel': 'run the do_expand_kernel Triton kernel for LoRA expand matrix multiplication without split-K reduction', 'run_do_shrink_kernel': 'run the do_shrink_kernel Triton kernel for LoRA shrink matrix multiplication with split-K atomic reduction', 'review_mm_k': 'review the mm_k Triton kernel that iterates through the K dimension with masking, casting, and GDC support', 'review_do_expand_kernel': 'review the do_expand_kernel Triton kernel that computes LoRA expand matrix product with block pointer construction'}
```

## File: vllm-project_vllm/vllm/lora/ops/triton_ops/lora_kernel_metadata.py

Prompts

```
['build an FP8-compatible matrix multiplication kernel with quantization support for Triton GPU execution', 'run the LoRA shrink kernel that computes matrix product and stores results with FP8 quantization support', 'run the LoRA expand kernel that computes FP8 matrix product with dequantization and stores results', 'test the core matrix multiplication accumulation logic with block-wise and tensor-wise quantization paths', 'refactor the FP8 kernel utilities to support configurable block-wise quantization group sizes', 'run the mm_k Triton kernel to compute partial or complete matrix block products with split-K support', 'run the do_expand_kernel Triton kernel for LoRA expand matrix multiplication without split-K reduction', 'run the do_shrink_kernel Triton kernel for LoRA shrink matrix multiplication with split-K atomic reduction', 'review the mm_k Triton kernel that iterates through the K dimension with masking, casting, and GDC support', 'review the do_expand_kernel Triton kernel that computes LoRA expand matrix product with block pointer construction', 'create LoRAKernelMeta instance with make(max_loras, max_num_tokens, device) to prepare kernel metadata tensors', 'build LoRA kernel metadata tensors by calling prepare_tensors(token_lora_mapping) for a forward pass', 'test LoRAKernelMeta._reset method clears active_lora_ids, num_tokens_per_lora, and lora_token_start_loc to defaults', 'refactor LoRAKernelMeta.meta_args to return kernel metadata tuple with optional cudagraph specialization', 'review LoRAKernelMeta cudagraph specialization that rounds up num_active_loras to nearest captured_lora_counts value', 'build LoRA A pointer metadata from a list of weight tensors and a CUDA device for Triton grouped GEMM', 'build LoRA B pointer metadata with slice offsets, strides, and hidden sizes for Triton grouped GEMM', 'run LoRA kernel config lookup by operation type, batch size, hidden size, rank, and number of slices', 'test whether the current CUDA device supports programmatic dependent launch (PDL) with SM90+', 'test whether the current CUDA device supports tensor memory aliasing (TMA) with SM90+']
```

Usage

```
{'create_LoRAKernelMeta': 'create LoRAKernelMeta instance with make(max_loras, max_num_tokens, device) to prepare kernel metadata tensors', 'build_LoRAKernelMeta_tensors': 'build LoRA kernel metadata tensors by calling prepare_tensors(token_lora_mapping) for a forward pass', 'test_LoRAKernelMeta_reset': 'test LoRAKernelMeta._reset method clears active_lora_ids, num_tokens_per_lora, and lora_token_start_loc to defaults', 'refactor_LoRAKernelMeta_meta_args': 'refactor LoRAKernelMeta.meta_args to return kernel metadata tuple with optional cudagraph specialization', 'review_LoRAKernelMeta_cudagraph': 'review LoRAKernelMeta cudagraph specialization that rounds up num_active_loras to nearest captured_lora_counts value'}
```

## File: vllm-project_vllm/vllm/lora/ops/triton_ops/utils.py

Prompts

```
['build an FP8-compatible matrix multiplication kernel with quantization support for Triton GPU execution', 'run the LoRA shrink kernel that computes matrix product and stores results with FP8 quantization support', 'run the LoRA expand kernel that computes FP8 matrix product with dequantization and stores results', 'test the core matrix multiplication accumulation logic with block-wise and tensor-wise quantization paths', 'refactor the FP8 kernel utilities to support configurable block-wise quantization group sizes', 'run the mm_k Triton kernel to compute partial or complete matrix block products with split-K support', 'run the do_expand_kernel Triton kernel for LoRA expand matrix multiplication without split-K reduction', 'run the do_shrink_kernel Triton kernel for LoRA shrink matrix multiplication with split-K atomic reduction', 'review the mm_k Triton kernel that iterates through the K dimension with masking, casting, and GDC support', 'review the do_expand_kernel Triton kernel that computes LoRA expand matrix product with block pointer construction', 'create LoRAKernelMeta instance with make(max_loras, max_num_tokens, device) to prepare kernel metadata tensors', 'build LoRA kernel metadata tensors by calling prepare_tensors(token_lora_mapping) for a forward pass', 'test LoRAKernelMeta._reset method clears active_lora_ids, num_tokens_per_lora, and lora_token_start_loc to defaults', 'refactor LoRAKernelMeta.meta_args to return kernel metadata tuple with optional cudagraph specialization', 'review LoRAKernelMeta cudagraph specialization that rounds up num_active_loras to nearest captured_lora_counts value', 'build LoRA A pointer metadata from a list of weight tensors and a CUDA device for Triton grouped GEMM', 'build LoRA B pointer metadata with slice offsets, strides, and hidden sizes for Triton grouped GEMM', 'run LoRA kernel config lookup by operation type, batch size, hidden size, rank, and number of slices', 'test whether the current CUDA device supports programmatic dependent launch (PDL) with SM90+', 'test whether the current CUDA device supports tensor memory aliasing (TMA) with SM90+']
```

Usage

```
{'build_lora_a_ptr': 'build LoRA A pointer metadata from a list of weight tensors and a CUDA device for Triton grouped GEMM', 'build_lora_b_ptr': 'build LoRA B pointer metadata with slice offsets, strides, and hidden sizes for Triton grouped GEMM', 'run_lora_op_configs': 'run LoRA kernel config lookup by operation type, batch size, hidden size, rank, and number of slices', 'test_supports_pdl': 'test whether the current CUDA device supports programmatic dependent launch (PDL) with SM90+', 'test_supports_tma': 'test whether the current CUDA device supports tensor memory aliasing (TMA) with SM90+'}
```

