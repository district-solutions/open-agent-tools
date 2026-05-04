# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/catch_scale/analysis.py

Prompts

```
['score a pandas DataFrame from catch scale experiments and return a float reward score', 'plot the learning curve of a catch scale experiment DataFrame using reward_scale as the scaling variable', 'plot the average performance across catch scale experiments using reward_scale as the sweep variable', 'plot performance by individual work unit for catch scale experiments colored by reward_scale', 'review the catch scale analysis module functions score plot_learning plot_average and plot_seeds', 'load a catch environment with scaled rewards using a given reward_scale and seed value', 'run a bsuite catch experiment with configurable reward scaling and episode count', 'create a reward-scaled catch environment wrapped with RewardScale using a specified seed', 'review the load function that wraps catch.Catch with RewardScale and sets episode count', 'summarize the catch_scale module that provides scaled reward environments for reinforcement learning experiments', 'test the catch_scale.load function with reward scale and seed parameters using absltest', 'test the catch_scale environment interface by feeding 100 random actions from valid set', 'review the InterfaceTest class that extends EnvironmentTestMixin and absltest.TestCase for catch_scale', 'run the absltest unit tests for the catch_scale experiment module with seed 22', 'summarize the catch_scale test file that validates environment loading and action sequences']
```

Usage

```
{'score_dataframe': 'score a pandas DataFrame from catch scale experiments and return a float reward score', 'plot_learning_curve': 'plot the learning curve of a catch scale experiment DataFrame using reward_scale as the scaling variable', 'plot_average_performance': 'plot the average performance across catch scale experiments using reward_scale as the sweep variable', 'plot_seeds_by_work_unit': 'plot performance by individual work unit for catch scale experiments colored by reward_scale', 'review_analysis_functions': 'review the catch scale analysis module functions score plot_learning plot_average and plot_seeds'}
```

## File: google-deepmind_bsuite/bsuite/experiments/catch_scale/catch_scale.py

Prompts

```
['score a pandas DataFrame from catch scale experiments and return a float reward score', 'plot the learning curve of a catch scale experiment DataFrame using reward_scale as the scaling variable', 'plot the average performance across catch scale experiments using reward_scale as the sweep variable', 'plot performance by individual work unit for catch scale experiments colored by reward_scale', 'review the catch scale analysis module functions score plot_learning plot_average and plot_seeds', 'load a catch environment with scaled rewards using a given reward_scale and seed value', 'run a bsuite catch experiment with configurable reward scaling and episode count', 'create a reward-scaled catch environment wrapped with RewardScale using a specified seed', 'review the load function that wraps catch.Catch with RewardScale and sets episode count', 'summarize the catch_scale module that provides scaled reward environments for reinforcement learning experiments', 'test the catch_scale.load function with reward scale and seed parameters using absltest', 'test the catch_scale environment interface by feeding 100 random actions from valid set', 'review the InterfaceTest class that extends EnvironmentTestMixin and absltest.TestCase for catch_scale', 'run the absltest unit tests for the catch_scale experiment module with seed 22', 'summarize the catch_scale test file that validates environment loading and action sequences']
```

Usage

```
{'load_catch_env_scaled_rewards': 'load a catch environment with scaled rewards using a given reward_scale and seed value', 'run_catch_experiment': 'run a bsuite catch experiment with configurable reward scaling and episode count', 'create_reward_scaled_env': 'create a reward-scaled catch environment wrapped with RewardScale using a specified seed', 'review_load_function': 'review the load function that wraps catch.Catch with RewardScale and sets episode count', 'summarize_catch_scale_module': 'summarize the catch_scale module that provides scaled reward environments for reinforcement learning experiments'}
```

## File: google-deepmind_bsuite/bsuite/experiments/catch_scale/catch_scale_test.py

Prompts

```
['score a pandas DataFrame from catch scale experiments and return a float reward score', 'plot the learning curve of a catch scale experiment DataFrame using reward_scale as the scaling variable', 'plot the average performance across catch scale experiments using reward_scale as the sweep variable', 'plot performance by individual work unit for catch scale experiments colored by reward_scale', 'review the catch scale analysis module functions score plot_learning plot_average and plot_seeds', 'load a catch environment with scaled rewards using a given reward_scale and seed value', 'run a bsuite catch experiment with configurable reward scaling and episode count', 'create a reward-scaled catch environment wrapped with RewardScale using a specified seed', 'review the load function that wraps catch.Catch with RewardScale and sets episode count', 'summarize the catch_scale module that provides scaled reward environments for reinforcement learning experiments', 'test the catch_scale.load function with reward scale and seed parameters using absltest', 'test the catch_scale environment interface by feeding 100 random actions from valid set', 'review the InterfaceTest class that extends EnvironmentTestMixin and absltest.TestCase for catch_scale', 'run the absltest unit tests for the catch_scale experiment module with seed 22', 'summarize the catch_scale test file that validates environment loading and action sequences']
```

Usage

```
{'test_catch_scale_load': 'test the catch_scale.load function with reward scale and seed parameters using absltest', 'test_interface_with_random_actions': 'test the catch_scale environment interface by feeding 100 random actions from valid set', 'review_interfacetest_class': 'review the InterfaceTest class that extends EnvironmentTestMixin and absltest.TestCase for catch_scale', 'run_catch_scale_unit_tests': 'run the absltest unit tests for the catch_scale experiment module with seed 22', 'summarize_catch_scale_test': 'summarize the catch_scale test file that validates environment loading and action sequences'}
```

