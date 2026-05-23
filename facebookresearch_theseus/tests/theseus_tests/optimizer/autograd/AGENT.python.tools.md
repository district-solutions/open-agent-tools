# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/tests/theseus_tests/optimizer/autograd/common.py

Prompts

```
["test a solve function's gradients using gradcheck and floating point precision validation", 'run gradient correctness checks on a solver function with specified eps, atol, and rtol tolerances', 'review the check_grad function to understand how it validates gradients via gradcheck and float precision', 'refactor check_grad to support additional input types beyond matrix A and vector b', 'summarize how check_grad uses torch.autograd.gradcheck and grad to verify solver gradient correctness', 'create a BaspachoSparseSolver with random sparse linearization for a given batch size and column count', 'test the backward gradient computation of BaspachoSolveFunction on random sparse linearization data', 'run parametrized CPU tests for Baspacho sparse solver backward gradient correctness', 'run parametrized CUDA tests for Baspacho sparse solver backward gradient correctness', 'review the BaspachoSolveFunction autograd function used for sparse linear system solving in Theseus', 'test the LUCudaSolveFunction autograd backward pass using check_grad with numerical gradient verification', 'build a sparse matrix in CSR format with random data, column indices, and row pointers for batched solving', 'create a LUCudaSparseSolver with an Objective, VariableOrdering, and damping parameter for sparse linear solves', 'test the sparse backward step by setting up a mock linearization and verifying gradients with check_grad', 'review the LUCudaSolveFunction.apply inputs including A_val, b, structure, damping, and solver context', 'test that CHOLMOD uses float64 precision by verifying delta values stay below 1.0', 'build a sparse matrix with random data and CSR structure for batched linearization testing', 'review the CholmodSolveFunction.apply method for sparse Cholesky solve with symbolic decomposition inputs', 'summarize the sparse backward test that validates autograd gradients for CholmodSparseSolver linearization']
```

Usage

```
{'test_check_grad': "test a solve function's gradients using gradcheck and floating point precision validation", 'run_check_grad': 'run gradient correctness checks on a solver function with specified eps, atol, and rtol tolerances', 'review_check_grad': 'review the check_grad function to understand how it validates gradients via gradcheck and float precision', 'refactor_check_grad': 'refactor check_grad to support additional input types beyond matrix A and vector b', 'summarize_check_grad': 'summarize how check_grad uses torch.autograd.gradcheck and grad to verify solver gradient correctness'}
```

## File: facebookresearch_theseus/tests/theseus_tests/optimizer/autograd/test_baspacho_sparse_backward.py

Prompts

```
["test a solve function's gradients using gradcheck and floating point precision validation", 'run gradient correctness checks on a solver function with specified eps, atol, and rtol tolerances', 'review the check_grad function to understand how it validates gradients via gradcheck and float precision', 'refactor check_grad to support additional input types beyond matrix A and vector b', 'summarize how check_grad uses torch.autograd.gradcheck and grad to verify solver gradient correctness', 'create a BaspachoSparseSolver with random sparse linearization for a given batch size and column count', 'test the backward gradient computation of BaspachoSolveFunction on random sparse linearization data', 'run parametrized CPU tests for Baspacho sparse solver backward gradient correctness', 'run parametrized CUDA tests for Baspacho sparse solver backward gradient correctness', 'review the BaspachoSolveFunction autograd function used for sparse linear system solving in Theseus', 'test the LUCudaSolveFunction autograd backward pass using check_grad with numerical gradient verification', 'build a sparse matrix in CSR format with random data, column indices, and row pointers for batched solving', 'create a LUCudaSparseSolver with an Objective, VariableOrdering, and damping parameter for sparse linear solves', 'test the sparse backward step by setting up a mock linearization and verifying gradients with check_grad', 'review the LUCudaSolveFunction.apply inputs including A_val, b, structure, damping, and solver context', 'test that CHOLMOD uses float64 precision by verifying delta values stay below 1.0', 'build a sparse matrix with random data and CSR structure for batched linearization testing', 'review the CholmodSolveFunction.apply method for sparse Cholesky solve with symbolic decomposition inputs', 'summarize the sparse backward test that validates autograd gradients for CholmodSparseSolver linearization']
```

Usage

```
{'get_linearization_and_solver_for_random_sparse': 'create a BaspachoSparseSolver with random sparse linearization for a given batch size and column count', 'check_sparse_backward_step': 'test the backward gradient computation of BaspachoSolveFunction on random sparse linearization data', 'test_sparse_backward_step_cpu': 'run parametrized CPU tests for Baspacho sparse solver backward gradient correctness', 'test_sparse_backward_step_cuda': 'run parametrized CUDA tests for Baspacho sparse solver backward gradient correctness', 'BaspachoSolveFunction': 'review the BaspachoSolveFunction autograd function used for sparse linear system solving in Theseus'}
```

