# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/channel/archs.py

Prompts

```
['create a Receiver nn.Module with n_features and n_hidden to decode channel messages via a linear layer', 'create a Sender nn.Module with n_hidden and n_features to encode inputs into channel messages via a linear layer', 'build a communication channel architecture using Sender and Receiver modules for multi-agent learning with PyTorch', 'review the Receiver forward method that takes hidden state x and returns decoded output through a linear layer', 'review the Sender forward method that encodes input features into hidden representations via a linear layer', 'run the channel game training loop with sender and receiver agents using CLI arguments', 'run get_params to parse CLI arguments for sender receiver hidden sizes and cell types', 'run the loss function to compute cross entropy and accuracy between receiver output and sender input', 'run dump to evaluate a trained game on uniform and powerlaw concept distributions', 'run main to configure train and test loaders build agents and start training with callbacks']
```

Usage

```
{'create_receiver_module': 'create a Receiver nn.Module with n_features and n_hidden to decode channel messages via a linear layer', 'create_sender_module': 'create a Sender nn.Module with n_hidden and n_features to encode inputs into channel messages via a linear layer', 'build_channel_architecture': 'build a communication channel architecture using Sender and Receiver modules for multi-agent learning with PyTorch', 'review_receiver_forward': 'review the Receiver forward method that takes hidden state x and returns decoded output through a linear layer', 'review_sender_forward': 'review the Sender forward method that encodes input features into hidden representations via a linear layer'}
```

## File: facebookresearch_egg/egg/zoo/channel/train.py

Prompts

```
['create a Receiver nn.Module with n_features and n_hidden to decode channel messages via a linear layer', 'create a Sender nn.Module with n_hidden and n_features to encode inputs into channel messages via a linear layer', 'build a communication channel architecture using Sender and Receiver modules for multi-agent learning with PyTorch', 'review the Receiver forward method that takes hidden state x and returns decoded output through a linear layer', 'review the Sender forward method that encodes input features into hidden representations via a linear layer', 'run the channel game training loop with sender and receiver agents using CLI arguments', 'run get_params to parse CLI arguments for sender receiver hidden sizes and cell types', 'run the loss function to compute cross entropy and accuracy between receiver output and sender input', 'run dump to evaluate a trained game on uniform and powerlaw concept distributions', 'run main to configure train and test loaders build agents and start training with callbacks']
```

Usage

```
{'run_channel_training': 'run the channel game training loop with sender and receiver agents using CLI arguments', 'run_get_params': 'run get_params to parse CLI arguments for sender receiver hidden sizes and cell types', 'run_loss': 'run the loss function to compute cross entropy and accuracy between receiver output and sender input', 'run_dump': 'run dump to evaluate a trained game on uniform and powerlaw concept distributions', 'run_main': 'run main to configure train and test loaders build agents and start training with callbacks'}
```

