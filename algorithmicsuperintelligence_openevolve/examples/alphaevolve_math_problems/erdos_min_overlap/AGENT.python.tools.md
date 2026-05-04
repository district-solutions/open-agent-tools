# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/erdos_min_overlap/evaluator.py

Prompts

```
['run the evaluate function to dynamically import and score a program solving the erdos minimum overlap problem', 'verify a C5 upper bound solution by checking h values are in [0,1] and integral equals 1', 'test the evaluate function with a program path that returns h_values, c5_bound, and n_points', 'review the verify_c5_solution function to understand the constraint checks for shape, range, integral, and correlation', 'refactor the evaluate function to support a different benchmark constant or scoring formula', 'run the ErdosOptimizer to find a step function that minimizes the maximum overlap integral', 'create a Hyperparameters dataclass to configure num_intervals, learning_rate, num_steps, and penalty_strength for optimization', 'review the ErdosOptimizer _objective_fn method that computes correlation loss via FFT and integral constraint penalty', 'summarize the run function that creates an ErdosOptimizer with default hyperparameters and executes optimization', 'refactor the ErdosOptimizer class to support custom domain width or alternative optimization algorithms']
```

Usage

```
{'run_evaluate_program': 'run the evaluate function to dynamically import and score a program solving the erdos minimum overlap problem', 'verify_c5_solution': 'verify a C5 upper bound solution by checking h values are in [0,1] and integral equals 1', 'test_evaluate': 'test the evaluate function with a program path that returns h_values, c5_bound, and n_points', 'review_verify_c5_solution': 'review the verify_c5_solution function to understand the constraint checks for shape, range, integral, and correlation', 'refactor_evaluate': 'refactor the evaluate function to support a different benchmark constant or scoring formula'}
```

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/erdos_min_overlap/initial_program.py

Prompts

```
['run the evaluate function to dynamically import and score a program solving the erdos minimum overlap problem', 'verify a C5 upper bound solution by checking h values are in [0,1] and integral equals 1', 'test the evaluate function with a program path that returns h_values, c5_bound, and n_points', 'review the verify_c5_solution function to understand the constraint checks for shape, range, integral, and correlation', 'refactor the evaluate function to support a different benchmark constant or scoring formula', 'run the ErdosOptimizer to find a step function that minimizes the maximum overlap integral', 'create a Hyperparameters dataclass to configure num_intervals, learning_rate, num_steps, and penalty_strength for optimization', 'review the ErdosOptimizer _objective_fn method that computes correlation loss via FFT and integral constraint penalty', 'summarize the run function that creates an ErdosOptimizer with default hyperparameters and executes optimization', 'refactor the ErdosOptimizer class to support custom domain width or alternative optimization algorithms']
```

Usage

```
{'run_optimization': 'run the ErdosOptimizer to find a step function that minimizes the maximum overlap integral', 'create_hyperparameters': 'create a Hyperparameters dataclass to configure num_intervals, learning_rate, num_steps, and penalty_strength for optimization', 'review_objective_fn': 'review the ErdosOptimizer _objective_fn method that computes correlation loss via FFT and integral constraint penalty', 'summarize_run': 'summarize the run function that creates an ErdosOptimizer with default hyperparameters and executes optimization', 'refactor_erdos_optimizer': 'refactor the ErdosOptimizer class to support custom domain width or alternative optimization algorithms'}
```

