# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/net_builder/value/fully_connected.py

Prompts

```
['build a fully connected value network using FullyConnected with custom sizes and activations', 'create a FullyConnected value net builder with default layer sizes 256 and 128', 'configure the FullyConnected builder to use layer normalization for value network training', 'validate that sizes and activations lists have matching lengths in FullyConnected initialization', 'get the state dimension from normalization data to build a FloatFeatureFullyConnected network', 'build a Seq2RewardNetwork using Seq2RewardNetBuilder with state normalization data', 'create a Seq2RewardNetBuilder with custom action_dim, num_hiddens, and num_hidden_layers', 'review the build_value_network method to understand how state_dim is extracted from normalization data', 'refactor Seq2RewardNetBuilder to support additional hyperparameters for the Seq2RewardNetwork', 'test Seq2RewardNetBuilder by instantiating it and calling build_value_network with mock NormalizationData']
```

Usage

```
{'build_value_network': 'build a fully connected value network using FullyConnected with custom sizes and activations', 'create_fully_connected_builder': 'create a FullyConnected value net builder with default layer sizes 256 and 128', 'configure_layer_norm': 'configure the FullyConnected builder to use layer normalization for value network training', 'validate_sizes_activations': 'validate that sizes and activations lists have matching lengths in FullyConnected initialization', 'get_state_dim': 'get the state dimension from normalization data to build a FloatFeatureFullyConnected network'}
```

## File: facebookresearch_reagent/reagent/net_builder/value/seq2reward_rnn.py

Prompts

```
['build a fully connected value network using FullyConnected with custom sizes and activations', 'create a FullyConnected value net builder with default layer sizes 256 and 128', 'configure the FullyConnected builder to use layer normalization for value network training', 'validate that sizes and activations lists have matching lengths in FullyConnected initialization', 'get the state dimension from normalization data to build a FloatFeatureFullyConnected network', 'build a Seq2RewardNetwork using Seq2RewardNetBuilder with state normalization data', 'create a Seq2RewardNetBuilder with custom action_dim, num_hiddens, and num_hidden_layers', 'review the build_value_network method to understand how state_dim is extracted from normalization data', 'refactor Seq2RewardNetBuilder to support additional hyperparameters for the Seq2RewardNetwork', 'test Seq2RewardNetBuilder by instantiating it and calling build_value_network with mock NormalizationData']
```

Usage

```
{'build_seq2reward_network': 'build a Seq2RewardNetwork using Seq2RewardNetBuilder with state normalization data', 'create_seq2reward_net_builder': 'create a Seq2RewardNetBuilder with custom action_dim, num_hiddens, and num_hidden_layers', 'review_build_value_network': 'review the build_value_network method to understand how state_dim is extracted from normalization data', 'refactor_seq2reward_net_builder': 'refactor Seq2RewardNetBuilder to support additional hyperparameters for the Seq2RewardNetwork', 'test_seq2reward_net_builder': 'test Seq2RewardNetBuilder by instantiating it and calling build_value_network with mock NormalizationData'}
```

