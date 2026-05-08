# Agent Python Tools

- repo: facebookresearch/mbrl-lib
- repo_uri: https://github.com/facebookresearch/mbrl-lib

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac_pranz24/model.py

Prompts

```
['create a ValueNetwork module with a given input dimension and hidden layer size', 'create a QNetwork with two heads for state-action value estimation in SAC', 'create a GaussianPolicy network that samples actions with reparameterization trick and log probabilities', 'create a DeterministicPolicy network that outputs actions with additive exploration noise', 'review the weights_init_ function that applies Xavier uniform initialization to Linear layers', 'create a ReplayMemory instance with a given capacity and random seed for experience storage', 'push a single state, action, reward, next_state, and done tuple into the replay buffer', 'add a batch of transitions to the replay buffer using numpy array inputs', 'sample a random batch of transitions from the replay buffer for training', 'save the replay buffer to disk with pickle or load it from a saved file path', 'create a SAC reinforcement learning agent with Gaussian or Deterministic policy for continuous control tasks', 'select an action from the SAC policy given a state for evaluation or exploration', 'update SAC agent parameters by sampling from replay memory and computing critic and policy losses', 'save SAC agent model parameters including policy, critic, and optimizer states to a checkpoint file', 'load SAC agent model parameters from a checkpoint file and set evaluation or training mode', 'create a log probability of a Gaussian distribution given mean, log_std, and sample tensor t', 'compute the numerically stable log-sum-exp of a PyTorch tensor along a specified dimension', 'soft update target network parameters from source network using a tau interpolation coefficient', 'hard update target network parameters by directly copying all parameters from the source network', 'review the PyTorch SAC utility functions for log Gaussian, logsumexp, soft update, and hard update']
```

Usage

```
{'create_value_network': 'create a ValueNetwork module with a given input dimension and hidden layer size', 'create_q_network': 'create a QNetwork with two heads for state-action value estimation in SAC', 'create_gaussian_policy': 'create a GaussianPolicy network that samples actions with reparameterization trick and log probabilities', 'create_deterministic_policy': 'create a DeterministicPolicy network that outputs actions with additive exploration noise', 'review_weights_init': 'review the weights_init_ function that applies Xavier uniform initialization to Linear layers'}
```

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac_pranz24/replay_memory.py

Prompts

```
['create a ValueNetwork module with a given input dimension and hidden layer size', 'create a QNetwork with two heads for state-action value estimation in SAC', 'create a GaussianPolicy network that samples actions with reparameterization trick and log probabilities', 'create a DeterministicPolicy network that outputs actions with additive exploration noise', 'review the weights_init_ function that applies Xavier uniform initialization to Linear layers', 'create a ReplayMemory instance with a given capacity and random seed for experience storage', 'push a single state, action, reward, next_state, and done tuple into the replay buffer', 'add a batch of transitions to the replay buffer using numpy array inputs', 'sample a random batch of transitions from the replay buffer for training', 'save the replay buffer to disk with pickle or load it from a saved file path', 'create a SAC reinforcement learning agent with Gaussian or Deterministic policy for continuous control tasks', 'select an action from the SAC policy given a state for evaluation or exploration', 'update SAC agent parameters by sampling from replay memory and computing critic and policy losses', 'save SAC agent model parameters including policy, critic, and optimizer states to a checkpoint file', 'load SAC agent model parameters from a checkpoint file and set evaluation or training mode', 'create a log probability of a Gaussian distribution given mean, log_std, and sample tensor t', 'compute the numerically stable log-sum-exp of a PyTorch tensor along a specified dimension', 'soft update target network parameters from source network using a tau interpolation coefficient', 'hard update target network parameters by directly copying all parameters from the source network', 'review the PyTorch SAC utility functions for log Gaussian, logsumexp, soft update, and hard update']
```

Usage

```
{'create_replay_memory': 'create a ReplayMemory instance with a given capacity and random seed for experience storage', 'push_experience': 'push a single state, action, reward, next_state, and done tuple into the replay buffer', 'add_batch_experiences': 'add a batch of transitions to the replay buffer using numpy array inputs', 'sample_batch': 'sample a random batch of transitions from the replay buffer for training', 'save_and_load_buffer': 'save the replay buffer to disk with pickle or load it from a saved file path'}
```

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac_pranz24/sac.py

