# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/circle_packing_with_artifacts/evaluator.py

Prompts

```
['validate that circles do not overlap and stay inside the unit square given centers and radii arrays', 'run a python program in a subprocess with a configurable timeout and return its circle packing results', 'evaluate a circle packing program by running it once and computing sum of radii against the target value', 'run a quick first-stage validation of a circle packing program checking shapes and geometric constraints', 'run the full second-stage evaluation of a circle packing program with all metrics and artifacts', 'run the circle packing constructor for 26 circles in a unit square and print the sum of radii', 'construct an arrangement of 26 circles in a unit square using a center and ring pattern', 'compute the maximum non-overlapping radii for given circle centers constrained to a unit square', 'visualize a circle packing arrangement with labeled circles plotted in a unit square using matplotlib', 'refactor the construct_packing function to support a configurable number of circles instead of hardcoded 26']
```

Usage

```
{'validate_packing': 'validate that circles do not overlap and stay inside the unit square given centers and radii arrays', 'run_with_timeout': 'run a python program in a subprocess with a configurable timeout and return its circle packing results', 'evaluate': 'evaluate a circle packing program by running it once and computing sum of radii against the target value', 'evaluate_stage1': 'run a quick first-stage validation of a circle packing program checking shapes and geometric constraints', 'evaluate_stage2': 'run the full second-stage evaluation of a circle packing program with all metrics and artifacts'}
```

## File: algorithmicsuperintelligence_openevolve/examples/circle_packing_with_artifacts/initial_program.py

Prompts

```
['validate that circles do not overlap and stay inside the unit square given centers and radii arrays', 'run a python program in a subprocess with a configurable timeout and return its circle packing results', 'evaluate a circle packing program by running it once and computing sum of radii against the target value', 'run a quick first-stage validation of a circle packing program checking shapes and geometric constraints', 'run the full second-stage evaluation of a circle packing program with all metrics and artifacts', 'run the circle packing constructor for 26 circles in a unit square and print the sum of radii', 'construct an arrangement of 26 circles in a unit square using a center and ring pattern', 'compute the maximum non-overlapping radii for given circle centers constrained to a unit square', 'visualize a circle packing arrangement with labeled circles plotted in a unit square using matplotlib', 'refactor the construct_packing function to support a configurable number of circles instead of hardcoded 26']
```

Usage

```
{'run_circle_packing': 'run the circle packing constructor for 26 circles in a unit square and print the sum of radii', 'construct_circle_packing': 'construct an arrangement of 26 circles in a unit square using a center and ring pattern', 'compute_max_radii': 'compute the maximum non-overlapping radii for given circle centers constrained to a unit square', 'visualize_circle_packing': 'visualize a circle packing arrangement with labeled circles plotted in a unit square using matplotlib', 'refactor_construct_packing': 'refactor the construct_packing function to support a configurable number of circles instead of hardcoded 26'}
```

