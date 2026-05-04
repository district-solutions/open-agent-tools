# Agent Python Tools

- repo: facebookresearch/dcd
- repo_uri: https://github.com/facebookresearch/dcd

## File: facebookresearch_dcd/algos/agent.py

Prompts

```
['create an ACAgent instance by passing an algo and storage object to the constructor', 'update the ACAgent by calling update with optional discard_grad and kl_dict parameters', 'act using the ACAgent by calling act with observation and recurrent hidden state arguments', 'get the value estimate from the ACAgent by calling get_value with the current observation', 'move the ACAgent and its storage to a target device like cuda by calling to', 'create a PPO reinforcement learning agent with an actor-critic network and Adam optimizer', 'update the PPO policy using rollout data with clipped surrogate objective and value loss', 'compute the L2 gradient norm across all actor-critic parameters for monitoring training stability', 'review the PPO update method to understand clipped surrogate loss and advantage normalization logic', 'refactor the PPO update method to add or modify KL divergence loss between protagonist and antagonist distributions', 'create a RolloutStorage buffer to store observations, actions, rewards, and value predictions for PPO training', 'insert a timestep of observations, actions, rewards, and masks into the RolloutStorage buffer', 'compute GAE or discounted returns for all timesteps in the RolloutStorage buffer using gamma and lambda', 'generate mini-batches from the RolloutStorage buffer for feed-forward PPO policy updates', 'generate mini-batches from the RolloutStorage buffer for recurrent PPO policy updates with hidden states']
```

Usage

```
{'create_acagent_instance': 'create an ACAgent instance by passing an algo and storage object to the constructor', 'update_acagent': 'update the ACAgent by calling update with optional discard_grad and kl_dict parameters', 'act_with_acagent': 'act using the ACAgent by calling act with observation and recurrent hidden state arguments', 'get_value_from_acagent': 'get the value estimate from the ACAgent by calling get_value with the current observation', 'move_acagent_to_device': 'move the ACAgent and its storage to a target device like cuda by calling to'}
```

## File: facebookresearch_dcd/algos/ppo.py

Prompts

```
['create an ACAgent instance by passing an algo and storage object to the constructor', 'update the ACAgent by calling update with optional discard_grad and kl_dict parameters', 'act using the ACAgent by calling act with observation and recurrent hidden state arguments', 'get the value estimate from the ACAgent by calling get_value with the current observation', 'move the ACAgent and its storage to a target device like cuda by calling to', 'create a PPO reinforcement learning agent with an actor-critic network and Adam optimizer', 'update the PPO policy using rollout data with clipped surrogate objective and value loss', 'compute the L2 gradient norm across all actor-critic parameters for monitoring training stability', 'review the PPO update method to understand clipped surrogate loss and advantage normalization logic', 'refactor the PPO update method to add or modify KL divergence loss between protagonist and antagonist distributions', 'create a RolloutStorage buffer to store observations, actions, rewards, and value predictions for PPO training', 'insert a timestep of observations, actions, rewards, and masks into the RolloutStorage buffer', 'compute GAE or discounted returns for all timesteps in the RolloutStorage buffer using gamma and lambda', 'generate mini-batches from the RolloutStorage buffer for feed-forward PPO policy updates', 'generate mini-batches from the RolloutStorage buffer for recurrent PPO policy updates with hidden states']
```

Usage

```
{'create_PPO_agent': 'create a PPO reinforcement learning agent with an actor-critic network and Adam optimizer', 'update_PPO_policy': 'update the PPO policy using rollout data with clipped surrogate objective and value loss', 'compute_PPO_grad_norm': 'compute the L2 gradient norm across all actor-critic parameters for monitoring training stability', 'review_PPO_update': 'review the PPO update method to understand clipped surrogate loss and advantage normalization logic', 'refactor_PPO_kl_loss': 'refactor the PPO update method to add or modify KL divergence loss between protagonist and antagonist distributions'}
```

## File: facebookresearch_dcd/algos/storage.py

Prompts

```
['create an ACAgent instance by passing an algo and storage object to the constructor', 'update the ACAgent by calling update with optional discard_grad and kl_dict parameters', 'act using the ACAgent by calling act with observation and recurrent hidden state arguments', 'get the value estimate from the ACAgent by calling get_value with the current observation', 'move the ACAgent and its storage to a target device like cuda by calling to', 'create a PPO reinforcement learning agent with an actor-critic network and Adam optimizer', 'update the PPO policy using rollout data with clipped surrogate objective and value loss', 'compute the L2 gradient norm across all actor-critic parameters for monitoring training stability', 'review the PPO update method to understand clipped surrogate loss and advantage normalization logic', 'refactor the PPO update method to add or modify KL divergence loss between protagonist and antagonist distributions', 'create a RolloutStorage buffer to store observations, actions, rewards, and value predictions for PPO training', 'insert a timestep of observations, actions, rewards, and masks into the RolloutStorage buffer', 'compute GAE or discounted returns for all timesteps in the RolloutStorage buffer using gamma and lambda', 'generate mini-batches from the RolloutStorage buffer for feed-forward PPO policy updates', 'generate mini-batches from the RolloutStorage buffer for recurrent PPO policy updates with hidden states']
```

Usage

```
{'create_RolloutStorage': 'create a RolloutStorage buffer to store observations, actions, rewards, and value predictions for PPO training', 'insert_rollout_data': 'insert a timestep of observations, actions, rewards, and masks into the RolloutStorage buffer', 'compute_returns': 'compute GAE or discounted returns for all timesteps in the RolloutStorage buffer using gamma and lambda', 'generate_feed_forward_batches': 'generate mini-batches from the RolloutStorage buffer for feed-forward PPO policy updates', 'generate_recurrent_batches': 'generate mini-batches from the RolloutStorage buffer for recurrent PPO policy updates with hidden states'}
```

