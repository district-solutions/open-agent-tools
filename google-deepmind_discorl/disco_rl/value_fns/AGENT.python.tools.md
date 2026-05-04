# Agent Python Tools

- repo: google-deepmind/discorl
- repo_uri: https://github.com/google-deepmind/disco_rl

## File: google-deepmind_discorl/disco_rl/value_fns/value_fn.py

Prompts

```
['build a ValueFunction with a ValueFnConfig and optional axis name for meta-training', 'create an initial ValueState with parameters and optimizer state from a dummy observation', 'get value estimates by running a forward pass of the value network on a rollout', 'update the value function state using TD loss computed from rollout and target logits', 'review the ValueFunction class used as a domain value function approximator in meta-training', 'calculate V-trace or Retrace value targets and advantage estimates from rollout data and network outputs', 'compute V-trace value estimates and advantages from state values and rollout rewards with importance sampling', 'compute Retrace action-value estimates and advantages from Q-values and rollout data with importance sampling', 'compute per-step value loss given network outputs and a scalar target using MSE or categorical cross-entropy', 'compute per-step value loss from a TD error using stop-gradient on the target construction']
```

Usage

```
{'build_value_function': 'build a ValueFunction with a ValueFnConfig and optional axis name for meta-training', 'create_initial_value_state': 'create an initial ValueState with parameters and optimizer state from a dummy observation', 'get_value_outputs': 'get value estimates by running a forward pass of the value network on a rollout', 'update_value_function': 'update the value function state using TD loss computed from rollout and target logits', 'review_value_function_class': 'review the ValueFunction class used as a domain value function approximator in meta-training'}
```

## File: google-deepmind_discorl/disco_rl/value_fns/value_utils.py

Prompts

```
['build a ValueFunction with a ValueFnConfig and optional axis name for meta-training', 'create an initial ValueState with parameters and optimizer state from a dummy observation', 'get value estimates by running a forward pass of the value network on a rollout', 'update the value function state using TD loss computed from rollout and target logits', 'review the ValueFunction class used as a domain value function approximator in meta-training', 'calculate V-trace or Retrace value targets and advantage estimates from rollout data and network outputs', 'compute V-trace value estimates and advantages from state values and rollout rewards with importance sampling', 'compute Retrace action-value estimates and advantages from Q-values and rollout data with importance sampling', 'compute per-step value loss given network outputs and a scalar target using MSE or categorical cross-entropy', 'compute per-step value loss from a TD error using stop-gradient on the target construction']
```

Usage

```
{'get_value_outs': 'calculate V-trace or Retrace value targets and advantage estimates from rollout data and network outputs', 'estimate_values': 'compute V-trace value estimates and advantages from state values and rollout rewards with importance sampling', 'estimate_q_values': 'compute Retrace action-value estimates and advantages from Q-values and rollout data with importance sampling', 'value_loss_from_target': 'compute per-step value loss given network outputs and a scalar target using MSE or categorical cross-entropy', 'value_loss_from_td': 'compute per-step value loss from a TD error using stop-gradient on the target construction'}
```

