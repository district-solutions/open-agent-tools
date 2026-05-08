# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/agents/ppo/algorithm.py

Prompts

```
['create a PPOAlgorithm instance with a batch environment, training step, and config object', 'perform action selection by calling PPOAlgorithm.perform with a batch of observation tensors', 'begin a new episode by calling PPOAlgorithm.begin_episode with agent index tensors', 'end an episode by calling PPOAlgorithm.end_episode to store episodes and trigger training updates', 'review the PPOAlgorithm training loop including policy update, value update, and KL penalty adjustment', 'create an EpisodeMemory instance with a tensor template, capacity, max_length, and variable scope', 'append a batch of transition tuples to specific rows in the EpisodeMemory', 'replace full episodes in the EpisodeMemory with new transition data and sequence lengths', 'retrieve a batch of episodes and their sequence lengths from the EpisodeMemory', 'reset episodes in the EpisodeMemory by setting their lengths to zero', 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance', 'transform a batch or single tensor using StreamingNormalize to normalize values by mean and stddev', 'update the StreamingNormalize mean and variance estimates with new batch or single value tensors', 'reset the StreamingNormalize mean and variance estimates back to their initial zero state', 'summarize the StreamingNormalize current mean and standard deviation estimates as a merged summary tensor', 'create TensorFlow variables from a nested tuple of tensors for PPO algorithm state tracking', 'reset all variables in a nested tuple to zeros with optional index-based partial reset', 'assign tensors to a matching nested tuple of variables in a single grouped operation', 'compute Generalized Advantage Estimation from reward, value, length, and discount tensors for PPO training', 'list all GPU device names detected by TensorFlow for multi-GPU PPO training configuration']
```

Usage

