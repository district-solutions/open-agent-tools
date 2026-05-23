# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_from_reinforce_to_a2c_s/a2c.py

Prompts

```
['create an A2C instance with config, create_env, and create_agent functions for reinforcement learning', 'run the A2C training loop with evaluation and logging until the time limit is reached', 'compute the critic loss, A2C loss, and entropy loss from trajectories using get_loss method', 'setup an S_EpisodeBatcher for evaluating agent performance in deterministic mode during training', 'setup an S_Batcher for sampling trajectory pieces across multiple threads and environments', 'build a ReinforceAgent that samples actions stochastically or deterministically from an action probability distribution', 'create an ActionModel neural network that maps observations to softmax action probabilities', 'create a CriticModel neural network that computes state value V(s) from observations', 'review the ReinforceAgent call_replay method that computes critic values and action probabilities from trajectories', 'build a Model container that wraps an ActionModel and CriticModel as nn.Module submodules', 'run an A2C reinforcement learning experiment on CartPole-v0 with configurable hyperparameters', 'create a single Gym environment by name using gym.make for use in multiprocessing', 'create multiple Gym environments wrapped with TimeLimit and return a GymEnv for parallel training', 'create a ReinforceAgent instance with a given model and number of actions', 'review the Experiment class that extends A2C and initializes with config, create_env, and create_agent']
```

Usage

```
{'create_A2C_instance': 'create an A2C instance with config, create_env, and create_agent functions for reinforcement learning', 'run_A2C_training': 'run the A2C training loop with evaluation and logging until the time limit is reached', 'compute_A2C_loss': 'compute the critic loss, A2C loss, and entropy loss from trajectories using get_loss method', 'setup_evaluation_batcher': 'setup an S_EpisodeBatcher for evaluating agent performance in deterministic mode during training', 'setup_training_batcher': 'setup an S_Batcher for sampling trajectory pieces across multiple threads and environments'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_from_reinforce_to_a2c_s/agent.py

Prompts

```
['create an A2C instance with config, create_env, and create_agent functions for reinforcement learning', 'run the A2C training loop with evaluation and logging until the time limit is reached', 'compute the critic loss, A2C loss, and entropy loss from trajectories using get_loss method', 'setup an S_EpisodeBatcher for evaluating agent performance in deterministic mode during training', 'setup an S_Batcher for sampling trajectory pieces across multiple threads and environments', 'build a ReinforceAgent that samples actions stochastically or deterministically from an action probability distribution', 'create an ActionModel neural network that maps observations to softmax action probabilities', 'create a CriticModel neural network that computes state value V(s) from observations', 'review the ReinforceAgent call_replay method that computes critic values and action probabilities from trajectories', 'build a Model container that wraps an ActionModel and CriticModel as nn.Module submodules', 'run an A2C reinforcement learning experiment on CartPole-v0 with configurable hyperparameters', 'create a single Gym environment by name using gym.make for use in multiprocessing', 'create multiple Gym environments wrapped with TimeLimit and return a GymEnv for parallel training', 'create a ReinforceAgent instance with a given model and number of actions', 'review the Experiment class that extends A2C and initializes with config, create_env, and create_agent']
```

Usage

```
{'build_reinforce_agent': 'build a ReinforceAgent that samples actions stochastically or deterministically from an action probability distribution', 'create_action_model': 'create an ActionModel neural network that maps observations to softmax action probabilities', 'create_critic_model': 'create a CriticModel neural network that computes state value V(s) from observations', 'review_reinforce_agent_call_replay': 'review the ReinforceAgent call_replay method that computes critic values and action probabilities from trajectories', 'build_model_container': 'build a Model container that wraps an ActionModel and CriticModel as nn.Module submodules'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_from_reinforce_to_a2c_s/main_a2c.py

Prompts

```
['create an A2C instance with config, create_env, and create_agent functions for reinforcement learning', 'run the A2C training loop with evaluation and logging until the time limit is reached', 'compute the critic loss, A2C loss, and entropy loss from trajectories using get_loss method', 'setup an S_EpisodeBatcher for evaluating agent performance in deterministic mode during training', 'setup an S_Batcher for sampling trajectory pieces across multiple threads and environments', 'build a ReinforceAgent that samples actions stochastically or deterministically from an action probability distribution', 'create an ActionModel neural network that maps observations to softmax action probabilities', 'create a CriticModel neural network that computes state value V(s) from observations', 'review the ReinforceAgent call_replay method that computes critic values and action probabilities from trajectories', 'build a Model container that wraps an ActionModel and CriticModel as nn.Module submodules', 'run an A2C reinforcement learning experiment on CartPole-v0 with configurable hyperparameters', 'create a single Gym environment by name using gym.make for use in multiprocessing', 'create multiple Gym environments wrapped with TimeLimit and return a GymEnv for parallel training', 'create a ReinforceAgent instance with a given model and number of actions', 'review the Experiment class that extends A2C and initializes with config, create_env, and create_agent']
```

Usage

```
{'run_a2c_experiment': 'run an A2C reinforcement learning experiment on CartPole-v0 with configurable hyperparameters', 'create_gym_env': 'create a single Gym environment by name using gym.make for use in multiprocessing', 'create_env': 'create multiple Gym environments wrapped with TimeLimit and return a GymEnv for parallel training', 'create_agent': 'create a ReinforceAgent instance with a given model and number of actions', 'review_Experiment_class': 'review the Experiment class that extends A2C and initializes with config, create_env, and create_agent'}
```

