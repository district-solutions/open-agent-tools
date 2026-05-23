# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/reinforce/agent.py

Prompts

```
['build a ReinforceAgent with a Model to execute one step of REINFORCE policy using action probabilities and baseline', 'create an ActionModel that computes softmax action probabilities from observation frames using a two-layer neural network', 'create a BaselineModel that computes state value V(s) from observation frames using a two-layer neural network', 'run one step of the ReinforceAgent by calling it with state, observation, and agent_info to get actions', 'update the ReinforceAgent model weights by loading a PyTorch state dict via the update method', 'run the Reinforce class training loop with config, environment, and agent creation functions', 'compute baseline, reinforce, and entropy losses from sampled trajectories using get_loss method', 'create an RL_Batcher for training or evaluation with environment and agent arguments', 'review the Reinforce class initialization and training loop configuration and hyperparameters', 'summarize the get_loss method that computes discounted cumulative rewards and policy gradient losses', 'run a REINFORCE reinforcement learning experiment on CartPole-v0 with configurable hyperparameters and evaluation', 'create a vectorized GymEnv from multiple gym environments with TimeLimit wrappers and a seed', 'create a single gym environment by name using gym.make for use in multiprocessing', 'create a ReinforceAgent instance with a given model and number of actions', 'review the Experiment class that extends Reinforce and creates ActionModel and BaselineModel']
```

Usage

```
{'build_reinforce_agent': 'build a ReinforceAgent with a Model to execute one step of REINFORCE policy using action probabilities and baseline', 'create_action_model': 'create an ActionModel that computes softmax action probabilities from observation frames using a two-layer neural network', 'create_baseline_model': 'create a BaselineModel that computes state value V(s) from observation frames using a two-layer neural network', 'run_reinforce_step': 'run one step of the ReinforceAgent by calling it with state, observation, and agent_info to get actions', 'update_agent_weights': 'update the ReinforceAgent model weights by loading a PyTorch state dict via the update method'}
```

## File: facebookresearch_rlstructures/rlalgos/reinforce/reinforce.py

Prompts

```
['build a ReinforceAgent with a Model to execute one step of REINFORCE policy using action probabilities and baseline', 'create an ActionModel that computes softmax action probabilities from observation frames using a two-layer neural network', 'create a BaselineModel that computes state value V(s) from observation frames using a two-layer neural network', 'run one step of the ReinforceAgent by calling it with state, observation, and agent_info to get actions', 'update the ReinforceAgent model weights by loading a PyTorch state dict via the update method', 'run the Reinforce class training loop with config, environment, and agent creation functions', 'compute baseline, reinforce, and entropy losses from sampled trajectories using get_loss method', 'create an RL_Batcher for training or evaluation with environment and agent arguments', 'review the Reinforce class initialization and training loop configuration and hyperparameters', 'summarize the get_loss method that computes discounted cumulative rewards and policy gradient losses', 'run a REINFORCE reinforcement learning experiment on CartPole-v0 with configurable hyperparameters and evaluation', 'create a vectorized GymEnv from multiple gym environments with TimeLimit wrappers and a seed', 'create a single gym environment by name using gym.make for use in multiprocessing', 'create a ReinforceAgent instance with a given model and number of actions', 'review the Experiment class that extends Reinforce and creates ActionModel and BaselineModel']
```

Usage

```
{'run_reinforce_training': 'run the Reinforce class training loop with config, environment, and agent creation functions', 'compute_reinforce_loss': 'compute baseline, reinforce, and entropy losses from sampled trajectories using get_loss method', 'create_rl_batcher': 'create an RL_Batcher for training or evaluation with environment and agent arguments', 'review_reinforce_class': 'review the Reinforce class initialization and training loop configuration and hyperparameters', 'summarize_get_loss': 'summarize the get_loss method that computes discounted cumulative rewards and policy gradient losses'}
```

## File: facebookresearch_rlstructures/rlalgos/reinforce/run_reinforce.py

Prompts

```
['build a ReinforceAgent with a Model to execute one step of REINFORCE policy using action probabilities and baseline', 'create an ActionModel that computes softmax action probabilities from observation frames using a two-layer neural network', 'create a BaselineModel that computes state value V(s) from observation frames using a two-layer neural network', 'run one step of the ReinforceAgent by calling it with state, observation, and agent_info to get actions', 'update the ReinforceAgent model weights by loading a PyTorch state dict via the update method', 'run the Reinforce class training loop with config, environment, and agent creation functions', 'compute baseline, reinforce, and entropy losses from sampled trajectories using get_loss method', 'create an RL_Batcher for training or evaluation with environment and agent arguments', 'review the Reinforce class initialization and training loop configuration and hyperparameters', 'summarize the get_loss method that computes discounted cumulative rewards and policy gradient losses', 'run a REINFORCE reinforcement learning experiment on CartPole-v0 with configurable hyperparameters and evaluation', 'create a vectorized GymEnv from multiple gym environments with TimeLimit wrappers and a seed', 'create a single gym environment by name using gym.make for use in multiprocessing', 'create a ReinforceAgent instance with a given model and number of actions', 'review the Experiment class that extends Reinforce and creates ActionModel and BaselineModel']
```

Usage

```
{'run_REINFORCE_experiment': 'run a REINFORCE reinforcement learning experiment on CartPole-v0 with configurable hyperparameters and evaluation', 'create_env_vecenv': 'create a vectorized GymEnv from multiple gym environments with TimeLimit wrappers and a seed', 'create_gym_env': 'create a single gym environment by name using gym.make for use in multiprocessing', 'create_agent_reinforce': 'create a ReinforceAgent instance with a given model and number of actions', 'review_Experiment_class': 'review the Experiment class that extends Reinforce and creates ActionModel and BaselineModel'}
```

