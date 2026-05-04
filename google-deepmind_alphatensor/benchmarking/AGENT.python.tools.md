# Agent Python Tools

- repo: google-deepmind/alphatensor
- repo_uri: https://github.com/google-deepmind/alphatensor

## File: google-deepmind_alphatensor/benchmarking/factorizations.py

Prompts

```
['get the rank-49 factorization array for fast 4x4 matrix multiplication optimized for NVIDIA V100 GPUs', 'get the rank-49 factorization array for fast 4x4 matrix multiplication optimized for Google TPUv2', 'get the Strassen squared rank-49 factorization array for fast 4x4 matrix multiplication', 'compute the Kronecker product of two tensor factorization arrays to produce a combined factorization', 'get the rank-7 Strassen factorization array for fast 2x2 matrix multiplication', 'run the test that verifies GPU factors decompose the 4x4x4 matrix multiplication tensor', 'run the test that verifies TPU factors decompose the 4x4x4 matrix multiplication tensor', 'run the test that compares AlphaTensor GPU algorithm output against standard matrix multiplication on 1024x1024 matrices', 'test the correctness of AlphaTensor fast matrix multiplication algorithms using absltest', 'review the MatrixMultiplicationCorrectnessTest class and its three test methods for tensor decomposition and precision', 'split a JAX array into an n_rows by n_cols block matrix using jnp.split', 'create a 3D tensor T_n of shape n^2 x n^2 x n^2 representing matrix multiplication', 'build a JAX function that multiplies block matrices using a tensor factorization', 'benchmark the performance of jnp.dot on random matrices with configurable trials and dtype', 'benchmark a fast matrix multiplication algorithm defined by tensor factorization factors']
```

Usage

```
{'get_alphatensor_gpu_factorization': 'get the rank-49 factorization array for fast 4x4 matrix multiplication optimized for NVIDIA V100 GPUs', 'get_alphatensor_tpu_factorization': 'get the rank-49 factorization array for fast 4x4 matrix multiplication optimized for Google TPUv2', 'get_strassen_squared_factorization': 'get the Strassen squared rank-49 factorization array for fast 4x4 matrix multiplication', 'compute_kronecker_product_of_factors': 'compute the Kronecker product of two tensor factorization arrays to produce a combined factorization', 'get_strassen_factorization': 'get the rank-7 Strassen factorization array for fast 2x2 matrix multiplication'}
```

## File: google-deepmind_alphatensor/benchmarking/test_correctness.py

Prompts

```
['get the rank-49 factorization array for fast 4x4 matrix multiplication optimized for NVIDIA V100 GPUs', 'get the rank-49 factorization array for fast 4x4 matrix multiplication optimized for Google TPUv2', 'get the Strassen squared rank-49 factorization array for fast 4x4 matrix multiplication', 'compute the Kronecker product of two tensor factorization arrays to produce a combined factorization', 'get the rank-7 Strassen factorization array for fast 2x2 matrix multiplication', 'run the test that verifies GPU factors decompose the 4x4x4 matrix multiplication tensor', 'run the test that verifies TPU factors decompose the 4x4x4 matrix multiplication tensor', 'run the test that compares AlphaTensor GPU algorithm output against standard matrix multiplication on 1024x1024 matrices', 'test the correctness of AlphaTensor fast matrix multiplication algorithms using absltest', 'review the MatrixMultiplicationCorrectnessTest class and its three test methods for tensor decomposition and precision', 'split a JAX array into an n_rows by n_cols block matrix using jnp.split', 'create a 3D tensor T_n of shape n^2 x n^2 x n^2 representing matrix multiplication', 'build a JAX function that multiplies block matrices using a tensor factorization', 'benchmark the performance of jnp.dot on random matrices with configurable trials and dtype', 'benchmark a fast matrix multiplication algorithm defined by tensor factorization factors']
```

Usage

```
{'run_tensor_decomposition_gpu_test': 'run the test that verifies GPU factors decompose the 4x4x4 matrix multiplication tensor', 'run_tensor_decomposition_tpu_test': 'run the test that verifies TPU factors decompose the 4x4x4 matrix multiplication tensor', 'run_gpu_matrix_multiplication_precision_test': 'run the test that compares AlphaTensor GPU algorithm output against standard matrix multiplication on 1024x1024 matrices', 'test_matrix_multiplication_correctness': 'test the correctness of AlphaTensor fast matrix multiplication algorithms using absltest', 'review_matrix_multiplication_correctness_test': 'review the MatrixMultiplicationCorrectnessTest class and its three test methods for tensor decomposition and precision'}
```

## File: google-deepmind_alphatensor/benchmarking/utils.py

Prompts

```
['get the rank-49 factorization array for fast 4x4 matrix multiplication optimized for NVIDIA V100 GPUs', 'get the rank-49 factorization array for fast 4x4 matrix multiplication optimized for Google TPUv2', 'get the Strassen squared rank-49 factorization array for fast 4x4 matrix multiplication', 'compute the Kronecker product of two tensor factorization arrays to produce a combined factorization', 'get the rank-7 Strassen factorization array for fast 2x2 matrix multiplication', 'run the test that verifies GPU factors decompose the 4x4x4 matrix multiplication tensor', 'run the test that verifies TPU factors decompose the 4x4x4 matrix multiplication tensor', 'run the test that compares AlphaTensor GPU algorithm output against standard matrix multiplication on 1024x1024 matrices', 'test the correctness of AlphaTensor fast matrix multiplication algorithms using absltest', 'review the MatrixMultiplicationCorrectnessTest class and its three test methods for tensor decomposition and precision', 'split a JAX array into an n_rows by n_cols block matrix using jnp.split', 'create a 3D tensor T_n of shape n^2 x n^2 x n^2 representing matrix multiplication', 'build a JAX function that multiplies block matrices using a tensor factorization', 'benchmark the performance of jnp.dot on random matrices with configurable trials and dtype', 'benchmark a fast matrix multiplication algorithm defined by tensor factorization factors']
```

Usage

```
{'block_split': 'split a JAX array into an n_rows by n_cols block matrix using jnp.split', 'get_matrix_multiplication_tensor': 'create a 3D tensor T_n of shape n^2 x n^2 x n^2 representing matrix multiplication', 'algorithm_from_factors': 'build a JAX function that multiplies block matrices using a tensor factorization', 'benchmark_jnp_dot': 'benchmark the performance of jnp.dot on random matrices with configurable trials and dtype', 'benchmark_factorized_algorithm': 'benchmark a fast matrix multiplication algorithm defined by tensor factorization factors'}
```