Prompts

```
['create a ValueNetwork module with a given input dimension and hidden layer size', 'create a QNetwork with two heads for state-action value estimation in SAC', 'create a GaussianPolicy network that samples actions with reparameterization trick and log probabilities', 'create a DeterministicPolicy network that outputs actions with additive exploration noise', 'review the weights_init_ function that applies Xavier uniform initialization to Linear layers', 'create a ReplayMemory instance with a given capacity and random seed for experience storage', 'push a single state, action, reward, next_state, and done tuple into the replay buffer', 'add a batch of transitions to the replay buffer using numpy array inputs', 'sample a random batch of transitions from the replay buffer for training', 'save the replay buffer to disk with pickle or load it from a saved file path', 'create a SAC reinforcement learning agent with Gaussian or Deterministic policy for continuous control tasks', 'select an action from the SAC policy given a state for evaluation or exploration', 'update SAC agent parameters by sampling from replay memory and computing critic and policy losses', 'save SAC agent model parameters including policy, critic, and optimizer states to a checkpoint file', 'load SAC agent model parameters from a checkpoint file and set evaluation or training mode', 'create a log probability of a Gaussian distribution given mean, log_std, and sample tensor t', 'compute the numerically stable log-sum-exp of a PyTorch tensor along a specified dimension', 'soft update target network parameters from source network using a tau interpolation coefficient', 'hard update target network parameters by directly copying all parameters from the source network', 'review the PyTorch SAC utility functions for log Gaussian, logsumexp, soft update, and hard update']
```

Usage

```
{'create_sac_agent': 'create a SAC reinforcement learning agent with Gaussian or Deterministic policy for continuous control tasks', 'select_action_sac': 'select an action from the SAC policy given a state for evaluation or exploration', 'update_parameters_sac': 'update SAC agent parameters by sampling from replay memory and computing critic and policy losses', 'save_checkpoint_sac': 'save SAC agent model parameters including policy, critic, and optimizer states to a checkpoint file', 'load_checkpoint_sac': 'load SAC agent model parameters from a checkpoint file and set evaluation or training mode'}
```

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac_pranz24/utils.py

Prompts

```
['create a ValueNetwork module with a given input dimension and hidden layer size', 'create a QNetwork with two heads for state-action value estimation in SAC', 'create a GaussianPolicy network that samples actions with reparameterization trick and log probabilities', 'create a DeterministicPolicy network that outputs actions with additive exploration noise', 'review the weights_init_ function that applies Xavier uniform initialization to Linear layers', 'create a ReplayMemory instance with a given capacity and random seed for experience storage', 'push a single state, action, reward, next_state, and done tuple into the replay buffer', 'add a batch of transitions to the replay buffer using numpy array inputs', 'sample a random batch of transitions from the replay buffer for training', 'save the replay buffer to disk with pickle or load it from a saved file path', 'create a SAC reinforcement learning agent with Gaussian or Deterministic policy for continuous control tasks', 'select an action from the SAC policy given a state for evaluation or exploration', 'update SAC agent parameters by sampling from replay memory and computing critic and policy losses', 'save SAC agent model parameters including policy, critic, and optimizer states to a checkpoint file', 'load SAC agent model parameters from a checkpoint file and set evaluation or training mode', 'create a log probability of a Gaussian distribution given mean, log_std, and sample tensor t', 'compute the numerically stable log-sum-exp of a PyTorch tensor along a specified dimension', 'soft update target network parameters from source network using a tau interpolation coefficient', 'hard update target network parameters by directly copying all parameters from the source network', 'review the PyTorch SAC utility functions for log Gaussian, logsumexp, soft update, and hard update']
```

Usage

```
{'create_log_gaussian': 'create a log probability of a Gaussian distribution given mean, log_std, and sample tensor t', 'compute_logsumexp': 'compute the numerically stable log-sum-exp of a PyTorch tensor along a specified dimension', 'soft_update_target_network': 'soft update target network parameters from source network using a tau interpolation coefficient', 'hard_update_target_network': 'hard update target network parameters by directly copying all parameters from the source network', 'review_utils_functions': 'review the PyTorch SAC utility functions for log Gaussian, logsumexp, soft update, and hard update'}
```

