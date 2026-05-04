# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/mnist_scale/analysis.py

Prompts

```
['score a pandas DataFrame from an MNIST scale experiment and return a float score', 'plot the learning curve of an MNIST scale experiment from a pandas DataFrame', 'plot the average performance across runs for an MNIST scale experiment', 'plot the performance by individual work unit for an MNIST scale experiment', 'summarize the MNIST scale analysis module functions for scoring and plotting experiment results', 'load an MNIST bandit environment with a given reward scale and random seed', 'run the MNIST scale experiment by calling load with reward_scale and seed parameters', 'review the load function that wraps MNISTBandit with RewardScale wrapper', 'summarize the MNIST bandit reward scaling experiment setup and dependencies', 'test the load function with different reward scales and seed values', 'test the InterfaceTest class that validates the MNIST scale environment using dm_env test utilities', 'run make_object_under_test to create an MNIST bandit environment with reward scale 2.0 and seed 101', 'run make_action_sequence to generate 100 random actions for the MNIST bandit environment', 'review the InterfaceTest class inheriting EnvironmentTestMixin and absltest.TestCase for MNIST scale environment testing', 'summarize the mnist_scale_test module that tests the MNIST bandit environment with configurable reward scaling']
```

Usage

```
{'score_dataframe': 'score a pandas DataFrame from an MNIST scale experiment and return a float score', 'plot_learning_curve': 'plot the learning curve of an MNIST scale experiment from a pandas DataFrame', 'plot_average_performance': 'plot the average performance across runs for an MNIST scale experiment', 'plot_seeds_performance': 'plot the performance by individual work unit for an MNIST scale experiment', 'summarize_analysis_module': 'summarize the MNIST scale analysis module functions for scoring and plotting experiment results'}
```

## File: google-deepmind_bsuite/bsuite/experiments/mnist_scale/mnist_scale.py

Prompts

```
['score a pandas DataFrame from an MNIST scale experiment and return a float score', 'plot the learning curve of an MNIST scale experiment from a pandas DataFrame', 'plot the average performance across runs for an MNIST scale experiment', 'plot the performance by individual work unit for an MNIST scale experiment', 'summarize the MNIST scale analysis module functions for scoring and plotting experiment results', 'load an MNIST bandit environment with a given reward scale and random seed', 'run the MNIST scale experiment by calling load with reward_scale and seed parameters', 'review the load function that wraps MNISTBandit with RewardScale wrapper', 'summarize the MNIST bandit reward scaling experiment setup and dependencies', 'test the load function with different reward scales and seed values', 'test the InterfaceTest class that validates the MNIST scale environment using dm_env test utilities', 'run make_object_under_test to create an MNIST bandit environment with reward scale 2.0 and seed 101', 'run make_action_sequence to generate 100 random actions for the MNIST bandit environment', 'review the InterfaceTest class inheriting EnvironmentTestMixin and absltest.TestCase for MNIST scale environment testing', 'summarize the mnist_scale_test module that tests the MNIST bandit environment with configurable reward scaling']
```

Usage

```
{'load_mnist_bandit_env': 'load an MNIST bandit environment with a given reward scale and random seed', 'run_mnist_scale_experiment': 'run the MNIST scale experiment by calling load with reward_scale and seed parameters', 'review_load_function': 'review the load function that wraps MNISTBandit with RewardScale wrapper', 'summarize_mnist_scale': 'summarize the MNIST bandit reward scaling experiment setup and dependencies', 'test_load_with_seeds': 'test the load function with different reward scales and seed values'}
```

## File: google-deepmind_bsuite/bsuite/experiments/mnist_scale/mnist_scale_test.py

Prompts

```
['score a pandas DataFrame from an MNIST scale experiment and return a float score', 'plot the learning curve of an MNIST scale experiment from a pandas DataFrame', 'plot the average performance across runs for an MNIST scale experiment', 'plot the performance by individual work unit for an MNIST scale experiment', 'summarize the MNIST scale analysis module functions for scoring and plotting experiment results', 'load an MNIST bandit environment with a given reward scale and random seed', 'run the MNIST scale experiment by calling load with reward_scale and seed parameters', 'review the load function that wraps MNISTBandit with RewardScale wrapper', 'summarize the MNIST bandit reward scaling experiment setup and dependencies', 'test the load function with different reward scales and seed values', 'test the InterfaceTest class that validates the MNIST scale environment using dm_env test utilities', 'run make_object_under_test to create an MNIST bandit environment with reward scale 2.0 and seed 101', 'run make_action_sequence to generate 100 random actions for the MNIST bandit environment', 'review the InterfaceTest class inheriting EnvironmentTestMixin and absltest.TestCase for MNIST scale environment testing', 'summarize the mnist_scale_test module that tests the MNIST bandit environment with configurable reward scaling']
```

Usage

```
{'test_InterfaceTest': 'test the InterfaceTest class that validates the MNIST scale environment using dm_env test utilities', 'run_InterfaceTest_make_object_under_test': 'run make_object_under_test to create an MNIST bandit environment with reward scale 2.0 and seed 101', 'run_InterfaceTest_make_action_sequence': 'run make_action_sequence to generate 100 random actions for the MNIST bandit environment', 'review_InterfaceTest': 'review the InterfaceTest class inheriting EnvironmentTestMixin and absltest.TestCase for MNIST scale environment testing', 'summarize_mnist_scale_test': 'summarize the mnist_scale_test module that tests the MNIST bandit environment with configurable reward scaling'}
```