## File: facebookresearch_theseus/tests/theseus_tests/optimizer/autograd/test_lu_cuda_sparse_backward.py

Prompts

```
["test a solve function's gradients using gradcheck and floating point precision validation", 'run gradient correctness checks on a solver function with specified eps, atol, and rtol tolerances', 'review the check_grad function to understand how it validates gradients via gradcheck and float precision', 'refactor check_grad to support additional input types beyond matrix A and vector b', 'summarize how check_grad uses torch.autograd.gradcheck and grad to verify solver gradient correctness', 'create a BaspachoSparseSolver with random sparse linearization for a given batch size and column count', 'test the backward gradient computation of BaspachoSolveFunction on random sparse linearization data', 'run parametrized CPU tests for Baspacho sparse solver backward gradient correctness', 'run parametrized CUDA tests for Baspacho sparse solver backward gradient correctness', 'review the BaspachoSolveFunction autograd function used for sparse linear system solving in Theseus', 'test the LUCudaSolveFunction autograd backward pass using check_grad with numerical gradient verification', 'build a sparse matrix in CSR format with random data, column indices, and row pointers for batched solving', 'create a LUCudaSparseSolver with an Objective, VariableOrdering, and damping parameter for sparse linear solves', 'test the sparse backward step by setting up a mock linearization and verifying gradients with check_grad', 'review the LUCudaSolveFunction.apply inputs including A_val, b, structure, damping, and solver context', 'test that CHOLMOD uses float64 precision by verifying delta values stay below 1.0', 'build a sparse matrix with random data and CSR structure for batched linearization testing', 'review the CholmodSolveFunction.apply method for sparse Cholesky solve with symbolic decomposition inputs', 'summarize the sparse backward test that validates autograd gradients for CholmodSparseSolver linearization']
```

Usage

```
{'test_LUCudaSolveFunction_backward': 'test the LUCudaSolveFunction autograd backward pass using check_grad with numerical gradient verification', 'build_sparse_matrix_CSR': 'build a sparse matrix in CSR format with random data, column indices, and row pointers for batched solving', 'create_LUCudaSparseSolver': 'create a LUCudaSparseSolver with an Objective, VariableOrdering, and damping parameter for sparse linear solves', 'test_sparse_backward_step': 'test the sparse backward step by setting up a mock linearization and verifying gradients with check_grad', 'review_LUCudaSolveFunction_apply': 'review the LUCudaSolveFunction.apply inputs including A_val, b, structure, damping, and solver context'}
```

## File: facebookresearch_theseus/tests/theseus_tests/optimizer/autograd/test_sparse_backward.py

Prompts

```
["test a solve function's gradients using gradcheck and floating point precision validation", 'run gradient correctness checks on a solver function with specified eps, atol, and rtol tolerances', 'review the check_grad function to understand how it validates gradients via gradcheck and float precision', 'refactor check_grad to support additional input types beyond matrix A and vector b', 'summarize how check_grad uses torch.autograd.gradcheck and grad to verify solver gradient correctness', 'create a BaspachoSparseSolver with random sparse linearization for a given batch size and column count', 'test the backward gradient computation of BaspachoSolveFunction on random sparse linearization data', 'run parametrized CPU tests for Baspacho sparse solver backward gradient correctness', 'run parametrized CUDA tests for Baspacho sparse solver backward gradient correctness', 'review the BaspachoSolveFunction autograd function used for sparse linear system solving in Theseus', 'test the LUCudaSolveFunction autograd backward pass using check_grad with numerical gradient verification', 'build a sparse matrix in CSR format with random data, column indices, and row pointers for batched solving', 'create a LUCudaSparseSolver with an Objective, VariableOrdering, and damping parameter for sparse linear solves', 'test the sparse backward step by setting up a mock linearization and verifying gradients with check_grad', 'review the LUCudaSolveFunction.apply inputs including A_val, b, structure, damping, and solver context', 'test that CHOLMOD uses float64 precision by verifying delta values stay below 1.0', 'build a sparse matrix with random data and CSR structure for batched linearization testing', 'review the CholmodSolveFunction.apply method for sparse Cholesky solve with symbolic decomposition inputs', 'summarize the sparse backward test that validates autograd gradients for CholmodSparseSolver linearization']
```

Usage

```
{'test_sparse_backward_step': 'test the CholmodSolveFunction backward pass using gradcheck with a mock sparse matrix and damping', 'test_float64_used': 'test that CHOLMOD uses float64 precision by verifying delta values stay below 1.0', 'build_sparse_mat': 'build a sparse matrix with random data and CSR structure for batched linearization testing', 'review_CholmodSolveFunction_apply': 'review the CholmodSolveFunction.apply method for sparse Cholesky solve with symbolic decomposition inputs', 'summarize_test_sparse_backward': 'summarize the sparse backward test that validates autograd gradients for CholmodSparseSolver linearization'}
```

