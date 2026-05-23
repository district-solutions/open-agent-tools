# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/nn/utils/test_grad.py

Prompts

```
['test that scale_grad correctly scales gradients by the specified factor during backpropagation', 'test that scale_grad raises a TypeError when passed a non-float tensor', 'run scale_grad on a PyTorch tensor to scale its gradient by a given factor', 'review the scale_grad function and its custom autograd Function for gradient scaling behavior', 'summarize the gradient utility tests covering scale_grad correctness and type validation', 'test compute_row_mask generates a boolean mask tensor with the expected shape and dtype', 'test compute_row_mask with custom row_lens to verify per-row length masking works correctly', 'test compute_row_mask raises ValueError when row_lens contains values smaller than span_len', 'refactor compute_row_mask to support a different masking strategy or additional parameters', 'review apply_mask to understand how boolean masks are applied to sequence tensors', 'test select_parameters to filter model parameters by regex pattern names', 'test select_parameters with exclude mode to filter out matching parameters', 'run select_parameters on an NLLB model to find encoder decoder attention layer norm biases', 'run get_nllb_model_hub to create and configure an NLLB dense 1b model', 'review select_parameters usage for including or excluding model parameters by regex']
```

Usage

```
{'test_scale_grad_scales_gradient_correctly': 'test that scale_grad correctly scales gradients by the specified factor during backpropagation', 'test_scale_grad_raises_error_if_tensor_is_non_float': 'test that scale_grad raises a TypeError when passed a non-float tensor', 'run_scale_grad_on_tensor': 'run scale_grad on a PyTorch tensor to scale its gradient by a given factor', 'review_scale_grad_implementation': 'review the scale_grad function and its custom autograd Function for gradient scaling behavior', 'summarize_grad_utils_test': 'summarize the gradient utility tests covering scale_grad correctness and type validation'}
```

## File: facebookresearch_fairseq2/tests/unit/nn/utils/test_mask.py

Prompts

```
['test that scale_grad correctly scales gradients by the specified factor during backpropagation', 'test that scale_grad raises a TypeError when passed a non-float tensor', 'run scale_grad on a PyTorch tensor to scale its gradient by a given factor', 'review the scale_grad function and its custom autograd Function for gradient scaling behavior', 'summarize the gradient utility tests covering scale_grad correctness and type validation', 'test compute_row_mask generates a boolean mask tensor with the expected shape and dtype', 'test compute_row_mask with custom row_lens to verify per-row length masking works correctly', 'test compute_row_mask raises ValueError when row_lens contains values smaller than span_len', 'refactor compute_row_mask to support a different masking strategy or additional parameters', 'review apply_mask to understand how boolean masks are applied to sequence tensors', 'test select_parameters to filter model parameters by regex pattern names', 'test select_parameters with exclude mode to filter out matching parameters', 'run select_parameters on an NLLB model to find encoder decoder attention layer norm biases', 'run get_nllb_model_hub to create and configure an NLLB dense 1b model', 'review select_parameters usage for including or excluding model parameters by regex']
```

Usage

```
{'test_compute_row_mask': 'test compute_row_mask generates a boolean mask tensor with the expected shape and dtype', 'test_compute_row_mask_with_row_lens': 'test compute_row_mask with custom row_lens to verify per-row length masking works correctly', 'test_compute_row_mask_error_handling': 'test compute_row_mask raises ValueError when row_lens contains values smaller than span_len', 'refactor_compute_row_mask': 'refactor compute_row_mask to support a different masking strategy or additional parameters', 'review_apply_mask': 'review apply_mask to understand how boolean masks are applied to sequence tensors'}
```

## File: facebookresearch_fairseq2/tests/unit/nn/utils/test_module.py

Prompts

```
['test that scale_grad correctly scales gradients by the specified factor during backpropagation', 'test that scale_grad raises a TypeError when passed a non-float tensor', 'run scale_grad on a PyTorch tensor to scale its gradient by a given factor', 'review the scale_grad function and its custom autograd Function for gradient scaling behavior', 'summarize the gradient utility tests covering scale_grad correctness and type validation', 'test compute_row_mask generates a boolean mask tensor with the expected shape and dtype', 'test compute_row_mask with custom row_lens to verify per-row length masking works correctly', 'test compute_row_mask raises ValueError when row_lens contains values smaller than span_len', 'refactor compute_row_mask to support a different masking strategy or additional parameters', 'review apply_mask to understand how boolean masks are applied to sequence tensors', 'test select_parameters to filter model parameters by regex pattern names', 'test select_parameters with exclude mode to filter out matching parameters', 'run select_parameters on an NLLB model to find encoder decoder attention layer norm biases', 'run get_nllb_model_hub to create and configure an NLLB dense 1b model', 'review select_parameters usage for including or excluding model parameters by regex']
```

Usage

```
{'test_select_parameters': 'test select_parameters to filter model parameters by regex pattern names', 'test_select_parameters_exclude': 'test select_parameters with exclude mode to filter out matching parameters', 'run_select_parameters_regex': 'run select_parameters on an NLLB model to find encoder decoder attention layer norm biases', 'run_get_nllb_model_hub': 'run get_nllb_model_hub to create and configure an NLLB dense 1b model', 'review_select_parameters_usage': 'review select_parameters usage for including or excluding model parameters by regex'}
```

