# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/language_bottleneck/guess_number/archs.py

Prompts

```
['create a Receiver neural network module that predicts bits from an embedded message and input bits', 'create a ReinforcedReceiver module that samples bits using a Bernoulli distribution with log probability and entropy', 'create a Sender neural network module that generates a message from input bits', 'review the Receiver forward pass that concatenates embedded bits with message and applies leaky relu then sigmoid', 'test the ReinforcedReceiver forward pass that samples during training and thresholds during evaluation', 'create a function that splits binary examples into sender and receiver tensors with masked bits', 'build a one-hot iterator that generates random binary batches with sender and receiver masks', 'build a PyTorch DataLoader that yields random one-hot encoded batches with configurable bit masking', 'build a PyTorch DataLoader that enumerates all binary combinations as sender and receiver examples', 'test the sender_receiver_examples function to verify sender and receiver bit masking logic', 'run the guess number language bottleneck training with GumbelSoftmax or Reinforce mode via CLI', 'get training parameters like n_bits, hidden sizes, learning rates, and entropy coefficients', 'compute differentiable binary cross entropy loss and accuracy for the receiver output', 'compute non-differentiable accuracy-based loss for reinforcement learning training', 'orchestrate sender receiver game setup optimizer and trainer with early stopping callbacks']
```

Usage

```
{'create_receiver_model': 'create a Receiver neural network module that predicts bits from an embedded message and input bits', 'create_reinforced_receiver_model': 'create a ReinforcedReceiver module that samples bits using a Bernoulli distribution with log probability and entropy', 'create_sender_model': 'create a Sender neural network module that generates a message from input bits', 'review_receiver_forward': 'review the Receiver forward pass that concatenates embedded bits with message and applies leaky relu then sigmoid', 'test_reinforced_receiver_training': 'test the ReinforcedReceiver forward pass that samples during training and thresholds during evaluation'}
```

## File: facebookresearch_egg/egg/zoo/language_bottleneck/guess_number/features.py

Prompts

```
['create a Receiver neural network module that predicts bits from an embedded message and input bits', 'create a ReinforcedReceiver module that samples bits using a Bernoulli distribution with log probability and entropy', 'create a Sender neural network module that generates a message from input bits', 'review the Receiver forward pass that concatenates embedded bits with message and applies leaky relu then sigmoid', 'test the ReinforcedReceiver forward pass that samples during training and thresholds during evaluation', 'create a function that splits binary examples into sender and receiver tensors with masked bits', 'build a one-hot iterator that generates random binary batches with sender and receiver masks', 'build a PyTorch DataLoader that yields random one-hot encoded batches with configurable bit masking', 'build a PyTorch DataLoader that enumerates all binary combinations as sender and receiver examples', 'test the sender_receiver_examples function to verify sender and receiver bit masking logic', 'run the guess number language bottleneck training with GumbelSoftmax or Reinforce mode via CLI', 'get training parameters like n_bits, hidden sizes, learning rates, and entropy coefficients', 'compute differentiable binary cross entropy loss and accuracy for the receiver output', 'compute non-differentiable accuracy-based loss for reinforcement learning training', 'orchestrate sender receiver game setup optimizer and trainer with early stopping callbacks']
```

Usage

```
{'create_sender_receiver_examples': 'create a function that splits binary examples into sender and receiver tensors with masked bits', 'build_OneHotIterator': 'build a one-hot iterator that generates random binary batches with sender and receiver masks', 'build_OneHotLoader': 'build a PyTorch DataLoader that yields random one-hot encoded batches with configurable bit masking', 'build_UniformLoader': 'build a PyTorch DataLoader that enumerates all binary combinations as sender and receiver examples', 'test_sender_receiver_examples': 'test the sender_receiver_examples function to verify sender and receiver bit masking logic'}
```

## File: facebookresearch_egg/egg/zoo/language_bottleneck/guess_number/train.py

Prompts

```
['create a Receiver neural network module that predicts bits from an embedded message and input bits', 'create a ReinforcedReceiver module that samples bits using a Bernoulli distribution with log probability and entropy', 'create a Sender neural network module that generates a message from input bits', 'review the Receiver forward pass that concatenates embedded bits with message and applies leaky relu then sigmoid', 'test the ReinforcedReceiver forward pass that samples during training and thresholds during evaluation', 'create a function that splits binary examples into sender and receiver tensors with masked bits', 'build a one-hot iterator that generates random binary batches with sender and receiver masks', 'build a PyTorch DataLoader that yields random one-hot encoded batches with configurable bit masking', 'build a PyTorch DataLoader that enumerates all binary combinations as sender and receiver examples', 'test the sender_receiver_examples function to verify sender and receiver bit masking logic', 'run the guess number language bottleneck training with GumbelSoftmax or Reinforce mode via CLI', 'get training parameters like n_bits, hidden sizes, learning rates, and entropy coefficients', 'compute differentiable binary cross entropy loss and accuracy for the receiver output', 'compute non-differentiable accuracy-based loss for reinforcement learning training', 'orchestrate sender receiver game setup optimizer and trainer with early stopping callbacks']
```

Usage

```
{'run_train_guess_number': 'run the guess number language bottleneck training with GumbelSoftmax or Reinforce mode via CLI', 'get_params_training_config': 'get training parameters like n_bits, hidden sizes, learning rates, and entropy coefficients', 'diff_loss_bce': 'compute differentiable binary cross entropy loss and accuracy for the receiver output', 'non_diff_loss_accuracy': 'compute non-differentiable accuracy-based loss for reinforcement learning training', 'main_orchestrate_training': 'orchestrate sender receiver game setup optimizer and trainer with early stopping callbacks'}
```

