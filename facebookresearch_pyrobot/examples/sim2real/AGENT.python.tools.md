# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/examples/sim2real/TD3.py

Prompts

```
['create a TD3 reinforcement learning agent with actor and critic networks for continuous control', 'select an action from the TD3 actor network given a state observation', 'train the TD3 agent using replay buffer samples with delayed policy updates and target networks', 'save the TD3 actor and critic network weights to disk as PyTorch checkpoint files', 'load previously saved TD3 actor and critic network weights from PyTorch checkpoint files', 'run a TD3 policy evaluation on a gym environment with configurable episodes and seed', 'run the sim2real test script with a loaded TD3 policy on LocoBotEnv-v0', 'run the TD3 policy test on a real robot with the use_real_robot flag enabled', 'evaluate a TD3 policy over multiple episodes and return the average reward', 'load a trained TD3 policy from file and test it in a gym environment', 'run TD3 reinforcement learning training on a gym environment with configurable hyperparameters', 'run TD3 training with collision checking and custom collision reward penalties enabled', 'run TD3 training and save the best performing PyTorch models to disk', 'run TD3 training with valid goal sampling and custom reaching reward configuration', 'create a ReplayBuffer instance with a custom max_size for storing RL experience tuples', 'add a tuple of state, next_state, action, reward, and done to the ReplayBuffer', 'sample a random batch of experience tuples from the ReplayBuffer as numpy arrays', 'refactor the ReplayBuffer to use a circular buffer when max_size is reached', 'review the ReplayBuffer sample method that returns batched numpy arrays for states, actions, rewards, and dones']
```

Usage

```
{'create_TD3_agent': 'create a TD3 reinforcement learning agent with actor and critic networks for continuous control', 'select_action_TD3': 'select an action from the TD3 actor network given a state observation', 'train_TD3_agent': 'train the TD3 agent using replay buffer samples with delayed policy updates and target networks', 'save_TD3_model': 'save the TD3 actor and critic network weights to disk as PyTorch checkpoint files', 'load_TD3_model': 'load previously saved TD3 actor and critic network weights from PyTorch checkpoint files'}
```

## File: facebookresearch_pyrobot/examples/sim2real/test.py

Prompts

```
['create a TD3 reinforcement learning agent with actor and critic networks for continuous control', 'select an action from the TD3 actor network given a state observation', 'train the TD3 agent using replay buffer samples with delayed policy updates and target networks', 'save the TD3 actor and critic network weights to disk as PyTorch checkpoint files', 'load previously saved TD3 actor and critic network weights from PyTorch checkpoint files', 'run a TD3 policy evaluation on a gym environment with configurable episodes and seed', 'run the sim2real test script with a loaded TD3 policy on LocoBotEnv-v0', 'run the TD3 policy test on a real robot with the use_real_robot flag enabled', 'evaluate a TD3 policy over multiple episodes and return the average reward', 'load a trained TD3 policy from file and test it in a gym environment', 'run TD3 reinforcement learning training on a gym environment with configurable hyperparameters', 'run TD3 training with collision checking and custom collision reward penalties enabled', 'run TD3 training and save the best performing PyTorch models to disk', 'run TD3 training with valid goal sampling and custom reaching reward configuration', 'create a ReplayBuffer instance with a custom max_size for storing RL experience tuples', 'add a tuple of state, next_state, action, reward, and done to the ReplayBuffer', 'sample a random batch of experience tuples from the ReplayBuffer as numpy arrays', 'refactor the ReplayBuffer to use a circular buffer when max_size is reached', 'review the ReplayBuffer sample method that returns batched numpy arrays for states, actions, rewards, and dones']
```

Usage

```
{'run_td3_policy_evaluation': 'run a TD3 policy evaluation on a gym environment with configurable episodes and seed', 'run_sim2real_test': 'run the sim2real test script with a loaded TD3 policy on LocoBotEnv-v0', 'run_real_robot_test': 'run the TD3 policy test on a real robot with the use_real_robot flag enabled', 'evaluate_policy_function': 'evaluate a TD3 policy over multiple episodes and return the average reward', 'load_and_test_td3_policy': 'load a trained TD3 policy from file and test it in a gym environment'}
```

