# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/generator/flow_matching/model.py

Prompts

```
['build a FlowMatching model with a reverse function, solver method, and configurable inference steps for generative sampling', 'run the FlowMatching loss computation by passing target data x1 and optional conditionals to compute training loss', 'run the FlowMatching generate_iter method to iteratively sample from noise using an ODE solver', 'run the ConditionalFlowMatching generate_iter method with optional noise override for conditional generative sampling', 'run the FlowMatching log_likelihood method to compute log-likelihood of data using Hutchinson divergence estimation', 'build a python module using the Euler ODE solver to integrate a dynamics function over time steps', 'build a python module using the RungeKutta4 solver to integrate a dynamics function with fourth-order accuracy', 'build a python module using the Midpoint solver to integrate a dynamics function with improved accuracy over Euler', 'build a python module using the SDE solver to integrate a dynamics function with configurable noise strength', 'build a python module using the gradient function to compute gradients of an output with respect to a tree of tensors']
```

Usage

```
{'build_FlowMatching_model': 'build a FlowMatching model with a reverse function, solver method, and configurable inference steps for generative sampling', 'run_FlowMatching_loss': 'run the FlowMatching loss computation by passing target data x1 and optional conditionals to compute training loss', 'run_FlowMatching_generate_iter': 'run the FlowMatching generate_iter method to iteratively sample from noise using an ODE solver', 'run_ConditionalFlowMatching_generate_iter': 'run the ConditionalFlowMatching generate_iter method with optional noise override for conditional generative sampling', 'run_FlowMatching_log_likelihood': 'run the FlowMatching log_likelihood method to compute log-likelihood of data using Hutchinson divergence estimation'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/generator/flow_matching/solver.py

Prompts

```
['build a FlowMatching model with a reverse function, solver method, and configurable inference steps for generative sampling', 'run the FlowMatching loss computation by passing target data x1 and optional conditionals to compute training loss', 'run the FlowMatching generate_iter method to iteratively sample from noise using an ODE solver', 'run the ConditionalFlowMatching generate_iter method with optional noise override for conditional generative sampling', 'run the FlowMatching log_likelihood method to compute log-likelihood of data using Hutchinson divergence estimation', 'build a python module using the Euler ODE solver to integrate a dynamics function over time steps', 'build a python module using the RungeKutta4 solver to integrate a dynamics function with fourth-order accuracy', 'build a python module using the Midpoint solver to integrate a dynamics function with improved accuracy over Euler', 'build a python module using the SDE solver to integrate a dynamics function with configurable noise strength', 'build a python module using the gradient function to compute gradients of an output with respect to a tree of tensors']
```

Usage

```
{'build_euler_solver': 'build a python module using the Euler ODE solver to integrate a dynamics function over time steps', 'build_runge_kutta_solver': 'build a python module using the RungeKutta4 solver to integrate a dynamics function with fourth-order accuracy', 'build_midpoint_solver': 'build a python module using the Midpoint solver to integrate a dynamics function with improved accuracy over Euler', 'build_sde_solver': 'build a python module using the SDE solver to integrate a dynamics function with configurable noise strength', 'build_gradient_utils': 'build a python module using the gradient function to compute gradients of an output with respect to a tree of tensors'}
```

