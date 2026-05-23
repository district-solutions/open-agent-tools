# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/dqn/agent.py

Prompts

```
['create a QAgent with a model and number of actions for epsilon-greedy action selection', 'build a QMLP neural network with linear layers and tanh activation for Q-value estimation', 'build a dueling QMLP network that separates value and advantage estimation for Q-values', 'build a CnnDQN model with convolutional feature extractor and fully connected layers for image-based RL', 'build a DuelingCnnDQN model with separate value and advantage streams for improved Q-value estimation', 'run the DQN algorithm with prioritized experience replay and double duelling Q-learning on a gym environment', 'create a ReplayBuffer instance with a fixed capacity N for storing and sampling experience transitions', 'sample prioritized transitions from the replay buffer using alpha and beta importance sampling weights', 'soft update the target network parameters using tau interpolation or hard copy every N epochs', 'compute the squared TD error loss for a batch of transitions using the learning and target models', 'run a DQN experiment on an Atari environment like PongNoFrameskip-v4 with configurable hyperparameters', 'create Atari environments wrapped with DeepMind and PyTorch wrappers for training or evaluation mode', 'create a QAgent instance with a specified model and number of actions for DQN training', 'review the Experiment class that extends DQN and selects DuelingCnnDQN or CnnDQN models', 'refactor the Experiment _create_model method to support additional CNN-based DQN model architectures', 'run a DQN experiment on CartPole-v0 using the Experiment class with config and create_env', 'create a GymEnv or GymEnvInf wrapper for n environments with optional time limit and seed', 'create a QMLP or DQMLP neural network model for the DQN agent with weight initialization', 'flatten a nested dictionary into a single-level dict with slash-separated keys']
```

Usage

```
{'create_QAgent': 'create a QAgent with a model and number of actions for epsilon-greedy action selection', 'build_QMLP': 'build a QMLP neural network with linear layers and tanh activation for Q-value estimation', 'build_DQMLP': 'build a dueling QMLP network that separates value and advantage estimation for Q-values', 'build_CnnDQN': 'build a CnnDQN model with convolutional feature extractor and fully connected layers for image-based RL', 'build_DuelingCnnDQN': 'build a DuelingCnnDQN model with separate value and advantage streams for improved Q-value estimation'}
```

## File: facebookresearch_rlstructures/rlalgos/dqn/duelling_dqn.py

Prompts

```
['create a QAgent with a model and number of actions for epsilon-greedy action selection', 'build a QMLP neural network with linear layers and tanh activation for Q-value estimation', 'build a dueling QMLP network that separates value and advantage estimation for Q-values', 'build a CnnDQN model with convolutional feature extractor and fully connected layers for image-based RL', 'build a DuelingCnnDQN model with separate value and advantage streams for improved Q-value estimation', 'run the DQN algorithm with prioritized experience replay and double duelling Q-learning on a gym environment', 'create a ReplayBuffer instance with a fixed capacity N for storing and sampling experience transitions', 'sample prioritized transitions from the replay buffer using alpha and beta importance sampling weights', 'soft update the target network parameters using tau interpolation or hard copy every N epochs', 'compute the squared TD error loss for a batch of transitions using the learning and target models', 'run a DQN experiment on an Atari environment like PongNoFrameskip-v4 with configurable hyperparameters', 'create Atari environments wrapped with DeepMind and PyTorch wrappers for training or evaluation mode', 'create a QAgent instance with a specified model and number of actions for DQN training', 'review the Experiment class that extends DQN and selects DuelingCnnDQN or CnnDQN models', 'refactor the Experiment _create_model method to support additional CNN-based DQN model architectures', 'run a DQN experiment on CartPole-v0 using the Experiment class with config and create_env', 'create a GymEnv or GymEnvInf wrapper for n environments with optional time limit and seed', 'create a QMLP or DQMLP neural network model for the DQN agent with weight initialization', 'flatten a nested dictionary into a single-level dict with slash-separated keys']
```

Usage

```
{'run_dqn_training': 'run the DQN algorithm with prioritized experience replay and double duelling Q-learning on a gym environment', 'create_replay_buffer': 'create a ReplayBuffer instance with a fixed capacity N for storing and sampling experience transitions', 'sample_prioritized_transitions': 'sample prioritized transitions from the replay buffer using alpha and beta importance sampling weights', 'update_target_network': 'soft update the target network parameters using tau interpolation or hard copy every N epochs', 'compute_dqn_loss': 'compute the squared TD error loss for a batch of transitions using the learning and target models'}
```

