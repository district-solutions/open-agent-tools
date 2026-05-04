# Agent Python Tools

- repo: facebookresearch/dcem
- repo_uri: https://github.com/facebookresearch/dcem

## File: facebookresearch_dcem/dcem/dcem.py

Prompts

```
['run the dcem function to optimize a scalar objective function over an nx-dimensional space using cross-entropy method', 'run the dcem function with lower and upper bounds to optimize an objective within a constrained domain', 'run the dcem function with n_batch greater than 1 to optimize multiple objectives in parallel', 'run the dcem function with a proj_iterate_cb to project sampled points before evaluating the objective', 'run the dcem function with an iter_cb to monitor mu, sigma, and elite samples each iteration', 'run CEM control optimization over a planning horizon with batched observations and a rollout cost function', 'run CEM control optimization with lower and upper bound constraints on control actions', 'run CEM control optimization with an iteration callback to monitor convergence progress', 'review the dcem_ctrl function that wraps the CEM optimizer for model predictive control tasks', 'summarize the dcem_ctrl output dictionary containing optimized control sequences, initial actions, costs, and the cost function', 'run the DCEM cross-entropy method optimization test with a quadratic objective function', 'test the dcem optimizer by solving a batched quadratic minimization problem with elite sampling', 'create a batched matrix-vector multiplication helper using PyTorch bmm for tensor operations', 'run a batched quadratic optimization problem using the DCEM cross-entropy method with 40 iterations', 'test the DCEM iteration callback to monitor objective function mean values during optimization']
```

Usage

```
{'run_cem_optimization': 'run the dcem function to optimize a scalar objective function over an nx-dimensional space using cross-entropy method', 'run_bounded_cem_optimization': 'run the dcem function with lower and upper bounds to optimize an objective within a constrained domain', 'run_batched_cem_optimization': 'run the dcem function with n_batch greater than 1 to optimize multiple objectives in parallel', 'run_cem_with_projection_callback': 'run the dcem function with a proj_iterate_cb to project sampled points before evaluating the objective', 'run_cem_with_iteration_callback': 'run the dcem function with an iter_cb to monitor mu, sigma, and elite samples each iteration'}
```

## File: facebookresearch_dcem/dcem/dcem_ctrl.py

Prompts

```
['run the dcem function to optimize a scalar objective function over an nx-dimensional space using cross-entropy method', 'run the dcem function with lower and upper bounds to optimize an objective within a constrained domain', 'run the dcem function with n_batch greater than 1 to optimize multiple objectives in parallel', 'run the dcem function with a proj_iterate_cb to project sampled points before evaluating the objective', 'run the dcem function with an iter_cb to monitor mu, sigma, and elite samples each iteration', 'run CEM control optimization over a planning horizon with batched observations and a rollout cost function', 'run CEM control optimization with lower and upper bound constraints on control actions', 'run CEM control optimization with an iteration callback to monitor convergence progress', 'review the dcem_ctrl function that wraps the CEM optimizer for model predictive control tasks', 'summarize the dcem_ctrl output dictionary containing optimized control sequences, initial actions, costs, and the cost function', 'run the DCEM cross-entropy method optimization test with a quadratic objective function', 'test the dcem optimizer by solving a batched quadratic minimization problem with elite sampling', 'create a batched matrix-vector multiplication helper using PyTorch bmm for tensor operations', 'run a batched quadratic optimization problem using the DCEM cross-entropy method with 40 iterations', 'test the DCEM iteration callback to monitor objective function mean values during optimization']
```

Usage

```
{'run_dcem_ctrl_optimization': 'run CEM control optimization over a planning horizon with batched observations and a rollout cost function', 'run_dcem_ctrl_with_constraints': 'run CEM control optimization with lower and upper bound constraints on control actions', 'run_dcem_ctrl_with_callbacks': 'run CEM control optimization with an iteration callback to monitor convergence progress', 'review_dcem_ctrl_function': 'review the dcem_ctrl function that wraps the CEM optimizer for model predictive control tasks', 'summarize_dcem_ctrl_output': 'summarize the dcem_ctrl output dictionary containing optimized control sequences, initial actions, costs, and the cost function'}
```

## File: facebookresearch_dcem/dcem/test.py

Prompts

```
['run the dcem function to optimize a scalar objective function over an nx-dimensional space using cross-entropy method', 'run the dcem function with lower and upper bounds to optimize an objective within a constrained domain', 'run the dcem function with n_batch greater than 1 to optimize multiple objectives in parallel', 'run the dcem function with a proj_iterate_cb to project sampled points before evaluating the objective', 'run the dcem function with an iter_cb to monitor mu, sigma, and elite samples each iteration', 'run CEM control optimization over a planning horizon with batched observations and a rollout cost function', 'run CEM control optimization with lower and upper bound constraints on control actions', 'run CEM control optimization with an iteration callback to monitor convergence progress', 'review the dcem_ctrl function that wraps the CEM optimizer for model predictive control tasks', 'summarize the dcem_ctrl output dictionary containing optimized control sequences, initial actions, costs, and the cost function', 'run the DCEM cross-entropy method optimization test with a quadratic objective function', 'test the dcem optimizer by solving a batched quadratic minimization problem with elite sampling', 'create a batched matrix-vector multiplication helper using PyTorch bmm for tensor operations', 'run a batched quadratic optimization problem using the DCEM cross-entropy method with 40 iterations', 'test the DCEM iteration callback to monitor objective function mean values during optimization']
```

Usage

```
{'run_dcem_test': 'run the DCEM cross-entropy method optimization test with a quadratic objective function', 'test_dcem_function': 'test the dcem optimizer by solving a batched quadratic minimization problem with elite sampling', 'create_bmv_helper': 'create a batched matrix-vector multiplication helper using PyTorch bmm for tensor operations', 'run_quadratic_optimization': 'run a batched quadratic optimization problem using the DCEM cross-entropy method with 40 iterations', 'test_iter_callback': 'test the DCEM iteration callback to monitor objective function mean values during optimization'}
```

