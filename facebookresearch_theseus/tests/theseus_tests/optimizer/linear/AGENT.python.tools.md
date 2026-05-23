# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/tests/theseus_tests/optimizer/linear/test_baspacho_sparse_solver.py

Prompts

```
['test the check_sparse_solver function to verify sparse solver correctness on CPU or CUDA devices', 'run the parametrized CPU test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'run the abbreviated CPU test for the baspacho sparse solver with batch size 128', 'run the parametrized CUDA test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'review the check_sparse_solver function which validates AtA x equals Atb using torch testing assertions', 'test the CholmodSparseSolver by solving a sparse linear system with damping and verifying correctness', 'build a sparse matrix in CSR format with random data for a given batch size', 'create a CholmodSparseSolver with an Objective, VariableOrdering, and damping parameter', 'run the solver to solve the linear system and return the solution vector', 'review the sparse solver correctness by checking AtA x + damping x equals Atb', 'test the LUDenseSolver by solving a batched linear system and verifying the solution error', 'test the CholeskyDenseSolver by solving a batched linear system and verifying the solution error', 'test dense solver solve with ellipsoidal and spherical damping options on a linear system', 'test that dense solvers handle singular matrices in a batch by warning and zeroing results', 'create a batched linear system with AtA, Atb, and ground truth x tensors for solver testing', 'test the LUCudaSparseSolver with sparse matrix data and verify solutions match expected AtA results', 'test the LUCudaSparseSolver multistep gradient computation and validate backward pass correctness', 'test the LUCudaSparseSolver raises RuntimeError when insufficient solver contexts are provided', 'build a sparse matrix with CSR format using column indices and row pointers for batched solving', 'run the LUCudaSparseSolver on CUDA with configurable damping and ellipsoidal damping options']
```

Usage

```
{'test_check_sparse_solver': 'test the check_sparse_solver function to verify sparse solver correctness on CPU or CUDA devices', 'run_test_baspacho_solver_cpu_full': 'run the parametrized CPU test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'run_test_baspacho_solver_cpu_abriged': 'run the abbreviated CPU test for the baspacho sparse solver with batch size 128', 'run_test_baspacho_solver_cuda': 'run the parametrized CUDA test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'review_check_sparse_solver': 'review the check_sparse_solver function which validates AtA x equals Atb using torch testing assertions'}
```

## File: facebookresearch_theseus/tests/theseus_tests/optimizer/linear/test_cholmod_sparse_solver.py

Prompts

```
['test the check_sparse_solver function to verify sparse solver correctness on CPU or CUDA devices', 'run the parametrized CPU test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'run the abbreviated CPU test for the baspacho sparse solver with batch size 128', 'run the parametrized CUDA test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'review the check_sparse_solver function which validates AtA x equals Atb using torch testing assertions', 'test the CholmodSparseSolver by solving a sparse linear system with damping and verifying correctness', 'build a sparse matrix in CSR format with random data for a given batch size', 'create a CholmodSparseSolver with an Objective, VariableOrdering, and damping parameter', 'run the solver to solve the linear system and return the solution vector', 'review the sparse solver correctness by checking AtA x + damping x equals Atb', 'test the LUDenseSolver by solving a batched linear system and verifying the solution error', 'test the CholeskyDenseSolver by solving a batched linear system and verifying the solution error', 'test dense solver solve with ellipsoidal and spherical damping options on a linear system', 'test that dense solvers handle singular matrices in a batch by warning and zeroing results', 'create a batched linear system with AtA, Atb, and ground truth x tensors for solver testing', 'test the LUCudaSparseSolver with sparse matrix data and verify solutions match expected AtA results', 'test the LUCudaSparseSolver multistep gradient computation and validate backward pass correctness', 'test the LUCudaSparseSolver raises RuntimeError when insufficient solver contexts are provided', 'build a sparse matrix with CSR format using column indices and row pointers for batched solving', 'run the LUCudaSparseSolver on CUDA with configurable damping and ellipsoidal damping options']
```

Usage

```
{'test_CholmodSparseSolver': 'test the CholmodSparseSolver by solving a sparse linear system with damping and verifying correctness', 'build_sparse_matrix': 'build a sparse matrix in CSR format with random data for a given batch size', 'create_CholmodSparseSolver': 'create a CholmodSparseSolver with an Objective, VariableOrdering, and damping parameter', 'run_sparse_solver_solve': 'run the solver to solve the linear system and return the solution vector', 'review_sparse_solver_correctness': 'review the sparse solver correctness by checking AtA x + damping x equals Atb'}
```

