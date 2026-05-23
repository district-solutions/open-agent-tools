# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/deprecated/a2c/a2c_episodes.py

Prompts

```
['run the A2CGAE training loop with Adam optimizer and gradient clipping on trajectories', 'create an A2CGAE experiment instance with config, environment factory, and agent factory', 'review the get_loss method that computes value loss, entropy loss, and reinforce loss from trajectories', 'summarize the get_gae method that computes Generalized Advantage Estimation with discount and lambda parameters', 'test the check_arguments method to validate evaluation rollouts and evaluation mode configuration', 'create an NNAgent instance with a model and number of actions for discrete action selection', 'run one step of the NNAgent to sample an action given an observation and state', 'update the NNAgent model weights by loading a new state dictionary', 'create an MLPAgentModel with linear layers for action scoring and value estimation', 'create a GRUAgentModel with a GRU cell for recurrent action scoring and value estimation', 'run the A2C CartPole experiment using Hydra config and the Experiment class', 'create a Gym environment from a config dict with the environment name key', 'create multiple Gym environments wrapped with TimeLimit and bundled into a GymEnv', 'create an NNAgent instance from a PyTorch model and number of actions', 'recursively flatten a nested OmegaConf DictConfig into a flat dictionary with slash-separated keys', 'run the A2C partial observability experiment on CartPole using Hydra config and GRU agent model', 'flatten a nested Hydra DictConfig into a flat dictionary with slash-separated keys']
```

Usage

```
{'run_A2CGAE_training': 'run the A2CGAE training loop with Adam optimizer and gradient clipping on trajectories', 'create_A2CGAE_experiment': 'create an A2CGAE experiment instance with config, environment factory, and agent factory', 'review_get_loss': 'review the get_loss method that computes value loss, entropy loss, and reinforce loss from trajectories', 'summarize_get_gae': 'summarize the get_gae method that computes Generalized Advantage Estimation with discount and lambda parameters', 'test_check_arguments': 'test the check_arguments method to validate evaluation rollouts and evaluation mode configuration'}
```

## File: facebookresearch_rlstructures/rlalgos/deprecated/a2c/agent.py

Prompts

```
['run the A2CGAE training loop with Adam optimizer and gradient clipping on trajectories', 'create an A2CGAE experiment instance with config, environment factory, and agent factory', 'review the get_loss method that computes value loss, entropy loss, and reinforce loss from trajectories', 'summarize the get_gae method that computes Generalized Advantage Estimation with discount and lambda parameters', 'test the check_arguments method to validate evaluation rollouts and evaluation mode configuration', 'create an NNAgent instance with a model and number of actions for discrete action selection', 'run one step of the NNAgent to sample an action given an observation and state', 'update the NNAgent model weights by loading a new state dictionary', 'create an MLPAgentModel with linear layers for action scoring and value estimation', 'create a GRUAgentModel with a GRU cell for recurrent action scoring and value estimation', 'run the A2C CartPole experiment using Hydra config and the Experiment class', 'create a Gym environment from a config dict with the environment name key', 'create multiple Gym environments wrapped with TimeLimit and bundled into a GymEnv', 'create an NNAgent instance from a PyTorch model and number of actions', 'recursively flatten a nested OmegaConf DictConfig into a flat dictionary with slash-separated keys', 'run the A2C partial observability experiment on CartPole using Hydra config and GRU agent model', 'flatten a nested Hydra DictConfig into a flat dictionary with slash-separated keys']
```

Usage

```
{'create_NNAgent': 'create an NNAgent instance with a model and number of actions for discrete action selection', 'run_NNAgent_call': 'run one step of the NNAgent to sample an action given an observation and state', 'update_NNAgent_model': 'update the NNAgent model weights by loading a new state dictionary', 'create_MLPAgentModel': 'create an MLPAgentModel with linear layers for action scoring and value estimation', 'create_GRUAgentModel': 'create a GRUAgentModel with a GRU cell for recurrent action scoring and value estimation'}
```

