# Agent Python Tools

- repo: facebookresearch/spider
- repo_uri: https://github.com/facebookresearch/spider

## File: facebookresearch_spider/spider/optimizers/sampling.py

Prompts

```
['sample control actions from a control signal by adding noise-scaled perturbations using config and sample parameters', 'build a rollout function that steps an environment with control actions and returns rewards, traces, and termination info', 'compute softmax weights over rewards by selecting top 10 percent of samples and normalizing with temperature', 'build a single-step DIAL MPC optimization function that samples controls, rolls out, and computes weighted mean controls', 'build a full optimization loop with parameter annealing, early stopping, and aggregated info across multiple iterations', 'build a rollout function that records qpos and qvel states during simulation for deterministic replay', 'build a single optimization step that selects the best trajectory from sampled control trajectories', 'build a deterministic optimizer that retries up to 4 times if tracking error exceeds thresholds', 'review the check_tracking_error function to validate object position and rotation tracking against reference poses', 'review the _snapshot_env_state function to clone all core simulation state fields into a tensor dictionary']
```

Usage

```
{'sample_ctrls': 'sample control actions from a control signal by adding noise-scaled perturbations using config and sample parameters', 'make_rollout_fn': 'build a rollout function that steps an environment with control actions and returns rewards, traces, and termination info', 'compute_weights': 'compute softmax weights over rewards by selecting top 10 percent of samples and normalizing with temperature', 'make_optimize_once_fn': 'build a single-step DIAL MPC optimization function that samples controls, rolls out, and computes weighted mean controls', 'make_optimize_fn': 'build a full optimization loop with parameter annealing, early stopping, and aggregated info across multiple iterations'}
```

## File: facebookresearch_spider/spider/optimizers/sampling_fast.py

Prompts

```
['sample control actions from a control signal by adding noise-scaled perturbations using config and sample parameters', 'build a rollout function that steps an environment with control actions and returns rewards, traces, and termination info', 'compute softmax weights over rewards by selecting top 10 percent of samples and normalizing with temperature', 'build a single-step DIAL MPC optimization function that samples controls, rolls out, and computes weighted mean controls', 'build a full optimization loop with parameter annealing, early stopping, and aggregated info across multiple iterations', 'build a rollout function that records qpos and qvel states during simulation for deterministic replay', 'build a single optimization step that selects the best trajectory from sampled control trajectories', 'build a deterministic optimizer that retries up to 4 times if tracking error exceeds thresholds', 'review the check_tracking_error function to validate object position and rotation tracking against reference poses', 'review the _snapshot_env_state function to clone all core simulation state fields into a tensor dictionary']
```

Usage

```
{'build_rollout_fn_fast': 'build a rollout function that records qpos and qvel states during simulation for deterministic replay', 'build_optimize_once_fn_fast': 'build a single optimization step that selects the best trajectory from sampled control trajectories', 'build_optimize_fn_fast': 'build a deterministic optimizer that retries up to 4 times if tracking error exceeds thresholds', 'review_check_tracking_error': 'review the check_tracking_error function to validate object position and rotation tracking against reference poses', 'review_snapshot_env_state': 'review the _snapshot_env_state function to clone all core simulation state fields into a tensor dictionary'}
```

