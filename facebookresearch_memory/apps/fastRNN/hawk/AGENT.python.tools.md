# Agent Python Tools

- repo: facebookresearch/memory
- repo_uri: https://github.com/facebookresearch/memory

## File: facebookresearch_memory/apps/fastRNN/hawk/core_hawk.py

Prompts

```
['build a BaseHawk RNN model from BaseHawkArgs config and initialize weights with init_weights', 'create an RGLRUBlock module with gated RGLRU recurrence and output projection for sequence processing', 'run the RGLRU forward pass with input tensor, sequence lengths, and parallel or sequential impl mode', 'review the SqrtBoundDerivative custom autograd function that clips sqrt gradients to prevent explosion', 'test the HawkBlock layer combining RGLRUBlock recurrence with FeedForward and RMSNorm residual connections', 'build a LMHawk language model using LMHawkArgs with vocab size and weight tying config', 'create a LMHawkArgs dataclass config with vocab size, seed, and loss reduction settings', 'run the LMHawk forward pass with token values and optional target tensor for loss', 'reset the LMHawk model parameters using trunc normal initialization with custom init std', 'get the set of torch ops to exclude from gradient checkpointing recomputation']
```

Usage

```
{'build_BaseHawk_model': 'build a BaseHawk RNN model from BaseHawkArgs config and initialize weights with init_weights', 'create_RGLRUBlock_module': 'create an RGLRUBlock module with gated RGLRU recurrence and output projection for sequence processing', 'run_RGLRU_forward': 'run the RGLRU forward pass with input tensor, sequence lengths, and parallel or sequential impl mode', 'review_SqrtBoundDerivative_custom_autograd': 'review the SqrtBoundDerivative custom autograd function that clips sqrt gradients to prevent explosion', 'test_HawkBlock_layer': 'test the HawkBlock layer combining RGLRUBlock recurrence with FeedForward and RMSNorm residual connections'}
```

## File: facebookresearch_memory/apps/fastRNN/hawk/hawk.py

Prompts

```
['build a BaseHawk RNN model from BaseHawkArgs config and initialize weights with init_weights', 'create an RGLRUBlock module with gated RGLRU recurrence and output projection for sequence processing', 'run the RGLRU forward pass with input tensor, sequence lengths, and parallel or sequential impl mode', 'review the SqrtBoundDerivative custom autograd function that clips sqrt gradients to prevent explosion', 'test the HawkBlock layer combining RGLRUBlock recurrence with FeedForward and RMSNorm residual connections', 'build a LMHawk language model using LMHawkArgs with vocab size and weight tying config', 'create a LMHawkArgs dataclass config with vocab size, seed, and loss reduction settings', 'run the LMHawk forward pass with token values and optional target tensor for loss', 'reset the LMHawk model parameters using trunc normal initialization with custom init std', 'get the set of torch ops to exclude from gradient checkpointing recomputation']
```

Usage

```
{'build_LMHawk_model': 'build a LMHawk language model using LMHawkArgs with vocab size and weight tying config', 'create_LMHawkArgs_config': 'create a LMHawkArgs dataclass config with vocab size, seed, and loss reduction settings', 'run_LMHawk_forward': 'run the LMHawk forward pass with token values and optional target tensor for loss', 'reset_LMHawk_parameters': 'reset the LMHawk model parameters using trunc normal initialization with custom init std', 'get_no_recompute_ops': 'get the set of torch ops to exclude from gradient checkpointing recomputation'}
```

