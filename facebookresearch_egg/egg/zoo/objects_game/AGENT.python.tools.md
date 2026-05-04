# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/objects_game/archs.py

Prompts

```
['create a Sender neural network module with n_features input and n_hidden output dimensions', 'create a Receiver neural network module with n_features input and linear_units output dimensions', 'run the Sender forward pass to encode input features through a linear layer with tanh activation', 'run the Receiver forward pass to compute energies between embedded input and sender message', 'review the Sender and Receiver neural network architectures for the objects game communication task', 'create a VectorsLoader with custom perceptual dimensions, distractors, and batch size for the objects game', 'generate train, validation, and test tuple splits from perceptual vector data using VectorsLoader', 'get PyTorch DataLoader iterators for train, validation, and test splits from VectorsLoader', 'load pre-saved train, validation, and test data from a numpy compressed file using VectorsLoader', 'create a TupleDataset PyTorch Dataset from tuples and target indices for the objects game', 'run the objects game training with GumbelSoftmax sender receiver using argparse CLI options', 'evaluate a trained objects game model on test data and compute accuracy and mutual info', 'run the objects game training loading data from a custom npz file path', 'run the objects game evaluation and dump sender receiver messages to a folder', 'run the objects game training with a custom number of distractor objects for the receiver', 'compute the binomial coefficient C(n, k) using a fast iterative method by Andrew Dalke', 'compute the baseline accuracy for a communication game given distribution count, symbols, and dimensions', 'calculate the Shannon entropy in bits for a list of elements including tensors and tuples', 'compute the mutual information between two sequences of elements such as sender inputs and messages', 'dump sender inputs, messages, receiver inputs, outputs, and labels from a game model over a dataset']
```

Usage

```
{'create_sender_model': 'create a Sender neural network module with n_features input and n_hidden output dimensions', 'create_receiver_model': 'create a Receiver neural network module with n_features input and linear_units output dimensions', 'run_sender_forward': 'run the Sender forward pass to encode input features through a linear layer with tanh activation', 'run_receiver_forward': 'run the Receiver forward pass to compute energies between embedded input and sender message', 'review_sender_receiver_archs': 'review the Sender and Receiver neural network architectures for the objects game communication task'}
```

## File: facebookresearch_egg/egg/zoo/objects_game/features.py

Prompts

```
['create a Sender neural network module with n_features input and n_hidden output dimensions', 'create a Receiver neural network module with n_features input and linear_units output dimensions', 'run the Sender forward pass to encode input features through a linear layer with tanh activation', 'run the Receiver forward pass to compute energies between embedded input and sender message', 'review the Sender and Receiver neural network architectures for the objects game communication task', 'create a VectorsLoader with custom perceptual dimensions, distractors, and batch size for the objects game', 'generate train, validation, and test tuple splits from perceptual vector data using VectorsLoader', 'get PyTorch DataLoader iterators for train, validation, and test splits from VectorsLoader', 'load pre-saved train, validation, and test data from a numpy compressed file using VectorsLoader', 'create a TupleDataset PyTorch Dataset from tuples and target indices for the objects game', 'run the objects game training with GumbelSoftmax sender receiver using argparse CLI options', 'evaluate a trained objects game model on test data and compute accuracy and mutual info', 'run the objects game training loading data from a custom npz file path', 'run the objects game evaluation and dump sender receiver messages to a folder', 'run the objects game training with a custom number of distractor objects for the receiver', 'compute the binomial coefficient C(n, k) using a fast iterative method by Andrew Dalke', 'compute the baseline accuracy for a communication game given distribution count, symbols, and dimensions', 'calculate the Shannon entropy in bits for a list of elements including tensors and tuples', 'compute the mutual information between two sequences of elements such as sender inputs and messages', 'dump sender inputs, messages, receiver inputs, outputs, and labels from a game model over a dataset']
```

Usage

```
{'create_VectorsLoader': 'create a VectorsLoader with custom perceptual dimensions, distractors, and batch size for the objects game', 'generate_tuples_VectorsLoader': 'generate train, validation, and test tuple splits from perceptual vector data using VectorsLoader', 'get_iterators_VectorsLoader': 'get PyTorch DataLoader iterators for train, validation, and test splits from VectorsLoader', 'load_data_VectorsLoader': 'load pre-saved train, validation, and test data from a numpy compressed file using VectorsLoader', 'create_TupleDataset': 'create a TupleDataset PyTorch Dataset from tuples and target indices for the objects game'}
```

