# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/rlmeta/agents/ppo/ppo_agent.py

Prompts

```
['create a PPOAgent with a model, optimizer, replay buffer, and hyperparameters for PPO training', 'train the PPOAgent for a specified number of steps using replay buffer samples and gradient updates', 'evaluate the PPOAgent over a set number of episodes and return aggregated stats', 'compute generalized advantage estimation and returns from value and reward sequences with optional rescaling', 'compute the clipped PPO policy loss and probability ratio from log probabilities and advantages', 'implement a subclass of PPOModel that defines forward and act methods for a custom policy', 'implement the forward method of PPOModel to return log probabilities and state values from observations', 'implement the act method of PPOModel to select actions and return action, log probability, and value', 'review the PPOModel abstract class and its forward and act method signatures', 'refactor a PPOModel subclass to handle additional keyword arguments in forward and act methods', 'build a PPO with RND agent using a model, optimizer, and hyperparameters for intrinsic reward coefficients', 'create an action from a timestep observation using the PPORNDAgent act method with external and intrinsic values', 'test the PPORNDAgent observe method to record actions, rewards, and value estimates into the trajectory buffer', 'review the PPORNDAgent train step that computes policy loss, value loss, entropy, and RND loss for gradient updates', 'summarize the PPORNDAgent intrinsic reward computation that batches next observations and calls the model intrinsic reward function', 'implement a subclass of PPORNDModel that overrides forward, act, intrinsic_reward, and rnd_loss methods', 'override the forward method to compute log probabilities and extrinsic/intrinsic values from observations', 'override the act method to select actions using greedy or sampled policy and return action with values', 'override the intrinsic_reward method to compute RND-based intrinsic rewards from observations', 'override the rnd_loss method to compute the Random Network Distillation loss from observations']
```

Usage

```
{'create_ppo_agent': 'create a PPOAgent with a model, optimizer, replay buffer, and hyperparameters for PPO training', 'train_ppo_agent': 'train the PPOAgent for a specified number of steps using replay buffer samples and gradient updates', 'eval_ppo_agent': 'evaluate the PPOAgent over a set number of episodes and return aggregated stats', 'compute_gae_and_return': 'compute generalized advantage estimation and returns from value and reward sequences with optional rescaling', 'compute_policy_loss': 'compute the clipped PPO policy loss and probability ratio from log probabilities and advantages'}
```

## File: facebookresearch_rlmeta/rlmeta/agents/ppo/ppo_model.py

Prompts

```
['create a PPOAgent with a model, optimizer, replay buffer, and hyperparameters for PPO training', 'train the PPOAgent for a specified number of steps using replay buffer samples and gradient updates', 'evaluate the PPOAgent over a set number of episodes and return aggregated stats', 'compute generalized advantage estimation and returns from value and reward sequences with optional rescaling', 'compute the clipped PPO policy loss and probability ratio from log probabilities and advantages', 'implement a subclass of PPOModel that defines forward and act methods for a custom policy', 'implement the forward method of PPOModel to return log probabilities and state values from observations', 'implement the act method of PPOModel to select actions and return action, log probability, and value', 'review the PPOModel abstract class and its forward and act method signatures', 'refactor a PPOModel subclass to handle additional keyword arguments in forward and act methods', 'build a PPO with RND agent using a model, optimizer, and hyperparameters for intrinsic reward coefficients', 'create an action from a timestep observation using the PPORNDAgent act method with external and intrinsic values', 'test the PPORNDAgent observe method to record actions, rewards, and value estimates into the trajectory buffer', 'review the PPORNDAgent train step that computes policy loss, value loss, entropy, and RND loss for gradient updates', 'summarize the PPORNDAgent intrinsic reward computation that batches next observations and calls the model intrinsic reward function', 'implement a subclass of PPORNDModel that overrides forward, act, intrinsic_reward, and rnd_loss methods', 'override the forward method to compute log probabilities and extrinsic/intrinsic values from observations', 'override the act method to select actions using greedy or sampled policy and return action with values', 'override the intrinsic_reward method to compute RND-based intrinsic rewards from observations', 'override the rnd_loss method to compute the Random Network Distillation loss from observations']
```

Usage

```
{'implement_PPOModel_subclass': 'implement a subclass of PPOModel that defines forward and act methods for a custom policy', 'implement_PPOModel_forward': 'implement the forward method of PPOModel to return log probabilities and state values from observations', 'implement_PPOModel_act': 'implement the act method of PPOModel to select actions and return action, log probability, and value', 'review_PPOModel_abstract_methods': 'review the PPOModel abstract class and its forward and act method signatures', 'refactor_PPOModel_subclass': 'refactor a PPOModel subclass to handle additional keyword arguments in forward and act methods'}
```

## File: facebookresearch_rlmeta/rlmeta/agents/ppo/ppo_rnd_agent.py

