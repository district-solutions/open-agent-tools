# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/jit_kernel/triton/gdn_fused_proj.py

Prompts

```
['build a triton kernel that splits interleaved qkvz weight tensors into separate q, k, v, z outputs for Qwen3-Next checkpoints', 'run a triton kernel that splits contiguous qkvz weight tensors into separate q, k, v, z outputs for Qwen3.5 checkpoints', 'test the fused_qkvzba_split_reshape_cat function with interleaved input format and verify output tensor shapes', 'refactor the fused_qkvzba_split_reshape_cat function to support different batch and sequence lengths', 'review the fused_qkvzba_split_reshape_cat_contiguous function and its contiguous input layout handling']
```

Usage

```
{'build_fused_qkvzba_split_reshape_cat': 'build a triton kernel that splits interleaved qkvz weight tensors into separate q, k, v, z outputs for Qwen3-Next checkpoints', 'run_fused_qkvzba_split_reshape_cat_contiguous': 'run a triton kernel that splits contiguous qkvz weight tensors into separate q, k, v, z outputs for Qwen3.5 checkpoints', 'test_fused_qkvzba_split_reshape_cat': 'test the fused_qkvzba_split_reshape_cat function with interleaved input format and verify output tensor shapes', 'refactor_fused_qkvzba_split_reshape_cat': 'refactor the fused_qkvzba_split_reshape_cat function to support different batch and sequence lengths', 'review_fused_qkvzba_split_reshape_cat_contiguous': 'review the fused_qkvzba_split_reshape_cat_contiguous function and its contiguous input layout handling'}
```