## File: facebookresearch_egg/egg/zoo/objects_game/train.py

Prompts

```
['create a Sender neural network module with n_features input and n_hidden output dimensions', 'create a Receiver neural network module with n_features input and linear_units output dimensions', 'run the Sender forward pass to encode input features through a linear layer with tanh activation', 'run the Receiver forward pass to compute energies between embedded input and sender message', 'review the Sender and Receiver neural network architectures for the objects game communication task', 'create a VectorsLoader with custom perceptual dimensions, distractors, and batch size for the objects game', 'generate train, validation, and test tuple splits from perceptual vector data using VectorsLoader', 'get PyTorch DataLoader iterators for train, validation, and test splits from VectorsLoader', 'load pre-saved train, validation, and test data from a numpy compressed file using VectorsLoader', 'create a TupleDataset PyTorch Dataset from tuples and target indices for the objects game', 'run the objects game training with GumbelSoftmax sender receiver using argparse CLI options', 'evaluate a trained objects game model on test data and compute accuracy and mutual info', 'run the objects game training loading data from a custom npz file path', 'run the objects game evaluation and dump sender receiver messages to a folder', 'run the objects game training with a custom number of distractor objects for the receiver', 'compute the binomial coefficient C(n, k) using a fast iterative method by Andrew Dalke', 'compute the baseline accuracy for a communication game given distribution count, symbols, and dimensions', 'calculate the Shannon entropy in bits for a list of elements including tensors and tuples', 'compute the mutual information between two sequences of elements such as sender inputs and messages', 'dump sender inputs, messages, receiver inputs, outputs, and labels from a game model over a dataset']
```

Usage

```
{'run_objects_game_training': 'run the objects game training with GumbelSoftmax sender receiver using argparse CLI options', 'run_objects_game_evaluation': 'evaluate a trained objects game model on test data and compute accuracy and mutual info', 'run_objects_game_with_custom_data': 'run the objects game training loading data from a custom npz file path', 'run_objects_game_dump_messages': 'run the objects game evaluation and dump sender receiver messages to a folder', 'run_objects_game_with_distractors': 'run the objects game training with a custom number of distractor objects for the receiver'}
```

## File: facebookresearch_egg/egg/zoo/objects_game/util.py

Prompts

```
['create a Sender neural network module with n_features input and n_hidden output dimensions', 'create a Receiver neural network module with n_features input and linear_units output dimensions', 'run the Sender forward pass to encode input features through a linear layer with tanh activation', 'run the Receiver forward pass to compute energies between embedded input and sender message', 'review the Sender and Receiver neural network architectures for the objects game communication task', 'create a VectorsLoader with custom perceptual dimensions, distractors, and batch size for the objects game', 'generate train, validation, and test tuple splits from perceptual vector data using VectorsLoader', 'get PyTorch DataLoader iterators for train, validation, and test splits from VectorsLoader', 'load pre-saved train, validation, and test data from a numpy compressed file using VectorsLoader', 'create a TupleDataset PyTorch Dataset from tuples and target indices for the objects game', 'run the objects game training with GumbelSoftmax sender receiver using argparse CLI options', 'evaluate a trained objects game model on test data and compute accuracy and mutual info', 'run the objects game training loading data from a custom npz file path', 'run the objects game evaluation and dump sender receiver messages to a folder', 'run the objects game training with a custom number of distractor objects for the receiver', 'compute the binomial coefficient C(n, k) using a fast iterative method by Andrew Dalke', 'compute the baseline accuracy for a communication game given distribution count, symbols, and dimensions', 'calculate the Shannon entropy in bits for a list of elements including tensors and tuples', 'compute the mutual information between two sequences of elements such as sender inputs and messages', 'dump sender inputs, messages, receiver inputs, outputs, and labels from a game model over a dataset']
```

Usage

```
{'compute_binomial_coefficient': 'compute the binomial coefficient C(n, k) using a fast iterative method by Andrew Dalke', 'compute_baseline_accuracy': 'compute the baseline accuracy for a communication game given distribution count, symbols, and dimensions', 'calculate_entropy': 'calculate the Shannon entropy in bits for a list of elements including tensors and tuples', 'compute_mutual_information': 'compute the mutual information between two sequences of elements such as sender inputs and messages', 'dump_sender_receiver_interactions': 'dump sender inputs, messages, receiver inputs, outputs, and labels from a game model over a dataset'}
```

