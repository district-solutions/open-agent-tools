# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/attention/ops/deepseek_v4_ops/cache_utils.py

Prompts

```
['quantize bf16 K tensor to UE8M0 FP8 and insert into the paged K cache for DeepSeekV4', 'gather and dequantize FP8 K values from the paged cache back to bf16 for sparse prefill', 'map local topk indices to global KV cache slot IDs and count valid entries per token', 'concatenate topk compressed indices with sliding window attention indices for sparse prefill', 'run the Triton kernel that quantizes a single token K vector and writes it into a paged cache block', 'build a python module that applies fused RoPE and FP8 quantization to indexer query tensors for sparse attention', 'build a python module that applies fused RoPE and MXFP4 quantization with ue8m0 block scales to indexer query tensors', 'build a python module that quantizes fp32 values to E2M1 4-bit nibbles using bucketized boundaries for MXFP4 packing', 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-token FP8 quantization for DeepSeek V4 indexer', 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-block MXFP4 quantization using ue8m0 scales', 'build a triton kernel that fuses inverse RoPE rotation with block-scaled FP8 quantization for DeepseekV4 attention', 'create a function that quantizes attention output tensors to FP8 format with pre-transformed TMA-aligned scales', 'test the fused_inv_rope_fp8_quant function with bf16 attention output and verify FP8 quantized results', 'refactor the fused_inv_rope_fp8_quant kernel to support INT32-packed UE8M0 scale format for SM100 hardware', 'review the _fused_inv_rope_fp8_quant_per_head kernel for correct inverse RoPE rotation logic on rope dimensions', 'build a python module that applies fused Q and KV RMS normalization using the fused_q_kv_rmsnorm function', 'create a triton JIT kernel that performs fused Q and KV RMSNorm operations on GPU tensors', 'test the fused_q_kv_rmsnorm function with torch tensors to verify correct RMS normalization output', 'refactor the _fused_q_kv_rmsnorm_kernel to support additional normalization variants beyond RMSNorm', 'review the fused_q_kv_rmsnorm function for correctness of fp32 precision and stride handling']
```

Usage

```
{'quantize_and_insert_k_cache': 'quantize bf16 K tensor to UE8M0 FP8 and insert into the paged K cache for DeepSeekV4', 'dequantize_and_gather_k_cache': 'gather and dequantize FP8 K values from the paged cache back to bf16 for sparse prefill', 'compute_global_topk_indices_and_lens': 'map local topk indices to global KV cache slot IDs and count valid entries per token', 'combine_topk_swa_indices': 'concatenate topk compressed indices with sliding window attention indices for sparse prefill', 'quantize_and_insert_k_kernel': 'run the Triton kernel that quantizes a single token K vector and writes it into a paged cache block'}
```

## File: vllm-project_vllm/vllm/v1/attention/ops/deepseek_v4_ops/fused_indexer_q.py

Prompts

```
['quantize bf16 K tensor to UE8M0 FP8 and insert into the paged K cache for DeepSeekV4', 'gather and dequantize FP8 K values from the paged cache back to bf16 for sparse prefill', 'map local topk indices to global KV cache slot IDs and count valid entries per token', 'concatenate topk compressed indices with sliding window attention indices for sparse prefill', 'run the Triton kernel that quantizes a single token K vector and writes it into a paged cache block', 'build a python module that applies fused RoPE and FP8 quantization to indexer query tensors for sparse attention', 'build a python module that applies fused RoPE and MXFP4 quantization with ue8m0 block scales to indexer query tensors', 'build a python module that quantizes fp32 values to E2M1 4-bit nibbles using bucketized boundaries for MXFP4 packing', 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-token FP8 quantization for DeepSeek V4 indexer', 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-block MXFP4 quantization using ue8m0 scales', 'build a triton kernel that fuses inverse RoPE rotation with block-scaled FP8 quantization for DeepseekV4 attention', 'create a function that quantizes attention output tensors to FP8 format with pre-transformed TMA-aligned scales', 'test the fused_inv_rope_fp8_quant function with bf16 attention output and verify FP8 quantized results', 'refactor the fused_inv_rope_fp8_quant kernel to support INT32-packed UE8M0 scale format for SM100 hardware', 'review the _fused_inv_rope_fp8_quant_per_head kernel for correct inverse RoPE rotation logic on rope dimensions', 'build a python module that applies fused Q and KV RMS normalization using the fused_q_kv_rmsnorm function', 'create a triton JIT kernel that performs fused Q and KV RMSNorm operations on GPU tensors', 'test the fused_q_kv_rmsnorm function with torch tensors to verify correct RMS normalization output', 'refactor the _fused_q_kv_rmsnorm_kernel to support additional normalization variants beyond RMSNorm', 'review the fused_q_kv_rmsnorm function for correctness of fp32 precision and stride handling']
```

Usage

```
{'build_fused_indexer_q_rope_quant': 'build a python module that applies fused RoPE and FP8 quantization to indexer query tensors for sparse attention', 'build_mxfp4_quantization': 'build a python module that applies fused RoPE and MXFP4 quantization with ue8m0 block scales to indexer query tensors', 'build_e2m1_nibble_quantizer': 'build a python module that quantizes fp32 values to E2M1 4-bit nibbles using bucketized boundaries for MXFP4 packing', 'review_fused_indexer_q_rope_quant_kernel': 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-token FP8 quantization for DeepSeek V4 indexer', 'review_fused_indexer_q_rope_mxfp4_kernel': 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-block MXFP4 quantization using ue8m0 scales'}
```

## File: vllm-project_vllm/vllm/v1/attention/ops/deepseek_v4_ops/fused_inv_rope_fp8_quant.py

Prompts

