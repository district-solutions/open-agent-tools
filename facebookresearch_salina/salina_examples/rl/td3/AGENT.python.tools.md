# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/rl/td3/agents.py

Prompts

```
['create an Atari environment with DeepMind wrappers and a TimeLimit step cap', 'create a standard Gym environment wrapped with a TimeLimit step cap', 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'review the ActionMLPAgent class that outputs TD3 policy actions with clipped noise exploration', 'review the QMLPAgent class that evaluates state-action pairs and outputs Q-values', 'run the TD3 reinforcement learning algorithm with twin Q-networks and delayed policy updates on a Gym environment', 'soft update target network parameters using exponential moving average with configurable tau coefficient', 'create TemporalAgent wrappers for Q-networks and action networks to process temporal sequences from replay buffer', 'setup and initialize a ReplayBuffer for storing environment transitions and sampling batches for training', 'optimize twin Q-networks using TD loss with gradient clipping and policy delay for stable learning', 'create a BraxAgent environment wrapper for running Brax physics-based RL environments', 'setup TemporalAgent wrappers around q-value and action agents for temporal forward passes', 'initialize a ReplayBuffer and populate it with environment interaction data for training']
```

Usage

```
{'create_atari_env': 'create an Atari environment with DeepMind wrappers and a TimeLimit step cap', 'create_gym_env': 'create a standard Gym environment wrapped with a TimeLimit step cap', 'build_mlp_network': 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'review_ActionMLPAgent': 'review the ActionMLPAgent class that outputs TD3 policy actions with clipped noise exploration', 'review_QMLPAgent': 'review the QMLPAgent class that evaluates state-action pairs and outputs Q-values'}
```

## File: facebookresearch_salina/salina_examples/rl/td3/td3.py

Prompts

```
['create an Atari environment with DeepMind wrappers and a TimeLimit step cap', 'create a standard Gym environment wrapped with a TimeLimit step cap', 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'review the ActionMLPAgent class that outputs TD3 policy actions with clipped noise exploration', 'review the QMLPAgent class that evaluates state-action pairs and outputs Q-values', 'run the TD3 reinforcement learning algorithm with twin Q-networks and delayed policy updates on a Gym environment', 'soft update target network parameters using exponential moving average with configurable tau coefficient', 'create TemporalAgent wrappers for Q-networks and action networks to process temporal sequences from replay buffer', 'setup and initialize a ReplayBuffer for storing environment transitions and sampling batches for training', 'optimize twin Q-networks using TD loss with gradient clipping and policy delay for stable learning', 'create a BraxAgent environment wrapper for running Brax physics-based RL environments', 'setup TemporalAgent wrappers around q-value and action agents for temporal forward passes', 'initialize a ReplayBuffer and populate it with environment interaction data for training']
```

Usage

```
{'run_td3_training': 'run the TD3 reinforcement learning algorithm with twin Q-networks and delayed policy updates on a Gym environment', 'soft_update_target_networks': 'soft update target network parameters using exponential moving average with configurable tau coefficient', 'create_temporal_agents': 'create TemporalAgent wrappers for Q-networks and action networks to process temporal sequences from replay buffer', 'setup_replay_buffer': 'setup and initialize a ReplayBuffer for storing environment transitions and sampling batches for training', 'optimize_q_networks': 'optimize twin Q-networks using TD loss with gradient clipping and policy delay for stable learning'}
```

## File: facebookresearch_salina/salina_examples/rl/td3/td3_with_brax.py

Prompts

```
['create an Atari environment with DeepMind wrappers and a TimeLimit step cap', 'create a standard Gym environment wrapped with a TimeLimit step cap', 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'review the ActionMLPAgent class that outputs TD3 policy actions with clipped noise exploration', 'review the QMLPAgent class that evaluates state-action pairs and outputs Q-values', 'run the TD3 reinforcement learning algorithm with twin Q-networks and delayed policy updates on a Gym environment', 'soft update target network parameters using exponential moving average with configurable tau coefficient', 'create TemporalAgent wrappers for Q-networks and action networks to process temporal sequences from replay buffer', 'setup and initialize a ReplayBuffer for storing environment transitions and sampling batches for training', 'optimize twin Q-networks using TD loss with gradient clipping and policy delay for stable learning', 'create a BraxAgent environment wrapper for running Brax physics-based RL environments', 'setup TemporalAgent wrappers around q-value and action agents for temporal forward passes', 'initialize a ReplayBuffer and populate it with environment interaction data for training']
```

Usage

```
{'run_td3_training': 'run the TD3 reinforcement learning algorithm with Brax environments using q and action agents', 'soft_update_target_networks': 'soft update target network parameters using exponential moving average with tau coefficient', 'create_brax_env_agent': 'create a BraxAgent environment wrapper for running Brax physics-based RL environments', 'setup_temporal_agents': 'setup TemporalAgent wrappers around q-value and action agents for temporal forward passes', 'initialize_replay_buffer': 'initialize a ReplayBuffer and populate it with environment interaction data for training'}
```

