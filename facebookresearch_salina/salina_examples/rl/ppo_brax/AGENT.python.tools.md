# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/rl/ppo_brax/agents.py

Prompts

```
['create a Brax environment wrapped with JaxToTorchWrapper for PyTorch compatibility', 'create a Gym environment with a TimeLimit wrapper and max episode steps', 'build an ActionAgent neural network policy for PPO with configurable layers and hidden size', 'build a CriticAgent neural network value function for PPO with configurable layers and hidden size', 'run the ActionAgent forward pass to sample actions and compute log probabilities', 'run the PPO reinforcement learning algorithm with action and critic agents on a Brax or Gym environment', 'create a Normalizer agent that computes running mean and variance to normalize environment observations online', 'run the main PPO training entry point using Hydra config to instantiate agents and start learning', 'clip the gradient norm of model parameters to a specified maximum value during training', 'review the run_ppo function that orchestrates environment acquisition, validation, and policy updates with GAE']
```

Usage

```
{'create_brax_env': 'create a Brax environment wrapped with JaxToTorchWrapper for PyTorch compatibility', 'create_gym_env': 'create a Gym environment with a TimeLimit wrapper and max episode steps', 'build_action_agent': 'build an ActionAgent neural network policy for PPO with configurable layers and hidden size', 'build_critic_agent': 'build a CriticAgent neural network value function for PPO with configurable layers and hidden size', 'run_action_agent_forward': 'run the ActionAgent forward pass to sample actions and compute log probabilities'}
```

## File: facebookresearch_salina/salina_examples/rl/ppo_brax/ppo.py

Prompts

```
['create a Brax environment wrapped with JaxToTorchWrapper for PyTorch compatibility', 'create a Gym environment with a TimeLimit wrapper and max episode steps', 'build an ActionAgent neural network policy for PPO with configurable layers and hidden size', 'build a CriticAgent neural network value function for PPO with configurable layers and hidden size', 'run the ActionAgent forward pass to sample actions and compute log probabilities', 'run the PPO reinforcement learning algorithm with action and critic agents on a Brax or Gym environment', 'create a Normalizer agent that computes running mean and variance to normalize environment observations online', 'run the main PPO training entry point using Hydra config to instantiate agents and start learning', 'clip the gradient norm of model parameters to a specified maximum value during training', 'review the run_ppo function that orchestrates environment acquisition, validation, and policy updates with GAE']
```

Usage

```
{'run_ppo_training': 'run the PPO reinforcement learning algorithm with action and critic agents on a Brax or Gym environment', 'create_normalizer_agent': 'create a Normalizer agent that computes running mean and variance to normalize environment observations online', 'run_ppo_main': 'run the main PPO training entry point using Hydra config to instantiate agents and start learning', 'clip_gradient_norm': 'clip the gradient norm of model parameters to a specified maximum value during training', 'review_run_ppo': 'review the run_ppo function that orchestrates environment acquisition, validation, and policy updates with GAE'}
```

