# Agent Python Tools

- repo: facebookresearch/memory
- repo_uri: https://github.com/facebookresearch/memory

## File: facebookresearch_memory/apps/fastRNN/component/compilable_scan.py

Prompts

```
['run the scan function to perform a warp scan over gates and tokens tensors on CUDA', 'run the scan function with reverse=True to perform a reverse warp scan over sequence data', 'test the scan_fwd custom op that computes forward warp scan on contiguous CUDA tensors', 'test the scan_bwd custom op that computes gradients for gates and tokens during backprop', 'review the scan autograd registration that wires scan_fwd with scan_bwd_bridge for gradient computation', 'run causal conv1d on a tensor with silu activation in parallel mode', 'run causal conv1d on a tensor using sequential mode with a cache state', 'run a parallel scan operation on tensors a and b with cu_seqlens', 'run a sequential scan step using cached states and tensors a and b', 'review the _prepare_for_cache function that resets hidden state between sequences in a batch']
```

Usage

```
{'run_scan_forward': 'run the scan function to perform a warp scan over gates and tokens tensors on CUDA', 'run_scan_reverse': 'run the scan function with reverse=True to perform a reverse warp scan over sequence data', 'test_scan_fwd_custom_op': 'test the scan_fwd custom op that computes forward warp scan on contiguous CUDA tensors', 'test_scan_bwd_custom_op': 'test the scan_bwd custom op that computes gradients for gates and tokens during backprop', 'review_scan_autograd': 'review the scan autograd registration that wires scan_fwd with scan_bwd_bridge for gradient computation'}
```

## File: facebookresearch_memory/apps/fastRNN/component/rnn_common.py

Prompts

```
['run the scan function to perform a warp scan over gates and tokens tensors on CUDA', 'run the scan function with reverse=True to perform a reverse warp scan over sequence data', 'test the scan_fwd custom op that computes forward warp scan on contiguous CUDA tensors', 'test the scan_bwd custom op that computes gradients for gates and tokens during backprop', 'review the scan autograd registration that wires scan_fwd with scan_bwd_bridge for gradient computation', 'run causal conv1d on a tensor with silu activation in parallel mode', 'run causal conv1d on a tensor using sequential mode with a cache state', 'run a parallel scan operation on tensors a and b with cu_seqlens', 'run a sequential scan step using cached states and tensors a and b', 'review the _prepare_for_cache function that resets hidden state between sequences in a batch']
```

Usage

```
{'run_conv1d_parallel': 'run causal conv1d on a tensor with silu activation in parallel mode', 'run_conv1d_sequential': 'run causal conv1d on a tensor using sequential mode with a cache state', 'run_scan_parallel': 'run a parallel scan operation on tensors a and b with cu_seqlens', 'run_scan_sequential': 'run a sequential scan step using cached states and tensors a and b', 'review_prepare_for_cache': 'review the _prepare_for_cache function that resets hidden state between sequences in a batch'}
```