## File: facebookresearch_rlstructures/rlalgos/dqn/run_atari.py

Prompts

```
['create a QAgent with a model and number of actions for epsilon-greedy action selection', 'build a QMLP neural network with linear layers and tanh activation for Q-value estimation', 'build a dueling QMLP network that separates value and advantage estimation for Q-values', 'build a CnnDQN model with convolutional feature extractor and fully connected layers for image-based RL', 'build a DuelingCnnDQN model with separate value and advantage streams for improved Q-value estimation', 'run the DQN algorithm with prioritized experience replay and double duelling Q-learning on a gym environment', 'create a ReplayBuffer instance with a fixed capacity N for storing and sampling experience transitions', 'sample prioritized transitions from the replay buffer using alpha and beta importance sampling weights', 'soft update the target network parameters using tau interpolation or hard copy every N epochs', 'compute the squared TD error loss for a batch of transitions using the learning and target models', 'run a DQN experiment on an Atari environment like PongNoFrameskip-v4 with configurable hyperparameters', 'create Atari environments wrapped with DeepMind and PyTorch wrappers for training or evaluation mode', 'create a QAgent instance with a specified model and number of actions for DQN training', 'review the Experiment class that extends DQN and selects DuelingCnnDQN or CnnDQN models', 'refactor the Experiment _create_model method to support additional CNN-based DQN model architectures', 'run a DQN experiment on CartPole-v0 using the Experiment class with config and create_env', 'create a GymEnv or GymEnvInf wrapper for n environments with optional time limit and seed', 'create a QMLP or DQMLP neural network model for the DQN agent with weight initialization', 'flatten a nested dictionary into a single-level dict with slash-separated keys']
```

Usage

```
{'run_DQN_on_Atari': 'run a DQN experiment on an Atari environment like PongNoFrameskip-v4 with configurable hyperparameters', 'create_env_Atari': 'create Atari environments wrapped with DeepMind and PyTorch wrappers for training or evaluation mode', 'create_agent_QAgent': 'create a QAgent instance with a specified model and number of actions for DQN training', 'review_Experiment_class': 'review the Experiment class that extends DQN and selects DuelingCnnDQN or CnnDQN models', 'refactor_Experiment_create_model': 'refactor the Experiment _create_model method to support additional CNN-based DQN model architectures'}
```

## File: facebookresearch_rlstructures/rlalgos/dqn/run_cartpole.py

Prompts

```
['create a QAgent with a model and number of actions for epsilon-greedy action selection', 'build a QMLP neural network with linear layers and tanh activation for Q-value estimation', 'build a dueling QMLP network that separates value and advantage estimation for Q-values', 'build a CnnDQN model with convolutional feature extractor and fully connected layers for image-based RL', 'build a DuelingCnnDQN model with separate value and advantage streams for improved Q-value estimation', 'run the DQN algorithm with prioritized experience replay and double duelling Q-learning on a gym environment', 'create a ReplayBuffer instance with a fixed capacity N for storing and sampling experience transitions', 'sample prioritized transitions from the replay buffer using alpha and beta importance sampling weights', 'soft update the target network parameters using tau interpolation or hard copy every N epochs', 'compute the squared TD error loss for a batch of transitions using the learning and target models', 'run a DQN experiment on an Atari environment like PongNoFrameskip-v4 with configurable hyperparameters', 'create Atari environments wrapped with DeepMind and PyTorch wrappers for training or evaluation mode', 'create a QAgent instance with a specified model and number of actions for DQN training', 'review the Experiment class that extends DQN and selects DuelingCnnDQN or CnnDQN models', 'refactor the Experiment _create_model method to support additional CNN-based DQN model architectures', 'run a DQN experiment on CartPole-v0 using the Experiment class with config and create_env', 'create a GymEnv or GymEnvInf wrapper for n environments with optional time limit and seed', 'create a QMLP or DQMLP neural network model for the DQN agent with weight initialization', 'flatten a nested dictionary into a single-level dict with slash-separated keys']
```

Usage

```
{'run_DQN_CartPole': 'run a DQN experiment on CartPole-v0 using the Experiment class with config and create_env', 'create_env_GymEnv': 'create a GymEnv or GymEnvInf wrapper for n environments with optional time limit and seed', 'create_agent_QAgent': 'create a QAgent instance with a model and number of actions for DQN training', 'create_model_QMLP_DQMLP': 'create a QMLP or DQMLP neural network model for the DQN agent with weight initialization', 'flatten_dict': 'flatten a nested dictionary into a single-level dict with slash-separated keys'}
```

