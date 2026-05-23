# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_reinforce_with_evaluation_s/agent.py

Prompts

```
['build a ReinforceAgent that samples actions stochastically or deterministically based on agent_info mode', 'create an ActionModel neural network that outputs softmax action probabilities from observation frames', 'create a BaselineModel neural network that computes state value V(s) for a given frame', 'review the Model class that composes an ActionModel and BaselineModel into a single nn.Module', 'test the ReinforceAgent call method to verify action sampling and masked_tensor selection logic', 'run a REINFORCE reinforcement learning experiment on CartPole-v0 with evaluation environments', 'create multiple Gym environments wrapped with TimeLimit and GymEnv for parallel training', 'create a single Gym environment by name using gym.make for the specified environment', 'create a ReinforceAgent instance with a given model and number of actions', 'review the Experiment class that extends Reinforce for REINFORCE training with evaluation', 'run the REINFORCE reinforcement learning algorithm with evaluation batcher and training loop', 'create a Reinforce instance with config, environment factory, and agent factory functions', 'compute REINFORCE loss, baseline loss, and entropy loss from sampled trajectories', 'review the Reinforce run method that manages training and evaluation batchers', 'refactor the cumulated reward reverse computation in get_loss to use vectorized operations']
```

Usage

```
{'build_reinforce_agent': 'build a ReinforceAgent that samples actions stochastically or deterministically based on agent_info mode', 'create_action_model': 'create an ActionModel neural network that outputs softmax action probabilities from observation frames', 'create_baseline_model': 'create a BaselineModel neural network that computes state value V(s) for a given frame', 'review_model_composition': 'review the Model class that composes an ActionModel and BaselineModel into a single nn.Module', 'test_reinforce_agent_call': 'test the ReinforceAgent call method to verify action sampling and masked_tensor selection logic'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_reinforce_with_evaluation_s/main_reinforce.py

Prompts

```
['build a ReinforceAgent that samples actions stochastically or deterministically based on agent_info mode', 'create an ActionModel neural network that outputs softmax action probabilities from observation frames', 'create a BaselineModel neural network that computes state value V(s) for a given frame', 'review the Model class that composes an ActionModel and BaselineModel into a single nn.Module', 'test the ReinforceAgent call method to verify action sampling and masked_tensor selection logic', 'run a REINFORCE reinforcement learning experiment on CartPole-v0 with evaluation environments', 'create multiple Gym environments wrapped with TimeLimit and GymEnv for parallel training', 'create a single Gym environment by name using gym.make for the specified environment', 'create a ReinforceAgent instance with a given model and number of actions', 'review the Experiment class that extends Reinforce for REINFORCE training with evaluation', 'run the REINFORCE reinforcement learning algorithm with evaluation batcher and training loop', 'create a Reinforce instance with config, environment factory, and agent factory functions', 'compute REINFORCE loss, baseline loss, and entropy loss from sampled trajectories', 'review the Reinforce run method that manages training and evaluation batchers', 'refactor the cumulated reward reverse computation in get_loss to use vectorized operations']
```

Usage

```
{'run_REINFORCE_experiment': 'run a REINFORCE reinforcement learning experiment on CartPole-v0 with evaluation environments', 'create_env': 'create multiple Gym environments wrapped with TimeLimit and GymEnv for parallel training', 'create_gym_env': 'create a single Gym environment by name using gym.make for the specified environment', 'create_agent': 'create a ReinforceAgent instance with a given model and number of actions', 'review_Experiment_class': 'review the Experiment class that extends Reinforce for REINFORCE training with evaluation'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_reinforce_with_evaluation_s/reinforce.py

Prompts

```
['build a ReinforceAgent that samples actions stochastically or deterministically based on agent_info mode', 'create an ActionModel neural network that outputs softmax action probabilities from observation frames', 'create a BaselineModel neural network that computes state value V(s) for a given frame', 'review the Model class that composes an ActionModel and BaselineModel into a single nn.Module', 'test the ReinforceAgent call method to verify action sampling and masked_tensor selection logic', 'run a REINFORCE reinforcement learning experiment on CartPole-v0 with evaluation environments', 'create multiple Gym environments wrapped with TimeLimit and GymEnv for parallel training', 'create a single Gym environment by name using gym.make for the specified environment', 'create a ReinforceAgent instance with a given model and number of actions', 'review the Experiment class that extends Reinforce for REINFORCE training with evaluation', 'run the REINFORCE reinforcement learning algorithm with evaluation batcher and training loop', 'create a Reinforce instance with config, environment factory, and agent factory functions', 'compute REINFORCE loss, baseline loss, and entropy loss from sampled trajectories', 'review the Reinforce run method that manages training and evaluation batchers', 'refactor the cumulated reward reverse computation in get_loss to use vectorized operations']
```

Usage

```
{'run_REINFORCE_training': 'run the REINFORCE reinforcement learning algorithm with evaluation batcher and training loop', 'create_Reinforce_instance': 'create a Reinforce instance with config, environment factory, and agent factory functions', 'compute_loss_from_trajectories': 'compute REINFORCE loss, baseline loss, and entropy loss from sampled trajectories', 'review_Reinforce_run_method': 'review the Reinforce run method that manages training and evaluation batchers', 'refactor_cumulated_reward_calculation': 'refactor the cumulated reward reverse computation in get_loss to use vectorized operations'}
```

