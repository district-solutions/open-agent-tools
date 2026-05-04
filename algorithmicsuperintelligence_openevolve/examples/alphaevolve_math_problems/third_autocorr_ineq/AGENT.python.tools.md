# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/third_autocorr_ineq/evaluator.py

Prompts

```
['run the evaluate function to dynamically import a program module and score its C3 autocorrelation solution', 'verify a C3 upper bound solution by recomputing the autocorrelation ratio from function values', 'run the evaluate function to import a candidate program, verify its C3 output, and return a combined score', 'verify the autocorrelation inequality solution by checking the computed C3 value matches the reported value', 'run the evaluate function to score a program against the known C3 benchmark bound of 1.4556', 'run the C3 optimizer to find an upper bound for the C3 constant using JAX and optax', 'create a Hyperparameters dataclass to configure num_intervals, learning_rate, num_steps, and warmup_steps for optimization', 'review the C3Optimizer _objective_fn method that computes the C3 ratio using FFT-based autoconvolution', 'refactor the C3Optimizer train_step method to customize gradient updates with optax adam optimizer', 'summarize the run entry point function that orchestrates C3 optimization and returns optimized function values']
```

Usage

```
{'run_evaluate_program': 'run the evaluate function to dynamically import a program module and score its C3 autocorrelation solution', 'verify_c3_solution': 'verify a C3 upper bound solution by recomputing the autocorrelation ratio from function values', 'run_evaluate_and_verify': 'run the evaluate function to import a candidate program, verify its C3 output, and return a combined score', 'verify_autocorrelation_bounds': 'verify the autocorrelation inequality solution by checking the computed C3 value matches the reported value', 'run_evaluate_with_benchmark': 'run the evaluate function to score a program against the known C3 benchmark bound of 1.4556'}
```

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/third_autocorr_ineq/initial_program.py

Prompts

```
['run the evaluate function to dynamically import a program module and score its C3 autocorrelation solution', 'verify a C3 upper bound solution by recomputing the autocorrelation ratio from function values', 'run the evaluate function to import a candidate program, verify its C3 output, and return a combined score', 'verify the autocorrelation inequality solution by checking the computed C3 value matches the reported value', 'run the evaluate function to score a program against the known C3 benchmark bound of 1.4556', 'run the C3 optimizer to find an upper bound for the C3 constant using JAX and optax', 'create a Hyperparameters dataclass to configure num_intervals, learning_rate, num_steps, and warmup_steps for optimization', 'review the C3Optimizer _objective_fn method that computes the C3 ratio using FFT-based autoconvolution', 'refactor the C3Optimizer train_step method to customize gradient updates with optax adam optimizer', 'summarize the run entry point function that orchestrates C3 optimization and returns optimized function values']
```

Usage

```
{'run_C3_optimization': 'run the C3 optimizer to find an upper bound for the C3 constant using JAX and optax', 'create_Hyperparameters': 'create a Hyperparameters dataclass to configure num_intervals, learning_rate, num_steps, and warmup_steps for optimization', 'review_C3Optimizer_objective_fn': 'review the C3Optimizer _objective_fn method that computes the C3 ratio using FFT-based autoconvolution', 'refactor_C3Optimizer_train_step': 'refactor the C3Optimizer train_step method to customize gradient updates with optax adam optimizer', 'summarize_run_entry_point': 'summarize the run entry point function that orchestrates C3 optimization and returns optimized function values'}
```

