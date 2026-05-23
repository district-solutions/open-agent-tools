# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/reinforce_diayn/agent.py

Prompts

```
['create a DIAYNAgent instance with a DIAYNModel and number of actions for reinforcement learning', 'run one step of the DIAYNAgent to sample actions and compute baselines from observations', 'build a DIAYNActionModel neural network that computes softmax action probabilities per policy index', 'build a DIAYNBaselineModel neural network that computes state value V(s) per policy index', 'update the DIAYNAgent model weights by loading a PyTorch state dictionary', 'run the Reinforce class training loop with DIAYN discriminator for offline RL policy learning', 'compute rewards from trajectories using the discriminator to score observations and extract policy probabilities', 'get the REINFORCE loss including baseline loss, entropy loss, and discriminator loss from sampled trajectories', 'create a Reinforce agent instance with config, environment factory, and agent factory functions', 'review the Reinforce run method that manages training and evaluation batchers with RMSprop optimizers', 'create a gym environment by calling gym.make with a given environment name string', 'create a vectorized GymEnv wrapping multiple gym environments with TimeLimit and an optional seed', 'create a DIAYNAgent instance from a given model and number of actions', 'run a DIAYN reinforcement learning experiment on CartPole-v0 using the Experiment class and config dict', 'review the Experiment class that extends Reinforce and creates DIAYN action and baseline models']
```

Usage

```
{'create_DIAYNAgent': 'create a DIAYNAgent instance with a DIAYNModel and number of actions for reinforcement learning', 'run_DIAYNAgent_call': 'run one step of the DIAYNAgent to sample actions and compute baselines from observations', 'build_DIAYNActionModel': 'build a DIAYNActionModel neural network that computes softmax action probabilities per policy index', 'build_DIAYNBaselineModel': 'build a DIAYNBaselineModel neural network that computes state value V(s) per policy index', 'update_DIAYNAgent': 'update the DIAYNAgent model weights by loading a PyTorch state dictionary'}
```

## File: facebookresearch_rlstructures/rlalgos/reinforce_diayn/reinforce_diayn.py

Prompts

```
['create a DIAYNAgent instance with a DIAYNModel and number of actions for reinforcement learning', 'run one step of the DIAYNAgent to sample actions and compute baselines from observations', 'build a DIAYNActionModel neural network that computes softmax action probabilities per policy index', 'build a DIAYNBaselineModel neural network that computes state value V(s) per policy index', 'update the DIAYNAgent model weights by loading a PyTorch state dictionary', 'run the Reinforce class training loop with DIAYN discriminator for offline RL policy learning', 'compute rewards from trajectories using the discriminator to score observations and extract policy probabilities', 'get the REINFORCE loss including baseline loss, entropy loss, and discriminator loss from sampled trajectories', 'create a Reinforce agent instance with config, environment factory, and agent factory functions', 'review the Reinforce run method that manages training and evaluation batchers with RMSprop optimizers', 'create a gym environment by calling gym.make with a given environment name string', 'create a vectorized GymEnv wrapping multiple gym environments with TimeLimit and an optional seed', 'create a DIAYNAgent instance from a given model and number of actions', 'run a DIAYN reinforcement learning experiment on CartPole-v0 using the Experiment class and config dict', 'review the Experiment class that extends Reinforce and creates DIAYN action and baseline models']
```

Usage

```
{'run_REINFORCE_DIAYN_training': 'run the Reinforce class training loop with DIAYN discriminator for offline RL policy learning', 'compute_reward_from_trajectories': 'compute rewards from trajectories using the discriminator to score observations and extract policy probabilities', 'get_loss_for_trajectories': 'get the REINFORCE loss including baseline loss, entropy loss, and discriminator loss from sampled trajectories', 'create_REINFORCE_agent': 'create a Reinforce agent instance with config, environment factory, and agent factory functions', 'review_REINFORCE_run_loop': 'review the Reinforce run method that manages training and evaluation batchers with RMSprop optimizers'}
```

## File: facebookresearch_rlstructures/rlalgos/reinforce_diayn/run_diayn.py

Prompts

```
['create a DIAYNAgent instance with a DIAYNModel and number of actions for reinforcement learning', 'run one step of the DIAYNAgent to sample actions and compute baselines from observations', 'build a DIAYNActionModel neural network that computes softmax action probabilities per policy index', 'build a DIAYNBaselineModel neural network that computes state value V(s) per policy index', 'update the DIAYNAgent model weights by loading a PyTorch state dictionary', 'run the Reinforce class training loop with DIAYN discriminator for offline RL policy learning', 'compute rewards from trajectories using the discriminator to score observations and extract policy probabilities', 'get the REINFORCE loss including baseline loss, entropy loss, and discriminator loss from sampled trajectories', 'create a Reinforce agent instance with config, environment factory, and agent factory functions', 'review the Reinforce run method that manages training and evaluation batchers with RMSprop optimizers', 'create a gym environment by calling gym.make with a given environment name string', 'create a vectorized GymEnv wrapping multiple gym environments with TimeLimit and an optional seed', 'create a DIAYNAgent instance from a given model and number of actions', 'run a DIAYN reinforcement learning experiment on CartPole-v0 using the Experiment class and config dict', 'review the Experiment class that extends Reinforce and creates DIAYN action and baseline models']
```

Usage

```
{'create_gym_env': 'create a gym environment by calling gym.make with a given environment name string', 'create_env': 'create a vectorized GymEnv wrapping multiple gym environments with TimeLimit and an optional seed', 'create_agent': 'create a DIAYNAgent instance from a given model and number of actions', 'run_DIAYN_experiment': 'run a DIAYN reinforcement learning experiment on CartPole-v0 using the Experiment class and config dict', 'review_Experiment_class': 'review the Experiment class that extends Reinforce and creates DIAYN action and baseline models'}
```

