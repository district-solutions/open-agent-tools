# Agent Python Tools

- repo: unslothai/unsloth
- repo_uri: https://github.com/unslothai/unsloth.git

## File: unslothai_unsloth/unsloth/kernels/moe/grouped_gemm/reference/moe_block.py

Prompts

```
['create a Qwen3MoeFusedGroupedGEMMBlock with config, gate, gate_up_proj, and down_proj tensors for fused MoE inference', 'build a Qwen3MoeFusedGroupedGEMMBlock from a Hugging Face Qwen3MoeSparseMoeBlock using from_hf factory method', 'run a forward pass through the fused MoE block that applies grouped GEMM with router gating and top-k expert selection', 'configure kernel tuning with autotune or explicit KernelConfigForward, KernelConfigBackward_dW, and KernelConfigBackward_dX settings', 'apply permute and unpermute operations to reorder tokens between token order and expert order in grouped GEMM', 'permute token hidden states by expert using gather indices for grouped GEMM ordering', 'unpermute grouped GEMM outputs back to original token order using scatter indices', 'calculate top-k expert routing weights and IDs with softmax or sigmoid activation and renormalization', 'get per-expert token counts and sorted gather indices for routing tokens to experts', 'run grouped matrix multiplication across expert weights with dynamic per-expert token counts']
```

Usage

```
{'create_Qwen3MoeFusedGroupedGEMMBlock': 'create a Qwen3MoeFusedGroupedGEMMBlock with config, gate, gate_up_proj, and down_proj tensors for fused MoE inference', 'build_from_hf_moe_block': 'build a Qwen3MoeFusedGroupedGEMMBlock from a Hugging Face Qwen3MoeSparseMoeBlock using from_hf factory method', 'run_forward_pass': 'run a forward pass through the fused MoE block that applies grouped GEMM with router gating and top-k expert selection', 'configure_kernel_tuning': 'configure kernel tuning with autotune or explicit KernelConfigForward, KernelConfigBackward_dW, and KernelConfigBackward_dX settings', 'apply_permute_unpermute': 'apply permute and unpermute operations to reorder tokens between token order and expert order in grouped GEMM'}
```

## File: unslothai_unsloth/unsloth/kernels/moe/grouped_gemm/reference/moe_ops.py

Prompts

```
['create a Qwen3MoeFusedGroupedGEMMBlock with config, gate, gate_up_proj, and down_proj tensors for fused MoE inference', 'build a Qwen3MoeFusedGroupedGEMMBlock from a Hugging Face Qwen3MoeSparseMoeBlock using from_hf factory method', 'run a forward pass through the fused MoE block that applies grouped GEMM with router gating and top-k expert selection', 'configure kernel tuning with autotune or explicit KernelConfigForward, KernelConfigBackward_dW, and KernelConfigBackward_dX settings', 'apply permute and unpermute operations to reorder tokens between token order and expert order in grouped GEMM', 'permute token hidden states by expert using gather indices for grouped GEMM ordering', 'unpermute grouped GEMM outputs back to original token order using scatter indices', 'calculate top-k expert routing weights and IDs with softmax or sigmoid activation and renormalization', 'get per-expert token counts and sorted gather indices for routing tokens to experts', 'run grouped matrix multiplication across expert weights with dynamic per-expert token counts']
```

Usage

```
{'create_permute_tokens': 'permute token hidden states by expert using gather indices for grouped GEMM ordering', 'create_unpermute_tokens': 'unpermute grouped GEMM outputs back to original token order using scatter indices', 'calculate_topk_experts': 'calculate top-k expert routing weights and IDs with softmax or sigmoid activation and renormalization', 'get_routing_indices': 'get per-expert token counts and sorted gather indices for routing tokens to experts', 'run_torch_grouped_gemm': 'run grouped matrix multiplication across expert weights with dynamic per-expert token counts'}
```

