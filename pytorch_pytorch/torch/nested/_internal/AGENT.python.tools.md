# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/nested/_internal/nested_tensor.py

Prompts

```
['create a NestedTensor from values and offsets tensors with optional lengths for jagged layout', 'build a NestedTensor from a list of same-shape tensors by concatenating and computing offsets', 'build a NestedTensor from a flat tensor, start indices, and sequence lengths', 'build a flat buffer tensor from a NestedTensor by extracting its underlying values', 'test jagged_from_list validates that all input tensors share dtype and device', 'build jagged nested tensor operations that dispatch aten ops through the JAGGED_OPS_TABLE dispatcher', 'test nested tensor pointwise operations including unary and binary functions with ragged broadcasting', 'refactor nested tensor backward operations like linear_backward and native_dropout_backward for gradient computation', 'review nested tensor shape manipulation operations including split, chunk, unbind, squeeze, unsqueeze, and cat', 'summarize the nested tensor dispatch mechanism using register_jagged_func and lookup_jagged for aten op routing', 'run jagged_scaled_dot_product_attention on nested tensor query, key, and value with optional dropout and causal mask', 'test _validate_sdpa_input to verify query, key, and value are matching nested tensors with compatible dtypes and devices', 'build _sdpa_nested_preprocessing to transform nested tensor qkv inputs into contiguous buffers with cumulative sequence lengths', 'review _select_sdp_backend to select the optimal SDPA backend from flash attention, efficient attention, or math backends', 'summarize _cumulative_and_max_seq_len_nnz to calculate cumulative sequence lengths and maximum sequence length from a nested tensor']
```

Usage

```
{'create_NestedTensor': 'create a NestedTensor from values and offsets tensors with optional lengths for jagged layout', 'build_jagged_from_list': 'build a NestedTensor from a list of same-shape tensors by concatenating and computing offsets', 'build_jagged_from_tensor_and_lengths': 'build a NestedTensor from a flat tensor, start indices, and sequence lengths', 'build_buffer_from_jagged': 'build a flat buffer tensor from a NestedTensor by extracting its underlying values', 'test_jagged_from_list_validation': 'test jagged_from_list validates that all input tensors share dtype and device'}
```

## File: pytorch_pytorch/torch/nested/_internal/ops.py

Prompts

```
['create a NestedTensor from values and offsets tensors with optional lengths for jagged layout', 'build a NestedTensor from a list of same-shape tensors by concatenating and computing offsets', 'build a NestedTensor from a flat tensor, start indices, and sequence lengths', 'build a flat buffer tensor from a NestedTensor by extracting its underlying values', 'test jagged_from_list validates that all input tensors share dtype and device', 'build jagged nested tensor operations that dispatch aten ops through the JAGGED_OPS_TABLE dispatcher', 'test nested tensor pointwise operations including unary and binary functions with ragged broadcasting', 'refactor nested tensor backward operations like linear_backward and native_dropout_backward for gradient computation', 'review nested tensor shape manipulation operations including split, chunk, unbind, squeeze, unsqueeze, and cat', 'summarize the nested tensor dispatch mechanism using register_jagged_func and lookup_jagged for aten op routing', 'run jagged_scaled_dot_product_attention on nested tensor query, key, and value with optional dropout and causal mask', 'test _validate_sdpa_input to verify query, key, and value are matching nested tensors with compatible dtypes and devices', 'build _sdpa_nested_preprocessing to transform nested tensor qkv inputs into contiguous buffers with cumulative sequence lengths', 'review _select_sdp_backend to select the optimal SDPA backend from flash attention, efficient attention, or math backends', 'summarize _cumulative_and_max_seq_len_nnz to calculate cumulative sequence lengths and maximum sequence length from a nested tensor']
```

Usage

```
{'build_jagged_nested_tensor_ops': 'build jagged nested tensor operations that dispatch aten ops through the JAGGED_OPS_TABLE dispatcher', 'test_nested_tensor_pointwise_ops': 'test nested tensor pointwise operations including unary and binary functions with ragged broadcasting', 'refactor_nested_tensor_backward_ops': 'refactor nested tensor backward operations like linear_backward and native_dropout_backward for gradient computation', 'review_nested_tensor_shape_ops': 'review nested tensor shape manipulation operations including split, chunk, unbind, squeeze, unsqueeze, and cat', 'summarize_nested_tensor_dispatch': 'summarize the nested tensor dispatch mechanism using register_jagged_func and lookup_jagged for aten op routing'}
```

## File: pytorch_pytorch/torch/nested/_internal/sdpa.py

Prompts

```
['create a NestedTensor from values and offsets tensors with optional lengths for jagged layout', 'build a NestedTensor from a list of same-shape tensors by concatenating and computing offsets', 'build a NestedTensor from a flat tensor, start indices, and sequence lengths', 'build a flat buffer tensor from a NestedTensor by extracting its underlying values', 'test jagged_from_list validates that all input tensors share dtype and device', 'build jagged nested tensor operations that dispatch aten ops through the JAGGED_OPS_TABLE dispatcher', 'test nested tensor pointwise operations including unary and binary functions with ragged broadcasting', 'refactor nested tensor backward operations like linear_backward and native_dropout_backward for gradient computation', 'review nested tensor shape manipulation operations including split, chunk, unbind, squeeze, unsqueeze, and cat', 'summarize the nested tensor dispatch mechanism using register_jagged_func and lookup_jagged for aten op routing', 'run jagged_scaled_dot_product_attention on nested tensor query, key, and value with optional dropout and causal mask', 'test _validate_sdpa_input to verify query, key, and value are matching nested tensors with compatible dtypes and devices', 'build _sdpa_nested_preprocessing to transform nested tensor qkv inputs into contiguous buffers with cumulative sequence lengths', 'review _select_sdp_backend to select the optimal SDPA backend from flash attention, efficient attention, or math backends', 'summarize _cumulative_and_max_seq_len_nnz to calculate cumulative sequence lengths and maximum sequence length from a nested tensor']
```

Usage

```
{'run_jagged_scaled_dot_product_attention': 'run jagged_scaled_dot_product_attention on nested tensor query, key, and value with optional dropout and causal mask', 'test_validate_sdpa_input': 'test _validate_sdpa_input to verify query, key, and value are matching nested tensors with compatible dtypes and devices', 'build_sdpa_nested_preprocessing': 'build _sdpa_nested_preprocessing to transform nested tensor qkv inputs into contiguous buffers with cumulative sequence lengths', 'review_select_sdp_backend': 'review _select_sdp_backend to select the optimal SDPA backend from flash attention, efficient attention, or math backends', 'summarize_cumulative_and_max_seq_len_nnz': 'summarize _cumulative_and_max_seq_len_nnz to calculate cumulative sequence lengths and maximum sequence length from a nested tensor'}
```

