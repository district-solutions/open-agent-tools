# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/cartpole_swingup/analysis.py

Prompts

```
['create a function that preprocesses cartpole swingup data by filtering episodes and computing perfection regret', 'build a scoring function that computes a combined regret and swingup score for cartpole swingup data', 'build a plot showing average return through time grouped by height threshold for cartpole swingup', 'build a scatter plot showing best episode observed by height threshold with color-coded swingup success', 'build a plot showing individual run returns through time colored by height threshold for cartpole swingup', 'create a CartpoleSwingup environment instance with custom height threshold and move cost parameters', 'run a cartpole swingup episode by calling reset then stepping with discrete actions', 'review the observation property that returns a normalized 8-dimensional state vector', 'test the action spec method that returns a discrete array with 3 action values', 'summarize the bsuite_info method that returns raw return, total upright, and best episode stats', 'test the CartpoleSwingup environment interface using dm_env test utilities with random actions', 'run the CartpoleSwingup unit tests with absltest using seed 42 and height threshold 0.8', 'create a CartpoleSwingup environment instance with a seed and height threshold parameter', 'review the InterfaceTest class that validates CartpoleSwingup environment behavior with 100 random actions', 'summarize the make_action_sequence method that yields 100 random discrete actions from values 0, 1, 2']
```

Usage

```
{'preprocess_cartpole_swingup_data': 'create a function that preprocesses cartpole swingup data by filtering episodes and computing perfection regret', 'score_cartpole_swingup_performance': 'build a scoring function that computes a combined regret and swingup score for cartpole swingup data', 'plot_cartpole_learning_curves': 'build a plot showing average return through time grouped by height threshold for cartpole swingup', 'plot_cartpole_scale_analysis': 'build a scatter plot showing best episode observed by height threshold with color-coded swingup success', 'plot_cartpole_seed_returns': 'build a plot showing individual run returns through time colored by height threshold for cartpole swingup'}
```

## File: google-deepmind_bsuite/bsuite/experiments/cartpole_swingup/cartpole_swingup.py

Prompts

```
['create a function that preprocesses cartpole swingup data by filtering episodes and computing perfection regret', 'build a scoring function that computes a combined regret and swingup score for cartpole swingup data', 'build a plot showing average return through time grouped by height threshold for cartpole swingup', 'build a scatter plot showing best episode observed by height threshold with color-coded swingup success', 'build a plot showing individual run returns through time colored by height threshold for cartpole swingup', 'create a CartpoleSwingup environment instance with custom height threshold and move cost parameters', 'run a cartpole swingup episode by calling reset then stepping with discrete actions', 'review the observation property that returns a normalized 8-dimensional state vector', 'test the action spec method that returns a discrete array with 3 action values', 'summarize the bsuite_info method that returns raw return, total upright, and best episode stats', 'test the CartpoleSwingup environment interface using dm_env test utilities with random actions', 'run the CartpoleSwingup unit tests with absltest using seed 42 and height threshold 0.8', 'create a CartpoleSwingup environment instance with a seed and height threshold parameter', 'review the InterfaceTest class that validates CartpoleSwingup environment behavior with 100 random actions', 'summarize the make_action_sequence method that yields 100 random discrete actions from values 0, 1, 2']
```

Usage

```
{'create_cartpole_swingup_env': 'create a CartpoleSwingup environment instance with custom height threshold and move cost parameters', 'run_cartpole_swingup_episode': 'run a cartpole swingup episode by calling reset then stepping with discrete actions', 'review_observation_property': 'review the observation property that returns a normalized 8-dimensional state vector', 'test_action_spec': 'test the action spec method that returns a discrete array with 3 action values', 'summarize_bsuite_info': 'summarize the bsuite_info method that returns raw return, total upright, and best episode stats'}
```

## File: google-deepmind_bsuite/bsuite/experiments/cartpole_swingup/cartpole_swingup_test.py

Prompts

```
['create a function that preprocesses cartpole swingup data by filtering episodes and computing perfection regret', 'build a scoring function that computes a combined regret and swingup score for cartpole swingup data', 'build a plot showing average return through time grouped by height threshold for cartpole swingup', 'build a scatter plot showing best episode observed by height threshold with color-coded swingup success', 'build a plot showing individual run returns through time colored by height threshold for cartpole swingup', 'create a CartpoleSwingup environment instance with custom height threshold and move cost parameters', 'run a cartpole swingup episode by calling reset then stepping with discrete actions', 'review the observation property that returns a normalized 8-dimensional state vector', 'test the action spec method that returns a discrete array with 3 action values', 'summarize the bsuite_info method that returns raw return, total upright, and best episode stats', 'test the CartpoleSwingup environment interface using dm_env test utilities with random actions', 'run the CartpoleSwingup unit tests with absltest using seed 42 and height threshold 0.8', 'create a CartpoleSwingup environment instance with a seed and height threshold parameter', 'review the InterfaceTest class that validates CartpoleSwingup environment behavior with 100 random actions', 'summarize the make_action_sequence method that yields 100 random discrete actions from values 0, 1, 2']
```

Usage

```
{'test_CartpoleSwingup_interface': 'test the CartpoleSwingup environment interface using dm_env test utilities with random actions', 'run_CartpoleSwingup_tests': 'run the CartpoleSwingup unit tests with absltest using seed 42 and height threshold 0.8', 'create_CartpoleSwingup_instance': 'create a CartpoleSwingup environment instance with a seed and height threshold parameter', 'review_InterfaceTest_class': 'review the InterfaceTest class that validates CartpoleSwingup environment behavior with 100 random actions', 'summarize_make_action_sequence': 'summarize the make_action_sequence method that yields 100 random discrete actions from values 0, 1, 2'}
```

