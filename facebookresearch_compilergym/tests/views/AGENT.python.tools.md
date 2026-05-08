# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/views/observation_test.py

Prompts

```
['test that ObservationView raises ValueError when initialized with an empty list of observation spaces', 'test ObservationView access by bracket notation and bound methods for string, int64, double, and binary observation types', 'test that ObservationView raises ServiceError when raw_step returns an unexpected number of observations', 'test that ObservationView raises ServiceError when the raw_step callback returns done=True with optional error details', 'test the MockRawStep class that simulates the raw_step callback for ObservationView unit testing', 'test that RewardView raises ValueError when initialized with an empty list of reward spaces', 'test that RewardView raises KeyError when accessing a reward space by an invalid name', 'test accessing reward values through dictionary-style indexing on a RewardView instance', 'test accessing reward values through bound method calls on a RewardView instance', 'review the MockReward class that simulates reward spaces with configurable return values for testing']
```

Usage

```
{'test_ObservationView_empty_space': 'test that ObservationView raises ValueError when initialized with an empty list of observation spaces', 'test_ObservationView_observed_value_types': 'test ObservationView access by bracket notation and bound methods for string, int64, double, and binary observation types', 'test_ObservationView_incorrect_observation_count': 'test that ObservationView raises ServiceError when raw_step returns an unexpected number of observations', 'test_ObservationView_raw_step_returns_done': 'test that ObservationView raises ServiceError when the raw_step callback returns done=True with optional error details', 'test_MockRawStep_callback': 'test the MockRawStep class that simulates the raw_step callback for ObservationView unit testing'}
```

## File: facebookresearch_compilergym/tests/views/reward_test.py

Prompts

```
['test that ObservationView raises ValueError when initialized with an empty list of observation spaces', 'test ObservationView access by bracket notation and bound methods for string, int64, double, and binary observation types', 'test that ObservationView raises ServiceError when raw_step returns an unexpected number of observations', 'test that ObservationView raises ServiceError when the raw_step callback returns done=True with optional error details', 'test the MockRawStep class that simulates the raw_step callback for ObservationView unit testing', 'test that RewardView raises ValueError when initialized with an empty list of reward spaces', 'test that RewardView raises KeyError when accessing a reward space by an invalid name', 'test accessing reward values through dictionary-style indexing on a RewardView instance', 'test accessing reward values through bound method calls on a RewardView instance', 'review the MockReward class that simulates reward spaces with configurable return values for testing']
```

Usage

```
{'test_empty_reward_space': 'test that RewardView raises ValueError when initialized with an empty list of reward spaces', 'test_invalid_reward_name': 'test that RewardView raises KeyError when accessing a reward space by an invalid name', 'test_reward_values_dict_access': 'test accessing reward values through dictionary-style indexing on a RewardView instance', 'test_reward_values_bound_methods': 'test accessing reward values through bound method calls on a RewardView instance', 'review_mock_reward_class': 'review the MockReward class that simulates reward spaces with configurable return values for testing'}
```

