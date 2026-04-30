# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/lora/backend/ascend_backend.py

Prompts

```
['run LoRA A shrink GEMM on NPU with segment lengths and scaling factors', 'run LoRA B expand GEMM on NPU with optional base output accumulation', 'run QKV LoRA forward with slice-based expand across three QKV output partitions', 'run Gate/Up LoRA forward with slice-based expand across two gate-up partitions', 'prepare LoRA batch info with weight indices, ranks, and scalings for forward pass', 'run LoRA A embedding lookup with CUDA graph support on input tokens and weights', 'initialize CUDA graph MoE intermediate buffers for LoRA with given batch size and ranks', 'initialize reusable LoRA batch info buffers for CUDA graph execution', 'determine optimal chunk size heuristically based on token count in forward batch', 'compute token permutation indices to group tokens by their LoRA adapter assignments', 'compute segment boundaries and weight indices for chunked SGMV kernel execution', 'init lm_head config for LoRA backend by resetting batch info and pass tracking state', 'build per-pass segment tuples from weight indices and pruned token lengths for chunked logprobs', 'prepare lm_head batch info tuple from forward batch, weight indices, and base batch info', 'build a LoRABatchInfo for pruned lm_head input using segments, batch info, chunk size, and expected tokens', 'test the LoRABackendLmHeadMixing class for chunked logprobs support with multiple LoRA adapters', 'register a new LoRA backend with a custom name using the register_lora_backend decorator', 'create a Triton-based LoRA backend class for SGLang inference', 'create a chunked SG-MV LoRA backend for optimized matrix operations', 'create an Ascend hardware-accelerated LoRA backend class', 'get a LoRA backend class by its registered name string', 'create a TorchNativeLoRABackend instance with max_loras_per_batch and torch device']
```

Usage

```
{'run_lora_a_sgemm': 'run LoRA A shrink GEMM on NPU with segment lengths and scaling factors', 'run_lora_b_sgemm': 'run LoRA B expand GEMM on NPU with optional base output accumulation', 'run_qkv_lora': 'run QKV LoRA forward with slice-based expand across three QKV output partitions', 'run_gate_up_lora': 'run Gate/Up LoRA forward with slice-based expand across two gate-up partitions', 'prepare_lora_batch': 'prepare LoRA batch info with weight indices, ranks, and scalings for forward pass'}
```

## File: sgl-project_sglang/python/sglang/srt/lora/backend/base_backend.py

Prompts

```
['run LoRA A shrink GEMM on NPU with segment lengths and scaling factors', 'run LoRA B expand GEMM on NPU with optional base output accumulation', 'run QKV LoRA forward with slice-based expand across three QKV output partitions', 'run Gate/Up LoRA forward with slice-based expand across two gate-up partitions', 'prepare LoRA batch info with weight indices, ranks, and scalings for forward pass', 'run LoRA A embedding lookup with CUDA graph support on input tokens and weights', 'initialize CUDA graph MoE intermediate buffers for LoRA with given batch size and ranks', 'initialize reusable LoRA batch info buffers for CUDA graph execution', 'determine optimal chunk size heuristically based on token count in forward batch', 'compute token permutation indices to group tokens by their LoRA adapter assignments', 'compute segment boundaries and weight indices for chunked SGMV kernel execution', 'init lm_head config for LoRA backend by resetting batch info and pass tracking state', 'build per-pass segment tuples from weight indices and pruned token lengths for chunked logprobs', 'prepare lm_head batch info tuple from forward batch, weight indices, and base batch info', 'build a LoRABatchInfo for pruned lm_head input using segments, batch info, chunk size, and expected tokens', 'test the LoRABackendLmHeadMixing class for chunked logprobs support with multiple LoRA adapters', 'register a new LoRA backend with a custom name using the register_lora_backend decorator', 'create a Triton-based LoRA backend class for SGLang inference', 'create a chunked SG-MV LoRA backend for optimized matrix operations', 'create an Ascend hardware-accelerated LoRA backend class', 'get a LoRA backend class by its registered name string', 'create a TorchNativeLoRABackend instance with max_loras_per_batch and torch device']
```

Usage

