# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/algos/model_accel/model_accel_npg.py

Prompts

```
['create a ModelAccelNPG instance with a learned WorldModel and planning parameters', 'run a training step with N trajectories using learned dynamics models and policy rollout', 'move all learned models and baseline network to a specified CUDA or CPU device', 'check if any learned model or baseline network is running on GPU', 'get an action from the policy or refined action based on the refine flag', 'create an MPCPolicy instance with a fitted dynamics model, plan horizon, and environment', 'run get_action on an MPCPolicy to compute the best action for a given observation', 'test the score_trajectory method to compute discounted reward scores for generated paths', 'review score_trajectory_ensemble to score paths using model disagreement and discounted rewards', 'refactor MPCPolicy warmstart logic to update the action sequence after each planning step', 'build a WorldModel to learn environment dynamics and predict next states from state-action pairs', 'create a DynamicsNet neural network to model state transitions with residual connections and input normalization', 'create a RewardNet neural network to predict rewards from state, action, and next state inputs', 'fit the WorldModel dynamics network on trajectory data with mini-batch gradient descent and automatic normalization', 'predict next states from given state and action inputs using the trained WorldModel dynamics network', 'run a parametric policy rollout on a learned environment model to collect trajectory data', 'run action sequences through a learned dynamics model to simulate trajectories from initial states', 'sample trajectories by rolling out an MPC policy on a real Gym environment with noise', 'generate perturbed action trajectories using filter coefficients and rollout on a learned model', 'evaluate a policy on an environment or learned model and record episode rewards and observations']
```

Usage

