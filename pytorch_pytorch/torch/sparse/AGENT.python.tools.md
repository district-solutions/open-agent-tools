# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/sparse/_semi_structured_conversions.py

Prompts

```
['create a dense matrix into sparse semi-structured representation using CUTLASS layout and metadata', 'reconstruct a dense matrix from sparse semi-structured compressed matrix and metadata', 'calculate scatter offsets for reordering metadata matrix elements into CUTLASS interleaved column major layout', 'test the sparse_semi_structured_from_dense_cutlass function with half and bfloat16 matrices', 'test the sparse_semi_structured_to_dense_cutlass function reconstructs dense matrix from sparse representation', 'run sparse BSR matrix multiplication with a dense tensor using Triton GPU kernels', 'create sampled addmm operation on BSR sparse tensors with alpha and beta scaling factors', 'run softmax normalization on BSR sparse tensor values row-wise using Triton kernels', 'run scattered matrix multiplication for BSR sparse blocks against dense tensors', 'test BSR dense addmm operation with configurable alpha, beta, and sparsity metadata', 'run triton kernel parameter tuning for bsr_dense_addmm operation with given input tensors', 'test retrieving pre-computed triton kernel meta parameters for scatter_mm or bsr_dense_addmm operations', 'run triton kernel parameter tuning for scatter_mm operation with given matrix shapes and block sizes', 'run automated optimization of bsr_dense_addmm kernel parameters across shape configurations', 'run full grid search optimization of triton kernel parameters for all shape and blocksize configurations', 'create a SparseSemiStructuredTensor from a 2D CUDA tensor with supported dtype (int8, float16, bfloat16, or float32)', 'build a conversion from a dense 2D CUDA tensor to a SparseSemiStructuredTensor using to_sparse_semi_structured function', 'test the mm matrix multiplication dispatch on SparseSemiStructuredTensor with CUTLASS or cuSPARSELt backend', 'refactor a SparseSemiStructuredTensor to its original dense form using the to_dense method with CUTLASS backend', 'review the values and indices extraction methods for SparseSemiStructuredTensor via torch.ops.aten.values.default and torch.ops.aten.indices.default']
```

Usage

```
{'create_sparse_semi_structured_from_dense_cutlass': 'create a dense matrix into sparse semi-structured representation using CUTLASS layout and metadata', 'build_sparse_semi_structured_to_dense_cutlass': 'reconstruct a dense matrix from sparse semi-structured compressed matrix and metadata', 'calculate_meta_reordering_scatter_offsets': 'calculate scatter offsets for reordering metadata matrix elements into CUTLASS interleaved column major layout', 'test_sparse_semi_structured_from_dense_cutlass': 'test the sparse_semi_structured_from_dense_cutlass function with half and bfloat16 matrices', 'test_sparse_semi_structured_to_dense_cutlass': 'test the sparse_semi_structured_to_dense_cutlass function reconstructs dense matrix from sparse representation'}
```

## File: pytorch_pytorch/torch/sparse/_triton_ops.py

Prompts

```
['create a dense matrix into sparse semi-structured representation using CUTLASS layout and metadata', 'reconstruct a dense matrix from sparse semi-structured compressed matrix and metadata', 'calculate scatter offsets for reordering metadata matrix elements into CUTLASS interleaved column major layout', 'test the sparse_semi_structured_from_dense_cutlass function with half and bfloat16 matrices', 'test the sparse_semi_structured_to_dense_cutlass function reconstructs dense matrix from sparse representation', 'run sparse BSR matrix multiplication with a dense tensor using Triton GPU kernels', 'create sampled addmm operation on BSR sparse tensors with alpha and beta scaling factors', 'run softmax normalization on BSR sparse tensor values row-wise using Triton kernels', 'run scattered matrix multiplication for BSR sparse blocks against dense tensors', 'test BSR dense addmm operation with configurable alpha, beta, and sparsity metadata', 'run triton kernel parameter tuning for bsr_dense_addmm operation with given input tensors', 'test retrieving pre-computed triton kernel meta parameters for scatter_mm or bsr_dense_addmm operations', 'run triton kernel parameter tuning for scatter_mm operation with given matrix shapes and block sizes', 'run automated optimization of bsr_dense_addmm kernel parameters across shape configurations', 'run full grid search optimization of triton kernel parameters for all shape and blocksize configurations', 'create a SparseSemiStructuredTensor from a 2D CUDA tensor with supported dtype (int8, float16, bfloat16, or float32)', 'build a conversion from a dense 2D CUDA tensor to a SparseSemiStructuredTensor using to_sparse_semi_structured function', 'test the mm matrix multiplication dispatch on SparseSemiStructuredTensor with CUTLASS or cuSPARSELt backend', 'refactor a SparseSemiStructuredTensor to its original dense form using the to_dense method with CUTLASS backend', 'review the values and indices extraction methods for SparseSemiStructuredTensor via torch.ops.aten.values.default and torch.ops.aten.indices.default']
```

Usage

```
{'run_bsr_dense_mm': 'run sparse BSR matrix multiplication with a dense tensor using Triton GPU kernels', 'create_sampled_addmm': 'create sampled addmm operation on BSR sparse tensors with alpha and beta scaling factors', 'run_bsr_softmax': 'run softmax normalization on BSR sparse tensor values row-wise using Triton kernels', 'run_bsr_scatter_mm': 'run scattered matrix multiplication for BSR sparse blocks against dense tensors', 'test_bsr_dense_addmm': 'test BSR dense addmm operation with configurable alpha, beta, and sparsity metadata'}
```

