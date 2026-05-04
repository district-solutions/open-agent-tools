# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/algorithms/transforms/rotation/utils/math.py

Prompts

```
['build a python module that constructs a deterministic Hadamard matrix of a given power-of-2 size using Sylvester construction', 'create a python module that generates a randomly signed Hadamard matrix supporting non-power-of-2 sizes from precomputed safetensors', 'test the is_pow2 function to check if an integer is a positive power of two using bitwise operations', 'review the deterministic_hadamard_matrix function to verify it raises ValueError for non-power-of-2 sizes and sizes less than or equal to zero', 'summarize the random_hadamard_matrix function that creates randomly signed Hadamard matrices by composing a random diagonal with precomputed base matrices', 'apply a rotation matrix to an input tensor for a PyTorch linear layer', 'apply a transposed rotation matrix to a weight tensor for a PyTorch linear layer', 'perform block-diagonal matrix multiplication on two tensors with matching inner dimensions', 'perform block-diagonal matrix multiplication where tensor A has a larger inner dimension than B', 'perform block-diagonal matrix multiplication where tensor B has a larger inner dimension than A']
```

Usage

```
{'build_deterministic_hadamard_matrix': 'build a python module that constructs a deterministic Hadamard matrix of a given power-of-2 size using Sylvester construction', 'create_random_hadamard_matrix': 'create a python module that generates a randomly signed Hadamard matrix supporting non-power-of-2 sizes from precomputed safetensors', 'test_is_pow2': 'test the is_pow2 function to check if an integer is a positive power of two using bitwise operations', 'review_deterministic_hadamard_matrix': 'review the deterministic_hadamard_matrix function to verify it raises ValueError for non-power-of-2 sizes and sizes less than or equal to zero', 'summarize_random_hadamard_matrix': 'summarize the random_hadamard_matrix function that creates randomly signed Hadamard matrices by composing a random diagonal with precomputed base matrices'}
```

## File: intel_auto-round/auto_round/algorithms/transforms/rotation/utils/matrix.py

Prompts

```
['build a python module that constructs a deterministic Hadamard matrix of a given power-of-2 size using Sylvester construction', 'create a python module that generates a randomly signed Hadamard matrix supporting non-power-of-2 sizes from precomputed safetensors', 'test the is_pow2 function to check if an integer is a positive power of two using bitwise operations', 'review the deterministic_hadamard_matrix function to verify it raises ValueError for non-power-of-2 sizes and sizes less than or equal to zero', 'summarize the random_hadamard_matrix function that creates randomly signed Hadamard matrices by composing a random diagonal with precomputed base matrices', 'apply a rotation matrix to an input tensor for a PyTorch linear layer', 'apply a transposed rotation matrix to a weight tensor for a PyTorch linear layer', 'perform block-diagonal matrix multiplication on two tensors with matching inner dimensions', 'perform block-diagonal matrix multiplication where tensor A has a larger inner dimension than B', 'perform block-diagonal matrix multiplication where tensor B has a larger inner dimension than A']
```

Usage

```
{'apply_transform_weight_input': 'apply a rotation matrix to an input tensor for a PyTorch linear layer', 'apply_transform_weight_weight': 'apply a transposed rotation matrix to a weight tensor for a PyTorch linear layer', 'multihead_matmul_equal_dims': 'perform block-diagonal matrix multiplication on two tensors with matching inner dimensions', 'multihead_matmul_larger_A': 'perform block-diagonal matrix multiplication where tensor A has a larger inner dimension than B', 'multihead_matmul_larger_B': 'perform block-diagonal matrix multiplication where tensor B has a larger inner dimension than A'}
```

