# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/circle_packing/best_program.py

Prompts

```
['run the circle packing optimization for 26 circles in a unit square and print the sum of radii', 'construct an optimized arrangement of 26 circles in a unit square using SLSQP optimization and return centers, radii, and sum', 'visualize the circle packing results by drawing circles with labeled indices on a unit square plot', 'refactor the construct_packing function to support a configurable number of circles instead of the hardcoded 26', 'review the constraint function in construct_packing that enforces no-overlap and boundary constraints for circle packing', "validate that circles don't overlap and stay inside the unit square using validate_packing", 'run a circle packing program in a subprocess with a configurable timeout using run_with_timeout', 'evaluate a circle packing program and return metrics like sum_radii and validity using evaluate', 'perform a quick first-stage validation of a circle packing program using evaluate_stage1', 'perform a full second-stage evaluation of a circle packing program using evaluate_stage2', 'construct an arrangement of 26 circles placed in concentric rings inside a unit square', 'compute the maximum non-overlapping radii for given circle centers constrained by borders and pairwise distance']
```

Usage

```
{'run_circle_packing': 'run the circle packing optimization for 26 circles in a unit square and print the sum of radii', 'construct_packing_optimization': 'construct an optimized arrangement of 26 circles in a unit square using SLSQP optimization and return centers, radii, and sum', 'visualize_circle_packing': 'visualize the circle packing results by drawing circles with labeled indices on a unit square plot', 'refactor_construct_packing': 'refactor the construct_packing function to support a configurable number of circles instead of the hardcoded 26', 'review_constraint_function': 'review the constraint function in construct_packing that enforces no-overlap and boundary constraints for circle packing'}
```

## File: algorithmicsuperintelligence_openevolve/examples/circle_packing/evaluator.py

Prompts

```
['run the circle packing optimization for 26 circles in a unit square and print the sum of radii', 'construct an optimized arrangement of 26 circles in a unit square using SLSQP optimization and return centers, radii, and sum', 'visualize the circle packing results by drawing circles with labeled indices on a unit square plot', 'refactor the construct_packing function to support a configurable number of circles instead of the hardcoded 26', 'review the constraint function in construct_packing that enforces no-overlap and boundary constraints for circle packing', "validate that circles don't overlap and stay inside the unit square using validate_packing", 'run a circle packing program in a subprocess with a configurable timeout using run_with_timeout', 'evaluate a circle packing program and return metrics like sum_radii and validity using evaluate', 'perform a quick first-stage validation of a circle packing program using evaluate_stage1', 'perform a full second-stage evaluation of a circle packing program using evaluate_stage2', 'construct an arrangement of 26 circles placed in concentric rings inside a unit square', 'compute the maximum non-overlapping radii for given circle centers constrained by borders and pairwise distance']
```

Usage

```
{'validate_circle_packing': "validate that circles don't overlap and stay inside the unit square using validate_packing", 'run_program_with_timeout': 'run a circle packing program in a subprocess with a configurable timeout using run_with_timeout', 'evaluate_circle_packing_solution': 'evaluate a circle packing program and return metrics like sum_radii and validity using evaluate', 'evaluate_stage1_quick_validation': 'perform a quick first-stage validation of a circle packing program using evaluate_stage1', 'evaluate_stage2_full_evaluation': 'perform a full second-stage evaluation of a circle packing program using evaluate_stage2'}
```

## File: algorithmicsuperintelligence_openevolve/examples/circle_packing/initial_program.py

Prompts

```
['run the circle packing optimization for 26 circles in a unit square and print the sum of radii', 'construct an optimized arrangement of 26 circles in a unit square using SLSQP optimization and return centers, radii, and sum', 'visualize the circle packing results by drawing circles with labeled indices on a unit square plot', 'refactor the construct_packing function to support a configurable number of circles instead of the hardcoded 26', 'review the constraint function in construct_packing that enforces no-overlap and boundary constraints for circle packing', "validate that circles don't overlap and stay inside the unit square using validate_packing", 'run a circle packing program in a subprocess with a configurable timeout using run_with_timeout', 'evaluate a circle packing program and return metrics like sum_radii and validity using evaluate', 'perform a quick first-stage validation of a circle packing program using evaluate_stage1', 'perform a full second-stage evaluation of a circle packing program using evaluate_stage2', 'construct an arrangement of 26 circles placed in concentric rings inside a unit square', 'compute the maximum non-overlapping radii for given circle centers constrained by borders and pairwise distance']
```

Usage

```
{'run_circle_packing': 'run the circle packing constructor for 26 circles in a unit square and return centers, radii, and sum', 'construct_circle_arrangement': 'construct an arrangement of 26 circles placed in concentric rings inside a unit square', 'compute_max_radii': 'compute the maximum non-overlapping radii for given circle centers constrained by borders and pairwise distance', 'visualize_circle_packing': 'visualize a circle packing by drawing labeled circles on a unit square plot with matplotlib', 'refactor_construct_packing': 'refactor the construct_packing function to support a configurable number of circles instead of hardcoded 26'}
```

