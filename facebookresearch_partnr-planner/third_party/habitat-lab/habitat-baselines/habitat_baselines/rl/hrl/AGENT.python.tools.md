# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hierarchical_policy.py

Prompts

```
['build a hierarchical RL policy that coordinates high-level and low-level skill policies for navigation tasks', 'create a HierarchicalPolicy instance from a Habitat config with observation and action spaces', 'test the HierarchicalPolicy act method to select actions by delegating between high-level and low-level skills', 'refactor the HierarchicalPolicy _update_skills method to change how the high-level policy selects and initializes new skills', 'review the HierarchicalPolicy _broadcast_skill_ids method that groups batched observations by active skill for efficient processing', 'review the HRLPPO class that extends PPO for hierarchical reinforcement learning policy updates', 'review the HRLDDPPO class that adds decentralized distributed training to HRLPPO', 'summarize the _update_from_batch method that computes PPO clipped surrogate loss and value loss', 'refactor the reduce_loss helper to support custom masking strategies for batched loss computation', 'test the HRLPPO _update_from_batch method with mock rollouts and learner metrics', 'create an HrlRolloutStorage instance with numsteps and num_envs for hierarchical RL rollout buffering', 'insert observations, actions, rewards, and value predictions into the HRL rollout buffer with conditional should_inserts', 'compute GAE returns for the HRL rollout buffer using gamma and tau discounting parameters', 'generate shuffled data batches from the HRL rollout storage for training with RNN sequence info', 'advance the HRL rollout write index forward only for environments that were inserted in the previous step', 'find the start and end indices of an action key in a Habitat action space tensor', 'review the find_action_range function to understand how it calculates action index ranges in HRL', 'test the find_action_range function with a Habitat ActionSpace and a valid search key', 'refactor the find_action_range function to return None instead of raising ValueError for missing keys', 'summarize the find_action_range utility used for hierarchical reinforcement learning action space indexing']
```

Usage

