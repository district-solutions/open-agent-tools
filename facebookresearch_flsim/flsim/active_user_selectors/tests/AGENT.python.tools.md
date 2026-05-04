# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/active_user_selectors/tests/test_active_user_selector.py

Prompts

```
['test the SequentialActiveUserSelector to cycle through users in order each FL round', 'test the UniformlyRandomActiveUserSelector to pick random users each FL training round', 'test the ImportanceSamplingActiveUserSelector to weight user selection by sample count', 'test the RandomRoundRobinActiveUserSelector to sample users without replacement across rounds', 'test ActiveUserSelectorUtils convert_to_probability to compute softmax probabilities with temperature and weights']
```

Usage

```
{'test_sequential_user_selector': 'test the SequentialActiveUserSelector to cycle through users in order each FL round', 'test_uniformly_random_user_selector': 'test the UniformlyRandomActiveUserSelector to pick random users each FL training round', 'test_importance_sampling_user_selector': 'test the ImportanceSamplingActiveUserSelector to weight user selection by sample count', 'test_random_round_robin_user_selector': 'test the RandomRoundRobinActiveUserSelector to sample users without replacement across rounds', 'test_convert_to_probability': 'test ActiveUserSelectorUtils convert_to_probability to compute softmax probabilities with temperature and weights'}
```

