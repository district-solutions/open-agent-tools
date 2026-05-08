# Agent Python Tools

- repo: facebookresearch/mbrl-lib
- repo_uri: https://github.com/facebookresearch/mbrl-lib

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac/agent/actor.py

Prompts

```
['create a TanhTransform instance to apply tanh bijective transform on PyTorch tensors', 'create a SquashedNormal distribution from loc and scale tensors with tanh squashing', 'create a DiagGaussianActor neural network policy for SAC reinforcement learning agents', 'run the DiagGaussianActor forward pass on observations to sample squashed normal actions', 'review the DiagGaussianActor log method for logging histograms and parameters to a logger', 'create a DoubleQCritic network with specified observation, action, hidden dimensions and depth', 'run a forward pass through the DoubleQCritic to get q1 and q2 values', 'build a double Q-learning critic network using two independent MLP heads', 'log the critic Q-value histograms and linear layer parameters to a logger', 'review the DoubleQCritic class and its double Q-learning implementation', 'create a SACAgent instance with critic and actor configs for a reinforcement learning environment', 'use the SACAgent act method to select actions from observations with optional sampling', 'update the SACAgent critic network using transition data from a replay buffer sample', 'update the SACAgent actor network and learnable temperature alpha using current observations', 'save the SACAgent critic and actor state dicts to a directory as pth files']
```

Usage

```
{'create_TanhTransform': 'create a TanhTransform instance to apply tanh bijective transform on PyTorch tensors', 'create_SquashedNormal': 'create a SquashedNormal distribution from loc and scale tensors with tanh squashing', 'create_DiagGaussianActor': 'create a DiagGaussianActor neural network policy for SAC reinforcement learning agents', 'run_DiagGaussianActor_forward': 'run the DiagGaussianActor forward pass on observations to sample squashed normal actions', 'review_DiagGaussianActor_log': 'review the DiagGaussianActor log method for logging histograms and parameters to a logger'}
```

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac/agent/critic.py

Prompts

```
['create a TanhTransform instance to apply tanh bijective transform on PyTorch tensors', 'create a SquashedNormal distribution from loc and scale tensors with tanh squashing', 'create a DiagGaussianActor neural network policy for SAC reinforcement learning agents', 'run the DiagGaussianActor forward pass on observations to sample squashed normal actions', 'review the DiagGaussianActor log method for logging histograms and parameters to a logger', 'create a DoubleQCritic network with specified observation, action, hidden dimensions and depth', 'run a forward pass through the DoubleQCritic to get q1 and q2 values', 'build a double Q-learning critic network using two independent MLP heads', 'log the critic Q-value histograms and linear layer parameters to a logger', 'review the DoubleQCritic class and its double Q-learning implementation', 'create a SACAgent instance with critic and actor configs for a reinforcement learning environment', 'use the SACAgent act method to select actions from observations with optional sampling', 'update the SACAgent critic network using transition data from a replay buffer sample', 'update the SACAgent actor network and learnable temperature alpha using current observations', 'save the SACAgent critic and actor state dicts to a directory as pth files']
```

Usage

```
{'create_double_q_critic': 'create a DoubleQCritic network with specified observation, action, hidden dimensions and depth', 'run_forward_pass': 'run a forward pass through the DoubleQCritic to get q1 and q2 values', 'build_critic_network': 'build a double Q-learning critic network using two independent MLP heads', 'log_critic_outputs': 'log the critic Q-value histograms and linear layer parameters to a logger', 'review_double_q_learning': 'review the DoubleQCritic class and its double Q-learning implementation'}
```

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac/agent/sac.py

Prompts

```
['create a TanhTransform instance to apply tanh bijective transform on PyTorch tensors', 'create a SquashedNormal distribution from loc and scale tensors with tanh squashing', 'create a DiagGaussianActor neural network policy for SAC reinforcement learning agents', 'run the DiagGaussianActor forward pass on observations to sample squashed normal actions', 'review the DiagGaussianActor log method for logging histograms and parameters to a logger', 'create a DoubleQCritic network with specified observation, action, hidden dimensions and depth', 'run a forward pass through the DoubleQCritic to get q1 and q2 values', 'build a double Q-learning critic network using two independent MLP heads', 'log the critic Q-value histograms and linear layer parameters to a logger', 'review the DoubleQCritic class and its double Q-learning implementation', 'create a SACAgent instance with critic and actor configs for a reinforcement learning environment', 'use the SACAgent act method to select actions from observations with optional sampling', 'update the SACAgent critic network using transition data from a replay buffer sample', 'update the SACAgent actor network and learnable temperature alpha using current observations', 'save the SACAgent critic and actor state dicts to a directory as pth files']
```

Usage

```
{'create_sac_agent': 'create a SACAgent instance with critic and actor configs for a reinforcement learning environment', 'act_sac_agent': 'use the SACAgent act method to select actions from observations with optional sampling', 'update_critic_sac_agent': 'update the SACAgent critic network using transition data from a replay buffer sample', 'update_actor_and_alpha_sac_agent': 'update the SACAgent actor network and learnable temperature alpha using current observations', 'save_sac_agent': 'save the SACAgent critic and actor state dicts to a directory as pth files'}
```

