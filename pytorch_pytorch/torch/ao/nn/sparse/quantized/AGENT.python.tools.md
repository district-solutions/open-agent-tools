# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/nn/sparse/quantized/linear.py

Prompts

```
['create a LinearPackedParams object with specified row and column block sizes for sparse quantized linear prepacking', 'build a SparseQuantizedLinear module with in/out features and block sizes for quantized sparse matrix multiplication', 'convert a float torch.nn.Linear module with qconfig and sparse_params into a SparseQuantizedLinear module', 'set quantized weight and bias tensors with row and column block sizes on a LinearPackedParams or Linear module', 'unpack prepacked sparse quantized linear parameters back into weight, bias, and block size tensors', 'test the _is_valid_linear_block_sparse_pattern function with row and column block size arguments', 'create a LinearBlockSparsePattern context manager with custom row_block_size and col_block_size values', 'test the LinearBlockSparsePattern class as a context manager that sets and restores global sparsity pattern', 'refactor the LinearBlockSparsePattern class to use a thread-safe context manager for block sparse pattern', 'summarize the LinearBlockSparsePattern.block_size static method that returns current row and column block sizes']
```

Usage

```
{'create_LinearPackedParams': 'create a LinearPackedParams object with specified row and column block sizes for sparse quantized linear prepacking', 'build_Linear_module': 'build a SparseQuantizedLinear module with in/out features and block sizes for quantized sparse matrix multiplication', 'convert_from_float': 'convert a float torch.nn.Linear module with qconfig and sparse_params into a SparseQuantizedLinear module', 'set_weight_bias': 'set quantized weight and bias tensors with row and column block sizes on a LinearPackedParams or Linear module', 'unpack_weight_bias': 'unpack prepacked sparse quantized linear parameters back into weight, bias, and block size tensors'}
```

## File: pytorch_pytorch/torch/ao/nn/sparse/quantized/utils.py

Prompts

```
['create a LinearPackedParams object with specified row and column block sizes for sparse quantized linear prepacking', 'build a SparseQuantizedLinear module with in/out features and block sizes for quantized sparse matrix multiplication', 'convert a float torch.nn.Linear module with qconfig and sparse_params into a SparseQuantizedLinear module', 'set quantized weight and bias tensors with row and column block sizes on a LinearPackedParams or Linear module', 'unpack prepacked sparse quantized linear parameters back into weight, bias, and block size tensors', 'test the _is_valid_linear_block_sparse_pattern function with row and column block size arguments', 'create a LinearBlockSparsePattern context manager with custom row_block_size and col_block_size values', 'test the LinearBlockSparsePattern class as a context manager that sets and restores global sparsity pattern', 'refactor the LinearBlockSparsePattern class to use a thread-safe context manager for block sparse pattern', 'summarize the LinearBlockSparsePattern.block_size static method that returns current row and column block sizes']
```

Usage

```
{'test_is_valid_linear_block_sparse_pattern': 'test the _is_valid_linear_block_sparse_pattern function with row and column block size arguments', 'create_linear_block_sparse_pattern': 'create a LinearBlockSparsePattern context manager with custom row_block_size and col_block_size values', 'test_linear_block_sparse_pattern': 'test the LinearBlockSparsePattern class as a context manager that sets and restores global sparsity pattern', 'refactor_linear_block_sparse_pattern': 'refactor the LinearBlockSparsePattern class to use a thread-safe context manager for block sparse pattern', 'summarize_block_size': 'summarize the LinearBlockSparsePattern.block_size static method that returns current row and column block sizes'}
```

