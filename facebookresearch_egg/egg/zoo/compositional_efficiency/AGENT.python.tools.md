# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/compositional_efficiency/archs.py

Prompts

```
['build a Receiver neural network module with configurable hidden layers and output dimensions', 'create an IdentitySender module that passes input messages through unchanged with offset', 'create a RotatedSender module that encodes sum and difference of input attributes', 'create a Lenses module that rotates input examples using a configurable theta angle', 'create a CircleSender module that maps continuous values in [-1,1] to discrete vocabulary tokens', 'run the compositional efficiency continuous sender receiver game with configurable receiver and sender parameters', 'get parsed command line arguments for the continuous game including receiver hidden size and cell type', 'compute the MSE loss between receiver output and sender input for the continuous communication game', 'create a CircleSender with optional Lenses transformation for the continuous compositional efficiency game', 'train an RNN receiver with LSTM or tree cell using reinforcement learning in the continuous game', 'generate all combinations of attribute values and split into train or test sets using hash-based filtering', 'convert a list of attribute value configurations into one-hot encoded PyTorch tensors for each configuration', 'create a PyTorch dataset of attribute-value combinations with optional one-hot encoding and configurable repetition multiplier', 'generate random 2D points on a unit disk with both Cartesian and polar coordinate representations', 'review the AttributeValueData and SphereData classes to understand their PyTorch dataset interface and data generation logic', 'run the discrete communication game training with identity or rotated language and autoenc loss', 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for receiver output', 'run get_params to parse command-line arguments for receiver hidden size, cell layers, and loss type', 'review the DiffLoss class that supports autoenc, mixed, and linear loss types for compositional efficiency', 'review the main function that sets up sender, receiver, game, optimizer, and trainer for training']
```

Usage

```
{'build_Receiver': 'build a Receiver neural network module with configurable hidden layers and output dimensions', 'create_IdentitySender': 'create an IdentitySender module that passes input messages through unchanged with offset', 'create_RotatedSender': 'create a RotatedSender module that encodes sum and difference of input attributes', 'create_Lenses': 'create a Lenses module that rotates input examples using a configurable theta angle', 'create_CircleSender': 'create a CircleSender module that maps continuous values in [-1,1] to discrete vocabulary tokens'}
```

## File: facebookresearch_egg/egg/zoo/compositional_efficiency/continuous.py

Prompts

```
['build a Receiver neural network module with configurable hidden layers and output dimensions', 'create an IdentitySender module that passes input messages through unchanged with offset', 'create a RotatedSender module that encodes sum and difference of input attributes', 'create a Lenses module that rotates input examples using a configurable theta angle', 'create a CircleSender module that maps continuous values in [-1,1] to discrete vocabulary tokens', 'run the compositional efficiency continuous sender receiver game with configurable receiver and sender parameters', 'get parsed command line arguments for the continuous game including receiver hidden size and cell type', 'compute the MSE loss between receiver output and sender input for the continuous communication game', 'create a CircleSender with optional Lenses transformation for the continuous compositional efficiency game', 'train an RNN receiver with LSTM or tree cell using reinforcement learning in the continuous game', 'generate all combinations of attribute values and split into train or test sets using hash-based filtering', 'convert a list of attribute value configurations into one-hot encoded PyTorch tensors for each configuration', 'create a PyTorch dataset of attribute-value combinations with optional one-hot encoding and configurable repetition multiplier', 'generate random 2D points on a unit disk with both Cartesian and polar coordinate representations', 'review the AttributeValueData and SphereData classes to understand their PyTorch dataset interface and data generation logic', 'run the discrete communication game training with identity or rotated language and autoenc loss', 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for receiver output', 'run get_params to parse command-line arguments for receiver hidden size, cell layers, and loss type', 'review the DiffLoss class that supports autoenc, mixed, and linear loss types for compositional efficiency', 'review the main function that sets up sender, receiver, game, optimizer, and trainer for training']
```

Usage

```
{'run_continuous_game': 'run the compositional efficiency continuous sender receiver game with configurable receiver and sender parameters', 'get_params_continuous': 'get parsed command line arguments for the continuous game including receiver hidden size and cell type', 'diff_loss_mse': 'compute the MSE loss between receiver output and sender input for the continuous communication game', 'create_circle_sender': 'create a CircleSender with optional Lenses transformation for the continuous compositional efficiency game', 'train_rnn_receiver': 'train an RNN receiver with LSTM or tree cell using reinforcement learning in the continuous game'}
```

