# Agent Python Tools

- repo: facebookresearch/memory
- repo_uri: https://github.com/facebookresearch/memory

## File: facebookresearch_memory/apps/mamba/component/causal_conv1d_compilable.py

Prompts

```
['run the causal_conv1d_fn function to perform a causal 1D convolution forward pass with optional silu activation', 'compile the causal_conv1d_fn function using torch.compile for optimized CUDA kernel execution', 'test the causal_conv1d backward pass by calling backward on the output and checking gradients', 'run the causal_conv1d_update function to perform incremental convolution state updates with circular buffer support', 'review the causal_conv1d_fwd and causal_conv1d_bwd custom ops registered with torch.library for torch.compile compatibility', 'run the mamba chunk scan combined SSM operation on CUDA tensors with optional z and dt_bias', 'run the torch.compile wrapped mamba chunk scan combined operation for optimized CUDA performance', 'test the custom op ssm_chunk_scan_combined_fwd forward pass with batched input tensors and chunk size', 'test the custom op ssm_chunk_scan_combined_bwd backward pass to compute gradients for all parameters', 'review the ssm_compilable module that wraps mamba SSM chunk scan for torch.compile compatibility']
```

Usage

```
{'run_causal_conv1d_forward': 'run the causal_conv1d_fn function to perform a causal 1D convolution forward pass with optional silu activation', 'compile_causal_conv1d': 'compile the causal_conv1d_fn function using torch.compile for optimized CUDA kernel execution', 'test_causal_conv1d_backward': 'test the causal_conv1d backward pass by calling backward on the output and checking gradients', 'run_causal_conv1d_update': 'run the causal_conv1d_update function to perform incremental convolution state updates with circular buffer support', 'review_causal_conv1d_custom_op': 'review the causal_conv1d_fwd and causal_conv1d_bwd custom ops registered with torch.library for torch.compile compatibility'}
```

## File: facebookresearch_memory/apps/mamba/component/ssm_compilable.py

Prompts

```
['run the causal_conv1d_fn function to perform a causal 1D convolution forward pass with optional silu activation', 'compile the causal_conv1d_fn function using torch.compile for optimized CUDA kernel execution', 'test the causal_conv1d backward pass by calling backward on the output and checking gradients', 'run the causal_conv1d_update function to perform incremental convolution state updates with circular buffer support', 'review the causal_conv1d_fwd and causal_conv1d_bwd custom ops registered with torch.library for torch.compile compatibility', 'run the mamba chunk scan combined SSM operation on CUDA tensors with optional z and dt_bias', 'run the torch.compile wrapped mamba chunk scan combined operation for optimized CUDA performance', 'test the custom op ssm_chunk_scan_combined_fwd forward pass with batched input tensors and chunk size', 'test the custom op ssm_chunk_scan_combined_bwd backward pass to compute gradients for all parameters', 'review the ssm_compilable module that wraps mamba SSM chunk scan for torch.compile compatibility']
```

Usage

```
{'run_mamba_chunk_scan_combined': 'run the mamba chunk scan combined SSM operation on CUDA tensors with optional z and dt_bias', 'run_compiled_mamba_chunk_scan': 'run the torch.compile wrapped mamba chunk scan combined operation for optimized CUDA performance', 'test_ssm_chunk_scan_fwd': 'test the custom op ssm_chunk_scan_combined_fwd forward pass with batched input tensors and chunk size', 'test_ssm_chunk_scan_bwd': 'test the custom op ssm_chunk_scan_combined_bwd backward pass to compute gradients for all parameters', 'review_mamba_compilable_wrapper': 'review the ssm_compilable module that wraps mamba SSM chunk scan for torch.compile compatibility'}
```

