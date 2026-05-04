# Agent Python Tools

- repo: facebookresearch/benchmarl
- repo_uri: https://github.com/facebookresearch/benchmarl

## File: facebookresearch_benchmarl/examples/extending/algorithm/algorithms/customalgorithm.py

Prompts

```
['build a custom DQN algorithm extending Algorithm with delay value and custom loss function parameters', 'create a CustomAlgorithmConfig dataclass with delay value, loss function, and custom arg fields', 'implement the _get_loss method to return a DQNLoss module with TD0 value estimator', 'implement the _get_policy_for_loss method to chain an actor module with a QValueModule', 'implement the process_batch method to expand shared done, terminated, and reward tensors for multi-agent groups']
```

Usage

```
{'build_custom_algorithm': 'build a custom DQN algorithm extending Algorithm with delay value and custom loss function parameters', 'create_custom_algorithm_config': 'create a CustomAlgorithmConfig dataclass with delay value, loss function, and custom arg fields', 'implement_get_loss': 'implement the _get_loss method to return a DQNLoss module with TD0 value estimator', 'implement_get_policy_for_loss': 'implement the _get_policy_for_loss method to chain an actor module with a QValueModule', 'implement_process_batch': 'implement the process_batch method to expand shared done, terminated, and reward tensors for multi-agent groups'}
```

