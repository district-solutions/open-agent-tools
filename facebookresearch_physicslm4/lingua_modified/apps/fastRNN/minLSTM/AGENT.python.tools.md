# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/minLSTM/core_lstm.py

Prompts

```
['build a BaseMinLSTM model from BaseMinLSTMArgs config and call init_weights to initialize all layer parameters', 'create an LSTM layer with configurable dim, hidden_dim, n_heads, and optional conv_size for causal convolution', 'run the LSTM forward pass with input tensor, tok_idx, cu_seqlens and impl mode parallel or sequential', 'review the LSTMBlock class that wraps an LSTM layer with RMSNorm and residual skip connection', 'test the LSTM reset_parameters method to verify trunc_normal initialization with configurable init_std and factor', 'create a LMMinLSTM language model with token embeddings and configurable weight tying', 'build a LMMinLSTMArgs dataclass to configure vocab size, seed, and loss reduction settings', 'run a forward pass on token values through the LMMinLSTM model to get logits or loss', 'reset LMMinLSTM model parameters using truncated normal initialization with configurable standard deviation', 'get the set of torch operations excluded from gradient checkpointing recomputation']
```

Usage

```
{'build_BaseMinLSTM_model': 'build a BaseMinLSTM model from BaseMinLSTMArgs config and call init_weights to initialize all layer parameters', 'create_LSTM_layer': 'create an LSTM layer with configurable dim, hidden_dim, n_heads, and optional conv_size for causal convolution', 'run_LSTM_forward': 'run the LSTM forward pass with input tensor, tok_idx, cu_seqlens and impl mode parallel or sequential', 'review_LSTMBlock_residual': 'review the LSTMBlock class that wraps an LSTM layer with RMSNorm and residual skip connection', 'test_reset_parameters': 'test the LSTM reset_parameters method to verify trunc_normal initialization with configurable init_std and factor'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/minLSTM/minlstm.py

Prompts

```
['build a BaseMinLSTM model from BaseMinLSTMArgs config and call init_weights to initialize all layer parameters', 'create an LSTM layer with configurable dim, hidden_dim, n_heads, and optional conv_size for causal convolution', 'run the LSTM forward pass with input tensor, tok_idx, cu_seqlens and impl mode parallel or sequential', 'review the LSTMBlock class that wraps an LSTM layer with RMSNorm and residual skip connection', 'test the LSTM reset_parameters method to verify trunc_normal initialization with configurable init_std and factor', 'create a LMMinLSTM language model with token embeddings and configurable weight tying', 'build a LMMinLSTMArgs dataclass to configure vocab size, seed, and loss reduction settings', 'run a forward pass on token values through the LMMinLSTM model to get logits or loss', 'reset LMMinLSTM model parameters using truncated normal initialization with configurable standard deviation', 'get the set of torch operations excluded from gradient checkpointing recomputation']
```

Usage

```
{'create_lm_min_lstm_model': 'create a LMMinLSTM language model with token embeddings and configurable weight tying', 'build_min_lstm_args_config': 'build a LMMinLSTMArgs dataclass to configure vocab size, seed, and loss reduction settings', 'run_forward_pass': 'run a forward pass on token values through the LMMinLSTM model to get logits or loss', 'reset_model_parameters': 'reset LMMinLSTM model parameters using truncated normal initialization with configurable standard deviation', 'get_no_recompute_ops': 'get the set of torch operations excluded from gradient checkpointing recomputation'}
```