```
['quantize bf16 K tensor to UE8M0 FP8 and insert into the paged K cache for DeepSeekV4', 'gather and dequantize FP8 K values from the paged cache back to bf16 for sparse prefill', 'map local topk indices to global KV cache slot IDs and count valid entries per token', 'concatenate topk compressed indices with sliding window attention indices for sparse prefill', 'run the Triton kernel that quantizes a single token K vector and writes it into a paged cache block', 'build a python module that applies fused RoPE and FP8 quantization to indexer query tensors for sparse attention', 'build a python module that applies fused RoPE and MXFP4 quantization with ue8m0 block scales to indexer query tensors', 'build a python module that quantizes fp32 values to E2M1 4-bit nibbles using bucketized boundaries for MXFP4 packing', 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-token FP8 quantization for DeepSeek V4 indexer', 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-block MXFP4 quantization using ue8m0 scales', 'build a triton kernel that fuses inverse RoPE rotation with block-scaled FP8 quantization for DeepseekV4 attention', 'create a function that quantizes attention output tensors to FP8 format with pre-transformed TMA-aligned scales', 'test the fused_inv_rope_fp8_quant function with bf16 attention output and verify FP8 quantized results', 'refactor the fused_inv_rope_fp8_quant kernel to support INT32-packed UE8M0 scale format for SM100 hardware', 'review the _fused_inv_rope_fp8_quant_per_head kernel for correct inverse RoPE rotation logic on rope dimensions', 'build a python module that applies fused Q and KV RMS normalization using the fused_q_kv_rmsnorm function', 'create a triton JIT kernel that performs fused Q and KV RMSNorm operations on GPU tensors', 'test the fused_q_kv_rmsnorm function with torch tensors to verify correct RMS normalization output', 'refactor the _fused_q_kv_rmsnorm_kernel to support additional normalization variants beyond RMSNorm', 'review the fused_q_kv_rmsnorm function for correctness of fp32 precision and stride handling']
```

Usage

```
{'build_fused_inv_rope_fp8_quant_kernel': 'build a triton kernel that fuses inverse RoPE rotation with block-scaled FP8 quantization for DeepseekV4 attention', 'create_fp8_quantization_for_attention_output': 'create a function that quantizes attention output tensors to FP8 format with pre-transformed TMA-aligned scales', 'test_fused_inv_rope_fp8_quant': 'test the fused_inv_rope_fp8_quant function with bf16 attention output and verify FP8 quantized results', 'refactor_tma_aligned_scales': 'refactor the fused_inv_rope_fp8_quant kernel to support INT32-packed UE8M0 scale format for SM100 hardware', 'review_inverse_rope_rotation': 'review the _fused_inv_rope_fp8_quant_per_head kernel for correct inverse RoPE rotation logic on rope dimensions'}
```

## File: vllm-project_vllm/vllm/v1/attention/ops/deepseek_v4_ops/fused_qk_rmsnorm.py

Prompts

```
['quantize bf16 K tensor to UE8M0 FP8 and insert into the paged K cache for DeepSeekV4', 'gather and dequantize FP8 K values from the paged cache back to bf16 for sparse prefill', 'map local topk indices to global KV cache slot IDs and count valid entries per token', 'concatenate topk compressed indices with sliding window attention indices for sparse prefill', 'run the Triton kernel that quantizes a single token K vector and writes it into a paged cache block', 'build a python module that applies fused RoPE and FP8 quantization to indexer query tensors for sparse attention', 'build a python module that applies fused RoPE and MXFP4 quantization with ue8m0 block scales to indexer query tensors', 'build a python module that quantizes fp32 values to E2M1 4-bit nibbles using bucketized boundaries for MXFP4 packing', 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-token FP8 quantization for DeepSeek V4 indexer', 'review the triton JIT kernel that fuses GPT-J interleaved RoPE with per-block MXFP4 quantization using ue8m0 scales', 'build a triton kernel that fuses inverse RoPE rotation with block-scaled FP8 quantization for DeepseekV4 attention', 'create a function that quantizes attention output tensors to FP8 format with pre-transformed TMA-aligned scales', 'test the fused_inv_rope_fp8_quant function with bf16 attention output and verify FP8 quantized results', 'refactor the fused_inv_rope_fp8_quant kernel to support INT32-packed UE8M0 scale format for SM100 hardware', 'review the _fused_inv_rope_fp8_quant_per_head kernel for correct inverse RoPE rotation logic on rope dimensions', 'build a python module that applies fused Q and KV RMS normalization using the fused_q_kv_rmsnorm function', 'create a triton JIT kernel that performs fused Q and KV RMSNorm operations on GPU tensors', 'test the fused_q_kv_rmsnorm function with torch tensors to verify correct RMS normalization output', 'refactor the _fused_q_kv_rmsnorm_kernel to support additional normalization variants beyond RMSNorm', 'review the fused_q_kv_rmsnorm function for correctness of fp32 precision and stride handling']
```

Usage

```
{'build_fused_qkv_rmsnorm': 'build a python module that applies fused Q and KV RMS normalization using the fused_q_kv_rmsnorm function', 'create_triton_kernel_rmsnorm': 'create a triton JIT kernel that performs fused Q and KV RMSNorm operations on GPU tensors', 'test_fused_qkv_rmsnorm': 'test the fused_q_kv_rmsnorm function with torch tensors to verify correct RMS normalization output', 'refactor_rmsnorm_kernel': 'refactor the _fused_q_kv_rmsnorm_kernel to support additional normalization variants beyond RMSNorm', 'review_fused_qkv_rmsnorm': 'review the fused_q_kv_rmsnorm function for correctness of fp32 precision and stride handling'}
```

