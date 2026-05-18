# Agent Python Tools

- repo: facebookresearch/minimax
- repo_uri: https://github.com/facebookresearch/minimax

## File: facebookresearch_minimax/src/minimax/models/common.py

Prompts

```
['build a Flax ScannedRNN module with LSTM or GRU cells and reset-aware time-major scanning', 'create a ValueHead neural network module with configurable hidden layers, activation, and orthogonal kernel init', 'build an EnsembleValueHead that vmaps multiple ValueHead modules to produce ensemble value predictions', 'create a stack of fully connected Flax Dense layers with optional layernorm and activation functions', 'review the RecurrentModuleBase class to understand LSTM and GRU carry initialization patterns', 'register a model with an env_group_id, model_id, and entry_point in the global registry', 'make a model instance by looking up a registered model using env_name and model_name', 'load a module and attribute from a colon-separated entry_point string using importlib', 'get the composite registration ID string from an env_group_id and model_id', 'review the global registered_models dictionary to inspect all registered model entry points', 'build a python module to create an S5 encoder stack with make_s5_encoder_stack for sequence modeling', 'create a Flax S5SSM module with HiPPO-initialized eigenvalues and configurable discretization method', 'test the discretize_zoh function to verify zero-order hold discretization of diagonalized SSM matrices', 'refactor the apply_ssm function to support custom reset logic in the parallel scan operation', 'review the SequenceLayer class to understand how S5 SSM integrates with GLU activations and layer norm']
```

Usage

```
{'build_scanned_rnn': 'build a Flax ScannedRNN module with LSTM or GRU cells and reset-aware time-major scanning', 'create_value_head': 'create a ValueHead neural network module with configurable hidden layers, activation, and orthogonal kernel init', 'build_ensemble_value_head': 'build an EnsembleValueHead that vmaps multiple ValueHead modules to produce ensemble value predictions', 'create_fc_layers': 'create a stack of fully connected Flax Dense layers with optional layernorm and activation functions', 'review_recurrent_module_base': 'review the RecurrentModuleBase class to understand LSTM and GRU carry initialization patterns'}
```

## File: facebookresearch_minimax/src/minimax/models/registration.py

Prompts

```
['build a Flax ScannedRNN module with LSTM or GRU cells and reset-aware time-major scanning', 'create a ValueHead neural network module with configurable hidden layers, activation, and orthogonal kernel init', 'build an EnsembleValueHead that vmaps multiple ValueHead modules to produce ensemble value predictions', 'create a stack of fully connected Flax Dense layers with optional layernorm and activation functions', 'review the RecurrentModuleBase class to understand LSTM and GRU carry initialization patterns', 'register a model with an env_group_id, model_id, and entry_point in the global registry', 'make a model instance by looking up a registered model using env_name and model_name', 'load a module and attribute from a colon-separated entry_point string using importlib', 'get the composite registration ID string from an env_group_id and model_id', 'review the global registered_models dictionary to inspect all registered model entry points', 'build a python module to create an S5 encoder stack with make_s5_encoder_stack for sequence modeling', 'create a Flax S5SSM module with HiPPO-initialized eigenvalues and configurable discretization method', 'test the discretize_zoh function to verify zero-order hold discretization of diagonalized SSM matrices', 'refactor the apply_ssm function to support custom reset logic in the parallel scan operation', 'review the SequenceLayer class to understand how S5 SSM integrates with GLU activations and layer norm']
```

Usage

```
{'register_model': 'register a model with an env_group_id, model_id, and entry_point in the global registry', 'make_model': 'make a model instance by looking up a registered model using env_name and model_name', 'load_entry_point': 'load a module and attribute from a colon-separated entry_point string using importlib', 'get_register_id': 'get the composite registration ID string from an env_group_id and model_id', 'review_registered_models': 'review the global registered_models dictionary to inspect all registered model entry points'}
```

## File: facebookresearch_minimax/src/minimax/models/s5.py

Prompts

```
['build a Flax ScannedRNN module with LSTM or GRU cells and reset-aware time-major scanning', 'create a ValueHead neural network module with configurable hidden layers, activation, and orthogonal kernel init', 'build an EnsembleValueHead that vmaps multiple ValueHead modules to produce ensemble value predictions', 'create a stack of fully connected Flax Dense layers with optional layernorm and activation functions', 'review the RecurrentModuleBase class to understand LSTM and GRU carry initialization patterns', 'register a model with an env_group_id, model_id, and entry_point in the global registry', 'make a model instance by looking up a registered model using env_name and model_name', 'load a module and attribute from a colon-separated entry_point string using importlib', 'get the composite registration ID string from an env_group_id and model_id', 'review the global registered_models dictionary to inspect all registered model entry points', 'build a python module to create an S5 encoder stack with make_s5_encoder_stack for sequence modeling', 'create a Flax S5SSM module with HiPPO-initialized eigenvalues and configurable discretization method', 'test the discretize_zoh function to verify zero-order hold discretization of diagonalized SSM matrices', 'refactor the apply_ssm function to support custom reset logic in the parallel scan operation', 'review the SequenceLayer class to understand how S5 SSM integrates with GLU activations and layer norm']
```

Usage

```
{'build_s5_encoder_stack': 'build a python module to create an S5 encoder stack with make_s5_encoder_stack for sequence modeling', 'create_s5ssm_module': 'create a Flax S5SSM module with HiPPO-initialized eigenvalues and configurable discretization method', 'test_discretize_zoh': 'test the discretize_zoh function to verify zero-order hold discretization of diagonalized SSM matrices', 'refactor_apply_ssm': 'refactor the apply_ssm function to support custom reset logic in the parallel scan operation', 'review_sequence_layer': 'review the SequenceLayer class to understand how S5 SSM integrates with GLU activations and layer norm'}
```