```
{'run_lora_a_embedding': 'run LoRA A embedding lookup with CUDA graph support on input tokens and weights', 'run_lora_a_sgemm': 'run segment GEMM of LoRA A modules on input matrix and LoRA weights', 'run_lora_b_sgemm': 'run segment GEMM of LoRA B modules on input matrix and LoRA weights', 'run_qkv_lora': 'run the LoRA pass for QKV projection layer with input matrix and LoRA weights', 'init_cuda_graph_moe_buffers': 'initialize CUDA graph MoE intermediate buffers for LoRA with given batch size and ranks'}
```

## File: sgl-project_sglang/python/sglang/srt/lora/backend/chunked_backend.py

Prompts

```
['run LoRA A shrink GEMM on NPU with segment lengths and scaling factors', 'run LoRA B expand GEMM on NPU with optional base output accumulation', 'run QKV LoRA forward with slice-based expand across three QKV output partitions', 'run Gate/Up LoRA forward with slice-based expand across two gate-up partitions', 'prepare LoRA batch info with weight indices, ranks, and scalings for forward pass', 'run LoRA A embedding lookup with CUDA graph support on input tokens and weights', 'initialize CUDA graph MoE intermediate buffers for LoRA with given batch size and ranks', 'initialize reusable LoRA batch info buffers for CUDA graph execution', 'determine optimal chunk size heuristically based on token count in forward batch', 'compute token permutation indices to group tokens by their LoRA adapter assignments', 'compute segment boundaries and weight indices for chunked SGMV kernel execution', 'init lm_head config for LoRA backend by resetting batch info and pass tracking state', 'build per-pass segment tuples from weight indices and pruned token lengths for chunked logprobs', 'prepare lm_head batch info tuple from forward batch, weight indices, and base batch info', 'build a LoRABatchInfo for pruned lm_head input using segments, batch info, chunk size, and expected tokens', 'test the LoRABackendLmHeadMixing class for chunked logprobs support with multiple LoRA adapters', 'register a new LoRA backend with a custom name using the register_lora_backend decorator', 'create a Triton-based LoRA backend class for SGLang inference', 'create a chunked SG-MV LoRA backend for optimized matrix operations', 'create an Ascend hardware-accelerated LoRA backend class', 'get a LoRA backend class by its registered name string', 'create a TorchNativeLoRABackend instance with max_loras_per_batch and torch device']
```

Usage

```
{'run_lora_a_embedding': 'run LoRA A embedding forward pass with input IDs, weights, and vocab size', 'run_lora_a_sgemm': 'run LoRA A shrink SGEMM forward pass with input tensor, weights, and batch info', 'run_lora_b_sgemm': 'run LoRA B expand SGEMM forward pass with input tensor, weights, and output offsets', 'run_qkv_lora': 'run QKV LoRA forward pass by chaining LoRA A shrink and LoRA B expand operations', 'run_gate_up_lora': 'run gate-up LoRA forward pass by chaining LoRA A shrink and LoRA B expand operations', 'prepare_lora_batch': 'prepare LoRA batch info by computing permutation, segments, and copying data to device', 'init_cuda_graph_batch_info': 'initialize reusable LoRA batch info buffers for CUDA graph execution', '_determine_chunk_size': 'determine optimal chunk size heuristically based on token count in forward batch', '_get_permutation': 'compute token permutation indices to group tokens by their LoRA adapter assignments', '_get_segments_info': 'compute segment boundaries and weight indices for chunked SGMV kernel execution'}
```

## File: sgl-project_sglang/python/sglang/srt/lora/backend/lmhead_mixing.py

Prompts

