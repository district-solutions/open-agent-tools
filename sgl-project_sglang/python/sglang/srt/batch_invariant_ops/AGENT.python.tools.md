# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/batch_invariant_ops/batch_invariant_ops.py

Prompts

```
['enable batch invariant mode to replace PyTorch matmul and bmm with deterministic Triton implementations', 'disable batch invariant mode and restore original PyTorch operations', 'set batch invariant mode as a context manager for scoped deterministic computation', 'run persistent matrix multiplication on CUDA tensors with optional bias using Triton or DeepGEMM', 'run batched matrix multiplication on 3D CUDA tensors with deterministic persistent kernel']
```

Usage

```
{'enable_batch_invariant_mode': 'enable batch invariant mode to replace PyTorch matmul and bmm with deterministic Triton implementations', 'disable_batch_invariant_mode': 'disable batch invariant mode and restore original PyTorch operations', 'set_batch_invariant_mode': 'set batch invariant mode as a context manager for scoped deterministic computation', 'matmul_persistent': 'run persistent matrix multiplication on CUDA tensors with optional bias using Triton or DeepGEMM', 'bmm_batch_invariant': 'run batched matrix multiplication on 3D CUDA tensors with deterministic persistent kernel'}
```

