# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_recurrent_policy/a2c.py

Prompts

```
['run the A2C class to train a recurrent policy agent using parallel environment batchers', 'create an A2C instance with config, environment factories, and agent factory for recurrent policy training', 'compute the critic loss, A2C loss, and entropy loss from sampled trajectories using get_loss', 'review the A2C run method training loop that alternates between sampling trajectories and gradient updates', 'summarize how A2C computes temporal difference targets using critic values and discounted rewards', 'create a RecurrentAgent instance with a model and number of actions for recurrent policy execution', 'call the RecurrentAgent to execute one step and return action probabilities and new state', 'update the RecurrentAgent model weights by loading a new state dictionary', 'build an AgentModel neural network that computes action scores from observations and hidden state', 'build a BaselineModel neural network that computes state value V(s) for the critic', 'create a gym environment by calling gym.make with the given environment name string', 'create a batch of GymEnv instances with TimeLimit wrappers for parallel environment execution', 'create a batch of GymEnvInf instances for training with multiple parallel environments', 'create a RecurrentAgent instance with a given model and number of action dimensions', 'run an A2C reinforcement learning experiment on CartPole-v0 using the Experiment class']
```

Usage

```
{'run_A2C_training': 'run the A2C class to train a recurrent policy agent using parallel environment batchers', 'create_A2C_instance': 'create an A2C instance with config, environment factories, and agent factory for recurrent policy training', 'compute_get_loss': 'compute the critic loss, A2C loss, and entropy loss from sampled trajectories using get_loss', 'review_A2C_run_loop': 'review the A2C run method training loop that alternates between sampling trajectories and gradient updates', 'summarize_A2C_temporal_difference': 'summarize how A2C computes temporal difference targets using critic values and discounted rewards'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_recurrent_policy/agent.py

Prompts

```
['run the A2C class to train a recurrent policy agent using parallel environment batchers', 'create an A2C instance with config, environment factories, and agent factory for recurrent policy training', 'compute the critic loss, A2C loss, and entropy loss from sampled trajectories using get_loss', 'review the A2C run method training loop that alternates between sampling trajectories and gradient updates', 'summarize how A2C computes temporal difference targets using critic values and discounted rewards', 'create a RecurrentAgent instance with a model and number of actions for recurrent policy execution', 'call the RecurrentAgent to execute one step and return action probabilities and new state', 'update the RecurrentAgent model weights by loading a new state dictionary', 'build an AgentModel neural network that computes action scores from observations and hidden state', 'build a BaselineModel neural network that computes state value V(s) for the critic', 'create a gym environment by calling gym.make with the given environment name string', 'create a batch of GymEnv instances with TimeLimit wrappers for parallel environment execution', 'create a batch of GymEnvInf instances for training with multiple parallel environments', 'create a RecurrentAgent instance with a given model and number of action dimensions', 'run an A2C reinforcement learning experiment on CartPole-v0 using the Experiment class']
```

Usage

```
{'create_RecurrentAgent': 'create a RecurrentAgent instance with a model and number of actions for recurrent policy execution', 'call_RecurrentAgent_step': 'call the RecurrentAgent to execute one step and return action probabilities and new state', 'update_RecurrentAgent_model': 'update the RecurrentAgent model weights by loading a new state dictionary', 'build_AgentModel': 'build an AgentModel neural network that computes action scores from observations and hidden state', 'build_BaselineModel': 'build a BaselineModel neural network that computes state value V(s) for the critic'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_recurrent_policy/main_a2c.py

Prompts

```
['run the A2C class to train a recurrent policy agent using parallel environment batchers', 'create an A2C instance with config, environment factories, and agent factory for recurrent policy training', 'compute the critic loss, A2C loss, and entropy loss from sampled trajectories using get_loss', 'review the A2C run method training loop that alternates between sampling trajectories and gradient updates', 'summarize how A2C computes temporal difference targets using critic values and discounted rewards', 'create a RecurrentAgent instance with a model and number of actions for recurrent policy execution', 'call the RecurrentAgent to execute one step and return action probabilities and new state', 'update the RecurrentAgent model weights by loading a new state dictionary', 'build an AgentModel neural network that computes action scores from observations and hidden state', 'build a BaselineModel neural network that computes state value V(s) for the critic', 'create a gym environment by calling gym.make with the given environment name string', 'create a batch of GymEnv instances with TimeLimit wrappers for parallel environment execution', 'create a batch of GymEnvInf instances for training with multiple parallel environments', 'create a RecurrentAgent instance with a given model and number of action dimensions', 'run an A2C reinforcement learning experiment on CartPole-v0 using the Experiment class']
```

Usage

```
{'create_gym_env': 'create a gym environment by calling gym.make with the given environment name string', 'create_env': 'create a batch of GymEnv instances with TimeLimit wrappers for parallel environment execution', 'create_train_env': 'create a batch of GymEnvInf instances for training with multiple parallel environments', 'create_agent': 'create a RecurrentAgent instance with a given model and number of action dimensions', 'run_experiment': 'run an A2C reinforcement learning experiment on CartPole-v0 using the Experiment class'}
```

