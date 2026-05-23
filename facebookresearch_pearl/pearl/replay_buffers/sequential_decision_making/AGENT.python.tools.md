# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/replay_buffers/sequential_decision_making/bootstrap_replay_buffer.py

Prompts

```
['create a BootstrapReplayBuffer with capacity, Bernoulli probability p, and ensemble size for Bootstrapped DQN', 'store a transition with state, action, reward, and Bernoulli bootstrap mask into the replay buffer', 'sample a batch of transitions with bootstrap masks from the replay buffer for training', 'review the Bernoulli(p) masking distribution implementation used in the Bootstrapped DQN ensemble replay buffer', 'refactor the BootstrapReplayBuffer to support a different masking distribution or ensemble configuration', 'create a HindsightExperienceReplayBuffer instance with capacity, goal_dim, and reward_fn for sparse reward problems', 'push state, action, reward, and next_state transitions into the HindsightExperienceReplayBuffer during an episode', 'review the HindsightExperienceReplayBuffer class that extends BasicReplayBuffer for goal-conditioned reinforcement learning', 'refactor the reward_fn callback to compute rewards from state and action for hindsight relabeling', 'test the terminated_fn callback that determines early episode termination for games']
```

Usage

```
{'create_bootstrap_replay_buffer': 'create a BootstrapReplayBuffer with capacity, Bernoulli probability p, and ensemble size for Bootstrapped DQN', 'store_transition_with_bootstrap_mask': 'store a transition with state, action, reward, and Bernoulli bootstrap mask into the replay buffer', 'sample_bootstrap_transitions': 'sample a batch of transitions with bootstrap masks from the replay buffer for training', 'review_bootstrap_mask_implementation': 'review the Bernoulli(p) masking distribution implementation used in the Bootstrapped DQN ensemble replay buffer', 'refactor_bootstrap_replay_buffer': 'refactor the BootstrapReplayBuffer to support a different masking distribution or ensemble configuration'}
```

## File: facebookresearch_pearl/pearl/replay_buffers/sequential_decision_making/hindsight_experience_replay_buffer.py

Prompts

```
['create a BootstrapReplayBuffer with capacity, Bernoulli probability p, and ensemble size for Bootstrapped DQN', 'store a transition with state, action, reward, and Bernoulli bootstrap mask into the replay buffer', 'sample a batch of transitions with bootstrap masks from the replay buffer for training', 'review the Bernoulli(p) masking distribution implementation used in the Bootstrapped DQN ensemble replay buffer', 'refactor the BootstrapReplayBuffer to support a different masking distribution or ensemble configuration', 'create a HindsightExperienceReplayBuffer instance with capacity, goal_dim, and reward_fn for sparse reward problems', 'push state, action, reward, and next_state transitions into the HindsightExperienceReplayBuffer during an episode', 'review the HindsightExperienceReplayBuffer class that extends BasicReplayBuffer for goal-conditioned reinforcement learning', 'refactor the reward_fn callback to compute rewards from state and action for hindsight relabeling', 'test the terminated_fn callback that determines early episode termination for games']
```

Usage

```
{'create_HindsightExperienceReplayBuffer': 'create a HindsightExperienceReplayBuffer instance with capacity, goal_dim, and reward_fn for sparse reward problems', 'push_transitions_to_buffer': 'push state, action, reward, and next_state transitions into the HindsightExperienceReplayBuffer during an episode', 'review_HindsightExperienceReplayBuffer_class': 'review the HindsightExperienceReplayBuffer class that extends BasicReplayBuffer for goal-conditioned reinforcement learning', 'refactor_reward_fn_callback': 'refactor the reward_fn callback to compute rewards from state and action for hindsight relabeling', 'test_terminated_fn_callback': 'test the terminated_fn callback that determines early episode termination for games'}
```

