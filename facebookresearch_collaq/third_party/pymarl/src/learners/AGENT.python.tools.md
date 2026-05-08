# Agent Python Tools

- repo: facebookresearch/collaq
- repo_uri: https://github.com/facebookresearch/collaq

## File: facebookresearch_collaq/third_party/pymarl/src/learners/coma_learner.py

Prompts

```
['create a COMALearner instance with mac, scheme, logger, and args for counterfactual multi-agent RL training', 'train the COMALearner on an EpisodeBatch by updating both the critic network and agent policy networks', 'review the _train_critic method that computes TD-lambda targets and performs backpropagation on the critic network', 'save the COMALearner mac models, critic state dict, and optimizer states to a directory path', 'load the COMALearner mac models, critic state dict, and optimizer states from a directory path', 'create a QLearner instance with a MAC, scheme, logger, and args for multi-agent Q-learning', 'train the QLearner on an EpisodeBatch to compute TD-error and update agent and mixer weights', 'update the target MAC and target mixer networks by copying weights from the live networks', 'save the MAC models, mixer state dict, and optimiser state to a given file path', 'load the MAC models, mixer state dict, and optimiser state from a given file path']
```

Usage

```
{'create_COMALearner': 'create a COMALearner instance with mac, scheme, logger, and args for counterfactual multi-agent RL training', 'train_COMALearner': 'train the COMALearner on an EpisodeBatch by updating both the critic network and agent policy networks', 'review_train_critic': 'review the _train_critic method that computes TD-lambda targets and performs backpropagation on the critic network', 'save_models_COMALearner': 'save the COMALearner mac models, critic state dict, and optimizer states to a directory path', 'load_models_COMALearner': 'load the COMALearner mac models, critic state dict, and optimizer states from a directory path'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/learners/q_learner.py

Prompts

```
['create a COMALearner instance with mac, scheme, logger, and args for counterfactual multi-agent RL training', 'train the COMALearner on an EpisodeBatch by updating both the critic network and agent policy networks', 'review the _train_critic method that computes TD-lambda targets and performs backpropagation on the critic network', 'save the COMALearner mac models, critic state dict, and optimizer states to a directory path', 'load the COMALearner mac models, critic state dict, and optimizer states from a directory path', 'create a QLearner instance with a MAC, scheme, logger, and args for multi-agent Q-learning', 'train the QLearner on an EpisodeBatch to compute TD-error and update agent and mixer weights', 'update the target MAC and target mixer networks by copying weights from the live networks', 'save the MAC models, mixer state dict, and optimiser state to a given file path', 'load the MAC models, mixer state dict, and optimiser state from a given file path']
```

Usage

```
{'create_QLearner': 'create a QLearner instance with a MAC, scheme, logger, and args for multi-agent Q-learning', 'train_QLearner': 'train the QLearner on an EpisodeBatch to compute TD-error and update agent and mixer weights', 'update_targets_QLearner': 'update the target MAC and target mixer networks by copying weights from the live networks', 'save_models_QLearner': 'save the MAC models, mixer state dict, and optimiser state to a given file path', 'load_models_QLearner': 'load the MAC models, mixer state dict, and optimiser state from a given file path'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/learners/qtran_learner.py

Prompts

```
['create a COMALearner instance with mac, scheme, logger, and args for counterfactual multi-agent RL training', 'train the COMALearner on an EpisodeBatch by updating both the critic network and agent policy networks', 'review the _train_critic method that computes TD-lambda targets and performs backpropagation on the critic network', 'save the COMALearner mac models, critic state dict, and optimizer states to a directory path', 'load the COMALearner mac models, critic state dict, and optimizer states from a directory path', 'create a QLearner instance with a MAC, scheme, logger, and args for multi-agent Q-learning', 'train the QLearner on an EpisodeBatch to compute TD-error and update agent and mixer weights', 'update the target MAC and target mixer networks by copying weights from the live networks', 'save the MAC models, mixer state dict, and optimiser state to a given file path', 'load the MAC models, mixer state dict, and optimiser state from a given file path']
```

Usage

```
{'create_QLearner': 'create a QLearner instance with a MAC, scheme, logger, and args for QTRAN multi-agent reinforcement learning', 'train_QLearner': 'train the QLearner on an EpisodeBatch computing TD, optimal, and non-optimal loss for QTRAN base mixing', 'update_targets_QLearner': 'update the target MAC and target mixer networks by copying weights from the online networks', 'save_models_QLearner': 'save the MAC models, mixer state dict, and optimizer state to a given file path', 'load_models_QLearner': 'load the MAC models, mixer state dict, and optimizer state from a given file path'}
```

