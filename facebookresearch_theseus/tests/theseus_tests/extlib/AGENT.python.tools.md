# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/tests/theseus_tests/extlib/test_baspacho.py

Prompts

```
['run check_baspacho to validate sparse least squares solver with given batch size and fill ratio', 'test the baspacho solver on CPU with parametrized batch size and sparsity settings', 'test the baspacho solver on CUDA with parametrized batch size and sparsity settings', 'review check_baspacho function that generates random sparse matrices and verifies solver residuals', 'summarize the test_baspacho_cpu pytest function that runs 64 parametrized solver test cases', 'run the check_simple function to verify sparse matrix solve with given row pointers and column indices', 'review the SymbolicDecomposition class usage for creating numeric decomposition and solving linear systems', 'refactor the check_simple function to support custom sparse matrix values and batch sizes', 'test the check_lu_solver function with custom batch size and sparse matrix dimensions', 'run the test_lu_solver_1 pytest test for a 50x30 sparse matrix with 0.2 fill ratio', 'run the test_lu_solver_3 pytest test for a 300x90 sparse matrix with batch size 10', 'review how CusolverLUSolver is initialized, factored, and used to solve linear systems', 'refactor check_lu_solver to support irregular batch sizes smaller than init_batch_size', 'test the mat_vec CUDA extension for sparse matrix vector multiplication with batched tensors', 'test the tmat_vec CUDA extension for transposed sparse matrix vector multiplication', 'test the mult_MtM CUDA extension that computes A transpose times A for sparse matrices', 'test the apply_damping CUDA extension that scales and shifts diagonal elements of sparse matrices', 'test the check_mat_mult helper function with custom batch size rows cols and fill parameters']
```

Usage

```
{'run_check_baspacho': 'run check_baspacho to validate sparse least squares solver with given batch size and fill ratio', 'test_baspacho_cpu': 'test the baspacho solver on CPU with parametrized batch size and sparsity settings', 'test_baspacho_cuda': 'test the baspacho solver on CUDA with parametrized batch size and sparsity settings', 'review_check_baspacho': 'review check_baspacho function that generates random sparse matrices and verifies solver residuals', 'summarize_test_baspacho_cpu': 'summarize the test_baspacho_cpu pytest function that runs 64 parametrized solver test cases'}
```

## File: facebookresearch_theseus/tests/theseus_tests/extlib/test_baspacho_simple.py

Prompts

```
['run check_baspacho to validate sparse least squares solver with given batch size and fill ratio', 'test the baspacho solver on CPU with parametrized batch size and sparsity settings', 'test the baspacho solver on CUDA with parametrized batch size and sparsity settings', 'review check_baspacho function that generates random sparse matrices and verifies solver residuals', 'summarize the test_baspacho_cpu pytest function that runs 64 parametrized solver test cases', 'run the check_simple function to verify sparse matrix solve with given row pointers and column indices', 'review the SymbolicDecomposition class usage for creating numeric decomposition and solving linear systems', 'refactor the check_simple function to support custom sparse matrix values and batch sizes', 'test the check_lu_solver function with custom batch size and sparse matrix dimensions', 'run the test_lu_solver_1 pytest test for a 50x30 sparse matrix with 0.2 fill ratio', 'run the test_lu_solver_3 pytest test for a 300x90 sparse matrix with batch size 10', 'review how CusolverLUSolver is initialized, factored, and used to solve linear systems', 'refactor check_lu_solver to support irregular batch sizes smaller than init_batch_size', 'test the mat_vec CUDA extension for sparse matrix vector multiplication with batched tensors', 'test the tmat_vec CUDA extension for transposed sparse matrix vector multiplication', 'test the mult_MtM CUDA extension that computes A transpose times A for sparse matrices', 'test the apply_damping CUDA extension that scales and shifts diagonal elements of sparse matrices', 'test the check_mat_mult helper function with custom batch size rows cols and fill parameters']
```

Usage

```
{'test_baspacho_cpu': 'test the BaSPACHO solver symbolic decomposition on CPU with sparse matrix factorization', 'test_baspacho_cuda': 'test the BaSPACHO solver symbolic decomposition on CUDA with sparse matrix factorization', 'run_check_simple': 'run the check_simple function to verify sparse matrix solve with given row pointers and column indices', 'review_symbolic_decomposition': 'review the SymbolicDecomposition class usage for creating numeric decomposition and solving linear systems', 'refactor_check_simple': 'refactor the check_simple function to support custom sparse matrix values and batch sizes'}
```

