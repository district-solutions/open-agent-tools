# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/constrained/triton_ops/bitmask_ops.py

Prompts

```
['apply a bitmask to logits tensor in-place using Triton, setting masked tokens to negative infinity', 'run the Triton JIT kernel that applies bitwise compressed bitmask to logits on GPU', 'apply token bitmask to specific rows of logits using an indices tensor for selective masking', 'apply token bitmask across a batch of logits tensors with matching batch dimensions', 'validate that bitmask width fits within the required int32 capacity for a given vocabulary size']
```

Usage

```
{'apply_token_bitmask_inplace_triton': 'apply a bitmask to logits tensor in-place using Triton, setting masked tokens to negative infinity', 'apply_token_bitmask_inplace_kernel': 'run the Triton JIT kernel that applies bitwise compressed bitmask to logits on GPU', 'apply_token_bitmask_with_indices': 'apply token bitmask to specific rows of logits using an indices tensor for selective masking', 'apply_token_bitmask_batch': 'apply token bitmask across a batch of logits tensors with matching batch dimensions', 'validate_bitmask_width': 'validate that bitmask width fits within the required int32 capacity for a given vocabulary size'}
```

