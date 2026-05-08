# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/fastRNN/minGRU/core_gru.py

Prompts

```
['build a BaseMinGRU model with configurable dim, n_layers, and n_heads using BaseMinGRUArgs', 'create a GRU layer with linear projections for gate, candidate hidden state, and output', 'run the GRU forward pass with token indices and cumulative sequence lengths for parallel or sequential mode', 'test the GRUBlock forward pass that applies RMSNorm and adds residual connection around the GRU layer', 'review the sequential_step function that computes a times states plus b for RNN state updates', 'build a language model using LMMinGRU with token embeddings, RMSNorm, and optional weight tying', 'create a StateCache module to store convolution and hidden state tensors for autoregressive decoding', 'run the LMMinGRU forward pass on token values to get logits or cross-entropy loss', 'reset LMMinGRU model parameters using truncated normal initialization with configurable standard deviation', 'get the set of torch operations to exclude from gradient checkpointing recomputation']
```

Usage

```
{'build_minGRU_model': 'build a BaseMinGRU model with configurable dim, n_layers, and n_heads using BaseMinGRUArgs', 'create_GRU_layer': 'create a GRU layer with linear projections for gate, candidate hidden state, and output', 'run_GRU_forward': 'run the GRU forward pass with token indices and cumulative sequence lengths for parallel or sequential mode', 'test_GRUBlock_residual': 'test the GRUBlock forward pass that applies RMSNorm and adds residual connection around the GRU layer', 'review_sequential_step': 'review the sequential_step function that computes a times states plus b for RNN state updates'}
```

## File: facebookresearch_lingua/apps/fastRNN/minGRU/mingru.py

Prompts

```
['build a BaseMinGRU model with configurable dim, n_layers, and n_heads using BaseMinGRUArgs', 'create a GRU layer with linear projections for gate, candidate hidden state, and output', 'run the GRU forward pass with token indices and cumulative sequence lengths for parallel or sequential mode', 'test the GRUBlock forward pass that applies RMSNorm and adds residual connection around the GRU layer', 'review the sequential_step function that computes a times states plus b for RNN state updates', 'build a language model using LMMinGRU with token embeddings, RMSNorm, and optional weight tying', 'create a StateCache module to store convolution and hidden state tensors for autoregressive decoding', 'run the LMMinGRU forward pass on token values to get logits or cross-entropy loss', 'reset LMMinGRU model parameters using truncated normal initialization with configurable standard deviation', 'get the set of torch operations to exclude from gradient checkpointing recomputation']
```

Usage

```
{'build_lm_min_gru_model': 'build a language model using LMMinGRU with token embeddings, RMSNorm, and optional weight tying', 'create_state_cache': 'create a StateCache module to store convolution and hidden state tensors for autoregressive decoding', 'run_lm_min_gru_forward': 'run the LMMinGRU forward pass on token values to get logits or cross-entropy loss', 'reset_lm_min_gru_parameters': 'reset LMMinGRU model parameters using truncated normal initialization with configurable standard deviation', 'get_no_recompute_ops': 'get the set of torch operations to exclude from gradient checkpointing recomputation'}
```

