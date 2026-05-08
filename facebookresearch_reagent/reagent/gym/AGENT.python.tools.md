# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/gym/normalizers.py

Prompts

```
['create a normalizer for discrete action features using the discrete_action_normalizer function', 'create a normalizer for continuous features with optional min and max value bounds', 'create a normalizer for continuous action features with optional min and max value bounds', 'build an OrderedDict of NormalizationParameters for features with a specified feature type', 'review the normalizer_helper function to understand feature type validation and normalization parameter creation', 'create a Transition dataclass instance with mdp_id, observation, action, reward, and terminal fields', 'add a Transition object to a Trajectory using the add_transition method to build episode history', 'calculate the discounted cumulative reward of a Trajectory using calculate_cumulative_reward with a gamma parameter', 'convert a Trajectory to a dictionary of PyTorch tensors using the to_dict method for training input', 'implement a Sampler subclass with sample_action and log_prob methods for action selection from scores', 'fill a replay buffer with transitions from running episodes using an agent and environment', 'build a state and action normalizer dictionary from a gym environment wrapper', 'create a pandas DataFrame from replay buffer samples for a given problem domain', 'transform a batch of features using a single element transform function with optional terminal handling', 'validate that MDP IDs and sequence numbers in a DataFrame are in correct increasing order']
```

Usage

```
{'create_discrete_action_normalizer': 'create a normalizer for discrete action features using the discrete_action_normalizer function', 'create_continuous_normalizer': 'create a normalizer for continuous features with optional min and max value bounds', 'create_continuous_action_normalizer': 'create a normalizer for continuous action features with optional min and max value bounds', 'build_normalizer_helper': 'build an OrderedDict of NormalizationParameters for features with a specified feature type', 'review_normalizer_helper': 'review the normalizer_helper function to understand feature type validation and normalization parameter creation'}
```

## File: facebookresearch_reagent/reagent/gym/types.py

Prompts

```
['create a normalizer for discrete action features using the discrete_action_normalizer function', 'create a normalizer for continuous features with optional min and max value bounds', 'create a normalizer for continuous action features with optional min and max value bounds', 'build an OrderedDict of NormalizationParameters for features with a specified feature type', 'review the normalizer_helper function to understand feature type validation and normalization parameter creation', 'create a Transition dataclass instance with mdp_id, observation, action, reward, and terminal fields', 'add a Transition object to a Trajectory using the add_transition method to build episode history', 'calculate the discounted cumulative reward of a Trajectory using calculate_cumulative_reward with a gamma parameter', 'convert a Trajectory to a dictionary of PyTorch tensors using the to_dict method for training input', 'implement a Sampler subclass with sample_action and log_prob methods for action selection from scores', 'fill a replay buffer with transitions from running episodes using an agent and environment', 'build a state and action normalizer dictionary from a gym environment wrapper', 'create a pandas DataFrame from replay buffer samples for a given problem domain', 'transform a batch of features using a single element transform function with optional terminal handling', 'validate that MDP IDs and sequence numbers in a DataFrame are in correct increasing order']
```

Usage

```
{'create_Transition_dataclass': 'create a Transition dataclass instance with mdp_id, observation, action, reward, and terminal fields', 'add_transition_to_Trajectory': 'add a Transition object to a Trajectory using the add_transition method to build episode history', 'calculate_cumulative_reward_Trajectory': 'calculate the discounted cumulative reward of a Trajectory using calculate_cumulative_reward with a gamma parameter', 'convert_Trajectory_to_dict': 'convert a Trajectory to a dictionary of PyTorch tensors using the to_dict method for training input', 'implement_Sampler_subclass': 'implement a Sampler subclass with sample_action and log_prob methods for action selection from scores'}
```

## File: facebookresearch_reagent/reagent/gym/utils.py

Prompts

```
['create a normalizer for discrete action features using the discrete_action_normalizer function', 'create a normalizer for continuous features with optional min and max value bounds', 'create a normalizer for continuous action features with optional min and max value bounds', 'build an OrderedDict of NormalizationParameters for features with a specified feature type', 'review the normalizer_helper function to understand feature type validation and normalization parameter creation', 'create a Transition dataclass instance with mdp_id, observation, action, reward, and terminal fields', 'add a Transition object to a Trajectory using the add_transition method to build episode history', 'calculate the discounted cumulative reward of a Trajectory using calculate_cumulative_reward with a gamma parameter', 'convert a Trajectory to a dictionary of PyTorch tensors using the to_dict method for training input', 'implement a Sampler subclass with sample_action and log_prob methods for action selection from scores', 'fill a replay buffer with transitions from running episodes using an agent and environment', 'build a state and action normalizer dictionary from a gym environment wrapper', 'create a pandas DataFrame from replay buffer samples for a given problem domain', 'transform a batch of features using a single element transform function with optional terminal handling', 'validate that MDP IDs and sequence numbers in a DataFrame are in correct increasing order']
```

Usage

```
{'fill_replay_buffer': 'fill a replay buffer with transitions from running episodes using an agent and environment', 'build_normalizer': 'build a state and action normalizer dictionary from a gym environment wrapper', 'create_df_from_replay_buffer': 'create a pandas DataFrame from replay buffer samples for a given problem domain', 'feature_transform': 'transform a batch of features using a single element transform function with optional terminal handling', 'validate_mdp_ids_seq_nums': 'validate that MDP IDs and sequence numbers in a DataFrame are in correct increasing order'}
```

