# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/test/unit/test_tutorials/test_dqn_and_double_dqn.py

Prompts

```
['build a PearlAgent with DeepQLearning policy learner and a VanillaQValueNetwork for CartPole-v1', 'build a PearlAgent with DoubleDQN policy learner and a VanillaQValueNetwork for CartPole-v1', 'train a DQN agent using online_learning for 40 episodes on CartPole-v1 environment', 'train a Double DQN agent using online_learning for 40 episodes on CartPole-v1 environment', 'instantiate a VanillaQValueNetwork with two 64-unit hidden layers for Q-value approximation', 'build a PearlAgent with DeepQLearning policy learner and a BasicReplayBuffer for the FrozenLake environment', 'run online learning to train a DQN agent on the FrozenLake-v1 gym environment', 'create a FrozenLake-v1 gym environment wrapped with OneHotObservationsFromDiscrete for the 4x4 map', 'train a PearlAgent through online interaction with a gym environment and return episodic rewards', 'set the random seed for reproducible experiments across torch and numpy', 'build a PyTorch LSTM-based sequence classification model for click prediction with MLP head', 'create a recommendation environment with dynamic action space and impression history state tracking', 'run a vanilla DQN PearlAgent with DeepQLearning policy and BasicReplayBuffer for recommendation', 'run a DQN agent with LSTM history summarization module to handle partial observability', 'run a BootstrappedDQN agent with EnsembleQValueNetwork and BootstrapReplayBuffer for better exploration']
```

Usage

```
{'build_dqn_agent': 'build a PearlAgent with DeepQLearning policy learner and a VanillaQValueNetwork for CartPole-v1', 'build_doubledqn_agent': 'build a PearlAgent with DoubleDQN policy learner and a VanillaQValueNetwork for CartPole-v1', 'train_dqn_online': 'train a DQN agent using online_learning for 40 episodes on CartPole-v1 environment', 'train_doubledqn_online': 'train a Double DQN agent using online_learning for 40 episodes on CartPole-v1 environment', 'instantiate_q_network': 'instantiate a VanillaQValueNetwork with two 64-unit hidden layers for Q-value approximation'}
```

## File: facebookresearch_pearl/test/unit/test_tutorials/test_frozen_lake.py

Prompts

```
['build a PearlAgent with DeepQLearning policy learner and a VanillaQValueNetwork for CartPole-v1', 'build a PearlAgent with DoubleDQN policy learner and a VanillaQValueNetwork for CartPole-v1', 'train a DQN agent using online_learning for 40 episodes on CartPole-v1 environment', 'train a Double DQN agent using online_learning for 40 episodes on CartPole-v1 environment', 'instantiate a VanillaQValueNetwork with two 64-unit hidden layers for Q-value approximation', 'build a PearlAgent with DeepQLearning policy learner and a BasicReplayBuffer for the FrozenLake environment', 'run online learning to train a DQN agent on the FrozenLake-v1 gym environment', 'create a FrozenLake-v1 gym environment wrapped with OneHotObservationsFromDiscrete for the 4x4 map', 'train a PearlAgent through online interaction with a gym environment and return episodic rewards', 'set the random seed for reproducible experiments across torch and numpy', 'build a PyTorch LSTM-based sequence classification model for click prediction with MLP head', 'create a recommendation environment with dynamic action space and impression history state tracking', 'run a vanilla DQN PearlAgent with DeepQLearning policy and BasicReplayBuffer for recommendation', 'run a DQN agent with LSTM history summarization module to handle partial observability', 'run a BootstrappedDQN agent with EnsembleQValueNetwork and BootstrapReplayBuffer for better exploration']
```

Usage

```
{'instantiate_dqn_agent': 'build a PearlAgent with DeepQLearning policy learner and a BasicReplayBuffer for the FrozenLake environment', 'test_dqn_frozen_lake': 'run online learning to train a DQN agent on the FrozenLake-v1 gym environment', 'setUp': 'create a FrozenLake-v1 gym environment wrapped with OneHotObservationsFromDiscrete for the 4x4 map', 'online_learning': 'train a PearlAgent through online interaction with a gym environment and return episodic rewards', 'set_seed': 'set the random seed for reproducible experiments across torch and numpy'}
```

## File: facebookresearch_pearl/test/unit/test_tutorials/test_rec_system.py

Prompts

```
['build a PearlAgent with DeepQLearning policy learner and a VanillaQValueNetwork for CartPole-v1', 'build a PearlAgent with DoubleDQN policy learner and a VanillaQValueNetwork for CartPole-v1', 'train a DQN agent using online_learning for 40 episodes on CartPole-v1 environment', 'train a Double DQN agent using online_learning for 40 episodes on CartPole-v1 environment', 'instantiate a VanillaQValueNetwork with two 64-unit hidden layers for Q-value approximation', 'build a PearlAgent with DeepQLearning policy learner and a BasicReplayBuffer for the FrozenLake environment', 'run online learning to train a DQN agent on the FrozenLake-v1 gym environment', 'create a FrozenLake-v1 gym environment wrapped with OneHotObservationsFromDiscrete for the 4x4 map', 'train a PearlAgent through online interaction with a gym environment and return episodic rewards', 'set the random seed for reproducible experiments across torch and numpy', 'build a PyTorch LSTM-based sequence classification model for click prediction with MLP head', 'create a recommendation environment with dynamic action space and impression history state tracking', 'run a vanilla DQN PearlAgent with DeepQLearning policy and BasicReplayBuffer for recommendation', 'run a DQN agent with LSTM history summarization module to handle partial observability', 'run a BootstrappedDQN agent with EnsembleQValueNetwork and BootstrapReplayBuffer for better exploration']
```

Usage

```
{'build_sequence_classification_model': 'build a PyTorch LSTM-based sequence classification model for click prediction with MLP head', 'create_rec_env': 'create a recommendation environment with dynamic action space and impression history state tracking', 'run_vanilla_dqn_agent': 'run a vanilla DQN PearlAgent with DeepQLearning policy and BasicReplayBuffer for recommendation', 'run_dqn_lstm_agent': 'run a DQN agent with LSTM history summarization module to handle partial observability', 'run_bootstrapped_dqn_agent': 'run a BootstrappedDQN agent with EnsembleQValueNetwork and BootstrapReplayBuffer for better exploration'}
```

