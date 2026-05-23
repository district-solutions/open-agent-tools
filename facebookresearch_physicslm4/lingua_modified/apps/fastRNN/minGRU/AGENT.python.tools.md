# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/minGRU/core_gru.py

Prompts

```
['build a BaseMinGRU model with configurable dim, n_layers, and n_heads using BaseMinGRUArgs', 'create a GRU layer with linear projections for gate z, candidate hidden state, and output', 'run a GRUBlock forward pass with RMSNorm and residual connection around the GRU layer', 'test the sequential_step function that computes a times states plus b for RNN recurrence', 'review the GRU reset_parameters method that initializes weights with truncated normal distribution', 'build a language model using LMMinGRU with token embeddings, RMSNorm, and configurable weight tying', 'create a StateCache module to manage convolution and hidden state buffers for MinGRU inference', 'run the LMMinGRU forward pass on token values to get logits or cross-entropy loss', 'reset LMMinGRU model parameters using truncated normal initialization with configurable standard deviation', 'get the set of torch operations that should not be recomputed during gradient checkpointing']
```

Usage

```
{'build_minGRU_model': 'build a BaseMinGRU model with configurable dim, n_layers, and n_heads using BaseMinGRUArgs', 'create_GRU_layer': 'create a GRU layer with linear projections for gate z, candidate hidden state, and output', 'run_GRUBlock_forward': 'run a GRUBlock forward pass with RMSNorm and residual connection around the GRU layer', 'test_sequential_step': 'test the sequential_step function that computes a times states plus b for RNN recurrence', 'review_GRU_reset_parameters': 'review the GRU reset_parameters method that initializes weights with truncated normal distribution'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/minGRU/mingru.py

Prompts

```
['build a BaseMinGRU model with configurable dim, n_layers, and n_heads using BaseMinGRUArgs', 'create a GRU layer with linear projections for gate z, candidate hidden state, and output', 'run a GRUBlock forward pass with RMSNorm and residual connection around the GRU layer', 'test the sequential_step function that computes a times states plus b for RNN recurrence', 'review the GRU reset_parameters method that initializes weights with truncated normal distribution', 'build a language model using LMMinGRU with token embeddings, RMSNorm, and configurable weight tying', 'create a StateCache module to manage convolution and hidden state buffers for MinGRU inference', 'run the LMMinGRU forward pass on token values to get logits or cross-entropy loss', 'reset LMMinGRU model parameters using truncated normal initialization with configurable standard deviation', 'get the set of torch operations that should not be recomputed during gradient checkpointing']
```

Usage

```
{'build_LMMinGRU_model': 'build a language model using LMMinGRU with token embeddings, RMSNorm, and configurable weight tying', 'create_StateCache_module': 'create a StateCache module to manage convolution and hidden state buffers for MinGRU inference', 'run_LMMinGRU_forward': 'run the LMMinGRU forward pass on token values to get logits or cross-entropy loss', 'reset_LMMinGRU_parameters': 'reset LMMinGRU model parameters using truncated normal initialization with configurable standard deviation', 'get_no_recompute_ops': 'get the set of torch operations that should not be recomputed during gradient checkpointing'}
```

