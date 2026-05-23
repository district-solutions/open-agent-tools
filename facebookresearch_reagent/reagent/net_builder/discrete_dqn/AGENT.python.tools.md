# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/net_builder/discrete_dqn/dueling.py

Prompts

```
['build a Dueling Q-network with custom hidden layer sizes and activation functions for discrete DQN', 'create a Dueling net builder instance with default 256 and 128 hidden layer sizes', 'review the Dueling class post-init validation that ensures sizes and activations lists match in length', 'refactor the Dueling net builder to support different activation functions beyond relu for hidden layers', 'summarize the Dueling DQN architecture that separates state value and advantage estimation in the Q-network', 'build a FullyConnected DQN network with custom layer sizes and activation functions', 'configure the FullyConnected net builder with custom hidden layer sizes and activation types', 'review the FullyConnected class post-init validation that checks sizes and activations list lengths match', 'refactor the FullyConnected net builder to enable batch normalization across all hidden layers', 'summarize the build_q_network method that constructs a FullyConnectedDQN model from state and output dimensions', 'build a Q-network using FullyConnectedWithEmbedding with state feature config, normalization data, and output dimension', 'create a FullyConnectedWithEmbedding net builder with custom layer sizes, activations, and dropout ratio', 'configure an EmbeddingBagConcat model by passing state dense dimension and model feature config', 'review the FullyConnectedDQN model with specified sizes, activations, and dropout ratio for DQN training', 'validate that the sizes and activations lists have matching lengths in FullyConnectedWithEmbedding']
```

Usage

```
{'build_dueling_q_network': 'build a Dueling Q-network with custom hidden layer sizes and activation functions for discrete DQN', 'create_dueling_net_builder': 'create a Dueling net builder instance with default 256 and 128 hidden layer sizes', 'review_dueling_validation': 'review the Dueling class post-init validation that ensures sizes and activations lists match in length', 'refactor_dueling_activations': 'refactor the Dueling net builder to support different activation functions beyond relu for hidden layers', 'summarize_dueling_architecture': 'summarize the Dueling DQN architecture that separates state value and advantage estimation in the Q-network'}
```

## File: facebookresearch_reagent/reagent/net_builder/discrete_dqn/fully_connected.py

Prompts

```
['build a Dueling Q-network with custom hidden layer sizes and activation functions for discrete DQN', 'create a Dueling net builder instance with default 256 and 128 hidden layer sizes', 'review the Dueling class post-init validation that ensures sizes and activations lists match in length', 'refactor the Dueling net builder to support different activation functions beyond relu for hidden layers', 'summarize the Dueling DQN architecture that separates state value and advantage estimation in the Q-network', 'build a FullyConnected DQN network with custom layer sizes and activation functions', 'configure the FullyConnected net builder with custom hidden layer sizes and activation types', 'review the FullyConnected class post-init validation that checks sizes and activations list lengths match', 'refactor the FullyConnected net builder to enable batch normalization across all hidden layers', 'summarize the build_q_network method that constructs a FullyConnectedDQN model from state and output dimensions', 'build a Q-network using FullyConnectedWithEmbedding with state feature config, normalization data, and output dimension', 'create a FullyConnectedWithEmbedding net builder with custom layer sizes, activations, and dropout ratio', 'configure an EmbeddingBagConcat model by passing state dense dimension and model feature config', 'review the FullyConnectedDQN model with specified sizes, activations, and dropout ratio for DQN training', 'validate that the sizes and activations lists have matching lengths in FullyConnectedWithEmbedding']
```

Usage

```
{'build_fully_connected_dqn_network': 'build a FullyConnected DQN network with custom layer sizes and activation functions', 'configure_fully_connected_sizes': 'configure the FullyConnected net builder with custom hidden layer sizes and activation types', 'review_fully_connected_validation': 'review the FullyConnected class post-init validation that checks sizes and activations list lengths match', 'refactor_fully_connected_batch_norm': 'refactor the FullyConnected net builder to enable batch normalization across all hidden layers', 'summarize_build_q_network': 'summarize the build_q_network method that constructs a FullyConnectedDQN model from state and output dimensions'}
```

## File: facebookresearch_reagent/reagent/net_builder/discrete_dqn/fully_connected_with_embedding.py

Prompts

```
['build a Dueling Q-network with custom hidden layer sizes and activation functions for discrete DQN', 'create a Dueling net builder instance with default 256 and 128 hidden layer sizes', 'review the Dueling class post-init validation that ensures sizes and activations lists match in length', 'refactor the Dueling net builder to support different activation functions beyond relu for hidden layers', 'summarize the Dueling DQN architecture that separates state value and advantage estimation in the Q-network', 'build a FullyConnected DQN network with custom layer sizes and activation functions', 'configure the FullyConnected net builder with custom hidden layer sizes and activation types', 'review the FullyConnected class post-init validation that checks sizes and activations list lengths match', 'refactor the FullyConnected net builder to enable batch normalization across all hidden layers', 'summarize the build_q_network method that constructs a FullyConnectedDQN model from state and output dimensions', 'build a Q-network using FullyConnectedWithEmbedding with state feature config, normalization data, and output dimension', 'create a FullyConnectedWithEmbedding net builder with custom layer sizes, activations, and dropout ratio', 'configure an EmbeddingBagConcat model by passing state dense dimension and model feature config', 'review the FullyConnectedDQN model with specified sizes, activations, and dropout ratio for DQN training', 'validate that the sizes and activations lists have matching lengths in FullyConnectedWithEmbedding']
```

Usage

```
{'build_q_network': 'build a Q-network using FullyConnectedWithEmbedding with state feature config, normalization data, and output dimension', 'create_fully_connected_with_embedding': 'create a FullyConnectedWithEmbedding net builder with custom layer sizes, activations, and dropout ratio', 'configure_embedding_bag_concat': 'configure an EmbeddingBagConcat model by passing state dense dimension and model feature config', 'review_fully_connected_dqn': 'review the FullyConnectedDQN model with specified sizes, activations, and dropout ratio for DQN training', 'validate_sizes_activations': 'validate that the sizes and activations lists have matching lengths in FullyConnectedWithEmbedding'}
```

