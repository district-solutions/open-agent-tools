# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/component/compilable_scan.py

Prompts

```
['build a CUDA warp scan operation using gates and tokens tensors for RNN sequence processing', 'test the scan_fwd custom op with contiguous gates and tokens tensors on CUDA device', 'test the scan_bwd backward pass returning gradients for gates and tokens tensors', 'review the scan autograd registration that bridges forward and backward passes via context', 'refactor the scan wrapper function to support additional reverse sequence processing options', 'run causal conv1d in parallel mode with silu activation on input tensor and conv weights', 'run causal conv1d in sequential mode using conv state cache for single step updates', 'run parallel scan operation on tensors a and b using accelerated scan implementation', 'run sequential scan step on hidden states using the linear recurrence formula a times states plus b', 'review the function that resets hidden state at sequence boundaries to prevent cross sequence carryover']
```

Usage

```
{'build_scan_operation': 'build a CUDA warp scan operation using gates and tokens tensors for RNN sequence processing', 'test_scan_fwd': 'test the scan_fwd custom op with contiguous gates and tokens tensors on CUDA device', 'test_scan_bwd': 'test the scan_bwd backward pass returning gradients for gates and tokens tensors', 'review_scan_autograd': 'review the scan autograd registration that bridges forward and backward passes via context', 'refactor_scan_wrapper': 'refactor the scan wrapper function to support additional reverse sequence processing options'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/component/rnn_common.py

Prompts

```
['build a CUDA warp scan operation using gates and tokens tensors for RNN sequence processing', 'test the scan_fwd custom op with contiguous gates and tokens tensors on CUDA device', 'test the scan_bwd backward pass returning gradients for gates and tokens tensors', 'review the scan autograd registration that bridges forward and backward passes via context', 'refactor the scan wrapper function to support additional reverse sequence processing options', 'run causal conv1d in parallel mode with silu activation on input tensor and conv weights', 'run causal conv1d in sequential mode using conv state cache for single step updates', 'run parallel scan operation on tensors a and b using accelerated scan implementation', 'run sequential scan step on hidden states using the linear recurrence formula a times states plus b', 'review the function that resets hidden state at sequence boundaries to prevent cross sequence carryover']
```

Usage

```
{'run_conv1d_parallel': 'run causal conv1d in parallel mode with silu activation on input tensor and conv weights', 'run_conv1d_sequential': 'run causal conv1d in sequential mode using conv state cache for single step updates', 'run_scan_parallel': 'run parallel scan operation on tensors a and b using accelerated scan implementation', 'run_scan_sequential': 'run sequential scan step on hidden states using the linear recurrence formula a times states plus b', 'review_prepare_for_cache': 'review the function that resets hidden state at sequence boundaries to prevent cross sequence carryover'}
```

