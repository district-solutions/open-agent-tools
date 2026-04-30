# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/layers/moe/ep_moe/kernels.py

Prompts

```
['run moe_ep_deepgemm_preprocess to sort topk_ids, compute src2dst mapping and FP8-quantize hidden states for grouped GEMM', 'run ep_scatter to scatter expert-received tokens and scales into per-expert output tensors using Triton kernels', 'run ep_gather to gather expert outputs back to token order using topk_ids, weights and input indices', 'run silu_and_mul_masked_post_quant_fwd to fuse SiLU activation, element-wise multiply and per-token-group FP8 quantization', 'run silu_and_mul_masked_post_per_tensor_quant_fwd to fuse SiLU, multiply and per-tensor FP8 quantization on masked expert tokens', 'build a DeepEPMoE layer for MoE expert parallel inference with FP8 quantization', 'create an NpuFuseEPMoE layer optimized for Ascend NPU hardware with fused dispatch and combine', 'test the MoriEPMoE class with aiter backend for expert parallel MoE inference', 'run the forward_aiter method using aiter fused_moe kernel with expert masking', 'build a get_moe_impl_class call to select the appropriate MoE implementation based on a2a backend']
```

Usage

```
{'run_moe_ep_deepgemm_preprocess': 'run moe_ep_deepgemm_preprocess to sort topk_ids, compute src2dst mapping and FP8-quantize hidden states for grouped GEMM', 'run_ep_scatter': 'run ep_scatter to scatter expert-received tokens and scales into per-expert output tensors using Triton kernels', 'run_ep_gather': 'run ep_gather to gather expert outputs back to token order using topk_ids, weights and input indices', 'run_silu_and_mul_masked_post_quant_fwd': 'run silu_and_mul_masked_post_quant_fwd to fuse SiLU activation, element-wise multiply and per-token-group FP8 quantization', 'run_silu_and_mul_masked_post_per_tensor_quant_fwd': 'run silu_and_mul_masked_post_per_tensor_quant_fwd to fuse SiLU, multiply and per-tensor FP8 quantization on masked expert tokens'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/moe/ep_moe/layer.py

Prompts

```
['run moe_ep_deepgemm_preprocess to sort topk_ids, compute src2dst mapping and FP8-quantize hidden states for grouped GEMM', 'run ep_scatter to scatter expert-received tokens and scales into per-expert output tensors using Triton kernels', 'run ep_gather to gather expert outputs back to token order using topk_ids, weights and input indices', 'run silu_and_mul_masked_post_quant_fwd to fuse SiLU activation, element-wise multiply and per-token-group FP8 quantization', 'run silu_and_mul_masked_post_per_tensor_quant_fwd to fuse SiLU, multiply and per-tensor FP8 quantization on masked expert tokens', 'build a DeepEPMoE layer for MoE expert parallel inference with FP8 quantization', 'create an NpuFuseEPMoE layer optimized for Ascend NPU hardware with fused dispatch and combine', 'test the MoriEPMoE class with aiter backend for expert parallel MoE inference', 'run the forward_aiter method using aiter fused_moe kernel with expert masking', 'build a get_moe_impl_class call to select the appropriate MoE implementation based on a2a backend']
```

Usage

```
{'build_DeepEPMoE': 'build a DeepEPMoE layer for MoE expert parallel inference with FP8 quantization', 'create_NpuFuseEPMoE': 'create an NpuFuseEPMoE layer optimized for Ascend NPU hardware with fused dispatch and combine', 'test_MoriEPMoE': 'test the MoriEPMoE class with aiter backend for expert parallel MoE inference', 'run_forward_aiter': 'run the forward_aiter method using aiter fused_moe kernel with expert masking', 'build_get_moe_impl_class': 'build a get_moe_impl_class call to select the appropriate MoE implementation based on a2a backend'}
```

