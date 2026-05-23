# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/a2c_gae/a2c.py

Prompts

```
['run the A2C reinforcement learning training loop with config, environments, and agent', 'create an A2C instance with config, train environment, environment, and agent factory functions', 'compute the critic loss, A2C loss, and entropy loss from agent trajectories', 'calculate Generalized Advantage Estimation from done flags, rewards, and critic values', "extract and move a model's state dict tensors to a specified device", 'build a recurrent action model with RNNCell that outputs softmax action probabilities from observation frames', 'build a critic model that computes state value V(s) by concatenating frame features with hidden state', 'build a recurrent RL agent that samples actions stochastically or greedily based on agent info flags', 'test the RecurrentAgent call_replay method to verify action probabilities match during trajectory replay', 'review the Model class that wraps an action model and critic model as a single PyTorch module', 'create an ActionModel CNN network that outputs softmax action probabilities for Atari frames', 'create a CriticModel CNN network that computes state value V(s) for Atari frames', 'build a Model combining an ActionModel and CriticModel for A2C reinforcement learning', 'run one step of the AtariAgent to sample actions from observation frames', 'review the AtariAgent call_replay method that recomputes critic values and action probabilities from trajectories', 'create Atari environments with DeepMind and PyTorch wrappers for evaluation', 'create infinite Atari training environments with DeepMind wrappers for A2C learning', 'create an AtariAgent instance with a given model and number of actions', 'run the A2C experiment with config for PongNoFrameskip-v4 Atari environment training', 'create an ActionModel and CriticModel combined into a Model for Atari tasks', 'create a Gym environment by calling gym.make with a given environment name string']
```

Usage

```
{'run_A2C_training': 'run the A2C reinforcement learning training loop with config, environments, and agent', 'create_A2C_instance': 'create an A2C instance with config, train environment, environment, and agent factory functions', 'compute_loss_trajectories': 'compute the critic loss, A2C loss, and entropy loss from agent trajectories', 'calculate_GAE': 'calculate Generalized Advantage Estimation from done flags, rewards, and critic values', 'extract_state_dict': "extract and move a model's state dict tensors to a specified device"}
```

## File: facebookresearch_rlstructures/rlalgos/a2c_gae/agent.py

Prompts

```
['run the A2C reinforcement learning training loop with config, environments, and agent', 'create an A2C instance with config, train environment, environment, and agent factory functions', 'compute the critic loss, A2C loss, and entropy loss from agent trajectories', 'calculate Generalized Advantage Estimation from done flags, rewards, and critic values', "extract and move a model's state dict tensors to a specified device", 'build a recurrent action model with RNNCell that outputs softmax action probabilities from observation frames', 'build a critic model that computes state value V(s) by concatenating frame features with hidden state', 'build a recurrent RL agent that samples actions stochastically or greedily based on agent info flags', 'test the RecurrentAgent call_replay method to verify action probabilities match during trajectory replay', 'review the Model class that wraps an action model and critic model as a single PyTorch module', 'create an ActionModel CNN network that outputs softmax action probabilities for Atari frames', 'create a CriticModel CNN network that computes state value V(s) for Atari frames', 'build a Model combining an ActionModel and CriticModel for A2C reinforcement learning', 'run one step of the AtariAgent to sample actions from observation frames', 'review the AtariAgent call_replay method that recomputes critic values and action probabilities from trajectories', 'create Atari environments with DeepMind and PyTorch wrappers for evaluation', 'create infinite Atari training environments with DeepMind wrappers for A2C learning', 'create an AtariAgent instance with a given model and number of actions', 'run the A2C experiment with config for PongNoFrameskip-v4 Atari environment training', 'create an ActionModel and CriticModel combined into a Model for Atari tasks', 'create a Gym environment by calling gym.make with a given environment name string']
```

Usage

```
{'build_ActionModel': 'build a recurrent action model with RNNCell that outputs softmax action probabilities from observation frames', 'build_CriticModel': 'build a critic model that computes state value V(s) by concatenating frame features with hidden state', 'build_RecurrentAgent': 'build a recurrent RL agent that samples actions stochastically or greedily based on agent info flags', 'test_RecurrentAgent_call_replay': 'test the RecurrentAgent call_replay method to verify action probabilities match during trajectory replay', 'review_Model': 'review the Model class that wraps an action model and critic model as a single PyTorch module'}
```

## File: facebookresearch_rlstructures/rlalgos/a2c_gae/atari_agent.py

Prompts

```
['run the A2C reinforcement learning training loop with config, environments, and agent', 'create an A2C instance with config, train environment, environment, and agent factory functions', 'compute the critic loss, A2C loss, and entropy loss from agent trajectories', 'calculate Generalized Advantage Estimation from done flags, rewards, and critic values', "extract and move a model's state dict tensors to a specified device", 'build a recurrent action model with RNNCell that outputs softmax action probabilities from observation frames', 'build a critic model that computes state value V(s) by concatenating frame features with hidden state', 'build a recurrent RL agent that samples actions stochastically or greedily based on agent info flags', 'test the RecurrentAgent call_replay method to verify action probabilities match during trajectory replay', 'review the Model class that wraps an action model and critic model as a single PyTorch module', 'create an ActionModel CNN network that outputs softmax action probabilities for Atari frames', 'create a CriticModel CNN network that computes state value V(s) for Atari frames', 'build a Model combining an ActionModel and CriticModel for A2C reinforcement learning', 'run one step of the AtariAgent to sample actions from observation frames', 'review the AtariAgent call_replay method that recomputes critic values and action probabilities from trajectories', 'create Atari environments with DeepMind and PyTorch wrappers for evaluation', 'create infinite Atari training environments with DeepMind wrappers for A2C learning', 'create an AtariAgent instance with a given model and number of actions', 'run the A2C experiment with config for PongNoFrameskip-v4 Atari environment training', 'create an ActionModel and CriticModel combined into a Model for Atari tasks', 'create a Gym environment by calling gym.make with a given environment name string']
```

