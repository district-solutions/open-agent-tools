# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/3SATTime/evaluate.py

Prompts

```
['run the DPLL solver on a pickled 3SAT dataset and print correctness metrics', 'run evaluate_dpll with a custom pickle file path to evaluate 3SAT formulas', 'test the evaluate_dpll function against a known 3SAT dataset and verify decision counts', 'refactor evaluate_dpll to accept the dataset path as a command-line argument instead of hardcoding it', 'review the evaluate_dpll function for early return behavior on incorrect solver results', 'run the heuristic_fn to randomly select an unassigned variable from 3SAT clauses and assign True', 'test the heuristic_fn with sample clauses and assignments to verify variable selection and True assignment', 'review the heuristic_fn to understand how it selects unassigned variables using a fixed random seed', 'refactor the heuristic_fn to support configurable random seeds instead of the hardcoded seed value of 10', 'summarize the heuristic_fn which returns a randomly chosen unassigned variable with a True value for 3SAT solving', 'create a DPLL solver instance with clauses and a heuristic function then call solve to find a satisfying assignment', 'use DPLL.is_satisfied_clause to check if a clause is satisfied given current variable assignments', 'use DPLL.is_conflicted_clause to detect if all literals in a clause evaluate to False under current assignments', 'use DPLL.is_unit_clause to identify clauses with exactly one unassigned literal for unit propagation', 'use DPLL.num_new_clauses to simulate assigning a variable and score the resulting clause reduction']
```

Usage

```
{'run_evaluate_dpll': 'run the DPLL solver on a pickled 3SAT dataset and print correctness metrics', 'run_evaluate_dpll_with_custom_path': 'run evaluate_dpll with a custom pickle file path to evaluate 3SAT formulas', 'test_evaluate_dpll': 'test the evaluate_dpll function against a known 3SAT dataset and verify decision counts', 'refactor_evaluate_dpll': 'refactor evaluate_dpll to accept the dataset path as a command-line argument instead of hardcoding it', 'review_evaluate_dpll': 'review the evaluate_dpll function for early return behavior on incorrect solver results'}
```

## File: facebookresearch_mlgym/data/3SATTime/heuristic.py

Prompts

```
['run the DPLL solver on a pickled 3SAT dataset and print correctness metrics', 'run evaluate_dpll with a custom pickle file path to evaluate 3SAT formulas', 'test the evaluate_dpll function against a known 3SAT dataset and verify decision counts', 'refactor evaluate_dpll to accept the dataset path as a command-line argument instead of hardcoding it', 'review the evaluate_dpll function for early return behavior on incorrect solver results', 'run the heuristic_fn to randomly select an unassigned variable from 3SAT clauses and assign True', 'test the heuristic_fn with sample clauses and assignments to verify variable selection and True assignment', 'review the heuristic_fn to understand how it selects unassigned variables using a fixed random seed', 'refactor the heuristic_fn to support configurable random seeds instead of the hardcoded seed value of 10', 'summarize the heuristic_fn which returns a randomly chosen unassigned variable with a True value for 3SAT solving', 'create a DPLL solver instance with clauses and a heuristic function then call solve to find a satisfying assignment', 'use DPLL.is_satisfied_clause to check if a clause is satisfied given current variable assignments', 'use DPLL.is_conflicted_clause to detect if all literals in a clause evaluate to False under current assignments', 'use DPLL.is_unit_clause to identify clauses with exactly one unassigned literal for unit propagation', 'use DPLL.num_new_clauses to simulate assigning a variable and score the resulting clause reduction']
```

Usage

```
{'run_heuristic_fn': 'run the heuristic_fn to randomly select an unassigned variable from 3SAT clauses and assign True', 'test_heuristic_fn': 'test the heuristic_fn with sample clauses and assignments to verify variable selection and True assignment', 'review_heuristic_fn': 'review the heuristic_fn to understand how it selects unassigned variables using a fixed random seed', 'refactor_heuristic_fn': 'refactor the heuristic_fn to support configurable random seeds instead of the hardcoded seed value of 10', 'summarize_heuristic_fn': 'summarize the heuristic_fn which returns a randomly chosen unassigned variable with a True value for 3SAT solving'}
```

## File: facebookresearch_mlgym/data/3SATTime/solver.py

Prompts

```
['run the DPLL solver on a pickled 3SAT dataset and print correctness metrics', 'run evaluate_dpll with a custom pickle file path to evaluate 3SAT formulas', 'test the evaluate_dpll function against a known 3SAT dataset and verify decision counts', 'refactor evaluate_dpll to accept the dataset path as a command-line argument instead of hardcoding it', 'review the evaluate_dpll function for early return behavior on incorrect solver results', 'run the heuristic_fn to randomly select an unassigned variable from 3SAT clauses and assign True', 'test the heuristic_fn with sample clauses and assignments to verify variable selection and True assignment', 'review the heuristic_fn to understand how it selects unassigned variables using a fixed random seed', 'refactor the heuristic_fn to support configurable random seeds instead of the hardcoded seed value of 10', 'summarize the heuristic_fn which returns a randomly chosen unassigned variable with a True value for 3SAT solving', 'create a DPLL solver instance with clauses and a heuristic function then call solve to find a satisfying assignment', 'use DPLL.is_satisfied_clause to check if a clause is satisfied given current variable assignments', 'use DPLL.is_conflicted_clause to detect if all literals in a clause evaluate to False under current assignments', 'use DPLL.is_unit_clause to identify clauses with exactly one unassigned literal for unit propagation', 'use DPLL.num_new_clauses to simulate assigning a variable and score the resulting clause reduction']
```

Usage

```
{'solve_3sat_with_dpll': 'create a DPLL solver instance with clauses and a heuristic function then call solve to find a satisfying assignment', 'check_clause_satisfaction': 'use DPLL.is_satisfied_clause to check if a clause is satisfied given current variable assignments', 'detect_conflicted_clauses': 'use DPLL.is_conflicted_clause to detect if all literals in a clause evaluate to False under current assignments', 'identify_unit_clauses': 'use DPLL.is_unit_clause to identify clauses with exactly one unassigned literal for unit propagation', 'simulate_variable_assignment': 'use DPLL.num_new_clauses to simulate assigning a variable and score the resulting clause reduction'}
```

