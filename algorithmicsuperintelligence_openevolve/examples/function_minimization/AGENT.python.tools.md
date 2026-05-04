# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/function_minimization/evaluator.py

Prompts

```
['run the evaluate function to score a program file across 10 trials against the known global minimum', 'run the evaluate_stage1 function to quickly validate a program runs and returns valid results', 'run the evaluate_stage2 function to perform a full 10-trial evaluation of a program file', 'run a function with a configurable timeout using ThreadPoolExecutor and raise TimeoutError on expiry', 'run safe_float to convert a value to float and return 0.0 on TypeError or ValueError', 'run the random search algorithm to find the minimum of the evaluation function within bounds', 'evaluate the complex trigonometric function at a given x and y coordinate pair', 'run the search entry point that calls search algorithm and returns the best result', 'refactor the search algorithm to use gradient descent instead of random search for better convergence', 'review the evaluate function to understand its trigonometric and polynomial components']
```

Usage

```
{'run_evaluate_program': 'run the evaluate function to score a program file across 10 trials against the known global minimum', 'run_evaluate_stage1': 'run the evaluate_stage1 function to quickly validate a program runs and returns valid results', 'run_evaluate_stage2': 'run the evaluate_stage2 function to perform a full 10-trial evaluation of a program file', 'run_with_timeout': 'run a function with a configurable timeout using ThreadPoolExecutor and raise TimeoutError on expiry', 'run_safe_float': 'run safe_float to convert a value to float and return 0.0 on TypeError or ValueError'}
```

## File: algorithmicsuperintelligence_openevolve/examples/function_minimization/initial_program.py

Prompts

```
['run the evaluate function to score a program file across 10 trials against the known global minimum', 'run the evaluate_stage1 function to quickly validate a program runs and returns valid results', 'run the evaluate_stage2 function to perform a full 10-trial evaluation of a program file', 'run a function with a configurable timeout using ThreadPoolExecutor and raise TimeoutError on expiry', 'run safe_float to convert a value to float and return 0.0 on TypeError or ValueError', 'run the random search algorithm to find the minimum of the evaluation function within bounds', 'evaluate the complex trigonometric function at a given x and y coordinate pair', 'run the search entry point that calls search algorithm and returns the best result', 'refactor the search algorithm to use gradient descent instead of random search for better convergence', 'review the evaluate function to understand its trigonometric and polynomial components']
```

Usage

```
{'run_search_algorithm': 'run the random search algorithm to find the minimum of the evaluation function within bounds', 'evaluate_function_at_point': 'evaluate the complex trigonometric function at a given x and y coordinate pair', 'run_search_entry': 'run the search entry point that calls search algorithm and returns the best result', 'refactor_search_algorithm': 'refactor the search algorithm to use gradient descent instead of random search for better convergence', 'review_evaluate_function': 'review the evaluate function to understand its trigonometric and polynomial components'}
```

