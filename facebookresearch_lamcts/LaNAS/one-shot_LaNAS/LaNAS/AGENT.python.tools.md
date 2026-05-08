# Agent Python Tools

- repo: facebookresearch/lamcts
- repo_uri: https://github.com/facebookresearch/lamcts

## File: facebookresearch_lamcts/LaNAS/one-shot_LaNAS/LaNAS/Classifier.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model on updated samples using MSE loss and Adam optimizer', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'split training samples into good and bad categories by training and comparing against mean accuracy', 'create an MCTS agent with a search space, trainer, and tree height for neural architecture search', 'run the MCTS search loop to iteratively sample and evaluate neural network architectures', 'select a leaf node from the MCTS tree using UCT-based exploration with boundary constraints', 'backpropagate accuracy results from a leaf node up through the MCTS tree to update statistics', 'dump the MCTS agent state including samples and search counter to a pickle file', 'create a Node object as the root of a UCT search tree for neural architecture search', 'collect an architecture sample with its accuracy into the Node bag dictionary', 'train the Node classifier to split data into good and bad kid datasets', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample and remove a random architecture from the Node bag for evaluation', 'create a LinearModel MLP predictor with given input and output dimensions', 'train the LinearModel on a dictionary of JSON feature keys mapped to accuracy values', 'propose top-N candidate neural network architectures from a search space using the trained model', 'run a forward pass through the LinearModel to predict accuracy scores for input features', 'reinitialize the LinearModel weights using Xavier uniform initialization']
```

Usage

```
{'create_Classifier': 'create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train_Classifier': 'train the Classifier model on updated samples using MSE loss and Adam optimizer', 'predict_Classifier': 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split_predictions_Classifier': 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'split_data_Classifier': 'split training samples into good and bad categories by training and comparing against mean accuracy'}
```

## File: facebookresearch_lamcts/LaNAS/one-shot_LaNAS/LaNAS/MCTS.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model on updated samples using MSE loss and Adam optimizer', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'split training samples into good and bad categories by training and comparing against mean accuracy', 'create an MCTS agent with a search space, trainer, and tree height for neural architecture search', 'run the MCTS search loop to iteratively sample and evaluate neural network architectures', 'select a leaf node from the MCTS tree using UCT-based exploration with boundary constraints', 'backpropagate accuracy results from a leaf node up through the MCTS tree to update statistics', 'dump the MCTS agent state including samples and search counter to a pickle file', 'create a Node object as the root of a UCT search tree for neural architecture search', 'collect an architecture sample with its accuracy into the Node bag dictionary', 'train the Node classifier to split data into good and bad kid datasets', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample and remove a random architecture from the Node bag for evaluation', 'create a LinearModel MLP predictor with given input and output dimensions', 'train the LinearModel on a dictionary of JSON feature keys mapped to accuracy values', 'propose top-N candidate neural network architectures from a search space using the trained model', 'run a forward pass through the LinearModel to predict accuracy scores for input features', 'reinitialize the LinearModel weights using Xavier uniform initialization']
```

Usage

```
{'init_MCTS': 'create an MCTS agent with a search space, trainer, and tree height for neural architecture search', 'run_MCTS_search': 'run the MCTS search loop to iteratively sample and evaluate neural network architectures', 'select_MCTS_node': 'select a leaf node from the MCTS tree using UCT-based exploration with boundary constraints', 'backpropagate_MCTS': 'backpropagate accuracy results from a leaf node up through the MCTS tree to update statistics', 'dump_MCTS_agent': 'dump the MCTS agent state including samples and search counter to a pickle file'}
```

## File: facebookresearch_lamcts/LaNAS/one-shot_LaNAS/LaNAS/Node.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model on updated samples using MSE loss and Adam optimizer', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'split training samples into good and bad categories by training and comparing against mean accuracy', 'create an MCTS agent with a search space, trainer, and tree height for neural architecture search', 'run the MCTS search loop to iteratively sample and evaluate neural network architectures', 'select a leaf node from the MCTS tree using UCT-based exploration with boundary constraints', 'backpropagate accuracy results from a leaf node up through the MCTS tree to update statistics', 'dump the MCTS agent state including samples and search counter to a pickle file', 'create a Node object as the root of a UCT search tree for neural architecture search', 'collect an architecture sample with its accuracy into the Node bag dictionary', 'train the Node classifier to split data into good and bad kid datasets', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample and remove a random architecture from the Node bag for evaluation', 'create a LinearModel MLP predictor with given input and output dimensions', 'train the LinearModel on a dictionary of JSON feature keys mapped to accuracy values', 'propose top-N candidate neural network architectures from a search space using the trained model', 'run a forward pass through the LinearModel to predict accuracy scores for input features', 'reinitialize the LinearModel weights using Xavier uniform initialization']
```

Usage

```
{'create_Node_tree': 'create a Node object as the root of a UCT search tree for neural architecture search', 'collect_sample_Node': 'collect an architecture sample with its accuracy into the Node bag dictionary', 'train_Node_classifier': 'train the Node classifier to split data into good and bad kid datasets', 'predict_Node_split': 'predict and split the Node bag into good and bad kid data using the classifier', 'sample_arch_Node': 'sample and remove a random architecture from the Node bag for evaluation'}
```

## File: facebookresearch_lamcts/LaNAS/one-shot_LaNAS/LaNAS/mlp_predictor.py

Prompts

```
['create a Classifier instance with samples dictionary and input dimension for neural architecture search', 'train the Classifier model on updated samples using MSE loss and Adam optimizer', 'predict accuracy scores for remaining network architectures using the trained Classifier model', 'split remaining network architectures into good and bad samples based on predicted accuracy threshold', 'split training samples into good and bad categories by training and comparing against mean accuracy', 'create an MCTS agent with a search space, trainer, and tree height for neural architecture search', 'run the MCTS search loop to iteratively sample and evaluate neural network architectures', 'select a leaf node from the MCTS tree using UCT-based exploration with boundary constraints', 'backpropagate accuracy results from a leaf node up through the MCTS tree to update statistics', 'dump the MCTS agent state including samples and search counter to a pickle file', 'create a Node object as the root of a UCT search tree for neural architecture search', 'collect an architecture sample with its accuracy into the Node bag dictionary', 'train the Node classifier to split data into good and bad kid datasets', 'predict and split the Node bag into good and bad kid data using the classifier', 'sample and remove a random architecture from the Node bag for evaluation', 'create a LinearModel MLP predictor with given input and output dimensions', 'train the LinearModel on a dictionary of JSON feature keys mapped to accuracy values', 'propose top-N candidate neural network architectures from a search space using the trained model', 'run a forward pass through the LinearModel to predict accuracy scores for input features', 'reinitialize the LinearModel weights using Xavier uniform initialization']
```

Usage

```
{'create_LinearModel': 'create a LinearModel MLP predictor with given input and output dimensions', 'train_LinearModel': 'train the LinearModel on a dictionary of JSON feature keys mapped to accuracy values', 'propose_networks_LinearModel': 'propose top-N candidate neural network architectures from a search space using the trained model', 'forward_LinearModel': 'run a forward pass through the LinearModel to predict accuracy scores for input features', 'weights_init_LinearModel': 'reinitialize the LinearModel weights using Xavier uniform initialization'}
```

