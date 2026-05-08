# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/fastRNN/component/compilable_scan.py

Prompts

```
['run the scan function with gates and tokens tensors to perform a warp scan forward pass on CUDA', 'run the scan function with reverse set to true to perform a backward warp scan on CUDA tensors', 'test the scan_fwd custom op that performs warp scan forward on batched gates and tokens tensors', 'test the scan_bwd custom op that computes gradients for gates and tokens during warp scan backward', 'review the scan autograd registration that wires scan_fwd with scan_bwd_bridge for gradient computation', 'run a causal conv1d operation in parallel mode with silu activation on input tensor x', 'run a causal conv1d operation in sequential mode using a cache tensor for state updates', 'run a parallel scan operation on tensors a and b using the accelerated scan implementation', 'run a sequential scan step on tensors a and b using cache for hidden state updates', 'run the prepare for cache function to reset hidden states between sequences in a batch']
```

Usage

```
{'run_scan_forward': 'run the scan function with gates and tokens tensors to perform a warp scan forward pass on CUDA', 'run_scan_reverse': 'run the scan function with reverse set to true to perform a backward warp scan on CUDA tensors', 'test_scan_fwd_custom_op': 'test the scan_fwd custom op that performs warp scan forward on batched gates and tokens tensors', 'test_scan_bwd_custom_op': 'test the scan_bwd custom op that computes gradients for gates and tokens during warp scan backward', 'review_scan_autograd': 'review the scan autograd registration that wires scan_fwd with scan_bwd_bridge for gradient computation'}
```

## File: facebookresearch_lingua/apps/fastRNN/component/rnn_common.py

Prompts

```
['run the scan function with gates and tokens tensors to perform a warp scan forward pass on CUDA', 'run the scan function with reverse set to true to perform a backward warp scan on CUDA tensors', 'test the scan_fwd custom op that performs warp scan forward on batched gates and tokens tensors', 'test the scan_bwd custom op that computes gradients for gates and tokens during warp scan backward', 'review the scan autograd registration that wires scan_fwd with scan_bwd_bridge for gradient computation', 'run a causal conv1d operation in parallel mode with silu activation on input tensor x', 'run a causal conv1d operation in sequential mode using a cache tensor for state updates', 'run a parallel scan operation on tensors a and b using the accelerated scan implementation', 'run a sequential scan step on tensors a and b using cache for hidden state updates', 'run the prepare for cache function to reset hidden states between sequences in a batch']
```

Usage

```
{'run_conv1d_parallel': 'run a causal conv1d operation in parallel mode with silu activation on input tensor x', 'run_conv1d_sequential': 'run a causal conv1d operation in sequential mode using a cache tensor for state updates', 'run_scan_parallel': 'run a parallel scan operation on tensors a and b using the accelerated scan implementation', 'run_scan_sequential': 'run a sequential scan step on tensors a and b using cache for hidden state updates', 'run_prepare_for_cache': 'run the prepare for cache function to reset hidden states between sequences in a batch'}
```

