# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/cartpole_scale/analysis.py

Prompts

```
['score a pandas DataFrame from cartpole_scale experiments and return a float reward score', 'plot learning curves for cartpole_scale experiments using a pandas DataFrame and optional sweep variables', 'plot average performance across cartpole_scale experiments using a pandas DataFrame and optional sweep variables', 'plot performance by individual work unit for cartpole_scale experiments using a pandas DataFrame', 'review the cartpole_scale analysis module functions that delegate to cartpole_noise and cartpole analysis modules', 'load a cartpole environment with scaled rewards using a given reward_scale and seed', 'run a cartpole scale experiment by calling load with a reward_scale and seed value', 'review the load function that wraps cartpole with RewardScale and sets episode count', 'summarize the cartpole_scale module which provides scaled reward cartpole environments', 'test the load function with different reward_scale and seed combinations for reproducibility', 'test the cartpole_scale environment interface using EnvironmentTestMixin with reward scale 10 and seed 22', 'run the InterfaceTest class to validate cartpole environment with 100 random actions from valid set', 'create a cartpole environment with scaled rewards using cartpole_scale.load with reward_scale and seed parameters', 'generate a sequence of 100 random actions from valid actions 0 1 and 2 using numpy RandomState', 'review the InterfaceTest class that extends EnvironmentTestMixin and provides make_object_under_test and make_action_sequence methods']
```

Usage

```
{'score_cartpole_scale': 'score a pandas DataFrame from cartpole_scale experiments and return a float reward score', 'plot_learning_cartpole_scale': 'plot learning curves for cartpole_scale experiments using a pandas DataFrame and optional sweep variables', 'plot_average_cartpole_scale': 'plot average performance across cartpole_scale experiments using a pandas DataFrame and optional sweep variables', 'plot_seeds_cartpole_scale': 'plot performance by individual work unit for cartpole_scale experiments using a pandas DataFrame', 'review_analysis_module': 'review the cartpole_scale analysis module functions that delegate to cartpole_noise and cartpole analysis modules'}
```

## File: google-deepmind_bsuite/bsuite/experiments/cartpole_scale/cartpole_scale.py

Prompts

```
['score a pandas DataFrame from cartpole_scale experiments and return a float reward score', 'plot learning curves for cartpole_scale experiments using a pandas DataFrame and optional sweep variables', 'plot average performance across cartpole_scale experiments using a pandas DataFrame and optional sweep variables', 'plot performance by individual work unit for cartpole_scale experiments using a pandas DataFrame', 'review the cartpole_scale analysis module functions that delegate to cartpole_noise and cartpole analysis modules', 'load a cartpole environment with scaled rewards using a given reward_scale and seed', 'run a cartpole scale experiment by calling load with a reward_scale and seed value', 'review the load function that wraps cartpole with RewardScale and sets episode count', 'summarize the cartpole_scale module which provides scaled reward cartpole environments', 'test the load function with different reward_scale and seed combinations for reproducibility', 'test the cartpole_scale environment interface using EnvironmentTestMixin with reward scale 10 and seed 22', 'run the InterfaceTest class to validate cartpole environment with 100 random actions from valid set', 'create a cartpole environment with scaled rewards using cartpole_scale.load with reward_scale and seed parameters', 'generate a sequence of 100 random actions from valid actions 0 1 and 2 using numpy RandomState', 'review the InterfaceTest class that extends EnvironmentTestMixin and provides make_object_under_test and make_action_sequence methods']
```

Usage

```
{'load_cartpole_env': 'load a cartpole environment with scaled rewards using a given reward_scale and seed', 'run_cartpole_experiment': 'run a cartpole scale experiment by calling load with a reward_scale and seed value', 'review_load_function': 'review the load function that wraps cartpole with RewardScale and sets episode count', 'summarize_cartpole_scale': 'summarize the cartpole_scale module which provides scaled reward cartpole environments', 'test_load_with_seeds': 'test the load function with different reward_scale and seed combinations for reproducibility'}
```

## File: google-deepmind_bsuite/bsuite/experiments/cartpole_scale/cartpole_scale_test.py

Prompts

```
['score a pandas DataFrame from cartpole_scale experiments and return a float reward score', 'plot learning curves for cartpole_scale experiments using a pandas DataFrame and optional sweep variables', 'plot average performance across cartpole_scale experiments using a pandas DataFrame and optional sweep variables', 'plot performance by individual work unit for cartpole_scale experiments using a pandas DataFrame', 'review the cartpole_scale analysis module functions that delegate to cartpole_noise and cartpole analysis modules', 'load a cartpole environment with scaled rewards using a given reward_scale and seed', 'run a cartpole scale experiment by calling load with a reward_scale and seed value', 'review the load function that wraps cartpole with RewardScale and sets episode count', 'summarize the cartpole_scale module which provides scaled reward cartpole environments', 'test the load function with different reward_scale and seed combinations for reproducibility', 'test the cartpole_scale environment interface using EnvironmentTestMixin with reward scale 10 and seed 22', 'run the InterfaceTest class to validate cartpole environment with 100 random actions from valid set', 'create a cartpole environment with scaled rewards using cartpole_scale.load with reward_scale and seed parameters', 'generate a sequence of 100 random actions from valid actions 0 1 and 2 using numpy RandomState', 'review the InterfaceTest class that extends EnvironmentTestMixin and provides make_object_under_test and make_action_sequence methods']
```

Usage

```
{'test_cartpole_scale_interface': 'test the cartpole_scale environment interface using EnvironmentTestMixin with reward scale 10 and seed 22', 'run_interface_test': 'run the InterfaceTest class to validate cartpole environment with 100 random actions from valid set', 'create_cartpole_env': 'create a cartpole environment with scaled rewards using cartpole_scale.load with reward_scale and seed parameters', 'generate_action_sequence': 'generate a sequence of 100 random actions from valid actions 0 1 and 2 using numpy RandomState', 'review_interfacetest_class': 'review the InterfaceTest class that extends EnvironmentTestMixin and provides make_object_under_test and make_action_sequence methods'}
```

