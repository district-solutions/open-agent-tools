# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/algotune/lu_factorization/best_program.py

Prompts

```
['run the lu factorization solver on a square matrix and return P, L, U matrices', 'compute the lu factorization of a square matrix using scipy with optimized pivoting', 'validate an lu factorization solution by checking permutation, triangular structure, and reconstruction', 'review the LUFactorization class solve and is_solution methods for correctness and performance', 'refactor the LUFactorization solve method to support block decomposition or jit compilation', 'run the evaluate function to compare an evolved LU factorization solution against the AlgoTune baseline and measure speedup', 'run the stage 1 cascade evaluation to check basic functionality of an evolved LU factorization solver', 'run the stage 2 cascade evaluation for thorough testing of an evolved LU factorization solver', 'calculate the speedup ratio between a baseline time and an evolved solution time for LU factorization', 'run any function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'test the LUFactorization class solve method with a sample square matrix and verify correctness']
```

Usage

```
{'run_lu_factorization_solver': 'run the lu factorization solver on a square matrix and return P, L, U matrices', 'solve_lu_factorization': 'compute the lu factorization of a square matrix using scipy with optimized pivoting', 'validate_lu_solution': 'validate an lu factorization solution by checking permutation, triangular structure, and reconstruction', 'review_lu_factorization_class': 'review the LUFactorization class solve and is_solution methods for correctness and performance', 'refactor_lu_factorization_solve': 'refactor the LUFactorization solve method to support block decomposition or jit compilation'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/lu_factorization/evaluator.py

Prompts

```
['run the lu factorization solver on a square matrix and return P, L, U matrices', 'compute the lu factorization of a square matrix using scipy with optimized pivoting', 'validate an lu factorization solution by checking permutation, triangular structure, and reconstruction', 'review the LUFactorization class solve and is_solution methods for correctness and performance', 'refactor the LUFactorization solve method to support block decomposition or jit compilation', 'run the evaluate function to compare an evolved LU factorization solution against the AlgoTune baseline and measure speedup', 'run the stage 1 cascade evaluation to check basic functionality of an evolved LU factorization solver', 'run the stage 2 cascade evaluation for thorough testing of an evolved LU factorization solver', 'calculate the speedup ratio between a baseline time and an evolved solution time for LU factorization', 'run any function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'test the LUFactorization class solve method with a sample square matrix and verify correctness']
```

Usage

```
{'evaluate_program': 'run the evaluate function to compare an evolved LU factorization solution against the AlgoTune baseline and measure speedup', 'evaluate_stage1_program': 'run the stage 1 cascade evaluation to check basic functionality of an evolved LU factorization solver', 'evaluate_stage2_program': 'run the stage 2 cascade evaluation for thorough testing of an evolved LU factorization solver', 'calculate_speedup': 'calculate the speedup ratio between a baseline time and an evolved solution time for LU factorization', 'run_with_timeout': 'run any function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/lu_factorization/initial_program.py

Prompts

```
['run the lu factorization solver on a square matrix and return P, L, U matrices', 'compute the lu factorization of a square matrix using scipy with optimized pivoting', 'validate an lu factorization solution by checking permutation, triangular structure, and reconstruction', 'review the LUFactorization class solve and is_solution methods for correctness and performance', 'refactor the LUFactorization solve method to support block decomposition or jit compilation', 'run the evaluate function to compare an evolved LU factorization solution against the AlgoTune baseline and measure speedup', 'run the stage 1 cascade evaluation to check basic functionality of an evolved LU factorization solver', 'run the stage 2 cascade evaluation for thorough testing of an evolved LU factorization solver', 'calculate the speedup ratio between a baseline time and an evolved solution time for LU factorization', 'run any function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'test the LUFactorization class solve method with a sample square matrix and verify correctness']
```

Usage

```
{'run_lu_factorization_solver': 'run the LUFactorization solver to compute P, L, U matrices from a square input matrix', 'solve_lu_factorization': 'solve the LU factorization problem by decomposing matrix A into permutation, lower, and upper triangular matrices', 'validate_lu_solution': 'validate an LU factorization solution by checking P, L, U matrices reconstruct the original matrix', 'test_lu_factorization': 'test the LUFactorization class solve method with a sample square matrix and verify correctness', 'refactor_lu_factorization_solve': 'refactor the LUFactorization solve method to use block LU decomposition for better cache utilization'}
```

