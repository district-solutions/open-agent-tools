# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/agents/ppo/algorithm.py

Prompts

```
['build a PPOAlgorithm instance with a batch environment, training step, and config object', 'create a begin_episode call to reset recurrent states and stored episode buffers for agent indices', 'run perform to compute a batch of actions from observations using the current policy network', 'test the experience method to process transition tuples and update streaming statistics during training', 'review the policy_loss method to understand the PPO surrogate loss, KL penalty, and KL cutoff components', 'build a python module to create an EpisodeMemory with template tensors, capacity, max_length, and scope for PPO agent training', 'create a function that appends a batch of transition tuples to specific episode rows in the EpisodeMemory', 'test the EpisodeMemory replace method to swap full episodes with new transition data and sequence lengths', 'review the EpisodeMemory data method to retrieve a batch of episodes and their sequence lengths from memory buffers', 'summarize the EpisodeMemory clear method that resets episode lengths to zero for specified rows in the memory', 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance estimates', 'normalize a batch or single tensor using current streaming mean and variance estimates', 'update the streaming mean and variance estimates with new batch or single value tensors', 'reset all streaming mean and variance estimates back to their initial zero state', 'generate a merged summary tensor showing the current streaming mean and standard deviation estimates', 'compute discounted Monte-Carlo returns from reward tensors, episode lengths, and a discount factor', 'compute generalized advantage estimation from reward, value, length, and discount tensors', 'compute TD-lambda returns from reward, value, length, discount, and lambda tensors', 'compute the empirical KL divergence between two diagonal covariance normal distributions', 'list all GPU device names detected by TensorFlow on the local machine']
```

Usage

