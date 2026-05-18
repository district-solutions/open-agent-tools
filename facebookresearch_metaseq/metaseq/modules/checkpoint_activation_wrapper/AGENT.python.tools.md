# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/modules/checkpoint_activation_wrapper/checkpoint_activations.py

Prompts

```
['wrap a PyTorch nn.Module with activation checkpointing to reduce GPU memory usage during training', 'use a context manager to temporarily disable activation checkpointing for a code block', 'check whether the current forward pass is running under activation checkpointing', 'check whether the current forward pass is recomputing activations during the backward pass', 'use a custom autograd Function to perform activation checkpointing with non-Tensor output support']
```

Usage

```
{'checkpoint_wrapper': 'wrap a PyTorch nn.Module with activation checkpointing to reduce GPU memory usage during training', 'disable_checkpointing': 'use a context manager to temporarily disable activation checkpointing for a code block', 'is_checkpointing': 'check whether the current forward pass is running under activation checkpointing', 'is_recomputing': 'check whether the current forward pass is recomputing activations during the backward pass', 'CheckpointFunction': 'use a custom autograd Function to perform activation checkpointing with non-Tensor output support'}
```

