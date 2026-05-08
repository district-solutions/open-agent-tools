# Agent Python Tools

- repo: facebookresearch/collaq
- repo_uri: https://github.com/facebookresearch/collaq

## File: facebookresearch_collaq/src_code/learners/q_explore_learner.py

Prompts

```
['create an RNDModel neural network module for random network distillation intrinsic reward', 'run the RNDModel get_reward method to compute intrinsic reward from state predictions', 'run the RNDModel update method to train the body model against the target network', 'create a QExploreLearner with VDN or QMixer and count or RND intrinsic exploration', 'run the QExploreLearner train method to perform one step of Q-learning with intrinsic rewards', 'create a QInfluenceLearner instance with a MAC, scheme, logger, and args configuration', 'train the QInfluenceLearner on an EpisodeBatch using TD-error loss and RMSprop optimization', 'update the target MAC and mixer networks by copying weights from the live networks', 'save the MAC models, mixer state dict, and optimizer state to a directory path', 'load the MAC models, mixer state dict, and optimizer state from a directory path', 'train the QInteractiveLearner on an EpisodeBatch with TD-error loss and regularization', 'update target MAC and mixer networks by copying current network weights', 'initialize a QInteractiveLearner with a MAC, logger, and configurable mixer type', 'save the MAC, mixer, and optimizer state dicts to a directory path', 'load the MAC, mixer, and optimizer state dicts from a directory path']
```

Usage

```
{'create_RNDModel': 'create an RNDModel neural network module for random network distillation intrinsic reward', 'run_RNDModel_get_reward': 'run the RNDModel get_reward method to compute intrinsic reward from state predictions', 'run_RNDModel_update': 'run the RNDModel update method to train the body model against the target network', 'create_QExploreLearner': 'create a QExploreLearner with VDN or QMixer and count or RND intrinsic exploration', 'run_QExploreLearner_train': 'run the QExploreLearner train method to perform one step of Q-learning with intrinsic rewards'}
```

## File: facebookresearch_collaq/src_code/learners/q_influence_learner.py

Prompts

```
['create an RNDModel neural network module for random network distillation intrinsic reward', 'run the RNDModel get_reward method to compute intrinsic reward from state predictions', 'run the RNDModel update method to train the body model against the target network', 'create a QExploreLearner with VDN or QMixer and count or RND intrinsic exploration', 'run the QExploreLearner train method to perform one step of Q-learning with intrinsic rewards', 'create a QInfluenceLearner instance with a MAC, scheme, logger, and args configuration', 'train the QInfluenceLearner on an EpisodeBatch using TD-error loss and RMSprop optimization', 'update the target MAC and mixer networks by copying weights from the live networks', 'save the MAC models, mixer state dict, and optimizer state to a directory path', 'load the MAC models, mixer state dict, and optimizer state from a directory path', 'train the QInteractiveLearner on an EpisodeBatch with TD-error loss and regularization', 'update target MAC and mixer networks by copying current network weights', 'initialize a QInteractiveLearner with a MAC, logger, and configurable mixer type', 'save the MAC, mixer, and optimizer state dicts to a directory path', 'load the MAC, mixer, and optimizer state dicts from a directory path']
```

Usage

```
{'create_QInfluenceLearner': 'create a QInfluenceLearner instance with a MAC, scheme, logger, and args configuration', 'train_QInfluenceLearner': 'train the QInfluenceLearner on an EpisodeBatch using TD-error loss and RMSprop optimization', 'update_targets_QInfluenceLearner': 'update the target MAC and mixer networks by copying weights from the live networks', 'save_models_QInfluenceLearner': 'save the MAC models, mixer state dict, and optimizer state to a directory path', 'load_models_QInfluenceLearner': 'load the MAC models, mixer state dict, and optimizer state from a directory path'}
```

## File: facebookresearch_collaq/src_code/learners/q_interactive_learner.py

Prompts

```
['create an RNDModel neural network module for random network distillation intrinsic reward', 'run the RNDModel get_reward method to compute intrinsic reward from state predictions', 'run the RNDModel update method to train the body model against the target network', 'create a QExploreLearner with VDN or QMixer and count or RND intrinsic exploration', 'run the QExploreLearner train method to perform one step of Q-learning with intrinsic rewards', 'create a QInfluenceLearner instance with a MAC, scheme, logger, and args configuration', 'train the QInfluenceLearner on an EpisodeBatch using TD-error loss and RMSprop optimization', 'update the target MAC and mixer networks by copying weights from the live networks', 'save the MAC models, mixer state dict, and optimizer state to a directory path', 'load the MAC models, mixer state dict, and optimizer state from a directory path', 'train the QInteractiveLearner on an EpisodeBatch with TD-error loss and regularization', 'update target MAC and mixer networks by copying current network weights', 'initialize a QInteractiveLearner with a MAC, logger, and configurable mixer type', 'save the MAC, mixer, and optimizer state dicts to a directory path', 'load the MAC, mixer, and optimizer state dicts from a directory path']
```

Usage

```
{'train_q_interactive_learner': 'train the QInteractiveLearner on an EpisodeBatch with TD-error loss and regularization', 'update_target_networks': 'update target MAC and mixer networks by copying current network weights', 'initialize_q_interactive_learner': 'initialize a QInteractiveLearner with a MAC, logger, and configurable mixer type', 'save_learner_models': 'save the MAC, mixer, and optimizer state dicts to a directory path', 'load_learner_models': 'load the MAC, mixer, and optimizer state dicts from a directory path'}
```

