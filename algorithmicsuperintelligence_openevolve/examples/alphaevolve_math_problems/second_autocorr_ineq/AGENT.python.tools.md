# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/second_autocorr_ineq/evaluator.py

Prompts

```
["run the evaluate function to dynamically import and score a candidate program's C2 solution against the benchmark", 'verify a C2 lower bound solution using piecewise linear integration on function values and autocorrelation norms', 'test the evaluate function by passing a path to a candidate program module that exports a run method', 'review the verify_c2_solution function to understand how L2, L1, and infinity norms are computed from autocorrelation', 'refactor the evaluate function to support alternative program import strategies or additional scoring metrics', 'run the C2Optimizer to find a lower bound for the C2 constant using JAX and optax', 'run the optimization entry point that returns optimized function values and the final C2 value', 'create a Hyperparameters dataclass to configure num_intervals, learning_rate, num_steps, and warmup_steps for optimization', 'compute the C2 ratio objective function using L2, L1, and infinity norms of the autoconvolution', 'perform a single JIT-compiled training step with gradient descent using Adam optimizer and cosine decay schedule']
```

Usage

```
{'run_evaluate_program': "run the evaluate function to dynamically import and score a candidate program's C2 solution against the benchmark", 'verify_c2_solution': 'verify a C2 lower bound solution using piecewise linear integration on function values and autocorrelation norms', 'test_evaluate': 'test the evaluate function by passing a path to a candidate program module that exports a run method', 'review_verify_c2_solution': 'review the verify_c2_solution function to understand how L2, L1, and infinity norms are computed from autocorrelation', 'refactor_evaluate': 'refactor the evaluate function to support alternative program import strategies or additional scoring metrics'}
```

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/second_autocorr_ineq/initial_program.py

Prompts

```
["run the evaluate function to dynamically import and score a candidate program's C2 solution against the benchmark", 'verify a C2 lower bound solution using piecewise linear integration on function values and autocorrelation norms', 'test the evaluate function by passing a path to a candidate program module that exports a run method', 'review the verify_c2_solution function to understand how L2, L1, and infinity norms are computed from autocorrelation', 'refactor the evaluate function to support alternative program import strategies or additional scoring metrics', 'run the C2Optimizer to find a lower bound for the C2 constant using JAX and optax', 'run the optimization entry point that returns optimized function values and the final C2 value', 'create a Hyperparameters dataclass to configure num_intervals, learning_rate, num_steps, and warmup_steps for optimization', 'compute the C2 ratio objective function using L2, L1, and infinity norms of the autoconvolution', 'perform a single JIT-compiled training step with gradient descent using Adam optimizer and cosine decay schedule']
```

Usage

```
{'run_optimization_c2': 'run the C2Optimizer to find a lower bound for the C2 constant using JAX and optax', 'run_entry_point': 'run the optimization entry point that returns optimized function values and the final C2 value', 'create_hyperparameters': 'create a Hyperparameters dataclass to configure num_intervals, learning_rate, num_steps, and warmup_steps for optimization', 'compute_objective_c2_ratio': 'compute the C2 ratio objective function using L2, L1, and infinity norms of the autoconvolution', 'train_step_gradient': 'perform a single JIT-compiled training step with gradient descent using Adam optimizer and cosine decay schedule'}
```