## File: pytorch_pytorch/torch/sparse/_triton_ops_meta.py

Prompts

```
['create a dense matrix into sparse semi-structured representation using CUTLASS layout and metadata', 'reconstruct a dense matrix from sparse semi-structured compressed matrix and metadata', 'calculate scatter offsets for reordering metadata matrix elements into CUTLASS interleaved column major layout', 'test the sparse_semi_structured_from_dense_cutlass function with half and bfloat16 matrices', 'test the sparse_semi_structured_to_dense_cutlass function reconstructs dense matrix from sparse representation', 'run sparse BSR matrix multiplication with a dense tensor using Triton GPU kernels', 'create sampled addmm operation on BSR sparse tensors with alpha and beta scaling factors', 'run softmax normalization on BSR sparse tensor values row-wise using Triton kernels', 'run scattered matrix multiplication for BSR sparse blocks against dense tensors', 'test BSR dense addmm operation with configurable alpha, beta, and sparsity metadata', 'run triton kernel parameter tuning for bsr_dense_addmm operation with given input tensors', 'test retrieving pre-computed triton kernel meta parameters for scatter_mm or bsr_dense_addmm operations', 'run triton kernel parameter tuning for scatter_mm operation with given matrix shapes and block sizes', 'run automated optimization of bsr_dense_addmm kernel parameters across shape configurations', 'run full grid search optimization of triton kernel parameters for all shape and blocksize configurations', 'create a SparseSemiStructuredTensor from a 2D CUDA tensor with supported dtype (int8, float16, bfloat16, or float32)', 'build a conversion from a dense 2D CUDA tensor to a SparseSemiStructuredTensor using to_sparse_semi_structured function', 'test the mm matrix multiplication dispatch on SparseSemiStructuredTensor with CUTLASS or cuSPARSELt backend', 'refactor a SparseSemiStructuredTensor to its original dense form using the to_dense method with CUTLASS backend', 'review the values and indices extraction methods for SparseSemiStructuredTensor via torch.ops.aten.values.default and torch.ops.aten.indices.default']
```

Usage

```
{'run_tune_bsr_dense_addmm': 'run triton kernel parameter tuning for bsr_dense_addmm operation with given input tensors', 'test_get_meta': 'test retrieving pre-computed triton kernel meta parameters for scatter_mm or bsr_dense_addmm operations', 'run_tune_scatter_mm': 'run triton kernel parameter tuning for scatter_mm operation with given matrix shapes and block sizes', 'run_optimize_bsr_dense_addmm': 'run automated optimization of bsr_dense_addmm kernel parameters across shape configurations', 'run_main_tuning': 'run full grid search optimization of triton kernel parameters for all shape and blocksize configurations'}
```

## File: pytorch_pytorch/torch/sparse/semi_structured.py

Prompts

```
['create a dense matrix into sparse semi-structured representation using CUTLASS layout and metadata', 'reconstruct a dense matrix from sparse semi-structured compressed matrix and metadata', 'calculate scatter offsets for reordering metadata matrix elements into CUTLASS interleaved column major layout', 'test the sparse_semi_structured_from_dense_cutlass function with half and bfloat16 matrices', 'test the sparse_semi_structured_to_dense_cutlass function reconstructs dense matrix from sparse representation', 'run sparse BSR matrix multiplication with a dense tensor using Triton GPU kernels', 'create sampled addmm operation on BSR sparse tensors with alpha and beta scaling factors', 'run softmax normalization on BSR sparse tensor values row-wise using Triton kernels', 'run scattered matrix multiplication for BSR sparse blocks against dense tensors', 'test BSR dense addmm operation with configurable alpha, beta, and sparsity metadata', 'run triton kernel parameter tuning for bsr_dense_addmm operation with given input tensors', 'test retrieving pre-computed triton kernel meta parameters for scatter_mm or bsr_dense_addmm operations', 'run triton kernel parameter tuning for scatter_mm operation with given matrix shapes and block sizes', 'run automated optimization of bsr_dense_addmm kernel parameters across shape configurations', 'run full grid search optimization of triton kernel parameters for all shape and blocksize configurations', 'create a SparseSemiStructuredTensor from a 2D CUDA tensor with supported dtype (int8, float16, bfloat16, or float32)', 'build a conversion from a dense 2D CUDA tensor to a SparseSemiStructuredTensor using to_sparse_semi_structured function', 'test the mm matrix multiplication dispatch on SparseSemiStructuredTensor with CUTLASS or cuSPARSELt backend', 'refactor a SparseSemiStructuredTensor to its original dense form using the to_dense method with CUTLASS backend', 'review the values and indices extraction methods for SparseSemiStructuredTensor via torch.ops.aten.values.default and torch.ops.aten.indices.default']
```

Usage

```
{'create_SparseSemiStructuredTensor': 'create a SparseSemiStructuredTensor from a 2D CUDA tensor with supported dtype (int8, float16, bfloat16, or float32)', 'build_to_sparse_semi_structured': 'build a conversion from a dense 2D CUDA tensor to a SparseSemiStructuredTensor using to_sparse_semi_structured function', 'test_mm_dispatch': 'test the mm matrix multiplication dispatch on SparseSemiStructuredTensor with CUTLASS or cuSPARSELt backend', 'refactor_to_dense': 'refactor a SparseSemiStructuredTensor to its original dense form using the to_dense method with CUTLASS backend', 'review_values_indices': 'review the values and indices extraction methods for SparseSemiStructuredTensor via torch.ops.aten.values.default and torch.ops.aten.indices.default'}
```

