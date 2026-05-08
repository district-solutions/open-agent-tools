# Agent Python Tools

- repo: facebookresearch/kill-the-bits
- repo_uri: https://github.com/facebookresearch/kill-the-bits

## File: facebookresearch_kill-the-bits/src/quantization/distance.py

Prompts

```
['build a ComputeDistances module with a weight matrix and centroids for multi-GPU distance computation', 'create a Distances layer that computes L2 distances between activations and centroids using broadcasting', 'create a Reduce layer that aggregates per-GPU distances by summing and taking the square root', 'run the ComputeDistances forward pass on input activations to get quantization distances', 'review the Distances class forward method and its automatic chunking strategy for GPU memory', 'create an EM quantizer with a given number of centroids and weight matrix M', 'initialize centroids by randomly sampling columns from the weight matrix M', 'run one EM iteration performing E-step assignment and M-step centroid update', 'assign each column of the weight matrix to its closest centroid', 'save or load EM centroids and assignments to and from disk', 'build a PQ product quantizer for a neural network layer using input activations and weight matrix', 'encode weight matrix into PQ centroids by running EM training iterations on sampled activations', 'decode quantized PQ centroids back into reconstructed weight matrix using learned assignments', 'review the PQ unroll_activations method that chunks and concatenates activations across n_blocks', 'summarize the PQ class that performs product quantization with joint centroid learning across blocks', 'compute the minimizer X of ||A[X,...,X] - B||^2 using the pseudo-inverse of matrix A', 'compute the minimizer X using a precomputed pseudo-inverse of A to avoid redundant calculations', 'sum columns of matrix B and multiply by the pseudo-inverse of A to find X', 'review the solve_stack function that finds the least-squares minimizer using PyTorch pseudo-inverse', 'summarize the solve_stack function which minimizes ||A[X,...,X] - B||^2 via pseudo-inverse']
```

Usage

```
{'build_compute_distances_module': 'build a ComputeDistances module with a weight matrix and centroids for multi-GPU distance computation', 'create_distances_layer': 'create a Distances layer that computes L2 distances between activations and centroids using broadcasting', 'create_reduce_layer': 'create a Reduce layer that aggregates per-GPU distances by summing and taking the square root', 'run_compute_distances_forward': 'run the ComputeDistances forward pass on input activations to get quantization distances', 'review_distances_chunking': 'review the Distances class forward method and its automatic chunking strategy for GPU memory'}
```

## File: facebookresearch_kill-the-bits/src/quantization/em.py

Prompts

```
['build a ComputeDistances module with a weight matrix and centroids for multi-GPU distance computation', 'create a Distances layer that computes L2 distances between activations and centroids using broadcasting', 'create a Reduce layer that aggregates per-GPU distances by summing and taking the square root', 'run the ComputeDistances forward pass on input activations to get quantization distances', 'review the Distances class forward method and its automatic chunking strategy for GPU memory', 'create an EM quantizer with a given number of centroids and weight matrix M', 'initialize centroids by randomly sampling columns from the weight matrix M', 'run one EM iteration performing E-step assignment and M-step centroid update', 'assign each column of the weight matrix to its closest centroid', 'save or load EM centroids and assignments to and from disk', 'build a PQ product quantizer for a neural network layer using input activations and weight matrix', 'encode weight matrix into PQ centroids by running EM training iterations on sampled activations', 'decode quantized PQ centroids back into reconstructed weight matrix using learned assignments', 'review the PQ unroll_activations method that chunks and concatenates activations across n_blocks', 'summarize the PQ class that performs product quantization with joint centroid learning across blocks', 'compute the minimizer X of ||A[X,...,X] - B||^2 using the pseudo-inverse of matrix A', 'compute the minimizer X using a precomputed pseudo-inverse of A to avoid redundant calculations', 'sum columns of matrix B and multiply by the pseudo-inverse of A to find X', 'review the solve_stack function that finds the least-squares minimizer using PyTorch pseudo-inverse', 'summarize the solve_stack function which minimizes ||A[X,...,X] - B||^2 via pseudo-inverse']
```

Usage

```
{'initialize_EM_quantizer': 'create an EM quantizer with a given number of centroids and weight matrix M', 'initialize_centroids_random': 'initialize centroids by randomly sampling columns from the weight matrix M', 'run_EM_step': 'run one EM iteration performing E-step assignment and M-step centroid update', 'assign_columns_to_centroids': 'assign each column of the weight matrix to its closest centroid', 'save_load_centroids': 'save or load EM centroids and assignments to and from disk'}
```

