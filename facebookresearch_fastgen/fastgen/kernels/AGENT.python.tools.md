# Agent Python Tools

- repo: facebookresearch/fastgen
- repo_uri: https://github.com/facebookresearch/fastgen

## File: facebookresearch_fastgen/fastgen/kernels/paged_memcpy.py

Prompts

```
['build a paged KV cache by copying tensors using paged_memcpy with a page table mapping', 'create a Triton JIT kernel that copies memory from source to paged destination using page table indirection', 'test the paged_memcpy function by copying source tensors to a paged destination with a page table', 'refactor the paged_memcpy_kernel to support different block sizes or element dimensions for memory copying', 'review the paged_memcpy input validation logic that checks tensor shapes, dtypes, and contiguity', 'run the rmsnorm function to compute root mean square normalization on a 2D PyTorch tensor', 'build a Triton JIT kernel that computes RMS normalization with configurable block size and warp count', 'test the rmsnorm function to verify it raises ValueError for non-contiguous or non-2D input tensors', 'review the rmsnorm_kernel Triton kernel and its evict_last and evict_first memory eviction policies', 'refactor the rmsnorm function to customize the BLOCK_SIZE calculation logic for different tensor dimensions', 'apply RoPE in place to a 3D tensor using position and frequency tensors', 'apply RoPE with approximate trigonometric functions for faster computation on bounded inputs', 'build a Triton JIT kernel that applies rotary positional embeddings to transformer head tensors', 'review the rope_kernel constexpr arguments HEAD_DIM, HEAD_GROUP_SIZE, and HEADS_PER_BLOCK for tuning', 'test the apply_rope function input validation for tensor shape and contiguity requirements']
```

Usage

```
{'build_paged_kv_cache': 'build a paged KV cache by copying tensors using paged_memcpy with a page table mapping', 'create_paged_memcpy_kernel': 'create a Triton JIT kernel that copies memory from source to paged destination using page table indirection', 'test_paged_memcpy': 'test the paged_memcpy function by copying source tensors to a paged destination with a page table', 'refactor_paged_memcpy_kernel': 'refactor the paged_memcpy_kernel to support different block sizes or element dimensions for memory copying', 'review_paged_memcpy_validation': 'review the paged_memcpy input validation logic that checks tensor shapes, dtypes, and contiguity'}
```

## File: facebookresearch_fastgen/fastgen/kernels/rmsnorm.py

Prompts

```
['build a paged KV cache by copying tensors using paged_memcpy with a page table mapping', 'create a Triton JIT kernel that copies memory from source to paged destination using page table indirection', 'test the paged_memcpy function by copying source tensors to a paged destination with a page table', 'refactor the paged_memcpy_kernel to support different block sizes or element dimensions for memory copying', 'review the paged_memcpy input validation logic that checks tensor shapes, dtypes, and contiguity', 'run the rmsnorm function to compute root mean square normalization on a 2D PyTorch tensor', 'build a Triton JIT kernel that computes RMS normalization with configurable block size and warp count', 'test the rmsnorm function to verify it raises ValueError for non-contiguous or non-2D input tensors', 'review the rmsnorm_kernel Triton kernel and its evict_last and evict_first memory eviction policies', 'refactor the rmsnorm function to customize the BLOCK_SIZE calculation logic for different tensor dimensions', 'apply RoPE in place to a 3D tensor using position and frequency tensors', 'apply RoPE with approximate trigonometric functions for faster computation on bounded inputs', 'build a Triton JIT kernel that applies rotary positional embeddings to transformer head tensors', 'review the rope_kernel constexpr arguments HEAD_DIM, HEAD_GROUP_SIZE, and HEADS_PER_BLOCK for tuning', 'test the apply_rope function input validation for tensor shape and contiguity requirements']
```

Usage

```
{'run_rmsnorm': 'run the rmsnorm function to compute root mean square normalization on a 2D PyTorch tensor', 'build_rmsnorm_kernel': 'build a Triton JIT kernel that computes RMS normalization with configurable block size and warp count', 'test_rmsnorm_tensor_validation': 'test the rmsnorm function to verify it raises ValueError for non-contiguous or non-2D input tensors', 'review_rmsnorm_kernel_eviction_policy': 'review the rmsnorm_kernel Triton kernel and its evict_last and evict_first memory eviction policies', 'refactor_rmsnorm_block_size': 'refactor the rmsnorm function to customize the BLOCK_SIZE calculation logic for different tensor dimensions'}
```

## File: facebookresearch_fastgen/fastgen/kernels/rope.py

Prompts

```
['build a paged KV cache by copying tensors using paged_memcpy with a page table mapping', 'create a Triton JIT kernel that copies memory from source to paged destination using page table indirection', 'test the paged_memcpy function by copying source tensors to a paged destination with a page table', 'refactor the paged_memcpy_kernel to support different block sizes or element dimensions for memory copying', 'review the paged_memcpy input validation logic that checks tensor shapes, dtypes, and contiguity', 'run the rmsnorm function to compute root mean square normalization on a 2D PyTorch tensor', 'build a Triton JIT kernel that computes RMS normalization with configurable block size and warp count', 'test the rmsnorm function to verify it raises ValueError for non-contiguous or non-2D input tensors', 'review the rmsnorm_kernel Triton kernel and its evict_last and evict_first memory eviction policies', 'refactor the rmsnorm function to customize the BLOCK_SIZE calculation logic for different tensor dimensions', 'apply RoPE in place to a 3D tensor using position and frequency tensors', 'apply RoPE with approximate trigonometric functions for faster computation on bounded inputs', 'build a Triton JIT kernel that applies rotary positional embeddings to transformer head tensors', 'review the rope_kernel constexpr arguments HEAD_DIM, HEAD_GROUP_SIZE, and HEADS_PER_BLOCK for tuning', 'test the apply_rope function input validation for tensor shape and contiguity requirements']
```

Usage

```
{'apply_rope_in_place': 'apply RoPE in place to a 3D tensor using position and frequency tensors', 'apply_rope_with_approx_trigo': 'apply RoPE with approximate trigonometric functions for faster computation on bounded inputs', 'build_rope_kernel': 'build a Triton JIT kernel that applies rotary positional embeddings to transformer head tensors', 'review_rope_kernel_constants': 'review the rope_kernel constexpr arguments HEAD_DIM, HEAD_GROUP_SIZE, and HEADS_PER_BLOCK for tuning', 'test_apply_rope_validation': 'test the apply_rope function input validation for tensor shape and contiguity requirements'}
```

