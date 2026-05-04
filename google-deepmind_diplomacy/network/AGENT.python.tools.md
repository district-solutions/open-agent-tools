# Agent Python Tools

- repo: google-deepmind/diplomacy
- repo_uri: https://github.com/google-deepmind/diplomacy

## File: google-deepmind_diplomacy/network/config.py

Prompts

```
['get the default network configuration ConfigDict for the Diplomacy reference checkpoint', 'review the get_config function to understand the network architecture hyperparameters and RNN settings', 'summarize the get_config function and its network_kwargs including filter sizes and core counts', 'refactor the get_config function to parameterize the number of players or map type', 'test the get_config function to verify it returns a valid ConfigDict with all expected network_kwargs keys', 'build a python module that computes the symmetric normalized Laplacian of a map adjacency matrix', 'create a Haiku module that performs one round of graph message passing with non-shared weights across nodes', 'build a Haiku module that encodes Diplomacy board state with shared and player-specific graph network layers', 'create a Haiku RNNCore that outputs order logits for a Diplomacy unit based on board representation and previous decisions', 'run the full Diplomacy network inference to compute value estimates and action logits for all units in a turn', 'create a Policy agent with a network handler, player count, and sampling temperature', 'reset the Policy agent observation transform state and network handler state', 'compute actions for player slots using observations and legal actions via the Policy agent', 'configure the Policy agent to calculate policies for all players regardless of slot list', 'inspect the Policy agent string representation showing its sampling temperature configuration', 'fix a list of Diplomacy actions so at most one waive appears at the end', 'sanitize network action outputs for all powers to be compatible with game runners', 'apply a batched function to unbatched arguments by expanding and squeezing tree dimensions', 'load serialized network parameters, state, and step count from a file handle using dill', 'run batched or unbatched inference on a Diplomacy observation using a JAX network policy']
```

Usage

```
{'get_network_config': 'get the default network configuration ConfigDict for the Diplomacy reference checkpoint', 'review_get_config': 'review the get_config function to understand the network architecture hyperparameters and RNN settings', 'summarize_get_config': 'summarize the get_config function and its network_kwargs including filter sizes and core counts', 'refactor_get_config': 'refactor the get_config function to parameterize the number of players or map type', 'test_get_config': 'test the get_config function to verify it returns a valid ConfigDict with all expected network_kwargs keys'}
```

## File: google-deepmind_diplomacy/network/network.py

Prompts

```
['get the default network configuration ConfigDict for the Diplomacy reference checkpoint', 'review the get_config function to understand the network architecture hyperparameters and RNN settings', 'summarize the get_config function and its network_kwargs including filter sizes and core counts', 'refactor the get_config function to parameterize the number of players or map type', 'test the get_config function to verify it returns a valid ConfigDict with all expected network_kwargs keys', 'build a python module that computes the symmetric normalized Laplacian of a map adjacency matrix', 'create a Haiku module that performs one round of graph message passing with non-shared weights across nodes', 'build a Haiku module that encodes Diplomacy board state with shared and player-specific graph network layers', 'create a Haiku RNNCore that outputs order logits for a Diplomacy unit based on board representation and previous decisions', 'run the full Diplomacy network inference to compute value estimates and action logits for all units in a turn', 'create a Policy agent with a network handler, player count, and sampling temperature', 'reset the Policy agent observation transform state and network handler state', 'compute actions for player slots using observations and legal actions via the Policy agent', 'configure the Policy agent to calculate policies for all players regardless of slot list', 'inspect the Policy agent string representation showing its sampling temperature configuration', 'fix a list of Diplomacy actions so at most one waive appears at the end', 'sanitize network action outputs for all powers to be compatible with game runners', 'apply a batched function to unbatched arguments by expanding and squeezing tree dimensions', 'load serialized network parameters, state, and step count from a file handle using dill', 'run batched or unbatched inference on a Diplomacy observation using a JAX network policy']
```

Usage

```
{'build_normalize_adjacency': 'build a python module that computes the symmetric normalized Laplacian of a map adjacency matrix', 'create_encoder_core': 'create a Haiku module that performs one round of graph message passing with non-shared weights across nodes', 'build_board_encoder': 'build a Haiku module that encodes Diplomacy board state with shared and player-specific graph network layers', 'create_relational_order_decoder': 'create a Haiku RNNCore that outputs order logits for a Diplomacy unit based on board representation and previous decisions', 'run_network_inference': 'run the full Diplomacy network inference to compute value estimates and action logits for all units in a turn'}
```

