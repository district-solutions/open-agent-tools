# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/examples/bandits/launcher.py

Prompts

```
['run an encrypted contextual bandits learning experiment on MNIST using the launcher with argparse cli', 'run the contextual bandits example in multiprocess mode with a specified world size', 'load and preprocess MNIST dataset with optional PCA dimensionality reduction and k-means clustering rewards', 'build an epsilon greedy or linucb learner with encrypted or plaintext backend and monitoring closures', 'visualize cumulative reward learning curves over time using visdom for contextual bandits', 'run a membership inference attack on checkpointed bandit models using the CLI with --checkpoint_folder', 'compute rewards for an epsilon-greedy contextual bandit using weights and a dataset tensor', 'measure the accuracy of a membership inference attack by comparing positive and negative reward sets', 'visualize membership inference advantage over training iterations using visdom with the --visualize flag', 'run the online_learner function to minimize linear least squared loss on a contextual bandit dataset', 'run the epsilon_greedy function to execute an epsilon-greedy linear least squares learner on a dataset', 'run the linucb function to execute a LinUCB contextual bandit learner on a dataset', 'review the online_learner function and its Sherman-Morrison formula for updating linear least squares accumulators', 'refactor the epsilon_greedy score_func to use a different exploration strategy for arm selection', 'run an epsilon-greedy linear least squares contextual bandit learner on a dataset with MPC privacy', 'run an online linear least squares contextual bandit learner with secret-shared rewards and contexts', 'set the Crypten encoder precision bits for secure multi-party computation numerical precision', 'refactor the epsilon_greedy scoring function to use a custom exploration mechanism instead of random scores']
```

Usage

```
{'run_contextual_bandits_experiment': 'run an encrypted contextual bandits learning experiment on MNIST using the launcher with argparse cli', 'run_multiprocess_bandits': 'run the contextual bandits example in multiprocess mode with a specified world size', 'load_mnist_data_with_pca': 'load and preprocess MNIST dataset with optional PCA dimensionality reduction and k-means clustering rewards', 'build_bandit_learner': 'build an epsilon greedy or linucb learner with encrypted or plaintext backend and monitoring closures', 'visualize_learning_curve': 'visualize cumulative reward learning curves over time using visdom for contextual bandits'}
```

## File: facebookresearch_crypten/examples/bandits/membership_inference.py

Prompts

```
['run an encrypted contextual bandits learning experiment on MNIST using the launcher with argparse cli', 'run the contextual bandits example in multiprocess mode with a specified world size', 'load and preprocess MNIST dataset with optional PCA dimensionality reduction and k-means clustering rewards', 'build an epsilon greedy or linucb learner with encrypted or plaintext backend and monitoring closures', 'visualize cumulative reward learning curves over time using visdom for contextual bandits', 'run a membership inference attack on checkpointed bandit models using the CLI with --checkpoint_folder', 'compute rewards for an epsilon-greedy contextual bandit using weights and a dataset tensor', 'measure the accuracy of a membership inference attack by comparing positive and negative reward sets', 'visualize membership inference advantage over training iterations using visdom with the --visualize flag', 'run the online_learner function to minimize linear least squared loss on a contextual bandit dataset', 'run the epsilon_greedy function to execute an epsilon-greedy linear least squares learner on a dataset', 'run the linucb function to execute a LinUCB contextual bandit learner on a dataset', 'review the online_learner function and its Sherman-Morrison formula for updating linear least squares accumulators', 'refactor the epsilon_greedy score_func to use a different exploration strategy for arm selection', 'run an epsilon-greedy linear least squares contextual bandit learner on a dataset with MPC privacy', 'run an online linear least squares contextual bandit learner with secret-shared rewards and contexts', 'set the Crypten encoder precision bits for secure multi-party computation numerical precision', 'refactor the epsilon_greedy scoring function to use a custom exploration mechanism instead of random scores']
```

Usage

```
{'run_membership_inference_attack': 'run a membership inference attack on checkpointed bandit models using the CLI with --checkpoint_folder', 'run_multiprocess_bandits': 'run the bandits membership inference example in multiprocess mode using the --multiprocess flag', 'compute_rewards_epsilon_greedy': 'compute rewards for an epsilon-greedy contextual bandit using weights and a dataset tensor', 'measure_membership_accuracy': 'measure the accuracy of a membership inference attack by comparing positive and negative reward sets', 'visualize_inference_advantage': 'visualize membership inference advantage over training iterations using visdom with the --visualize flag'}
```

