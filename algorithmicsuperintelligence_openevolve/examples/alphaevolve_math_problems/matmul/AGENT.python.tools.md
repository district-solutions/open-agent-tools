# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/matmul/evaluator.py

Prompts

```
['run the evaluate function to score a matrix multiplication program by its tensor decomposition rank', 'verify a tensor decomposition tuple of three factor matrices matches the target matmul tensor', 'test the evaluate function with a program path that returns a decomposition and rank', 'review the verify_tensor_decomposition function to understand shape validation and einsum reconstruction logic', 'refactor the evaluate function to improve error handling when importing and running candidate programs', 'run the two-phase optimization to find a half-integer decomposition of the 2x4x5 matrix multiplication tensor', 'create the tensor representation of matrix multiplication for given dimensions n, m, and p', 'build a continuous optimizer that finds approximate solutions using Adam and constrained tanh decomposition', 'build a discrete optimizer that refines continuous solutions to exact half-integer values using a straight-through estimator', 'test the straight-through estimator function that rounds values to the nearest half-integer with identity gradients']
```

Usage

```
{'run_evaluate_program': 'run the evaluate function to score a matrix multiplication program by its tensor decomposition rank', 'verify_tensor_decomposition': 'verify a tensor decomposition tuple of three factor matrices matches the target matmul tensor', 'test_evaluate_with_program': 'test the evaluate function with a program path that returns a decomposition and rank', 'review_verify_tensor_decomposition': 'review the verify_tensor_decomposition function to understand shape validation and einsum reconstruction logic', 'refactor_evaluate_error_handling': 'refactor the evaluate function to improve error handling when importing and running candidate programs'}
```

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/matmul/initial_program.py

Prompts

```
['run the evaluate function to score a matrix multiplication program by its tensor decomposition rank', 'verify a tensor decomposition tuple of three factor matrices matches the target matmul tensor', 'test the evaluate function with a program path that returns a decomposition and rank', 'review the verify_tensor_decomposition function to understand shape validation and einsum reconstruction logic', 'refactor the evaluate function to improve error handling when importing and running candidate programs', 'run the two-phase optimization to find a half-integer decomposition of the 2x4x5 matrix multiplication tensor', 'create the tensor representation of matrix multiplication for given dimensions n, m, and p', 'build a continuous optimizer that finds approximate solutions using Adam and constrained tanh decomposition', 'build a discrete optimizer that refines continuous solutions to exact half-integer values using a straight-through estimator', 'test the straight-through estimator function that rounds values to the nearest half-integer with identity gradients']
```

Usage

```
{'run_matmul_algorithm': 'run the two-phase optimization to find a half-integer decomposition of the 2x4x5 matrix multiplication tensor', 'create_matrix_multiplication_tensor': 'create the tensor representation of matrix multiplication for given dimensions n, m, and p', 'build_continuous_optimizer': 'build a continuous optimizer that finds approximate solutions using Adam and constrained tanh decomposition', 'build_discrete_optimizer': 'build a discrete optimizer that refines continuous solutions to exact half-integer values using a straight-through estimator', 'test_round_to_half_ste': 'test the straight-through estimator function that rounds values to the nearest half-integer with identity gradients'}
```

