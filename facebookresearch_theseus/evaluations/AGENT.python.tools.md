# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/evaluations/time_local_cost_backward.py

Prompts

```
['run a benchmark to measure forward and backward pass timing for Local cost on SO3 or SE3 groups', 'run a LevenbergMarquardt optimizer with TheseusLayer on Lie group variables with configurable damping and step size', 'run a TheseusLayer forward pass with input tensors and optimizer kwargs for Lie group optimization', 'run an Objective with Local cost between two Lie group variables using ScaleCostWeight', 'run a backward pass with Adam optimizer on Lie group parameters and compute error metric loss']
```

Usage

```
{'run_local_cost_backward_benchmark': 'run a benchmark to measure forward and backward pass timing for Local cost on SO3 or SE3 groups', 'run_LevenbergMarquardt_optimizer': 'run a LevenbergMarquardt optimizer with TheseusLayer on Lie group variables with configurable damping and step size', 'run_theseus_layer_forward': 'run a TheseusLayer forward pass with input tensors and optimizer kwargs for Lie group optimization', 'run_local_cost_objective': 'run an Objective with Local cost between two Lie group variables using ScaleCostWeight', 'run_backward_pass_adam': 'run a backward pass with Adam optimizer on Lie group parameters and compute error metric loss'}
```

