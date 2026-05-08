# Agent Python Tools

- repo: facebookresearch/collaq
- repo_uri: https://github.com/facebookresearch/collaq

## File: facebookresearch_collaq/third_party/pymarl/src/components/action_selectors.py

Prompts

```
['create a MultinomialActionSelector that samples actions from masked policy distributions using Categorical sampling', 'create an EpsilonGreedyActionSelector that selects actions using epsilon-greedy strategy with linear decay schedule', 'select actions from agent policy inputs by sampling from a masked Categorical distribution', 'select actions using epsilon-greedy exploration by masking unavailable Q-values and sampling randomly or greedily', 'register a new action selector class in the REGISTRY dictionary by key name', 'create an EpisodeBatch with a scheme, groups, batch size, and max sequence length for MARL episode data', 'update an EpisodeBatch with new transition or episode data using batch and time slices', 'sample a random batch of episodes from a ReplayBuffer for training a multi-agent RL policy', 'insert an EpisodeBatch into a ReplayBuffer with automatic wraparound and buffer index management', 'slice an EpisodeBatch by batch index or time steps to extract subsets of episode data', 'create a DecayThenFlatSchedule with linear decay from start to finish over a given time_length', 'create a DecayThenFlatSchedule with exponential decay from start to finish over a given time_length', 'eval a DecayThenFlatSchedule at time step T to get the current epsilon value', 'review the DecayThenFlatSchedule class and its linear and exponential decay evaluation logic', 'refactor the DecayThenFlatSchedule eval method to support additional decay types beyond linear and exp', 'create a OneHot transform that one-hot encodes a PyTorch tensor to a specified output dimension', 'transform a PyTorch tensor into a one-hot encoded tensor using the OneHot transform class', 'infer the output shape and dtype of a OneHot transform given input shape and dtype', 'extend the Transform base class to implement a custom tensor transformation with transform and infer_output_info methods', 'review the Transform base class and OneHot subclass for tensor transformation capabilities in PyMARL']
```

Usage

