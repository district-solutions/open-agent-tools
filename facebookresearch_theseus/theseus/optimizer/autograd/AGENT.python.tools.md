# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/theseus/optimizer/autograd/baspacho_sparse_autograd.py

Prompts

```
['review the BaspachoSolveFunction class implementing PyTorch autograd for sparse linear system solving with Baspacho', 'summarize the forward method that solves sparse least squares systems using numeric decomposition and factorization', 'summarize the backward method that computes gradients w.r.t. A and b using tensor product differences', 'test the BaspachoSolveFunction forward pass by solving a sparse linear system with symbolic decomposition', 'test the BaspachoSolveFunction backward pass to verify gradient computation for sparse matrix A and vector b', 'build a PyTorch autograd function to solve batched sparse linear systems via Cholesky decomposition', 'build a backward pass that computes gradients through the Cholmod sparse Cholesky solver', 'review the CholmodSolveFunction class and its forward and backward methods for sparse linear algebra', 'test the CholmodSolveFunction forward method with batched sparse matrices and damping parameters', 'refactor the CholmodSolveFunction backward method to optimize the row-wise tensor product gradient computation', 'compute the gradient of sparse matrix A using CSR row pointers and column indices', 'compute A gradient with detached Hessian by multiplying residual b with Hessian H', 'compute A gradient using b_Ax, Hessian H, AH, and solution x without detaching', 'compute A gradient with multiplicative damping correction using alpha and beta values', 'review the compute_A_grad function to understand its CSR sparse matrix gradient computation', 'review the LUCudaSolveFunction class that implements CUDA sparse LU solver with autograd support for least squares', 'review the forward method that computes AtA, applies damping, factors with CusolverLUSolver, and solves for x', 'review the backward method that computes gradients w.r.t. A and b using tensor product formulas', 'summarize the LUCudaSolveFunction autograd function for differentiable sparse linear solves on CUDA', 'test the backward method gradient computation using tensor products of residuals and Hessian inverse']
```

Usage

```
{'review_BaspachoSolveFunction': 'review the BaspachoSolveFunction class implementing PyTorch autograd for sparse linear system solving with Baspacho', 'summarize_forward_method': 'summarize the forward method that solves sparse least squares systems using numeric decomposition and factorization', 'summarize_backward_method': 'summarize the backward method that computes gradients w.r.t. A and b using tensor product differences', 'test_BaspachoSolveFunction_forward': 'test the BaspachoSolveFunction forward pass by solving a sparse linear system with symbolic decomposition', 'test_BaspachoSolveFunction_backward': 'test the BaspachoSolveFunction backward pass to verify gradient computation for sparse matrix A and vector b'}
```

## File: facebookresearch_theseus/theseus/optimizer/autograd/cholmod_sparse_autograd.py

Prompts

```
['review the BaspachoSolveFunction class implementing PyTorch autograd for sparse linear system solving with Baspacho', 'summarize the forward method that solves sparse least squares systems using numeric decomposition and factorization', 'summarize the backward method that computes gradients w.r.t. A and b using tensor product differences', 'test the BaspachoSolveFunction forward pass by solving a sparse linear system with symbolic decomposition', 'test the BaspachoSolveFunction backward pass to verify gradient computation for sparse matrix A and vector b', 'build a PyTorch autograd function to solve batched sparse linear systems via Cholesky decomposition', 'build a backward pass that computes gradients through the Cholmod sparse Cholesky solver', 'review the CholmodSolveFunction class and its forward and backward methods for sparse linear algebra', 'test the CholmodSolveFunction forward method with batched sparse matrices and damping parameters', 'refactor the CholmodSolveFunction backward method to optimize the row-wise tensor product gradient computation', 'compute the gradient of sparse matrix A using CSR row pointers and column indices', 'compute A gradient with detached Hessian by multiplying residual b with Hessian H', 'compute A gradient using b_Ax, Hessian H, AH, and solution x without detaching', 'compute A gradient with multiplicative damping correction using alpha and beta values', 'review the compute_A_grad function to understand its CSR sparse matrix gradient computation', 'review the LUCudaSolveFunction class that implements CUDA sparse LU solver with autograd support for least squares', 'review the forward method that computes AtA, applies damping, factors with CusolverLUSolver, and solves for x', 'review the backward method that computes gradients w.r.t. A and b using tensor product formulas', 'summarize the LUCudaSolveFunction autograd function for differentiable sparse linear solves on CUDA', 'test the backward method gradient computation using tensor products of residuals and Hessian inverse']
```

Usage

```
{'build_cholmod_solve_forward': 'build a PyTorch autograd function to solve batched sparse linear systems via Cholesky decomposition', 'build_cholmod_solve_backward': 'build a backward pass that computes gradients through the Cholmod sparse Cholesky solver', 'review_CholmodSolveFunction': 'review the CholmodSolveFunction class and its forward and backward methods for sparse linear algebra', 'test_CholmodSolveFunction_forward': 'test the CholmodSolveFunction forward method with batched sparse matrices and damping parameters', 'refactor_CholmodSolveFunction_backward': 'refactor the CholmodSolveFunction backward method to optimize the row-wise tensor product gradient computation'}
```

