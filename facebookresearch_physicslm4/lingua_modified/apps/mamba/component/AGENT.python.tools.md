# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/mamba/component/causal_conv1d_compilable.py

Prompts

```
['run the causal_conv1d_fwd custom op to perform a forward causal convolution on CUDA tensors', 'run the causal_conv1d_bwd custom op to compute gradients for the causal convolution backward pass', 'run the causal_conv1d_fn wrapper to apply causal 1D convolution with optional silu or swish activation', 'run the causal_conv1d_update function to update convolution state using a circular buffer for incremental decoding', 'test the causal_conv1d_fn with torch.compile to verify compiled forward and backward pass correctness', 'run the mamba chunk scan combined SSM operation on CUDA tensors with configurable chunk size', 'compile the mamba chunk scan combined function with torch.compile for optimized CUDA execution', 'register the ssm_chunk_scan_combined_fwd custom op with torch.library for Mamba SSM forward pass', 'register the ssm_chunk_scan_combined_bwd custom op with torch.library for Mamba SSM backward pass', 'register the autograd bridge function linking forward and backward passes for gradient computation']
```

Usage

```
{'run_causal_conv1d_fwd': 'run the causal_conv1d_fwd custom op to perform a forward causal convolution on CUDA tensors', 'run_causal_conv1d_bwd': 'run the causal_conv1d_bwd custom op to compute gradients for the causal convolution backward pass', 'run_causal_conv1d_fn': 'run the causal_conv1d_fn wrapper to apply causal 1D convolution with optional silu or swish activation', 'run_causal_conv1d_update': 'run the causal_conv1d_update function to update convolution state using a circular buffer for incremental decoding', 'test_causal_conv1d_compiled': 'test the causal_conv1d_fn with torch.compile to verify compiled forward and backward pass correctness'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/mamba/component/ssm_compilable.py

Prompts

```
['run the causal_conv1d_fwd custom op to perform a forward causal convolution on CUDA tensors', 'run the causal_conv1d_bwd custom op to compute gradients for the causal convolution backward pass', 'run the causal_conv1d_fn wrapper to apply causal 1D convolution with optional silu or swish activation', 'run the causal_conv1d_update function to update convolution state using a circular buffer for incremental decoding', 'test the causal_conv1d_fn with torch.compile to verify compiled forward and backward pass correctness', 'run the mamba chunk scan combined SSM operation on CUDA tensors with configurable chunk size', 'compile the mamba chunk scan combined function with torch.compile for optimized CUDA execution', 'register the ssm_chunk_scan_combined_fwd custom op with torch.library for Mamba SSM forward pass', 'register the ssm_chunk_scan_combined_bwd custom op with torch.library for Mamba SSM backward pass', 'register the autograd bridge function linking forward and backward passes for gradient computation']
```

Usage

```
{'run_mamba_chunk_scan_combined': 'run the mamba chunk scan combined SSM operation on CUDA tensors with configurable chunk size', 'compile_mamba_chunk_scan': 'compile the mamba chunk scan combined function with torch.compile for optimized CUDA execution', 'register_custom_op_fwd': 'register the ssm_chunk_scan_combined_fwd custom op with torch.library for Mamba SSM forward pass', 'register_custom_op_bwd': 'register the ssm_chunk_scan_combined_bwd custom op with torch.library for Mamba SSM backward pass', 'setup_autograd_bridge': 'register the autograd bridge function linking forward and backward passes for gradient computation'}
```

