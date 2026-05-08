# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/nn/utils/grad.py

Prompts

```
['normalize gradients of a module by the total number of targets across all processes in a gang', 'scale gradients of a module by a given float value or tensor multiplier', 'scale the gradient of a tensor during backpropagation to control learning rate for a model part', 'clip the gradient norms of a module to a maximum norm value with support for FSDP and DTensor', 'sanity check the total gradient norm across all processes and raise an error if inconsistent', 'apply a boolean mask to PyTorch sequences replacing unmasked elements with a fill value', 'compute a random row mask tensor with configurable span length and maximum mask probability', 'implement the RowMaskFactory protocol to create custom random row mask generation logic', 'review the compute_row_mask function to understand how mask spans are computed and normalized across rows', 'test the apply_mask function with a batch of sequences and a boolean mask tensor', 'reset the parameters and buffers of a PyTorch module and its descendants', 'reset the non-persistent buffers of a PyTorch module and its descendant modules', 'run a visitor function on a PyTorch module and optionally its descendant modules', 'move the parameters and buffers of a PyTorch module to a target device', 'broadcast a PyTorch module to all processes in a distributed gang', 'pad a list of variable length tensors to equal length using pad_seqs', 'pad sequences with a custom pad_value instead of the default zero', 'pad sequences rounding up the sequence dimension to a specified multiple', 'pad sequences and move the result to a specific device non blocking', 'pad sequences and get the BatchLayout describing sequence lengths and shape']
```

Usage

```
{'normalize_grads': 'normalize gradients of a module by the total number of targets across all processes in a gang', 'scale_grads': 'scale gradients of a module by a given float value or tensor multiplier', 'scale_grad': 'scale the gradient of a tensor during backpropagation to control learning rate for a model part', 'clip_grad_norm': 'clip the gradient norms of a module to a maximum norm value with support for FSDP and DTensor', 'check_grad_norms': 'sanity check the total gradient norm across all processes and raise an error if inconsistent'}
```

## File: facebookresearch_fairseq2/src/fairseq2/nn/utils/mask.py

Prompts

```
['normalize gradients of a module by the total number of targets across all processes in a gang', 'scale gradients of a module by a given float value or tensor multiplier', 'scale the gradient of a tensor during backpropagation to control learning rate for a model part', 'clip the gradient norms of a module to a maximum norm value with support for FSDP and DTensor', 'sanity check the total gradient norm across all processes and raise an error if inconsistent', 'apply a boolean mask to PyTorch sequences replacing unmasked elements with a fill value', 'compute a random row mask tensor with configurable span length and maximum mask probability', 'implement the RowMaskFactory protocol to create custom random row mask generation logic', 'review the compute_row_mask function to understand how mask spans are computed and normalized across rows', 'test the apply_mask function with a batch of sequences and a boolean mask tensor', 'reset the parameters and buffers of a PyTorch module and its descendants', 'reset the non-persistent buffers of a PyTorch module and its descendant modules', 'run a visitor function on a PyTorch module and optionally its descendant modules', 'move the parameters and buffers of a PyTorch module to a target device', 'broadcast a PyTorch module to all processes in a distributed gang', 'pad a list of variable length tensors to equal length using pad_seqs', 'pad sequences with a custom pad_value instead of the default zero', 'pad sequences rounding up the sequence dimension to a specified multiple', 'pad sequences and move the result to a specific device non blocking', 'pad sequences and get the BatchLayout describing sequence lengths and shape']
```

Usage

```
{'apply_mask_to_sequences': 'apply a boolean mask to PyTorch sequences replacing unmasked elements with a fill value', 'compute_row_mask_for_batch': 'compute a random row mask tensor with configurable span length and maximum mask probability', 'implement_RowMaskFactory_protocol': 'implement the RowMaskFactory protocol to create custom random row mask generation logic', 'review_compute_row_mask': 'review the compute_row_mask function to understand how mask spans are computed and normalized across rows', 'test_apply_mask_function': 'test the apply_mask function with a batch of sequences and a boolean mask tensor'}
```