## File: facebookresearch_theseus/tests/theseus_tests/extlib/test_cusolver_lu_solver.py

Prompts

```
['run check_baspacho to validate sparse least squares solver with given batch size and fill ratio', 'test the baspacho solver on CPU with parametrized batch size and sparsity settings', 'test the baspacho solver on CUDA with parametrized batch size and sparsity settings', 'review check_baspacho function that generates random sparse matrices and verifies solver residuals', 'summarize the test_baspacho_cpu pytest function that runs 64 parametrized solver test cases', 'run the check_simple function to verify sparse matrix solve with given row pointers and column indices', 'review the SymbolicDecomposition class usage for creating numeric decomposition and solving linear systems', 'refactor the check_simple function to support custom sparse matrix values and batch sizes', 'test the check_lu_solver function with custom batch size and sparse matrix dimensions', 'run the test_lu_solver_1 pytest test for a 50x30 sparse matrix with 0.2 fill ratio', 'run the test_lu_solver_3 pytest test for a 300x90 sparse matrix with batch size 10', 'review how CusolverLUSolver is initialized, factored, and used to solve linear systems', 'refactor check_lu_solver to support irregular batch sizes smaller than init_batch_size', 'test the mat_vec CUDA extension for sparse matrix vector multiplication with batched tensors', 'test the tmat_vec CUDA extension for transposed sparse matrix vector multiplication', 'test the mult_MtM CUDA extension that computes A transpose times A for sparse matrices', 'test the apply_damping CUDA extension that scales and shifts diagonal elements of sparse matrices', 'test the check_mat_mult helper function with custom batch size rows cols and fill parameters']
```

Usage

```
{'test_check_lu_solver': 'test the check_lu_solver function with custom batch size and sparse matrix dimensions', 'run_test_lu_solver_1': 'run the test_lu_solver_1 pytest test for a 50x30 sparse matrix with 0.2 fill ratio', 'run_test_lu_solver_3': 'run the test_lu_solver_3 pytest test for a 300x90 sparse matrix with batch size 10', 'review_CusolverLUSolver_usage': 'review how CusolverLUSolver is initialized, factored, and used to solve linear systems', 'refactor_check_lu_solver': 'refactor check_lu_solver to support irregular batch sizes smaller than init_batch_size'}
```

## File: facebookresearch_theseus/tests/theseus_tests/extlib/test_mat_mult.py

Prompts

```
['run check_baspacho to validate sparse least squares solver with given batch size and fill ratio', 'test the baspacho solver on CPU with parametrized batch size and sparsity settings', 'test the baspacho solver on CUDA with parametrized batch size and sparsity settings', 'review check_baspacho function that generates random sparse matrices and verifies solver residuals', 'summarize the test_baspacho_cpu pytest function that runs 64 parametrized solver test cases', 'run the check_simple function to verify sparse matrix solve with given row pointers and column indices', 'review the SymbolicDecomposition class usage for creating numeric decomposition and solving linear systems', 'refactor the check_simple function to support custom sparse matrix values and batch sizes', 'test the check_lu_solver function with custom batch size and sparse matrix dimensions', 'run the test_lu_solver_1 pytest test for a 50x30 sparse matrix with 0.2 fill ratio', 'run the test_lu_solver_3 pytest test for a 300x90 sparse matrix with batch size 10', 'review how CusolverLUSolver is initialized, factored, and used to solve linear systems', 'refactor check_lu_solver to support irregular batch sizes smaller than init_batch_size', 'test the mat_vec CUDA extension for sparse matrix vector multiplication with batched tensors', 'test the tmat_vec CUDA extension for transposed sparse matrix vector multiplication', 'test the mult_MtM CUDA extension that computes A transpose times A for sparse matrices', 'test the apply_damping CUDA extension that scales and shifts diagonal elements of sparse matrices', 'test the check_mat_mult helper function with custom batch size rows cols and fill parameters']
```

Usage

```
{'test_sparse_mat_vec_multiply': 'test the mat_vec CUDA extension for sparse matrix vector multiplication with batched tensors', 'test_sparse_tmat_vec_multiply': 'test the tmat_vec CUDA extension for transposed sparse matrix vector multiplication', 'test_sparse_MtM_multiply': 'test the mult_MtM CUDA extension that computes A transpose times A for sparse matrices', 'test_apply_damping': 'test the apply_damping CUDA extension that scales and shifts diagonal elements of sparse matrices', 'test_check_mat_mult': 'test the check_mat_mult helper function with custom batch size rows cols and fill parameters'}
```

