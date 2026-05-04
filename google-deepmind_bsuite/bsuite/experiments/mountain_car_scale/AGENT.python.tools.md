# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/mountain_car_scale/analysis.py

Prompts

```
['score a pandas DataFrame from the mountain_car_scale experiment using reward scaling', 'plot learning curves for the mountain_car_scale experiment with optional sweep variables', 'plot average performance for the mountain_car_scale experiment across reward scales', 'plot performance by individual work unit for the mountain_car_scale experiment', 'review the mountain_car_scale analysis module and its delegation to noise and base analysis', 'load a MountainCar RL environment with a custom reward scale and random seed', 'run the MountainCar scale experiment by calling load with a reward scale and seed', 'review the load function that wraps MountainCar with RewardScale and sets episode count', 'summarize the mountain_car_scale module which configures a scaled MountainCar RL environment', 'test the load function by passing different reward scale values and seed integers', 'test the mountain_car_scale environment interface using absltest with reward scale 10 and seed 22', 'test creating a mountain_car environment via mountain_car_scale.load with reward scale and seed parameters', 'test generating 100 random actions from valid action space [0, 1, 2] using numpy RandomState', 'review the InterfaceTest class that extends EnvironmentTestMixin and TestCase for mountain car scale', 'run the absltest suite for mountain_car_scale experiment with 100 random action steps']
```

Usage

```
{'score_mountain_car_scale': 'score a pandas DataFrame from the mountain_car_scale experiment using reward scaling', 'plot_learning_mountain_car_scale': 'plot learning curves for the mountain_car_scale experiment with optional sweep variables', 'plot_average_mountain_car_scale': 'plot average performance for the mountain_car_scale experiment across reward scales', 'plot_seeds_mountain_car_scale': 'plot performance by individual work unit for the mountain_car_scale experiment', 'review_analysis_module': 'review the mountain_car_scale analysis module and its delegation to noise and base analysis'}
```

## File: google-deepmind_bsuite/bsuite/experiments/mountain_car_scale/mountain_car_scale.py

Prompts

```
['score a pandas DataFrame from the mountain_car_scale experiment using reward scaling', 'plot learning curves for the mountain_car_scale experiment with optional sweep variables', 'plot average performance for the mountain_car_scale experiment across reward scales', 'plot performance by individual work unit for the mountain_car_scale experiment', 'review the mountain_car_scale analysis module and its delegation to noise and base analysis', 'load a MountainCar RL environment with a custom reward scale and random seed', 'run the MountainCar scale experiment by calling load with a reward scale and seed', 'review the load function that wraps MountainCar with RewardScale and sets episode count', 'summarize the mountain_car_scale module which configures a scaled MountainCar RL environment', 'test the load function by passing different reward scale values and seed integers', 'test the mountain_car_scale environment interface using absltest with reward scale 10 and seed 22', 'test creating a mountain_car environment via mountain_car_scale.load with reward scale and seed parameters', 'test generating 100 random actions from valid action space [0, 1, 2] using numpy RandomState', 'review the InterfaceTest class that extends EnvironmentTestMixin and TestCase for mountain car scale', 'run the absltest suite for mountain_car_scale experiment with 100 random action steps']
```

Usage

```
{'load_mountain_car_env': 'load a MountainCar RL environment with a custom reward scale and random seed', 'run_mountain_car_experiment': 'run the MountainCar scale experiment by calling load with a reward scale and seed', 'review_load_function': 'review the load function that wraps MountainCar with RewardScale and sets episode count', 'summarize_mountain_car_scale': 'summarize the mountain_car_scale module which configures a scaled MountainCar RL environment', 'test_load_with_parameters': 'test the load function by passing different reward scale values and seed integers'}
```

## File: google-deepmind_bsuite/bsuite/experiments/mountain_car_scale/mountain_car_scale_test.py

Prompts

```
['score a pandas DataFrame from the mountain_car_scale experiment using reward scaling', 'plot learning curves for the mountain_car_scale experiment with optional sweep variables', 'plot average performance for the mountain_car_scale experiment across reward scales', 'plot performance by individual work unit for the mountain_car_scale experiment', 'review the mountain_car_scale analysis module and its delegation to noise and base analysis', 'load a MountainCar RL environment with a custom reward scale and random seed', 'run the MountainCar scale experiment by calling load with a reward scale and seed', 'review the load function that wraps MountainCar with RewardScale and sets episode count', 'summarize the mountain_car_scale module which configures a scaled MountainCar RL environment', 'test the load function by passing different reward scale values and seed integers', 'test the mountain_car_scale environment interface using absltest with reward scale 10 and seed 22', 'test creating a mountain_car environment via mountain_car_scale.load with reward scale and seed parameters', 'test generating 100 random actions from valid action space [0, 1, 2] using numpy RandomState', 'review the InterfaceTest class that extends EnvironmentTestMixin and TestCase for mountain car scale', 'run the absltest suite for mountain_car_scale experiment with 100 random action steps']
```

Usage

```
{'test_mountain_car_scale_interface': 'test the mountain_car_scale environment interface using absltest with reward scale 10 and seed 22', 'test_make_object_under_test': 'test creating a mountain_car environment via mountain_car_scale.load with reward scale and seed parameters', 'test_make_action_sequence': 'test generating 100 random actions from valid action space [0, 1, 2] using numpy RandomState', 'review_interfacetest_class': 'review the InterfaceTest class that extends EnvironmentTestMixin and TestCase for mountain car scale', 'run_mountain_car_scale_tests': 'run the absltest suite for mountain_car_scale experiment with 100 random action steps'}
```