## File: facebookresearch_egg/egg/zoo/compositional_efficiency/dataset.py

Prompts

```
['build a Receiver neural network module with configurable hidden layers and output dimensions', 'create an IdentitySender module that passes input messages through unchanged with offset', 'create a RotatedSender module that encodes sum and difference of input attributes', 'create a Lenses module that rotates input examples using a configurable theta angle', 'create a CircleSender module that maps continuous values in [-1,1] to discrete vocabulary tokens', 'run the compositional efficiency continuous sender receiver game with configurable receiver and sender parameters', 'get parsed command line arguments for the continuous game including receiver hidden size and cell type', 'compute the MSE loss between receiver output and sender input for the continuous communication game', 'create a CircleSender with optional Lenses transformation for the continuous compositional efficiency game', 'train an RNN receiver with LSTM or tree cell using reinforcement learning in the continuous game', 'generate all combinations of attribute values and split into train or test sets using hash-based filtering', 'convert a list of attribute value configurations into one-hot encoded PyTorch tensors for each configuration', 'create a PyTorch dataset of attribute-value combinations with optional one-hot encoding and configurable repetition multiplier', 'generate random 2D points on a unit disk with both Cartesian and polar coordinate representations', 'review the AttributeValueData and SphereData classes to understand their PyTorch dataset interface and data generation logic', 'run the discrete communication game training with identity or rotated language and autoenc loss', 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for receiver output', 'run get_params to parse command-line arguments for receiver hidden size, cell layers, and loss type', 'review the DiffLoss class that supports autoenc, mixed, and linear loss types for compositional efficiency', 'review the main function that sets up sender, receiver, game, optimizer, and trainer for training']
```

Usage

```
{'enumerate_attribute_value': 'generate all combinations of attribute values and split into train or test sets using hash-based filtering', 'one_hotify': 'convert a list of attribute value configurations into one-hot encoded PyTorch tensors for each configuration', 'AttributeValueData': 'create a PyTorch dataset of attribute-value combinations with optional one-hot encoding and configurable repetition multiplier', 'SphereData': 'generate random 2D points on a unit disk with both Cartesian and polar coordinate representations', 'review_dataset_classes': 'review the AttributeValueData and SphereData classes to understand their PyTorch dataset interface and data generation logic'}
```

## File: facebookresearch_egg/egg/zoo/compositional_efficiency/discrete.py

Prompts

```
['build a Receiver neural network module with configurable hidden layers and output dimensions', 'create an IdentitySender module that passes input messages through unchanged with offset', 'create a RotatedSender module that encodes sum and difference of input attributes', 'create a Lenses module that rotates input examples using a configurable theta angle', 'create a CircleSender module that maps continuous values in [-1,1] to discrete vocabulary tokens', 'run the compositional efficiency continuous sender receiver game with configurable receiver and sender parameters', 'get parsed command line arguments for the continuous game including receiver hidden size and cell type', 'compute the MSE loss between receiver output and sender input for the continuous communication game', 'create a CircleSender with optional Lenses transformation for the continuous compositional efficiency game', 'train an RNN receiver with LSTM or tree cell using reinforcement learning in the continuous game', 'generate all combinations of attribute values and split into train or test sets using hash-based filtering', 'convert a list of attribute value configurations into one-hot encoded PyTorch tensors for each configuration', 'create a PyTorch dataset of attribute-value combinations with optional one-hot encoding and configurable repetition multiplier', 'generate random 2D points on a unit disk with both Cartesian and polar coordinate representations', 'review the AttributeValueData and SphereData classes to understand their PyTorch dataset interface and data generation logic', 'run the discrete communication game training with identity or rotated language and autoenc loss', 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for receiver output', 'run get_params to parse command-line arguments for receiver hidden size, cell layers, and loss type', 'review the DiffLoss class that supports autoenc, mixed, and linear loss types for compositional efficiency', 'review the main function that sets up sender, receiver, game, optimizer, and trainer for training']
```

Usage

```
{'run_discrete_training': 'run the discrete communication game training with identity or rotated language and autoenc loss', 'run_diffloss_forward': 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for receiver output', 'run_get_params': 'run get_params to parse command-line arguments for receiver hidden size, cell layers, and loss type', 'review_DiffLoss_class': 'review the DiffLoss class that supports autoenc, mixed, and linear loss types for compositional efficiency', 'review_main_function': 'review the main function that sets up sender, receiver, game, optimizer, and trainer for training'}
```