Usage

```
{'create_ActionModel': 'create an ActionModel CNN network that outputs softmax action probabilities for Atari frames', 'create_CriticModel': 'create a CriticModel CNN network that computes state value V(s) for Atari frames', 'build_Model': 'build a Model combining an ActionModel and CriticModel for A2C reinforcement learning', 'run_A AtariAgent_call': 'run one step of the AtariAgent to sample actions from observation frames', 'review_A AtariAgent_call_replay': 'review the AtariAgent call_replay method that recomputes critic values and action probabilities from trajectories'}
```

## File: facebookresearch_rlstructures/rlalgos/a2c_gae/main_atari.py

Prompts

```
['run the A2C reinforcement learning training loop with config, environments, and agent', 'create an A2C instance with config, train environment, environment, and agent factory functions', 'compute the critic loss, A2C loss, and entropy loss from agent trajectories', 'calculate Generalized Advantage Estimation from done flags, rewards, and critic values', "extract and move a model's state dict tensors to a specified device", 'build a recurrent action model with RNNCell that outputs softmax action probabilities from observation frames', 'build a critic model that computes state value V(s) by concatenating frame features with hidden state', 'build a recurrent RL agent that samples actions stochastically or greedily based on agent info flags', 'test the RecurrentAgent call_replay method to verify action probabilities match during trajectory replay', 'review the Model class that wraps an action model and critic model as a single PyTorch module', 'create an ActionModel CNN network that outputs softmax action probabilities for Atari frames', 'create a CriticModel CNN network that computes state value V(s) for Atari frames', 'build a Model combining an ActionModel and CriticModel for A2C reinforcement learning', 'run one step of the AtariAgent to sample actions from observation frames', 'review the AtariAgent call_replay method that recomputes critic values and action probabilities from trajectories', 'create Atari environments with DeepMind and PyTorch wrappers for evaluation', 'create infinite Atari training environments with DeepMind wrappers for A2C learning', 'create an AtariAgent instance with a given model and number of actions', 'run the A2C experiment with config for PongNoFrameskip-v4 Atari environment training', 'create an ActionModel and CriticModel combined into a Model for Atari tasks', 'create a Gym environment by calling gym.make with a given environment name string']
```

Usage

```
{'create_env': 'create Atari environments with DeepMind and PyTorch wrappers for evaluation', 'create_train_env': 'create infinite Atari training environments with DeepMind wrappers for A2C learning', 'create_agent': 'create an AtariAgent instance with a given model and number of actions', 'run_Experiment': 'run the A2C experiment with config for PongNoFrameskip-v4 Atari environment training', 'create_model_Experiment': 'create an ActionModel and CriticModel combined into a Model for Atari tasks'}
```

## File: facebookresearch_rlstructures/rlalgos/a2c_gae/main_cartpole.py

Prompts

```
['run the A2C reinforcement learning training loop with config, environments, and agent', 'create an A2C instance with config, train environment, environment, and agent factory functions', 'compute the critic loss, A2C loss, and entropy loss from agent trajectories', 'calculate Generalized Advantage Estimation from done flags, rewards, and critic values', "extract and move a model's state dict tensors to a specified device", 'build a recurrent action model with RNNCell that outputs softmax action probabilities from observation frames', 'build a critic model that computes state value V(s) by concatenating frame features with hidden state', 'build a recurrent RL agent that samples actions stochastically or greedily based on agent info flags', 'test the RecurrentAgent call_replay method to verify action probabilities match during trajectory replay', 'review the Model class that wraps an action model and critic model as a single PyTorch module', 'create an ActionModel CNN network that outputs softmax action probabilities for Atari frames', 'create a CriticModel CNN network that computes state value V(s) for Atari frames', 'build a Model combining an ActionModel and CriticModel for A2C reinforcement learning', 'run one step of the AtariAgent to sample actions from observation frames', 'review the AtariAgent call_replay method that recomputes critic values and action probabilities from trajectories', 'create Atari environments with DeepMind and PyTorch wrappers for evaluation', 'create infinite Atari training environments with DeepMind wrappers for A2C learning', 'create an AtariAgent instance with a given model and number of actions', 'run the A2C experiment with config for PongNoFrameskip-v4 Atari environment training', 'create an ActionModel and CriticModel combined into a Model for Atari tasks', 'create a Gym environment by calling gym.make with a given environment name string']
```

Usage

```
{'create_gym_env': 'create a Gym environment by calling gym.make with a given environment name string', 'create_env': 'create multiple Gym environments wrapped with TimeLimit and returned as a GymEnv batch', 'create_train_env': 'create multiple Gym environments wrapped with TimeLimit and returned as a GymEnvInf batch for training', 'create_agent': 'create a RecurrentAgent instance with a given model and number of actions', 'run_Experiment': 'run an A2C experiment on CartPole-v0 by instantiating Experiment with a config dict and calling run'}
```

