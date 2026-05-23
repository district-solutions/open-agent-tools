# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/hawk/core_hawk.py

Prompts

```
['build a BaseHawk RNN model from BaseHawkArgs config and call init_weights to initialize parameters', 'create an RGLRUBlock module with gated linear units and recursive LRU for sequence processing', 'test the RGLRU forward pass with token indices and cumulative sequence lengths', 'review the SqrtBoundDerivative autograd function that clips sqrt gradients to prevent explosion', 'summarize the HawkBlock architecture combining RGLRU recurrence with feed-forward and RMSNorm layers', 'create an LMHawkArgs dataclass to configure vocab size, weight tying, seed, and loss reduction for the Hawk language model', 'build an LMHawk language model with token embeddings, RMSNorm, and optional weight tying for next token prediction', 'run the LMHawk forward pass with token values and optional targets to get logits or cross entropy loss', 'test the LMHawk reset_parameters method to reinitialize token embeddings and output weights with truncated normal distribution', 'review the get_no_recompute_ops function that returns a set of torch operations to skip during gradient checkpointing recomputation']
```

Usage

```
{'build_BaseHawk_model': 'build a BaseHawk RNN model from BaseHawkArgs config and call init_weights to initialize parameters', 'create_RGLRUBlock_module': 'create an RGLRUBlock module with gated linear units and recursive LRU for sequence processing', 'test_RGLRU_forward': 'test the RGLRU forward pass with token indices and cumulative sequence lengths', 'review_SqrtBoundDerivative_autograd': 'review the SqrtBoundDerivative autograd function that clips sqrt gradients to prevent explosion', 'summarize_HawkBlock_architecture': 'summarize the HawkBlock architecture combining RGLRU recurrence with feed-forward and RMSNorm layers'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/hawk/hawk.py

Prompts

```
['build a BaseHawk RNN model from BaseHawkArgs config and call init_weights to initialize parameters', 'create an RGLRUBlock module with gated linear units and recursive LRU for sequence processing', 'test the RGLRU forward pass with token indices and cumulative sequence lengths', 'review the SqrtBoundDerivative autograd function that clips sqrt gradients to prevent explosion', 'summarize the HawkBlock architecture combining RGLRU recurrence with feed-forward and RMSNorm layers', 'create an LMHawkArgs dataclass to configure vocab size, weight tying, seed, and loss reduction for the Hawk language model', 'build an LMHawk language model with token embeddings, RMSNorm, and optional weight tying for next token prediction', 'run the LMHawk forward pass with token values and optional targets to get logits or cross entropy loss', 'test the LMHawk reset_parameters method to reinitialize token embeddings and output weights with truncated normal distribution', 'review the get_no_recompute_ops function that returns a set of torch operations to skip during gradient checkpointing recomputation']
```

Usage

```
{'create_LMHawkArgs_dataclass': 'create an LMHawkArgs dataclass to configure vocab size, weight tying, seed, and loss reduction for the Hawk language model', 'build_LMHawk_model': 'build an LMHawk language model with token embeddings, RMSNorm, and optional weight tying for next token prediction', 'run_LMHawk_forward': 'run the LMHawk forward pass with token values and optional targets to get logits or cross entropy loss', 'test_LMHawk_reset_parameters': 'test the LMHawk reset_parameters method to reinitialize token embeddings and output weights with truncated normal distribution', 'review_get_no_recompute_ops': 'review the get_no_recompute_ops function that returns a set of torch operations to skip during gradient checkpointing recomputation'}
```