```
{'create_ModelAccelNPG': 'create a ModelAccelNPG instance with a learned WorldModel and planning parameters', 'run_train_step': 'run a training step with N trajectories using learned dynamics models and policy rollout', 'move_to_device': 'move all learned models and baseline network to a specified CUDA or CPU device', 'check_cuda_status': 'check if any learned model or baseline network is running on GPU', 'get_action': 'get an action from the policy or refined action based on the refine flag'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/algos/model_accel/model_learning_mpc.py

Prompts

```
['create a ModelAccelNPG instance with a learned WorldModel and planning parameters', 'run a training step with N trajectories using learned dynamics models and policy rollout', 'move all learned models and baseline network to a specified CUDA or CPU device', 'check if any learned model or baseline network is running on GPU', 'get an action from the policy or refined action based on the refine flag', 'create an MPCPolicy instance with a fitted dynamics model, plan horizon, and environment', 'run get_action on an MPCPolicy to compute the best action for a given observation', 'test the score_trajectory method to compute discounted reward scores for generated paths', 'review score_trajectory_ensemble to score paths using model disagreement and discounted rewards', 'refactor MPCPolicy warmstart logic to update the action sequence after each planning step', 'build a WorldModel to learn environment dynamics and predict next states from state-action pairs', 'create a DynamicsNet neural network to model state transitions with residual connections and input normalization', 'create a RewardNet neural network to predict rewards from state, action, and next state inputs', 'fit the WorldModel dynamics network on trajectory data with mini-batch gradient descent and automatic normalization', 'predict next states from given state and action inputs using the trained WorldModel dynamics network', 'run a parametric policy rollout on a learned environment model to collect trajectory data', 'run action sequences through a learned dynamics model to simulate trajectories from initial states', 'sample trajectories by rolling out an MPC policy on a real Gym environment with noise', 'generate perturbed action trajectories using filter coefficients and rollout on a learned model', 'evaluate a policy on an environment or learned model and record episode rewards and observations']
```

Usage

```
{'create_MPCPolicy': 'create an MPCPolicy instance with a fitted dynamics model, plan horizon, and environment', 'run_get_action': 'run get_action on an MPCPolicy to compute the best action for a given observation', 'test_score_trajectory': 'test the score_trajectory method to compute discounted reward scores for generated paths', 'review_score_trajectory_ensemble': 'review score_trajectory_ensemble to score paths using model disagreement and discounted rewards', 'refactor_MPCPolicy_warmstart': 'refactor MPCPolicy warmstart logic to update the action sequence after each planning step'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/algos/model_accel/nn_dynamics.py

Prompts

```
['create a ModelAccelNPG instance with a learned WorldModel and planning parameters', 'run a training step with N trajectories using learned dynamics models and policy rollout', 'move all learned models and baseline network to a specified CUDA or CPU device', 'check if any learned model or baseline network is running on GPU', 'get an action from the policy or refined action based on the refine flag', 'create an MPCPolicy instance with a fitted dynamics model, plan horizon, and environment', 'run get_action on an MPCPolicy to compute the best action for a given observation', 'test the score_trajectory method to compute discounted reward scores for generated paths', 'review score_trajectory_ensemble to score paths using model disagreement and discounted rewards', 'refactor MPCPolicy warmstart logic to update the action sequence after each planning step', 'build a WorldModel to learn environment dynamics and predict next states from state-action pairs', 'create a DynamicsNet neural network to model state transitions with residual connections and input normalization', 'create a RewardNet neural network to predict rewards from state, action, and next state inputs', 'fit the WorldModel dynamics network on trajectory data with mini-batch gradient descent and automatic normalization', 'predict next states from given state and action inputs using the trained WorldModel dynamics network', 'run a parametric policy rollout on a learned environment model to collect trajectory data', 'run action sequences through a learned dynamics model to simulate trajectories from initial states', 'sample trajectories by rolling out an MPC policy on a real Gym environment with noise', 'generate perturbed action trajectories using filter coefficients and rollout on a learned model', 'evaluate a policy on an environment or learned model and record episode rewards and observations']
```

Usage

```
{'build_WorldModel': 'build a WorldModel to learn environment dynamics and predict next states from state-action pairs', 'create_DynamicsNet': 'create a DynamicsNet neural network to model state transitions with residual connections and input normalization', 'create_RewardNet': 'create a RewardNet neural network to predict rewards from state, action, and next state inputs', 'fit_dynamics_WorldModel': 'fit the WorldModel dynamics network on trajectory data with mini-batch gradient descent and automatic normalization', 'predict_WorldModel': 'predict next states from given state and action inputs using the trained WorldModel dynamics network'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/algos/model_accel/sampling.py

Prompts

```
['create a ModelAccelNPG instance with a learned WorldModel and planning parameters', 'run a training step with N trajectories using learned dynamics models and policy rollout', 'move all learned models and baseline network to a specified CUDA or CPU device', 'check if any learned model or baseline network is running on GPU', 'get an action from the policy or refined action based on the refine flag', 'create an MPCPolicy instance with a fitted dynamics model, plan horizon, and environment', 'run get_action on an MPCPolicy to compute the best action for a given observation', 'test the score_trajectory method to compute discounted reward scores for generated paths', 'review score_trajectory_ensemble to score paths using model disagreement and discounted rewards', 'refactor MPCPolicy warmstart logic to update the action sequence after each planning step', 'build a WorldModel to learn environment dynamics and predict next states from state-action pairs', 'create a DynamicsNet neural network to model state transitions with residual connections and input normalization', 'create a RewardNet neural network to predict rewards from state, action, and next state inputs', 'fit the WorldModel dynamics network on trajectory data with mini-batch gradient descent and automatic normalization', 'predict next states from given state and action inputs using the trained WorldModel dynamics network', 'run a parametric policy rollout on a learned environment model to collect trajectory data', 'run action sequences through a learned dynamics model to simulate trajectories from initial states', 'sample trajectories by rolling out an MPC policy on a real Gym environment with noise', 'generate perturbed action trajectories using filter coefficients and rollout on a learned model', 'evaluate a policy on an environment or learned model and record episode rewards and observations']
```

Usage

```
{'run_policy_rollout': 'run a parametric policy rollout on a learned environment model to collect trajectory data', 'run_trajectory_rollout': 'run action sequences through a learned dynamics model to simulate trajectories from initial states', 'run_sample_paths': 'sample trajectories by rolling out an MPC policy on a real Gym environment with noise', 'run_generate_paths': 'generate perturbed action trajectories using filter coefficients and rollout on a learned model', 'run_evaluate_policy': 'evaluate a policy on an environment or learned model and record episode rewards and observations'}
```

