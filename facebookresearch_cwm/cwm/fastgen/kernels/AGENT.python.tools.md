# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/fastgen/kernels/paged_memcpy.py

Prompts

```
['run paged_memcpy to copy source tensor elements into a paged destination tensor using a page table', 'run paged_memcpy with dst_shard tuple to copy only elements matching a specific shard index modulo shard count', 'run paged_memcpy with src_batch tensor to map each source element to a specific row of the page table', 'run paged_memcpy with batch_size scalar tensor to limit processing to the first N elements for CUDA graph compatibility', 'review the paged_memcpy_kernel Triton JIT kernel that performs element-wise memory copy with page table indirection and sharding support', 'run the rmsnorm function to compute root mean square normalization on a 2D PyTorch tensor', 'run the Triton JIT rmsnorm_kernel to normalize tensor data on GPU with configurable block size', 'test the rmsnorm function with a 2D contiguous tensor and weight vector to verify normalization output', 'review the rmsnorm_kernel Triton JIT function for eviction policy and block-based RMS normalization logic', 'refactor the rmsnorm function to support non-contiguous input tensors or additional normalization options', 'apply RoPE in place to a 3D tensor using position and frequency tensors', 'apply RoPE with approximate trigonometric functions for faster sin and cos computation', 'run the Triton JIT rope_kernel to apply rotary positional embeddings on GPU tensors', 'review the rope_kernel Triton JIT function for RoPE computation with configurable head group size', 'refactor apply_rope to support additional tensor shapes or frequency scaling schemes']
```

Usage

```
{'run_paged_memcpy_copy': 'run paged_memcpy to copy source tensor elements into a paged destination tensor using a page table', 'run_paged_memcpy_with_sharding': 'run paged_memcpy with dst_shard tuple to copy only elements matching a specific shard index modulo shard count', 'run_paged_memcpy_with_batch': 'run paged_memcpy with src_batch tensor to map each source element to a specific row of the page table', 'run_paged_memcpy_with_batch_size': 'run paged_memcpy with batch_size scalar tensor to limit processing to the first N elements for CUDA graph compatibility', 'review_paged_memcpy_kernel': 'review the paged_memcpy_kernel Triton JIT kernel that performs element-wise memory copy with page table indirection and sharding support'}
```

## File: facebookresearch_cwm/cwm/fastgen/kernels/rmsnorm.py

Prompts

```
['run paged_memcpy to copy source tensor elements into a paged destination tensor using a page table', 'run paged_memcpy with dst_shard tuple to copy only elements matching a specific shard index modulo shard count', 'run paged_memcpy with src_batch tensor to map each source element to a specific row of the page table', 'run paged_memcpy with batch_size scalar tensor to limit processing to the first N elements for CUDA graph compatibility', 'review the paged_memcpy_kernel Triton JIT kernel that performs element-wise memory copy with page table indirection and sharding support', 'run the rmsnorm function to compute root mean square normalization on a 2D PyTorch tensor', 'run the Triton JIT rmsnorm_kernel to normalize tensor data on GPU with configurable block size', 'test the rmsnorm function with a 2D contiguous tensor and weight vector to verify normalization output', 'review the rmsnorm_kernel Triton JIT function for eviction policy and block-based RMS normalization logic', 'refactor the rmsnorm function to support non-contiguous input tensors or additional normalization options', 'apply RoPE in place to a 3D tensor using position and frequency tensors', 'apply RoPE with approximate trigonometric functions for faster sin and cos computation', 'run the Triton JIT rope_kernel to apply rotary positional embeddings on GPU tensors', 'review the rope_kernel Triton JIT function for RoPE computation with configurable head group size', 'refactor apply_rope to support additional tensor shapes or frequency scaling schemes']
```

Usage

```
{'run_rmsnorm': 'run the rmsnorm function to compute root mean square normalization on a 2D PyTorch tensor', 'run_rmsnorm_kernel': 'run the Triton JIT rmsnorm_kernel to normalize tensor data on GPU with configurable block size', 'test_rmsnorm': 'test the rmsnorm function with a 2D contiguous tensor and weight vector to verify normalization output', 'review_rmsnorm_kernel': 'review the rmsnorm_kernel Triton JIT function for eviction policy and block-based RMS normalization logic', 'refactor_rmsnorm': 'refactor the rmsnorm function to support non-contiguous input tensors or additional normalization options'}
```

## File: facebookresearch_cwm/cwm/fastgen/kernels/rope.py

Prompts

```
['run paged_memcpy to copy source tensor elements into a paged destination tensor using a page table', 'run paged_memcpy with dst_shard tuple to copy only elements matching a specific shard index modulo shard count', 'run paged_memcpy with src_batch tensor to map each source element to a specific row of the page table', 'run paged_memcpy with batch_size scalar tensor to limit processing to the first N elements for CUDA graph compatibility', 'review the paged_memcpy_kernel Triton JIT kernel that performs element-wise memory copy with page table indirection and sharding support', 'run the rmsnorm function to compute root mean square normalization on a 2D PyTorch tensor', 'run the Triton JIT rmsnorm_kernel to normalize tensor data on GPU with configurable block size', 'test the rmsnorm function with a 2D contiguous tensor and weight vector to verify normalization output', 'review the rmsnorm_kernel Triton JIT function for eviction policy and block-based RMS normalization logic', 'refactor the rmsnorm function to support non-contiguous input tensors or additional normalization options', 'apply RoPE in place to a 3D tensor using position and frequency tensors', 'apply RoPE with approximate trigonometric functions for faster sin and cos computation', 'run the Triton JIT rope_kernel to apply rotary positional embeddings on GPU tensors', 'review the rope_kernel Triton JIT function for RoPE computation with configurable head group size', 'refactor apply_rope to support additional tensor shapes or frequency scaling schemes']
```

Usage

```
{'apply_rope_inplace': 'apply RoPE in place to a 3D tensor using position and frequency tensors', 'apply_rope_approx_trigo': 'apply RoPE with approximate trigonometric functions for faster sin and cos computation', 'run_rope_kernel': 'run the Triton JIT rope_kernel to apply rotary positional embeddings on GPU tensors', 'review_rope_kernel': 'review the rope_kernel Triton JIT function for RoPE computation with configurable head group size', 'refactor_apply_rope': 'refactor apply_rope to support additional tensor shapes or frequency scaling schemes'}
```