## File: facebookresearch_theseus/theseus/optimizer/autograd/common.py

Prompts

```
['review the BaspachoSolveFunction class implementing PyTorch autograd for sparse linear system solving with Baspacho', 'summarize the forward method that solves sparse least squares systems using numeric decomposition and factorization', 'summarize the backward method that computes gradients w.r.t. A and b using tensor product differences', 'test the BaspachoSolveFunction forward pass by solving a sparse linear system with symbolic decomposition', 'test the BaspachoSolveFunction backward pass to verify gradient computation for sparse matrix A and vector b', 'build a PyTorch autograd function to solve batched sparse linear systems via Cholesky decomposition', 'build a backward pass that computes gradients through the Cholmod sparse Cholesky solver', 'review the CholmodSolveFunction class and its forward and backward methods for sparse linear algebra', 'test the CholmodSolveFunction forward method with batched sparse matrices and damping parameters', 'refactor the CholmodSolveFunction backward method to optimize the row-wise tensor product gradient computation', 'compute the gradient of sparse matrix A using CSR row pointers and column indices', 'compute A gradient with detached Hessian by multiplying residual b with Hessian H', 'compute A gradient using b_Ax, Hessian H, AH, and solution x without detaching', 'compute A gradient with multiplicative damping correction using alpha and beta values', 'review the compute_A_grad function to understand its CSR sparse matrix gradient computation', 'review the LUCudaSolveFunction class that implements CUDA sparse LU solver with autograd support for least squares', 'review the forward method that computes AtA, applies damping, factors with CusolverLUSolver, and solves for x', 'review the backward method that computes gradients w.r.t. A and b using tensor product formulas', 'summarize the LUCudaSolveFunction autograd function for differentiable sparse linear solves on CUDA', 'test the backward method gradient computation using tensor products of residuals and Hessian inverse']
```

Usage

```
{'compute_A_grad_basic': 'compute the gradient of sparse matrix A using CSR row pointers and column indices', 'compute_A_grad_detach_hessian': 'compute A gradient with detached Hessian by multiplying residual b with Hessian H', 'compute_A_grad_full': 'compute A gradient using b_Ax, Hessian H, AH, and solution x without detaching', 'compute_A_grad_damping': 'compute A gradient with multiplicative damping correction using alpha and beta values', 'review_compute_A_grad': 'review the compute_A_grad function to understand its CSR sparse matrix gradient computation'}
```

## File: facebookresearch_theseus/theseus/optimizer/autograd/lu_cuda_sparse_autograd.py

Prompts

```
['review the BaspachoSolveFunction class implementing PyTorch autograd for sparse linear system solving with Baspacho', 'summarize the forward method that solves sparse least squares systems using numeric decomposition and factorization', 'summarize the backward method that computes gradients w.r.t. A and b using tensor product differences', 'test the BaspachoSolveFunction forward pass by solving a sparse linear system with symbolic decomposition', 'test the BaspachoSolveFunction backward pass to verify gradient computation for sparse matrix A and vector b', 'build a PyTorch autograd function to solve batched sparse linear systems via Cholesky decomposition', 'build a backward pass that computes gradients through the Cholmod sparse Cholesky solver', 'review the CholmodSolveFunction class and its forward and backward methods for sparse linear algebra', 'test the CholmodSolveFunction forward method with batched sparse matrices and damping parameters', 'refactor the CholmodSolveFunction backward method to optimize the row-wise tensor product gradient computation', 'compute the gradient of sparse matrix A using CSR row pointers and column indices', 'compute A gradient with detached Hessian by multiplying residual b with Hessian H', 'compute A gradient using b_Ax, Hessian H, AH, and solution x without detaching', 'compute A gradient with multiplicative damping correction using alpha and beta values', 'review the compute_A_grad function to understand its CSR sparse matrix gradient computation', 'review the LUCudaSolveFunction class that implements CUDA sparse LU solver with autograd support for least squares', 'review the forward method that computes AtA, applies damping, factors with CusolverLUSolver, and solves for x', 'review the backward method that computes gradients w.r.t. A and b using tensor product formulas', 'summarize the LUCudaSolveFunction autograd function for differentiable sparse linear solves on CUDA', 'test the backward method gradient computation using tensor products of residuals and Hessian inverse']
```

Usage

```
{'review_LUCudaSolveFunction': 'review the LUCudaSolveFunction class that implements CUDA sparse LU solver with autograd support for least squares', 'review_forward_method': 'review the forward method that computes AtA, applies damping, factors with CusolverLUSolver, and solves for x', 'review_backward_method': 'review the backward method that computes gradients w.r.t. A and b using tensor product formulas', 'summarize_LUCudaSolveFunction': 'summarize the LUCudaSolveFunction autograd function for differentiable sparse linear solves on CUDA', 'test_backward_gradient': 'test the backward method gradient computation using tensor products of residuals and Hessian inverse'}
```

