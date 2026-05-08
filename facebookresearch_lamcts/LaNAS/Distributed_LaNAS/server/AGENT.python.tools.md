# Agent Python Tools

- repo: facebookresearch/lamcts
- repo_uri: https://github.com/facebookresearch/lamcts

## File: facebookresearch_lamcts/LaNAS/Distributed_LaNAS/server/Classifier.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split predicted network architectures into good and bad samples based on average accuracy threshold', 'train the Classifier and split existing samples into good and bad based on predicted mean accuracy', 'create an MCTS agent with a search space, tree height, and architecture code length', 'run the MCTS search loop to explore neural architecture search space with distributed job dispatch', 'select a leaf node from the MCTS tree using UCT values for architecture sampling', 'backpropagate accuracy rewards from a leaf node up to the root through the MCTS tree', 'dispatch architecture evaluation jobs to a server and retrieve accuracy results from clients', 'create a Node object as the root of a MCTS search tree with an architecture code length', 'collect an architecture sample with its accuracy into the Node bag for training', 'train the Node classifier to split data into good and bad kid datasets', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample a random architecture from the Node bag and remove it for evaluation', 'create a Net_Trainer instance that loads architecture data from features.json', 'train a neural network architecture and return its accuracy score', 'print the best training traces sorted by accuracy so far', 'review the Net_Trainer class and its architecture search capabilities', 'summarize the train_net method that evaluates network architectures against a dataset']
```

Usage

```
{'create_classifier': 'create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train_classifier': 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict_accuracy': 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split_predictions': 'split predicted network architectures into good and bad samples based on average accuracy threshold', 'split_data': 'train the Classifier and split existing samples into good and bad based on predicted mean accuracy'}
```

## File: facebookresearch_lamcts/LaNAS/Distributed_LaNAS/server/MCTS.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split predicted network architectures into good and bad samples based on average accuracy threshold', 'train the Classifier and split existing samples into good and bad based on predicted mean accuracy', 'create an MCTS agent with a search space, tree height, and architecture code length', 'run the MCTS search loop to explore neural architecture search space with distributed job dispatch', 'select a leaf node from the MCTS tree using UCT values for architecture sampling', 'backpropagate accuracy rewards from a leaf node up to the root through the MCTS tree', 'dispatch architecture evaluation jobs to a server and retrieve accuracy results from clients', 'create a Node object as the root of a MCTS search tree with an architecture code length', 'collect an architecture sample with its accuracy into the Node bag for training', 'train the Node classifier to split data into good and bad kid datasets', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample a random architecture from the Node bag and remove it for evaluation', 'create a Net_Trainer instance that loads architecture data from features.json', 'train a neural network architecture and return its accuracy score', 'print the best training traces sorted by accuracy so far', 'review the Net_Trainer class and its architecture search capabilities', 'summarize the train_net method that evaluates network architectures against a dataset']
```

Usage

```
{'create_mcts_agent': 'create an MCTS agent with a search space, tree height, and architecture code length', 'run_mcts_search': 'run the MCTS search loop to explore neural architecture search space with distributed job dispatch', 'select_mcts_leaf': 'select a leaf node from the MCTS tree using UCT values for architecture sampling', 'backpropagate_mcts_rewards': 'backpropagate accuracy rewards from a leaf node up to the root through the MCTS tree', 'dispatch_mcts_jobs': 'dispatch architecture evaluation jobs to a server and retrieve accuracy results from clients'}
```

## File: facebookresearch_lamcts/LaNAS/Distributed_LaNAS/server/Node.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split predicted network architectures into good and bad samples based on average accuracy threshold', 'train the Classifier and split existing samples into good and bad based on predicted mean accuracy', 'create an MCTS agent with a search space, tree height, and architecture code length', 'run the MCTS search loop to explore neural architecture search space with distributed job dispatch', 'select a leaf node from the MCTS tree using UCT values for architecture sampling', 'backpropagate accuracy rewards from a leaf node up to the root through the MCTS tree', 'dispatch architecture evaluation jobs to a server and retrieve accuracy results from clients', 'create a Node object as the root of a MCTS search tree with an architecture code length', 'collect an architecture sample with its accuracy into the Node bag for training', 'train the Node classifier to split data into good and bad kid datasets', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample a random architecture from the Node bag and remove it for evaluation', 'create a Net_Trainer instance that loads architecture data from features.json', 'train a neural network architecture and return its accuracy score', 'print the best training traces sorted by accuracy so far', 'review the Net_Trainer class and its architecture search capabilities', 'summarize the train_net method that evaluates network architectures against a dataset']
```

Usage

```
{'create_Node_tree': 'create a Node object as the root of a MCTS search tree with an architecture code length', 'collect_sample_Node': 'collect an architecture sample with its accuracy into the Node bag for training', 'train_Node_classifier': 'train the Node classifier to split data into good and bad kid datasets', 'predict_Node_split': 'predict and split the Node bag into good and bad kid data using the classifier', 'sample_arch_Node': 'sample a random architecture from the Node bag and remove it for evaluation'}
```

## File: facebookresearch_lamcts/LaNAS/Distributed_LaNAS/server/net_training.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model using MSE loss on network samples and accuracy labels', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split predicted network architectures into good and bad samples based on average accuracy threshold', 'train the Classifier and split existing samples into good and bad based on predicted mean accuracy', 'create an MCTS agent with a search space, tree height, and architecture code length', 'run the MCTS search loop to explore neural architecture search space with distributed job dispatch', 'select a leaf node from the MCTS tree using UCT values for architecture sampling', 'backpropagate accuracy rewards from a leaf node up to the root through the MCTS tree', 'dispatch architecture evaluation jobs to a server and retrieve accuracy results from clients', 'create a Node object as the root of a MCTS search tree with an architecture code length', 'collect an architecture sample with its accuracy into the Node bag for training', 'train the Node classifier to split data into good and bad kid datasets', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample a random architecture from the Node bag and remove it for evaluation', 'create a Net_Trainer instance that loads architecture data from features.json', 'train a neural network architecture and return its accuracy score', 'print the best training traces sorted by accuracy so far', 'review the Net_Trainer class and its architecture search capabilities', 'summarize the train_net method that evaluates network architectures against a dataset']
```

Usage

```
{'init_net_trainer': 'create a Net_Trainer instance that loads architecture data from features.json', 'train_net': 'train a neural network architecture and return its accuracy score', 'print_best_traces': 'print the best training traces sorted by accuracy so far', 'review_net_trainer_class': 'review the Net_Trainer class and its architecture search capabilities', 'summarize_train_net': 'summarize the train_net method that evaluates network architectures against a dataset'}
```

