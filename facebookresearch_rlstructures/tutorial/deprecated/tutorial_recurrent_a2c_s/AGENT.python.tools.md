# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_recurrent_a2c_s/a2c.py

Prompts

```
['run the A2C reinforcement learning training loop with config, environments, and agent factories', 'create an A2C instance with config, train env factory, eval env factory, and agent factory', 'compute the A2C critic loss, actor loss, and entropy loss from replayed trajectories', 'review the A2C run method that manages training and evaluation batchers in a time-limited loop', 'refactor the A2C get_loss method to support custom loss weighting or additional loss terms', 'build a recurrent A2C agent with an action model and critic model for reinforcement learning', 'create an action model with an RNN cell that outputs action probabilities from observation frames', 'create a critic model that computes state value V(s) from hidden state and observation frames', 'test the RecurrentAgent call_replay method to verify action probabilities match stored trajectory data', 'refactor the ActionModel forward pass to support custom activation functions or additional input features', 'create a gym environment by calling gym.make with the specified environment name', 'create multiple gym environments wrapped in GymEnv with TimeLimit for evaluation', 'create multiple gym environments wrapped in GymEnvInf with TimeLimit for training', 'create a RecurrentAgent instance with a given model and number of actions', 'run an A2C reinforcement learning experiment on CartPole-v0 with configurable hyperparameters']
```

Usage

```
{'run_A2C_training': 'run the A2C reinforcement learning training loop with config, environments, and agent factories', 'create_A2C_instance': 'create an A2C instance with config, train env factory, eval env factory, and agent factory', 'compute_get_loss': 'compute the A2C critic loss, actor loss, and entropy loss from replayed trajectories', 'review_A2C_run': 'review the A2C run method that manages training and evaluation batchers in a time-limited loop', 'refactor_A2C_get_loss': 'refactor the A2C get_loss method to support custom loss weighting or additional loss terms'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_recurrent_a2c_s/agent.py

Prompts

```
['run the A2C reinforcement learning training loop with config, environments, and agent factories', 'create an A2C instance with config, train env factory, eval env factory, and agent factory', 'compute the A2C critic loss, actor loss, and entropy loss from replayed trajectories', 'review the A2C run method that manages training and evaluation batchers in a time-limited loop', 'refactor the A2C get_loss method to support custom loss weighting or additional loss terms', 'build a recurrent A2C agent with an action model and critic model for reinforcement learning', 'create an action model with an RNN cell that outputs action probabilities from observation frames', 'create a critic model that computes state value V(s) from hidden state and observation frames', 'test the RecurrentAgent call_replay method to verify action probabilities match stored trajectory data', 'refactor the ActionModel forward pass to support custom activation functions or additional input features', 'create a gym environment by calling gym.make with the specified environment name', 'create multiple gym environments wrapped in GymEnv with TimeLimit for evaluation', 'create multiple gym environments wrapped in GymEnvInf with TimeLimit for training', 'create a RecurrentAgent instance with a given model and number of actions', 'run an A2C reinforcement learning experiment on CartPole-v0 with configurable hyperparameters']
```

Usage

```
{'build_RecurrentAgent': 'build a recurrent A2C agent with an action model and critic model for reinforcement learning', 'create_ActionModel': 'create an action model with an RNN cell that outputs action probabilities from observation frames', 'create_CriticModel': 'create a critic model that computes state value V(s) from hidden state and observation frames', 'test_RecurrentAgent_call_replay': 'test the RecurrentAgent call_replay method to verify action probabilities match stored trajectory data', 'refactor_ActionModel_forward': 'refactor the ActionModel forward pass to support custom activation functions or additional input features'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_recurrent_a2c_s/main_a2c.py

Prompts

```
['run the A2C reinforcement learning training loop with config, environments, and agent factories', 'create an A2C instance with config, train env factory, eval env factory, and agent factory', 'compute the A2C critic loss, actor loss, and entropy loss from replayed trajectories', 'review the A2C run method that manages training and evaluation batchers in a time-limited loop', 'refactor the A2C get_loss method to support custom loss weighting or additional loss terms', 'build a recurrent A2C agent with an action model and critic model for reinforcement learning', 'create an action model with an RNN cell that outputs action probabilities from observation frames', 'create a critic model that computes state value V(s) from hidden state and observation frames', 'test the RecurrentAgent call_replay method to verify action probabilities match stored trajectory data', 'refactor the ActionModel forward pass to support custom activation functions or additional input features', 'create a gym environment by calling gym.make with the specified environment name', 'create multiple gym environments wrapped in GymEnv with TimeLimit for evaluation', 'create multiple gym environments wrapped in GymEnvInf with TimeLimit for training', 'create a RecurrentAgent instance with a given model and number of actions', 'run an A2C reinforcement learning experiment on CartPole-v0 with configurable hyperparameters']
```

Usage

```
{'create_gym_env': 'create a gym environment by calling gym.make with the specified environment name', 'create_env': 'create multiple gym environments wrapped in GymEnv with TimeLimit for evaluation', 'create_train_env': 'create multiple gym environments wrapped in GymEnvInf with TimeLimit for training', 'create_agent': 'create a RecurrentAgent instance with a given model and number of actions', 'run_experiment': 'run an A2C reinforcement learning experiment on CartPole-v0 with configurable hyperparameters'}
```

