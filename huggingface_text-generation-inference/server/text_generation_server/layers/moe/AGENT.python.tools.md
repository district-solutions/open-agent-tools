# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/server/text_generation_server/layers/moe/fp8.py

Prompts

```
['build an FP8 quantized sparse MoE layer with configurable expert count, topk routing, and grouped expert selection', 'run the FP8SparseMoELayer forward pass with input tensor and gating output to get MoE results', 'create a function to load FP8 expert weights across all experts with per-expert quantization scales', 'refactor the column-wise multi-weight loading for gate and up projections across all MoE experts', 'review the row-wise expert weight loading function that fetches down projection weights per expert', 'build a python module that runs grouped_topk to select top-k experts using group-aware gating scores', 'build a python module that runs fused_topk to select top-k experts from softmax gating output', 'test the grouped_topk function with torch tensors for expert group masking and top-k selection', 'test the fused_topk function with torch tensors for softmax gating and top-k expert selection', 'refactor the grouped_topk function to support a different expert grouping strategy or masking logic', 'build a GPTQMarlinSparseMoELayer with n_experts, topk, and weights for quantized MoE inference', 'run the fused_marlin_moe function with hidden_states, w1, w2 weights and gating_output for MoE forward pass', 'check if marlin MoE GEMM is available given quant_method, quantize, and sym parameters', 'create a GPTQMarlinMoEWeight dataclass with qweight, qzeros, scales, g_idx, perm, and is_full_k tensors', 'review the _pack_weight function that packs individual expert GPTQMarlinWeight into a shared MoE weight tensor', 'build a Mixture of Experts layer with configurable top-k gating and expert routing for an LLM model', 'run a fused MoE forward pass using w1 and w2 weights with top-k expert selection and gating', 'create a function to load and stack gate and up projection weights for all experts into a single tensor', 'create a function to load and stack down projection weights for all experts into a single tensor', 'review the UnquantizedSparseMoELayer forward method to understand platform-specific MoE kernel dispatch for CUDA, ROCm, and IPEX']
```

Usage