## File: facebookresearch_kill-the-bits/src/quantization/pq.py

Prompts

```
['build a ComputeDistances module with a weight matrix and centroids for multi-GPU distance computation', 'create a Distances layer that computes L2 distances between activations and centroids using broadcasting', 'create a Reduce layer that aggregates per-GPU distances by summing and taking the square root', 'run the ComputeDistances forward pass on input activations to get quantization distances', 'review the Distances class forward method and its automatic chunking strategy for GPU memory', 'create an EM quantizer with a given number of centroids and weight matrix M', 'initialize centroids by randomly sampling columns from the weight matrix M', 'run one EM iteration performing E-step assignment and M-step centroid update', 'assign each column of the weight matrix to its closest centroid', 'save or load EM centroids and assignments to and from disk', 'build a PQ product quantizer for a neural network layer using input activations and weight matrix', 'encode weight matrix into PQ centroids by running EM training iterations on sampled activations', 'decode quantized PQ centroids back into reconstructed weight matrix using learned assignments', 'review the PQ unroll_activations method that chunks and concatenates activations across n_blocks', 'summarize the PQ class that performs product quantization with joint centroid learning across blocks', 'compute the minimizer X of ||A[X,...,X] - B||^2 using the pseudo-inverse of matrix A', 'compute the minimizer X using a precomputed pseudo-inverse of A to avoid redundant calculations', 'sum columns of matrix B and multiply by the pseudo-inverse of A to find X', 'review the solve_stack function that finds the least-squares minimizer using PyTorch pseudo-inverse', 'summarize the solve_stack function which minimizes ||A[X,...,X] - B||^2 via pseudo-inverse']
```

Usage

```
{'build_PQ_quantizer': 'build a PQ product quantizer for a neural network layer using input activations and weight matrix', 'encode_PQ_centroids': 'encode weight matrix into PQ centroids by running EM training iterations on sampled activations', 'decode_PQ_weights': 'decode quantized PQ centroids back into reconstructed weight matrix using learned assignments', 'review_PQ_unroll_activations': 'review the PQ unroll_activations method that chunks and concatenates activations across n_blocks', 'summarize_PQ_class': 'summarize the PQ class that performs product quantization with joint centroid learning across blocks'}
```

## File: facebookresearch_kill-the-bits/src/quantization/solver.py

Prompts

```
['build a ComputeDistances module with a weight matrix and centroids for multi-GPU distance computation', 'create a Distances layer that computes L2 distances between activations and centroids using broadcasting', 'create a Reduce layer that aggregates per-GPU distances by summing and taking the square root', 'run the ComputeDistances forward pass on input activations to get quantization distances', 'review the Distances class forward method and its automatic chunking strategy for GPU memory', 'create an EM quantizer with a given number of centroids and weight matrix M', 'initialize centroids by randomly sampling columns from the weight matrix M', 'run one EM iteration performing E-step assignment and M-step centroid update', 'assign each column of the weight matrix to its closest centroid', 'save or load EM centroids and assignments to and from disk', 'build a PQ product quantizer for a neural network layer using input activations and weight matrix', 'encode weight matrix into PQ centroids by running EM training iterations on sampled activations', 'decode quantized PQ centroids back into reconstructed weight matrix using learned assignments', 'review the PQ unroll_activations method that chunks and concatenates activations across n_blocks', 'summarize the PQ class that performs product quantization with joint centroid learning across blocks', 'compute the minimizer X of ||A[X,...,X] - B||^2 using the pseudo-inverse of matrix A', 'compute the minimizer X using a precomputed pseudo-inverse of A to avoid redundant calculations', 'sum columns of matrix B and multiply by the pseudo-inverse of A to find X', 'review the solve_stack function that finds the least-squares minimizer using PyTorch pseudo-inverse', 'summarize the solve_stack function which minimizes ||A[X,...,X] - B||^2 via pseudo-inverse']
```

Usage

```
{'solve_stack_minimizer': 'compute the minimizer X of ||A[X,...,X] - B||^2 using the pseudo-inverse of matrix A', 'solve_stack_with_pinv': 'compute the minimizer X using a precomputed pseudo-inverse of A to avoid redundant calculations', 'solve_stack_sum_columns': 'sum columns of matrix B and multiply by the pseudo-inverse of A to find X', 'review_solve_stack': 'review the solve_stack function that finds the least-squares minimizer using PyTorch pseudo-inverse', 'summarize_solve_stack': 'summarize the solve_stack function which minimizes ||A[X,...,X] - B||^2 via pseudo-inverse'}
```

