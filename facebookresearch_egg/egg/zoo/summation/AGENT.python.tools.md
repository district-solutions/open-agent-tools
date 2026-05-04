# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/summation/archs.py

Prompts

```
['build a Receiver nn.Module with a Linear layer that maps n_hidden features to 2 output classes', 'build an Encoder nn.Module with RNN, GRU, or LSTM cell for encoding token sequences into hidden states', 'run the Encoder forward pass on padded token sequences to extract final hidden states', 'run the Receiver forward pass on hidden states to produce 2-class output logits', 'review the Encoder class to understand support for RNN, GRU, and LSTM cell types', 'create a SequenceLoader DataLoader that yields batches of positive and negative summation sequence examples', 'generate positive examples where equal counts of 1s and 2s are produced as PyTorch tensors', 'generate negative examples where unequal counts of 1s and 2s are produced as PyTorch tensors', 'iterate over a _DataIterator to yield sorted batches of labeled sequence examples per epoch', 'review the SequenceLoader class and its integration with PyTorch DataLoader for summation tasks', 'run the summation game training with configurable sender and receiver RNN hyperparameters', 'build an argparse parser for sender receiver RNN training with hidden layer and cell type options', 'create a cross entropy loss function that returns accuracy alongside the loss value', 'train a sender receiver RNN game using EGG core with Gumbel Softmax sampling', 'dump and print sender receiver game interactions showing sequences messages and outputs']
```

Usage

```
{'build_Receiver': 'build a Receiver nn.Module with a Linear layer that maps n_hidden features to 2 output classes', 'build_Encoder': 'build an Encoder nn.Module with RNN, GRU, or LSTM cell for encoding token sequences into hidden states', 'run_Encoder_forward': 'run the Encoder forward pass on padded token sequences to extract final hidden states', 'run_Receiver_forward': 'run the Receiver forward pass on hidden states to produce 2-class output logits', 'review_Encoder_cell_types': 'review the Encoder class to understand support for RNN, GRU, and LSTM cell types'}
```

## File: facebookresearch_egg/egg/zoo/summation/features.py

Prompts

```
['build a Receiver nn.Module with a Linear layer that maps n_hidden features to 2 output classes', 'build an Encoder nn.Module with RNN, GRU, or LSTM cell for encoding token sequences into hidden states', 'run the Encoder forward pass on padded token sequences to extract final hidden states', 'run the Receiver forward pass on hidden states to produce 2-class output logits', 'review the Encoder class to understand support for RNN, GRU, and LSTM cell types', 'create a SequenceLoader DataLoader that yields batches of positive and negative summation sequence examples', 'generate positive examples where equal counts of 1s and 2s are produced as PyTorch tensors', 'generate negative examples where unequal counts of 1s and 2s are produced as PyTorch tensors', 'iterate over a _DataIterator to yield sorted batches of labeled sequence examples per epoch', 'review the SequenceLoader class and its integration with PyTorch DataLoader for summation tasks', 'run the summation game training with configurable sender and receiver RNN hyperparameters', 'build an argparse parser for sender receiver RNN training with hidden layer and cell type options', 'create a cross entropy loss function that returns accuracy alongside the loss value', 'train a sender receiver RNN game using EGG core with Gumbel Softmax sampling', 'dump and print sender receiver game interactions showing sequences messages and outputs']
```

Usage

```
{'create_SequenceLoader': 'create a SequenceLoader DataLoader that yields batches of positive and negative summation sequence examples', 'generate_positive_examples': 'generate positive examples where equal counts of 1s and 2s are produced as PyTorch tensors', 'generate_negative_examples': 'generate negative examples where unequal counts of 1s and 2s are produced as PyTorch tensors', 'iterate_DataIterator': 'iterate over a _DataIterator to yield sorted batches of labeled sequence examples per epoch', 'review_SequenceLoader': 'review the SequenceLoader class and its integration with PyTorch DataLoader for summation tasks'}
```

## File: facebookresearch_egg/egg/zoo/summation/train.py

Prompts

```
['build a Receiver nn.Module with a Linear layer that maps n_hidden features to 2 output classes', 'build an Encoder nn.Module with RNN, GRU, or LSTM cell for encoding token sequences into hidden states', 'run the Encoder forward pass on padded token sequences to extract final hidden states', 'run the Receiver forward pass on hidden states to produce 2-class output logits', 'review the Encoder class to understand support for RNN, GRU, and LSTM cell types', 'create a SequenceLoader DataLoader that yields batches of positive and negative summation sequence examples', 'generate positive examples where equal counts of 1s and 2s are produced as PyTorch tensors', 'generate negative examples where unequal counts of 1s and 2s are produced as PyTorch tensors', 'iterate over a _DataIterator to yield sorted batches of labeled sequence examples per epoch', 'review the SequenceLoader class and its integration with PyTorch DataLoader for summation tasks', 'run the summation game training with configurable sender and receiver RNN hyperparameters', 'build an argparse parser for sender receiver RNN training with hidden layer and cell type options', 'create a cross entropy loss function that returns accuracy alongside the loss value', 'train a sender receiver RNN game using EGG core with Gumbel Softmax sampling', 'dump and print sender receiver game interactions showing sequences messages and outputs']
```

Usage

```
{'run_summation_training': 'run the summation game training with configurable sender and receiver RNN hyperparameters', 'build_get_params': 'build an argparse parser for sender receiver RNN training with hidden layer and cell type options', 'create_loss_function': 'create a cross entropy loss function that returns accuracy alongside the loss value', 'train_sender_receiver_game': 'train a sender receiver RNN game using EGG core with Gumbel Softmax sampling', 'dump_interactions': 'dump and print sender receiver game interactions showing sequences messages and outputs'}
```

