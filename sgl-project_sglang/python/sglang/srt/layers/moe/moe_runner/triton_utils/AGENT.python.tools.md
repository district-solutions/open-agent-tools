# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/layers/moe/moe_runner/triton_utils/fused_moe.py

Prompts

```
['run the fused MoE layer with hidden states, expert weights, and top-k gating output', 'create a fused MoE computation pipeline with expert weights, top-k ids, and activation function', 'test the fused MoE expert computation with optional quantization and gating parameters', 'refactor the inplace fused MoE expert kernel to mutate hidden states in-place', 'summarize the MoE kernel sequence with gate, activation, down-projection, and token combination steps', 'build a function that generates a JSON config file name from MoE parameters like E, N, dtype, and block_shape', 'create a function that loads optimized Triton fused MoE kernel configurations from versioned JSON config files', 'create a function that returns default block size tuning parameters for the fused MoE kernel based on dtype and shape', 'test the function that loads optimal MoE kernel config from JSON files or falls back to default config', 'create a function that maps torch dtype and quantization flags to a config dtype string like fp8_w8a8 or int8_w8a8', 'invoke the fused MoE kernel to perform expert-parallel matrix multiplication with fp8 or int8 quantization', 'run the triton activation and multiply kernel for gate-up output with silu or gelu activation', 'run the MoE sum-reduce kernel to aggregate top-k expert outputs with a scaling factor', 'build topk ids and weights tensors appended with shared expert entries and a scale factor', 'build topk ids and weights tensors appended with shared expert entries using per-token shared weights', 'create a function that aligns token distribution across experts for block size matrix multiplication', 'build sorted token IDs tensor from top-k expert assignments padded to block size', 'test the moe_align_block_size function with topk_ids, block_size, and num_experts parameters', 'refactor the moe_align_block_size function to support expert parallelism with filtered expert IDs', 'summarize the moe_align_block_size function that pads tokens per expert for block matrix operations']
```

Usage

