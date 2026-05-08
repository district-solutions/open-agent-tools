# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/mamba/component/causal_conv1d_compilable.py

Prompts

```
['run causal_conv1d_fn to perform a causal 1D convolution on CUDA tensors with optional silu activation', 'run causal_conv1d_update to incrementally update conv state for autoregressive decoding with circular buffer support', 'compile causal_conv1d_fn with torch.compile for optimized causal 1D convolution forward and backward passes', 'review the causal_conv1d_fwd custom op that wraps the CUDA kernel for causal 1D convolution forward pass', 'review the causal_conv1d_bwd custom op that computes gradients for x, weight, and bias tensors', 'run the mamba chunk scan combined SSM forward pass on CUDA tensors with optional z and dt_bias', 'run the torch.compile wrapped mamba chunk scan combined forward and backward passes for performance', 'test the custom op ssm chunk scan combined forward function with cu_seqlens for variable length sequences', 'test the custom op ssm chunk scan combined backward function computing gradients for all SSM parameters', 'review the torch.library custom op registration and autograd bridge for mamba SSM chunk scan operations']
```

Usage

```
{'run_causal_conv1d_fn': 'run causal_conv1d_fn to perform a causal 1D convolution on CUDA tensors with optional silu activation', 'run_causal_conv1d_update': 'run causal_conv1d_update to incrementally update conv state for autoregressive decoding with circular buffer support', 'compile_causal_conv1d_fn': 'compile causal_conv1d_fn with torch.compile for optimized causal 1D convolution forward and backward passes', 'review_causal_conv1d_fwd': 'review the causal_conv1d_fwd custom op that wraps the CUDA kernel for causal 1D convolution forward pass', 'review_causal_conv1d_bwd': 'review the causal_conv1d_bwd custom op that computes gradients for x, weight, and bias tensors'}
```

## File: facebookresearch_lingua/apps/mamba/component/ssm_compilable.py

Prompts

```
['run causal_conv1d_fn to perform a causal 1D convolution on CUDA tensors with optional silu activation', 'run causal_conv1d_update to incrementally update conv state for autoregressive decoding with circular buffer support', 'compile causal_conv1d_fn with torch.compile for optimized causal 1D convolution forward and backward passes', 'review the causal_conv1d_fwd custom op that wraps the CUDA kernel for causal 1D convolution forward pass', 'review the causal_conv1d_bwd custom op that computes gradients for x, weight, and bias tensors', 'run the mamba chunk scan combined SSM forward pass on CUDA tensors with optional z and dt_bias', 'run the torch.compile wrapped mamba chunk scan combined forward and backward passes for performance', 'test the custom op ssm chunk scan combined forward function with cu_seqlens for variable length sequences', 'test the custom op ssm chunk scan combined backward function computing gradients for all SSM parameters', 'review the torch.library custom op registration and autograd bridge for mamba SSM chunk scan operations']
```

Usage

```
{'run_mamba_chunk_scan_combined': 'run the mamba chunk scan combined SSM forward pass on CUDA tensors with optional z and dt_bias', 'run_compiled_mamba_chunk_scan': 'run the torch.compile wrapped mamba chunk scan combined forward and backward passes for performance', 'test_ssm_chunk_scan_fwd': 'test the custom op ssm chunk scan combined forward function with cu_seqlens for variable length sequences', 'test_ssm_chunk_scan_bwd': 'test the custom op ssm chunk scan combined backward function computing gradients for all SSM parameters', 'review_custom_op_registration': 'review the torch.library custom op registration and autograd bridge for mamba SSM chunk scan operations'}
```