## File: facebookresearch_fairseq2/src/fairseq2/nn/utils/module.py

Prompts

```
['normalize gradients of a module by the total number of targets across all processes in a gang', 'scale gradients of a module by a given float value or tensor multiplier', 'scale the gradient of a tensor during backpropagation to control learning rate for a model part', 'clip the gradient norms of a module to a maximum norm value with support for FSDP and DTensor', 'sanity check the total gradient norm across all processes and raise an error if inconsistent', 'apply a boolean mask to PyTorch sequences replacing unmasked elements with a fill value', 'compute a random row mask tensor with configurable span length and maximum mask probability', 'implement the RowMaskFactory protocol to create custom random row mask generation logic', 'review the compute_row_mask function to understand how mask spans are computed and normalized across rows', 'test the apply_mask function with a batch of sequences and a boolean mask tensor', 'reset the parameters and buffers of a PyTorch module and its descendants', 'reset the non-persistent buffers of a PyTorch module and its descendant modules', 'run a visitor function on a PyTorch module and optionally its descendant modules', 'move the parameters and buffers of a PyTorch module to a target device', 'broadcast a PyTorch module to all processes in a distributed gang', 'pad a list of variable length tensors to equal length using pad_seqs', 'pad sequences with a custom pad_value instead of the default zero', 'pad sequences rounding up the sequence dimension to a specified multiple', 'pad sequences and move the result to a specific device non blocking', 'pad sequences and get the BatchLayout describing sequence lengths and shape']
```

Usage

```
{'reset_parameters_module': 'reset the parameters and buffers of a PyTorch module and its descendants', 'reset_non_persistent_buffers_module': 'reset the non-persistent buffers of a PyTorch module and its descendant modules', 'visit_module_with_visitor': 'run a visitor function on a PyTorch module and optionally its descendant modules', 'to_device_module': 'move the parameters and buffers of a PyTorch module to a target device', 'broadcast_module_gang': 'broadcast a PyTorch module to all processes in a distributed gang'}
```

## File: facebookresearch_fairseq2/src/fairseq2/nn/utils/padding.py

Prompts

```
['normalize gradients of a module by the total number of targets across all processes in a gang', 'scale gradients of a module by a given float value or tensor multiplier', 'scale the gradient of a tensor during backpropagation to control learning rate for a model part', 'clip the gradient norms of a module to a maximum norm value with support for FSDP and DTensor', 'sanity check the total gradient norm across all processes and raise an error if inconsistent', 'apply a boolean mask to PyTorch sequences replacing unmasked elements with a fill value', 'compute a random row mask tensor with configurable span length and maximum mask probability', 'implement the RowMaskFactory protocol to create custom random row mask generation logic', 'review the compute_row_mask function to understand how mask spans are computed and normalized across rows', 'test the apply_mask function with a batch of sequences and a boolean mask tensor', 'reset the parameters and buffers of a PyTorch module and its descendants', 'reset the non-persistent buffers of a PyTorch module and its descendant modules', 'run a visitor function on a PyTorch module and optionally its descendant modules', 'move the parameters and buffers of a PyTorch module to a target device', 'broadcast a PyTorch module to all processes in a distributed gang', 'pad a list of variable length tensors to equal length using pad_seqs', 'pad sequences with a custom pad_value instead of the default zero', 'pad sequences rounding up the sequence dimension to a specified multiple', 'pad sequences and move the result to a specific device non blocking', 'pad sequences and get the BatchLayout describing sequence lengths and shape']
```

Usage

```
{'pad_seqs_basic': 'pad a list of variable length tensors to equal length using pad_seqs', 'pad_seqs_custom_value': 'pad sequences with a custom pad_value instead of the default zero', 'pad_seqs_multiple': 'pad sequences rounding up the sequence dimension to a specified multiple', 'pad_seqs_device': 'pad sequences and move the result to a specific device non blocking', 'pad_seqs_layout': 'pad sequences and get the BatchLayout describing sequence lengths and shape'}
```

