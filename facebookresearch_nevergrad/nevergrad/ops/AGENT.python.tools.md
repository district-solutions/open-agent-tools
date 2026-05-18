# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/ops/constraints.py

Prompts

```
['create a Constraint operator with a custom constraint function, optimizer name, and budget for parameter optimization', 'apply a constraint to a nevergrad Parameter to find a new parameter that better satisfies the constraint', 'check the stopping criterion callback to determine if the optimizer found a solution with zero constraint loss', 'get a constraint-free parameter from the Constraint operator for use in the optimization process', 'get the cached constrained value by calling the layered get value method which applies constraint if needed', 'test the Constraint operator with parametrized scalar parameters using pytest', 'test that Constraint layer function returns correct values for positive and negative inputs', 'test that constrained parameter args stay below threshold after constraint application', 'review the helper function that returns single arg or list of args', 'run the parametrized test_constraint with num values 1 and 3']
```

Usage

```
{'create_constraint_operator': 'create a Constraint operator with a custom constraint function, optimizer name, and budget for parameter optimization', 'apply_constraint_to_parameter': 'apply a constraint to a nevergrad Parameter to find a new parameter that better satisfies the constraint', 'check_stopping_criterion': 'check the stopping criterion callback to determine if the optimizer found a solution with zero constraint loss', 'get_constraint_free_parameter': 'get a constraint-free parameter from the Constraint operator for use in the optimization process', 'get_constrained_value': 'get the cached constrained value by calling the layered get value method which applies constraint if needed'}
```

## File: facebookresearch_nevergrad/nevergrad/ops/test_constraints.py

Prompts

```
['create a Constraint operator with a custom constraint function, optimizer name, and budget for parameter optimization', 'apply a constraint to a nevergrad Parameter to find a new parameter that better satisfies the constraint', 'check the stopping criterion callback to determine if the optimizer found a solution with zero constraint loss', 'get a constraint-free parameter from the Constraint operator for use in the optimization process', 'get the cached constrained value by calling the layered get value method which applies constraint if needed', 'test the Constraint operator with parametrized scalar parameters using pytest', 'test that Constraint layer function returns correct values for positive and negative inputs', 'test that constrained parameter args stay below threshold after constraint application', 'review the helper function that returns single arg or list of args', 'run the parametrized test_constraint with num values 1 and 3']
```

Usage

```
{'test_constraint_function': 'test the Constraint operator with parametrized scalar parameters using pytest', 'test_constraint_layer_functionality': 'test that Constraint layer function returns correct values for positive and negative inputs', 'test_constraint_value_bounds': 'test that constrained parameter args stay below threshold after constraint application', 'review_function_helper': 'review the helper function that returns single arg or list of args', 'run_test_constraint_parametrized': 'run the parametrized test_constraint with num values 1 and 3'}
```

