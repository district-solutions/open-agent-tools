# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/simple_autoenc/archs.py

Prompts

```
['build a Receiver nn.Module that maps hidden features back to original feature dimensions', 'build a Sender nn.Module that projects input features down to a hidden bottleneck representation', 'test the Receiver forward pass by passing hidden tensors and verifying output shape', 'test the Sender forward pass by passing input tensors and verifying hidden output shape', 'review the Sender and Receiver classes to understand the simple autoencoder bottleneck architecture', 'run the simple autoencoder training loop with reinforce or gumbel softmax mode via argparse cli', 'parse command line arguments for sender receiver hidden sizes learning rates and training mode', 'compute cross entropy loss and accuracy between receiver output and sender input tensors', 'train a sender receiver game using EGG framework with configurable RNN cell types and entropy coefficients', 'review the main function to understand reinforce and gumbel softmax training mode branching logic']
```

Usage

```
{'build_receiver_module': 'build a Receiver nn.Module that maps hidden features back to original feature dimensions', 'build_sender_module': 'build a Sender nn.Module that projects input features down to a hidden bottleneck representation', 'test_receiver_forward': 'test the Receiver forward pass by passing hidden tensors and verifying output shape', 'test_sender_forward': 'test the Sender forward pass by passing input tensors and verifying hidden output shape', 'review_sender_receiver_arch': 'review the Sender and Receiver classes to understand the simple autoencoder bottleneck architecture'}
```

## File: facebookresearch_egg/egg/zoo/simple_autoenc/train.py

Prompts

```
['build a Receiver nn.Module that maps hidden features back to original feature dimensions', 'build a Sender nn.Module that projects input features down to a hidden bottleneck representation', 'test the Receiver forward pass by passing hidden tensors and verifying output shape', 'test the Sender forward pass by passing input tensors and verifying hidden output shape', 'review the Sender and Receiver classes to understand the simple autoencoder bottleneck architecture', 'run the simple autoencoder training loop with reinforce or gumbel softmax mode via argparse cli', 'parse command line arguments for sender receiver hidden sizes learning rates and training mode', 'compute cross entropy loss and accuracy between receiver output and sender input tensors', 'train a sender receiver game using EGG framework with configurable RNN cell types and entropy coefficients', 'review the main function to understand reinforce and gumbel softmax training mode branching logic']
```

Usage

```
{'run_simple_autoenc_training': 'run the simple autoencoder training loop with reinforce or gumbel softmax mode via argparse cli', 'get_params_parse_args': 'parse command line arguments for sender receiver hidden sizes learning rates and training mode', 'loss_compute_cross_entropy': 'compute cross entropy loss and accuracy between receiver output and sender input tensors', 'main_train_sender_receiver': 'train a sender receiver game using EGG framework with configurable RNN cell types and entropy coefficients', 'review_main_training_modes': 'review the main function to understand reinforce and gumbel softmax training mode branching logic'}
```

