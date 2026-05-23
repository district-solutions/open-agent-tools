# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/simple_ddqn/agent.py

Prompts

```
['create a QAgent instance with a model and number of actions for epsilon-greedy action selection', 'call the QAgent to select actions using epsilon-greedy policy based on observation frames', 'update the QAgent model weights by loading a new state dictionary', 'create a DQMLP neural network with dueling architecture for value and advantage estimation', 'run a forward pass through the DQMLP network to compute Q-values from state inputs', 'create a ReplayBuffer with capacity N to store and sample experience transitions for DQN training', 'push trajectory transitions into the ReplayBuffer using the push method for experience replay', 'sample n random transitions from the ReplayBuffer for training the DQN agent', 'run the DQN training loop with config, environment factory, and agent factory to learn a policy', 'compute the double DQN loss from sampled transitions using the learning and target models', 'run a Double DQN experiment on the CartPole-v0 Gym environment with configurable hyperparameters', 'create a list of Gym environments wrapped with TimeLimit and return as GymEnv or GymEnvInf', 'create a QAgent instance with a given model and number of actions for DQN training', 'create a DQMLP neural network module with weight initialization for the observation space and action count', 'flatten a nested dictionary or DictConfig into a single-level dictionary with slash-separated keys']
```

Usage

```
{'create_QAgent': 'create a QAgent instance with a model and number of actions for epsilon-greedy action selection', 'call_QAgent': 'call the QAgent to select actions using epsilon-greedy policy based on observation frames', 'update_QAgent': 'update the QAgent model weights by loading a new state dictionary', 'create_DQMLP': 'create a DQMLP neural network with dueling architecture for value and advantage estimation', 'forward_DQMLP': 'run a forward pass through the DQMLP network to compute Q-values from state inputs'}
```

## File: facebookresearch_rlstructures/rlalgos/simple_ddqn/ddqn.py

Prompts

```
['create a QAgent instance with a model and number of actions for epsilon-greedy action selection', 'call the QAgent to select actions using epsilon-greedy policy based on observation frames', 'update the QAgent model weights by loading a new state dictionary', 'create a DQMLP neural network with dueling architecture for value and advantage estimation', 'run a forward pass through the DQMLP network to compute Q-values from state inputs', 'create a ReplayBuffer with capacity N to store and sample experience transitions for DQN training', 'push trajectory transitions into the ReplayBuffer using the push method for experience replay', 'sample n random transitions from the ReplayBuffer for training the DQN agent', 'run the DQN training loop with config, environment factory, and agent factory to learn a policy', 'compute the double DQN loss from sampled transitions using the learning and target models', 'run a Double DQN experiment on the CartPole-v0 Gym environment with configurable hyperparameters', 'create a list of Gym environments wrapped with TimeLimit and return as GymEnv or GymEnvInf', 'create a QAgent instance with a given model and number of actions for DQN training', 'create a DQMLP neural network module with weight initialization for the observation space and action count', 'flatten a nested dictionary or DictConfig into a single-level dictionary with slash-separated keys']
```

Usage

```
{'create_replay_buffer': 'create a ReplayBuffer with capacity N to store and sample experience transitions for DQN training', 'push_transitions_to_buffer': 'push trajectory transitions into the ReplayBuffer using the push method for experience replay', 'sample_replay_buffer': 'sample n random transitions from the ReplayBuffer for training the DQN agent', 'run_ddqn_training': 'run the DQN training loop with config, environment factory, and agent factory to learn a policy', 'compute_ddqn_loss': 'compute the double DQN loss from sampled transitions using the learning and target models'}
```

## File: facebookresearch_rlstructures/rlalgos/simple_ddqn/run_cartpole.py

Prompts

```
['create a QAgent instance with a model and number of actions for epsilon-greedy action selection', 'call the QAgent to select actions using epsilon-greedy policy based on observation frames', 'update the QAgent model weights by loading a new state dictionary', 'create a DQMLP neural network with dueling architecture for value and advantage estimation', 'run a forward pass through the DQMLP network to compute Q-values from state inputs', 'create a ReplayBuffer with capacity N to store and sample experience transitions for DQN training', 'push trajectory transitions into the ReplayBuffer using the push method for experience replay', 'sample n random transitions from the ReplayBuffer for training the DQN agent', 'run the DQN training loop with config, environment factory, and agent factory to learn a policy', 'compute the double DQN loss from sampled transitions using the learning and target models', 'run a Double DQN experiment on the CartPole-v0 Gym environment with configurable hyperparameters', 'create a list of Gym environments wrapped with TimeLimit and return as GymEnv or GymEnvInf', 'create a QAgent instance with a given model and number of actions for DQN training', 'create a DQMLP neural network module with weight initialization for the observation space and action count', 'flatten a nested dictionary or DictConfig into a single-level dictionary with slash-separated keys']
```

Usage

```
{'run_DDQN_CartPole': 'run a Double DQN experiment on the CartPole-v0 Gym environment with configurable hyperparameters', 'create_env_GymEnv': 'create a list of Gym environments wrapped with TimeLimit and return as GymEnv or GymEnvInf', 'create_agent_QAgent': 'create a QAgent instance with a given model and number of actions for DQN training', 'create_model_DQMLP': 'create a DQMLP neural network module with weight initialization for the observation space and action count', 'flatten_dict': 'flatten a nested dictionary or DictConfig into a single-level dictionary with slash-separated keys'}
```

