# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/lora/ops/torch_ops/lora_ops.py

Prompts

```
['build a function to expand LoRA B weights using sequence group matrix vector multiplication with repeat-interleaved indices', 'build a function to expand LoRA B weights via batched GEMV with einsum and optional input addition', 'build a function to shrink LoRA A weights using sequence group matrix vector multiplication with scaling', 'build a function to shrink LoRA A weights via batched GEMV with per-token scaling', 'build a function to expand a slice of LoRA B weights into an output tensor with configurable offset and size']
```

Usage

```
{'build_sgmv_expand': 'build a function to expand LoRA B weights using sequence group matrix vector multiplication with repeat-interleaved indices', 'build_bgmv_expand': 'build a function to expand LoRA B weights via batched GEMV with einsum and optional input addition', 'build_sgmv_shrink': 'build a function to shrink LoRA A weights using sequence group matrix vector multiplication with scaling', 'build_bgmv_shrink': 'build a function to shrink LoRA A weights via batched GEMV with per-token scaling', 'build_sgmv_expand_slice': 'build a function to expand a slice of LoRA B weights into an output tensor with configurable offset and size'}
```

