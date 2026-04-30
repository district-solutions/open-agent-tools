# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/layers/moe/fused_moe_triton/fused_marlin_moe.py

Prompts

```
['run the fused_marlin_moe function to compute a Mixture of Experts layer with top-k gating and quantized weights', 'build a call to fused_marlin_moe with hidden_states, quantized expert weights w1 and w2, gating_output, and topk_ids', 'test the get_scalar_type function with num_bits and has_zp parameters to return the correct scalar type', 'review the fused_marlin_moe function for shape assertions, block size selection, and workspace allocation logic', 'summarize the fused_marlin_moe function that performs a two-stage quantized MoE forward pass with silu_and_mul activation', 'create a FusedMoE layer with num_experts, hidden_size, intermediate_size, and quantization config for MoE transformer models', 'run the forward pass of a FusedMoE layer given hidden_states and topk_output to compute expert-activated outputs', 'build expert parameter mappings from checkpoint names to FusedMoE weight names for loading MoE expert weights', 'test the weight_loader method to load checkpoint weights into a FusedMoE layer with TP sharding and quantization support', 'create a MoE token dispatcher (standard, DeepEP, or FlashInfer) based on the configured a2a backend for expert routing', 'run the triton MoE forward pass with hidden states, expert weights, and top-k routing output', 'run the triton fused experts kernel with routing data, gather indices, and scatter indices for MoE computation', 'run the triton MoE forward pass with bias terms and expert weights for MoE layers', 'run the triton fused experts kernel with bias, precision config, and fused activation for MoE layers', 'quantize expert weights to bfloat16 with InFlexData for triton MoE kernel input']
```

Usage

```
{'run_fused_marlin_moe': 'run the fused_marlin_moe function to compute a Mixture of Experts layer with top-k gating and quantized weights', 'build_fused_marlin_moe_call': 'build a call to fused_marlin_moe with hidden_states, quantized expert weights w1 and w2, gating_output, and topk_ids', 'test_get_scalar_type': 'test the get_scalar_type function with num_bits and has_zp parameters to return the correct scalar type', 'review_fused_marlin_moe': 'review the fused_marlin_moe function for shape assertions, block size selection, and workspace allocation logic', 'summarize_fused_marlin_moe': 'summarize the fused_marlin_moe function that performs a two-stage quantized MoE forward pass with silu_and_mul activation'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/moe/fused_moe_triton/layer.py

Prompts

```
['run the fused_marlin_moe function to compute a Mixture of Experts layer with top-k gating and quantized weights', 'build a call to fused_marlin_moe with hidden_states, quantized expert weights w1 and w2, gating_output, and topk_ids', 'test the get_scalar_type function with num_bits and has_zp parameters to return the correct scalar type', 'review the fused_marlin_moe function for shape assertions, block size selection, and workspace allocation logic', 'summarize the fused_marlin_moe function that performs a two-stage quantized MoE forward pass with silu_and_mul activation', 'create a FusedMoE layer with num_experts, hidden_size, intermediate_size, and quantization config for MoE transformer models', 'run the forward pass of a FusedMoE layer given hidden_states and topk_output to compute expert-activated outputs', 'build expert parameter mappings from checkpoint names to FusedMoE weight names for loading MoE expert weights', 'test the weight_loader method to load checkpoint weights into a FusedMoE layer with TP sharding and quantization support', 'create a MoE token dispatcher (standard, DeepEP, or FlashInfer) based on the configured a2a backend for expert routing', 'run the triton MoE forward pass with hidden states, expert weights, and top-k routing output', 'run the triton fused experts kernel with routing data, gather indices, and scatter indices for MoE computation', 'run the triton MoE forward pass with bias terms and expert weights for MoE layers', 'run the triton fused experts kernel with bias, precision config, and fused activation for MoE layers', 'quantize expert weights to bfloat16 with InFlexData for triton MoE kernel input']
```

Usage

```
{'create_FusedMoE_layer': 'create a FusedMoE layer with num_experts, hidden_size, intermediate_size, and quantization config for MoE transformer models', 'run_FusedMoE_forward': 'run the forward pass of a FusedMoE layer given hidden_states and topk_output to compute expert-activated outputs', 'build_expert_params_mapping': 'build expert parameter mappings from checkpoint names to FusedMoE weight names for loading MoE expert weights', 'test_weight_loader': 'test the weight_loader method to load checkpoint weights into a FusedMoE layer with TP sharding and quantization support', 'create_moe_dispatcher': 'create a MoE token dispatcher (standard, DeepEP, or FlashInfer) based on the configured a2a backend for expert routing'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/moe/fused_moe_triton/triton_kernels_moe.py

Prompts

```
['run the fused_marlin_moe function to compute a Mixture of Experts layer with top-k gating and quantized weights', 'build a call to fused_marlin_moe with hidden_states, quantized expert weights w1 and w2, gating_output, and topk_ids', 'test the get_scalar_type function with num_bits and has_zp parameters to return the correct scalar type', 'review the fused_marlin_moe function for shape assertions, block size selection, and workspace allocation logic', 'summarize the fused_marlin_moe function that performs a two-stage quantized MoE forward pass with silu_and_mul activation', 'create a FusedMoE layer with num_experts, hidden_size, intermediate_size, and quantization config for MoE transformer models', 'run the forward pass of a FusedMoE layer given hidden_states and topk_output to compute expert-activated outputs', 'build expert parameter mappings from checkpoint names to FusedMoE weight names for loading MoE expert weights', 'test the weight_loader method to load checkpoint weights into a FusedMoE layer with TP sharding and quantization support', 'create a MoE token dispatcher (standard, DeepEP, or FlashInfer) based on the configured a2a backend for expert routing', 'run the triton MoE forward pass with hidden states, expert weights, and top-k routing output', 'run the triton fused experts kernel with routing data, gather indices, and scatter indices for MoE computation', 'run the triton MoE forward pass with bias terms and expert weights for MoE layers', 'run the triton fused experts kernel with bias, precision config, and fused activation for MoE layers', 'quantize expert weights to bfloat16 with InFlexData for triton MoE kernel input']
```

Usage

```
{'run_triton_kernel_moe_forward': 'run the triton MoE forward pass with hidden states, expert weights, and top-k routing output', 'run_triton_kernel_fused_experts': 'run the triton fused experts kernel with routing data, gather indices, and scatter indices for MoE computation', 'run_triton_kernel_moe_with_bias_forward': 'run the triton MoE forward pass with bias terms and expert weights for MoE layers', 'run_triton_kernel_fused_experts_with_bias': 'run the triton fused experts kernel with bias, precision config, and fused activation for MoE layers', 'quantize_weights_bf16': 'quantize expert weights to bfloat16 with InFlexData for triton MoE kernel input'}
```

