# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/circle_packing_rect/evaluator.py

Prompts

```
['run the evaluate function to score a circle packing program against the benchmark', 'compute the minimum circumscribing rectangle width and height for a set of circles', 'validate that all circle radii are non-negative and not nan', 'validate that no two circles overlap beyond a given tolerance', 'validate that all circles fit inside a rectangle of perimeter 4', 'run the circle_packing21 function to generate a 21-circle packing solution array', 'review the circle_packing21 function that places 21 circles in a rectangle of perimeter 4', 'refactor circle_packing21 to compute actual circle positions and radii instead of returning zeros', 'test the circle_packing21 function returns a numpy array of shape 21 by 3', 'summarize the circle_packing21 function that maximizes the sum of radii for 21 circles']
```

Usage

```
{'evaluate_circle_packing_program': 'run the evaluate function to score a circle packing program against the benchmark', 'compute_circumscribing_rectangle': 'compute the minimum circumscribing rectangle width and height for a set of circles', 'validate_circle_radii': 'validate that all circle radii are non-negative and not nan', 'validate_circle_overlap': 'validate that no two circles overlap beyond a given tolerance', 'validate_circles_inside_rectangle': 'validate that all circles fit inside a rectangle of perimeter 4'}
```

## File: algorithmicsuperintelligence_openevolve/examples/alphaevolve_math_problems/circle_packing_rect/initial_program.py

Prompts

```
['run the evaluate function to score a circle packing program against the benchmark', 'compute the minimum circumscribing rectangle width and height for a set of circles', 'validate that all circle radii are non-negative and not nan', 'validate that no two circles overlap beyond a given tolerance', 'validate that all circles fit inside a rectangle of perimeter 4', 'run the circle_packing21 function to generate a 21-circle packing solution array', 'review the circle_packing21 function that places 21 circles in a rectangle of perimeter 4', 'refactor circle_packing21 to compute actual circle positions and radii instead of returning zeros', 'test the circle_packing21 function returns a numpy array of shape 21 by 3', 'summarize the circle_packing21 function that maximizes the sum of radii for 21 circles']
```

Usage

```
{'run_circle_packing21': 'run the circle_packing21 function to generate a 21-circle packing solution array', 'review_circle_packing21': 'review the circle_packing21 function that places 21 circles in a rectangle of perimeter 4', 'refactor_circle_packing21': 'refactor circle_packing21 to compute actual circle positions and radii instead of returning zeros', 'test_circle_packing21': 'test the circle_packing21 function returns a numpy array of shape 21 by 3', 'summarize_circle_packing21': 'summarize the circle_packing21 function that maximizes the sum of radii for 21 circles'}
```

