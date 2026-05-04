# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/bandit_scale/analysis.py

Prompts

```
['score a pandas DataFrame from bandit_scale experiments and return a float metric', 'plot learning curves for bandit_scale experiments using a pandas DataFrame', 'plot average performance across reward scales for bandit_scale experiments', 'plot performance by individual work unit with reward scale coloring', 'review the bandit_scale analysis module score and plotting functions', 'run a bandit_scale experiment by calling load with a reward_scale, seed, and mapping_seed', 'create a reward-scaled SimpleBandit environment using the load function with custom reward_scale and seed', 'review the load function that wraps SimpleBandit with RewardScale and sets bsuite_num_episodes', 'summarize the bandit_scale module which provides a diagnostic independent arm bandit challenge with rescaled rewards', 'test the load function by passing reward_scale, seed, and mapping_seed arguments and verifying the returned environment', 'run the InterfaceTest class to validate the bandit_scale environment with absltest', 'test the make_action_sequence method that yields 100 random actions from range 11', 'review the make_object_under_test method that instantiates a bandit_scale environment via bandit_scale.load', 'summarize the InterfaceTest class that extends EnvironmentTestMixin and TestCase for bandit_scale validation']
```

Usage

```
{'score_bandit_scale_dataframe': 'score a pandas DataFrame from bandit_scale experiments and return a float metric', 'plot_learning_bandit_scale': 'plot learning curves for bandit_scale experiments using a pandas DataFrame', 'plot_average_bandit_scale': 'plot average performance across reward scales for bandit_scale experiments', 'plot_seeds_bandit_scale': 'plot performance by individual work unit with reward scale coloring', 'review_analysis_functions': 'review the bandit_scale analysis module score and plotting functions'}
```

## File: google-deepmind_bsuite/bsuite/experiments/bandit_scale/bandit_scale.py

Prompts

```
['score a pandas DataFrame from bandit_scale experiments and return a float metric', 'plot learning curves for bandit_scale experiments using a pandas DataFrame', 'plot average performance across reward scales for bandit_scale experiments', 'plot performance by individual work unit with reward scale coloring', 'review the bandit_scale analysis module score and plotting functions', 'run a bandit_scale experiment by calling load with a reward_scale, seed, and mapping_seed', 'create a reward-scaled SimpleBandit environment using the load function with custom reward_scale and seed', 'review the load function that wraps SimpleBandit with RewardScale and sets bsuite_num_episodes', 'summarize the bandit_scale module which provides a diagnostic independent arm bandit challenge with rescaled rewards', 'test the load function by passing reward_scale, seed, and mapping_seed arguments and verifying the returned environment', 'run the InterfaceTest class to validate the bandit_scale environment with absltest', 'test the make_action_sequence method that yields 100 random actions from range 11', 'review the make_object_under_test method that instantiates a bandit_scale environment via bandit_scale.load', 'summarize the InterfaceTest class that extends EnvironmentTestMixin and TestCase for bandit_scale validation']
```

Usage

```
{'run_bandit_scale_experiment': 'run a bandit_scale experiment by calling load with a reward_scale, seed, and mapping_seed', 'create_reward_scaled_bandit_env': 'create a reward-scaled SimpleBandit environment using the load function with custom reward_scale and seed', 'review_load_function': 'review the load function that wraps SimpleBandit with RewardScale and sets bsuite_num_episodes', 'summarize_bandit_scale_module': 'summarize the bandit_scale module which provides a diagnostic independent arm bandit challenge with rescaled rewards', 'test_bandit_scale_load': 'test the load function by passing reward_scale, seed, and mapping_seed arguments and verifying the returned environment'}
```

## File: google-deepmind_bsuite/bsuite/experiments/bandit_scale/bandit_scale_test.py

Prompts

```
['score a pandas DataFrame from bandit_scale experiments and return a float metric', 'plot learning curves for bandit_scale experiments using a pandas DataFrame', 'plot average performance across reward scales for bandit_scale experiments', 'plot performance by individual work unit with reward scale coloring', 'review the bandit_scale analysis module score and plotting functions', 'run a bandit_scale experiment by calling load with a reward_scale, seed, and mapping_seed', 'create a reward-scaled SimpleBandit environment using the load function with custom reward_scale and seed', 'review the load function that wraps SimpleBandit with RewardScale and sets bsuite_num_episodes', 'summarize the bandit_scale module which provides a diagnostic independent arm bandit challenge with rescaled rewards', 'test the load function by passing reward_scale, seed, and mapping_seed arguments and verifying the returned environment', 'run the InterfaceTest class to validate the bandit_scale environment with absltest', 'test the make_action_sequence method that yields 100 random actions from range 11', 'review the make_object_under_test method that instantiates a bandit_scale environment via bandit_scale.load', 'summarize the InterfaceTest class that extends EnvironmentTestMixin and TestCase for bandit_scale validation']
```

Usage

```
{'run_InterfaceTest': 'run the InterfaceTest class to validate the bandit_scale environment with absltest', 'test_bandit_scale_load': 'test the bandit_scale.load function by creating an environment with reward scale 10 and seed 42', 'test_make_action_sequence': 'test the make_action_sequence method that yields 100 random actions from range 11', 'review_InterfaceTest_make_object_under_test': 'review the make_object_under_test method that instantiates a bandit_scale environment via bandit_scale.load', 'summarize_InterfaceTest': 'summarize the InterfaceTest class that extends EnvironmentTestMixin and TestCase for bandit_scale validation'}
```

