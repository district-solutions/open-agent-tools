# Agent Python Tools

- repo: unslothai/unsloth
- repo_uri: https://github.com/unslothai/unsloth.git

## File: unslothai_unsloth/unsloth/kernels/moe/grouped_gemm/reference/layers/llama4_moe.py

Prompts

```
['build a Llama4MoE block with torch-native grouped gemm for expert computation', 'create a Llama4MoE block with triton grouped gemm for optimized expert computation', 'test the Llama4MoResult dataclass that holds intermediate MoE layer tensors and routing data', 'review the forward method of Llama4GroupedGemmTextMoe that runs router, permute, grouped gemm, and unpermute', 'summarize the forward method of Llama4TritonTextMoe that uses triton grouped gemm with kernel configs', 'create a Qwen3MoeGroupedGEMMBlock from a HuggingFace Qwen3MoeSparseMoeBlock using from_hf', 'create a fused Qwen3MoeFusedGroupedGEMMBlock with triton kernels and optional autotuning', 'run the Qwen3MoeGroupedGEMMBlock forward pass on hidden states and return expert routing results', 'extract and stack HuggingFace MoE expert weights into gate, gate_up_proj, and down_proj tensors', 'run the MoE router to compute routing weights and select top-k experts for each token']
```

Usage

```
{'build_Llama4GroupedGemmTextMoe': 'build a Llama4MoE block with torch-native grouped gemm for expert computation', 'create_Llama4TritonTextMoe': 'create a Llama4MoE block with triton grouped gemm for optimized expert computation', 'test_Llama4MoeResult': 'test the Llama4MoResult dataclass that holds intermediate MoE layer tensors and routing data', 'review_Llama4GroupedGemmTextMoe_forward': 'review the forward method of Llama4GroupedGemmTextMoe that runs router, permute, grouped gemm, and unpermute', 'summarize_Llama4TritonTextMoe_forward': 'summarize the forward method of Llama4TritonTextMoe that uses triton grouped gemm with kernel configs'}
```

## File: unslothai_unsloth/unsloth/kernels/moe/grouped_gemm/reference/layers/qwen3_moe.py

Prompts

```
['build a Llama4MoE block with torch-native grouped gemm for expert computation', 'create a Llama4MoE block with triton grouped gemm for optimized expert computation', 'test the Llama4MoResult dataclass that holds intermediate MoE layer tensors and routing data', 'review the forward method of Llama4GroupedGemmTextMoe that runs router, permute, grouped gemm, and unpermute', 'summarize the forward method of Llama4TritonTextMoe that uses triton grouped gemm with kernel configs', 'create a Qwen3MoeGroupedGEMMBlock from a HuggingFace Qwen3MoeSparseMoeBlock using from_hf', 'create a fused Qwen3MoeFusedGroupedGEMMBlock with triton kernels and optional autotuning', 'run the Qwen3MoeGroupedGEMMBlock forward pass on hidden states and return expert routing results', 'extract and stack HuggingFace MoE expert weights into gate, gate_up_proj, and down_proj tensors', 'run the MoE router to compute routing weights and select top-k experts for each token']
```

Usage

```
{'create_Qwen3MoeGroupedGEMMBlock': 'create a Qwen3MoeGroupedGEMMBlock from a HuggingFace Qwen3MoeSparseMoeBlock using from_hf', 'create_Qwen3MoeFusedGroupedGEMMBlock': 'create a fused Qwen3MoeFusedGroupedGEMMBlock with triton kernels and optional autotuning', 'run_Qwen3Moe_forward': 'run the Qwen3MoeGroupedGEMMBlock forward pass on hidden states and return expert routing results', 'extract_HF_weights': 'extract and stack HuggingFace MoE expert weights into gate, gate_up_proj, and down_proj tensors', 'run_router': 'run the MoE router to compute routing weights and select top-k experts for each token'}
```

