# Agent Python Tools

- repo: facebookresearch/memory
- repo_uri: https://github.com/facebookresearch/memory

## File: facebookresearch_memory/apps/fastRNN/minLSTM/core_lstm.py

Prompts

```
['build a BaseMinLSTM model with configurable dim, n_layers, and n_heads using BaseMinLSTMArgs', 'create an LSTM layer with linear projections for forget/input gates and state scan operations', 'run an LSTMBlock forward pass with RMSNorm and residual connection on input tensor', 'review the LSTM reset_parameters method that initializes weights with truncated normal distribution', 'test the BaseMinLSTM init_weights method that sets layer weights using depth-based scaling factors', 'build a LMMinLSTM language model from LMMinLSTMArgs with vocab size and weight tying config', 'create a LMMinLSTMArgs dataclass with vocab size, weight tying, seed, and loss reduction settings', 'run a forward pass on token values through LMMinLSTM to get logits or cross entropy loss', 'reset LMMinLSTM model parameters using trunc normal initialization with configurable init std', 'get the set of torch ops to exclude from gradient checkpointing recomputation']
```

Usage

```
{'build_BaseMinLSTM_model': 'build a BaseMinLSTM model with configurable dim, n_layers, and n_heads using BaseMinLSTMArgs', 'create_LSTM_layer': 'create an LSTM layer with linear projections for forget/input gates and state scan operations', 'run_LSTMBlock_forward': 'run an LSTMBlock forward pass with RMSNorm and residual connection on input tensor', 'review_LSTM_reset_parameters': 'review the LSTM reset_parameters method that initializes weights with truncated normal distribution', 'test_BaseMinLSTM_init_weights': 'test the BaseMinLSTM init_weights method that sets layer weights using depth-based scaling factors'}
```

## File: facebookresearch_memory/apps/fastRNN/minLSTM/minlstm.py

Prompts

```
['build a BaseMinLSTM model with configurable dim, n_layers, and n_heads using BaseMinLSTMArgs', 'create an LSTM layer with linear projections for forget/input gates and state scan operations', 'run an LSTMBlock forward pass with RMSNorm and residual connection on input tensor', 'review the LSTM reset_parameters method that initializes weights with truncated normal distribution', 'test the BaseMinLSTM init_weights method that sets layer weights using depth-based scaling factors', 'build a LMMinLSTM language model from LMMinLSTMArgs with vocab size and weight tying config', 'create a LMMinLSTMArgs dataclass with vocab size, weight tying, seed, and loss reduction settings', 'run a forward pass on token values through LMMinLSTM to get logits or cross entropy loss', 'reset LMMinLSTM model parameters using trunc normal initialization with configurable init std', 'get the set of torch ops to exclude from gradient checkpointing recomputation']
```

Usage

```
{'build_lm_min_lstm_model': 'build a LMMinLSTM language model from LMMinLSTMArgs with vocab size and weight tying config', 'create_lm_min_lstm_args': 'create a LMMinLSTMArgs dataclass with vocab size, weight tying, seed, and loss reduction settings', 'run_forward_pass': 'run a forward pass on token values through LMMinLSTM to get logits or cross entropy loss', 'reset_lm_min_lstm_parameters': 'reset LMMinLSTM model parameters using trunc normal initialization with configurable init std', 'get_no_recompute_ops': 'get the set of torch ops to exclude from gradient checkpointing recomputation'}
```

