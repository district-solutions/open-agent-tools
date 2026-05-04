# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/algotune/polynomial_real/best_program.py

Prompts

```
['run the polynomial solver to find real roots from a list of coefficients', 'solve for the real roots of a polynomial given its coefficients in descending order', 'validate a proposed list of polynomial roots against the reference solution', 'run the JIT-compiled JAX function to compute sorted real roots from coefficients', 'review the PolynomialReal class solve and is_solution methods for correctness', 'run the evaluator to compare an evolved polynomial solver against the AlgoTune baseline and calculate speedup', 'run a basic functionality check on an evolved polynomial solver to verify it runs without errors', 'run a thorough evaluation of an evolved polynomial solver with full baseline comparison and speedup metrics', 'run a function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'calculate the speedup ratio between a baseline implementation time and an evolved solution time', 'run the polynomial real roots solver on a list of coefficients using run_solver', 'refactor the PolynomialReal solve method to use JAX JIT compilation for faster root finding']
```

Usage

```
{'run_polynomial_solver': 'run the polynomial solver to find real roots from a list of coefficients', 'solve_polynomial_roots': 'solve for the real roots of a polynomial given its coefficients in descending order', 'validate_polynomial_solution': 'validate a proposed list of polynomial roots against the reference solution', 'run_jit_root_finder': 'run the JIT-compiled JAX function to compute sorted real roots from coefficients', 'review_polynomialreal_class': 'review the PolynomialReal class solve and is_solution methods for correctness'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/polynomial_real/evaluator.py

Prompts

```
['run the polynomial solver to find real roots from a list of coefficients', 'solve for the real roots of a polynomial given its coefficients in descending order', 'validate a proposed list of polynomial roots against the reference solution', 'run the JIT-compiled JAX function to compute sorted real roots from coefficients', 'review the PolynomialReal class solve and is_solution methods for correctness', 'run the evaluator to compare an evolved polynomial solver against the AlgoTune baseline and calculate speedup', 'run a basic functionality check on an evolved polynomial solver to verify it runs without errors', 'run a thorough evaluation of an evolved polynomial solver with full baseline comparison and speedup metrics', 'run a function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'calculate the speedup ratio between a baseline implementation time and an evolved solution time', 'run the polynomial real roots solver on a list of coefficients using run_solver', 'refactor the PolynomialReal solve method to use JAX JIT compilation for faster root finding']
```

Usage

```
{'evaluate_program': 'run the evaluator to compare an evolved polynomial solver against the AlgoTune baseline and calculate speedup', 'evaluate_stage1_program': 'run a basic functionality check on an evolved polynomial solver to verify it runs without errors', 'evaluate_stage2_program': 'run a thorough evaluation of an evolved polynomial solver with full baseline comparison and speedup metrics', 'run_with_timeout': 'run a function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'calculate_speedup': 'calculate the speedup ratio between a baseline implementation time and an evolved solution time'}
```

## File: algorithmicsuperintelligence_openevolve/examples/algotune/polynomial_real/initial_program.py

Prompts

```
['run the polynomial solver to find real roots from a list of coefficients', 'solve for the real roots of a polynomial given its coefficients in descending order', 'validate a proposed list of polynomial roots against the reference solution', 'run the JIT-compiled JAX function to compute sorted real roots from coefficients', 'review the PolynomialReal class solve and is_solution methods for correctness', 'run the evaluator to compare an evolved polynomial solver against the AlgoTune baseline and calculate speedup', 'run a basic functionality check on an evolved polynomial solver to verify it runs without errors', 'run a thorough evaluation of an evolved polynomial solver with full baseline comparison and speedup metrics', 'run a function with a configurable timeout using a thread pool executor and raise TimeoutError on expiry', 'calculate the speedup ratio between a baseline implementation time and an evolved solution time', 'run the polynomial real roots solver on a list of coefficients using run_solver', 'refactor the PolynomialReal solve method to use JAX JIT compilation for faster root finding']
```

Usage

```
{'run_polynomial_roots_solver': 'run the polynomial real roots solver on a list of coefficients using run_solver', 'solve_polynomial_roots': 'solve for the real roots of a polynomial given its coefficients in descending order', 'validate_polynomial_solution': 'validate a proposed list of polynomial roots against the reference solution using is_solution', 'refactor_solve_method': 'refactor the PolynomialReal solve method to use JAX JIT compilation for faster root finding', 'review_polynomialreal_class': 'review the PolynomialReal class solve and is_solution methods for correctness and performance'}
```