```
['run LoRA A shrink GEMM on NPU with segment lengths and scaling factors', 'run LoRA B expand GEMM on NPU with optional base output accumulation', 'run QKV LoRA forward with slice-based expand across three QKV output partitions', 'run Gate/Up LoRA forward with slice-based expand across two gate-up partitions', 'prepare LoRA batch info with weight indices, ranks, and scalings for forward pass', 'run LoRA A embedding lookup with CUDA graph support on input tokens and weights', 'initialize CUDA graph MoE intermediate buffers for LoRA with given batch size and ranks', 'initialize reusable LoRA batch info buffers for CUDA graph execution', 'determine optimal chunk size heuristically based on token count in forward batch', 'compute token permutation indices to group tokens by their LoRA adapter assignments', 'compute segment boundaries and weight indices for chunked SGMV kernel execution', 'init lm_head config for LoRA backend by resetting batch info and pass tracking state', 'build per-pass segment tuples from weight indices and pruned token lengths for chunked logprobs', 'prepare lm_head batch info tuple from forward batch, weight indices, and base batch info', 'build a LoRABatchInfo for pruned lm_head input using segments, batch info, chunk size, and expected tokens', 'test the LoRABackendLmHeadMixing class for chunked logprobs support with multiple LoRA adapters', 'register a new LoRA backend with a custom name using the register_lora_backend decorator', 'create a Triton-based LoRA backend class for SGLang inference', 'create a chunked SG-MV LoRA backend for optimized matrix operations', 'create an Ascend hardware-accelerated LoRA backend class', 'get a LoRA backend class by its registered name string', 'create a TorchNativeLoRABackend instance with max_loras_per_batch and torch device']
```

Usage

```
{'init_lm_head_config': 'init lm_head config for LoRA backend by resetting batch info and pass tracking state', 'build_lm_head_pass_segments': 'build per-pass segment tuples from weight indices and pruned token lengths for chunked logprobs', 'prepare_lm_head_batch_info': 'prepare lm_head batch info tuple from forward batch, weight indices, and base batch info', 'build_lm_head_batch_info': 'build a LoRABatchInfo for pruned lm_head input using segments, batch info, chunk size, and expected tokens', 'test_lm_head_mixing': 'test the LoRABackendLmHeadMixing class for chunked logprobs support with multiple LoRA adapters'}
```

## File: sgl-project_sglang/python/sglang/srt/lora/backend/lora_registry.py

Prompts

```
['run LoRA A shrink GEMM on NPU with segment lengths and scaling factors', 'run LoRA B expand GEMM on NPU with optional base output accumulation', 'run QKV LoRA forward with slice-based expand across three QKV output partitions', 'run Gate/Up LoRA forward with slice-based expand across two gate-up partitions', 'prepare LoRA batch info with weight indices, ranks, and scalings for forward pass', 'run LoRA A embedding lookup with CUDA graph support on input tokens and weights', 'initialize CUDA graph MoE intermediate buffers for LoRA with given batch size and ranks', 'initialize reusable LoRA batch info buffers for CUDA graph execution', 'determine optimal chunk size heuristically based on token count in forward batch', 'compute token permutation indices to group tokens by their LoRA adapter assignments', 'compute segment boundaries and weight indices for chunked SGMV kernel execution', 'init lm_head config for LoRA backend by resetting batch info and pass tracking state', 'build per-pass segment tuples from weight indices and pruned token lengths for chunked logprobs', 'prepare lm_head batch info tuple from forward batch, weight indices, and base batch info', 'build a LoRABatchInfo for pruned lm_head input using segments, batch info, chunk size, and expected tokens', 'test the LoRABackendLmHeadMixing class for chunked logprobs support with multiple LoRA adapters', 'register a new LoRA backend with a custom name using the register_lora_backend decorator', 'create a Triton-based LoRA backend class for SGLang inference', 'create a chunked SG-MV LoRA backend for optimized matrix operations', 'create an Ascend hardware-accelerated LoRA backend class', 'get a LoRA backend class by its registered name string', 'create a TorchNativeLoRABackend instance with max_loras_per_batch and torch device']
```

Usage

```
{'register_lora_backend': 'register a new LoRA backend with a custom name using the register_lora_backend decorator', 'create_triton_backend': 'create a Triton-based LoRA backend class for SGLang inference', 'create_triton_csgmv_backend': 'create a chunked SG-MV LoRA backend for optimized matrix operations', 'create_ascend_backend': 'create an Ascend hardware-accelerated LoRA backend class', 'get_backend_from_name': 'get a LoRA backend class by its registered name string'}
```

## File: sgl-project_sglang/python/sglang/srt/lora/backend/torch_backend.py

Prompts

