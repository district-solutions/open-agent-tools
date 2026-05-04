# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/external_game/archs.py

Prompts

```
['build a ReinforceReceiver module that samples actions using a categorical distribution with entropy tracking', 'build a Receiver module with a linear layer that maps hidden states to output logits', 'build a Sender module with a linear layer that encodes input features into hidden representations', 'review the ReinforceReceiver forward method that returns sampled actions, log probabilities, and entropy', 'test the ReinforceReceiver to verify it samples stochastically in training and greedily in eval mode', 'create a CSVDataset from a semicolon-delimited CSV file with sender_input and label columns', 'get the number of input features from the first sample in the CSVDataset', 'get the output label size from the first sample in the CSVDataset', 'get the maximum label value across all samples in the CSVDataset', 'retrieve a specific (sender_input, label) tensor pair by index from the CSVDataset', 'run the external game training with GumbelSoftmax or Reinforce mode using CSV data', 'build a Sender and Receiver model pair with configurable hidden layers and cell types', 'dump game interactions to print sender input, message, receiver output, and labels', 'review the differentiable loss function that computes cross entropy and accuracy for GumbelSoftmax training', 'review the non differentiable loss function that computes accuracy for Reinforce training']
```

Usage

```
{'build_ReinforceReceiver': 'build a ReinforceReceiver module that samples actions using a categorical distribution with entropy tracking', 'build_Receiver': 'build a Receiver module with a linear layer that maps hidden states to output logits', 'build_Sender': 'build a Sender module with a linear layer that encodes input features into hidden representations', 'review_ReinforceReceiver_forward': 'review the ReinforceReceiver forward method that returns sampled actions, log probabilities, and entropy', 'test_ReinforceReceiver_training_mode': 'test the ReinforceReceiver to verify it samples stochastically in training and greedily in eval mode'}
```

## File: facebookresearch_egg/egg/zoo/external_game/features.py

Prompts

```
['build a ReinforceReceiver module that samples actions using a categorical distribution with entropy tracking', 'build a Receiver module with a linear layer that maps hidden states to output logits', 'build a Sender module with a linear layer that encodes input features into hidden representations', 'review the ReinforceReceiver forward method that returns sampled actions, log probabilities, and entropy', 'test the ReinforceReceiver to verify it samples stochastically in training and greedily in eval mode', 'create a CSVDataset from a semicolon-delimited CSV file with sender_input and label columns', 'get the number of input features from the first sample in the CSVDataset', 'get the output label size from the first sample in the CSVDataset', 'get the maximum label value across all samples in the CSVDataset', 'retrieve a specific (sender_input, label) tensor pair by index from the CSVDataset', 'run the external game training with GumbelSoftmax or Reinforce mode using CSV data', 'build a Sender and Receiver model pair with configurable hidden layers and cell types', 'dump game interactions to print sender input, message, receiver output, and labels', 'review the differentiable loss function that computes cross entropy and accuracy for GumbelSoftmax training', 'review the non differentiable loss function that computes accuracy for Reinforce training']
```

Usage

```
{'create_csv_dataset': 'create a CSVDataset from a semicolon-delimited CSV file with sender_input and label columns', 'get_n_features': 'get the number of input features from the first sample in the CSVDataset', 'get_output_size': 'get the output label size from the first sample in the CSVDataset', 'get_output_max': 'get the maximum label value across all samples in the CSVDataset', 'getitem_dataset': 'retrieve a specific (sender_input, label) tensor pair by index from the CSVDataset'}
```

## File: facebookresearch_egg/egg/zoo/external_game/game.py

Prompts

```
['build a ReinforceReceiver module that samples actions using a categorical distribution with entropy tracking', 'build a Receiver module with a linear layer that maps hidden states to output logits', 'build a Sender module with a linear layer that encodes input features into hidden representations', 'review the ReinforceReceiver forward method that returns sampled actions, log probabilities, and entropy', 'test the ReinforceReceiver to verify it samples stochastically in training and greedily in eval mode', 'create a CSVDataset from a semicolon-delimited CSV file with sender_input and label columns', 'get the number of input features from the first sample in the CSVDataset', 'get the output label size from the first sample in the CSVDataset', 'get the maximum label value across all samples in the CSVDataset', 'retrieve a specific (sender_input, label) tensor pair by index from the CSVDataset', 'run the external game training with GumbelSoftmax or Reinforce mode using CSV data', 'build a Sender and Receiver model pair with configurable hidden layers and cell types', 'dump game interactions to print sender input, message, receiver output, and labels', 'review the differentiable loss function that computes cross entropy and accuracy for GumbelSoftmax training', 'review the non differentiable loss function that computes accuracy for Reinforce training']
```

Usage

```
{'run_external_game_training': 'run the external game training with GumbelSoftmax or Reinforce mode using CSV data', 'build_model_sender_receiver': 'build a Sender and Receiver model pair with configurable hidden layers and cell types', 'dump_game_interactions': 'dump game interactions to print sender input, message, receiver output, and labels', 'review_differentiable_loss': 'review the differentiable loss function that computes cross entropy and accuracy for GumbelSoftmax training', 'review_non_differentiable_loss': 'review the non differentiable loss function that computes accuracy for Reinforce training'}
```

