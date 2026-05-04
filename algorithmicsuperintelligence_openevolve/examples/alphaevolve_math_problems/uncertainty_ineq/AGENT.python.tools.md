# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/uncertainty_ineq/evaluator.py

Prompts

```
['evaluate a Python program that solves the uncertainty inequality problem and returns its c4 bound score', 'compute the c4 bound and r_max values from Hermite polynomial coefficients for the uncertainty inequality', 'verify reported c4 and r_max values match recomputed results from given polynomial coefficients', 'build a Hermite polynomial combination where P(0) equals zero using given coefficients', 'find the largest positive real root of a polynomial divided by x squared', 'run the uncertainty optimizer to find the best C4 upper bound across multiple restart trials', 'create an UncertaintyOptimizer instance with custom hyperparameters for Hermite polynomial coefficient optimization', 'run a single optimization trial with noise-perturbed initial parameters using JAX JIT compilation', 'calculate the precise C4 upper bound and largest positive root from final optimization parameters', 'compute the C4 bound and r_max from a Hermite coefficient vector using polynomial root analysis']
```

Usage

```
{'evaluate_uncertainty_ineq_program': 'evaluate a Python program that solves the uncertainty inequality problem and returns its c4 bound score', 'compute_c4_and_rmax_from_coeffs': 'compute the c4 bound and r_max values from Hermite polynomial coefficients for the uncertainty inequality', 'verify_c4_solution_strict': 'verify reported c4 and r_max values match recomputed results from given polynomial coefficients', 'construct_hermite_polynomial_with_forced_zero': 'build a Hermite polynomial combination where P(0) equals zero using given coefficients', 'find_largest_positive_root_of_polynomial': 'find the largest positive real root of a polynomial divided by x squared'}
```

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/uncertainty_ineq/initial_program.py

Prompts

```
['evaluate a Python program that solves the uncertainty inequality problem and returns its c4 bound score', 'compute the c4 bound and r_max values from Hermite polynomial coefficients for the uncertainty inequality', 'verify reported c4 and r_max values match recomputed results from given polynomial coefficients', 'build a Hermite polynomial combination where P(0) equals zero using given coefficients', 'find the largest positive real root of a polynomial divided by x squared', 'run the uncertainty optimizer to find the best C4 upper bound across multiple restart trials', 'create an UncertaintyOptimizer instance with custom hyperparameters for Hermite polynomial coefficient optimization', 'run a single optimization trial with noise-perturbed initial parameters using JAX JIT compilation', 'calculate the precise C4 upper bound and largest positive root from final optimization parameters', 'compute the C4 bound and r_max from a Hermite coefficient vector using polynomial root analysis']
```

Usage

```
{'run_optimization': 'run the uncertainty optimizer to find the best C4 upper bound across multiple restart trials', 'create_optimizer': 'create an UncertaintyOptimizer instance with custom hyperparameters for Hermite polynomial coefficient optimization', 'run_single_trial': 'run a single optimization trial with noise-perturbed initial parameters using JAX JIT compilation', 'get_c4_from_params': 'calculate the precise C4 upper bound and largest positive root from final optimization parameters', 'compute_c4_from_hermite': 'compute the C4 bound and r_max from a Hermite coefficient vector using polynomial root analysis'}
```

