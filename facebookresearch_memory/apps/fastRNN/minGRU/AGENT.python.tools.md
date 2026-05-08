# Agent Python Tools

- repo: facebookresearch/memory
- repo_uri: https://github.com/facebookresearch/memory

## File: facebookresearch_memory/apps/fastRNN/minGRU/core_gru.py

Prompts

```
['build a BaseMinGRU model with configurable dim, n_layers, and n_heads using BaseMinGRUArgs', 'create a GRU layer with linear projections, optional conv1d, and recurrent scan for sequence processing', 'create a GRUBlock with RMSNorm and residual connection wrapping a GRU layer', 'run a forward pass through the GRU module with parallel or sequential scan implementation', 'initialize BaseMinGRU weights using trunc_normal with depth-based or dim-ratio scaling factors', 'build a language model using LMMinGRU with LMMinGRUArgs config including vocab size and weight tying', 'create a StateCache module to store convolution and hidden state tensors for autoregressive decoding', 'run the LMMinGRU forward pass with token values and optional targets to get logits or loss', 'reset LMMinGRU model parameters using trunc normal initialization with configurable init standard deviation', 'get the set of torch ops to exclude from gradient checkpointing recomputation including mm and scan ops']
```

Usage

```
{'build_minGRU_model': 'build a BaseMinGRU model with configurable dim, n_layers, and n_heads using BaseMinGRUArgs', 'create_GRU_layer': 'create a GRU layer with linear projections, optional conv1d, and recurrent scan for sequence processing', 'create_GRUBlock_with_residual': 'create a GRUBlock with RMSNorm and residual connection wrapping a GRU layer', 'run_GRU_forward_pass': 'run a forward pass through the GRU module with parallel or sequential scan implementation', 'init_minGRU_weights': 'initialize BaseMinGRU weights using trunc_normal with depth-based or dim-ratio scaling factors'}
```

## File: facebookresearch_memory/apps/fastRNN/minGRU/mingru.py

Prompts

```
['build a BaseMinGRU model with configurable dim, n_layers, and n_heads using BaseMinGRUArgs', 'create a GRU layer with linear projections, optional conv1d, and recurrent scan for sequence processing', 'create a GRUBlock with RMSNorm and residual connection wrapping a GRU layer', 'run a forward pass through the GRU module with parallel or sequential scan implementation', 'initialize BaseMinGRU weights using trunc_normal with depth-based or dim-ratio scaling factors', 'build a language model using LMMinGRU with LMMinGRUArgs config including vocab size and weight tying', 'create a StateCache module to store convolution and hidden state tensors for autoregressive decoding', 'run the LMMinGRU forward pass with token values and optional targets to get logits or loss', 'reset LMMinGRU model parameters using trunc normal initialization with configurable init standard deviation', 'get the set of torch ops to exclude from gradient checkpointing recomputation including mm and scan ops']
```

Usage

```
{'build_lm_min_gru_model': 'build a language model using LMMinGRU with LMMinGRUArgs config including vocab size and weight tying', 'create_state_cache': 'create a StateCache module to store convolution and hidden state tensors for autoregressive decoding', 'run_lm_min_gru_forward': 'run the LMMinGRU forward pass with token values and optional targets to get logits or loss', 'reset_lm_min_gru_parameters': 'reset LMMinGRU model parameters using trunc normal initialization with configurable init standard deviation', 'get_no_recompute_ops': 'get the set of torch ops to exclude from gradient checkpointing recomputation including mm and scan ops'}
```

