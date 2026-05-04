# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/catch_noise/analysis.py

Prompts

```
['compute a single score for the catch noise experiment using mean minus std over noise_scale', 'plot the average regret through time for the catch noise experiment grouped by noise_scale', 'plot the average regret at the final episode for the catch noise experiment grouped by noise_scale', 'plot performance by individual work unit for the catch noise experiment colored by noise_scale', 'review the catch noise analysis module functions for scoring and plotting regret across noise scales', 'load a catch environment with noisy rewards using a given noise scale and seed', 'run the catch noise experiment by calling load with a noise scale and seed value', 'review the load function that wraps catch.Catch with RewardNoise and sets episode count', 'summarize the catch noise module that creates a noisy reward environment for reinforcement learning', 'test the load function by passing different noise scale and seed values to verify environment creation', 'test the InterfaceTest class that validates the catch_noise environment using absltest and dm_env test utilities', 'run the make_object_under_test method to create a catch_noise environment with noise scale 1.0 and seed 22', 'run the make_action_sequence method to generate 100 random actions from valid actions 0, 1, and 2', 'review the InterfaceTest class inheriting from EnvironmentTestMixin and TestCase for catch_noise experiment validation', 'summarize the catch_noise test module that tests the catch environment with noisy rewards using absltest']
```

Usage

```
{'score_catch_noise_experiment': 'compute a single score for the catch noise experiment using mean minus std over noise_scale', 'plot_learning_catch_noise': 'plot the average regret through time for the catch noise experiment grouped by noise_scale', 'plot_average_catch_noise': 'plot the average regret at the final episode for the catch noise experiment grouped by noise_scale', 'plot_seeds_catch_noise': 'plot performance by individual work unit for the catch noise experiment colored by noise_scale', 'review_analysis_module': 'review the catch noise analysis module functions for scoring and plotting regret across noise scales'}
```

## File: google-deepmind_bsuite/bsuite/experiments/catch_noise/catch_noise.py

Prompts

```
['compute a single score for the catch noise experiment using mean minus std over noise_scale', 'plot the average regret through time for the catch noise experiment grouped by noise_scale', 'plot the average regret at the final episode for the catch noise experiment grouped by noise_scale', 'plot performance by individual work unit for the catch noise experiment colored by noise_scale', 'review the catch noise analysis module functions for scoring and plotting regret across noise scales', 'load a catch environment with noisy rewards using a given noise scale and seed', 'run the catch noise experiment by calling load with a noise scale and seed value', 'review the load function that wraps catch.Catch with RewardNoise and sets episode count', 'summarize the catch noise module that creates a noisy reward environment for reinforcement learning', 'test the load function by passing different noise scale and seed values to verify environment creation', 'test the InterfaceTest class that validates the catch_noise environment using absltest and dm_env test utilities', 'run the make_object_under_test method to create a catch_noise environment with noise scale 1.0 and seed 22', 'run the make_action_sequence method to generate 100 random actions from valid actions 0, 1, and 2', 'review the InterfaceTest class inheriting from EnvironmentTestMixin and TestCase for catch_noise experiment validation', 'summarize the catch_noise test module that tests the catch environment with noisy rewards using absltest']
```

Usage

```
{'load_catch_noise_env': 'load a catch environment with noisy rewards using a given noise scale and seed', 'run_catch_noise_experiment': 'run the catch noise experiment by calling load with a noise scale and seed value', 'review_load_function': 'review the load function that wraps catch.Catch with RewardNoise and sets episode count', 'summarize_catch_noise_module': 'summarize the catch noise module that creates a noisy reward environment for reinforcement learning', 'test_load_with_parameters': 'test the load function by passing different noise scale and seed values to verify environment creation'}
```

## File: google-deepmind_bsuite/bsuite/experiments/catch_noise/catch_noise_test.py

Prompts

```
['compute a single score for the catch noise experiment using mean minus std over noise_scale', 'plot the average regret through time for the catch noise experiment grouped by noise_scale', 'plot the average regret at the final episode for the catch noise experiment grouped by noise_scale', 'plot performance by individual work unit for the catch noise experiment colored by noise_scale', 'review the catch noise analysis module functions for scoring and plotting regret across noise scales', 'load a catch environment with noisy rewards using a given noise scale and seed', 'run the catch noise experiment by calling load with a noise scale and seed value', 'review the load function that wraps catch.Catch with RewardNoise and sets episode count', 'summarize the catch noise module that creates a noisy reward environment for reinforcement learning', 'test the load function by passing different noise scale and seed values to verify environment creation', 'test the InterfaceTest class that validates the catch_noise environment using absltest and dm_env test utilities', 'run the make_object_under_test method to create a catch_noise environment with noise scale 1.0 and seed 22', 'run the make_action_sequence method to generate 100 random actions from valid actions 0, 1, and 2', 'review the InterfaceTest class inheriting from EnvironmentTestMixin and TestCase for catch_noise experiment validation', 'summarize the catch_noise test module that tests the catch environment with noisy rewards using absltest']
```

Usage

```
{'test_InterfaceTest': 'test the InterfaceTest class that validates the catch_noise environment using absltest and dm_env test utilities', 'run_InterfaceTest_make_object_under_test': 'run the make_object_under_test method to create a catch_noise environment with noise scale 1.0 and seed 22', 'run_InterfaceTest_make_action_sequence': 'run the make_action_sequence method to generate 100 random actions from valid actions 0, 1, and 2', 'review_InterfaceTest': 'review the InterfaceTest class inheriting from EnvironmentTestMixin and TestCase for catch_noise experiment validation', 'summarize_catch_noise_test': 'summarize the catch_noise test module that tests the catch environment with noisy rewards using absltest'}
```

