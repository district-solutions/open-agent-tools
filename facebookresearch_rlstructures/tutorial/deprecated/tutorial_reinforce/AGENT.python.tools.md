# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_reinforce/agent.py

Prompts

```
['create a ReinforceAgent instance with a model and number of actions for REINFORCE policy', 'call the ReinforceAgent to execute one step and sample an action from observation', 'update the ReinforceAgent model weights by loading a new state dict', 'build an AgentModel neural network that outputs action probabilities from observation frames', 'build a BaselineModel neural network that computes state value V(s) for critic', 'create a gym environment by calling gym.make with the specified environment name', 'create multiple gym environments wrapped with TimeLimit and return a GymEnv instance', 'create a ReinforceAgent with the provided model and number of actions', 'run a REINFORCE reinforcement learning experiment with CartPole-v0 using multiprocessing', 'review the Experiment class that extends Reinforce for reinforcement learning training', 'run the Reinforce class to train an RL agent using policy gradient with baseline and entropy regularization', 'create a Reinforce instance with config, create_env, and create_agent callbacks for environment and agent setup', 'compute the REINFORCE loss including baseline loss, reinforce loss, and entropy loss from sampled trajectories', 'review the Reinforce run method training loop that samples trajectories, computes loss, and updates model weights', 'refactor the get_loss method to vectorize the cumulative discounted reward computation instead of using a for loop']
```

Usage

```
{'create_ReinforceAgent': 'create a ReinforceAgent instance with a model and number of actions for REINFORCE policy', 'call_ReinforceAgent': 'call the ReinforceAgent to execute one step and sample an action from observation', 'update_ReinforceAgent': 'update the ReinforceAgent model weights by loading a new state dict', 'build_AgentModel': 'build an AgentModel neural network that outputs action probabilities from observation frames', 'build_BaselineModel': 'build a BaselineModel neural network that computes state value V(s) for critic'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_reinforce/main_reinforce.py

Prompts

```
['create a ReinforceAgent instance with a model and number of actions for REINFORCE policy', 'call the ReinforceAgent to execute one step and sample an action from observation', 'update the ReinforceAgent model weights by loading a new state dict', 'build an AgentModel neural network that outputs action probabilities from observation frames', 'build a BaselineModel neural network that computes state value V(s) for critic', 'create a gym environment by calling gym.make with the specified environment name', 'create multiple gym environments wrapped with TimeLimit and return a GymEnv instance', 'create a ReinforceAgent with the provided model and number of actions', 'run a REINFORCE reinforcement learning experiment with CartPole-v0 using multiprocessing', 'review the Experiment class that extends Reinforce for reinforcement learning training', 'run the Reinforce class to train an RL agent using policy gradient with baseline and entropy regularization', 'create a Reinforce instance with config, create_env, and create_agent callbacks for environment and agent setup', 'compute the REINFORCE loss including baseline loss, reinforce loss, and entropy loss from sampled trajectories', 'review the Reinforce run method training loop that samples trajectories, computes loss, and updates model weights', 'refactor the get_loss method to vectorize the cumulative discounted reward computation instead of using a for loop']
```

Usage

```
{'create_gym_env': 'create a gym environment by calling gym.make with the specified environment name', 'create_env': 'create multiple gym environments wrapped with TimeLimit and return a GymEnv instance', 'create_agent': 'create a ReinforceAgent with the provided model and number of actions', 'run_Experiment': 'run a REINFORCE reinforcement learning experiment with CartPole-v0 using multiprocessing', 'review_Experiment_class': 'review the Experiment class that extends Reinforce for reinforcement learning training'}
```

## File: facebookresearch_rlstructures/tutorial/deprecated/tutorial_reinforce/reinforce.py

Prompts

```
['create a ReinforceAgent instance with a model and number of actions for REINFORCE policy', 'call the ReinforceAgent to execute one step and sample an action from observation', 'update the ReinforceAgent model weights by loading a new state dict', 'build an AgentModel neural network that outputs action probabilities from observation frames', 'build a BaselineModel neural network that computes state value V(s) for critic', 'create a gym environment by calling gym.make with the specified environment name', 'create multiple gym environments wrapped with TimeLimit and return a GymEnv instance', 'create a ReinforceAgent with the provided model and number of actions', 'run a REINFORCE reinforcement learning experiment with CartPole-v0 using multiprocessing', 'review the Experiment class that extends Reinforce for reinforcement learning training', 'run the Reinforce class to train an RL agent using policy gradient with baseline and entropy regularization', 'create a Reinforce instance with config, create_env, and create_agent callbacks for environment and agent setup', 'compute the REINFORCE loss including baseline loss, reinforce loss, and entropy loss from sampled trajectories', 'review the Reinforce run method training loop that samples trajectories, computes loss, and updates model weights', 'refactor the get_loss method to vectorize the cumulative discounted reward computation instead of using a for loop']
```

Usage

```
{'run_REINFORCE_training': 'run the Reinforce class to train an RL agent using policy gradient with baseline and entropy regularization', 'create_REINFORCE_instance': 'create a Reinforce instance with config, create_env, and create_agent callbacks for environment and agent setup', 'compute_get_loss': 'compute the REINFORCE loss including baseline loss, reinforce loss, and entropy loss from sampled trajectories', 'review_REINFORCE_run_loop': 'review the Reinforce run method training loop that samples trajectories, computes loss, and updates model weights', 'refactor_get_loss_cumulative_reward': 'refactor the get_loss method to vectorize the cumulative discounted reward computation instead of using a for loop'}
```