## File: facebookresearch_crypten/examples/bandits/plain_contextual_bandits.py

Prompts

```
['run an encrypted contextual bandits learning experiment on MNIST using the launcher with argparse cli', 'run the contextual bandits example in multiprocess mode with a specified world size', 'load and preprocess MNIST dataset with optional PCA dimensionality reduction and k-means clustering rewards', 'build an epsilon greedy or linucb learner with encrypted or plaintext backend and monitoring closures', 'visualize cumulative reward learning curves over time using visdom for contextual bandits', 'run a membership inference attack on checkpointed bandit models using the CLI with --checkpoint_folder', 'compute rewards for an epsilon-greedy contextual bandit using weights and a dataset tensor', 'measure the accuracy of a membership inference attack by comparing positive and negative reward sets', 'visualize membership inference advantage over training iterations using visdom with the --visualize flag', 'run the online_learner function to minimize linear least squared loss on a contextual bandit dataset', 'run the epsilon_greedy function to execute an epsilon-greedy linear least squares learner on a dataset', 'run the linucb function to execute a LinUCB contextual bandit learner on a dataset', 'review the online_learner function and its Sherman-Morrison formula for updating linear least squares accumulators', 'refactor the epsilon_greedy score_func to use a different exploration strategy for arm selection', 'run an epsilon-greedy linear least squares contextual bandit learner on a dataset with MPC privacy', 'run an online linear least squares contextual bandit learner with secret-shared rewards and contexts', 'set the Crypten encoder precision bits for secure multi-party computation numerical precision', 'refactor the epsilon_greedy scoring function to use a custom exploration mechanism instead of random scores']
```

Usage

```
{'run_online_learner': 'run the online_learner function to minimize linear least squared loss on a contextual bandit dataset', 'run_epsilon_greedy': 'run the epsilon_greedy function to execute an epsilon-greedy linear least squares learner on a dataset', 'run_linucb': 'run the linucb function to execute a LinUCB contextual bandit learner on a dataset', 'review_online_learner': 'review the online_learner function and its Sherman-Morrison formula for updating linear least squares accumulators', 'refactor_epsilon_greedy': 'refactor the epsilon_greedy score_func to use a different exploration strategy for arm selection'}
```

## File: facebookresearch_crypten/examples/bandits/private_contextual_bandits.py

Prompts

```
['run an encrypted contextual bandits learning experiment on MNIST using the launcher with argparse cli', 'run the contextual bandits example in multiprocess mode with a specified world size', 'load and preprocess MNIST dataset with optional PCA dimensionality reduction and k-means clustering rewards', 'build an epsilon greedy or linucb learner with encrypted or plaintext backend and monitoring closures', 'visualize cumulative reward learning curves over time using visdom for contextual bandits', 'run a membership inference attack on checkpointed bandit models using the CLI with --checkpoint_folder', 'compute rewards for an epsilon-greedy contextual bandit using weights and a dataset tensor', 'measure the accuracy of a membership inference attack by comparing positive and negative reward sets', 'visualize membership inference advantage over training iterations using visdom with the --visualize flag', 'run the online_learner function to minimize linear least squared loss on a contextual bandit dataset', 'run the epsilon_greedy function to execute an epsilon-greedy linear least squares learner on a dataset', 'run the linucb function to execute a LinUCB contextual bandit learner on a dataset', 'review the online_learner function and its Sherman-Morrison formula for updating linear least squares accumulators', 'refactor the epsilon_greedy score_func to use a different exploration strategy for arm selection', 'run an epsilon-greedy linear least squares contextual bandit learner on a dataset with MPC privacy', 'run an online linear least squares contextual bandit learner with secret-shared rewards and contexts', 'set the Crypten encoder precision bits for secure multi-party computation numerical precision', 'refactor the epsilon_greedy scoring function to use a custom exploration mechanism instead of random scores']
```

Usage

```
{'run_epsilon_greedy_bandit': 'run an epsilon-greedy linear least squares contextual bandit learner on a dataset with MPC privacy', 'run_online_learner_bandit': 'run an online linear least squares contextual bandit learner with secret-shared rewards and contexts', 'set_precision_crypten': 'set the Crypten encoder precision bits for secure multi-party computation numerical precision', 'review_online_learner': 'review the online_learner function that minimizes linear least squared loss using Sherman-Morrison updates', 'refactor_epsilon_greedy_score': 'refactor the epsilon_greedy scoring function to use a custom exploration mechanism instead of random scores'}
```

