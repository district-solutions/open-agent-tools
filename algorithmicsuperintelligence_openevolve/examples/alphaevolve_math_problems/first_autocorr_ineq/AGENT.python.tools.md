# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/first_autocorr_ineq/evaluator.py

Prompts

```
['run the evaluate function to dynamically import and score a candidate program module', 'verify an autocorrelation solution by recomputing C1 from function values and checking consistency', 'test the evaluate function by passing a path to a candidate program module', 'review the verify_autocorrelation_solution function to understand shape and non-negativity checks', 'summarize the evaluate function flow including dynamic import, execution, and scoring', 'run the autocorrelation optimization to find the minimal C1 constant using JAX and optax', 'create a Hyperparameters dataclass with configurable num_intervals, learning_rate, num_steps, and warmup_steps', 'build an AutocorrelationOptimizer instance that minimizes the C1 ratio via gradient descent with Adam', 'review the _objective_fn method that computes the C1 ratio using FFT-based autocorrelation', 'summarize the train_step method that performs a single JIT-compiled gradient update step']
```

Usage

```
{'run_evaluate_program': 'run the evaluate function to dynamically import and score a candidate program module', 'verify_autocorrelation_solution': 'verify an autocorrelation solution by recomputing C1 from function values and checking consistency', 'test_evaluate_with_program': 'test the evaluate function by passing a path to a candidate program module', 'review_verify_autocorrelation': 'review the verify_autocorrelation_solution function to understand shape and non-negativity checks', 'summarize_evaluate_flow': 'summarize the evaluate function flow including dynamic import, execution, and scoring'}
```

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/first_autocorr_ineq/initial_program.py

Prompts

```
['run the evaluate function to dynamically import and score a candidate program module', 'verify an autocorrelation solution by recomputing C1 from function values and checking consistency', 'test the evaluate function by passing a path to a candidate program module', 'review the verify_autocorrelation_solution function to understand shape and non-negativity checks', 'summarize the evaluate function flow including dynamic import, execution, and scoring', 'run the autocorrelation optimization to find the minimal C1 constant using JAX and optax', 'create a Hyperparameters dataclass with configurable num_intervals, learning_rate, num_steps, and warmup_steps', 'build an AutocorrelationOptimizer instance that minimizes the C1 ratio via gradient descent with Adam', 'review the _objective_fn method that computes the C1 ratio using FFT-based autocorrelation', 'summarize the train_step method that performs a single JIT-compiled gradient update step']
```

Usage

```
{'run_optimization': 'run the autocorrelation optimization to find the minimal C1 constant using JAX and optax', 'create_hyperparameters': 'create a Hyperparameters dataclass with configurable num_intervals, learning_rate, num_steps, and warmup_steps', 'build_optimizer': 'build an AutocorrelationOptimizer instance that minimizes the C1 ratio via gradient descent with Adam', 'review_objective_fn': 'review the _objective_fn method that computes the C1 ratio using FFT-based autocorrelation', 'summarize_train_step': 'summarize the train_step method that performs a single JIT-compiled gradient update step'}
```