```
{'run_fused_moe': 'run the fused MoE layer with hidden states, expert weights, and top-k gating output', 'create_fused_experts_impl': 'create a fused MoE computation pipeline with expert weights, top-k ids, and activation function', 'test_fused_experts': 'test the fused MoE expert computation with optional quantization and gating parameters', 'refactor_inplace_fused_experts': 'refactor the inplace fused MoE expert kernel to mutate hidden states in-place', 'summarize_fused_moe_kernel_sequence': 'summarize the MoE kernel sequence with gate, activation, down-projection, and token combination steps'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/moe/moe_runner/triton_utils/fused_moe_triton_config.py

Prompts

```
['run the fused MoE layer with hidden states, expert weights, and top-k gating output', 'create a fused MoE computation pipeline with expert weights, top-k ids, and activation function', 'test the fused MoE expert computation with optional quantization and gating parameters', 'refactor the inplace fused MoE expert kernel to mutate hidden states in-place', 'summarize the MoE kernel sequence with gate, activation, down-projection, and token combination steps', 'build a function that generates a JSON config file name from MoE parameters like E, N, dtype, and block_shape', 'create a function that loads optimized Triton fused MoE kernel configurations from versioned JSON config files', 'create a function that returns default block size tuning parameters for the fused MoE kernel based on dtype and shape', 'test the function that loads optimal MoE kernel config from JSON files or falls back to default config', 'create a function that maps torch dtype and quantization flags to a config dtype string like fp8_w8a8 or int8_w8a8', 'invoke the fused MoE kernel to perform expert-parallel matrix multiplication with fp8 or int8 quantization', 'run the triton activation and multiply kernel for gate-up output with silu or gelu activation', 'run the MoE sum-reduce kernel to aggregate top-k expert outputs with a scaling factor', 'build topk ids and weights tensors appended with shared expert entries and a scale factor', 'build topk ids and weights tensors appended with shared expert entries using per-token shared weights', 'create a function that aligns token distribution across experts for block size matrix multiplication', 'build sorted token IDs tensor from top-k expert assignments padded to block size', 'test the moe_align_block_size function with topk_ids, block_size, and num_experts parameters', 'refactor the moe_align_block_size function to support expert parallelism with filtered expert IDs', 'summarize the moe_align_block_size function that pads tokens per expert for block matrix operations']
```

Usage

```
{'build_get_config_file_name': 'build a function that generates a JSON config file name from MoE parameters like E, N, dtype, and block_shape', 'create_get_moe_configs': 'create a function that loads optimized Triton fused MoE kernel configurations from versioned JSON config files', 'create_get_default_config': 'create a function that returns default block size tuning parameters for the fused MoE kernel based on dtype and shape', 'test_try_get_optimal_moe_config': 'test the function that loads optimal MoE kernel config from JSON files or falls back to default config', 'create_get_config_dtype_str': 'create a function that maps torch dtype and quantization flags to a config dtype string like fp8_w8a8 or int8_w8a8'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/moe/moe_runner/triton_utils/fused_moe_triton_kernels.py

Prompts

```
['run the fused MoE layer with hidden states, expert weights, and top-k gating output', 'create a fused MoE computation pipeline with expert weights, top-k ids, and activation function', 'test the fused MoE expert computation with optional quantization and gating parameters', 'refactor the inplace fused MoE expert kernel to mutate hidden states in-place', 'summarize the MoE kernel sequence with gate, activation, down-projection, and token combination steps', 'build a function that generates a JSON config file name from MoE parameters like E, N, dtype, and block_shape', 'create a function that loads optimized Triton fused MoE kernel configurations from versioned JSON config files', 'create a function that returns default block size tuning parameters for the fused MoE kernel based on dtype and shape', 'test the function that loads optimal MoE kernel config from JSON files or falls back to default config', 'create a function that maps torch dtype and quantization flags to a config dtype string like fp8_w8a8 or int8_w8a8', 'invoke the fused MoE kernel to perform expert-parallel matrix multiplication with fp8 or int8 quantization', 'run the triton activation and multiply kernel for gate-up output with silu or gelu activation', 'run the MoE sum-reduce kernel to aggregate top-k expert outputs with a scaling factor', 'build topk ids and weights tensors appended with shared expert entries and a scale factor', 'build topk ids and weights tensors appended with shared expert entries using per-token shared weights', 'create a function that aligns token distribution across experts for block size matrix multiplication', 'build sorted token IDs tensor from top-k expert assignments padded to block size', 'test the moe_align_block_size function with topk_ids, block_size, and num_experts parameters', 'refactor the moe_align_block_size function to support expert parallelism with filtered expert IDs', 'summarize the moe_align_block_size function that pads tokens per expert for block matrix operations']
```

Usage

```
{'invoke_fused_moe_kernel': 'invoke the fused MoE kernel to perform expert-parallel matrix multiplication with fp8 or int8 quantization', 'act_and_mul_triton': 'run the triton activation and multiply kernel for gate-up output with silu or gelu activation', 'moe_sum_reduce_triton': 'run the MoE sum-reduce kernel to aggregate top-k expert outputs with a scaling factor', 'fused_append_shared_experts': 'build topk ids and weights tensors appended with shared expert entries and a scale factor', 'fused_append_shared_experts_with_weights': 'build topk ids and weights tensors appended with shared expert entries using per-token shared weights'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/moe/moe_runner/triton_utils/moe_align_block_size.py

Prompts

```
['run the fused MoE layer with hidden states, expert weights, and top-k gating output', 'create a fused MoE computation pipeline with expert weights, top-k ids, and activation function', 'test the fused MoE expert computation with optional quantization and gating parameters', 'refactor the inplace fused MoE expert kernel to mutate hidden states in-place', 'summarize the MoE kernel sequence with gate, activation, down-projection, and token combination steps', 'build a function that generates a JSON config file name from MoE parameters like E, N, dtype, and block_shape', 'create a function that loads optimized Triton fused MoE kernel configurations from versioned JSON config files', 'create a function that returns default block size tuning parameters for the fused MoE kernel based on dtype and shape', 'test the function that loads optimal MoE kernel config from JSON files or falls back to default config', 'create a function that maps torch dtype and quantization flags to a config dtype string like fp8_w8a8 or int8_w8a8', 'invoke the fused MoE kernel to perform expert-parallel matrix multiplication with fp8 or int8 quantization', 'run the triton activation and multiply kernel for gate-up output with silu or gelu activation', 'run the MoE sum-reduce kernel to aggregate top-k expert outputs with a scaling factor', 'build topk ids and weights tensors appended with shared expert entries and a scale factor', 'build topk ids and weights tensors appended with shared expert entries using per-token shared weights', 'create a function that aligns token distribution across experts for block size matrix multiplication', 'build sorted token IDs tensor from top-k expert assignments padded to block size', 'test the moe_align_block_size function with topk_ids, block_size, and num_experts parameters', 'refactor the moe_align_block_size function to support expert parallelism with filtered expert IDs', 'summarize the moe_align_block_size function that pads tokens per expert for block matrix operations']
```

Usage

```
{'create_moe_align_block_size': 'create a function that aligns token distribution across experts for block size matrix multiplication', 'build_sorted_token_ids': 'build sorted token IDs tensor from top-k expert assignments padded to block size', 'test_moe_align_block_size': 'test the moe_align_block_size function with topk_ids, block_size, and num_experts parameters', 'refactor_moe_align_block_size': 'refactor the moe_align_block_size function to support expert parallelism with filtered expert IDs', 'summarize_moe_align_block_size': 'summarize the moe_align_block_size function that pads tokens per expert for block matrix operations'}
```