## File: facebookresearch_pyrobot/examples/sim2real/train.py

Prompts

```
['create a TD3 reinforcement learning agent with actor and critic networks for continuous control', 'select an action from the TD3 actor network given a state observation', 'train the TD3 agent using replay buffer samples with delayed policy updates and target networks', 'save the TD3 actor and critic network weights to disk as PyTorch checkpoint files', 'load previously saved TD3 actor and critic network weights from PyTorch checkpoint files', 'run a TD3 policy evaluation on a gym environment with configurable episodes and seed', 'run the sim2real test script with a loaded TD3 policy on LocoBotEnv-v0', 'run the TD3 policy test on a real robot with the use_real_robot flag enabled', 'evaluate a TD3 policy over multiple episodes and return the average reward', 'load a trained TD3 policy from file and test it in a gym environment', 'run TD3 reinforcement learning training on a gym environment with configurable hyperparameters', 'run TD3 training with collision checking and custom collision reward penalties enabled', 'run TD3 training and save the best performing PyTorch models to disk', 'run TD3 training with valid goal sampling and custom reaching reward configuration', 'create a ReplayBuffer instance with a custom max_size for storing RL experience tuples', 'add a tuple of state, next_state, action, reward, and done to the ReplayBuffer', 'sample a random batch of experience tuples from the ReplayBuffer as numpy arrays', 'refactor the ReplayBuffer to use a circular buffer when max_size is reached', 'review the ReplayBuffer sample method that returns batched numpy arrays for states, actions, rewards, and dones']
```

Usage

```
{'run_td3_training': 'run TD3 reinforcement learning training on a gym environment with configurable hyperparameters', 'run_training_with_collision': 'run TD3 training with collision checking and custom collision reward penalties enabled', 'run_training_save_models': 'run TD3 training and save the best performing PyTorch models to disk', 'evaluate_policy_function': 'evaluate a TD3 policy over multiple episodes and return the average reward', 'run_training_valid_goals': 'run TD3 training with valid goal sampling and custom reaching reward configuration'}
```

## File: facebookresearch_pyrobot/examples/sim2real/utils.py

Prompts

```
['create a TD3 reinforcement learning agent with actor and critic networks for continuous control', 'select an action from the TD3 actor network given a state observation', 'train the TD3 agent using replay buffer samples with delayed policy updates and target networks', 'save the TD3 actor and critic network weights to disk as PyTorch checkpoint files', 'load previously saved TD3 actor and critic network weights from PyTorch checkpoint files', 'run a TD3 policy evaluation on a gym environment with configurable episodes and seed', 'run the sim2real test script with a loaded TD3 policy on LocoBotEnv-v0', 'run the TD3 policy test on a real robot with the use_real_robot flag enabled', 'evaluate a TD3 policy over multiple episodes and return the average reward', 'load a trained TD3 policy from file and test it in a gym environment', 'run TD3 reinforcement learning training on a gym environment with configurable hyperparameters', 'run TD3 training with collision checking and custom collision reward penalties enabled', 'run TD3 training and save the best performing PyTorch models to disk', 'run TD3 training with valid goal sampling and custom reaching reward configuration', 'create a ReplayBuffer instance with a custom max_size for storing RL experience tuples', 'add a tuple of state, next_state, action, reward, and done to the ReplayBuffer', 'sample a random batch of experience tuples from the ReplayBuffer as numpy arrays', 'refactor the ReplayBuffer to use a circular buffer when max_size is reached', 'review the ReplayBuffer sample method that returns batched numpy arrays for states, actions, rewards, and dones']
```

Usage

```
{'create_ReplayBuffer': 'create a ReplayBuffer instance with a custom max_size for storing RL experience tuples', 'add_experience_to_ReplayBuffer': 'add a tuple of state, next_state, action, reward, and done to the ReplayBuffer', 'sample_from_ReplayBuffer': 'sample a random batch of experience tuples from the ReplayBuffer as numpy arrays', 'refactor_ReplayBuffer_max_size': 'refactor the ReplayBuffer to use a circular buffer when max_size is reached', 'review_ReplayBuffer_sample': 'review the ReplayBuffer sample method that returns batched numpy arrays for states, actions, rewards, and dones'}
```

