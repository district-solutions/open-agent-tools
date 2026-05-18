# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/functions/rocket/rocket.py

Prompts

```
['run the rocket simulation function with a 24-element thrust bias numpy array', 'create a Rocket ArrayExperimentFunction instance with optional symmetry for nevergrad optimization', 'test the rocket function by passing a zero-initialized 24-element numpy array', 'review the grav_force helper function that computes gravitational force components in ECEF coordinates', 'summarize the drag_force helper function that calculates aerodynamic drag using air density and velocity', 'test the Rocket class by instantiating it and evaluating a zero input array', 'run the notest_rocket function to verify Rocket returns near zero for zero input', 'review the notest_rocket test function that validates Rocket dimension and evaluation', 'summarize the test_rocket module which contains a single skipped test for the Rocket function', 'refactor the notest_rocket function to enable it as a standard pytest test case']
```

Usage

```
{'run_rocket_simulation': 'run the rocket simulation function with a 24-element thrust bias numpy array', 'create_rocket_experiment': 'create a Rocket ArrayExperimentFunction instance with optional symmetry for nevergrad optimization', 'test_rocket_function': 'test the rocket function by passing a zero-initialized 24-element numpy array', 'review_grav_force': 'review the grav_force helper function that computes gravitational force components in ECEF coordinates', 'summarize_drag_force': 'summarize the drag_force helper function that calculates aerodynamic drag using air density and velocity'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/rocket/test_rocket.py

Prompts

```
['run the rocket simulation function with a 24-element thrust bias numpy array', 'create a Rocket ArrayExperimentFunction instance with optional symmetry for nevergrad optimization', 'test the rocket function by passing a zero-initialized 24-element numpy array', 'review the grav_force helper function that computes gravitational force components in ECEF coordinates', 'summarize the drag_force helper function that calculates aerodynamic drag using air density and velocity', 'test the Rocket class by instantiating it and evaluating a zero input array', 'run the notest_rocket function to verify Rocket returns near zero for zero input', 'review the notest_rocket test function that validates Rocket dimension and evaluation', 'summarize the test_rocket module which contains a single skipped test for the Rocket function', 'refactor the notest_rocket function to enable it as a standard pytest test case']
```

Usage

```
{'test_rocket_class': 'test the Rocket class by instantiating it and evaluating a zero input array', 'run_notest_rocket': 'run the notest_rocket function to verify Rocket returns near zero for zero input', 'review_notest_rocket': 'review the notest_rocket test function that validates Rocket dimension and evaluation', 'summarize_rocket_test': 'summarize the test_rocket module which contains a single skipped test for the Rocket function', 'refactor_notest_rocket': 'refactor the notest_rocket function to enable it as a standard pytest test case'}
```

