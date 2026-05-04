# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/bandit_noise/analysis.py

Prompts

```
['compute a single score for bandit noise experiment using mean minus std over noise scale', 'plot the average regret through time for bandit noise experiments grouped by noise scale', 'plot the average regret by noise scale with a baseline regret dashed line', 'plot performance by individual work unit colored by noise scale for bandit noise experiments', 'review the bandit noise analysis module functions for scoring and plotting regret metrics', 'run a bandit_noise experiment with configurable noise scale and seed using the load function', 'create a SimpleBandit environment wrapped with RewardNoise for testing exploration under noisy rewards', 'review the load function that wraps SimpleBandit with RewardNoise and sets episode count', 'summarize the bandit_noise module which provides a diagnostic independent arm bandit problem with reward noise', 'test the load function with a custom num_actions parameter to change the number of bandit arms', 'test the bandit_noise environment interface using EnvironmentTestMixin with random action sequences', 'run the bandit_noise unit test suite with absltest using seed 42 and noise scale 1.0', 'review the InterfaceTest class that validates bandit_noise environment with 11 valid actions', 'test the make_action_sequence method that yields 100 random actions from range 11', 'review the bandit_noise load function called with noise scale, seed, and mapping seed parameters']
```

Usage

```
{'score_bandit_noise': 'compute a single score for bandit noise experiment using mean minus std over noise scale', 'plot_learning_bandit_noise': 'plot the average regret through time for bandit noise experiments grouped by noise scale', 'plot_average_bandit_noise': 'plot the average regret by noise scale with a baseline regret dashed line', 'plot_seeds_bandit_noise': 'plot performance by individual work unit colored by noise scale for bandit noise experiments', 'review_analysis_module': 'review the bandit noise analysis module functions for scoring and plotting regret metrics'}
```

## File: google-deepmind_bsuite/bsuite/experiments/bandit_noise/bandit_noise.py

Prompts

```
['compute a single score for bandit noise experiment using mean minus std over noise scale', 'plot the average regret through time for bandit noise experiments grouped by noise scale', 'plot the average regret by noise scale with a baseline regret dashed line', 'plot performance by individual work unit colored by noise scale for bandit noise experiments', 'review the bandit noise analysis module functions for scoring and plotting regret metrics', 'run a bandit_noise experiment with configurable noise scale and seed using the load function', 'create a SimpleBandit environment wrapped with RewardNoise for testing exploration under noisy rewards', 'review the load function that wraps SimpleBandit with RewardNoise and sets episode count', 'summarize the bandit_noise module which provides a diagnostic independent arm bandit problem with reward noise', 'test the load function with a custom num_actions parameter to change the number of bandit arms', 'test the bandit_noise environment interface using EnvironmentTestMixin with random action sequences', 'run the bandit_noise unit test suite with absltest using seed 42 and noise scale 1.0', 'review the InterfaceTest class that validates bandit_noise environment with 11 valid actions', 'test the make_action_sequence method that yields 100 random actions from range 11', 'review the bandit_noise load function called with noise scale, seed, and mapping seed parameters']
```

Usage

```
{'run_bandit_noise_experiment': 'run a bandit_noise experiment with configurable noise scale and seed using the load function', 'create_noisy_bandit_env': 'create a SimpleBandit environment wrapped with RewardNoise for testing exploration under noisy rewards', 'review_load_function': 'review the load function that wraps SimpleBandit with RewardNoise and sets episode count', 'summarize_bandit_noise_module': 'summarize the bandit_noise module which provides a diagnostic independent arm bandit problem with reward noise', 'test_bandit_noise_with_custom_actions': 'test the load function with a custom num_actions parameter to change the number of bandit arms'}
```

## File: google-deepmind_bsuite/bsuite/experiments/bandit_noise/bandit_noise_test.py

Prompts

```
['compute a single score for bandit noise experiment using mean minus std over noise scale', 'plot the average regret through time for bandit noise experiments grouped by noise scale', 'plot the average regret by noise scale with a baseline regret dashed line', 'plot performance by individual work unit colored by noise scale for bandit noise experiments', 'review the bandit noise analysis module functions for scoring and plotting regret metrics', 'run a bandit_noise experiment with configurable noise scale and seed using the load function', 'create a SimpleBandit environment wrapped with RewardNoise for testing exploration under noisy rewards', 'review the load function that wraps SimpleBandit with RewardNoise and sets episode count', 'summarize the bandit_noise module which provides a diagnostic independent arm bandit problem with reward noise', 'test the load function with a custom num_actions parameter to change the number of bandit arms', 'test the bandit_noise environment interface using EnvironmentTestMixin with random action sequences', 'run the bandit_noise unit test suite with absltest using seed 42 and noise scale 1.0', 'review the InterfaceTest class that validates bandit_noise environment with 11 valid actions', 'test the make_action_sequence method that yields 100 random actions from range 11', 'review the bandit_noise load function called with noise scale, seed, and mapping seed parameters']
```

Usage

```
{'test_bandit_noise_interface': 'test the bandit_noise environment interface using EnvironmentTestMixin with random action sequences', 'run_bandit_noise_test': 'run the bandit_noise unit test suite with absltest using seed 42 and noise scale 1.0', 'review_interfacetest_class': 'review the InterfaceTest class that validates bandit_noise environment with 11 valid actions', 'test_make_action_sequence': 'test the make_action_sequence method that yields 100 random actions from range 11', 'review_bandit_noise_load': 'review the bandit_noise load function called with noise scale, seed, and mapping seed parameters'}
```

