# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/replay_buffers/replay_buffer.py

Prompts

```
['implement a concrete ReplayBuffer subclass that overrides push, sample, clear, and __len__ abstract methods', 'push a transition with state, action, reward, and termination flags into a ReplayBuffer subclass instance', 'sample a batch of transitions from a ReplayBuffer subclass for training a reinforcement learning agent', 'set the device_for_batches property on a ReplayBuffer subclass to move sampled batches to GPU', 'set the is_action_continuous property on a ReplayBuffer subclass to indicate continuous action space', 'create a TensorBasedReplayBuffer instance with a specified capacity for storing RL transitions', 'push a state action reward transition into the replay buffer with optional cost', 'sample a random batch of transitions from the replay buffer and return a TransitionBatch', 'create padded action tensors and boolean masks for discrete action spaces with unavailable actions', 'create a TransitionBatch by concatenating a list of individual Transition objects into batched tensors', 'create a Transition dataclass instance with state, action, and reward tensors for a single RL transition', 'create a TransitionBatch dataclass instance with batched state, action, and reward tensors for replay buffer storage', 'move a Transition instance and all its tensor fields to a specified torch device using the to method', 'validate a TransitionBatch shape and dimensions automatically via the __post_init__ method on instantiation', 'filter a TransitionWithBootstrapMaskBatch by ensemble index z using filter_batch_by_bootstrap_mask to get active transitions']
```

Usage

```
{'implement_ReplayBuffer_subclass': 'implement a concrete ReplayBuffer subclass that overrides push, sample, clear, and __len__ abstract methods', 'push_transition_to_ReplayBuffer': 'push a transition with state, action, reward, and termination flags into a ReplayBuffer subclass instance', 'sample_batch_from_ReplayBuffer': 'sample a batch of transitions from a ReplayBuffer subclass for training a reinforcement learning agent', 'set_device_for_batches_ReplayBuffer': 'set the device_for_batches property on a ReplayBuffer subclass to move sampled batches to GPU', 'set_is_action_continuous_ReplayBuffer': 'set the is_action_continuous property on a ReplayBuffer subclass to indicate continuous action space'}
```

## File: facebookresearch_pearl/pearl/replay_buffers/tensor_based_replay_buffer.py

Prompts

```
['implement a concrete ReplayBuffer subclass that overrides push, sample, clear, and __len__ abstract methods', 'push a transition with state, action, reward, and termination flags into a ReplayBuffer subclass instance', 'sample a batch of transitions from a ReplayBuffer subclass for training a reinforcement learning agent', 'set the device_for_batches property on a ReplayBuffer subclass to move sampled batches to GPU', 'set the is_action_continuous property on a ReplayBuffer subclass to indicate continuous action space', 'create a TensorBasedReplayBuffer instance with a specified capacity for storing RL transitions', 'push a state action reward transition into the replay buffer with optional cost', 'sample a random batch of transitions from the replay buffer and return a TransitionBatch', 'create padded action tensors and boolean masks for discrete action spaces with unavailable actions', 'create a TransitionBatch by concatenating a list of individual Transition objects into batched tensors', 'create a Transition dataclass instance with state, action, and reward tensors for a single RL transition', 'create a TransitionBatch dataclass instance with batched state, action, and reward tensors for replay buffer storage', 'move a Transition instance and all its tensor fields to a specified torch device using the to method', 'validate a TransitionBatch shape and dimensions automatically via the __post_init__ method on instantiation', 'filter a TransitionWithBootstrapMaskBatch by ensemble index z using filter_batch_by_bootstrap_mask to get active transitions']
```

Usage

```
{'create_replay_buffer': 'create a TensorBasedReplayBuffer instance with a specified capacity for storing RL transitions', 'push_transition': 'push a state action reward transition into the replay buffer with optional cost', 'sample_batch': 'sample a random batch of transitions from the replay buffer and return a TransitionBatch', 'create_action_tensor_and_mask': 'create padded action tensors and boolean masks for discrete action spaces with unavailable actions', 'create_transition_batch': 'create a TransitionBatch by concatenating a list of individual Transition objects into batched tensors'}
```

## File: facebookresearch_pearl/pearl/replay_buffers/transition.py

Prompts

```
['implement a concrete ReplayBuffer subclass that overrides push, sample, clear, and __len__ abstract methods', 'push a transition with state, action, reward, and termination flags into a ReplayBuffer subclass instance', 'sample a batch of transitions from a ReplayBuffer subclass for training a reinforcement learning agent', 'set the device_for_batches property on a ReplayBuffer subclass to move sampled batches to GPU', 'set the is_action_continuous property on a ReplayBuffer subclass to indicate continuous action space', 'create a TensorBasedReplayBuffer instance with a specified capacity for storing RL transitions', 'push a state action reward transition into the replay buffer with optional cost', 'sample a random batch of transitions from the replay buffer and return a TransitionBatch', 'create padded action tensors and boolean masks for discrete action spaces with unavailable actions', 'create a TransitionBatch by concatenating a list of individual Transition objects into batched tensors', 'create a Transition dataclass instance with state, action, and reward tensors for a single RL transition', 'create a TransitionBatch dataclass instance with batched state, action, and reward tensors for replay buffer storage', 'move a Transition instance and all its tensor fields to a specified torch device using the to method', 'validate a TransitionBatch shape and dimensions automatically via the __post_init__ method on instantiation', 'filter a TransitionWithBootstrapMaskBatch by ensemble index z using filter_batch_by_bootstrap_mask to get active transitions']
```

Usage

```
{'create_Transition': 'create a Transition dataclass instance with state, action, and reward tensors for a single RL transition', 'create_TransitionBatch': 'create a TransitionBatch dataclass instance with batched state, action, and reward tensors for replay buffer storage', 'use_Transition_to_device': 'move a Transition instance and all its tensor fields to a specified torch device using the to method', 'use_TransitionBatch_validation': 'validate a TransitionBatch shape and dimensions automatically via the __post_init__ method on instantiation', 'filter_batch_by_bootstrap_mask': 'filter a TransitionWithBootstrapMaskBatch by ensemble index z using filter_batch_by_bootstrap_mask to get active transitions'}
```

