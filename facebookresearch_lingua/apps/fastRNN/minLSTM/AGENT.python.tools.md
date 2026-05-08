# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/fastRNN/minLSTM/core_lstm.py

Prompts

```
['build a BaseMinLSTM model with configurable dim, n_layers, and n_heads using BaseMinLSTMArgs', 'create an LSTM layer with linear projections, optional conv1d, and scan-based state recurrence', 'run the LSTM forward pass with token indices and cumulative sequence lengths for parallel or sequential impl', 'review the LSTM reset_parameters method that initializes weights with trunc_normal based on init_std and factor', 'test the LSTMBlock forward pass that applies RMSNorm then adds LSTM output as a residual connection', 'run the LMMinLSTM forward pass with token values and optional target tensor for loss computation', 'create an LMMinLSTMArgs dataclass to configure vocab size, weight tying, seed, and loss reduction', 'reset LMMinLSTM model parameters using trunc normal initialization with configurable init standard deviation', 'get the set of torch ops to exclude from gradient checkpointing recomputation for minLSTM']
```

Usage

```
{'build_minlstm_model': 'build a BaseMinLSTM model with configurable dim, n_layers, and n_heads using BaseMinLSTMArgs', 'create_lstm_layer': 'create an LSTM layer with linear projections, optional conv1d, and scan-based state recurrence', 'run_lstm_forward': 'run the LSTM forward pass with token indices and cumulative sequence lengths for parallel or sequential impl', 'review_lstm_reset_parameters': 'review the LSTM reset_parameters method that initializes weights with trunc_normal based on init_std and factor', 'test_lstmblock_residual': 'test the LSTMBlock forward pass that applies RMSNorm then adds LSTM output as a residual connection'}
```

## File: facebookresearch_lingua/apps/fastRNN/minLSTM/minlstm.py

Prompts

```
['build a BaseMinLSTM model with configurable dim, n_layers, and n_heads using BaseMinLSTMArgs', 'create an LSTM layer with linear projections, optional conv1d, and scan-based state recurrence', 'run the LSTM forward pass with token indices and cumulative sequence lengths for parallel or sequential impl', 'review the LSTM reset_parameters method that initializes weights with trunc_normal based on init_std and factor', 'test the LSTMBlock forward pass that applies RMSNorm then adds LSTM output as a residual connection', 'run the LMMinLSTM forward pass with token values and optional target tensor for loss computation', 'create an LMMinLSTMArgs dataclass to configure vocab size, weight tying, seed, and loss reduction', 'reset LMMinLSTM model parameters using trunc normal initialization with configurable init standard deviation', 'get the set of torch ops to exclude from gradient checkpointing recomputation for minLSTM']
```

Usage

```
{'build_minlstm_model': 'build a language model using LMMinLSTM with LMMinLSTMArgs for vocab size and weight tying config', 'run_minlstm_forward': 'run the LMMinLSTM forward pass with token values and optional target tensor for loss computation', 'create_minlstm_args': 'create an LMMinLSTMArgs dataclass to configure vocab size, weight tying, seed, and loss reduction', 'reset_minlstm_parameters': 'reset LMMinLSTM model parameters using trunc normal initialization with configurable init standard deviation', 'get_no_recompute_ops': 'get the set of torch ops to exclude from gradient checkpointing recomputation for minLSTM'}
```