Prompts

```
['create a PPOAgent with a model, optimizer, replay buffer, and hyperparameters for PPO training', 'train the PPOAgent for a specified number of steps using replay buffer samples and gradient updates', 'evaluate the PPOAgent over a set number of episodes and return aggregated stats', 'compute generalized advantage estimation and returns from value and reward sequences with optional rescaling', 'compute the clipped PPO policy loss and probability ratio from log probabilities and advantages', 'implement a subclass of PPOModel that defines forward and act methods for a custom policy', 'implement the forward method of PPOModel to return log probabilities and state values from observations', 'implement the act method of PPOModel to select actions and return action, log probability, and value', 'review the PPOModel abstract class and its forward and act method signatures', 'refactor a PPOModel subclass to handle additional keyword arguments in forward and act methods', 'build a PPO with RND agent using a model, optimizer, and hyperparameters for intrinsic reward coefficients', 'create an action from a timestep observation using the PPORNDAgent act method with external and intrinsic values', 'test the PPORNDAgent observe method to record actions, rewards, and value estimates into the trajectory buffer', 'review the PPORNDAgent train step that computes policy loss, value loss, entropy, and RND loss for gradient updates', 'summarize the PPORNDAgent intrinsic reward computation that batches next observations and calls the model intrinsic reward function', 'implement a subclass of PPORNDModel that overrides forward, act, intrinsic_reward, and rnd_loss methods', 'override the forward method to compute log probabilities and extrinsic/intrinsic values from observations', 'override the act method to select actions using greedy or sampled policy and return action with values', 'override the intrinsic_reward method to compute RND-based intrinsic rewards from observations', 'override the rnd_loss method to compute the Random Network Distillation loss from observations']
```

Usage

```
{'build_PPORNDAgent': 'build a PPO with RND agent using a model, optimizer, and hyperparameters for intrinsic reward coefficients', 'create_act_method': 'create an action from a timestep observation using the PPORNDAgent act method with external and intrinsic values', 'test_observe_method': 'test the PPORNDAgent observe method to record actions, rewards, and value estimates into the trajectory buffer', 'review_train_step': 'review the PPORNDAgent train step that computes policy loss, value loss, entropy, and RND loss for gradient updates', 'summarize_compute_intrinsic_reward': 'summarize the PPORNDAgent intrinsic reward computation that batches next observations and calls the model intrinsic reward function'}
```

## File: facebookresearch_rlmeta/rlmeta/agents/ppo/ppo_rnd_model.py

Prompts

```
['create a PPOAgent with a model, optimizer, replay buffer, and hyperparameters for PPO training', 'train the PPOAgent for a specified number of steps using replay buffer samples and gradient updates', 'evaluate the PPOAgent over a set number of episodes and return aggregated stats', 'compute generalized advantage estimation and returns from value and reward sequences with optional rescaling', 'compute the clipped PPO policy loss and probability ratio from log probabilities and advantages', 'implement a subclass of PPOModel that defines forward and act methods for a custom policy', 'implement the forward method of PPOModel to return log probabilities and state values from observations', 'implement the act method of PPOModel to select actions and return action, log probability, and value', 'review the PPOModel abstract class and its forward and act method signatures', 'refactor a PPOModel subclass to handle additional keyword arguments in forward and act methods', 'build a PPO with RND agent using a model, optimizer, and hyperparameters for intrinsic reward coefficients', 'create an action from a timestep observation using the PPORNDAgent act method with external and intrinsic values', 'test the PPORNDAgent observe method to record actions, rewards, and value estimates into the trajectory buffer', 'review the PPORNDAgent train step that computes policy loss, value loss, entropy, and RND loss for gradient updates', 'summarize the PPORNDAgent intrinsic reward computation that batches next observations and calls the model intrinsic reward function', 'implement a subclass of PPORNDModel that overrides forward, act, intrinsic_reward, and rnd_loss methods', 'override the forward method to compute log probabilities and extrinsic/intrinsic values from observations', 'override the act method to select actions using greedy or sampled policy and return action with values', 'override the intrinsic_reward method to compute RND-based intrinsic rewards from observations', 'override the rnd_loss method to compute the Random Network Distillation loss from observations']
```

Usage

```
{'implement_PPORNDModel_subclass': 'implement a subclass of PPORNDModel that overrides forward, act, intrinsic_reward, and rnd_loss methods', 'override_forward_method': 'override the forward method to compute log probabilities and extrinsic/intrinsic values from observations', 'override_act_method': 'override the act method to select actions using greedy or sampled policy and return action with values', 'override_intrinsic_reward_method': 'override the intrinsic_reward method to compute RND-based intrinsic rewards from observations', 'override_rnd_loss_method': 'override the rnd_loss method to compute the Random Network Distillation loss from observations'}
```