```
{'build_FP8SparseMoELayer': 'build an FP8 quantized sparse MoE layer with configurable expert count, topk routing, and grouped expert selection', 'run_FP8SparseMoELayer_forward': 'run the FP8SparseMoELayer forward pass with input tensor and gating output to get MoE results', 'create_load_expert_weights': 'create a function to load FP8 expert weights across all experts with per-expert quantization scales', 'refactor_load_expert_multi_weights_col': 'refactor the column-wise multi-weight loading for gate and up projections across all MoE experts', 'review_load_expert_weights_row': 'review the row-wise expert weight loading function that fetches down projection weights per expert'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/layers/moe/fused_moe_ipex.py

Prompts

```
['build an FP8 quantized sparse MoE layer with configurable expert count, topk routing, and grouped expert selection', 'run the FP8SparseMoELayer forward pass with input tensor and gating output to get MoE results', 'create a function to load FP8 expert weights across all experts with per-expert quantization scales', 'refactor the column-wise multi-weight loading for gate and up projections across all MoE experts', 'review the row-wise expert weight loading function that fetches down projection weights per expert', 'build a python module that runs grouped_topk to select top-k experts using group-aware gating scores', 'build a python module that runs fused_topk to select top-k experts from softmax gating output', 'test the grouped_topk function with torch tensors for expert group masking and top-k selection', 'test the fused_topk function with torch tensors for softmax gating and top-k expert selection', 'refactor the grouped_topk function to support a different expert grouping strategy or masking logic', 'build a GPTQMarlinSparseMoELayer with n_experts, topk, and weights for quantized MoE inference', 'run the fused_marlin_moe function with hidden_states, w1, w2 weights and gating_output for MoE forward pass', 'check if marlin MoE GEMM is available given quant_method, quantize, and sym parameters', 'create a GPTQMarlinMoEWeight dataclass with qweight, qzeros, scales, g_idx, perm, and is_full_k tensors', 'review the _pack_weight function that packs individual expert GPTQMarlinWeight into a shared MoE weight tensor', 'build a Mixture of Experts layer with configurable top-k gating and expert routing for an LLM model', 'run a fused MoE forward pass using w1 and w2 weights with top-k expert selection and gating', 'create a function to load and stack gate and up projection weights for all experts into a single tensor', 'create a function to load and stack down projection weights for all experts into a single tensor', 'review the UnquantizedSparseMoELayer forward method to understand platform-specific MoE kernel dispatch for CUDA, ROCm, and IPEX']
```

Usage

```
{'build_grouped_topk': 'build a python module that runs grouped_topk to select top-k experts using group-aware gating scores', 'build_fused_topk': 'build a python module that runs fused_topk to select top-k experts from softmax gating output', 'test_grouped_topk': 'test the grouped_topk function with torch tensors for expert group masking and top-k selection', 'test_fused_topk': 'test the fused_topk function with torch tensors for softmax gating and top-k expert selection', 'refactor_grouped_topk': 'refactor the grouped_topk function to support a different expert grouping strategy or masking logic'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/layers/moe/gptq_marlin.py

Prompts

```
['build an FP8 quantized sparse MoE layer with configurable expert count, topk routing, and grouped expert selection', 'run the FP8SparseMoELayer forward pass with input tensor and gating output to get MoE results', 'create a function to load FP8 expert weights across all experts with per-expert quantization scales', 'refactor the column-wise multi-weight loading for gate and up projections across all MoE experts', 'review the row-wise expert weight loading function that fetches down projection weights per expert', 'build a python module that runs grouped_topk to select top-k experts using group-aware gating scores', 'build a python module that runs fused_topk to select top-k experts from softmax gating output', 'test the grouped_topk function with torch tensors for expert group masking and top-k selection', 'test the fused_topk function with torch tensors for softmax gating and top-k expert selection', 'refactor the grouped_topk function to support a different expert grouping strategy or masking logic', 'build a GPTQMarlinSparseMoELayer with n_experts, topk, and weights for quantized MoE inference', 'run the fused_marlin_moe function with hidden_states, w1, w2 weights and gating_output for MoE forward pass', 'check if marlin MoE GEMM is available given quant_method, quantize, and sym parameters', 'create a GPTQMarlinMoEWeight dataclass with qweight, qzeros, scales, g_idx, perm, and is_full_k tensors', 'review the _pack_weight function that packs individual expert GPTQMarlinWeight into a shared MoE weight tensor', 'build a Mixture of Experts layer with configurable top-k gating and expert routing for an LLM model', 'run a fused MoE forward pass using w1 and w2 weights with top-k expert selection and gating', 'create a function to load and stack gate and up projection weights for all experts into a single tensor', 'create a function to load and stack down projection weights for all experts into a single tensor', 'review the UnquantizedSparseMoELayer forward method to understand platform-specific MoE kernel dispatch for CUDA, ROCm, and IPEX']
```

Usage

```
{'build_GPTQMarlinSparseMoELayer': 'build a GPTQMarlinSparseMoELayer with n_experts, topk, and weights for quantized MoE inference', 'run_fused_marlin_moe': 'run the fused_marlin_moe function with hidden_states, w1, w2 weights and gating_output for MoE forward pass', 'check_can_use_marlin_moe_gemm': 'check if marlin MoE GEMM is available given quant_method, quantize, and sym parameters', 'create_GPTQMarlinMoEWeight': 'create a GPTQMarlinMoEWeight dataclass with qweight, qzeros, scales, g_idx, perm, and is_full_k tensors', 'review_pack_weight': 'review the _pack_weight function that packs individual expert GPTQMarlinWeight into a shared MoE weight tensor'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/layers/moe/unquantized.py

Prompts

```
['build an FP8 quantized sparse MoE layer with configurable expert count, topk routing, and grouped expert selection', 'run the FP8SparseMoELayer forward pass with input tensor and gating output to get MoE results', 'create a function to load FP8 expert weights across all experts with per-expert quantization scales', 'refactor the column-wise multi-weight loading for gate and up projections across all MoE experts', 'review the row-wise expert weight loading function that fetches down projection weights per expert', 'build a python module that runs grouped_topk to select top-k experts using group-aware gating scores', 'build a python module that runs fused_topk to select top-k experts from softmax gating output', 'test the grouped_topk function with torch tensors for expert group masking and top-k selection', 'test the fused_topk function with torch tensors for softmax gating and top-k expert selection', 'refactor the grouped_topk function to support a different expert grouping strategy or masking logic', 'build a GPTQMarlinSparseMoELayer with n_experts, topk, and weights for quantized MoE inference', 'run the fused_marlin_moe function with hidden_states, w1, w2 weights and gating_output for MoE forward pass', 'check if marlin MoE GEMM is available given quant_method, quantize, and sym parameters', 'create a GPTQMarlinMoEWeight dataclass with qweight, qzeros, scales, g_idx, perm, and is_full_k tensors', 'review the _pack_weight function that packs individual expert GPTQMarlinWeight into a shared MoE weight tensor', 'build a Mixture of Experts layer with configurable top-k gating and expert routing for an LLM model', 'run a fused MoE forward pass using w1 and w2 weights with top-k expert selection and gating', 'create a function to load and stack gate and up projection weights for all experts into a single tensor', 'create a function to load and stack down projection weights for all experts into a single tensor', 'review the UnquantizedSparseMoELayer forward method to understand platform-specific MoE kernel dispatch for CUDA, ROCm, and IPEX']
```

Usage

```
{'build_UnquantizedSparseMoELayer': 'build a Mixture of Experts layer with configurable top-k gating and expert routing for an LLM model', 'run_fused_moe': 'run a fused MoE forward pass using w1 and w2 weights with top-k expert selection and gating', 'create_load_expert_multi_weights_col': 'create a function to load and stack gate and up projection weights for all experts into a single tensor', 'create_load_expert_weights_row': 'create a function to load and stack down projection weights for all experts into a single tensor', 'review_UnquantizedSparseMoELayer_forward': 'review the UnquantizedSparseMoELayer forward method to understand platform-specific MoE kernel dispatch for CUDA, ROCm, and IPEX'}
```

