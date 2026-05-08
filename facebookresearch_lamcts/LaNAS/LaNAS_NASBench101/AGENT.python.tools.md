# Agent Python Tools

- repo: facebookresearch/lamcts
- repo_uri: https://github.com/facebookresearch/lamcts

## File: facebookresearch_lamcts/LaNAS/LaNAS_NASBench101/Classifier.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'update the Classifier with new network samples and their accuracy values for retraining', 'create an MCTS agent with a search space, tree height, and architecture code length', 'run the MCTS search loop to explore and evaluate neural architecture candidates', 'select a leaf node from the MCTS tree using UCT scoring and exploration', 'backpropagate accuracy values up the MCTS tree from a leaf to the root', 'dump the full MCTS agent state including samples and nodes to a pickle file', 'create a root Node instance with is_root=True for MCTS tree search', 'train the Node classifier using bag samples and split data into good and bad kid groups', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample a random architecture from the Node bag and remove it for evaluation', 'get the UCT score of a Node for MCTS selection with configurable exploration constant', 'train a neural network architecture using Net_Trainer and get accuracy from NASBench101 dataset', 'print the best accuracy traces found so far during neural architecture search', 'initialize a Net_Trainer that loads the NASBench101 dataset from nasbench_dataset file', 'review the Net_Trainer class and its neural architecture search training logic', 'summarize the train_net method that evaluates network architectures against the dataset']
```

Usage

```
{'create_classifier': 'create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train_classifier': 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict_accuracy': 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split_predictions': 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'update_samples': 'update the Classifier with new network samples and their accuracy values for retraining'}
```

## File: facebookresearch_lamcts/LaNAS/LaNAS_NASBench101/MCTS.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'update the Classifier with new network samples and their accuracy values for retraining', 'create an MCTS agent with a search space, tree height, and architecture code length', 'run the MCTS search loop to explore and evaluate neural architecture candidates', 'select a leaf node from the MCTS tree using UCT scoring and exploration', 'backpropagate accuracy values up the MCTS tree from a leaf to the root', 'dump the full MCTS agent state including samples and nodes to a pickle file', 'create a root Node instance with is_root=True for MCTS tree search', 'train the Node classifier using bag samples and split data into good and bad kid groups', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample a random architecture from the Node bag and remove it for evaluation', 'get the UCT score of a Node for MCTS selection with configurable exploration constant', 'train a neural network architecture using Net_Trainer and get accuracy from NASBench101 dataset', 'print the best accuracy traces found so far during neural architecture search', 'initialize a Net_Trainer that loads the NASBench101 dataset from nasbench_dataset file', 'review the Net_Trainer class and its neural architecture search training logic', 'summarize the train_net method that evaluates network architectures against the dataset']
```

Usage

```
{'create_MCTS_agent': 'create an MCTS agent with a search space, tree height, and architecture code length', 'run_MCTS_search': 'run the MCTS search loop to explore and evaluate neural architecture candidates', 'select_MCTS_leaf': 'select a leaf node from the MCTS tree using UCT scoring and exploration', 'backpropagate_MCTS_accuracy': 'backpropagate accuracy values up the MCTS tree from a leaf to the root', 'dump_MCTS_state': 'dump the full MCTS agent state including samples and nodes to a pickle file'}
```

## File: facebookresearch_lamcts/LaNAS/LaNAS_NASBench101/Node.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'update the Classifier with new network samples and their accuracy values for retraining', 'create an MCTS agent with a search space, tree height, and architecture code length', 'run the MCTS search loop to explore and evaluate neural architecture candidates', 'select a leaf node from the MCTS tree using UCT scoring and exploration', 'backpropagate accuracy values up the MCTS tree from a leaf to the root', 'dump the full MCTS agent state including samples and nodes to a pickle file', 'create a root Node instance with is_root=True for MCTS tree search', 'train the Node classifier using bag samples and split data into good and bad kid groups', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample a random architecture from the Node bag and remove it for evaluation', 'get the UCT score of a Node for MCTS selection with configurable exploration constant', 'train a neural network architecture using Net_Trainer and get accuracy from NASBench101 dataset', 'print the best accuracy traces found so far during neural architecture search', 'initialize a Net_Trainer that loads the NASBench101 dataset from nasbench_dataset file', 'review the Net_Trainer class and its neural architecture search training logic', 'summarize the train_net method that evaluates network architectures against the dataset']
```

Usage

```
{'create_Node_root': 'create a root Node instance with is_root=True for MCTS tree search', 'train_Node_classifier': 'train the Node classifier using bag samples and split data into good and bad kid groups', 'predict_Node_split': 'predict and split the Node bag into good and bad kid data using the classifier', 'sample_arch_Node': 'sample a random architecture from the Node bag and remove it for evaluation', 'get_uct_Node': 'get the UCT score of a Node for MCTS selection with configurable exploration constant'}
```

## File: facebookresearch_lamcts/LaNAS/LaNAS_NASBench101/net_training.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'update the Classifier with new network samples and their accuracy values for retraining', 'create an MCTS agent with a search space, tree height, and architecture code length', 'run the MCTS search loop to explore and evaluate neural architecture candidates', 'select a leaf node from the MCTS tree using UCT scoring and exploration', 'backpropagate accuracy values up the MCTS tree from a leaf to the root', 'dump the full MCTS agent state including samples and nodes to a pickle file', 'create a root Node instance with is_root=True for MCTS tree search', 'train the Node classifier using bag samples and split data into good and bad kid groups', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample a random architecture from the Node bag and remove it for evaluation', 'get the UCT score of a Node for MCTS selection with configurable exploration constant', 'train a neural network architecture using Net_Trainer and get accuracy from NASBench101 dataset', 'print the best accuracy traces found so far during neural architecture search', 'initialize a Net_Trainer that loads the NASBench101 dataset from nasbench_dataset file', 'review the Net_Trainer class and its neural architecture search training logic', 'summarize the train_net method that evaluates network architectures against the dataset']
```

Usage

```
{'train_net_architecture': 'train a neural network architecture using Net_Trainer and get accuracy from NASBench101 dataset', 'print_best_traces': 'print the best accuracy traces found so far during neural architecture search', 'init_net_trainer': 'initialize a Net_Trainer that loads the NASBench101 dataset from nasbench_dataset file', 'review_net_trainer_class': 'review the Net_Trainer class and its neural architecture search training logic', 'summarize_train_net_method': 'summarize the train_net method that evaluates network architectures against the dataset'}
```

