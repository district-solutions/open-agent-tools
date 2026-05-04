# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/mnist_noise/analysis.py

Prompts

```
['compute a single score for the mnist_noise experiment using mean minus std over noise_scale', 'plot the average regret through time for the mnist_noise experiment grouped by noise_scale', 'plot the average regret at the final episode for the mnist_noise experiment grouped by noise_scale', 'plot the performance by individual work unit for the mnist_noise experiment colored by noise_scale', 'review the mnist_noise analysis module and its score and plotting functions for correctness', 'load an MNIST bandit environment with configurable reward noise scale and random seed', 'run the MNIST noise experiment by calling load with a noise scale and seed', 'review the load function that wraps MNISTBandit with RewardNoise and sets episode count', 'summarize the MNIST noise experiment which tests generalization under noisy rewards', 'test the load function by creating an environment with different noise scales and seeds', 'test the InterfaceTest class that validates the MNIST noise environment using absltest and dm_env test utilities', 'run make_object_under_test to create an MNIST noise environment with noise_scale 2.0 and seed 101', 'review make_action_sequence which yields 100 random actions sampled from the environment action spec', 'summarize the mnist_noise load function that wraps MNISTBandit with reward noise using the given noise scale and seed', 'refactor the InterfaceTest class to adjust the noise scale or action sequence length for different test scenarios']
```

Usage

```
{'score_mnist_noise': 'compute a single score for the mnist_noise experiment using mean minus std over noise_scale', 'plot_learning_mnist_noise': 'plot the average regret through time for the mnist_noise experiment grouped by noise_scale', 'plot_average_mnist_noise': 'plot the average regret at the final episode for the mnist_noise experiment grouped by noise_scale', 'plot_seeds_mnist_noise': 'plot the performance by individual work unit for the mnist_noise experiment colored by noise_scale', 'review_analysis_mnist_noise': 'review the mnist_noise analysis module and its score and plotting functions for correctness'}
```

## File: google-deepmind_bsuite/bsuite/experiments/mnist_noise/mnist_noise.py

Prompts

```
['compute a single score for the mnist_noise experiment using mean minus std over noise_scale', 'plot the average regret through time for the mnist_noise experiment grouped by noise_scale', 'plot the average regret at the final episode for the mnist_noise experiment grouped by noise_scale', 'plot the performance by individual work unit for the mnist_noise experiment colored by noise_scale', 'review the mnist_noise analysis module and its score and plotting functions for correctness', 'load an MNIST bandit environment with configurable reward noise scale and random seed', 'run the MNIST noise experiment by calling load with a noise scale and seed', 'review the load function that wraps MNISTBandit with RewardNoise and sets episode count', 'summarize the MNIST noise experiment which tests generalization under noisy rewards', 'test the load function by creating an environment with different noise scales and seeds', 'test the InterfaceTest class that validates the MNIST noise environment using absltest and dm_env test utilities', 'run make_object_under_test to create an MNIST noise environment with noise_scale 2.0 and seed 101', 'review make_action_sequence which yields 100 random actions sampled from the environment action spec', 'summarize the mnist_noise load function that wraps MNISTBandit with reward noise using the given noise scale and seed', 'refactor the InterfaceTest class to adjust the noise scale or action sequence length for different test scenarios']
```

Usage

```
{'load_mnist_noise_env': 'load an MNIST bandit environment with configurable reward noise scale and random seed', 'run_mnist_noise_experiment': 'run the MNIST noise experiment by calling load with a noise scale and seed', 'review_load_function': 'review the load function that wraps MNISTBandit with RewardNoise and sets episode count', 'summarize_mnist_noise': 'summarize the MNIST noise experiment which tests generalization under noisy rewards', 'test_mnist_noise_load': 'test the load function by creating an environment with different noise scales and seeds'}
```

## File: google-deepmind_bsuite/bsuite/experiments/mnist_noise/mnist_noise_test.py

Prompts

```
['compute a single score for the mnist_noise experiment using mean minus std over noise_scale', 'plot the average regret through time for the mnist_noise experiment grouped by noise_scale', 'plot the average regret at the final episode for the mnist_noise experiment grouped by noise_scale', 'plot the performance by individual work unit for the mnist_noise experiment colored by noise_scale', 'review the mnist_noise analysis module and its score and plotting functions for correctness', 'load an MNIST bandit environment with configurable reward noise scale and random seed', 'run the MNIST noise experiment by calling load with a noise scale and seed', 'review the load function that wraps MNISTBandit with RewardNoise and sets episode count', 'summarize the MNIST noise experiment which tests generalization under noisy rewards', 'test the load function by creating an environment with different noise scales and seeds', 'test the InterfaceTest class that validates the MNIST noise environment using absltest and dm_env test utilities', 'run make_object_under_test to create an MNIST noise environment with noise_scale 2.0 and seed 101', 'review make_action_sequence which yields 100 random actions sampled from the environment action spec', 'summarize the mnist_noise load function that wraps MNISTBandit with reward noise using the given noise scale and seed', 'refactor the InterfaceTest class to adjust the noise scale or action sequence length for different test scenarios']
```

Usage

```
{'test_InterfaceTest': 'test the InterfaceTest class that validates the MNIST noise environment using absltest and dm_env test utilities', 'run_InterfaceTest_make_object_under_test': 'run make_object_under_test to create an MNIST noise environment with noise_scale 2.0 and seed 101', 'review_InterfaceTest_make_action_sequence': 'review make_action_sequence which yields 100 random actions sampled from the environment action spec', 'summarize_mnist_noise_load': 'summarize the mnist_noise load function that wraps MNISTBandit with reward noise using the given noise scale and seed', 'refactor_InterfaceTest': 'refactor the InterfaceTest class to adjust the noise scale or action sequence length for different test scenarios'}
```