```
{'create_PPOAlgorithm': 'create a PPOAlgorithm instance with a batch environment, training step, and config object', 'perform_PPOAlgorithm_actions': 'perform action selection by calling PPOAlgorithm.perform with a batch of observation tensors', 'begin_episode_PPOAlgorithm': 'begin a new episode by calling PPOAlgorithm.begin_episode with agent index tensors', 'end_episode_PPOAlgorithm': 'end an episode by calling PPOAlgorithm.end_episode to store episodes and trigger training updates', 'review_PPOAlgorithm_training': 'review the PPOAlgorithm training loop including policy update, value update, and KL penalty adjustment'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/agents/ppo/memory.py

Prompts

```
['create a PPOAlgorithm instance with a batch environment, training step, and config object', 'perform action selection by calling PPOAlgorithm.perform with a batch of observation tensors', 'begin a new episode by calling PPOAlgorithm.begin_episode with agent index tensors', 'end an episode by calling PPOAlgorithm.end_episode to store episodes and trigger training updates', 'review the PPOAlgorithm training loop including policy update, value update, and KL penalty adjustment', 'create an EpisodeMemory instance with a tensor template, capacity, max_length, and variable scope', 'append a batch of transition tuples to specific rows in the EpisodeMemory', 'replace full episodes in the EpisodeMemory with new transition data and sequence lengths', 'retrieve a batch of episodes and their sequence lengths from the EpisodeMemory', 'reset episodes in the EpisodeMemory by setting their lengths to zero', 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance', 'transform a batch or single tensor using StreamingNormalize to normalize values by mean and stddev', 'update the StreamingNormalize mean and variance estimates with new batch or single value tensors', 'reset the StreamingNormalize mean and variance estimates back to their initial zero state', 'summarize the StreamingNormalize current mean and standard deviation estimates as a merged summary tensor', 'create TensorFlow variables from a nested tuple of tensors for PPO algorithm state tracking', 'reset all variables in a nested tuple to zeros with optional index-based partial reset', 'assign tensors to a matching nested tuple of variables in a single grouped operation', 'compute Generalized Advantage Estimation from reward, value, length, and discount tensors for PPO training', 'list all GPU device names detected by TensorFlow for multi-GPU PPO training configuration']
```

Usage

```
{'create_EpisodeMemory': 'create an EpisodeMemory instance with a tensor template, capacity, max_length, and variable scope', 'append_transitions_to_EpisodeMemory': 'append a batch of transition tuples to specific rows in the EpisodeMemory', 'replace_episodes_in_EpisodeMemory': 'replace full episodes in the EpisodeMemory with new transition data and sequence lengths', 'retrieve_data_from_EpisodeMemory': 'retrieve a batch of episodes and their sequence lengths from the EpisodeMemory', 'clear_EpisodeMemory': 'reset episodes in the EpisodeMemory by setting their lengths to zero'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/agents/ppo/normalize.py

Prompts

```
['create a PPOAlgorithm instance with a batch environment, training step, and config object', 'perform action selection by calling PPOAlgorithm.perform with a batch of observation tensors', 'begin a new episode by calling PPOAlgorithm.begin_episode with agent index tensors', 'end an episode by calling PPOAlgorithm.end_episode to store episodes and trigger training updates', 'review the PPOAlgorithm training loop including policy update, value update, and KL penalty adjustment', 'create an EpisodeMemory instance with a tensor template, capacity, max_length, and variable scope', 'append a batch of transition tuples to specific rows in the EpisodeMemory', 'replace full episodes in the EpisodeMemory with new transition data and sequence lengths', 'retrieve a batch of episodes and their sequence lengths from the EpisodeMemory', 'reset episodes in the EpisodeMemory by setting their lengths to zero', 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance', 'transform a batch or single tensor using StreamingNormalize to normalize values by mean and stddev', 'update the StreamingNormalize mean and variance estimates with new batch or single value tensors', 'reset the StreamingNormalize mean and variance estimates back to their initial zero state', 'summarize the StreamingNormalize current mean and standard deviation estimates as a merged summary tensor', 'create TensorFlow variables from a nested tuple of tensors for PPO algorithm state tracking', 'reset all variables in a nested tuple to zeros with optional index-based partial reset', 'assign tensors to a matching nested tuple of variables in a single grouped operation', 'compute Generalized Advantage Estimation from reward, value, length, and discount tensors for PPO training', 'list all GPU device names detected by TensorFlow for multi-GPU PPO training configuration']
```

Usage

```
{'create_StreamingNormalize': 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance', 'transform_tensor_with_StreamingNormalize': 'transform a batch or single tensor using StreamingNormalize to normalize values by mean and stddev', 'update_StreamingNormalize_estimates': 'update the StreamingNormalize mean and variance estimates with new batch or single value tensors', 'reset_StreamingNormalize': 'reset the StreamingNormalize mean and variance estimates back to their initial zero state', 'summarize_StreamingNormalize_stats': 'summarize the StreamingNormalize current mean and standard deviation estimates as a merged summary tensor'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/agents/ppo/utility.py

Prompts

```
['create a PPOAlgorithm instance with a batch environment, training step, and config object', 'perform action selection by calling PPOAlgorithm.perform with a batch of observation tensors', 'begin a new episode by calling PPOAlgorithm.begin_episode with agent index tensors', 'end an episode by calling PPOAlgorithm.end_episode to store episodes and trigger training updates', 'review the PPOAlgorithm training loop including policy update, value update, and KL penalty adjustment', 'create an EpisodeMemory instance with a tensor template, capacity, max_length, and variable scope', 'append a batch of transition tuples to specific rows in the EpisodeMemory', 'replace full episodes in the EpisodeMemory with new transition data and sequence lengths', 'retrieve a batch of episodes and their sequence lengths from the EpisodeMemory', 'reset episodes in the EpisodeMemory by setting their lengths to zero', 'create a StreamingNormalize instance with a template tensor to track streaming mean and variance', 'transform a batch or single tensor using StreamingNormalize to normalize values by mean and stddev', 'update the StreamingNormalize mean and variance estimates with new batch or single value tensors', 'reset the StreamingNormalize mean and variance estimates back to their initial zero state', 'summarize the StreamingNormalize current mean and standard deviation estimates as a merged summary tensor', 'create TensorFlow variables from a nested tuple of tensors for PPO algorithm state tracking', 'reset all variables in a nested tuple to zeros with optional index-based partial reset', 'assign tensors to a matching nested tuple of variables in a single grouped operation', 'compute Generalized Advantage Estimation from reward, value, length, and discount tensors for PPO training', 'list all GPU device names detected by TensorFlow for multi-GPU PPO training configuration']
```

Usage

```
{'create_nested_vars': 'create TensorFlow variables from a nested tuple of tensors for PPO algorithm state tracking', 'reinit_nested_vars': 'reset all variables in a nested tuple to zeros with optional index-based partial reset', 'assign_nested_vars': 'assign tensors to a matching nested tuple of variables in a single grouped operation', 'lambda_advantage': 'compute Generalized Advantage Estimation from reward, value, length, and discount tensors for PPO training', 'available_gpus': 'list all GPU device names detected by TensorFlow for multi-GPU PPO training configuration'}
```

