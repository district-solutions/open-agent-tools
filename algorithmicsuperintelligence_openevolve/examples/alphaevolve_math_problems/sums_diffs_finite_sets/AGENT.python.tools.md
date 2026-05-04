# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/sums_diffs_finite_sets/evaluator.py

Prompts

```
['evaluate a python program that solves the sums and differences of finite sets problem and returns the C6 bound score', 'verify a C6 lower bound solution by checking the numpy array constraints and recomputing the bound', 'run the full evaluation pipeline by importing a program module and verifying its C6 solution output', 'review the evaluate function to understand how it dynamically imports and scores candidate programs', 'test the verify_c6_solution function with a numpy array and expected C6 bound value', 'run the simulated annealing search to find the best C6 lower bound for finite sets', 'run a single simulated annealing trial with a given random key and hyperparameters', 'calculate the C6 lower bound objective function value for a given set mask', 'perform one step of simulated annealing with Metropolis acceptance criterion on the current mask', 'configure the search hyperparameters including max integer, restarts, steps, and initial temperature']
```

Usage

```
{'evaluate_program': 'evaluate a python program that solves the sums and differences of finite sets problem and returns the C6 bound score', 'verify_c6_solution': 'verify a C6 lower bound solution by checking the numpy array constraints and recomputing the bound', 'run_evaluation_pipeline': 'run the full evaluation pipeline by importing a program module and verifying its C6 solution output', 'review_evaluate_function': 'review the evaluate function to understand how it dynamically imports and scores candidate programs', 'test_verify_c6_solution': 'test the verify_c6_solution function with a numpy array and expected C6 bound value'}
```

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/sums_diffs_finite_sets/initial_program.py

Prompts

```
['evaluate a python program that solves the sums and differences of finite sets problem and returns the C6 bound score', 'verify a C6 lower bound solution by checking the numpy array constraints and recomputing the bound', 'run the full evaluation pipeline by importing a program module and verifying its C6 solution output', 'review the evaluate function to understand how it dynamically imports and scores candidate programs', 'test the verify_c6_solution function with a numpy array and expected C6 bound value', 'run the simulated annealing search to find the best C6 lower bound for finite sets', 'run a single simulated annealing trial with a given random key and hyperparameters', 'calculate the C6 lower bound objective function value for a given set mask', 'perform one step of simulated annealing with Metropolis acceptance criterion on the current mask', 'configure the search hyperparameters including max integer, restarts, steps, and initial temperature']
```

Usage

```
{'run_C6_search': 'run the simulated annealing search to find the best C6 lower bound for finite sets', 'run_single_trial': 'run a single simulated annealing trial with a given random key and hyperparameters', 'calculate_C6_objective': 'calculate the C6 lower bound objective function value for a given set mask', 'perform_anneal_step': 'perform one step of simulated annealing with Metropolis acceptance criterion on the current mask', 'configure_hyperparameters': 'configure the search hyperparameters including max integer, restarts, steps, and initial temperature'}
```