```
['run LoRA A shrink GEMM on NPU with segment lengths and scaling factors', 'run LoRA B expand GEMM on NPU with optional base output accumulation', 'run QKV LoRA forward with slice-based expand across three QKV output partitions', 'run Gate/Up LoRA forward with slice-based expand across two gate-up partitions', 'prepare LoRA batch info with weight indices, ranks, and scalings for forward pass', 'run LoRA A embedding lookup with CUDA graph support on input tokens and weights', 'initialize CUDA graph MoE intermediate buffers for LoRA with given batch size and ranks', 'initialize reusable LoRA batch info buffers for CUDA graph execution', 'determine optimal chunk size heuristically based on token count in forward batch', 'compute token permutation indices to group tokens by their LoRA adapter assignments', 'compute segment boundaries and weight indices for chunked SGMV kernel execution', 'init lm_head config for LoRA backend by resetting batch info and pass tracking state', 'build per-pass segment tuples from weight indices and pruned token lengths for chunked logprobs', 'prepare lm_head batch info tuple from forward batch, weight indices, and base batch info', 'build a LoRABatchInfo for pruned lm_head input using segments, batch info, chunk size, and expected tokens', 'test the LoRABackendLmHeadMixing class for chunked logprobs support with multiple LoRA adapters', 'register a new LoRA backend with a custom name using the register_lora_backend decorator', 'create a Triton-based LoRA backend class for SGLang inference', 'create a chunked SG-MV LoRA backend for optimized matrix operations', 'create an Ascend hardware-accelerated LoRA backend class', 'get a LoRA backend class by its registered name string', 'create a TorchNativeLoRABackend instance with max_loras_per_batch and torch device']
```

Usage

```
{'create_TorchNativeLoRABackend': 'create a TorchNativeLoRABackend instance with max_loras_per_batch and torch device', 'run_lora_a_sgemm': 'run lora A sparse GEMM on input tensor with weights and batch info', 'run_lora_b_sgemm': 'run lora B sparse GEMM on input tensor with weights and optional base output', 'run_qkv_lora': 'run qkv lora forward pass with lora A and B weights, output offsets, and base output', 'prepare_lora_batch': 'prepare lora batch info from forward batch, weight indices, ranks, and scalings'}
```

## File: sgl-project_sglang/python/sglang/srt/lora/backend/triton_backend.py

Prompts

```
['run LoRA A shrink GEMM on NPU with segment lengths and scaling factors', 'run LoRA B expand GEMM on NPU with optional base output accumulation', 'run QKV LoRA forward with slice-based expand across three QKV output partitions', 'run Gate/Up LoRA forward with slice-based expand across two gate-up partitions', 'prepare LoRA batch info with weight indices, ranks, and scalings for forward pass', 'run LoRA A embedding lookup with CUDA graph support on input tokens and weights', 'initialize CUDA graph MoE intermediate buffers for LoRA with given batch size and ranks', 'initialize reusable LoRA batch info buffers for CUDA graph execution', 'determine optimal chunk size heuristically based on token count in forward batch', 'compute token permutation indices to group tokens by their LoRA adapter assignments', 'compute segment boundaries and weight indices for chunked SGMV kernel execution', 'init lm_head config for LoRA backend by resetting batch info and pass tracking state', 'build per-pass segment tuples from weight indices and pruned token lengths for chunked logprobs', 'prepare lm_head batch info tuple from forward batch, weight indices, and base batch info', 'build a LoRABatchInfo for pruned lm_head input using segments, batch info, chunk size, and expected tokens', 'test the LoRABackendLmHeadMixing class for chunked logprobs support with multiple LoRA adapters', 'register a new LoRA backend with a custom name using the register_lora_backend decorator', 'create a Triton-based LoRA backend class for SGLang inference', 'create a chunked SG-MV LoRA backend for optimized matrix operations', 'create an Ascend hardware-accelerated LoRA backend class', 'get a LoRA backend class by its registered name string', 'create a TorchNativeLoRABackend instance with max_loras_per_batch and torch device']
```

Usage

```
{'run_lora_a_embedding': 'run the TritonLoRABackend LoRA A embedding lookup with input ids, weights, and vocab size', 'run_lora_b_sgemm': 'run the TritonLoRABackend LoRA B sparse GEMM operation with input tensor and weights', 'run_qkv_lora': 'run the TritonLoRABackend QKV projection with LoRA A and LoRA B matrices', 'run_gate_up_lora': 'run the TritonLoRABackend gate and up FFN layers with LoRA A and LoRA B matrices', 'prepare_lora_batch': 'prepare the TritonLoRABackend LoRA batch info from forward batch, weight indices, ranks, and scalings'}
```