```
{'create_multinomial_action_selector': 'create a MultinomialActionSelector that samples actions from masked policy distributions using Categorical sampling', 'create_epsilon_greedy_action_selector': 'create an EpsilonGreedyActionSelector that selects actions using epsilon-greedy strategy with linear decay schedule', 'select_action_multinomial': 'select actions from agent policy inputs by sampling from a masked Categorical distribution', 'select_action_epsilon_greedy': 'select actions using epsilon-greedy exploration by masking unavailable Q-values and sampling randomly or greedily', 'register_action_selector': 'register a new action selector class in the REGISTRY dictionary by key name'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/components/episode_buffer.py

Prompts

```
['create a MultinomialActionSelector that samples actions from masked policy distributions using Categorical sampling', 'create an EpsilonGreedyActionSelector that selects actions using epsilon-greedy strategy with linear decay schedule', 'select actions from agent policy inputs by sampling from a masked Categorical distribution', 'select actions using epsilon-greedy exploration by masking unavailable Q-values and sampling randomly or greedily', 'register a new action selector class in the REGISTRY dictionary by key name', 'create an EpisodeBatch with a scheme, groups, batch size, and max sequence length for MARL episode data', 'update an EpisodeBatch with new transition or episode data using batch and time slices', 'sample a random batch of episodes from a ReplayBuffer for training a multi-agent RL policy', 'insert an EpisodeBatch into a ReplayBuffer with automatic wraparound and buffer index management', 'slice an EpisodeBatch by batch index or time steps to extract subsets of episode data', 'create a DecayThenFlatSchedule with linear decay from start to finish over a given time_length', 'create a DecayThenFlatSchedule with exponential decay from start to finish over a given time_length', 'eval a DecayThenFlatSchedule at time step T to get the current epsilon value', 'review the DecayThenFlatSchedule class and its linear and exponential decay evaluation logic', 'refactor the DecayThenFlatSchedule eval method to support additional decay types beyond linear and exp', 'create a OneHot transform that one-hot encodes a PyTorch tensor to a specified output dimension', 'transform a PyTorch tensor into a one-hot encoded tensor using the OneHot transform class', 'infer the output shape and dtype of a OneHot transform given input shape and dtype', 'extend the Transform base class to implement a custom tensor transformation with transform and infer_output_info methods', 'review the Transform base class and OneHot subclass for tensor transformation capabilities in PyMARL']
```

Usage

```
{'create_EpisodeBatch': 'create an EpisodeBatch with a scheme, groups, batch size, and max sequence length for MARL episode data', 'update_EpisodeBatch': 'update an EpisodeBatch with new transition or episode data using batch and time slices', 'sample_ReplayBuffer': 'sample a random batch of episodes from a ReplayBuffer for training a multi-agent RL policy', 'insert_ReplayBuffer': 'insert an EpisodeBatch into a ReplayBuffer with automatic wraparound and buffer index management', 'slice_EpisodeBatch': 'slice an EpisodeBatch by batch index or time steps to extract subsets of episode data'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/components/epsilon_schedules.py

Prompts

```
['create a MultinomialActionSelector that samples actions from masked policy distributions using Categorical sampling', 'create an EpsilonGreedyActionSelector that selects actions using epsilon-greedy strategy with linear decay schedule', 'select actions from agent policy inputs by sampling from a masked Categorical distribution', 'select actions using epsilon-greedy exploration by masking unavailable Q-values and sampling randomly or greedily', 'register a new action selector class in the REGISTRY dictionary by key name', 'create an EpisodeBatch with a scheme, groups, batch size, and max sequence length for MARL episode data', 'update an EpisodeBatch with new transition or episode data using batch and time slices', 'sample a random batch of episodes from a ReplayBuffer for training a multi-agent RL policy', 'insert an EpisodeBatch into a ReplayBuffer with automatic wraparound and buffer index management', 'slice an EpisodeBatch by batch index or time steps to extract subsets of episode data', 'create a DecayThenFlatSchedule with linear decay from start to finish over a given time_length', 'create a DecayThenFlatSchedule with exponential decay from start to finish over a given time_length', 'eval a DecayThenFlatSchedule at time step T to get the current epsilon value', 'review the DecayThenFlatSchedule class and its linear and exponential decay evaluation logic', 'refactor the DecayThenFlatSchedule eval method to support additional decay types beyond linear and exp', 'create a OneHot transform that one-hot encodes a PyTorch tensor to a specified output dimension', 'transform a PyTorch tensor into a one-hot encoded tensor using the OneHot transform class', 'infer the output shape and dtype of a OneHot transform given input shape and dtype', 'extend the Transform base class to implement a custom tensor transformation with transform and infer_output_info methods', 'review the Transform base class and OneHot subclass for tensor transformation capabilities in PyMARL']
```

Usage

```
{'create_decay_then_flat_schedule_linear': 'create a DecayThenFlatSchedule with linear decay from start to finish over a given time_length', 'create_decay_then_flat_schedule_exp': 'create a DecayThenFlatSchedule with exponential decay from start to finish over a given time_length', 'eval_schedule_at_time': 'eval a DecayThenFlatSchedule at time step T to get the current epsilon value', 'review_decay_then_flat_schedule_class': 'review the DecayThenFlatSchedule class and its linear and exponential decay evaluation logic', 'refactor_eval_method': 'refactor the DecayThenFlatSchedule eval method to support additional decay types beyond linear and exp'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/components/transforms.py

Prompts

```
['create a MultinomialActionSelector that samples actions from masked policy distributions using Categorical sampling', 'create an EpsilonGreedyActionSelector that selects actions using epsilon-greedy strategy with linear decay schedule', 'select actions from agent policy inputs by sampling from a masked Categorical distribution', 'select actions using epsilon-greedy exploration by masking unavailable Q-values and sampling randomly or greedily', 'register a new action selector class in the REGISTRY dictionary by key name', 'create an EpisodeBatch with a scheme, groups, batch size, and max sequence length for MARL episode data', 'update an EpisodeBatch with new transition or episode data using batch and time slices', 'sample a random batch of episodes from a ReplayBuffer for training a multi-agent RL policy', 'insert an EpisodeBatch into a ReplayBuffer with automatic wraparound and buffer index management', 'slice an EpisodeBatch by batch index or time steps to extract subsets of episode data', 'create a DecayThenFlatSchedule with linear decay from start to finish over a given time_length', 'create a DecayThenFlatSchedule with exponential decay from start to finish over a given time_length', 'eval a DecayThenFlatSchedule at time step T to get the current epsilon value', 'review the DecayThenFlatSchedule class and its linear and exponential decay evaluation logic', 'refactor the DecayThenFlatSchedule eval method to support additional decay types beyond linear and exp', 'create a OneHot transform that one-hot encodes a PyTorch tensor to a specified output dimension', 'transform a PyTorch tensor into a one-hot encoded tensor using the OneHot transform class', 'infer the output shape and dtype of a OneHot transform given input shape and dtype', 'extend the Transform base class to implement a custom tensor transformation with transform and infer_output_info methods', 'review the Transform base class and OneHot subclass for tensor transformation capabilities in PyMARL']
```

Usage

```
{'create_onehot_transform': 'create a OneHot transform that one-hot encodes a PyTorch tensor to a specified output dimension', 'transform_tensor_onehot': 'transform a PyTorch tensor into a one-hot encoded tensor using the OneHot transform class', 'infer_output_info_onehot': 'infer the output shape and dtype of a OneHot transform given input shape and dtype', 'extend_transform_base': 'extend the Transform base class to implement a custom tensor transformation with transform and infer_output_info methods', 'review_transform_classes': 'review the Transform base class and OneHot subclass for tensor transformation capabilities in PyMARL'}
```

