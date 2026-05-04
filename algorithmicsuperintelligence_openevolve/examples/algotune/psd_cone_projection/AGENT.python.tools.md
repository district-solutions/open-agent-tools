# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/algotune/psd_cone_projection/best_program.py

Prompts

```
['run the PSDConeProjection solve method to project a symmetric matrix onto the PSD cone', 'test a proposed PSD cone projection solution using the is_solution method', 'run the run_solver function to solve a PSD cone projection problem', 'review the PSDConeProjection class solve and is_solution methods for correctness', 'refactor the PSDConeProjection solve method to use truncated eigendecomposition for large matrices', 'run the evaluator to compare an evolved PSD cone projection solver against the AlgoTune baseline and measure speedup', 'run the stage 1 cascade evaluation to check basic functionality of an evolved solver', 'run the stage 2 cascade evaluation for thorough testing of an evolved solver against the baseline', 'calculate the speedup ratio between a baseline implementation time and an evolved solution time', 'run a function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'refactor the PSDConeProjection solve method to use eigh instead of eig for symmetric matrices', 'review the is_solution method to verify symmetry, positive semidefiniteness, and optimality checks']
```

Usage

```
{'solve_psd_cone_projection': 'run the PSDConeProjection solve method to project a symmetric matrix onto the PSD cone', 'validate_psd_solution': 'test a proposed PSD cone projection solution using the is_solution method', 'run_psd_solver': 'run the run_solver function to solve a PSD cone projection problem', 'review_psd_cone_class': 'review the PSDConeProjection class solve and is_solution methods for correctness', 'refactor_psd_eigendecomposition': 'refactor the PSDConeProjection solve method to use truncated eigendecomposition for large matrices'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/psd_cone_projection/evaluator.py

Prompts

```
['run the PSDConeProjection solve method to project a symmetric matrix onto the PSD cone', 'test a proposed PSD cone projection solution using the is_solution method', 'run the run_solver function to solve a PSD cone projection problem', 'review the PSDConeProjection class solve and is_solution methods for correctness', 'refactor the PSDConeProjection solve method to use truncated eigendecomposition for large matrices', 'run the evaluator to compare an evolved PSD cone projection solver against the AlgoTune baseline and measure speedup', 'run the stage 1 cascade evaluation to check basic functionality of an evolved solver', 'run the stage 2 cascade evaluation for thorough testing of an evolved solver against the baseline', 'calculate the speedup ratio between a baseline implementation time and an evolved solution time', 'run a function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'refactor the PSDConeProjection solve method to use eigh instead of eig for symmetric matrices', 'review the is_solution method to verify symmetry, positive semidefiniteness, and optimality checks']
```

Usage

```
{'evaluate_program': 'run the evaluator to compare an evolved PSD cone projection solver against the AlgoTune baseline and measure speedup', 'evaluate_stage1_program': 'run the stage 1 cascade evaluation to check basic functionality of an evolved solver', 'evaluate_stage2_program': 'run the stage 2 cascade evaluation for thorough testing of an evolved solver against the baseline', 'calculate_speedup': 'calculate the speedup ratio between a baseline implementation time and an evolved solution time', 'run_with_timeout': 'run a function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/psd_cone_projection/initial_program.py

Prompts

```
['run the PSDConeProjection solve method to project a symmetric matrix onto the PSD cone', 'test a proposed PSD cone projection solution using the is_solution method', 'run the run_solver function to solve a PSD cone projection problem', 'review the PSDConeProjection class solve and is_solution methods for correctness', 'refactor the PSDConeProjection solve method to use truncated eigendecomposition for large matrices', 'run the evaluator to compare an evolved PSD cone projection solver against the AlgoTune baseline and measure speedup', 'run the stage 1 cascade evaluation to check basic functionality of an evolved solver', 'run the stage 2 cascade evaluation for thorough testing of an evolved solver against the baseline', 'calculate the speedup ratio between a baseline implementation time and an evolved solution time', 'run a function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'refactor the PSDConeProjection solve method to use eigh instead of eig for symmetric matrices', 'review the is_solution method to verify symmetry, positive semidefiniteness, and optimality checks']
```

Usage

```
{'solve_psd_cone_projection': 'run the PSDConeProjection solver to project a symmetric matrix onto the positive semidefinite cone', 'validate_psd_solution': 'test a proposed PSD cone projection solution against the reference solution for correctness', 'run_psd_solver': 'run the run_solver function to solve a PSD cone projection problem with a given matrix', 'refactor_solve_method': 'refactor the PSDConeProjection solve method to use eigh instead of eig for symmetric matrices', 'review_is_solution_checks': 'review the is_solution method to verify symmetry, positive semidefiniteness, and optimality checks'}
```

