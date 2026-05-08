# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/simultaneous_translation/utils/functions.py

Prompts

```
['run prob_check on a PyTorch tensor to validate it contains valid probability values', 'run exclusive_cumprod on a PyTorch tensor along a specified dimension to get exclusive cumulative product', 'run safe_cumprod on a non-negative PyTorch tensor to compute numerically stable cumulative product', 'run moving_sum on a 3D tensor with start and end indices to compute a sliding window sum', 'review the simultaneous translation utility functions module for prob_check, exclusive_cumprod, safe_cumprod, and moving_sum', 'compute the expected alignment tensor from stepwise probability using monotonic alignment enforcement', 'compute expected soft attention for monotonic infinite lookback from alignment and soft energy tensors', 'compute expected soft attention using monotonic chunkwise attention with a specified chunk size', 'apply mass preservation to assign residual alignment weights to the last source token', 'apply mass preservation with right padding to scatter residual weights to the last valid token', 'build a wait-k policy matrix tensor for simultaneous translation with a fixed lagging offset', 'create step-wise read and write probabilities from an energy tensor using sigmoid activation', 'test the waitk_p_choose function with a given target length, source length, batch size, and wait-k lagging value', 'test the learnable_p_choose function with an energy tensor and configurable noise parameters during training', 'review the waitk_p_choose function and its handling of left padding via key_padding_mask']
```

Usage

```
{'run_prob_check': 'run prob_check on a PyTorch tensor to validate it contains valid probability values', 'run_exclusive_cumprod': 'run exclusive_cumprod on a PyTorch tensor along a specified dimension to get exclusive cumulative product', 'run_safe_cumprod': 'run safe_cumprod on a non-negative PyTorch tensor to compute numerically stable cumulative product', 'run_moving_sum': 'run moving_sum on a 3D tensor with start and end indices to compute a sliding window sum', 'review_functions_module': 'review the simultaneous translation utility functions module for prob_check, exclusive_cumprod, safe_cumprod, and moving_sum'}
```

## File: facebookresearch_fairseq/examples/simultaneous_translation/utils/monotonic_attention.py

Prompts

```
['run prob_check on a PyTorch tensor to validate it contains valid probability values', 'run exclusive_cumprod on a PyTorch tensor along a specified dimension to get exclusive cumulative product', 'run safe_cumprod on a non-negative PyTorch tensor to compute numerically stable cumulative product', 'run moving_sum on a 3D tensor with start and end indices to compute a sliding window sum', 'review the simultaneous translation utility functions module for prob_check, exclusive_cumprod, safe_cumprod, and moving_sum', 'compute the expected alignment tensor from stepwise probability using monotonic alignment enforcement', 'compute expected soft attention for monotonic infinite lookback from alignment and soft energy tensors', 'compute expected soft attention using monotonic chunkwise attention with a specified chunk size', 'apply mass preservation to assign residual alignment weights to the last source token', 'apply mass preservation with right padding to scatter residual weights to the last valid token', 'build a wait-k policy matrix tensor for simultaneous translation with a fixed lagging offset', 'create step-wise read and write probabilities from an energy tensor using sigmoid activation', 'test the waitk_p_choose function with a given target length, source length, batch size, and wait-k lagging value', 'test the learnable_p_choose function with an energy tensor and configurable noise parameters during training', 'review the waitk_p_choose function and its handling of left padding via key_padding_mask']
```

Usage

```
{'compute_expected_alignment_from_p_choose': 'compute the expected alignment tensor from stepwise probability using monotonic alignment enforcement', 'compute_expected_soft_attention': 'compute expected soft attention for monotonic infinite lookback from alignment and soft energy tensors', 'compute_expected_soft_attention_chunkwise': 'compute expected soft attention using monotonic chunkwise attention with a specified chunk size', 'apply_mass_preservation': 'apply mass preservation to assign residual alignment weights to the last source token', 'apply_mass_preservation_right_padding': 'apply mass preservation with right padding to scatter residual weights to the last valid token'}
```

## File: facebookresearch_fairseq/examples/simultaneous_translation/utils/p_choose_strategy.py

Prompts

```
['run prob_check on a PyTorch tensor to validate it contains valid probability values', 'run exclusive_cumprod on a PyTorch tensor along a specified dimension to get exclusive cumulative product', 'run safe_cumprod on a non-negative PyTorch tensor to compute numerically stable cumulative product', 'run moving_sum on a 3D tensor with start and end indices to compute a sliding window sum', 'review the simultaneous translation utility functions module for prob_check, exclusive_cumprod, safe_cumprod, and moving_sum', 'compute the expected alignment tensor from stepwise probability using monotonic alignment enforcement', 'compute expected soft attention for monotonic infinite lookback from alignment and soft energy tensors', 'compute expected soft attention using monotonic chunkwise attention with a specified chunk size', 'apply mass preservation to assign residual alignment weights to the last source token', 'apply mass preservation with right padding to scatter residual weights to the last valid token', 'build a wait-k policy matrix tensor for simultaneous translation with a fixed lagging offset', 'create step-wise read and write probabilities from an energy tensor using sigmoid activation', 'test the waitk_p_choose function with a given target length, source length, batch size, and wait-k lagging value', 'test the learnable_p_choose function with an energy tensor and configurable noise parameters during training', 'review the waitk_p_choose function and its handling of left padding via key_padding_mask']
```

Usage

```
{'build_waitk_policy_matrix': 'build a wait-k policy matrix tensor for simultaneous translation with a fixed lagging offset', 'create_learnable_p_choose': 'create step-wise read and write probabilities from an energy tensor using sigmoid activation', 'test_waitk_p_choose': 'test the waitk_p_choose function with a given target length, source length, batch size, and wait-k lagging value', 'test_learnable_p_choose': 'test the learnable_p_choose function with an energy tensor and configurable noise parameters during training', 'review_waitk_p_choose_padding': 'review the waitk_p_choose function and its handling of left padding via key_padding_mask'}
```