## File: google-deepmind_diplomacy/network/network_policy.py

Prompts

```
['get the default network configuration ConfigDict for the Diplomacy reference checkpoint', 'review the get_config function to understand the network architecture hyperparameters and RNN settings', 'summarize the get_config function and its network_kwargs including filter sizes and core counts', 'refactor the get_config function to parameterize the number of players or map type', 'test the get_config function to verify it returns a valid ConfigDict with all expected network_kwargs keys', 'build a python module that computes the symmetric normalized Laplacian of a map adjacency matrix', 'create a Haiku module that performs one round of graph message passing with non-shared weights across nodes', 'build a Haiku module that encodes Diplomacy board state with shared and player-specific graph network layers', 'create a Haiku RNNCore that outputs order logits for a Diplomacy unit based on board representation and previous decisions', 'run the full Diplomacy network inference to compute value estimates and action logits for all units in a turn', 'create a Policy agent with a network handler, player count, and sampling temperature', 'reset the Policy agent observation transform state and network handler state', 'compute actions for player slots using observations and legal actions via the Policy agent', 'configure the Policy agent to calculate policies for all players regardless of slot list', 'inspect the Policy agent string representation showing its sampling temperature configuration', 'fix a list of Diplomacy actions so at most one waive appears at the end', 'sanitize network action outputs for all powers to be compatible with game runners', 'apply a batched function to unbatched arguments by expanding and squeezing tree dimensions', 'load serialized network parameters, state, and step count from a file handle using dill', 'run batched or unbatched inference on a Diplomacy observation using a JAX network policy']
```

Usage

```
{'create_policy_agent': 'create a Policy agent with a network handler, player count, and sampling temperature', 'reset_policy_state': 'reset the Policy agent observation transform state and network handler state', 'compute_policy_actions': 'compute actions for player slots using observations and legal actions via the Policy agent', 'configure_all_policies': 'configure the Policy agent to calculate policies for all players regardless of slot list', 'inspect_policy_string': 'inspect the Policy agent string representation showing its sampling temperature configuration'}
```

## File: google-deepmind_diplomacy/network/parameter_provider.py

Prompts

```
['get the default network configuration ConfigDict for the Diplomacy reference checkpoint', 'review the get_config function to understand the network architecture hyperparameters and RNN settings', 'summarize the get_config function and its network_kwargs including filter sizes and core counts', 'refactor the get_config function to parameterize the number of players or map type', 'test the get_config function to verify it returns a valid ConfigDict with all expected network_kwargs keys', 'build a python module that computes the symmetric normalized Laplacian of a map adjacency matrix', 'create a Haiku module that performs one round of graph message passing with non-shared weights across nodes', 'build a Haiku module that encodes Diplomacy board state with shared and player-specific graph network layers', 'create a Haiku RNNCore that outputs order logits for a Diplomacy unit based on board representation and previous decisions', 'run the full Diplomacy network inference to compute value estimates and action logits for all units in a turn', 'create a Policy agent with a network handler, player count, and sampling temperature', 'reset the Policy agent observation transform state and network handler state', 'compute actions for player slots using observations and legal actions via the Policy agent', 'configure the Policy agent to calculate policies for all players regardless of slot list', 'inspect the Policy agent string representation showing its sampling temperature configuration', 'fix a list of Diplomacy actions so at most one waive appears at the end', 'sanitize network action outputs for all powers to be compatible with game runners', 'apply a batched function to unbatched arguments by expanding and squeezing tree dimensions', 'load serialized network parameters, state, and step count from a file handle using dill', 'run batched or unbatched inference on a Diplomacy observation using a JAX network policy']
```

Usage

```
{'fix_waives_action_list': 'fix a list of Diplomacy actions so at most one waive appears at the end', 'fix_actions_network_outputs': 'sanitize network action outputs for all powers to be compatible with game runners', 'apply_unbatched_function': 'apply a batched function to unbatched arguments by expanding and squeezing tree dimensions', 'ParameterProvider_load_params': 'load serialized network parameters, state, and step count from a file handle using dill', 'SequenceNetworkHandler_inference': 'run batched or unbatched inference on a Diplomacy observation using a JAX network policy'}
```