## File: facebookresearch_theseus/tests/theseus_tests/optimizer/linear/test_dense_solver.py

Prompts

```
['test the check_sparse_solver function to verify sparse solver correctness on CPU or CUDA devices', 'run the parametrized CPU test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'run the abbreviated CPU test for the baspacho sparse solver with batch size 128', 'run the parametrized CUDA test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'review the check_sparse_solver function which validates AtA x equals Atb using torch testing assertions', 'test the CholmodSparseSolver by solving a sparse linear system with damping and verifying correctness', 'build a sparse matrix in CSR format with random data for a given batch size', 'create a CholmodSparseSolver with an Objective, VariableOrdering, and damping parameter', 'run the solver to solve the linear system and return the solution vector', 'review the sparse solver correctness by checking AtA x + damping x equals Atb', 'test the LUDenseSolver by solving a batched linear system and verifying the solution error', 'test the CholeskyDenseSolver by solving a batched linear system and verifying the solution error', 'test dense solver solve with ellipsoidal and spherical damping options on a linear system', 'test that dense solvers handle singular matrices in a batch by warning and zeroing results', 'create a batched linear system with AtA, Atb, and ground truth x tensors for solver testing', 'test the LUCudaSparseSolver with sparse matrix data and verify solutions match expected AtA results', 'test the LUCudaSparseSolver multistep gradient computation and validate backward pass correctness', 'test the LUCudaSparseSolver raises RuntimeError when insufficient solver contexts are provided', 'build a sparse matrix with CSR format using column indices and row pointers for batched solving', 'run the LUCudaSparseSolver on CUDA with configurable damping and ellipsoidal damping options']
```

Usage

```
{'test_LUDenseSolver': 'test the LUDenseSolver by solving a batched linear system and verifying the solution error', 'test_CholeskyDenseSolver': 'test the CholeskyDenseSolver by solving a batched linear system and verifying the solution error', 'test_solver_damping': 'test dense solver solve with ellipsoidal and spherical damping options on a linear system', 'test_handle_singular': 'test that dense solvers handle singular matrices in a batch by warning and zeroing results', 'create_linear_system': 'create a batched linear system with AtA, Atb, and ground truth x tensors for solver testing'}
```

## File: facebookresearch_theseus/tests/theseus_tests/optimizer/linear/test_lu_cuda_sparse_solver.py

Prompts

```
['test the check_sparse_solver function to verify sparse solver correctness on CPU or CUDA devices', 'run the parametrized CPU test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'run the abbreviated CPU test for the baspacho sparse solver with batch size 128', 'run the parametrized CUDA test for the baspacho sparse solver across multiple batch sizes and fill ratios', 'review the check_sparse_solver function which validates AtA x equals Atb using torch testing assertions', 'test the CholmodSparseSolver by solving a sparse linear system with damping and verifying correctness', 'build a sparse matrix in CSR format with random data for a given batch size', 'create a CholmodSparseSolver with an Objective, VariableOrdering, and damping parameter', 'run the solver to solve the linear system and return the solution vector', 'review the sparse solver correctness by checking AtA x + damping x equals Atb', 'test the LUDenseSolver by solving a batched linear system and verifying the solution error', 'test the CholeskyDenseSolver by solving a batched linear system and verifying the solution error', 'test dense solver solve with ellipsoidal and spherical damping options on a linear system', 'test that dense solvers handle singular matrices in a batch by warning and zeroing results', 'create a batched linear system with AtA, Atb, and ground truth x tensors for solver testing', 'test the LUCudaSparseSolver with sparse matrix data and verify solutions match expected AtA results', 'test the LUCudaSparseSolver multistep gradient computation and validate backward pass correctness', 'test the LUCudaSparseSolver raises RuntimeError when insufficient solver contexts are provided', 'build a sparse matrix with CSR format using column indices and row pointers for batched solving', 'run the LUCudaSparseSolver on CUDA with configurable damping and ellipsoidal damping options']
```

Usage

```
{'test_LUCudaSparseSolver': 'test the LUCudaSparseSolver with sparse matrix data and verify solutions match expected AtA results', 'test_multistep_gradient': 'test the LUCudaSparseSolver multistep gradient computation and validate backward pass correctness', 'test_multistep_exception': 'test the LUCudaSparseSolver raises RuntimeError when insufficient solver contexts are provided', 'build_sparse_mat': 'build a sparse matrix with CSR format using column indices and row pointers for batched solving', 'run_cuda_sparse_solver': 'run the LUCudaSparseSolver on CUDA with configurable damping and ellipsoidal damping options'}
```