## File: facebookresearch_rlstructures/rlalgos/deprecated/a2c/run_cartpole.py

Prompts

```
['run the A2CGAE training loop with Adam optimizer and gradient clipping on trajectories', 'create an A2CGAE experiment instance with config, environment factory, and agent factory', 'review the get_loss method that computes value loss, entropy loss, and reinforce loss from trajectories', 'summarize the get_gae method that computes Generalized Advantage Estimation with discount and lambda parameters', 'test the check_arguments method to validate evaluation rollouts and evaluation mode configuration', 'create an NNAgent instance with a model and number of actions for discrete action selection', 'run one step of the NNAgent to sample an action given an observation and state', 'update the NNAgent model weights by loading a new state dictionary', 'create an MLPAgentModel with linear layers for action scoring and value estimation', 'create a GRUAgentModel with a GRU cell for recurrent action scoring and value estimation', 'run the A2C CartPole experiment using Hydra config and the Experiment class', 'create a Gym environment from a config dict with the environment name key', 'create multiple Gym environments wrapped with TimeLimit and bundled into a GymEnv', 'create an NNAgent instance from a PyTorch model and number of actions', 'recursively flatten a nested OmegaConf DictConfig into a flat dictionary with slash-separated keys', 'run the A2C partial observability experiment on CartPole using Hydra config and GRU agent model', 'flatten a nested Hydra DictConfig into a flat dictionary with slash-separated keys']
```

Usage

```
{'run_a2c_cartpole_experiment': 'run the A2C CartPole experiment using Hydra config and the Experiment class', 'create_gym_environment': 'create a Gym environment from a config dict with the environment name key', 'create_wrapped_env': 'create multiple Gym environments wrapped with TimeLimit and bundled into a GymEnv', 'create_nn_agent': 'create an NNAgent instance from a PyTorch model and number of actions', 'flatten_omegaconf_dict': 'recursively flatten a nested OmegaConf DictConfig into a flat dictionary with slash-separated keys'}
```

## File: facebookresearch_rlstructures/rlalgos/deprecated/a2c/run_cartpole_pomdp.py

Prompts

```
['run the A2CGAE training loop with Adam optimizer and gradient clipping on trajectories', 'create an A2CGAE experiment instance with config, environment factory, and agent factory', 'review the get_loss method that computes value loss, entropy loss, and reinforce loss from trajectories', 'summarize the get_gae method that computes Generalized Advantage Estimation with discount and lambda parameters', 'test the check_arguments method to validate evaluation rollouts and evaluation mode configuration', 'create an NNAgent instance with a model and number of actions for discrete action selection', 'run one step of the NNAgent to sample an action given an observation and state', 'update the NNAgent model weights by loading a new state dictionary', 'create an MLPAgentModel with linear layers for action scoring and value estimation', 'create a GRUAgentModel with a GRU cell for recurrent action scoring and value estimation', 'run the A2C CartPole experiment using Hydra config and the Experiment class', 'create a Gym environment from a config dict with the environment name key', 'create multiple Gym environments wrapped with TimeLimit and bundled into a GymEnv', 'create an NNAgent instance from a PyTorch model and number of actions', 'recursively flatten a nested OmegaConf DictConfig into a flat dictionary with slash-separated keys', 'run the A2C partial observability experiment on CartPole using Hydra config and GRU agent model', 'flatten a nested Hydra DictConfig into a flat dictionary with slash-separated keys']
```

Usage

```
{'run_A2C_POMDP_experiment': 'run the A2C partial observability experiment on CartPole using Hydra config and GRU agent model', 'create_gym_environment': 'create a Gym environment from a config dict with the environment name key', 'create_wrapped_env': 'create multiple wrapped Gym environments with MyWrapper and TimeLimit wrappers for A2C training', 'create_NNAgent': 'create an NNAgent instance from a model and number of actions for reinforcement learning', 'flatten_DictConfig': 'flatten a nested Hydra DictConfig into a flat dictionary with slash-separated keys'}
```