```
{'build_HierarchicalPolicy': 'build a hierarchical RL policy that coordinates high-level and low-level skill policies for navigation tasks', 'create_HierarchicalPolicy_from_config': 'create a HierarchicalPolicy instance from a Habitat config with observation and action spaces', 'test_HierarchicalPolicy_act': 'test the HierarchicalPolicy act method to select actions by delegating between high-level and low-level skills', 'refactor_HierarchicalPolicy_update_skills': 'refactor the HierarchicalPolicy _update_skills method to change how the high-level policy selects and initializes new skills', 'review_HierarchicalPolicy_broadcast_skill_ids': 'review the HierarchicalPolicy _broadcast_skill_ids method that groups batched observations by active skill for efficient processing'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hrl_ppo.py

Prompts

```
['build a hierarchical RL policy that coordinates high-level and low-level skill policies for navigation tasks', 'create a HierarchicalPolicy instance from a Habitat config with observation and action spaces', 'test the HierarchicalPolicy act method to select actions by delegating between high-level and low-level skills', 'refactor the HierarchicalPolicy _update_skills method to change how the high-level policy selects and initializes new skills', 'review the HierarchicalPolicy _broadcast_skill_ids method that groups batched observations by active skill for efficient processing', 'review the HRLPPO class that extends PPO for hierarchical reinforcement learning policy updates', 'review the HRLDDPPO class that adds decentralized distributed training to HRLPPO', 'summarize the _update_from_batch method that computes PPO clipped surrogate loss and value loss', 'refactor the reduce_loss helper to support custom masking strategies for batched loss computation', 'test the HRLPPO _update_from_batch method with mock rollouts and learner metrics', 'create an HrlRolloutStorage instance with numsteps and num_envs for hierarchical RL rollout buffering', 'insert observations, actions, rewards, and value predictions into the HRL rollout buffer with conditional should_inserts', 'compute GAE returns for the HRL rollout buffer using gamma and tau discounting parameters', 'generate shuffled data batches from the HRL rollout storage for training with RNN sequence info', 'advance the HRL rollout write index forward only for environments that were inserted in the previous step', 'find the start and end indices of an action key in a Habitat action space tensor', 'review the find_action_range function to understand how it calculates action index ranges in HRL', 'test the find_action_range function with a Habitat ActionSpace and a valid search key', 'refactor the find_action_range function to return None instead of raising ValueError for missing keys', 'summarize the find_action_range utility used for hierarchical reinforcement learning action space indexing']
```

Usage

```
{'review_HRLPPO_class': 'review the HRLPPO class that extends PPO for hierarchical reinforcement learning policy updates', 'review_HRLDDPPO_class': 'review the HRLDDPPO class that adds decentralized distributed training to HRLPPO', 'summarize_update_from_batch': 'summarize the _update_from_batch method that computes PPO clipped surrogate loss and value loss', 'refactor_reduce_loss': 'refactor the reduce_loss helper to support custom masking strategies for batched loss computation', 'test_HRLPPO_training': 'test the HRLPPO _update_from_batch method with mock rollouts and learner metrics'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/hrl_rollout_storage.py

Prompts

```
['build a hierarchical RL policy that coordinates high-level and low-level skill policies for navigation tasks', 'create a HierarchicalPolicy instance from a Habitat config with observation and action spaces', 'test the HierarchicalPolicy act method to select actions by delegating between high-level and low-level skills', 'refactor the HierarchicalPolicy _update_skills method to change how the high-level policy selects and initializes new skills', 'review the HierarchicalPolicy _broadcast_skill_ids method that groups batched observations by active skill for efficient processing', 'review the HRLPPO class that extends PPO for hierarchical reinforcement learning policy updates', 'review the HRLDDPPO class that adds decentralized distributed training to HRLPPO', 'summarize the _update_from_batch method that computes PPO clipped surrogate loss and value loss', 'refactor the reduce_loss helper to support custom masking strategies for batched loss computation', 'test the HRLPPO _update_from_batch method with mock rollouts and learner metrics', 'create an HrlRolloutStorage instance with numsteps and num_envs for hierarchical RL rollout buffering', 'insert observations, actions, rewards, and value predictions into the HRL rollout buffer with conditional should_inserts', 'compute GAE returns for the HRL rollout buffer using gamma and tau discounting parameters', 'generate shuffled data batches from the HRL rollout storage for training with RNN sequence info', 'advance the HRL rollout write index forward only for environments that were inserted in the previous step', 'find the start and end indices of an action key in a Habitat action space tensor', 'review the find_action_range function to understand how it calculates action index ranges in HRL', 'test the find_action_range function with a Habitat ActionSpace and a valid search key', 'refactor the find_action_range function to return None instead of raising ValueError for missing keys', 'summarize the find_action_range utility used for hierarchical reinforcement learning action space indexing']
```

Usage

```
{'create_HrlRolloutStorage': 'create an HrlRolloutStorage instance with numsteps and num_envs for hierarchical RL rollout buffering', 'insert_HrlRolloutStorage': 'insert observations, actions, rewards, and value predictions into the HRL rollout buffer with conditional should_inserts', 'compute_returns_HrlRolloutStorage': 'compute GAE returns for the HRL rollout buffer using gamma and tau discounting parameters', 'data_generator_HrlRolloutStorage': 'generate shuffled data batches from the HRL rollout storage for training with RNN sequence info', 'advance_rollout_HrlRolloutStorage': 'advance the HRL rollout write index forward only for environments that were inserted in the previous step'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/hrl/utils.py

Prompts

```
['build a hierarchical RL policy that coordinates high-level and low-level skill policies for navigation tasks', 'create a HierarchicalPolicy instance from a Habitat config with observation and action spaces', 'test the HierarchicalPolicy act method to select actions by delegating between high-level and low-level skills', 'refactor the HierarchicalPolicy _update_skills method to change how the high-level policy selects and initializes new skills', 'review the HierarchicalPolicy _broadcast_skill_ids method that groups batched observations by active skill for efficient processing', 'review the HRLPPO class that extends PPO for hierarchical reinforcement learning policy updates', 'review the HRLDDPPO class that adds decentralized distributed training to HRLPPO', 'summarize the _update_from_batch method that computes PPO clipped surrogate loss and value loss', 'refactor the reduce_loss helper to support custom masking strategies for batched loss computation', 'test the HRLPPO _update_from_batch method with mock rollouts and learner metrics', 'create an HrlRolloutStorage instance with numsteps and num_envs for hierarchical RL rollout buffering', 'insert observations, actions, rewards, and value predictions into the HRL rollout buffer with conditional should_inserts', 'compute GAE returns for the HRL rollout buffer using gamma and tau discounting parameters', 'generate shuffled data batches from the HRL rollout storage for training with RNN sequence info', 'advance the HRL rollout write index forward only for environments that were inserted in the previous step', 'find the start and end indices of an action key in a Habitat action space tensor', 'review the find_action_range function to understand how it calculates action index ranges in HRL', 'test the find_action_range function with a Habitat ActionSpace and a valid search key', 'refactor the find_action_range function to return None instead of raising ValueError for missing keys', 'summarize the find_action_range utility used for hierarchical reinforcement learning action space indexing']
```

Usage

```
{'find_action_range': 'find the start and end indices of an action key in a Habitat action space tensor', 'review_find_action_range': 'review the find_action_range function to understand how it calculates action index ranges in HRL', 'test_find_action_range': 'test the find_action_range function with a Habitat ActionSpace and a valid search key', 'refactor_find_action_range': 'refactor the find_action_range function to return None instead of raising ValueError for missing keys', 'summarize_find_action_range': 'summarize the find_action_range utility used for hierarchical reinforcement learning action space indexing'}
```

