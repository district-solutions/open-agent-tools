# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/models/deepseek_common/attention_backend_handler.py

Prompts

```
['register an attention backend handler function in the AttentionBackendRegistry by backend name', 'get the registered attention handler function for a given backend name from AttentionBackendRegistry', 'handle flashinfer attention backend routing to select the appropriate forward method for DeepSeek models', 'handle triton attention backend routing to select the appropriate forward method for DeepSeek models', 'handle ascend NPU attention backend routing to select DSA or MHA forward method for DeepSeek models', 'load model weights from checkpoint for DeepSeek V2/V3 models with expert params and stacked param mappings', 'quantize weights to FP8 UE8M0 format for DeepSeek nvfp4 checkpoints', 'process kv_b_proj weights including AWQ dequantization, FP8 requantization, and split into w_kc and w_vc components', 'generate a filter function that tests whether layer and expert IDs from weight names match a logical experts map', 'mark NextN MoE weight scales as UE8M0 format to avoid requantization', 'get the AWQ dequantize function for the current device (CUDA, HIP, or NPU)', 'check if next-token MoE BF16-to-FP8 casting is enabled for a modelopt FP4 quant config', 'compute YaRN extrapolation mscale factor given a scale and mscale multiplier', 'compute Llama-4 style position scaling tensor from original max positions, beta, and position indices', 'list supported forward-absorb core attention backends (fa3, nsa, flashinfer, cutlass_mla, trtllm_mla, ascend)']
```

Usage

```
{'register_attention_backend': 'register an attention backend handler function in the AttentionBackendRegistry by backend name', 'get_attention_handler': 'get the registered attention handler function for a given backend name from AttentionBackendRegistry', 'handle_flashinfer_attention': 'handle flashinfer attention backend routing to select the appropriate forward method for DeepSeek models', 'handle_triton_attention': 'handle triton attention backend routing to select the appropriate forward method for DeepSeek models', 'handle_ascend_attention': 'handle ascend NPU attention backend routing to select DSA or MHA forward method for DeepSeek models'}
```

## File: sgl-project_sglang/python/sglang/srt/models/deepseek_common/deepseek_weight_loader.py

Prompts

```
['register an attention backend handler function in the AttentionBackendRegistry by backend name', 'get the registered attention handler function for a given backend name from AttentionBackendRegistry', 'handle flashinfer attention backend routing to select the appropriate forward method for DeepSeek models', 'handle triton attention backend routing to select the appropriate forward method for DeepSeek models', 'handle ascend NPU attention backend routing to select DSA or MHA forward method for DeepSeek models', 'load model weights from checkpoint for DeepSeek V2/V3 models with expert params and stacked param mappings', 'quantize weights to FP8 UE8M0 format for DeepSeek nvfp4 checkpoints', 'process kv_b_proj weights including AWQ dequantization, FP8 requantization, and split into w_kc and w_vc components', 'generate a filter function that tests whether layer and expert IDs from weight names match a logical experts map', 'mark NextN MoE weight scales as UE8M0 format to avoid requantization', 'get the AWQ dequantize function for the current device (CUDA, HIP, or NPU)', 'check if next-token MoE BF16-to-FP8 casting is enabled for a modelopt FP4 quant config', 'compute YaRN extrapolation mscale factor given a scale and mscale multiplier', 'compute Llama-4 style position scaling tensor from original max positions, beta, and position indices', 'list supported forward-absorb core attention backends (fa3, nsa, flashinfer, cutlass_mla, trtllm_mla, ascend)']
```

Usage

```
{'load_deepseek_weights': 'load model weights from checkpoint for DeepSeek V2/V3 models with expert params and stacked param mappings', 'quantize_weights_fp8_ue8m0': 'quantize weights to FP8 UE8M0 format for DeepSeek nvfp4 checkpoints', 'process_kv_b_proj_weights': 'process kv_b_proj weights including AWQ dequantization, FP8 requantization, and split into w_kc and w_vc components', 'filter_expert_weights': 'generate a filter function that tests whether layer and expert IDs from weight names match a logical experts map', 'mark_nextn_moe_weights_ue8m0': 'mark NextN MoE weight scales as UE8M0 format to avoid requantization'}
```

## File: sgl-project_sglang/python/sglang/srt/models/deepseek_common/utils.py

Prompts

```
['register an attention backend handler function in the AttentionBackendRegistry by backend name', 'get the registered attention handler function for a given backend name from AttentionBackendRegistry', 'handle flashinfer attention backend routing to select the appropriate forward method for DeepSeek models', 'handle triton attention backend routing to select the appropriate forward method for DeepSeek models', 'handle ascend NPU attention backend routing to select DSA or MHA forward method for DeepSeek models', 'load model weights from checkpoint for DeepSeek V2/V3 models with expert params and stacked param mappings', 'quantize weights to FP8 UE8M0 format for DeepSeek nvfp4 checkpoints', 'process kv_b_proj weights including AWQ dequantization, FP8 requantization, and split into w_kc and w_vc components', 'generate a filter function that tests whether layer and expert IDs from weight names match a logical experts map', 'mark NextN MoE weight scales as UE8M0 format to avoid requantization', 'get the AWQ dequantize function for the current device (CUDA, HIP, or NPU)', 'check if next-token MoE BF16-to-FP8 casting is enabled for a modelopt FP4 quant config', 'compute YaRN extrapolation mscale factor given a scale and mscale multiplier', 'compute Llama-4 style position scaling tensor from original max positions, beta, and position indices', 'list supported forward-absorb core attention backends (fa3, nsa, flashinfer, cutlass_mla, trtllm_mla, ascend)']
```

Usage

```
{'get_awq_dequantize_function': 'get the AWQ dequantize function for the current device (CUDA, HIP, or NPU)', 'check_moe_bf16_fp8_cast': 'check if next-token MoE BF16-to-FP8 casting is enabled for a modelopt FP4 quant config', 'compute_yarn_mscale': 'compute YaRN extrapolation mscale factor given a scale and mscale multiplier', 'compute_llama4_position_scaling': 'compute Llama-4 style position scaling tensor from original max positions, beta, and position indices', 'list_attention_backends': 'list supported forward-absorb core attention backends (fa3, nsa, flashinfer, cutlass_mla, trtllm_mla, ascend)'}
```