```
{'build_PPOAlgorithm': 'build a PPOAlgorithm instance with a batch environment, training step, and config object', 'create_begin_episode': 'create a begin_episode call to reset recurrent states and stored episode buffers for agent indices', 'run_perform': 'run perform to compute a batch of actions from observations using the current policy network', 'test_experience': 'test the experience method to process transition tuples and update streaming statistics during training', 'review_policy_loss': 'review the policy_loss method to understand the PPO surrogate loss, KL penalty, and KL cutoff components'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/agents/ppo/memory.py

Prompts

```
['build a PPOAlgorithm instance with a batch environment, training step, and config object', 'create a begin_episode call to reset recurrent states and stored episode buffers for agent indices', 'run perform to compute a batch of actions from observations using the current policy network', 'test the experience method to process transition tuples and update streaming statistics during training', 'review the policy_loss method to understand the PPO surrogate loss, KL penalty, and KL cutoff components', 'build a python module to create an EpisodeMemory with template tensors, capacity, max_length, and scope for PPO agent training', 'create a function that appends a batch of transition tuples to specific episode rows in the EpisodeMemory', 'test the EpisodeMemory replace method to swap full episodes with new transition data and sequence lengths', 'review the EpisodeMemory data method to retrieve a batch of episodes and their sequence lengths from memory buffers', 'summarize the EpisodeMemory clear method that resets episode lengths to zero for specified rows in the memory', 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance estimates', 'normalize a batch or single tensor using current streaming mean and variance estimates', 'update the streaming mean and variance estimates with new batch or single value tensors', 'reset all streaming mean and variance estimates back to their initial zero state', 'generate a merged summary tensor showing the current streaming mean and standard deviation estimates', 'compute discounted Monte-Carlo returns from reward tensors, episode lengths, and a discount factor', 'compute generalized advantage estimation from reward, value, length, and discount tensors', 'compute TD-lambda returns from reward, value, length, discount, and lambda tensors', 'compute the empirical KL divergence between two diagonal covariance normal distributions', 'list all GPU device names detected by TensorFlow on the local machine']
```

Usage

```
{'build_EpisodeMemory': 'build a python module to create an EpisodeMemory with template tensors, capacity, max_length, and scope for PPO agent training', 'create_EpisodeMemory_append': 'create a function that appends a batch of transition tuples to specific episode rows in the EpisodeMemory', 'test_EpisodeMemory_replace': 'test the EpisodeMemory replace method to swap full episodes with new transition data and sequence lengths', 'review_EpisodeMemory_data': 'review the EpisodeMemory data method to retrieve a batch of episodes and their sequence lengths from memory buffers', 'summarize_EpisodeMemory_clear': 'summarize the EpisodeMemory clear method that resets episode lengths to zero for specified rows in the memory'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/agents/ppo/normalize.py

Prompts

```
['build a PPOAlgorithm instance with a batch environment, training step, and config object', 'create a begin_episode call to reset recurrent states and stored episode buffers for agent indices', 'run perform to compute a batch of actions from observations using the current policy network', 'test the experience method to process transition tuples and update streaming statistics during training', 'review the policy_loss method to understand the PPO surrogate loss, KL penalty, and KL cutoff components', 'build a python module to create an EpisodeMemory with template tensors, capacity, max_length, and scope for PPO agent training', 'create a function that appends a batch of transition tuples to specific episode rows in the EpisodeMemory', 'test the EpisodeMemory replace method to swap full episodes with new transition data and sequence lengths', 'review the EpisodeMemory data method to retrieve a batch of episodes and their sequence lengths from memory buffers', 'summarize the EpisodeMemory clear method that resets episode lengths to zero for specified rows in the memory', 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance estimates', 'normalize a batch or single tensor using current streaming mean and variance estimates', 'update the streaming mean and variance estimates with new batch or single value tensors', 'reset all streaming mean and variance estimates back to their initial zero state', 'generate a merged summary tensor showing the current streaming mean and standard deviation estimates', 'compute discounted Monte-Carlo returns from reward tensors, episode lengths, and a discount factor', 'compute generalized advantage estimation from reward, value, length, and discount tensors', 'compute TD-lambda returns from reward, value, length, discount, and lambda tensors', 'compute the empirical KL divergence between two diagonal covariance normal distributions', 'list all GPU device names detected by TensorFlow on the local machine']
```

Usage

```
{'create_StreamingNormalize': 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance estimates', 'transform_normalize_tensor': 'normalize a batch or single tensor using current streaming mean and variance estimates', 'update_streaming_estimates': 'update the streaming mean and variance estimates with new batch or single value tensors', 'reset_normalization_state': 'reset all streaming mean and variance estimates back to their initial zero state', 'summary_mean_stddev': 'generate a merged summary tensor showing the current streaming mean and standard deviation estimates'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/agents/ppo/utility.py

Prompts

```
['build a PPOAlgorithm instance with a batch environment, training step, and config object', 'create a begin_episode call to reset recurrent states and stored episode buffers for agent indices', 'run perform to compute a batch of actions from observations using the current policy network', 'test the experience method to process transition tuples and update streaming statistics during training', 'review the policy_loss method to understand the PPO surrogate loss, KL penalty, and KL cutoff components', 'build a python module to create an EpisodeMemory with template tensors, capacity, max_length, and scope for PPO agent training', 'create a function that appends a batch of transition tuples to specific episode rows in the EpisodeMemory', 'test the EpisodeMemory replace method to swap full episodes with new transition data and sequence lengths', 'review the EpisodeMemory data method to retrieve a batch of episodes and their sequence lengths from memory buffers', 'summarize the EpisodeMemory clear method that resets episode lengths to zero for specified rows in the memory', 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance estimates', 'normalize a batch or single tensor using current streaming mean and variance estimates', 'update the streaming mean and variance estimates with new batch or single value tensors', 'reset all streaming mean and variance estimates back to their initial zero state', 'generate a merged summary tensor showing the current streaming mean and standard deviation estimates', 'compute discounted Monte-Carlo returns from reward tensors, episode lengths, and a discount factor', 'compute generalized advantage estimation from reward, value, length, and discount tensors', 'compute TD-lambda returns from reward, value, length, discount, and lambda tensors', 'compute the empirical KL divergence between two diagonal covariance normal distributions', 'list all GPU device names detected by TensorFlow on the local machine']
```

Usage

```
{'compute_discounted_return': 'compute discounted Monte-Carlo returns from reward tensors, episode lengths, and a discount factor', 'compute_lambda_advantage': 'compute generalized advantage estimation from reward, value, length, and discount tensors', 'compute_lambda_return': 'compute TD-lambda returns from reward, value, length, discount, and lambda tensors', 'compute_diag_normal_kl': 'compute the empirical KL divergence between two diagonal covariance normal distributions', 'list_available_gpus': 'list all GPU device names detected by TensorFlow on the local machine'}
```

