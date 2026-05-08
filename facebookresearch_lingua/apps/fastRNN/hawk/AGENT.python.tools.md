# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/fastRNN/hawk/core_hawk.py

Prompts

```
['build a BaseHawk RNN model using BaseHawkArgs to configure dim, n_layers, and n_heads', 'create an RGLRU gated recurrence module with configurable heads, head_dim, and optional conv_size', 'create an RGLRUBlock that combines RGLRU recurrence with gated output and residual connections', 'test the HawkBlock forward pass combining RGLRU and feed-forward layers with RMSNorm', 'review the SqrtBoundDerivative autograd function that clips sqrt gradients to prevent explosion', 'build a LMHawk language model using LMHawkArgs with vocab size and weight tying config', 'create LMHawkArgs dataclass with vocab size, weight tying, seed, and loss reduction settings', 'run the LMHawk forward pass with token values and optional target tensor for loss', 'reset LMHawk model parameters using trunc normal init with configurable standard deviation', 'get the set of torch ops to exclude from gradient checkpointing recomputation']
```

Usage

```
{'build_BaseHawk_model': 'build a BaseHawk RNN model using BaseHawkArgs to configure dim, n_layers, and n_heads', 'create_RGLRU_module': 'create an RGLRU gated recurrence module with configurable heads, head_dim, and optional conv_size', 'create_RGLRUBlock_module': 'create an RGLRUBlock that combines RGLRU recurrence with gated output and residual connections', 'test_HawkBlock_forward': 'test the HawkBlock forward pass combining RGLRU and feed-forward layers with RMSNorm', 'review_sqrt_bounded_derivative': 'review the SqrtBoundDerivative autograd function that clips sqrt gradients to prevent explosion'}
```

## File: facebookresearch_lingua/apps/fastRNN/hawk/hawk.py

Prompts

```
['build a BaseHawk RNN model using BaseHawkArgs to configure dim, n_layers, and n_heads', 'create an RGLRU gated recurrence module with configurable heads, head_dim, and optional conv_size', 'create an RGLRUBlock that combines RGLRU recurrence with gated output and residual connections', 'test the HawkBlock forward pass combining RGLRU and feed-forward layers with RMSNorm', 'review the SqrtBoundDerivative autograd function that clips sqrt gradients to prevent explosion', 'build a LMHawk language model using LMHawkArgs with vocab size and weight tying config', 'create LMHawkArgs dataclass with vocab size, weight tying, seed, and loss reduction settings', 'run the LMHawk forward pass with token values and optional target tensor for loss', 'reset LMHawk model parameters using trunc normal init with configurable standard deviation', 'get the set of torch ops to exclude from gradient checkpointing recomputation']
```

Usage

```
{'build_lm_hawk_model': 'build a LMHawk language model using LMHawkArgs with vocab size and weight tying config', 'create_lm_hawk_args': 'create LMHawkArgs dataclass with vocab size, weight tying, seed, and loss reduction settings', 'run_lm_hawk_forward': 'run the LMHawk forward pass with token values and optional target tensor for loss', 'reset_lm_hawk_parameters': 'reset LMHawk model parameters using trunc normal init with configurable standard deviation', 'get_no_recompute_ops': 'get the set of torch ops to exclude from gradient checkpointing recomputation'}
```

